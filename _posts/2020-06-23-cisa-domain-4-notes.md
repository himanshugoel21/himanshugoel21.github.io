---
title: CISA Domain 4 Notes
tags: [Certification, CISA]
style: fill
color: light
description: Important notes on CISA Domain 4
---
Main points to remember (please excuse the brevity and spell errors):
1. **Service provider SLA**:
    - **Most Imp --> Transition to new or internal process post contract termination**
    - Right to audit -- imp
    - To check uptime reports in SLA --> check **Availability reports**.
1. **Database**:
    - Assurance on Database Referential integrity should be provided by reviewing --> **Foreign Key Structure**
        - **Referential entity in a RDBMS refers** to the consistency between couple (linked) tables. Ref integrity is usually enforced by the combination of a primary key or candidate key (alternate key) and **foreign key**. For ref integrity to hold, any field in a table that is declared a foreign key should contain only values from a parent tables primary key or candidate key.
    - Default configuration should be changed
    - Concerning if DBA is performing OS patches as that should be done by System Admin
    - DBA suggests that efficiency can be increased using **De-normalization** --> It results in Data Redundancy --> **Normalization is a design or optimization process for RDBMS that increases redundancy**
    - Concurrency objective in DB --> **Ensure integrity when 2 processes attempt to update same data**
    - **GREATEST ASSURANCE of DATABASE INTEGRITY** --> **Table link/Reference checks**  --> Performing these **checks detect table link errors (such as completeness and accuracy** of the contents of db) and thus provide greatest assurance of database integrity.
    - Database audit logs should be **deleted other than DBA**
    - During maintenance of RDBMS --> several values of **foreign key in a transaction table have been corrupted** --> consequence --> **Detail of involved transactions may no longer be associated with master data, causing errors when these transactions are processed**
    - In RDBMS with referential integrity --> t**he use of which of the following keys would prevent deletion** of a ROW from customer table as long as customer number of that row is stored with live orders on the orders table ---> **FOREIGN KEY**
    - **DENORMALIZATION -- WILL INCREASE RISK OF**  ----> **🔥LOSS OF DATA INTEGRITY**
    - Which DB controls would ensure that the **integrity of transactions is maintained in an online transaction processing systems database**  ---> **🔥🔥COMMITMENT AND ROLL BACK CONTROLS**
    - User Spool and Database limit controls can affect the performances significantly.
    - **Database processing suddenly comes to a halt --> Integrity best ensured by -->** Database commits and rollbacks**
    - **IT mgmt has decided to install RAD and remove off-site backups ---> IT auditor should re-instate for off-site backups** #readquestionproperly #understandmeaning #remove2options
    - IS auditor sees corrupted data in database --> **corrective control is** --> **🔥🔥Data restore procedures**
