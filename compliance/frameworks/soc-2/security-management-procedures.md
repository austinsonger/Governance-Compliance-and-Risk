# Security Management Procedures

### **Policies and Procedures**

Looking at the organization as a whole you need to look at the people, processes, and technology that encompass the organization. The policies are what guide the organization forward and the processes are what guide the employees within the organization to accomplish the desired procedures.

Most of the time the company will use technology to accomplish these goals. Thus you have People, Processes, and Technology at the heart of what the auditors will be measuring the controls against.

\***Policies > Processes > Procedures\***

As a lead implementer for your SOC 2 program you will need to set out and define what policies are needed for the organization. Some things to consider when designing and implementing a policy.

\***Considerations for policy implementation\***

1. Is the policy needed?
2. Will it impact the organization?
3. What is the desired outcome for the policy?

![img](https://files.cdn.thinkific.com/file\_uploads/628111/images/b4c/3b7/c57/1649082170020.jpg)

### **Passwords and MFA**

While we are on this topic let's have a short discussion regarding three types of authentication factors that are offered to users by most of today's computing systems.

\***Authentication Factors\***

1. Passwords - Something that you know
2. Biometrics - Something you are
3. Token - Something you have

When looking at the controls that have been developed for an organization. It is important to remember that passwords must be in compliance with the password policy that has been defined for the organization. Also, several controls within the common criteria deal with Multi-factor Authentication. It will be your job to check to see those authentication systems in scope of the audit, encompass MFA.

\***Example Password Policy\***

1. Minimum of 8 Characters
2. Special Character Required
3. Uppercase Character Required
4. Lowercase Character Required

**Examples of MFA use cases**

1. A Hard Token (Employees Carry a Physical Token Providing a Random Number)
2. An email containing 6 - 8 digits for one-time use
3. An SMS message is sent to a phone number usually 6 - 8 digits

Additionally, the organizations using MFA, should have this defined in their password policy and it should list if there are any exceptions to this policy. For example, service accounts might need access to write data or move data based upon certain data jobs within the platform. Obviously, since it is a service account and the job is automated, the service account can not input a two-factor authentication code.

### **Risk Mitigation**

\***Risk Assessment\***

After both the business and technical risk assessments have been conducted. You will need to then review the findings and assign a risk score based upon your own defined matrix. Next you will need to Mitigate that risk, or put in place a compensating control to limit risk exposure.

\***Control Types\***

Earlier in this course we discussed different control types. They were identified as the following

1. Preventative
2. Detective
3. Corrective

Now is the time to review your risk matrix and align each risk to a control type. If you have already performed this as part of your scoring model, then this is not needed. However, It's easier to have the mitigating control type listed alongside the risks.

| **Severity** | **Identified Risk** | **Probability of Risk Occurring** | **Mitigating Control Type** |
| ------------ | ------------------- | --------------------------------- | --------------------------- |
| Critical     | "Risk 1"            | 23%                               | Corrective                  |
| High         | "Risk 2"            | 85%                               | Compensating                |
| Medium       | "Risk 3"            | 15%                               | Detective                   |
| Low          | "Risk 4"            | 27%                               | Preventative, Detective     |

**Formula for Determining Risk - High-Level Explanation**

Drawing from this information you can now start to develop risk mitigations based upon the scoring model or risk matrix you have developed. During this time your main focus will be working with the organization to come up with controls to mitigate the risk.

Some of the control types you develop and implement to minimize risk could impact budget. It's important to understand this concept and ensure the organizations' management team is aware that if deficiencies exist they could cost money and resources to fix.

\***Risk Acceptance\***

During this time, if you have found that the organization is willing to tolerate or accept a certain level of risk. Please ensure that it is notated and explained to the audit team. As a lead implementer, it is not your job to force the organization to mitigate risk but for them to understand the risk level and for them to determine the level of acceptance. It's also important to ensure that the level of risk acceptance does not fail a common criteria which may lead to a qualified audit opinion.

### **Risk Assessment**

Every organization should be performing some type of Risk Assessment. Risk Assessments can vary in nature and degree. However, they should lay out risks from both a business and technical perspective. Oftentimes you'll encounter that organizations are not performing a risk assessment at all.

**Business Risk Assessment**

Business Risk Assessment should address the following.

1. \***Insider threats\***
2. \***Business Continuity & Crisis\***
3. \***Legal Risks\*** "Data Privacy, Compliance with Federal, State, Country-Specific Laws”
4. \***Cyber Insurance\*** "Vertical Specific"
5. \***Data Mapping\*** - "Where is the data" Customer Data
6. \***Managed Services\***
7. \***Sub Organization Processors\***

It will be your job to help lead these discussions with the business and document the results. From these conversations, you will be able to layout risks from a business perspective that will help define what risks the organization is susceptible to.

When looking at the technical risk assessment there are multiple different domains within that category. Depending on how in-depth you want to assess the organization. These types of risks assessments can vary. What should be included in a typical risk assessment is defined below.

\***Technical Risk Assessment\***

1. Assets Management
2. Identity Access Management
3. User Access Reviews
4. Third-Party Penetration Test
5. Vulnerability Scanning
6. Log Aggregation
7. Intrusion Detection & Prevention
8. Managed Services "Technical Consulting"
9. Code vulnerability scanning
10. Change management

The items for the technical risk assessment above will not be inclusive to all organizations however it is meant to be a guide. At a minimum, all organizations should be undergoing at least internal vulnerability scans of their infrastructure, code scanning prior to deployment to production, and a penetration test performed by a third party.

Secondly, log aggregation is meant to serve as a way to detect and respond to events before they become critical or worse, turn into a crisis for an organization. Log aggregation can often be expensive, however, you as a lead implementer should assist in coming up with solutions that will fit the organization's budget and needs.

If you’re a lead implementer, be sure to use the templates we have defined for guiding the organization through this process. After the risk assessments are completed, it will be your job to communicate the findings to the organization and then move on to the risk remediation phase.

\***Risk Assessment\***

After both the business and technical risk assessments have been conducted. You will need to then review the findings, then assign it a risk score based upon your own defined matrix and scoring model. It's best to look at the organization as a whole when determining risk.

\***Developing The Risk Matrix\***

The table below represents a snapshot of what the final report to an organization's management team should look like. It should address critical and high findings first and then medium findings. If it's a low finding it should be included in the overall report, however, redacted from the management or executive report unless otherwise stated by the management team.

\***Example - Risk Matrix\***

| **Severity** | **Identified Risk** | **Probability of Risk Occurring** |
| ------------ | ------------------- | --------------------------------- |
| Critical     | "Risk 1"            | 23%                               |
| High         | "Risk 2"            | 85%                               |
| Medium       | "Risk 3"            | 15%                               |
| Low          | "Risk 4"            | 27%                               |

### **User Access Review**

**User Access Reviews**

One of the most important controls that any organization will undertake is performing user access reviews.

**What are user access reviews?**

Essentially it is reviewing the permissions of employees within the defined scope of the audit. Oftentimes, user access reviews will also ensure that employees that have been terminated actually have their accounts revoked.

**How are user access reviews performed?**

That is a great question and will vary from organization to organization. Each organization will be using different technology. However, they should have one thing in common.

An identity access management platform. For very small organizations, this may not be true. However, for larger organizations, the user access reviews will make life easier if they have an identity access management platform.

\***User Access Review Steps\***

1. Pull the current list of employees from human resources
2. Pull the current list of all employees that are active inside of the Identity management platform. "Ensure that each active employee id is also notated within the identity management platform, If this has not occurred, please have the organization do this on your behalf and ensure a process is put in place to enforce this going forward"
3. Cross-reference the two lists and reconcile
4. Notate your findings
5. Remediate any findings

Another detailed user access review would be to also pull the permission groups within the defined scope of the platform and associated infrastructure. This will include things like databases, servers, or computerless instances. From here, you would review job descriptions, job duties and notate any potential deviations. Again, organization size is another factor in this type of review. Some people in the organization might wear multiple hats. That is perfectly fine, however, be sure to notate it as a finding.

### **Security Awareness Training**

\***Trainings - We all take them\***

Found across many frameworks from CIS, NIST, PCI, SOC 2, and HighTrust. One thing they all have in common is for end-users in the organization to be trained on how to spot, prevent and report potential attacks against the organization.

\***More than just training\***

Security Awareness training also known as cyber awareness training is not just about checking a compliance checkbox, but also trying to give the end-users in the organization the tools necessary to be alert against things like phishing and malware.

After all, business email compromises are one of the easiest ways for hackers, and nation-states to steal data, gain access to a network, or worse deploy ransomware. You as a lead implementer or consultant is to ensure that the organization is compliant with this requirement.

This will be audited using automation. However, if not. You must ensure that the organization is performing end-user security awareness training at least on a yearly basis.

\***Audit Method\***

1. Pull list of all employees from human resources
2. Pull list of all employees that have successfully completed training
3. Reconcile list
4. Notate any findings or deviations

Topics that should be included in the security awareness training include basic cyber security principles, phishing examples, ransomware, and social engineering concepts that end-users could face.

### **Security Risk Vs Security Vulnerabilities**

**Quick Notes**

In this section, we will look at security risks and security vulnerabilities. The difference between the two and how you should be measuring them differently. In an earlier section within this module, we talked about risk assessments both from a business and technical perspective. On a similar note, security risks can encompass both business and technical risks. Whereas security vulnerabilities are mainly technical.

Let's review examples of a security risk both from a business and technical perspective

\***Examples\***

1. A business does not have Cyber Liability Insurance, however, they process and store patient health information and have over 2.3 million records.
2. A business is not performing internal or external vulnerability scans of their infrastructure

\***Let's review and talk about the examples above\***

1. From the first example, we have determined that a business is not carrying cyber liability insurance. Some businesses may think that because they have great technical and administrative controls in place this isn't needed. However in today's advanced world where more lines of code are pumped out than ever before. More and more zero days will become prevalent, thus increasing the risk for the organization. Especially when relying on third parties.
2. A business is not performing internal or external vulnerability scans of its infrastructure. This is a security risk that can be easily mitigated by having the business perform internal and external scanning. the control may be technical in nature, but overall it is a security risk

\***Security vulnerabilities\***

What is a security vulnerability? In essence, it's when a technical shortcoming has occurred within a system, code, or process and can be exploited for profit, personal gain, or data enrichment.

\***Examples of Security Vulnerabilities\***

1. The organization that did not have vulnerability scanning before now has a tool in place to perform scanning of internal and external resources. The tool produces a report detailing the vulnerabilities for several systems. Oftentimes these systems are running a certain application or service that is vulnerable, or the operating system itself is susceptible to attack. This would be known as a security vulnerability.
2. A business has just implemented new RFID badges to allow employees access to the building during normal working hours. However, the RFID badges that they have implemented are not encrypted. One day an attacker decides to implant a reader next to the actual door reader so that he can copy employee badge codes and provision himself a badge to gain access to the building. This is a vulnerability and not a security risk.

Let's review example number 2 under security vulnerabilities, and talk about why it is a vulnerability and not a security risk. Essentially the business did not use encrypted RFID badges. However, if they did use encrypted badges it would be a security risk. This is because it would take an attacker considerable time to break the encryption and provision himself a badge, whereas the badge numbers are in plaintext and the attacker can copy the badge and provide him/her self access.

### Endpoint Management and Anti-Malware

In today's ever-growing remote workforce-enabled world, this is a control that should be taken seriously. You as a lead implementer will be responsible for ensuring that organizations have an employee endpoint solution in place. The endpoint management solution should have the following capabilities or minimum set of requirements.

\***Requirements for Endpoint Management Solution\***

1. Deploy software
2. Remote Wipe
3. Remote Lock
4. View Versions of Applications

Granted not all endpoint solutions have these features, and multiple agents "different solutions" may have to be deployed on endpoints to accomplish the list above. However, use it as a reference when designing and implementing controls for an organization. You as a lead implementer will be responsible for assisting the organization with auditing and pulling this information together.

\***Audit Steps\***

1. Obtain a listing of all active employees from human resources
2. Populate listing of all endpoints from endpoint management solution
3. Reconcile lists and compare
4. Report deficiencies found
5. Notate Deviations
6. Ensure Remediation Occurs
7. Check that Anti Malware software is set to automatically download the latest configurations

Note - For very large organizations this is like a moving target, the success rate for this audit will rarely come back at 100 percent.

Employees leave, employees get terminated, new employees are hired, and IT departments get behind. Especially when it comes to equipment returning, success criteria for this audit should be within the 95th percentile. However, if the organization is small, a larger percentile should be used.

\***Anti Malware\***

Also another point we are going to focus on here is anti-malware. Most organizations see this as an expense. However, more than ever with a remote workforce, this needs to be in place. Like we talked about earlier, the organization is a target, the bigger the target, the more likely organizations are to become breached.

\***Traditional Anti-malware\***

Traditional anti-malware systems still exist and will provide coverage for compliance. However please note, there are delays between when updates are provided for traditional anti-malware systems that are hash-based. Depending on the size of the organization and data involved this could be a security risk.

\***Next-Gen Anti-Malware Systems\***

Next-Gen Anti-Malware systems encompass both traditional and newer features, oftentimes these systems have hooks into the kernel of the operating system and look at things such as software signatures, process manipulation, and will have an AI or behavioral monitoring system used in the cloud, these systems are more advanced.

\***Audit Steps\***

1. Pull a listing of all machines from the endpoint management solution
2. Pull a listing of all machines that are active from the Anti-Malware platform
3. Reconcile the list and compare
4. Report deficiencies found
5. Notate Deviations
6. Ensure Remediation Occurs

### Assets Mapping and Classification

If you have ever worked for a large enterprise, you know how daunting it can be to get up to speed on things. Things are oftentimes slower, there are more standard processes in place and oftentimes it's really boring. With that being the case, the larger the organization becomes, the more data it has. Big Business = Big Data.

To ensure that this information is not lost. It's important for organizations at the soonest possible stage to implement data classification and asset mapping. Not to mention, it can become a nightmare when things are unorganized. Let's first talk about data classification.

\***Data Classification\***

Data classification can be different for organizations, some organizations will deal with personally identifiable information, whereas others might have protected health information. Depending on the organization and the types of data they are working with. They will need to implement a data classification program. The data classification should be a set of procedures that contain multiple processes.

\***Example\***

Acme Corporation is standing up a new database that will handle a large volume of health-protected information. This information contains the patients' social security number, patient id, name, and health records. Once this database has been placed into production, it should be tagged within the asset management tool or architecture diagram that this database contains protected health information. Other ways organizations could also classify these types of systems is through an internal classification system that is pertinent to them.

\***Lead Implementer or Consultant Role\***

Your responsibility as a lead implementer will be to take the organization on a journey to find out where the data is located and implement a classification system. If one is already in place, be sure that that data classifications are readily available for your review.

\***Audit Steps\***

1. Select multiple assets that have not been defined in the data classification program
2. Define owner for each asset
3. Audit the asset to see if confidential data resides on the system, database, or flat storage.
4. Report deficiencies
5. Notate findings
6. Remediate if necessary

\***Asset Mapping\***

As we mentioned earlier, **Big Data = Big Business**. However, another important component is asset mapping and tracking. There are several reasons why this is important.

1. Having a detailed asset map allows you to visualize what assets are in existence in your production network.
2. It allows you from a network perspective to see potential data flows between systems. This is important if a security breach has occurred.

\***Lead Implementer Role\***

Your responsibility as a lead implementer will be to ensure that the organization has a detailed mapping of all assets that are in the production environment. This mapping could be a visual network architecture diagram, showing data flows across the organization.

\***Audit Steps\***

1. Ask the organization to produce an updated architecture diagram
2. Review the production network and notate the network subnets and data flows
3.
   1. You will need to graphically layout yourself what the network looks like
   2. Notate the subnets, if any
4. Compare your diagram and findings against what was produced by the organization
5. Report Findings
6. Report Deficiencies
7. Ask Questions (Ask More Questions)
8. Notate Findings
9. Remediate if necessary

### Human Resources

#### Recruitment

The human resources department in regards to SOC 2 audit has an instrumental part in helping the organization obtain an unqualified opinion, and it all starts with its most basic practice “recruiting”. The human resources department should have a process in place to recruit top talent. In regards to recruiting top talent.

The organization should be collecting and receiving recruiting documents so that they can be easily stored and accessed. Most commonly this is performed by an HR solution provider such as Greenboard, BambooHR, or for larger organizations PeopleSoft or ADP solutions.

Although recruiting practices remain largely the same across organizations, a lot of organizations still lack the process of completing a reference and background check for newly hired employees. This is because the organization doesn’t want to spend the time, money, and resources on a potential candidate. However, this is an administrative control that should be implemented early on in a company. Since this is a control output that will be expected to be produced for a SOC 2 audit.

**Example recruiting process**

1. Candidate submits application
2. Review of candidates' qualifications
3. Interview setup
4. Interview scheduled with candidate
5. Home assignment for the candidate to review and complete if applicable
6. Evaluation of assignment
7. Second round interview if necessary
8. Selection process
9. Start date set and onboarding

Where a lot of organizations lack is simple proper planning. An organization can miss out on a great candidate if they fail to notify the candidate in a timely manner and keep up with communication in regards to where the candidate is during the interview process. This process will need to be defined and laid out for review

As of this writing, businesses are experiencing something known as the great resignation. This has never occurred before throughout history and going forward I think employers should do more to excite and retain employees, because once an employee leaves the organization. The knowledge regarding the projects they worked on and contributions made to the organization also leaves with them.

#### Onboarding & Training

Once the human resources team has selected its candidate and everyone on the team feels comfortable. It's the responsibility of the human resources department to ensure that an onboarding process is in place and followed. The onboarding process should include timely communication with the employees and also an introduction to the organization either through email or instant messaging platforms such as Slack, or Microsoft teams.

The onboarding process should also include the necessary training for a newly hired employee. Including what the company does as a whole, what processes they will own, and an overview of the reporting structure of the company.

This is also a great time for the organization to have the employee review any company policies and gather a signature. A lot of times these processes can be automated with the organization's HR solution. If it's not available then a manual process will have to be completed. This is also a great time for the organization to ensure employees are made aware of basic job responsibilities and processes within the team or department.

Tip - SOC 2 Auditors will pull samples for requested training, it's vital to have this information available for the auditors during the audit period.

**Example Training List**

1. Company Overview
2. Platform training
3. Security awareness training
4. Software development lifecycle training (SDLC) if applicable
5. Safety Training
6. Financial securities training if applicable

#### Transitioning positions within an organization

As the business grows, the human resources team will find itself trying to scale a business, and with any new product or service on the market. It will have a tough time finding employees that have the right skills and experience to fill more senior-level positions. With that being said, internal promotions are going to happen.

Sometimes, employees will change departments completely. Just like when a new employee was hired and the human resources team announced it. The human resources team needs to announce when an employee changes positions. This will allow the employees to be notified but also from a security perspective, reassign processes and roles based upon the job duties of the position.

At a high level, there should be a ticketing system in place that human resource managers submit employee position changes to. On the backend, “ticketing side” there should be a process to re-evaluate the employees' access roles within the environment. Typically the change is completed by the Information Technology department with the addition of more access approved by the manager over the employee. Please see the basic process flow attached below.

####

#### Offboarding and Terminations

All companies will face offboarding and terminations at some point. During this phase even if you're a small startup. Offboarding procedures need to be in place. They need to be defined and followed. This is a critical step, as a lot of organizations will not remove access days or even weeks after an employee has been terminated. This is simply because there is no defined process and the lack of communication between Human Resources and Information technology departments did not occur.

**Example offboarding procedures**

1. Human Resources is notified that an employee is leaving or should be terminated.
2. Human Resources submits a ticket notifying Information Technology to remove access on desired date and time.
3. Information Technology receives requests and plans accordingly.
4. The former employee is termed and access is cut.
5. Communication to the organization notifying departments or teams that the employee has been offboarded.

####

#### Annual Evaluation

One of the most critical things for an employee to receive at the beginning, or at the end of each year is their annual evaluation. This is important not only for the employee but also for the organization to continue developing its employees and giving them a chance to bring attention to issues that could be plaguing the organization but not known at the management level.

Not only is the annual evaluation good for both the employee and employer, but it's also a metric used for control within the SOC 2 framework. The annual evaluation can follow any format, as long as they are recorded and the feedback is provided back to the employee.

For organizations that do not believe in an annual evaluation because they have weekly 1:1 sessions. This is also acceptable, however, you will want to ensure that the managers are maintaining notes and at a high level at least performing yearly reviews that touch base on projects that were completed by the team and individual contributions made by the employee.

**Legal Commitments**

Acting as the muscle of the organization and driving it forward, the human resources team will have access to large amounts of data. Typically they are the first to know about terminations, they have access to employee confidential information, and they are obligated to keep it held in strict confidence. Usually by federal and state laws.

This information should be held for safekeeping and following the defined retention periods as permitted by law. Secondly, employees records should also be maintained and updated in accordance with local, state, and federal laws governing that country's jurisdiction.

### Maintenance, Monitoring, and Analysis of Audit Logs

Many times during your career in audit you'll find that organizations if they grow too quickly will be lacking processes to ensure proper maintenance occurs. This is a result of poor processes and procedures.

**Maintenance**

Just like keeping up with your bicycle or vehicle, maintenance will be required for servers, databases, and code as infrastructure. It's important that organizations perform these actions, oftentimes there are patches required. Updates that need to be applied, or a fix for a zero-day vulnerability.

**Defined Maintenance Schedule**

Next the organization should have a defined maintenance schedule or "window". Oftentimes this should occur when it will have the least amount of impact on customers.

**Example Defined Maintenance Windows**

| Servers      | Databases             | Employee Endpoints |
| ------------ | --------------------- | ------------------ |
| Every Month  | Quarterly             | Weekly             |
| 1st Thursday | Last Month in Quarter | Automated Weekly   |

**Lead Implementer Role**

Your role as a lead implementer will be to ensure that the organization has defined processes and procedures in place for the maintenance to occur. This should be in the form of a policy at the highest level or at least detailed within a policy. This way there is administrative oversight and control of this process. Something to note here, the organization should also have defined roll-back procedures or a defined process to avert issues caused by maintenance.

**Logging Maintenance Activity**

A log should be kept with each maintenance activity that occurs. This is important because the service auditors will want to see this if the organization is going from criteria such as availability. This can be used for potential evidence.

#### Monitoring

Systems errors are a part of life, more often than not, most organizations have experienced a system failure at some point. Have it been in the cloud, or with an on-premise solution. In any case most of the time they were caused by human error. For critical parts of the production network, databases, servers, etc. It is important that any organization have monitoring in place. There are many solutions available in the market today, on top of that they are relatively low cost and can provide an enormous benefit when implemented correctly. Often times alerting before issues become critical.

**Audit Steps**

When reviewing for monitoring, as a lead implementer you will want to see and check for the following.

1. What platform or software is used to monitor the infrastructure.
2. How the monitoring alerts employees "Examples: Text Messages, Emails, Phone Calls"
3. Sample of previous monitoring alerts
4. You can also help determine what should be in scope by reviewing the architecture diagram and critical process flows

#### Analysis of Audit Logs

You will see that a lot of organizations fail to realize the power of audit logs. Or that they are not keeping them at all, and if they are keeping them, they are usually siloed and stored on that specific system, oftentimes logs are never checked or reviewed. However new technologies called System Incident and Event Management Systems or SIEM for short, allow for the collection and processing of audit logs from multiple sources.

This provides security teams within an organization access to real-time data that before was usually hard to see and very time-consuming to access across multiple systems. On top of that, the correlation aspect of correlating logs between different systems was a very difficult task. However, SIEM technology has made that possible. Not every organization is going to have a SIEM in place, or afford that luxury. Oftentimes a simple hosted solution that provides similar capabilities within the cloud are also available.

**Lead Implementer Role**

You will be responsible to ensure that the organization has at the very minimum logging enabled on production and development systems that are within the scope of the system.

This should include but is not limited to;

**Example of Log Sources**

1. Operating system logs
2. Database logs
3. Application Logs
4. Access Logs

Tip: When reviewing this information, it is imperative that time sources align between each system. Meaning that the time source used for the system should be the same. From operating systems to applications logs. They should always be pulling the time from the same time source. If organizations fail to understand why this is critical, explain to them that in cases where a breach was to occur, it's important that a forensic auditing team be able to piece the puzzle together.

**Audit Steps**

There are several ways you could audit this. It will vary from organization to organization. However, the key points are outlined below.

1. Is logging enabled for all systems, applications, services, databases that are in scope of the platform or system
2. Review the architecture diagram that has been provided
3. Request a sample of logs from the diagram that outlines applications, services, databases
4. If a SIEM is used, request to see a population of systems that are pushing logs into the SIEM

### Data Breaches and Disclosures

From the previous modules we have learned that you as a lead implementer will be asking the organization a lot of questions around their processes, people and technology. Now we will be discussing ethics around data breaches, data disclosures, and your role as a lead implementer or consultant.

Data has been extracted

We have seen it come across the headlines one too many times. Organizations across the globe face a very real and dangerous threat. The threat of hackers, nation-states, and insider threats. Data breaches, although a common occurrence in today's world, should not be as prevalent as they are. If organizations have the right technology in place and have proper procedures in place, you would not see as nearly as many breaches.

To help limit exposure, the controls we have talked about throughout this module should assist organizations from facing a serious breach. Although there are more to come, It starts at the top. You as a lead implementer need to ensure both the technical and business controls are in place.

**Example of Controls**

1. Ensuring Policies are in place
2. Eliminating Risks
3. Remediating Risk
4. Data Classification
5. Asset Mapping
6. Insurance

However there will come a time when an organization is breached and they need to be prepared. You will need to walk the organization through a tabletop exercise. As this will help them identify potential process weaknesses. Part of this exercise should include a breach where the hacker(s) have exfiltrated data out of the network, your job will be to run point on the simulation and ask key questions. Build the scenario around the organization, but use your imagination and creativity.

**Table Top Questions**

1. Is there a defined communication plan
2. If yes, where is it? Who do we contact?
3. Can they identify the data that was breached
4. Can customers be identified that were affected by the breach?
5. Have the assets that have been breached been identified?
6. Are the logs available?

**Cyber Liability Insurance**

Many times organizations that have cyber liability insurance will have resources available during, and after a breach. Be sure to request a copy of the policy to help address questions and provide a defined playbook for the organization that you're working with.

**Examples of Coverage that is included for Cyber Liability Insurance**

1. Public relations communications
2. Incident response resources
3. Assistance for recovery and business continuity

**Audit Steps**

1. Perform a tabletop exercise
2. Notate deficiencies during the exercise
3. Assist the organization in the creation of a data breach playbook
4. Ensure defined roles are known to all parties
5. Ensure the playbook is updated yearly

**Data Disclosure**

We all know organizations share data, they buy and sell our data. We have seen this occur with social tech giants like Facebook, now known as Meta. Google with their advertising and tracking ids. However many companies also buy and sell our data or share it with their partners.

They do this for multiple reasons. The most common being it provides organizations monetary value or for data enrichment purposes.

With that being said, it's important to know the following.

1. Does the organization sell its customers' data?
2.
   * If yes, to whom?
3. Are customers made aware that this behavior occurs?
4. Does the data disclosure list the companies it provides data with?
5.
   * If not how does the company define the term "Parties or Third Parties"

Audit Steps

1. Audit the privacy policy
2.
   * Does it outline the data the platform captures and processes?
3. Are Data Processing Agreements "DPA's" in place with contracts?
4.
   * You will need to pull a list of contracts and DPA's
   *
     * Important Note - DPA's are not always needed
5. Review a sample of that data that was sold, or provided to a third party.
6.
   * Do the data fields align with what is defined in the data disclosure?
7. Ask for a population of third parties the data was shared with'''

### Crisis Management

When the organization isn't being attacked and or a breach occurs. The organization will face another threat. The threat of a crisis.

What is a crisis - Well to make things simple, a crisis is when something has gone terribly wrong. From our perspective, we will keep things simple and use the following example.

**Example**

Roger, who is a systems engineer, arrived at work to find that a critical application hosted in the cloud production environment went down overnight. Neither he nor his team was notified of the incident, and today during normal business hours they are losing 1.2 million dollars per hour. The system has already been down for over 12 hours. The business has had an estimated loss of 13 million dollars since the crisis began. Things are getting heated at corporate, the executive team is furious as to what has unfolded, enormous pressure from management has compounded. The hallways are filled with yelling and screaming between managers protecting their employees and executives who report to the board of directors.

After reading the example above you can see where proper planning and cooler heads would have prevailed in this situation. However, not every organization is going to be like this.

You as a lead implementer will be responsible for ensuring that the organization has a defined crisis management plan. The plan at a minimum should encompass the following processes.

**Crisis Management Plan Processes**

1. Communication to employees during a crisis
2. Communication to customers, partners, and vendors
3.
   1. How will the communication occur? Social Media?
4. Process for recovering after a crisis
5. Notification after the incident
6. Performing a Post Mortem "Root Cause Analysis"

For organizations that already have a defined crisis communication plan, review it with them. Ensure that key stakeholders are called out by title. Roles and responsibilities should be defined and known to all applicable parties. Last but not least ensure that a root cause analysis is performed, and lessons learned follow-up occurs after.

### Segregation of Duties and Least Privilege

The more people, the less you have to worry about. The fewer people the more you have to worry. This phrase rings true with smaller-sized businesses. Where multiple different people wear different hats.

**What is Segregation of Duties?**

Segregation of duties is where the "people" performing the processes inside of the business do not have full control over anyone activity that could be detrimental or cause significant harm to the business.

Let's take, for example, Joe. Joe is a programmer who was hired when the company was first getting started. Since Joe was an early employee, he enjoyed many access rights from the beginning. Many of which still exist today. Joe one day decides that he's not being compensated fairly. Joe is of the entitled mindset, and since Joe thinks he is smarter than everyone else and has been there long enough. He starts plotting his retirement dreams in the Cayman Islands.

Joe immediately gets to work, sets up offshore bank accounts, and starts embezzling money. After a few months, the business notices that some transactional data is off. The numbers just don't add up. From these findings an internal investigation was launched with an independent third party. They find that there were significant code changes within the last 6 months and that is why the transactional data is off.

From this example above, you can see why segregation of duties is important. The people who approve the code, should not be the ones that write it. However if not, you will have to perform the following.

**Auditing Steps**

1. Interview and understand critical business processes
2. Review Access rights of employees of critical business processes
3. Perform sample and population pulls for critical business processes
4. Report deficiencies
5. Notate findings
6. Perform Remediation

Your role as a lead implementor will be to ensure that the business has documented these key roles and processes and that employees within the organization have at least a two-man rule applied for critical business processes such as code changes, architectural changes, and transactional changes.

**Least privilege**

This brings us into the principle of least privilege. This is when a user has the minimum amount of privileges needed to perform his/her work. This also applies to users that would normally need elevated privileges such as IT administrators or system administrators. For smaller teams, this is very hard to implement and maintain. Although very disciplined teams can manage this set of procedures and processes. Ensure that that organization has a defined access matrix from provisioning access to systems and services.

**Audit Steps**

1. Pull a listing of all employees that have access rights
2. Pull a list of all access groups that are defined
3.
   1. Determine what level of access each access group provides
4. Pull a sample of job descriptions and perform interviews to determine if employees potentially have too much access.
5. Alternatively if the organization has a role-based access matrix, you can use this as a guide.

### Change Management

Every organization, no matter what size, should have a proper change management process in place. Changes to any system should be controlled throughout the lifecycle of the system and components. The change management process can be generally broken down into the following aspects:

* A change management policy and procedure document should be in place that describes the whole change management process.
* A change methodology should be adopted by management i.e. Agile or devops.
* A ticketing system should be considered at the Organization, in order to log, classify, track, document, manage and keep evidence of the change e.g. Evidence of testing can be uploaded and linked to a specific ticket.
* All changes should be discussed, analysed and prioritized prior to being developed.
* A process should be in place on how changes are designed and developed
* Responsibilities in the change management process should be segregated as below:
*
  * Develops the change
  * Test the change
  * Implements the change
* Developers cannot have access to production. If its a small environment, than access should be monitored or a process should be in place where temporary access is given for developers to work on production or to implement the change.
* Testing strategies should be formalised and implemented. All changes should ideally be tested prior to implementation. This includes functional testing, UAT testing, QA testing etc.
* All changes must be approved and authorised prior to implementation. This should be a formal sign off or authorisation on a ticketing tool. This is normally a key piece of evidence for the auditors.
* An emergency change process should also be implemented and clearly defined in the change management policy.
* Separate environments of a system should exist:
*
  * Development environment
  * QA/ test environment
  * Production environment

The above is not a conclusive list of how a change management process should look like, but these are the key elements.

**Audit Steps**

1. Select one change and perform a walkthrough with management, so that the auditors can get an understanding of the change management process.
2. Pull a listing of changes for the period of review from the ticketing tool or the system itself
3. Select a sample of changes and request the following evidence:
4.
   1. Evidence that the change was tested
   2. Evidence that the change was approved
   3. Evidence that the developer and the implementer of the change were different people.
5. Screenshot showing the different environments i.e. DEV, QA and PROD
6. Pull a list of developers and compare with a list of prod users and also with a list of user roles who have access to make changes in PROD.

### Internal Audit

Internal Audit teams are few and far between and usually if an internal audit team does exist, they mainly just focus on financial controls and oversight. It's very rare that you will see an internal audit team that performs both financial and information technology compliance audits. Usually, this is only performed in consultation with third parties.

Many organizations you work with especially in start-up land will not have an internal audit team. Your duty as a lead implementer will however focus on getting the organization to consider or delegate duties for compliance activities. After all, in module one we discussed that management needs to set the tone at the top and provide the necessary tools and availability to ensure a successful audit.

Tip: For the people that are performing the internal audit, these can not or should not be the same people that have access to change system results, manipulate data, or have the ability to conceal it. The team or individuals should also have a different reporting structure.
