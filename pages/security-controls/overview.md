---
permalink: /security-controls/
layout: styleguide
title: Security Controls
category: Security Controls
lead: NIST 800-53 Control Responses
---
Secutity controls must meet minimum security control baseline requirements. Upon categorizing a system as Low, Moderate, or High sensitivity in accordance with FIPS 199, the corresponding security control baseline standards apply. Some of the control baselines have enhanced controls which are indicated in parentheses.

Security controls that are representitive of the sensitivity of Red Hat OpenShift Dedicated are described in the sections that follow. Security controls that are designated as "Not Selected" or "Withdrawn by NIST" are not described unless they have additional FedRAMP controls. Guidance on how to describe the implemented standard can be found in NIST 800-53, Rev 4. Control enhancements are marked in the parentheses in the sensitivity columns. 

Systems that are categorized as FIPS 199 Low use the controls designated as Low, systems categorized as FIPS 199 Moderate use the controls designated as Moderate and systems categorized as FIPS 199 High use the controls designated as High. A summary of which security standards pertain to which sensitivity level is found in the table below.

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-abx8{font-weight:bold;background-color:#c0c0c0;text-align:left;vertical-align:top}
.tg .tg-1nlt{background-color:#010066;color:#ffffff;text-align:center;vertical-align:top}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg" align="center">
  <tr>
    <th class="tg-1nlt" rowspan="2">ID</th>
    <th class="tg-1nlt" rowspan="2">Control Description</th>
    <th class="tg-1nlt" colspan="3">Sensitivity Level</th>
  </tr>
  <tr>
    <td class="tg-1nlt">Low</td>
    <td class="tg-1nlt">Moderate</td>
    <td class="tg-1nlt">High</td>
  </tr>
  <tr>
    <td class="tg-abx8">AC</td>
    <td class="tg-abx8" colspan="4">Access Control</td>
  </tr>
  <tr>
    <td class="tg-0lax">AC-1</td>
    <td class="tg-0lax">Access Control Policy and Proceedures</td>
    <td class="tg-baqh">AC-1</td>
    <td class="tg-baqh">AC-1</td>
    <td class="tg-baqh">AC-1</td>
  </tr>
  <tr>
    <td class="tg-0lax">AC-2</td>
    <td class="tg-0lax">Account Management</td>
    <td class="tg-baqh">AC-2</td>
    <td class="tg-baqh">AC-2 (1) (2) (3) (4) (5) (7) (9) (10) (12)</td>
    <td class="tg-baqh">AC-2 (1) (2) (3) (4) (5) (7) (9) (10) (11) (12) (13)</td>
  </tr>
  <tr>
    <td class="tg-0lax">AC-3</td>
    <td class="tg-0lax">Access Enforcement</td>
    <td class="tg-baqh">AC-3</td>
    <td class="tg-baqh">AC-3</td>
    <td class="tg-baqh">AC-3</td>
  </tr>
  <tr>
    <td class="tg-0lax">AC-4</td>
    <td class="tg-0lax">Information Flow Enforcement</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">AC-4 (21)</td>
    <td class="tg-baqh">AC-4 (8) (21)</td>
  </tr>
  <tr>
    <td class="tg-0lax">AC-5</td>
    <td class="tg-0lax">Separation of Duties</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">AC-5</td>
    <td class="tg-baqh">AC-5</td>
  </tr>
  <tr>
    <td class="tg-0lax">AC-6</td>
    <td class="tg-0lax">Least Privilege</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">AC-6 (1) (2) (5) (9) (10)</td>
    <td class="tg-baqh">AC-6 (1) (2) (3) (5) (7) (8) (9) (10)</td>
  </tr>
  <tr>
    <td class="tg-0lax">AC-7</td>
    <td class="tg-0lax">Unsuccessful Logon Attempts</td>
    <td class="tg-baqh">AC-7</td>
    <td class="tg-baqh">AC-7</td>
    <td class="tg-baqh">AC-7 (2)</td>
  </tr>
  <tr>
    <td class="tg-0lax">AC-8</td>
    <td class="tg-0lax">System Use Notification</td>
    <td class="tg-baqh">AC-8</td>
    <td class="tg-baqh">AC-8</td>
    <td class="tg-baqh">AC-8</td>
  </tr>
  <tr>
    <td class="tg-0lax">AC-10</td>
    <td class="tg-0lax">Concurrent Session Control</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">AC-10</td>
    <td class="tg-baqh">AC-10</td>
  </tr>
  <tr>
    <td class="tg-0lax">AC-11</td>
    <td class="tg-0lax">Session Lock</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">AC-11 (1)</td>
    <td class="tg-baqh">AC-11 (1)</td>
  </tr>
  <tr>
    <td class="tg-0lax">AC-12</td>
    <td class="tg-0lax">Session Termination</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">AC-12</td>
    <td class="tg-baqh">AC-12 (1)</td>
  </tr>
  <tr>
    <td class="tg-0lax">AC-14</td>
    <td class="tg-0lax">Permitted Actions Without Identification or Authentication</td>
    <td class="tg-baqh">AC-14</td>
    <td class="tg-baqh">AC-14</td>
    <td class="tg-baqh">AC-14</td>
  </tr>
  <tr>
    <td class="tg-0lax">AC-17</td>
    <td class="tg-0lax">Remote Access</td>
    <td class="tg-baqh">AC-17</td>
    <td class="tg-baqh">AC-17 (1) (2) (3) (4) (9)</td>
    <td class="tg-baqh">AC-17 (1) (2) (3) (4) (9)</td>
  </tr>
  <tr>
    <td class="tg-0lax">AC-18</td>
    <td class="tg-0lax">Wireless Access</td>
    <td class="tg-baqh">AC-18</td>
    <td class="tg-baqh">AC-18 (1)</td>
    <td class="tg-baqh">AC-18 (1) (3) (4) (5)</td>
  </tr>
  <tr>
    <td class="tg-0lax">AC-19</td>
    <td class="tg-0lax">Access Control for Mobile Devices</td>
    <td class="tg-baqh">AC-19</td>
    <td class="tg-baqh">AC-19 (5)</td>
    <td class="tg-baqh">AC-19 (5)</td>
  </tr>
  <tr>
    <td class="tg-0lax">AC-20</td>
    <td class="tg-0lax">Use of External Information Systems</td>
    <td class="tg-baqh">AC-20</td>
    <td class="tg-baqh">AC-20 (1) (2)</td>
    <td class="tg-baqh">AC-20 (1) (2)</td>
  </tr>
  <tr>
    <td class="tg-0lax">AC-21</td>
    <td class="tg-0lax">Information Sharing</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">AC-21</td>
    <td class="tg-baqh">AC-21</td>
  </tr>
  <tr>
    <td class="tg-0lax">AC-22</td>
    <td class="tg-0lax">Publicly Accessible Content</td>
    <td class="tg-baqh">AC-22</td>
    <td class="tg-baqh">AC-22</td>
    <td class="tg-baqh">AC-22</td>
  </tr>
  <tr>
    <td class="tg-abx8">AT</td>
    <td class="tg-abx8" colspan="4">Awareness and Training</td>
  </tr>
  <tr>
    <td class="tg-0lax">AT-1</td>
    <td class="tg-0lax">Security Awareness and Training Policy and Procedures</td>
    <td class="tg-baqh">AT-1</td>
    <td class="tg-baqh">AT-1</td>
    <td class="tg-baqh">AT-1</td>
  </tr>
  <tr>
    <td class="tg-0lax">AT-2</td>
    <td class="tg-0lax">Security Awareness Training</td>
    <td class="tg-baqh">AT-2</td>
    <td class="tg-baqh">AT-2 (2)</td>
    <td class="tg-baqh">AT-2 (2)</td>
  </tr>
  <tr>
    <td class="tg-0lax">AT-3</td>
    <td class="tg-0lax">Role-Based Security Training</td>
    <td class="tg-baqh">AT-3</td>
    <td class="tg-baqh">AT-3</td>
    <td class="tg-baqh">AT-3 (3) (4)</td>
  </tr>
  <tr>
    <td class="tg-0lax">AT-4</td>
    <td class="tg-0lax">Security Training Records</td>
    <td class="tg-baqh">AT-4</td>
    <td class="tg-baqh">AT-4</td>
    <td class="tg-baqh">AT-4</td>
  </tr>
  <tr>
    <td class="tg-abx8">AU</td>
    <td class="tg-abx8" colspan="4">Audit and Accountability</td>
  </tr>
  <tr>
    <td class="tg-0lax">AU-1</td>
    <td class="tg-0lax">Audit and Accountability Policy and Procedures</td>
    <td class="tg-baqh">AU-1</td>
    <td class="tg-baqh">AU-1</td>
    <td class="tg-baqh">AU-1</td>
  </tr>
  <tr>
    <td class="tg-0lax">AU-2</td>
    <td class="tg-0lax">Audit Events</td>
    <td class="tg-baqh">AU-2</td>
    <td class="tg-baqh">AU-2 (3)</td>
    <td class="tg-baqh">AU-2 (3)</td>
  </tr>
  <tr>
    <td class="tg-0lax">AU-3</td>
    <td class="tg-0lax">Content of Audit Records</td>
    <td class="tg-baqh">AU-3</td>
    <td class="tg-baqh">AU-3 (1)</td>
    <td class="tg-baqh">AU-3 (1) (2)</td>
  </tr>
  <tr>
    <td class="tg-0lax">AU-4</td>
    <td class="tg-0lax">Audit Storage Capacity</td>
    <td class="tg-baqh">AU-4</td>
    <td class="tg-baqh">AU-4</td>
    <td class="tg-baqh">AU-4</td>
  </tr>
  <tr>
    <td class="tg-0lax">AU-5</td>
    <td class="tg-0lax">Response to Audit Processing Failures</td>
    <td class="tg-baqh">AU-5</td>
    <td class="tg-baqh">AU-5</td>
    <td class="tg-baqh">AU-5</td>
  </tr>
  <tr>
    <td class="tg-0lax">AU-6</td>
    <td class="tg-0lax">Audit Review, Analysis and Reporting</td>
    <td class="tg-baqh">AU-6</td>
    <td class="tg-baqh">AU-6 (1) (3)</td>
    <td class="tg-baqh">AU-6 (1) (3) (4) (5) (6) (7)</td>
  </tr>
  <tr>
    <td class="tg-0lax">AU-7</td>
    <td class="tg-0lax">Audit Reduction and Report Generation</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">AU-7 (1)</td>
    <td class="tg-baqh">AU-7 (1)</td>
  </tr>
  <tr>
    <td class="tg-0lax">AU-8</td>
    <td class="tg-0lax">Time Stamps</td>
    <td class="tg-baqh">AU-8</td>
    <td class="tg-baqh">AU-8 (1)</td>
    <td class="tg-baqh">AU-8 (1)</td>
  </tr>
  <tr>
    <td class="tg-0lax">AU-9</td>
    <td class="tg-0lax">Protection of Audit Information</td>
    <td class="tg-baqh">AU-9</td>
    <td class="tg-baqh">AU-9 (2) (4)</td>
    <td class="tg-baqh">AU-9 (2) (3) (4)</td>
  </tr>
  <tr>
    <td class="tg-0lax">AU-10</td>
    <td class="tg-0lax">Non-repudiation</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">AU-10</td>
  </tr>
  <tr>
    <td class="tg-0lax">AU-11</td>
    <td class="tg-0lax">Audit Record Retention</td>
    <td class="tg-baqh">AU-11</td>
    <td class="tg-baqh">AU-11</td>
    <td class="tg-baqh">AU-11</td>
  </tr>
  <tr>
    <td class="tg-0lax">AU-12</td>
    <td class="tg-0lax">Audit Generation</td>
    <td class="tg-baqh">AU-12</td>
    <td class="tg-baqh">AU-12</td>
    <td class="tg-baqh">AU-12 (1) (3)</td>
  </tr>
  <tr>
    <td class="tg-abx8">CA</td>
    <td class="tg-abx8" colspan="4">Security Assessment and Authorization</td>
  </tr>
  <tr>
    <td class="tg-0lax">CA-1</td>
    <td class="tg-0lax">Security Assessment and Authorization Policies and Proceedures</td>
    <td class="tg-baqh">CA-1</td>
    <td class="tg-baqh">CA-1</td>
    <td class="tg-baqh">CA-1</td>
  </tr>
  <tr>
    <td class="tg-0lax">CA-2</td>
    <td class="tg-0lax">Security Assessments</td>
    <td class="tg-baqh">CA-2 (1)</td>
    <td class="tg-baqh">CA-2 (1) (2) (3)</td>
    <td class="tg-baqh">CA-2 (1) (2) (3)</td>
  </tr>
  <tr>
    <td class="tg-0lax">CA-3</td>
    <td class="tg-0lax">System Interconnections</td>
    <td class="tg-baqh">CA-3</td>
    <td class="tg-baqh">CA-3 (3) (5)</td>
    <td class="tg-baqh">CA-3 (3) (5)</td>
  </tr>
  <tr>
    <td class="tg-0lax">CA-5</td>
    <td class="tg-0lax">Plan of Action and Milestones</td>
    <td class="tg-baqh">CA-5</td>
    <td class="tg-baqh">CA-5</td>
    <td class="tg-baqh">CA-5</td>
  </tr>
  <tr>
    <td class="tg-0lax">CA-6</td>
    <td class="tg-0lax">Security Authorization</td>
    <td class="tg-baqh">CA-6</td>
    <td class="tg-baqh">CA-6</td>
    <td class="tg-baqh">CA-6</td>
  </tr>
  <tr>
    <td class="tg-0lax">CA-7</td>
    <td class="tg-0lax">Continuous Monitoring</td>
    <td class="tg-baqh">CA-7</td>
    <td class="tg-baqh">CA-7 (1)</td>
    <td class="tg-baqh">CA-7 (1) (3)</td>
  </tr>
  <tr>
    <td class="tg-0lax">CA-8</td>
    <td class="tg-0lax">Penetration Testing</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">CA-8 (1)</td>
    <td class="tg-baqh">CA-8 (1)</td>
  </tr>
  <tr>
    <td class="tg-0lax">CA-9</td>
    <td class="tg-0lax">Internal System Connections</td>
    <td class="tg-baqh">CA-9</td>
    <td class="tg-baqh">CA-9</td>
    <td class="tg-baqh">CA-9</td>
  </tr>
  <tr>
    <td class="tg-abx8">CM</td>
    <td class="tg-abx8" colspan="4">Configuration Management</td>
  </tr>
  <tr>
    <td class="tg-0lax">CM-1</td>
    <td class="tg-0lax">Configuration Management Policy and Proceedures</td>
    <td class="tg-baqh">CM-1</td>
    <td class="tg-baqh">CM-1</td>
    <td class="tg-baqh">CM-1</td>
  </tr>
  <tr>
    <td class="tg-0lax">CM-2</td>
    <td class="tg-0lax">Baseline Configuration</td>
    <td class="tg-baqh">CM-2</td>
    <td class="tg-baqh">CM-2 (1) (2) (3) (7)</td>
    <td class="tg-baqh">CM-2 (1) (2) (3) (7)</td>
  </tr>
  <tr>
    <td class="tg-0lax">CM-3</td>
    <td class="tg-0lax">Configuration Change Control</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">CM-3 (2)</td>
    <td class="tg-baqh">CM-3 (1) (2) (4) (6)</td>
  </tr>
  <tr>
    <td class="tg-0lax">CM-4</td>
    <td class="tg-0lax">Security Impact Analysis</td>
    <td class="tg-baqh">CM-4</td>
    <td class="tg-baqh">CM-4</td>
    <td class="tg-baqh">CM-4</td>
  </tr>
  <tr>
    <td class="tg-0lax">CM-5</td>
    <td class="tg-0lax">Access Restrictions for Change</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">CM-5 (1) (3) (5)</td>
    <td class="tg-baqh">CM-5 (1) (2) (3) (5)</td>
  </tr>
  <tr>
    <td class="tg-0lax">CM-6</td>
    <td class="tg-0lax">Configuration Settings</td>
    <td class="tg-baqh">CM-6</td>
    <td class="tg-baqh">CM-6 (1)</td>
    <td class="tg-baqh">CM-6 (1) (2)</td>
  </tr>
  <tr>
    <td class="tg-0lax">CM-7</td>
    <td class="tg-0lax">Least Functionality</td>
    <td class="tg-baqh">CM-7</td>
    <td class="tg-baqh">CM-7 (1) (2) (5)</td>
    <td class="tg-baqh">CM-7 (1) (2) (5)</td>
  </tr>
  <tr>
    <td class="tg-0lax">CM-8</td>
    <td class="tg-0lax">Information System Component Inventory</td>
    <td class="tg-baqh">CM-8</td>
    <td class="tg-baqh">CM-8 (1) (3) (5)</td>
    <td class="tg-baqh">CM-8 (1) (2) (3) (4) (5)</td>
  </tr>
  <tr>
    <td class="tg-0lax">CM-9</td>
    <td class="tg-0lax">Configuration Management Plan</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">CM-9</td>
    <td class="tg-baqh">CM-9</td>
  </tr>
  <tr>
    <td class="tg-0lax">CM-10</td>
    <td class="tg-0lax">Software Usage Restrictions</td>
    <td class="tg-baqh">CM-10</td>
    <td class="tg-baqh">CM-10 (1)</td>
    <td class="tg-baqh">CM-10 (1)</td>
  </tr>
  <tr>
    <td class="tg-0lax">CM-11</td>
    <td class="tg-0lax">User-Installed Software</td>
    <td class="tg-baqh">CM-11</td>
    <td class="tg-baqh">CM-11</td>
    <td class="tg-baqh">CM-11</td>
  </tr>
  <tr>
    <td class="tg-abx8">CP</td>
    <td class="tg-abx8" colspan="4">Contingency Planning</td>
  </tr>
  <tr>
    <td class="tg-0lax">CP-1</td>
    <td class="tg-0lax">Contingency Planning Policy and Procedures</td>
    <td class="tg-baqh">CP-1</td>
    <td class="tg-baqh">CP-1</td>
    <td class="tg-baqh">CP-1</td>
  </tr>
  <tr>
    <td class="tg-0lax">CP-2</td>
    <td class="tg-0lax">Contingency Plan</td>
    <td class="tg-baqh">CP-2</td>
    <td class="tg-baqh">CP-2 (1) (2) (3) (8)</td>
    <td class="tg-baqh">CP-2 (1) (2) (3) (4) (5) (8)</td>
  </tr>
  <tr>
    <td class="tg-0lax">CP-3</td>
    <td class="tg-0lax">Contingency Training</td>
    <td class="tg-baqh">CP-3</td>
    <td class="tg-baqh">CP-3</td>
    <td class="tg-baqh">CP-3 (1)</td>
  </tr>
  <tr>
    <td class="tg-0lax">CP-4</td>
    <td class="tg-0lax">Contingency Plan Testing</td>
    <td class="tg-baqh">CP-4</td>
    <td class="tg-baqh">CP-4 (1)</td>
    <td class="tg-baqh">CP-4 (1) (2)</td>
  </tr>
  <tr>
    <td class="tg-0lax">CP-6</td>
    <td class="tg-0lax">Alternate Storage Site</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">CP-6 (1) (3)</td>
    <td class="tg-baqh">CP-6 (1) (2) (3)</td>
  </tr>
  <tr>
    <td class="tg-0lax">CP-7</td>
    <td class="tg-0lax">Alternate Processing Site</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">CP-7 (1) (2) (3)</td>
    <td class="tg-baqh">CP-7 (1) (2) (3) (4)</td>
  </tr>
  <tr>
    <td class="tg-0lax">CP-8</td>
    <td class="tg-0lax">Telecommunication Services</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">CP-8 (1) (2)</td>
    <td class="tg-baqh">CP-8 (1) (2) (3) (4)</td>
  </tr>
  <tr>
    <td class="tg-0lax">CP-9</td>
    <td class="tg-0lax">Information System Backup</td>
    <td class="tg-baqh">CP-9</td>
    <td class="tg-baqh">CP-9 (1) (3)</td>
    <td class="tg-baqh">CP-9 (1) (2) (3) (5)</td>
  </tr>
  <tr>
    <td class="tg-0lax">CP-10</td>
    <td class="tg-0lax">Information System Recovery and Reconstitution</td>
    <td class="tg-baqh">CP-10</td>
    <td class="tg-baqh">CP-10 (2)</td>
    <td class="tg-baqh">CP-10 (2) (4)</td>
  </tr>
  <tr>
    <td class="tg-abx8">IA</td>
    <td class="tg-abx8" colspan="4">Identification and Authentication</td>
  </tr>
  <tr>
    <td class="tg-0lax">IA-1</td>
    <td class="tg-0lax">Identification and Authentication Policy and Procedures</td>
    <td class="tg-baqh">IA-1</td>
    <td class="tg-baqh">IA-1</td>
    <td class="tg-baqh">IA-1</td>
  </tr>
  <tr>
    <td class="tg-0lax">IA-2</td>
    <td class="tg-0lax">Identification and Authentication (Organizational Users)</td>
    <td class="tg-baqh">IA-2 (1) (12)</td>
    <td class="tg-baqh">IA-2 (1) (2) (3) (5) (8) (11) (12)</td>
    <td class="tg-baqh">IA-2 (1) (2) (3) (4) (5) (8) (9) (11) (12)</td>
  </tr>
  <tr>
    <td class="tg-0lax">IA-3</td>
    <td class="tg-0lax">Device Identification and Authentication</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">IA-3</td>
    <td class="tg-baqh">IA-3</td>
  </tr>
  <tr>
    <td class="tg-0lax">IA-4</td>
    <td class="tg-0lax">Identifier Management</td>
    <td class="tg-baqh">IA-4</td>
    <td class="tg-baqh">IA-4 (4)</td>
    <td class="tg-baqh">IA-4 (4)</td>
  </tr>
  <tr>
    <td class="tg-0lax">IA-5</td>
    <td class="tg-0lax">Authenticator Management</td>
    <td class="tg-baqh">IA-5 (1) (11)</td>
    <td class="tg-baqh">IA-5 (1) (2) (3) (4) (6) (7) (11)</td>
    <td class="tg-baqh">IA-5 (1) (2) (3) (4) (6) (7) (8) (11) (13)</td>
  </tr>
  <tr>
    <td class="tg-0lax">IA-6</td>
    <td class="tg-0lax">Authenticator Feedback</td>
    <td class="tg-baqh">IA-6</td>
    <td class="tg-baqh">IA-6</td>
    <td class="tg-baqh">IA-6</td>
  </tr>
  <tr>
    <td class="tg-0lax">IA-7</td>
    <td class="tg-0lax">Cryptographic Module Authentication</td>
    <td class="tg-baqh">IA-7</td>
    <td class="tg-baqh">IA-7</td>
    <td class="tg-baqh">IA-7</td>
  </tr>
  <tr>
    <td class="tg-0lax">IA-8</td>
    <td class="tg-0lax">Identification and Authentication (Non-Organizational users)</td>
    <td class="tg-baqh">IA-8 (1) (2) (3) (4)</td>
    <td class="tg-baqh">IA-8 (1) (2) (3) (4)</td>
    <td class="tg-baqh">IA-8 (1) (2) (3) (4)</td>
  </tr>
  <tr>
    <td class="tg-abx8">IR</td>
    <td class="tg-abx8" colspan="4">Incident Response</td>
  </tr>
  <tr>
    <td class="tg-0lax">IR-1</td>
    <td class="tg-0lax">Incident Response Policy and Procedures</td>
    <td class="tg-baqh">IR-1</td>
    <td class="tg-baqh">IR-1</td>
    <td class="tg-baqh">IR-1</td>
  </tr>
  <tr>
    <td class="tg-0lax">IR-2</td>
    <td class="tg-0lax">Incident Response Training</td>
    <td class="tg-baqh">IR-2</td>
    <td class="tg-baqh">IR-2</td>
    <td class="tg-baqh">IR-2 (1) (2)</td>
  </tr>
  <tr>
    <td class="tg-0lax">IR-3</td>
    <td class="tg-0lax">Incident Response Testing</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">IR-3 (2)</td>
    <td class="tg-baqh">IR-3 (2)</td>
  </tr>
  <tr>
    <td class="tg-0lax">IR-4</td>
    <td class="tg-0lax">Incident Handling</td>
    <td class="tg-baqh">IR-4</td>
    <td class="tg-baqh">IR-4 (1)</td>
    <td class="tg-baqh">IR-4 (1) (2) (3) (4) (6) (8)</td>
  </tr>
  <tr>
    <td class="tg-0lax">IR-5</td>
    <td class="tg-0lax">Incident Monitoring</td>
    <td class="tg-baqh">IR-5</td>
    <td class="tg-baqh">IR-5</td>
    <td class="tg-baqh">IR-5 (1)</td>
  </tr>
  <tr>
    <td class="tg-0lax">IR-6</td>
    <td class="tg-0lax">Incident Reporting</td>
    <td class="tg-baqh">IR-6</td>
    <td class="tg-baqh">IR-6 (1)</td>
    <td class="tg-baqh">IR-6 (1)</td>
  </tr>
  <tr>
    <td class="tg-0lax">IR-7</td>
    <td class="tg-0lax">Incident Response Assistance</td>
    <td class="tg-baqh">IR-7</td>
    <td class="tg-baqh">IR-7 (1) (2)</td>
    <td class="tg-baqh">IR-7 (1) (2)</td>
  </tr>
  <tr>
    <td class="tg-0lax">IR-8</td>
    <td class="tg-0lax">Incident Response Plan</td>
    <td class="tg-baqh">IR-8</td>
    <td class="tg-baqh">IR-8</td>
    <td class="tg-baqh">IR-8</td>
  </tr>
  <tr>
    <td class="tg-0lax">IR-9</td>
    <td class="tg-0lax">Information Spillage Response</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">IR-9 (1) (2) (3) (4)</td>
    <td class="tg-baqh">IR-9 (1) (2) (3) (4)</td>
  </tr>
  <tr>
    <td class="tg-abx8">MA</td>
    <td class="tg-abx8" colspan="4">Maintenance</td>
  </tr>
  <tr>
    <td class="tg-0lax">MA-1</td>
    <td class="tg-0lax">System Maintenance Policy and Procedures</td>
    <td class="tg-baqh">MA-1</td>
    <td class="tg-baqh">MA-1</td>
    <td class="tg-baqh">MA-1</td>
  </tr>
  <tr>
    <td class="tg-0lax">MA-2</td>
    <td class="tg-0lax">Controlled Maintenance</td>
    <td class="tg-baqh">MA-2</td>
    <td class="tg-baqh">MA-2</td>
    <td class="tg-baqh">MA-2 (2)</td>
  </tr>
  <tr>
    <td class="tg-0lax">MA-3</td>
    <td class="tg-0lax">Maintenance Tools</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">MA-3 (1) (2) (3)</td>
    <td class="tg-baqh">MA-3 (1) (2) (3)</td>
  </tr>
  <tr>
    <td class="tg-0lax">MA-4</td>
    <td class="tg-0lax">Nonlocal Maintenance</td>
    <td class="tg-baqh">MA-4</td>
    <td class="tg-baqh">MA-4 (2)</td>
    <td class="tg-baqh">MA-4 (2) (3) (6)</td>
  </tr>
  <tr>
    <td class="tg-0lax">MA-5</td>
    <td class="tg-0lax">Maintenance Personnel</td>
    <td class="tg-baqh">MA-5</td>
    <td class="tg-baqh">MA-5 (1)</td>
    <td class="tg-baqh">MA-5 (1)</td>
  </tr>
  <tr>
    <td class="tg-0lax">MA-6</td>
    <td class="tg-0lax">Timely Maintenance</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">MA-6</td>
    <td class="tg-baqh">MA-6</td>
  </tr>
  <tr>
    <td class="tg-abx8">MP</td>
    <td class="tg-abx8" colspan="4">Media Protection</td>
  </tr>
  <tr>
    <td class="tg-0lax">MP-1</td>
    <td class="tg-0lax">Media Protection Policy and Procedures</td>
    <td class="tg-baqh">MP-1</td>
    <td class="tg-baqh">MP-1</td>
    <td class="tg-baqh">MP-1</td>
  </tr>
  <tr>
    <td class="tg-0lax">MP-2</td>
    <td class="tg-0lax">Media Access</td>
    <td class="tg-baqh">MP-2</td>
    <td class="tg-baqh">MP-2</td>
    <td class="tg-baqh">MP-2</td>
  </tr>
  <tr>
    <td class="tg-0lax">MP-3</td>
    <td class="tg-0lax">Media Marking</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">MP-3</td>
    <td class="tg-baqh">MP-3</td>
  </tr>
  <tr>
    <td class="tg-0lax">MP-4</td>
    <td class="tg-0lax">Media Storage</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">MP-4</td>
    <td class="tg-baqh">MP-4</td>
  </tr>
  <tr>
    <td class="tg-0lax">MP-5</td>
    <td class="tg-0lax">Media Transport</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">MP-5 (4)</td>
    <td class="tg-baqh">MP-5 (4)</td>
  </tr>
  <tr>
    <td class="tg-0lax">MP-6</td>
    <td class="tg-0lax">Media Sanitization</td>
    <td class="tg-baqh">MP-6</td>
    <td class="tg-baqh">MP-6 (2)</td>
    <td class="tg-baqh">MP-6 (1) (2) (3)</td>
  </tr>
  <tr>
    <td class="tg-0lax">MP-7</td>
    <td class="tg-0lax">Media Use</td>
    <td class="tg-baqh">MP-7</td>
    <td class="tg-baqh">MP-7 (1)</td>
    <td class="tg-baqh">MP-7 (1)</td>
  </tr>
  <tr>
    <td class="tg-abx8">PE</td>
    <td class="tg-abx8" colspan="4">Physical and Environmental Protection</td>
  </tr>
  <tr>
    <td class="tg-0lax">PE-1</td>
    <td class="tg-0lax">Physical and Environmental Protection Policy and Procedures</td>
    <td class="tg-baqh">PE-1</td>
    <td class="tg-baqh">PE-1</td>
    <td class="tg-baqh">PE-1</td>
  </tr>
  <tr>
    <td class="tg-0lax">PE-2</td>
    <td class="tg-0lax">Physical Access Authorizations</td>
    <td class="tg-baqh">PE-2</td>
    <td class="tg-baqh">PE-2</td>
    <td class="tg-baqh">PE-2</td>
  </tr>
  <tr>
    <td class="tg-0lax">PE-3</td>
    <td class="tg-0lax">Physical Access Control</td>
    <td class="tg-baqh">PE-3</td>
    <td class="tg-baqh">PE-3</td>
    <td class="tg-baqh">PE-3 (1)</td>
  </tr>
  <tr>
    <td class="tg-0lax">PE-4</td>
    <td class="tg-0lax">Access Control for Transmission Medium</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">PE-4</td>
    <td class="tg-baqh">PE-4</td>
  </tr>
  <tr>
    <td class="tg-0lax">PE-5</td>
    <td class="tg-0lax">Access Control for Output Devices</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">PE-5</td>
    <td class="tg-baqh">PE-5</td>
  </tr>
  <tr>
    <td class="tg-0lax">PE-6</td>
    <td class="tg-0lax">Monitoring Physical Access</td>
    <td class="tg-baqh">PE-6</td>
    <td class="tg-baqh">PE-6 (1)</td>
    <td class="tg-baqh">PE-6 (1) (4)</td>
  </tr>
  <tr>
    <td class="tg-0lax">PE-8</td>
    <td class="tg-0lax">Visitor Access Records</td>
    <td class="tg-baqh">PE-8</td>
    <td class="tg-baqh">PE-8</td>
    <td class="tg-baqh">PE-8 (1)</td>
  </tr>
  <tr>
    <td class="tg-0lax">PE-9</td>
    <td class="tg-0lax">Power Equipment and Cabling</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">PE-9</td>
    <td class="tg-baqh">PE-9</td>
  </tr>
  <tr>
    <td class="tg-0lax">PE-10</td>
    <td class="tg-0lax">Emergency Shutoff</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">PE-10</td>
    <td class="tg-baqh">PE-10</td>
  </tr>
  <tr>
    <td class="tg-0lax">PE-11</td>
    <td class="tg-0lax">Emergency Power</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">PE-11</td>
    <td class="tg-baqh">PE-11 (1)</td>
  </tr>
  <tr>
    <td class="tg-0lax">PE-12</td>
    <td class="tg-0lax">Emergency Lighting</td>
    <td class="tg-baqh">PE-12</td>
    <td class="tg-baqh">PE-12</td>
    <td class="tg-baqh">PE-12</td>
  </tr>
  <tr>
    <td class="tg-0lax">PE-13</td>
    <td class="tg-0lax">Fire Protection</td>
    <td class="tg-baqh">PE-13</td>
    <td class="tg-baqh">PE-13 (2) (3)</td>
    <td class="tg-baqh">PE-13 (1) (2) (3)</td>
  </tr>
  <tr>
    <td class="tg-0lax">PE-14</td>
    <td class="tg-0lax">Temperature and Humidity Controls</td>
    <td class="tg-baqh">PE-14</td>
    <td class="tg-baqh">PE-14 (2)</td>
    <td class="tg-baqh">PE-14 (2)</td>
  </tr>
  <tr>
    <td class="tg-0lax">PE-15</td>
    <td class="tg-0lax">Water Damage Protection</td>
    <td class="tg-baqh">PE-15</td>
    <td class="tg-baqh">PE-15</td>
    <td class="tg-baqh">PE-15 (1)</td>
  </tr>
  <tr>
    <td class="tg-0lax">PE-16</td>
    <td class="tg-0lax">Delivery and Removal</td>
    <td class="tg-baqh">PE-16</td>
    <td class="tg-baqh">PE-16</td>
    <td class="tg-baqh">PE-16</td>
  </tr>
  <tr>
    <td class="tg-0lax">PE-17</td>
    <td class="tg-0lax">Alternate Work Site</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">PE-17</td>
    <td class="tg-baqh">PE-17</td>
  </tr>
  <tr>
    <td class="tg-0lax">PE-18</td>
    <td class="tg-0lax">Location of Information System Components</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">PE-18</td>
  </tr>
  <tr>
    <td class="tg-abx8">PL</td>
    <td class="tg-abx8" colspan="4">Planning</td>
  </tr>
  <tr>
    <td class="tg-0lax">PL-1</td>
    <td class="tg-0lax">Security Planning Policy and Procedures</td>
    <td class="tg-baqh">PL-1</td>
    <td class="tg-baqh">PL-1</td>
    <td class="tg-baqh">PL-1</td>
  </tr>
  <tr>
    <td class="tg-0lax">PL-2</td>
    <td class="tg-0lax">System Security Plan</td>
    <td class="tg-baqh">PL-2</td>
    <td class="tg-baqh">PL-2 (3)</td>
    <td class="tg-baqh">PL-2 (3)</td>
  </tr>
  <tr>
    <td class="tg-0lax">PL-4</td>
    <td class="tg-0lax">Rules of Behavior</td>
    <td class="tg-baqh">PL-4</td>
    <td class="tg-baqh">Pl-4 (1)</td>
    <td class="tg-baqh">PL-4 (1)</td>
  </tr>
  <tr>
    <td class="tg-0lax">PL-8</td>
    <td class="tg-0lax">Information Security Architecture</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">PL-8</td>
    <td class="tg-baqh">PL-8</td>
  </tr>
  <tr>
    <td class="tg-abx8">PS</td>
    <td class="tg-abx8" colspan="4">Personnel Security</td>
  </tr>
  <tr>
    <td class="tg-0lax">PS-1</td>
    <td class="tg-0lax">Personnel Security Policy and Procedures</td>
    <td class="tg-baqh">PS-1</td>
    <td class="tg-baqh">PS-1</td>
    <td class="tg-baqh">PS-1</td>
  </tr>
  <tr>
    <td class="tg-0lax">PS-2</td>
    <td class="tg-0lax">Position Risk Designation</td>
    <td class="tg-baqh">PS-2</td>
    <td class="tg-baqh">PS-2</td>
    <td class="tg-baqh">PS-2</td>
  </tr>
  <tr>
    <td class="tg-0lax">PS-3</td>
    <td class="tg-0lax">Personnel Screening</td>
    <td class="tg-baqh">PS-3</td>
    <td class="tg-baqh">PS-3 (3)</td>
    <td class="tg-baqh">PS-3 (3)</td>
  </tr>
  <tr>
    <td class="tg-0lax">PS-4</td>
    <td class="tg-0lax">Personnel Termination</td>
    <td class="tg-baqh">PS-4</td>
    <td class="tg-baqh">PS-4</td>
    <td class="tg-baqh">PS-4 (2)</td>
  </tr>
  <tr>
    <td class="tg-0lax">PS-5</td>
    <td class="tg-0lax">Personnel Transfer</td>
    <td class="tg-baqh">PS-5</td>
    <td class="tg-baqh">PS-5</td>
    <td class="tg-baqh">PS-5</td>
  </tr>
  <tr>
    <td class="tg-0lax">PS-6</td>
    <td class="tg-0lax">Access Agreements</td>
    <td class="tg-baqh">PS-6</td>
    <td class="tg-baqh">PS-6</td>
    <td class="tg-baqh">PS-6</td>
  </tr>
  <tr>
    <td class="tg-0lax">PS-7</td>
    <td class="tg-0lax">Third-Party Personnel Security</td>
    <td class="tg-baqh">PS-7</td>
    <td class="tg-baqh">PS-7</td>
    <td class="tg-baqh">PS-7</td>
  </tr>
  <tr>
    <td class="tg-0lax">PS-8</td>
    <td class="tg-0lax">Personnel Santions</td>
    <td class="tg-baqh">PS-8</td>
    <td class="tg-baqh">PS-8</td>
    <td class="tg-baqh">PS-8</td>
  </tr>
  <tr>
    <td class="tg-abx8">RA</td>
    <td class="tg-abx8" colspan="4">Risk Assessment</td>
  </tr>
  <tr>
    <td class="tg-0lax">RA-1</td>
    <td class="tg-0lax">Risk Assessment Policy and Procedures</td>
    <td class="tg-baqh">RA-1</td>
    <td class="tg-baqh">RA-1</td>
    <td class="tg-baqh">RA-1</td>
  </tr>
  <tr>
    <td class="tg-0lax">RA-2</td>
    <td class="tg-0lax">Security Categorization</td>
    <td class="tg-baqh">RA-2</td>
    <td class="tg-baqh">RA-2</td>
    <td class="tg-baqh">RA-2</td>
  </tr>
  <tr>
    <td class="tg-0lax">RA-3</td>
    <td class="tg-0lax">Risk Assessment</td>
    <td class="tg-baqh">RA-3</td>
    <td class="tg-baqh">RA-3</td>
    <td class="tg-baqh">RA-3</td>
  </tr>
  <tr>
    <td class="tg-0lax">RA-5</td>
    <td class="tg-0lax">Vulnerability Scanning</td>
    <td class="tg-baqh">RA-5</td>
    <td class="tg-baqh">RA-5 (1) (2) (3) (5) (6) (8)</td>
    <td class="tg-baqh">RA-5 (1) (2) (3) (4) (5) (6) (8) (10)</td>
  </tr>
  <tr>
    <td class="tg-abx8">SA</td>
    <td class="tg-abx8" colspan="4">System and Services Acquisition</td>
  </tr>
  <tr>
    <td class="tg-0lax">SA-1</td>
    <td class="tg-0lax">System and Services Acquisition Policy and Procedures</td>
    <td class="tg-baqh">SA-1</td>
    <td class="tg-baqh">SA-1</td>
    <td class="tg-baqh">SA-1</td>
  </tr>
  <tr>
    <td class="tg-0lax">SA-2</td>
    <td class="tg-0lax">Allocation of Resources</td>
    <td class="tg-baqh">SA-2</td>
    <td class="tg-baqh">SA-2</td>
    <td class="tg-baqh">SA-2</td>
  </tr>
  <tr>
    <td class="tg-0lax">SA-3</td>
    <td class="tg-0lax">System Development Life Cycle</td>
    <td class="tg-baqh">SA-3</td>
    <td class="tg-baqh">SA-3</td>
    <td class="tg-baqh">SA-3</td>
  </tr>
  <tr>
    <td class="tg-0lax">SA-4</td>
    <td class="tg-0lax">Acquisition Process</td>
    <td class="tg-baqh">SA-4 (10)</td>
    <td class="tg-baqh">SA-4 (1) (2) (8) (9) (10)</td>
    <td class="tg-baqh">SA-4 (1) (2) (8) (9) (10)</td>
  </tr>
  <tr>
    <td class="tg-0lax">SA-5</td>
    <td class="tg-0lax">Information System Documentation</td>
    <td class="tg-baqh">SA-5</td>
    <td class="tg-baqh">SA-5</td>
    <td class="tg-baqh">SA-5</td>
  </tr>
  <tr>
    <td class="tg-0lax">SA-8</td>
    <td class="tg-0lax">Security Engineering Principles</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">SA-8</td>
    <td class="tg-baqh">SA-8</td>
  </tr>
  <tr>
    <td class="tg-0lax">SA-9</td>
    <td class="tg-0lax">External Information System Services</td>
    <td class="tg-baqh">SA-9</td>
    <td class="tg-baqh">SA-9 (1) (2) (4) (5)</td>
    <td class="tg-baqh">SA-9 (1) (2) (4) (5)</td>
  </tr>
  <tr>
    <td class="tg-0lax">SA-10</td>
    <td class="tg-0lax">Developer Configuration Management</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">SA-10 (1)</td>
    <td class="tg-baqh">SA-10 (1)</td>
  </tr>
  <tr>
    <td class="tg-0lax">SA-11</td>
    <td class="tg-0lax">Developer Security Testing and Evaluation</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">SA-11 (1) (2) (8)</td>
    <td class="tg-baqh">SA-11 (1) (2) (8)</td>
  </tr>
  <tr>
    <td class="tg-0lax">SA-12</td>
    <td class="tg-0lax">Supply Chain Protection</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">SA-12</td>
  </tr>
  <tr>
    <td class="tg-0lax">SA-15</td>
    <td class="tg-0lax">Development Process, Standards and Tools</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">SA-15</td>
  </tr>
  <tr>
    <td class="tg-0lax">SA-17</td>
    <td class="tg-0lax">Developer Security Architecture and Design</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">SA-17</td>
  </tr>
  <tr>
    <td class="tg-abx8">SC</td>
    <td class="tg-abx8" colspan="4">System and Communications Protection</td>
  </tr>
  <tr>
    <td class="tg-0lax">SC-1</td>
    <td class="tg-0lax">System and Communications Protection Policy and Procedures</td>
    <td class="tg-baqh">SC-1</td>
    <td class="tg-baqh">SC-1</td>
    <td class="tg-baqh">SC-1</td>
  </tr>
  <tr>
    <td class="tg-0lax">SC-2</td>
    <td class="tg-0lax">Application Partitioning</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">SC-2</td>
    <td class="tg-baqh">SC-2</td>
  </tr>
  <tr>
    <td class="tg-0lax">SC-3</td>
    <td class="tg-0lax">Security Function Isolation</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">SC-3</td>
  </tr>
  <tr>
    <td class="tg-0lax">SC-4</td>
    <td class="tg-0lax">Information In Shared Resources</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">SC-4</td>
    <td class="tg-baqh">SC-4</td>
  </tr>
  <tr>
    <td class="tg-0lax">SC-5</td>
    <td class="tg-0lax">Denial of Service Protection</td>
    <td class="tg-baqh">SC-5</td>
    <td class="tg-baqh">SC-5</td>
    <td class="tg-baqh">SC-5</td>
  </tr>
  <tr>
    <td class="tg-0lax">SC-6</td>
    <td class="tg-0lax">Resource Availability</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">SC-6</td>
    <td class="tg-baqh">SC-6</td>
  </tr>
  <tr>
    <td class="tg-0lax">SC-7</td>
    <td class="tg-0lax">Boundary Protection</td>
    <td class="tg-baqh">SC-7</td>
    <td class="tg-baqh">SC-7 (3) (4) (5) (7) (8) (12) (13) (18)</td>
    <td class="tg-baqh">SC-7 (3) (4) (5) (7) (8) (10) (12) (13) (18) (20) (21)</td>
  </tr>
  <tr>
    <td class="tg-0lax">SC-8</td>
    <td class="tg-0lax">Transmission Confidentiality and Integrity</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">SC-8 (1)</td>
    <td class="tg-baqh">SC-8 (1)</td>
  </tr>
  <tr>
    <td class="tg-0lax">SC-10</td>
    <td class="tg-0lax">Network Disconnect</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">SC-10</td>
    <td class="tg-baqh">SC-10</td>
  </tr>
  <tr>
    <td class="tg-0lax">SC-12</td>
    <td class="tg-0lax">Cryptographic Key Establishment and Management</td>
    <td class="tg-baqh">SC-12</td>
    <td class="tg-baqh">SC-12 (2) (3)</td>
    <td class="tg-baqh">SC-12 (1) (2) (3)</td>
  </tr>
  <tr>
    <td class="tg-0lax">SC-13</td>
    <td class="tg-0lax">Cryptographic Protection</td>
    <td class="tg-baqh">SC-13</td>
    <td class="tg-baqh">SC-13</td>
    <td class="tg-baqh">SC-13</td>
  </tr>
  <tr>
    <td class="tg-0lax">SC-15</td>
    <td class="tg-0lax">Collaborative Computing Devices</td>
    <td class="tg-baqh">SC-15</td>
    <td class="tg-baqh">SC-15</td>
    <td class="tg-baqh">SC-15</td>
  </tr>
  <tr>
    <td class="tg-0lax">SC-17</td>
    <td class="tg-0lax">Public Key Infrastructure Certificates</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">SC-17</td>
    <td class="tg-baqh">SC-17</td>
  </tr>
  <tr>
    <td class="tg-0lax">SC-18</td>
    <td class="tg-0lax">Mobile Code</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">SC-18</td>
    <td class="tg-baqh">SC-18</td>
  </tr>
  <tr>
    <td class="tg-0lax">SC-19</td>
    <td class="tg-0lax">Voice Over Internet Protocol</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">SC-19</td>
    <td class="tg-baqh">SC-19</td>
  </tr>
  <tr>
    <td class="tg-0lax">SC-20</td>
    <td class="tg-0lax">Secure Name / Address Resolution Service (Authoritative Source)</td>
    <td class="tg-baqh">SC-20</td>
    <td class="tg-baqh">SC-20</td>
    <td class="tg-baqh">SC-20</td>
  </tr>
  <tr>
    <td class="tg-0lax">SC-21</td>
    <td class="tg-0lax">Secure Name / Address Resolution Service (Recursive or Caching Resolver)</td>
    <td class="tg-baqh">SC-21</td>
    <td class="tg-baqh">SC-21</td>
    <td class="tg-baqh">SC-21</td>
  </tr>
  <tr>
    <td class="tg-0lax">SC-22</td>
    <td class="tg-0lax">Architecture and Provisioning for Name / Address Resolution Service</td>
    <td class="tg-baqh">SC-22</td>
    <td class="tg-baqh">SC-22</td>
    <td class="tg-baqh">SC-22</td>
  </tr>
  <tr>
    <td class="tg-0lax">SC-23</td>
    <td class="tg-0lax">Session Authenticity</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">SC-23</td>
    <td class="tg-baqh">SC-23 (1)</td>
  </tr>
  <tr>
    <td class="tg-0lax">SC-24</td>
    <td class="tg-0lax">Fail in Known State</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">SC-24</td>
  </tr>
  <tr>
    <td class="tg-0lax">SC-28</td>
    <td class="tg-0lax">Protection of Information at Rest</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">SC-28 (1)</td>
    <td class="tg-baqh">SC-28 (1)</td>
  </tr>
  <tr>
    <td class="tg-0lax">SC-39</td>
    <td class="tg-0lax">Process Isolation</td>
    <td class="tg-baqh">SC-39</td>
    <td class="tg-baqh">SC-39</td>
    <td class="tg-baqh">SC-39</td>
  </tr>
  <tr>
    <td class="tg-abx8">SI</td>
    <td class="tg-abx8" colspan="4">System and Information Integrity</td>
  </tr>
  <tr>
    <td class="tg-0lax">SI-1</td>
    <td class="tg-0lax">System and Information Integrity Policy and Procedures</td>
    <td class="tg-baqh">SI-1</td>
    <td class="tg-baqh">SI-1</td>
    <td class="tg-baqh">SI-1</td>
  </tr>
  <tr>
    <td class="tg-0lax">SI-2</td>
    <td class="tg-0lax">Flaw Remediation</td>
    <td class="tg-baqh">SI-2</td>
    <td class="tg-baqh">SI-2 (2) (3)</td>
    <td class="tg-baqh">SI-2 (1) (2) (3)</td>
  </tr>
  <tr>
    <td class="tg-0lax">SI-3</td>
    <td class="tg-0lax">Malicious Code Protection</td>
    <td class="tg-baqh">SI-3</td>
    <td class="tg-baqh">SI-3 (1) (2) (7)</td>
    <td class="tg-baqh">SI-3 (1) (2) (7)</td>
  </tr>
  <tr>
    <td class="tg-0lax">SI-4</td>
    <td class="tg-0lax">Information System Monitoring</td>
    <td class="tg-baqh">SI-4</td>
    <td class="tg-baqh">SI-4 (1) (2) (4) (5) (14) (16) (23)</td>
    <td class="tg-baqh">SI-4 (1) (2) (4) (5) (11) (14) (16) (18) (19) (20) (22) (23) (24)</td>
  </tr>
  <tr>
    <td class="tg-0lax">SI-5</td>
    <td class="tg-0lax">Security Alerts, Advisories and Directives</td>
    <td class="tg-baqh">SI-5</td>
    <td class="tg-baqh">SI-5</td>
    <td class="tg-baqh">SI-5 (1)</td>
  </tr>
  <tr>
    <td class="tg-0lax">SI-6</td>
    <td class="tg-0lax">Security Function Verification</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">SI-6</td>
    <td class="tg-baqh">SI-6</td>
  </tr>
  <tr>
    <td class="tg-0lax">SI-7</td>
    <td class="tg-0lax">Software, Firmware and Information Integrity</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">SI-7 (1) (7)</td>
    <td class="tg-baqh">SI-7 (1) (2) (5) (7) (14)</td>
  </tr>
  <tr>
    <td class="tg-0lax">SI-8</td>
    <td class="tg-0lax">Spam Protection</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">SI-8 (1) (2)</td>
    <td class="tg-baqh">SI-8 (1) (2)</td>
  </tr>
  <tr>
    <td class="tg-0lax">SI-10</td>
    <td class="tg-0lax">Information Input Validation</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">SI-10</td>
    <td class="tg-baqh">SI-10</td>
  </tr>
  <tr>
    <td class="tg-0lax">SI-11</td>
    <td class="tg-0lax">Error Handling</td>
    <td class="tg-baqh">Not Selected</td>
    <td class="tg-baqh">SI-11</td>
    <td class="tg-baqh">SI-11</td>
  </tr>
  <tr>
    <td class="tg-0lax">SI-12</td>
    <td class="tg-0lax">Information Handling and Retention</td>
    <td class="tg-baqh">SI-12</td>
    <td class="tg-baqh">SI-12</td>
    <td class="tg-baqh">SI-12</td>
  </tr>
  <tr>
    <td class="tg-0lax">SI-16</td>
    <td class="tg-0lax">Memory Protection</td>
    <td class="tg-baqh">SI-16</td>
    <td class="tg-baqh">SI-16</td>
    <td class="tg-baqh">SI-16</td>
  </tr>
</table>

The definitions in the table below indicate where each security control originates.


| Control Origination | Definition | Example |
|:--------------------|:-----------|:--------|
| Service Provider Corporate | A control that originates from the Red Hat corporate network. | DNS from the Red Hat corporate network provides address resolution services for the information system and service offering. |
| Service Provider System Specific | A control specific to a particular system at Red Hat and the control is not part of the standard corporate controls. | A unique host-based intrusion detection system (HIDS) is available on the service offering platform but is not available on the corporate network. |
| Service Provider Hybrid | A control that makes use of both corporate controls and additional controls specific to a particular system at Red Hat. | There are scans of the corporate network infrastructure; scans of databases and web-based application are system specific. |
| Configured by Customer | A control where the customer needs to apply a configuration in order to meet the control requirement. | User profiles, policy/audit configurations, enabling/disabling key switches (e.g., enable/disable http or https, etc), entering an IP range specific to their organization are configurable by the customer. |
| Provided by Customer | A control where the customer needs to provide additional hardware or software in order to meet the control requirement. | The customer provides a SAML SSO solution to implement two-factor authentication. | 
| Shared | A control that is managed and implemented partially by Red hat and partially by the customer. | Security awareness training must be conducted by both Red Hat and the customer. |
| Inherited from pre-existing FedRAMP Authorization | A control that is inherited from another Red Hat system that has already received a RedRAMP Authorization. | A PaaS or SaaS provider inherits PE controls from an IaaS provider. |