1. Auditor notices patches are deployed as per vendor --> MOST significant RISK would be that IT has🔥 not **TESTED THESE PATCHES**.
1. For any changes done in business like -- service provider change etc.. --> **APPLICATION OWNERS SHOULD BE INFORMED**.
1. Auditor checking change mgmnt - Most imp control that IS auditor should look for to ensure system availability --> **Test Plans and procedures exist and are closely followed**
1. 🔴🔥Disaster Recovery Plan - DRP (💥Addresses Tech aspect of BCP💥)
    - Auditor reviewing **DR PLAN** --> Plan should **PRIMARILY COVERS** --> **🔥🔥🔥🔴🔴🔴💥💥ANALYSIS and PRIORITIZATION OF BUSINESS FUNCTIONS**
    - Downtime cost increases with time.
    - 🔥**Most Imp element** to effectively execute a DRP --> **Offsite storage of backup data**
    - **Business Impact Analysis** should be used in DRP for it to be successful
    - 🔥**NO TEST DONE IS CRITICAL** -- DRP --> **auditor observed remote offices have very limited local IT resources** --> **MOST Critical** --> is that **🔴no test is done to ensure that local resources** could maintain security and service standards when recovering from a disaster or incident.
    - **Periodically Test - DRP -- for continued compatibility** of the contingency facilities
    - Org recovery from disaster in which not all critical data was retained -- > **Issue with RPO**
    - Org DR plan - Auditor should **Primarily** verify that -- **regularly reviewed and updated**
    - Auditor reviewing DR of hot site used by financial institution --> **Greatest Concern** in this is --> **Disk space Utilization data are not kept current** --> without data of disks it can lead to a big disaster
    - **BEST Evidence of an org DR capabilities** ---> **RESULTS OF TESTS**
    - 🔥**MOST IMP** to review when conducting -- DR AUDIT --> **DATA BACKUPS ARE Performed Timely and Stored Offsite**
    - Data Mirroring Strategy --> When Data doesn't need be lost at all --> **Hence RPO is low** ---> **Low Data Loss --> Low RPO**
    - 🔥🔥🔥When **reviewing DRP** --> Auditor will be **MOST CONCERNED** with the lack of 🔴🔴**PROCESS OWNER INVOLVEMENT**
    - **IF Recovery TIME OBJECTIVE INCREASES --> 🔥🔥The Disaster Tolerance Increases** --> it means if 5 days are required than company can tolerate upto 5 days of without business.
    - DRP of a big org is changed and not tested --> **Impact is catastrophic service disruption**
    - When developing **DRP, the criteria for determining the acceptable downtime** should be --> **🔥🔥MAXIMUM TOLERABLE OUTAGE**
    - **BACKUP TECHNIQUES to use** --> MOST appropriate when an org requires **🔴🔴EXTREMELY GRANULAR** data restore points --> **CONTINUOUS DATA BACKUP** --> **SHORT /LOW RPO --> Continuous backup -- best option**
    - **LOWER RECOVERY TIME OBJECTIVE**  ---> **HIGHER COSTS** -- **💥HOT SITE**
    - **LOWER RPO --> Granular backup --> Continuous backup**
    - During DR test, auditor notes that **server is slow --**> **🔥Best possible scenario is to check the configuration of the server** (if some unauth actions done on server, then check logs)
    - **GREATEST CONCERN** when reviewing IT DR **TEST** ---> **🔥🔥During test, some of the backup systems were DEFECTIVE and NOT WORKING -- causing the test to FAIL**
    - **Frequent updating of which** of the following is key to the continued **effectiveness of a DR plan** ---> **🔴💥Contact information of key personnel**
    - **To address an org DR requirements, backup intervals should not exceed ---> 🔥🔥RPO**
    - **MOST EFFICIENT WAY TO DETERMINE EFFECTIVENESS OF THE DR PLAN** ------> **Efficient** --> **🔥Preparedness test**
    - In a contract with a hot, warm, or cold site, contractual provisions should PRIMARILY cover --> **🔥🔥Number of subscribers permitted to use a site at one time**🔥🔥
    - **MOST APPROPRIATE recovery strategy for a sensitive system with a high recovery time objective (RTO)**  ----> **High RTO --High disaster tolerance** --> **🔥Cold Site.**
    - **For structured DR -- MOST imp is that business continuity and disaster recover plan**  --- > **🔥TESTED REGULARLY**
    - **BEST METHOD TO ENSURE** --- critical IT system failures doesn't recur -->> **PERFORM ROOT CAUSE ANALYSIS**.
    - **Auditor reviewing most recent disaster recovery plan of an org** --> WHOSE APPROVAL IS IMP when determining availability of system resources required for the PLAN -------- >>> **🔥IT MANAGEMENT**
    - **AFTER TABLE TOP** ---> **NEXT STEP WOULD BE to be perform 🔥🔥FUNCTIONAL TESTS** -- which includes mobilization of the staff to exercise admin and org functions.
    - **TESTS FOR CO-ORDINATION in which relevant members participate --> Paper based test**
    - **Prepared-ness test is performed by EACH local office to test the adequacy of the preparedness of local operations.**
