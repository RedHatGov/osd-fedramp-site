---
permalink: /getting-started/information-system-type/
layout: styleguide
title: Information System Type
category: Getting Started
lead:
subnav:
  - text: Cloud Service Models
    link: '#cloud-service-models'
  - text: Cloud Deployment Models
    href: '#cloud-deployment-models'
  - text: Leveraged Authorizations
    href: '#leveraged-authorizations'
---

Red Hat OpenShift Dedicated makes use of unique managed service provider architecture layer(s).

## Cloud Service Models
Information systems, particularly those based on cloud architecture models, are made up of different service layers. Below are some questions that help system owners determine if their system is a cloud followed by specific questions to help the system owner determine the type of cloud.

| Question (Yes/No) | Response | Conclusion |
|:------------------|:--------:|:-----------|
| Does the system use virtual machines? | Yes | A no response means that system is most likely not a cloud.|
| Does the system have the ability to expand its capacity to meet customer demand? | Yes | A no response means that the system is most likely not a cloud. | 
| Does the system allow the consumer to build anything other than servers? | Yes | A no response means that the system is an IaaS. A yes response means that the system is either a PaaS or a SaaS.|
| Does the system offer the ability to create databases? | Yes | A yes response means the system is a PaaS. |
| Does the system offer various developer toolkits and APIs? | Yes | A yes response means that the system is a PaaS. |
| Does the system offer only applications that are available by obtaining a login? | Yes | A yes response means the system is a SaaS. A no response measn that the system is either a PaaS or an IaaS. |

The layers of the Red Hat OpenShift Dedicated defined in this SSP are indicated below:

| | |
|:-:|:-|:-|
| X | Software as a Service (SaaS) | Major Application |
| X | Platform as a Service (PaaS) | Major Application |
| | Infrastructure as a Service (IaaS) | General Support System |
| | Other | |

Note: Refer to NIST SP 800-145 for information on cloud computing architecture models.

## Cloud Deployment Models
Information systems are made up of different deployment models. The deployment models of the Red Hat OpenShift Dedicated that are defined in this SSP and are not leveraged by any other FedRAMP Authorizations, are indicated below:

Service Provider Cloud Deployment Model

| | |
|:-:|:-|:-|
| X | Public | Cloud services and infrastructure supporting multiple organizations and agency clients. |
| | Private | Cloud services and infrastructure dedicated to a specific organization/agency and no other clients. |
| | Government Only Community | Cloud services and infrastructure shared by several organizations/agencies with the same policy and compliance considerations. |
| | Hybrid | Explain: (e.g. cloud services and infrastructure that provides private cloud for secured applications and data where required and public cloud for other applications and data) |

## Leveraged Authorizations
The Red Hat OpenShift Dedicated leverages a pre-existing FedRAMP Authorization. FedRAMP Authorizations levered by this Red Hat OpenShift Dedicated are listed below:


| Leveraged Information System Name | Leveraged Service Provider Owner | Date Granted |
|:----------------------------------|:---------------------------------|:------------:|
| [Amazon - AWS US East/West](https://marketplace.fedramp.gov/#/product/aws-us-eastwest?sort=productName&productNameSearch=amazon) | Amazon | 11/13/2007 |