# The Planning Phase

### Defining The Audit Scope

**Scope**

Prior to the engagement with an auditing firm or service auditor. The management at the service organization should have properly defined the system scope. However, with smaller organizations, that is not always the case. This is where part of your responsibilities as a Lead Implementer or consultant will come into play.

**Let's review the following basic responsibilities when determining scope;**

1. Identification of services provided to customers
2. Identification of system(s) used to provide services
3. Identification of business partners or consultants that provide copyrights, patents or Intellectual property or services to the system(s)
4. Defining and selecting the Trust Services Categories to be included in the scope of attestation.
5. Defining if the organization should undergo a Type I or Type II SOC 2 audit.
6. Defining the "As of Date" as notated for a SOC 2 Type 1 Report
7. Determining if sub-service organizations/sub-level services are a part of the overall system and if they need to be included in the attestation report.
8. Identifying and analyzing risks that hinder a service organization from its service commitments of defined SLA's.
9. Obtaining system-level requirements as they relate to business partners.

The list above is a great reference when assisting customers on their journey through the SOC 2 audit process. Please notate it and use it as a reference when working with customers. Now that you have an understanding of basic requirements for defining the system scope. Let's take a closer look at sub-service organizations, and what they are.





It is important to note that when defining the scope of a system you as a lead implementor or consultant will look to see what “pieces of the puzzle” the system is made of. This will have a profound impact on the types of controls that you help design and implement for an organization.

Once you have a solid understanding of the system scope and the pieces of the puzzle, it's best to get confirmation from the organization's management team that all sub-level service organizations have been identified and are listed as in scope for the audit. It is also important to verify with management on whether these sub services would be included in the attestation report or will a carve-out method be used. Should it be the latter, then it should be clearly specified in section 1 of the report that all controls relating to the sub-service organization will be excluded.

The next steps in the audit scoping process would be to sit down and map out what controls types if any sub-level organizations would fall under. An example of this would be controls for availability. Most of the time when evaluating cloud services controls that deal with availability will fall under the cloud hosting providers, such as Amazon AWS, Google Cloud, and Microsoft Azure. However, it will be the organizations' responsibility to ensure that these configurations and processes are put into place.

### **Creation of the System Description**

**What is the system description?**

The system description is a document that describes the business environment in which the controls are designed and implemented.. The description documents the people, processes, technologies, and accompanying controls for the organization. Think of this similar to a network architecture diagram, but with no diagrams and a lot of reading regarding the organizations' structure, processes, and controls. The system description is intended to provide users with information about the system, particularly system controls intended to meet the criteria: security, availability, processing integrity, confidentiality, and privacy.

**System description**

The system description encompasses the following; infrastructure, applications, services, and people that make up the platform. Including the sub-level organizations that were identified previously.

**Section III**

Within the overall report produced by the auditors, they will oftentimes refer to what is known as section three of the report. This is essentially the system description that has been written by the organization and the defined scope the auditor(s) have audited against.

The section III portion of the SOC 2 report should be written by the organizations' management team with the lead implementer or consultant ensuring that it gets completed by the specified project date. Each department within the organization will most likely have a small subsection within the report. This would include but is not limited to; Human Resources, Information Security, Engineering and Development Teams, Operations, and Support. If you would like assistance with writing this section.

**Management's Approval**

Depending on how the project has been scoped and the personnel involved. Once the Section III report or “System Description” has been created. It will be the responsibility of the consultant or lead implementer to have the management team review and approve the Section III outline. The system description can start to be worked on once a defined scope has been identified and set with the auditing team.

### **Types of Controls**

As a lead Implementer when designing controls you first must understand what the control is trying to accomplish. You then have to determine what type of control is being put into place based upon the requirements from the SOC 2 Control. First, let's take a look at the three different types of controls.

**Internal Auditing Controls**

1. Detective
2. Preventative
3. Corrective

**Detective Control** - Controls that alert employees to an action. ie, Log Monitoring with Alerts, Data leak Prevention, Intrusion Detection System.

**Preventative Control** - Controls used to help prevent certain events from occurring. ie, Example - A signature is required before an employee spends over 2,000.00 dollars on a service or equipment.

**Corrective Control** - Control that takes corrective action based upon an event that occurred. For Example, the DevOps team developed a script to spin up in a new region if their current region goes down.

**Compensating control**

A compensating control is when a process or technology is deficient and would require enormous changes, or it would be very costly for the organization to remediate.