1. **Business Continuity PLAN**:
    - **Continuity Test Plan** that **simulates crash and uses actual resources** to cost effectively obtain evidence -----> 🔥**PREPAREDNESS TEST**
    - 🔴**Designing BCP for airlines** --> **MOST APPROPRIATE** method of data transfer/backup at an offsite location would be --> 🔥**SHADOW FILE PROCESSING** --> **Exact duplicates of the files are maintained** at the same site or at a remote site --> Two files are processed concurrently --> good for airlines. (**hot sites takes time - like few hours**)
    - **Most Imp in developing - BCP** -------->>>>> 🔥**Process Owner**
    - **MAJOR CONCERN**  for IS auditor --> Test results are not documented -- **Effectiveness of BCP can be best determined through tests**
    - **PRIMARY OBJECTIVE** of BCP test is --> **Identify limitations of BCP**
    - IS auditor **interviews key stakeholders in an org to determine whether they understand their roles and resp** ---> IS auditor is attempting to **🔥🔥evaluate the clarity and simplicity of the business continuity plans**.
    - During BCP -- **IS auditor noticed that the point at which** Situation is declared to be a crisis has not been identified **---->** MAJOR RISK associated with this is ---> 🔥🔥EXECUTION OF THE DR PLAN COULD BE IMPACTED**
    - **WHICH BEST helps define disaster recovery strategies** --> **🔥🔥MAX TOLERABLE Downtime and data loss**
    - **After disaster declaration**  --> Media creation date at a warm recovery site is based on **💥🔥RPO**
    - **Activation of an enterprise BCP should be based on pre-determined criteria** ---> that address the **🔥🔥🔴DURATION OF THE OUTAGE**.
    - **MOST effective business continuity plan** --> **Planning involves all user departments**
    - **Important to note that -- Responsibility of declaring a disaster is very imp**
    - **PRIMARY OBJECTIVE of BCP PROCESS** ---> is to **🔥🔥focus on managing and mitigating risk during recovery** of operations due to an event that affected operations
1. **For acceptable time period for the resumption of critical business processes** --> **🔥Both downtime costs and recovery costs need to be evaluated**
1. 🔴Unshielded twisted pair (UTP) cable for data communication over copper based has advantage of --> **reducing crosstalk**
1. Method of routing traffic through **split cable or duplicate cable** is **Diverse Cable** (SC DC)
1. **To verify correct version of a data file used for prod** --> Auditor should review **SYSTEM LOGS**
1. 🔥🔥Best audit procedures to determine if **unauth changes have been made to prod code** --> is to **🔥Examine object code to find instances of changes and trace them back to change control records**
1. 🔴🔥**IS auditor should review?** to ensure servers are optimally configured to support processing requirements --  **SERVER UTILIZATION REPORTS**
1. 🔥**Purpose of Code Signing** is -----> **🔴Software has not been subsequently modified.**
1. 🔥When reviewing process for continuous monitoring of the capacity and performance of IT resources an IS auditor **PRIMARILY** ensure that process is focused on --> **Accurate feedback on IT resource capacity**
1. **Business impact analysis (BIA)**
    - Best source of information for determining the criticality of application systems --> **Business Process Owners**
    - **PRIMARY PURPOSE of business impact analysis** ----> **Define recovery strategy**
1. 🔥Which of the following reports should an **IS auditor use to check compliance with a service level agreement's** requirement for uptime --> **Availability reports**
1. 🔥IS auditor use to determine if unauthorized modifications were made to production programs --> **Compliance Testing**
1. 🔴**MOST helpful** when evaluating the effectiveness and adequacy of a preventive computer maintenance program --> **System downtime log provides evidence regarding the effectiveness and adequacy of computer preventive maintenance program**
1. 🔥**Online pooling tool to monitor** and record application outages is the best option for an org to monitor the software as a service application availability.
1. 🔴**Help Desk Function** --> is a service oriented unit --> **End users must be advised before an incident can be regarded as closed**
1. POS --> **centralized communication processor for connecting to the banking** network. Best DR plan --> **Alternative standby processor at another network node** would be the best solution. The unavailability of the central communications processor would disrupt.
1. Evaluating programmed controls over password management, which of the following is the IS auditor **MOST** likely to rely on --> ****Validity check would be the most useful for the verification of passwords** because it would verify that the **required format** has been used - for example not using dictionary word.
1. **Reciprocal Agreement**:
    - **GREATEST RISK** of reciprocal in different companies -- Developments may result in h/w and s/w incompatibility.
    - **GREATEST RISK** in reciprocal of same business units --> Affected by **same disaster risk -- same incident.**
    - **Reciprocal MITIGATION OF RISKS** --> Ensure that partnering organizations are separated geographically
