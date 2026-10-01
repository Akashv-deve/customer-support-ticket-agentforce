# Customer Support Ticket Priority Prediction and Automated Assignment System Using Agentforce

## Overview
Salesforce-based customer support automation using Agentforce and an Auto-Launched Flow to retrieve the latest ticket, classify priority, create an urgent task for high-priority cases, assign the support level, and return the result conversationally.

## Salesforce Implementation
- Salesforce Platform
- Support Ticket Intelligence custom object: `Support_Ticket_Intelligence__c`
- Auto-Launched Flow: `Support_Ticket_Intelligence`
- Agentforce subagent: `Support Ticket Priority Analysis`
- Flow-based Agentforce action: `Support_Ticket_Intelligence`

## Demo Scenario
Account: ABC Technologies
Ticket: TKT-0002
Description: Urgent, the application is not working

Expected outcome demonstrated in the project:
- Priority: High
- Assigned Agent: Senior Support Agent
- Urgent Ticket Handling task created
- Account ID and Ticket ID returned to Agentforce

## Repository Contents
- `phase_wise_templates/` – project-specific phase-wise template/document
- `docs/` – project document and Salesforce configuration notes
- `screenshots/` – Salesforce implementation evidence
- `demo/` – final project demonstration video

This repository contains Salesforce configuration/documentation rather than application source code because the implemented project is built in Salesforce using declarative configuration, Flow, and Agentforce.
