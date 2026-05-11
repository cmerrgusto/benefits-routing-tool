# Benefits Services Routing Tool

An interactive decision tree that helps Engagement ICs quickly identify 
the correct ticket reason, team owner, and issue description template 
for benefits-related requests — without needing to reference multiple 
SOPs or tag ticket owners for guidance.

## What this tool does

Engagement ICs support customers with a wide range of benefits-related 
requests that need to be routed to the correct Benefits Services team 
in Salesforce. Incorrect ticket reasons, missing information, and 
misrouted tickets are among the most common causes of resolution delays.

This tool walks the IC through a series of guided questions based on 
the type of issue, whether it is group-level or member-level, the 
status of the related MOps case, and other key factors — and surfaces 
the correct ticket reason, ticket reason detail, owner, and a 
pre-filled issue description template ready to copy into Salesforce.

## Teams covered

- Escalations and Quality (EQ)
- Member Ops — New Hire Enrollment
- Member Ops — Termination
- Member Ops — Adjudication (QLE, TAdA)
- Member Ops — Continuation (COBRA)
- Member Ops — Group Terminations
- Member Ops — Updates
- Member Ops — BYB
- Benefits Transfers (BOR)
- Advising Fulfillment
- Benefits BYB
- Benefits Help (BenHelp Slack channel)

## How to use

Open `index.html` in any browser or visit the live URL. No login, 
no installation, and no external dependencies required. Multiple 
users can access it simultaneously.

## How to update

All routing logic, ticket templates, and field options live in the 
`index.html` file. To update a template, ticket reason, or routing 
path, open the file and locate the relevant result object in the 
JavaScript section. Each result is labeled with the ticket shortcut 
code (e.g. `;cien`, `;mien`, `;ern`) for easy reference.

## Maintained by

Benefits Services — Chere Merrick  
Last updated: May 2026
