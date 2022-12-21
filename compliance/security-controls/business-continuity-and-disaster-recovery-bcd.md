---
cover: ../../.gitbook/assets/Business Continuity and Disaster Recovery.png
coverY: 0
---

# Business Continuity and Disaster Recovery (BCD)

## Purpose <a href="#purpose" id="purpose"></a>

Maintains the capability to sustain business-critical functions while successfully responding to and recovering from incidents through a well-documented and exercised process to help recover from adverse situations with the minimal impact to operations, as well as provide the ability for e-discovery.

## Scope <a href="#scope" id="scope"></a>

The business continuity and disaster recovery plan is comprehensive by nature and will impact all stakeholders. The scope of Business Continuity & Disaster Recovery Plan will cover:

* BC/DR plan for \<Environment>
* Processes and procedures that support business operations and above environments

## Ownership <a href="#ownership" id="ownership"></a>

* Business Operations owns this control.
* Infrastructure will provide implementation support for all of the above mentioned sites and owns the backup configuration 100%. They are responsible to run both app snapshots and database backups.

## Controls <a href="#controls" id="controls"></a>

### Business Continuity Management System (BCMS)

**Control Statement:** Has implemented mechanisms to facilitate contingency planning security controls to help ensure resilient assets and services.

**Goal:** Does the organization facilitate the implementation of contingency planning controls?

**Test of Design**

1. Identify formal policies, procedures or other relevant documentation that outline  mechanisms to facilitate contingency planning. Including but not limited to: communication, roles and responsibilities, business continuity, recovery, insurance, incident response and incident reporting.
2. Interview key organizational personnel  to discuss high level workflows that support the facilitation of the organizational level contingency plan.
3. Examine policies and procedures for: purpose; scope; roles and responsibilities; management commitment; coordination among organizational entities; compliance; and implementation requirements.

**Test of Operating Effectiveness**

1. Examine organizational contingency planning policy and procedures or other relevant documents to support the facilitation of contingency planning protocols.
2. Examine security controls as they relate to contingency planning for evidence that security controls facilitate implementation and adherence of contingency plans to help ensure resilient assets and services.



### Identify Critical Assets

**Control Statement:** Has established mechanisms to identify, document and resume the critical systems, applications and services that support essential missions and business processes within Recovery Time Objectives (RTOs) with little or no loss of operational continuity of the defined time period of the contingency plan’s activation.

**Goal:** Does the organization identify and document the critical systems, applications and services that support essential missions and business functions?

**Test of Design**

* Inspect formal policies, procedures or other relevant documentation that outline Recovery Time Objectives (RTO), restoration priorities and metrics to resume all missions and business functions, essential mission and business functions and continue essential mission and business functions.

**Test of Operating Effectiveness**

* Examine associated policies and procedures as outlined in the TOD for evidence the critical systems, applications and services list that support essential missions and business functions is included as part of contingency plan documentation and activation procedures.



### Contingency Plan Testing & Exercises

**Control Statement:**  Has implemented mechanisms to conduct tests and/or exercises to determine the contingency plan’s effectiveness and the organization’s readiness to execute the plan.

**Goal:** Does the organization conduct tests and/or exercises to determine the contingency plan's effectiveness and the organization’s readiness to execute the plan?

****

**Test of Design**

* Examine contingency planning policy and procedures addressing contingency plan testing and/or exercises results for evidence that the measures identified determine the contingency plan’s effectiveness and  readiness to execute the plan.

**Test of Operating Effectiveness**

1. Pull a population of all contingency plan tests and/or exercises during the examination period.
2. Examine results for a sample selection of contingency plan tests/exercises conducted to determine if the contingency plans effectiveness and organization’s readiness to execute the plan were taken into account.



### Contingency Plan Root Cause Analysis (RCA) & Lessons Learned

**Control Statement:**  Has implemented mechanisms to conduct Root Cause Analysis (RCA) and “lessons learned” activity every the contingency plan is activated.

