---
title: "Canary Deployment"
date: 2018-04-16T09:22:55-04:00
type: page
draft: false
---
## Activity name
Canary deployment

## Participants
- Platform Architect
- Customer's Platform Team

## Guidance
One of the requirements prior to inception of a Platform Dojo is a so-called "canary deployment" of PCF.  This is done to ensure that the infrastructure is ready for PCF installation prior to the delivery team arriving at the customer.

The canary deployment involves manually deploying PCF Ops Manager and PAS to 1 of the customer's environments, and deploying an application to PAS.  This will verify that the infrastructure prerequisites have been met.  Once this is done PCF can be deleted.

## Outcome
A successful installation of PCF Ops Manager and PAS, which validates the environment is ready for executing the Platform Dojo.

---
< [Previous]({{< ref "candidate-app.md" >}}) | [Next]({{< ref "tiles.md" >}}) >

