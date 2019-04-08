---
permalink: /getting-started/general-system-description/
layout: styleguide
title: General System Description
category: Getting Started
lead:
subnav:
  - text: System Function or Purpose
    link: '#system-function-or-purpose'
  - text: Information System Components and Boundaries
    href: '#information-system-components-and-boundaries'
  - text: Types of Users
    href: '#types-of-users'
  - text: Network Architecture
    href: '#network-architecture'
---

This section includes a general description of Red Hat OpenShift Dedicated.

## System Function or Purpose
<tbd - in the space that follows, describe the purpose and functions of this system>

## Information System Components and Boundaries
<tbd - 
Instruction: In the space that follows, provide an explicit definition of the system’s Authorization Boundary.  Provide a diagram that portrays this Authorization Boundary and all its connections and components, including the means for monitoring and controlling communications at the external boundary and at key internal boundaries within the system. Address all components and managed interfaces of the information system authorized for operation (e.g., routers, firewalls). 
The diagram must include a predominant border drawn around all system components and services included in the authorization boundary. The diagram must be easy to read and understand.
Formal names of components as they are known at the service provider organization in functional specifications, configuration guides, other documents and live configurations shall be named on the diagram and described. Components identified in the Boundary diagram should be consistent with the Network diagram and the inventory(ies). Provide a key to symbols used.  Ensure consistency between the boundary and network diagrams and respective descriptions (Section 9.4) and the appropriate Security Controls [AC-20, CA-3(1)].  
Additional FedRAMP Requirements and Guidance:
Guidance: See the FedRAMP Documents page under Key Cloud Service Provider (CSP) Documents> FedRAMP Authorization Boundary Guidance
 https://www.fedramp.gov/documents/

Delete this and all other instructions from your final version of this document>

A detailed and explicit definition of the system authorization boundary diagram is represented in the figure/diagram below:

<TBD - boundary diagram>

## Types of Users
All personnel have their status categorized with a sensitivity level in accordance with PS-2. Personnel (employees or contractors) of service providers are considered Internal Users. All other users are considered External Users. User privileges (authorization permission after authentication takes place) are described in the table that follows.

Personnel Roles and Privileges

| Role | Internal or External | Privileged (P), Non-Privileged (NP), or No Logical Access (NLA) | Sensitivity Level | Authorized Privileges | Functions Performed |
|:--|:-:|:--|:-:|:--|:--|
| System Administrator | Internal | P | Moderate | Full administrative access (root) | Add/remove users, install/configure software, OS updates, patches and hotfixes, perform backups. |
| Client Administrator | External | NP | N/A | Portal Administration | Add/remove client users. Create, modify, delete client applications. |

There are currently <TBD> internal personnel and <TBD> external personnel. Within one year, it is anticipated that there will be <number> internal personnel and <number> external personnel.

## Network Architecture
<i>Instruction: Insert a network architectural diagram in the space that follows. Ensure that the following items are labeled on the diagram: hostnames, Domain Name System (DNS) servers, DHCP servers, authentication and access control servers, directory servers, firewalls, routers, switches, database servers, major applications, storage, Internet connectivity providers, telecom circuit numbers, network interfaces and numbers, VLANs. Major security components should be represented. If necessary, include multiple network diagrams.
Delete this and all other instructions from your final version of this document.</i>

Assessors should be able to easily map hardware, software, and network inventories back to this diagram. 

The logical network topology is shown in figure "Network Diagram" mapping the data flow between components.

The following figure "Network Diagram(s)" provides a visual depiction of the system network components that constitute Red Hat OpenShift Dedicated.