**Goal:**  Does the organization conduct a Root Cause Analysis (RCA) and "lessons learned" activity every time the contingency plan is activated?

**Test of Design**

* Examine contingency planning policies, procedures or other relevant documentation that outline contingency planning Root Cause Analysis (RCA) and lessons learned requirements each time the contingency plan is activated.

**Test of Operating Effectiveness**





### Contingency Planning & Updates

**Control Statement:  H**as established mechanisms to keep contingency plans current with business requirements and technology changes.

**Goal:** Does the organization keep contingency plans current with business needs and technology changes?

**Test of Design**

* Examine contingency planning policies, procedures and other relevant documents for the measures to be employed to ensure contingency plans are current with business requirements and technology changes as well as frequency and documentation of review.

**Test of Operating Effectiveness**





### Alternative Security Measures

**Control Statement:**  Has implemented alternative or compensating controls to satisfy security requirements when the primary means of implementing the security requirements is unavailable or compromised.

**Goal:** Does the organization implement alternative or compensating controls to satisfy security functions when the primary means of implementing the security function is unavailable or compromised?

**Test of Design**

* Examine contingency planning policies, procedures or other relevant documentation that outline measures to support risk mitigation alternatives or compensating controls to satisfy security requirements when the primary means of implementing security requirements is unavailable or compromised.

**Test of Operating Effectiveness**

1. Examine alternative or compensating controls outlined in the contingency planning documentation for evidence that the measures identified support security requirements when the primary means of security requirements is unavailable or compromised.
2. Examine documentation or configurations describing continuous monitoring efforts for evidence that these mechanisms are configured to satisfy security requirements when primary means of implementing security requirements are unavailable or compromised.



### Data Backups

**Control Statement:**  Has implemented mechanisms to create and routinely test recurring backups of data, software and system images verifying the reliability of the backup process to ensure the integrity and availability of the data.

**Goal:** Does the organization create recurring backups of data, software and system images to ensure the availability of the data?

**Test of Design**

1. Inquire of appropriate personnel to determine the process for completing backups.
2. Inspect the (Backup policy, system evidence etc.) to determine the process for completing backups.

**Test of Operating Effectiveness**

1. According to the defined frequency of backups, select a sample of (days/weeks/months) and obtain evidence for the selected sample to determine if the backups were completed successfully.
2. In case of any failures, obtain and inspect documentation that the failure(s) was researched and resolved timely and in line with the backup policy.



### Information System Recovery & Reconstitution

**Control Statement:**  Has implemented mechanisms to ensure the recovery and restoration of systems to a known state after a disruption, compromise or failure.

**Goal:** Does the organization ensure the recovery and reconstitution of systems to a known state after a disruption, compromise or failure?

**Test of Design**

1. Inquire of appropriate personnel to determine the process for completing backup restoration tests from completed backups.
2. Inspect (Backup policy, Restoration guidance etc.) to determine the process for completing backups restoration tests.

**Test of Operating Effectiveness**

1. Obtain and inspect the results for the backup restoration test.
2. Review the results of the backup restoration test and the supporting documentation to validate that backups are completed appropriately and are available for restoration.
3. In case of any noted issues identified in the backup restoration test, validate that they have been resolved appropriately.



### Backup & Restoration Hardware Protection

**Control Statement:**  Has implemented mechanisms to protect backup and restoration of hardware and software.

**Goal:** Does the organization protect backup and restoration hardware and software?

**Test of Design**

* Examine security documentation for backup and restoration of hardware and software policies and procedures.

**Test of Operating Effectiveness**

1. Examine documentation for outlined automated or configured mechanisms settings to support the backup and restoration of hardware and software as outlined in the policies and procedures.
2. Pull a population of all hardware and software backups and restoration during the examination period.
3. Confirm hardware and software backup and restorations conducted during the examination period align with the automated or configured mechanism settings.
