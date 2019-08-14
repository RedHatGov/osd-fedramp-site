---
type: component
title: Privacy Impact Assessment Talking Points
parent: pii
order: 03
---
According to NIST SP 800-122, Appendix D,

`````There must be no personal data record-keeping systems whose very existence is secret.`````

Additionally, NIST SP 800-122, Appendix D states,

`````There should be a general policy of openness about developments, practices and policies whith respect to personal data. Means should be readily available of establishing the existence and nature of personal data and the main purposes of their use, as well as the identity and usual residence of the data controller.`````

In light of the NIST guidance, Privacy Impact Assessment talking points have been developed for the purpose of ensuring full disclosure between stakeholders.

Identifiers in parenthesis after a section title indicate NIST 800-53, Appendix J privacy controls that are related to the particular talking point. These mappings to Appendix J privacy controls are not considered a replacement for Appendix J controls.

## PII Mapping of Components (SE-1, DM-1)
Red Hat Openshift Dedicated consists of <<COMPONENTS>>. Each component has been analyzed to determine if any elements of that component collect and/or store PII. The type of PII collected and/or stored by Red Hat OpenShift Dedicated and the functions that collect it are recorded in the table below:

| Components | Does this Component Collect or Store PII? (Yes/No) | Type of PII | Reason for Collection of PII | Safeguards |
|:-----------|:--------------------------------------------------:|:------------|:-----------------------------|:----------|
| tbd | tbd | tbd | tbd | tbd |

## Prospective PII Use
Respond to the following questions:

### 1. Are there any data fields in the platform or application that have been targeted for the collection and storage of PII? If yes, please name those fields. (SE-1, DM-1, IP-1)
    
    Answer will go here

### 2. If PII fields are used, can individuals "opt-out" of PII fields by declining to provide PII or by consenting to only a particular use (e.g. allowing basic use of their personal information, but not sharing with other government agencies)? (IP-1)

    Answer will go here.

## Sources of PII and Purpose

#### 3. Does Red Hat have knowledge of existing federal agencies that provide PII that gets imported into the system? (AP-2)

        Answer 

#### 4. Has any agency that is known to provide PII to the system provided a stated purpose for populating the system with PII? (AP-1, AP-2)

    Answer

#### 5. Does Red Hat currently populate the system with PII? If yes, where does the PII come from and what is the purpose? (AP-1, AP-2)

    Answer

#### 6. Will any third party sources be providing PII that will be imported into the system (if known)? Please explain. (AP-1, AP-2)

    Answer
    
## Access to PII and Sharing

#### 7. What third-party organizations will have access to the PII (if known)? Who establishes the criteria for what PII can be shared? (AP-1, AP-2, AR-8, IP-1, UL-2)

    Answer

#### 8. What Red Hat personnel roles will have access to PII fields (e.g. users, managers, system adminsitrators, developers, contractors, other)? Explain the need for Red Hat personnel to ahve access to the PII. (AR-8, UL-2)

    Answer

#### 9. Cor Red Hat support staff, how is access to the PII determined? Are criteria, procedures, controls, and responsibilities regarding access documented? Does access to PII require manager approval? (IP-2)

    Answer

#### 10. Do other systems that interconnect to the system share, transmit, or access the PII in the system? If yes, explain the purpose for system to system transmission, access, or sharing of PII. (UL-2)

        Answer

## PII Safeguards and Liabilities

#### 11. What controls are in place to prevent the misuse (e.g. browsing) of PII by those having access? (AR-2)

    Answer

#### 12. Who will be responsible for protecting the privacy rights of the individuals whose PII is collected, maintained, or shared on the system? Have policies and/or procedures been established for this responsibility and accountability? (AR-1, AR-2)

    Answer

#### 13. Does Red Hat provide annual security training including privacy training? Does Red Hat require their contractors that have access to the PII to take the training? (AR-5)

    Answer

#### 14. Who is privacy officer responsible for assuring safeguards for the PII? (AR-1)

    Answer

#### 15. What is the magnitude of harm to the individuals if privacy related data is disclosed, intentionally or unintentionally? (AR-2)

    Answer

#### 16. What involvement will contractors have with the design and maintenance of the system? Has a contractor confidentiality agreement or a Non-Disclosure Agreement (NDA) been developed for contractors who work on the system? (AR-3)

    Answer

#### 17. Is the PII owner advised about what federal agencies or other organizations share of have access to the data? (AR-1)

    Answer

## Contracts, Agreements, and Ownership

#### 18. NIST SP 800-144 states, "Organizations are ultimately accountable for the security and privacy of data held by a cloud provider on their behalf." Is the accountability described in contracts with customers? Why or why not? (AR-3)

    Answer

#### 19. Do contracts with customers establish who has ownership rights over data including PII? (AR-2, AR-3)

    Answer

#### 20. Do contracts with customers require that customers notify Red Hat if the customer intends to populate the service platform with PII? Why or why not? (AR-3)

    Answer

#### 21. Do Red Hat contracts with customers establish record retention responsibilities for both the customer and Red Hat? (AR-2, AR-3)

    Answer

#### 22. Is the degree to which Red Hat will accept liability for exposure of PII clearly defined in agreements with customers? (AR-3)

    Answer

## Accuracy of the PII and Redress

#### 23. Is the PII collected verified for accuracy? Why or why not? (DI-1)

    Answer

#### 24. Is the PII current? How is this determined? (DI-1)

    Answer

#### 25. Is there a process for indivuals to have inaccurate PII that is maintained by the system corrected or amended, as appropriate?

    Answer

## Maintenance and Administrative Controls

#### 26. If the system is operated in more than one site, how is consistent use of the PII maintained in all sites? Are the same controls used?

    Answer

#### 27. What are retention periods of PII for this system? Under what guidelines are the retention periods determined? Who establishes the retention guidelines? (AR-2, AR-3, DM-2)

    Answer

#### 28. What are the procedures for disposition of the PII at the end of the retention period? How long will any reports that contain PII be maintained? How is the information disposed (e.g., shredding, degaussing, overwriting, etc.)? Who establishes the decommissioning procedures? (AR-2, DM-2)

    Answer

#### 29. Is the system using new technologies that contain PII in ways that have not previously deployed? (e.g. smart cards, caller-ID, biometrics, PIV cards, etc.)?

    Answer

#### 30. How does the use of this technology affect privacy? Does the use of this technology introduce compromise that did not exist prior to the deployment of this technology?

    Answer

#### 31. Is access to the PII being monitored, tracked, or recorded? (AR-4)

    Answer

#### 32. if the system is in the process of being modified and a SORN exists, will the SORN require amendment or revision? (TR-2)

    Answer

## Business Process and Technology

#### 33. Have the talking poinds found herin resulted in circumstances that requires changes to business practices?

    Answer

#### 34. Does the outcome of these talking points require that technology or operational changes be made to the system? 

    Answer

## Privacy Policy

#### 35. Is there a system privacy policy and is it provided to all individuals whose PII you collect, maintain or store? (IP-1, TR-1, TR-3)

    Answer

#### 36. Is the data privacy publicly viewable? If yes, provide the URL. (TR-1, TR-3)

    Answer

## Signatures
The information found herin has been documented by Red Hat and has been reviewed by the Red Hat OpenShift Dedicated, Chief Privacy Officer for accuracy.

