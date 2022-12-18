# SOC 2

## Introduction

### **SOC Definition**

SOC Stands for Service Organization Controls (SOC). The controls that you design and implement inside your control environment will vary based upon the people, technology, and products your company develops. Service organizations have a responsibility to protect the customers data they collect as well as the products they develop and build. The customers of service organizations will rely greatly on ensuring the organization is providing a safe, secure, and reliable platform that customers utilize to help conduct business.You can think of the product or solutions organizations develop and provide, as a small piece of the puzzle to other organizations' infrastructure and operating procedures. Compile many of these services and they help a business operate and thrive.

### **Example**

For example, imagine a business that provides a SaaS solution that helps organizations onboard new employees and takes them through the onboarding process. This solution would collect personal information such as Names, Social Security Numbers, Telephones numbers, and email addresses. The product or service the organization provides needs to be implemented securely, and the organization's customers will want to ensure that the company is operating effectively while protecting their data.



### **AICPA COSO Framework**

\
**What is the COSO Framework?**

The COSO Framework is a framework for designing, implementing, and monitoring internal controls to be incorporated into business processes. Additionally, the framework provides a level of assurance that the organization is ethically sound, transparent in its operating procedures, and aligned with industry best practices.

\
**What makes up the framework?**

The framework consists of five different components. Along with three internal objectives.The three internal objectives that the COSO framework aims to achieve are the following

1. Operations Objectives
2. Reporting Objectives&#x20;
3. Compliance Objectives

\
**The five components that help achieve the objectives above are the following**

1. Control Environment
2. Risk Assessment
3. Control Activities
4. Information & Communication
5. Monitoring Activities

\
It’s important to note that the control environment is the scope of the environment where control activities are taking place. Oftentimes companies and auditors will limit the scope of the environment depending on the size of the organization and how the data is moved across the platform. This will then impact things such as risk assessments and control activities. \
Risk assessments should be actively taking place in the organization. This will include a subset of controls such as evaluating vendor risk and software vendors. In today's fast-paced business world security assessments often come in the form of a security questionnaire. Which is then evaluated by the business from a security perspective. Alternatively, businesses are also requesting attestation reports such as a SOC 2, or ISO 270001 report before deciding between vendors.  Monitoring activities come in the form of many different processes and procedures. However, with regards to SOC 2, there are two different types. Administrative, and technical. As we continue through this course you will start to see and notate the difference between administrative and technical controls. \
\
\
\


### **Trust Services Criteria and Points of Focus**

#### **What are Trust Service Criteria?**

The trust service criteria are the overall criteria that your organization will be audited on. The organization will have gone over the criteria beforehand with the auditor. Or if you're an auditor, you will go over the Trust Service Criteria with your client to ensure that a proper scope has been defined before the auditing period begins. The Trust Service Criteria are listed below.

* Security
* Availability
* Processing Integrity
* Confidentiality
* Privacy

When reviewing the trust services criteria it is important to note that not all of the trust service criteria have to be met in order to obtain a satisfactory SOC 2 report. However, the business has to meet the objectives that have been defined as part of the scope between the business and the auditing firm. Also at a minimum, the business will need to comply with the common criteria.

****

#### **Description of TSC**

**Security** - Ensuring that the information systems and data are protected against unauthorized access and disclosure. Also make sure that damage from malicious software doesn't impact your information systems to the extent that it would impact confidentiality, integrity, or availability. Also known as the CIA triad.

**Availability** - Ensuring that your Information Systems are operational during normal operating hours, and their intended use is not impacted by your organizations' processes.

**Processing Integrity** - The system or solution that has been developed, processes information correctly, in a timely manner, and encompasses proper authorization when doing so. Meaning proper access is defined and reports or data can not be accessed by a user who doesn't have the appropriate access rights.

**Confidentiality** - Information that has been classified as confidential is secure within the documented scope of Information systems and is free from tampering or misuse.

**Privacy** - Customer or personal information that is obtained, used, disclosed, or retained is properly obtained using legal methods; such as a DPA, Contract, Data sharing agreement. Also, the organization should have a policy and process in place for collection methods, and data deletion.