1. **Most effective in ensuring that production code and object code are in sync** -->  **Date and timestamp reviews of source and object code**
1. **Most Effective** to detect malicious activity in production program --> **Review of system log files**
1. **Recovery procedures for an Information processing facility** --  **BEST** BASED ON --> **Recovery Time Objective**
1. Maximum Tolerable Outage --> amount of time allowed for the recovery of a business function or resource after a disaster occurs: **represents a time by which the service must be restored**
1. 🔵Capacity Management
    - **Primary benefit** of IT Manager monitoring technical capacity --ensure that SLA req are met. Capacity Management has several objectives --> **MAIN IS SLA REQ**
1. Change Control Process
    - **Most efficient way to test effectiveness of change management process** ---> **Perform end to end walkthrough of the process**
    - IS auditor noted a **system crash caused by security patch** --> To provide assurance this wont happen again, auditor should --> **change management process is adequate**
1. **For proper SOD --> developer should have access to development only -- any code change should be again done as part of the development cycle**
1. Reporting and responsibility lines cannot always be established when auditing automated systems because --->  **ownership is difficult to establish where resources are shared**
1. **Library control S/w** --->  **Main objective** of Library control s/w is **changes have been authorized**
1. Auditor examining the security config of an OS should review --> **parameter settings**
1. **In Open Source s/w --> Identify and test suitable patches before applying them**
1. **Main Criterion for determining the severity level of a service disruption incident is** ------>>> **🔥DOWNTIME**
1. Performing preventive maintenance on electrical systems can result in **unexpected downtime** during office hours.
1. During recent app development --> auditor noted that sla was miss due to **incorrect priorities** --> **Support model was not properly developed and implemented**
1. **GREATEST RISK WHEN SERVER STORAGE IS NOT MANAGED PROPERLY** ---> **🔥🔥Server recovery work may not meet the recovery time objective**
1. **FIRST STEP in the execution of a problem management mechanism should be ---->🔥🔥 Exception Reporting**
1. **RAID LEVEL**  --- **PRIMARY PURPOSE** ----> 🔥Ensure Availability of data
1. **Important consideration in providing backup for online systems --> Ensuring periodic dumps of transaction logs**.
1. **Supervisory approval and review of critical changes** by the accountable managers in the enterprises are required to avoid and detect any unauth change.
1. **Incident response team** --> should handle this **first after a major incident** in a facility --> **🔥💥💥Containment at the facility**
1. **SERVICE DELIVERY OBJECTIVE -- SDO** --> is the **🔥level of service to be reached during the alternate process mode** until the normal situation is restored. This is directly related to the business needs.
1. **Configuration mgmt database (CMDB) -- is used to track configuration items** - CI. **OUT OF DATE CMDB in a large MNC could result in incorrect approvals**
1. **Incremental backup --> When first time full backup thereafter daily backup only --> MOST APPROPRIATE WHEN THERE IS LIMITED MEDIA CAPACITY**
1. What MITIGATES the best -- risk of backup media containing irreplaceable information being lost or stolen in transit ---> **DUPLICATE COPY**
1. **Emergency changes can be approved later on -- after the activity is finished**
1. MOST efficient strategy to backup large quantity mission critical data that needs to be supported 24hours a day --> **implementing a fault tolerant disk to disk backup solution**
1. For **PATCHES** ensure **🔥🔥APP OWNER and 🔴🔴DATA OWNER ARE** aware of the same and **their approvals** are taken.
1. **Emergency changes are done when** ---> there is a high probability of significant impact on operations.
1. For **Emergency changes, best accountability for the support personnel is to create a specific individual support ID -- when required** -- later on to be deleted.
1. **Automated tool can immediately provide a report which patches are running and applied**
1. **BEST ensures accountability when updating data directly in a production database** ---> **🔥🔥Review of Audit Logs**
1. **Performance criteria for the authentication servers would be helpful to evaluate thresholds of the system performance**
1. **MOST effective control for enforcing ACCOUNTABILITY ---> Implement a log management process**