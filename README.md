# Healthresponse-incident-tracking

# Real-Time Incident Tracking & Outcome Reporting using Power Automate, Google Sheets, and Looker Studio

Automated, real-time incident tracking and outcome reporting system built for an emergency response provider, replacing fragmented manual logging with live, decision-ready dashboards.

## 🔗 Live Dashboard
[View interactive Looker Studio dashboard](https://datastudio.google.com/s/nnZGgC9Ttws)

📄 [Download full dashboard report (PDF)](https://acrobat.adobe.com/id/urn:aaid:sc:EU:da66a94c-8739-496f-bb64-5406d8ca2f0c)

---

##  Overview

HealthResponse Ltd is a UK-based emergency medical response provider handling 3,000+ incidents, offering emergency medical transport, patient monitoring, and incident management to hospitals, local government health services, and private health organisations. This project replaces their manual, disconnected incident-logging process with an automated, real-time reporting system.

##  Business Problem

HealthResponse tracked emergency incidents through manual logging with no integration between dispatch, incident, and patient outcome data, resulting in:

- Delayed, post-incident reporting instead of real-time visibility
- Risk of inaccurate or incomplete incident logs
- No clear view of whether response speed matched actual patient risk
- Inability to spot operational trends until well after the fact

##  Objectives

- Automate incident logging to eliminate manual data entry
- Build real-time dashboards to track response times, patient outcomes, and resource allocation
- Improve data accuracy through automated validation and integration
- Surface actionable insights to support faster, better-informed operational decisions

##  Tech Stack

- **Microsoft Forms** — real-time incident data capture by dispatch teams
- **Power Automate** — automated data transfer from Forms into Google Sheets
- **Google Sheets** — central data store for incident, patient, and outcome records
- **Looker Studio** — live, interactive dashboard reporting layer

##  Approach

1. **Data Collection** — Incident data captured in real time via Microsoft Forms
2. **Data Automation** — Power Automate instantly transfers submissions into Google Sheets
3. **Data Integration** — Google Sheets serves as the single source of truth for incident and patient records
4. **Real-Time Visualisation** — Looker Studio connects directly to Google Sheets, powering three live dashboards
5. **Analysis & Reporting** — Dashboards used to identify trends, response gaps, and resourcing needs

### Dashboards Built
- **Executive Overview & Response Performance**
- **Patient Outcome Insights & Geographic Analysis**
- **Operational Risk & Resource Efficiency**

##  Dataset

Key fields tracked include: incident reference, timestamps, incident type, priority level, location/city/region, patient age/gender, vulnerability and mental health history flags, initial patient status, dispatcher and response team, response mode, dispatch/arrival times, response time (minutes), intervention type, escalation flag, and final incident outcome.

##  Key Findings

**Response speed was inverted relative to urgency**
Critical incidents had the slowest average response time of any priority level, despite 607 Critical cases and a 36.43% escalation rate. Response time and outcome severity showed a visible upward pattern, reinforcing the link between delay and worse outcomes.

**The gap wasn't one weak team — it's systemic**
All six response teams performed within a similar range, pointing toward a dispatch or triage process issue rather than a training or staffing gap.

**Virtual Support was a compounding weak point**
The least-used response channel (15.9% of dispatches) was also the slowest of all four modes, despite likely being the primary channel for complex, mental-health-linked cases.

**Distress, not medical criticality, dominated patient conditions**
1,340 patients (the largest single category) were found Distressed at first contact — over 5x more than Unresponsive (242) — with De-escalation Support ranking among the top-3 interventions used.

**Most incidents required continued care beyond first contact**
Follow-Up Required and Hospital Referral together outweighed on-site resolution, with meaningful case volume concentrated in Bristol (211) and Nottingham (200).

##  Recommendations

- Re-align dispatch prioritisation so response speed matches actual urgency, not just incident category
- Expand and speed up Virtual Support capacity, particularly for mental-health-linked cases
- Increase de-escalation-trained response capacity in high-volume cities (Bristol, Nottingham)
- Plan staffing around follow-up and hospital referral load, not just first-response speed

##  Future Improvements

- Predictive escalation-risk scoring at intake
- Automated SLA-breach alerts for high-priority cases
- Deeper geographic resource-allocation modelling
- Live integration with CMMS-style systems for fully automated end-to-end tracking

##  Business Impact

This project demonstrates how automating incident data capture and building real-time dashboards can:

- Surface urgent operational gaps (like the response-speed inversion) that manual, delayed reporting would miss
- Support faster, evidence-based resourcing decisions
- Improve patient outcomes by aligning response capacity with actual risk and demand

##  Project Structure
Healthresponse-incident-tracking-dashboard/

│

├── README.md

└── Health_Response_Incident.pdf

##  Let's Connect

If you're working on similar problems or have feedback, feel free to connect or reach out.

**Nwafor Franklin**
📧 fhranklyndre@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/nwaforfranklin100)
🔗 [GitHub](https://github.com/fhranklyndre)

`#DataAnalytics` `#LookerStudio` `#PowerAutomate` `#HealthcareAnalytics` `#EmergencyResponse` `#BusinessIntelligence`



