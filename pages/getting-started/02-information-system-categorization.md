---
permalink: /getting-started/information-system-categorization
layout: styleguide
title: Information System Categorization
category: Getting Started
lead:
subnav:
  - text: Information Types
    link: '#information-types'
  - text: Security Objectives Categorization (FIPS 199)
    href: '#security-objectives-categorization'
  - text: Digital Identity Determination
    href: '#digital-identity-determination'
---


The overall information system sensitivity categorization is recorded below. 

<table>
	<tr>
		<td>System Sensitivity Level:</td>
		<td>Moderate</td>
	</tr>
</table>

## Information Types
This section describes how the information types used by the information system are categorized for confidentiality, integrity and availability sensitivity levels.

The following tables identify the information types that are input, stored, processed and/or output from Red Hat OpenShift Dedicated. The selection of the information typoes is based on guidance provided by Office of Management and Budget (OMB) Federal Enterprise Architecture Program Management office Business Reference Model 2.0 and FIPS Pub 199, Standards for Security Categorization of Federal Informnation and Information Systems which is based on NIST Special Publication (SP) 800-60, Guide for Mapping Types of Information and Information Systems to Security Categories.

The tables also identify the security impact levels for confidentiality, integrity and availability for each of the information types expressed as low, moderate, or high. The security impact levels are based on the potential impact definitions for each of the security objectives (i.e., confidentiality, integrity and availability) discussed in NIST SP 800-60 and FIPS Pub 199.

The potential impact is low if:
<ul>
	<li>The loss of confidentiality, integrity, or availability could be expected to have a limited adverse effect on organizational operations, organizational assets, or individuals.</li>
	<li>A limited adverse effect measn that, for example, the loss of confidentiality, integrity, or availability might: (i) cause a degradation in mission capability to an extend and duration that the organization is able to perform its primary functions, but the effectiveness of the functions is noticeably reduced; (ii) result in minor damange to organizational assets; (iii) result in minor financial loss; of (iv) result in minor harm to individuals.</li>
</ul>

The potential impact is moderate if:
<ul>
	<li>The loss of confidentiality, integrity, or availability could be expected to have serious adverse effect on organizational operations, organizational assets, or individuals.</li>
	<li>A serious adverse effect means that, for example, the loss of confidentiality, integrity, or availability might: (i) cause a significant degradation in mission capability to an extend and duration that the organization is able to perform its primary functions, but the effectiveness of the functions is significantly reduced; (ii) result in significant damage to organizational assets; (iii) result in significant financial loss; or (iv) result in significant harm to individuals that does not involve loss of life or serious life threatening injuries.</li>
</ul>

The potential impact is high if:
<ul>
	<li>The loss of confidentiality, integrity, or availability could be expected to have a severe or catastrophic adverse effect on organizational operations, organizational assets, or individuals.</li>
	<li>A severe or catastrophic adverse effect means that, for example, the loss of confidentiality, integrity, or availability might: (i) cause a severe degradation in loss of mission capability to an extend and duration that the organization is not able to perform one or more of its primary functions; (ii) result in major damage to organizational assets; (iii) result in major financial loss; or (iv) result in severe or catastrophic harm to individuals involving loss of life or serious life threatening injuries.</li>
</ul>

Sensitivity Categorization of Information Types

| Information Type (Use only information types from NIST SP 800-60, Volumes I and II as amended) | NIST 800-60 identifier for Associated Information Type | Confidentiality | Integrity | Availability |
|:---|:---|:--:|:--:|:--:|
| TBD | TBD | TBD | TBD | TBD |

## Security Objectives Categorization (FIPS 199)
Based on the information provided in the Sensitivity Categorization of Information Types, for Red Hat OpenShift Dedicated, default to the high-water mark for the Information Types as identified in the table below:

Security Impact Level

| Security Objective | Low, Moderate, or High |
|:-------------------|:----------------------:|
| TBD | TBD |

Through review and analysis, it has been determined that the baseline security categorization for Red Hat OpenShift Dedicated is listed in the table below:

<table>
	<tr>
		<td>Enter Information System Abbreviation Security Categorization</td>
		<td>Moderate</td>
	</tr>
</table>

Using this categorization, in conjunction with the risk assessment and any unique security requirements, we have established the security controls for this system, as detailed in this SSP.

## Digital Identity Determination
The digital identity information may be found in ATTACHMENT 3 - Digital Identity Worksheet.

Note: NIST SP 600-63-3, "Digital Identity Guidelines," does not recognize the four Levels of Assurance model previously used by federal agencies and described in OMB M-04-04, instead requiring agencies to individually select levels corresponding to each function being performed.

The digital identity level is: TBD

Additional digital identity information can be found in Section 15 Attachements Digital Identity Level Selection.