# Salesforce Configuration Summary

## Custom Object
Support Ticket Intelligence (`Support_Ticket_Intelligence__c`)

## Flow
`Support_Ticket_Intelligence` – Auto-Launched Flow

### Flow sequence
Start → Get Account → Store Account Id → Get Ticket → Store Ticket Id → Analyze Description → Set Priority → Is High Priority → Create Urgent Task (High path) → Set Assigned Agent → Set Final Message → End

### Priority conditions
High: `urgent`, `not working`, `failure`
Medium: `issue`, `slow`, `delay`
Low: none of the above

## Agentforce
Agent: `Agentforce (Default)`
Subagent: `Support Ticket Priority Analysis`
Agent Action: `Support_Ticket_Intelligence`

## Agent Action Input
`varAccountName`

## Agent Action Outputs
`varAccountId`, `varActionMessage`, `varAssignedTo`, `varPriorityLevel`, `varTicketId`
