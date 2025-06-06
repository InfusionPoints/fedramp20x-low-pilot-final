# Command Center on XBU40
InfusionPoints is pleased to submit our FedRAMP 20x Low Pilot package for Command Center on XBU40. This should be considered our formal submission and is based on our [prior draft submission](https://github.com/InfusionPoints/infpts_fedramp20x_draft).

Command Center is our cloud-native next-gen Governance, Risk, and Compliance (GRC) tool hosted in AWS GovCloud (US) that streamlines and orchestrates all aspects of FedRAMP and DoD ATOs including:

- Continuous Monitoring
- Audit Orchestration
- User Management
- Ticketing
- Document Management

## Solution Overview
Command Center is the interface for InfusionPoints' full-lifecycle managed hosting service XBU40 that provides for military grade security for hosting our customers' cloud environments and supported by our Cloud Operations and Security Operations teams. XBU40 was developed using opinionated, cloud-native security architectures that are audited annually for DoD Impact Level 4 on the FedRAMP Moderate baseline. We pioneered the concept of ATO acceleration and have assisted dozens of organizations in rapidly achieving and maintaining ATOs in FedRAMP and DoD. InfusionPoints is leaning into the FedRAMP 20x initiatve with AuditShield, our automated evidence collection capability to support continuous auditing and reporting on compliance status within Command Center. Command Center and AuditShield is also available in our XccelerATOr solution that we build and manage in a customers' enclave.

## AuditShield
AuditShield provides CSPs, 3PAOs, and Agency stakeholders alike with a reports view and gathers actionable insights for security and compliance status in real-time. InfusionPoints AuditShield provides CSPs with the ability to automate the evidence collection process for FedRAMP KSIs. Uniqely, AuditShield allows for live evidence views (We're doing it live!) using APIs and serverless calls and maps output artifacts to specific KSIs. The Command Center interface allows a 3PAO to attest to the validations by showing the exact commands used in each validation and the resulting output. In future releases, the 3PAO will be able to record their opinion on the outcome for each validation attestation and its sufficiency while the validation is free to run continuously. 

AuditShield provides details concerning what commands are run to gather KSI artifacts and provide stakeholders with the ability to track a full chain of custody of an artifact to their source within the environment. AuditShield will have capabilities to reflect evidence mapped to additional frameworks over time. 

## Submission Details
Our submission is in two parts, including this public view as well as a stakeholder-only view, currently shared with the FedRAMP PMO. This public view consists of:

| File | Description |
|----------|----------|
| [Audit Shield Human Readable (HTML)](https://html-preview.github.io/?url=https://github.com/InfusionPoints/fedramp20x-low-pilot-final/blob/master/auditshield/AuditShield_Dashboard.html)    |  Human Readable HTML KSI Report Exported from Command Center  |
| [Audit Shield Machine Readable (JSON)](ksi_report_redacted.json)    |  Machine Readable JSON KSI Report Exported from Command Center  |
| [Schema (JSON)](schema.json)    |  KSI Report Schema  |
| [3PAO KSI Methods Letter](InfusionPoints-FedRAMP_20x_KSIs-Methods-Letter-05232025.pdf)  | 3PAO Letter attestesting to our validation methods |

## 3PAO Review and Digital Signing
This package submission has been reviewed by Fortreum, the designated 3PAO for this engagement. As part of our validation process, we are testing digital signing capabilities using PGP keys to ensure the integrity and authenticity of submission artifacts.

## Command Center and Audit Shield Tour
### Home
![Home](img/home.png)

### Audit Shield KSI View
![Audit Shield KSI View](img/as-1.png)

### KSI Objective View
![KSI Objective View](img/as-2.png)

### KSI Objective Check Detail View
![KSI Objective Check Detail View](img/as-4.png)

### KSI Objective Check List
![KSI Objective Check List](img/as-5.png)

### ConMon Dashboard
![Continuous Monitoring Dashboard in Command Center](img/conmon.png)

### Document Repository
![Document Repository](img/document_repository.png)

### Ticketing
![Ticketing](img/ticketing.png)

### A message from Bill
![FedRAMP 20x](img/do-it-live.png)