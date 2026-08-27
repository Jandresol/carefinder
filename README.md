# CareFinder+: Intelligent Referral Coordination Platform

A high-fidelity prototype for an AI-assisted case-management and referral platform that helps hospital discharge planners and case managers identify appropriate providers and place patients faster—without replacing human judgment.

## Vision

CareFinder+ reduces administrative burden in patient placement by **preparing referrals before a coordinator begins reviewing them**. The platform handles clinical summary preparation, information verification, facility recommendations, and referral packet assembly—allowing care coordinators to focus on clinical judgment and relationship building rather than paperwork.

## Problem Space

Discharge planning and patient placement are critical yet incredibly time-consuming. Case managers and discharge coordinators must:
- Manually review patient clinical records
- Search through networks of potential facilities
- Verify bed availability, insurance coverage, and patient compatibility
- Assemble multi-page referral packets
- Manage back-and-forth communication

This process delays patient placement, increases readmission rates, and burns out care coordinators.

## Solution

CareFinder+ acts as an **intelligent preparation assistant** that:
- **Summarizes** patient clinical profiles automatically
- **Verifies** insurance coverage and patient eligibility
- **Recommends** facilities with explainable reasoning
- **Assembles** complete referral packets ready for review
- **Tracks** referral status and outcomes in real-time

## Prototype Features

### 🏥 Dashboard
- **Today's Priorities**: Pending placements ranked by urgency
- **Warm, healthcare-focused UI**: Designed for busy clinical environments
- **Guided Product Tour**: Onboarding for first-time users

### 👤 Patient Workspace
- Clinical summary with key medical facts
- Insurance and coverage verification
- Patient preferences and requirements
- Relevant comorbidities and special considerations

### 🔍 Placement Analysis
- Multi-criteria facility matching
- Bed availability real-time status
- Geographic proximity and transportation options
- Cost and insurance compatibility analysis

### 💡 Explainable Facility Recommendations
- Top-ranked facilities with reasoning
- Why each facility matches patient needs
- Risk factors and considerations
- Comparison tables

### 📋 Referral Packet Review
- Auto-generated referral documents
- Pre-populated forms and required info
- Document assembly workflow
- Approval and send capability

### 📊 Referral Timeline & Outcomes
- Track referral status from submission to placement
- Outcome recording (accepted, bed occupied date, etc.)
- Performance analytics and insights
- Historical referral patterns

### 🏢 Facility Network
- View partner facilities, beds, and specialties
- Capacity and current census
- Reputation and outcome tracking

## Technical Stack

**Intentionally Simple & Deployable:**
- Single `index.html` file
- HTML, CSS, vanilla JavaScript
- No build step or dependencies
- No backend required
- Deployable via GitHub Pages

**Why this approach?**
- Rapid iteration with stakeholders
- Easy testing in clinical environments
- Simple deployment across hospital systems
- Natural friction points guide next-phase architecture

