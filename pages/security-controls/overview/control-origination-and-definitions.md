---
permalink: /security-controls/control-origination-and-definitions/
layout: styleguide
category: Security Controls
title: Control Origination and Definitions
lead: The definitions below indicate where each security control originates
---


| Control Origination | Definition | Example |
|:--------------------|:-----------|:--------|
| Service Provider Corporate | A control that originates from the Red Hat corporate network. | DNS from the Red Hat corporate network provides address resolution services for the information system and service offering. |
| Service Provider System Specific | A control specific to a particular system at Red Hat and the control is not part of the standard corporate controls. | A unique host-based intrusion detection system (HIDS) is available on the service offering platform but is not available on the corporate network. |
| Service Provider Hybrid | A control that makes use of both corporate controls and additional controls specific to a particular system at Red Hat. | There are scans of the corporate network infrastructure; scans of databases and web-based application are system specific. |
| Configured by Customer | A control where the customer needs to apply a configuration in order to meet the control requirement. | User profiles, policy/audit configurations, enabling/disabling key switches (e.g., enable/disable http or https, etc), entering an IP range specific to their organization are configurable by the customer. |
| Provided by Customer | A control where the customer needs to provide additional hardware or software in order to meet the control requirement. | The customer provides a SAML SSO solution to implement two-factor authentication. | 
| Shared | A control that is managed and implemented partially by Red hat and partially by the customer. | Security awareness training must be conducted by both Red Hat and the customer. |
| Inherited from pre-existing FedRAMP Authorization | A control that is inherited from another Red Hat system that has already received a RedRAMP Authorization. | A PaaS or SaaS provider inherits PE controls from an IaaS provider. |