****

#### **Overview - Points of Focus**

Points of Focus are intended for you as a SOC implementor or consultant to help customers achieve controls that are suitable to their organization. You can think of points of focus like helpful hints, tips, and tricks in regards to what the control is trying to prevent, mitigate or detect. Additionally, organizations that are trying to achieve a SOC 2 attestation do not have to comply with all of the Points of Focus. It's important to understand that these are not requirements.

**Example**

Let's review several examples of point-of-focus statements.



<figure><img src="https://files.cdn.thinkific.com/file_uploads/628111/images/9c3/43a/8ad/1648647907062.jpg" alt=""><figcaption><p>Figure A.2</p></figcaption></figure>

When reviewing figure A.2 you can see how the trust service criteria, component of COSO (control environment), common criteria, and point of focus are laid out.



****

**Point of Focus Example**\


<figure><img src="https://files.cdn.thinkific.com/file_uploads/628111/images/5cc/40e/672/1648647907155.jpg" alt=""><figcaption><p>Figure A.3</p></figcaption></figure>

<figure><img src="https://files.cdn.thinkific.com/file_uploads/628111/images/98f/de0/74c/1648647908696.jpg" alt=""><figcaption><p>Figure A.4</p></figcaption></figure>

There are two points of focus mentioned above in figure A.4. They are the following;

1. Uses Defined Configuration Standards
2. Monitors Infrastructure and Software

\
Breaking down the points of focus. Using the scope that was defined early on in the audit engagement. You as a SOC 2 Lead Implementer should know what information systems and processes are in scope. The first point of focus talks about configuration management. This is talking about the configuration standards for the information systems that are in scope.The second point of focus is referring to infrastructure and monitoring of software. The organization should be monitoring for system outages or more specifically when the CIA triad is violated. The second part of this point of focus is the organization should be monitoring what type of software is deployed in the environment.

###

### Audit Timeline and Period

#### **SOC 2 Type 1 & 2 Auditing Periods**

Different types of SOC audits have different audit timelines and audit periods. For example, take into account that a SOC 2 Type 1 Report has a minimum auditing period of 3 months. A SOC 2 Type 2 report has a minimum audit period of 6 months. Typically, an organization will first obtain a SOC 2 Type 1 report as a metric to see where the organization stands when it comes to its people, processes, and technology.Then there are the organizations that are more mature. Mature in their processes, systems, and technology

****

#### **Auditing Timelines**

Timelines will vary greatly between organizations. However several key metrics are used to determine how much work needs to be completed for an organization before an audit period begins. One of these key metrics is known as a gap analysis. Another key metric would be a risk assessment. The risk assessment should be able to also identify gaps of where controls could be missing or processes that are deficient. We will talk more about what a Gap Analysis is and what it entails in module 2 of this course.For now please review the high-level overview of the audit lifecycle.\


#### Overview of Audit Lifecycle

<figure><img src="https://files.cdn.thinkific.com/file_uploads/628111/images/068/405/182/1648649602644.jpg" alt=""><figcaption><p><strong>Figure B.1</strong></p></figcaption></figure>

The above diagram does not depict all processes in an audit however it provides you with a high-level overview of what is to be expected during the audit lifecycle and is meant to be used as a guide. Every auditing firm, consultant, and lead implementer will have its own processes and techniques for completing the audit.&#x20;

### Certification bodies

There are only a few entities that can provide attestation rights for a SOC 2 Report. These business entities are usually professional organizations that have years of experience in tax advisory services, or the law. Review the list below of common types of organizations that can attest to a SOC 2 Report. Please note, although SOC 2 compliance encompasses a majority of cyber-security-related controls. The final attestation must be provided by a licensed and qualified Certified Public Accountant (CPA).

**Example**

Example Law Corporation wants to add an IT Services and audit branch to its current service offerings and start performing SOC 2 audits.&#x20;

They must have a qualified CPA that can attest to the SOC 2 report and provide an auditor's opinion on the design and suitability of controls that have been developed. It’s important to note that auditors or firms must go through a review process every three years. This is a must in order to keep the status of an auditor.



