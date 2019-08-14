---
type: component
title: Methodology
parent: fips199
order: 02
---
Impact levels are determined for each information type based on the security objectives (confidentiality, integrity, availability). The confidentiality, integrity, and availability impact levels define the security sensitivity category of each information type. The FIPS PUB 199 is the high watermark for the impact level of all the applicable information types. 

The FIPS PUB 199 analysis represents the information type and sensitivity levels of the CSP’s cloud service offering (and is not intended to include sensitivity levels of agency data). Customer agencies will be expected to perform a separate FIPS 199 Categorization report analysis for their own data hosted on the CSP’s cloud environment. The analysis must be added as an appendix to the SSP and drive the results for the Categorization section.  

The Table 2 1 CSP Applicable Information Types with Security Impact Levels Using NIST SP 800-60 V2 R1 below uses the NIST SP 800-60 V2 R1 Volume II Appendices to Guide for Mapping Types of Information and Information Systems to Security Categories to identify information types with the security impacts.

| Information Type | NIST SP 800-60 V2 R1 Recommended Confidentiality Impact Level | NIST SP 800-60 V2 R1 Recommended Integrity Impact Level | NIST SP 800-60 V2 R1 Recommended Availability Impact Level | CSP Selected Confidentiality Impact Level | CSP Selected Integrity Impact Level | CSP Selected Availability Impact Level |
|:-|:-:|:-:|:-:|:-:|:-:|:-:|
| Corrective Action (Policy/Regulation) | Low | Low | Low | High | High | High |
| Program Evaluation | Low | Low | Low | High | High | High |
| Policy Guidance and Development | Low | Low | Low | High | High | High |
| Public Comment Tracking | Low | Low | Low | High | High | High |
| Regulatory Creation | Low | Low | Low | High | High | High |
| Rule Publication | Low | Low | Low | High | High | High |
| Budget Formation | Low | Low | Low | High | High | High |
| Capital Planning | Low | Low | Low | High | High | High |
| Enterprise Architecture | Low | Low | Low | High | High | High |
| Strategic Planning | Low | Low | Low | High | High | High |
| Budget Execution | Low | Low | Low | High | High | High |
| Workforce Planning | Low | Low | Low | High | High | High |
| Management Improvement | Low | Low | Low | High | High | High |
| Budget & Performance Integration | Low | Low | Low | High | High | High |
| Tax and Fiscal Policy | Low | Low | Low | High | High | High |
| Contingency Planning | Moderate | Moderate | Moderate | High | High | High |
| Continuity of Operations | Moderate | Moderate | Moderate | High | High | High |
| Service Recovery | Low | Low | Low | High | High | High |
| Debt Collection | Moderate | Low | Low | High | High | High |
| User Fee Collection | Low | Low | Moderate | High | High | High |
| Federal Asset Sales | Low | Moderate | Low | High | High | High |
| Customer Service | Low | Low | Low | High | High | High |
| Official Information Dissemination | Low | Low | Low | High | High | High |
| Product Outreach | Low | Low | Low | High | High | High |
| Public Relations | Low | Low | Low | High | High | High |
| Legislation Tracking | Low | Low | Low | High | High | High |
| Legislation Testimony | Low | Low | Low | High | High | High |
| Proposal Development | Moderate | Low | Low | High | High | High |
| Congressional Liaison Operations | Moderate | Low | Low | High | High | High |
| Central Fiscal Operations | Moderate | Low | Low | High | High | High |
| Legislative Functions | Low | Low | Low | High | High | High |
| Executive Functions | Low | Low | Low | High | High | High |
| Central Property Management | Low | Low | Low | High | High | High |
| Central Personnel Management | Low | Low | Low | High | High | High |
| Taxation Management | Moderate | Low | Low | High | High | High |
| Central Records and Statistics Management | Moderate | Low | Low | High | High | High |
| Income Information | Moderate | Moderate | Moderate | High | High | High |
| Personal Identity and Authentication | Moderate | Moderate | Moderate | High | High | High |
| Entitlement Event Information | Moderate | Moderate | Moderate | High | High | High |
| Representative Payee Information | moderate | Moderate | Moderate | High | High | High |
| General Information | Low | Low | Low | High | High | High |
| Facilities, Fleet, and Equipment Mgmt | Low | Low | Low | High | High | High |
| Help Desk Services | Low | Low | Low | High | High | High |
| Security Management | Moderate | Moderate | Low | High | High | High |
| Travel | Low | Low | Low | High | High | High |
| Workplace Policy Development and Management | Low | Low | Low | High | High | High |
| Asset Liability Management | Low | Low | Low | High | High | High |
| Reporting and Information | Low | Moderate | Low | High | High | High |
| Funds Control | Moderate | Moderate | Low | High | High | High |
| Accounting | Low | Moderate | Low | High | High | High |
| Payments | Low | Moderate | Low | High | High | High |
| Collections and Receivables | Low | Moderate | Low | High | High | High |
| Cost Accounting / Performance Measurement | Low | Moderate | Low | High | High | High |
| HR Strategy | Low | Low | Low | High | High | High |
| Staff Aquisition | Low | Low | Low | High | High | High |
| Organization and Position Movement | Low | Low | Low | High | High | High |
| Compensation Management | Low | Low | Low | High | High | High |
| Benefits Management | Low | Low | Low | High | High | High |
| Employee Performance Management | Low | Low | Low | High | High | High |
| Employee Relations | Low | Low | Low | High | High | High |
| Labor Relations | Low | Low | Low | High | High | High |
| Separation Management | Low | Low | Low | High | High | High |
| Human Resources Development | Low | Low | Low | High | High | High |
| Goods Aquisition | Low | Low | Low | High | High | High |
| Inventory Control | Low | Low | Low | High | High | High |
| Logistics Management | Low | Low | Low | High | High | High |
| Services Acquisition | Low | Low | Low | High | High | High |
| System Development | Low | Moderate | Low | High | High | High |
| Lifecycle / Change Management | Low | Moderate | Low | High | High | High |
| System Maintenance | Low | Low | Low | High | High | High |
| IT Infrastructure Maintenance | Low | Low | Low | High | High | High |
| Information System Security | Low | Moderate | Low | High | High | High |
| Record Retention | Low | Low | Low | High | High | High |
| Information Management | Low | Moderate | Low | High | High | High |
| System and Network Monitoring | Moderate | Moderate | Low | High | High | High |
| Information Sharing | N/A | N/A | N/A | N/A | N/A | N/A |

## STATEMENT FOR IMPACT ADJUSTMENT JUSTIFICATION
As a shared hosting provider Red Hat OpenShift Dedicated must implement security controls to the highest potential level of confidentiality, integrity, and availability, of customer data.<br/>
<br/>
Red Hat has deemed any compromise to OpenShift Dedicated may, in worst-case scenarios and for each NIST 800-60 V2 R1 Information Type, result in severe or catastrophic adverse effects on OpenShift Dedicated operations, organizational assets, or customers. For this reason, Red Hat has tailored all confidentiality, integrity, and availability controls to <b>high</b>.