Oftentimes compensating controls are used more to assist information systems and IT processes, rather than business processes. It's important to understand what controls are, and the different types that can be implemented.

Oftentimes technologies such as anti-malware will encompass all three control types especially with newer systems such as Carbon Black and CrowdStrike that have a machine learning backend.

### **Gap Analysis**

The gap analysis is a forward-looking review of the organization's controls and processes, that seeks to identify where there are shortcomings or subpar implementations that could result in security flaws, regulatory non-compliance or simply non-adherence to business and control environment best practices.

The gap analysis process is a forward-looking exercise. The current implementation of the process is examined, identifying any areas of concerns, and then a corrective action plan is drafted up, reviewed, agreed upon, and approved in order to provide guidance for how to remediate the identified gaps.

It is important to note that when performing a gap analysis for SOC 2, the organization should set out to identify any gaps based on the relevant TSC for the scoping criteria relevant to the audit in particular. In order to successfully achieve this, the lead implementer should identify all controls and processes relevant to the organization (based on the TSC scope relevant to the audit) and then perform a line-by-line review of this to identify any relevant gaps.Successfully performing the gap analysis process will set up the organization for SOC 2 success.

### **Identifying Gaps and Remediation**

As mentioned, the gap analysis is a forward-looking, ongoing process. It should identify all relevant controls to the organization for the audit, evaluate the current operational processes and controls, identify where deficiencies exist, and provide clear, realistic guidance for resolving all focus areas.

The lead implementer should include all relevant parties for the gap analysis process in order to have an accurate understanding of the organizational controls and processes. The process should include inquiry, walkthroughs, etc, in order to have a precise understanding of the necessary controls and processes. It is also important that all relevant parties are involved in order to establish accountability for the implementation in order to resolve these gaps.

Gap remediation should be prioritized according to the impact of the gap on the organization and its security in particular, as well as based on the benefit to the organization (by resolving this deficiency).Time lines need to be established in order to maintain appropriate resolution of gaps as well as to provide feedback to any stakeholders regarding the improvement and forward-looking plans for the organization.

### **Creation and Mapping of Controls**

You as a lead implementer or consultant will be responsible for leading the organization through a successful audit. As part of that criteria, sometimes you will need to assist organizations on mapping out controls that are currently in place to a point of focus that is mapped to a common criteria.

Have it be a business process, technical control, IT General Control or one of the three types of internal auditing controls we discussed previously. Let's first review the types of internal auditing controls along with an additional control type we discussed.

**They are as follows; Internal Auditing Controls**

1. Detective Control
2. Preventative Control
3. Corrective Control
4. Compensating Control

After the scoping period which should have already occurred, you will have a better understanding of what the organization is using for technology, their processes, and the people that make up those processes.

It is now your duty to start designing controls based upon the Gap Analysis / Risk Assessment that was previously performed. To do this, you will take the Gaps that should be aligned with the Common Criteria and review the Points of focus associated with each component. This will provide you with an understanding of what the intended control you develop should accomplish.

### **Choosing the Auditing Firm**

**What to look for**

It's important for organizations when looking for an auditor that, they pick a firm with a proven track record of successful attestations. Often times its best to interview at least three different auditing firms.

**Size Matters**

Depending on the size of your organization it's best to start your search locally. Many times there is a local auditing firm that can provide the same if not better results than large firms that have many clients.

**Personality types**

You as a lead implementer or consultant for the organization will be working hand in hand with the auditing team. During the selection phase it's important to get to know their personalities. Ask yourself, can I envision myself working with this auditor in a continuous audit engagement.

**Previous attestations and recommendations**

Prior to selection, it's always nice to review your auditors' work from previous engagements. Ask them about controls they have found not suitably designed. For example, you could ask the auditor(s) the following questions.

1. How did you report on a control that you found not suitably designed and not operating effectively.
2. Did you assist the client with recommendations regarding how to fix the control?
3. What is the most common occurrence you see during the audit engagement that clients fail to understand?
4. Ask the potential auditor if they can provide a list of contacts so you can make a reference check.
5. Ask them about their sampling methodology to ensure it is in line with best practice.
6. Ask the relevant audit manager, how many SOC 2 attestation he/she has performed.

**Communication Style**

Communication style is important. Everyone communicates differently and when running point one a SOC 2 project for an organization. It's imperative that the communication barrier is broken down. You as a lead implementer for the organization will need to communicate with the organization as well as the auditors.&#x20;



You will need to translate the requirements to the business and then help communicate those findings back to the auditors. Ensuring to do it from their perspective.
