---
title: CISA Domain 1 Notes
tags: [Certification, CISA]
style: fill
color: danger
description: Important CISA Domain 1 notes.
---

Source: CISA Manual


## CISA Domain 1 Notes

**Risk = P * I (probability x impact).**

**Risk Assessment steps:**
- Identify critical assets/processes
- Identify relevant risks
- Do Impact Analysis
- Risk Prioritization 
- Risk Treatment

**Preventive, Corrective, Detective Controls** and their examples #preventive #detective #corrective. Continuous audit is detective.

**RISK BASED AUDIT** -Purpose is **Material areas are addressed first** -- (High impact doesn't really mean High Risk).

**Types of Testing** #typesoftesting #compliancetesting #substantivetest:
1. Compliance Test - Attribute Sampling (CA). Substantive Test - Variable Sampling (SV). **Compliance check with control (CCC)**. **Substantive test integrity of transactions (SIT)**. #shortcuts
2. **Compliance Testing:** It is **gathering of evidences for the purpose of testing** an enterprise's **compliance with control procedures.** This differs from **Substantive Test** in which **evidences** are **gathered to check for the integrity of individual transactions**, data or other information.
3. **Substantive Testing:** Obtaining **evidence on the completeness, accuracy or existence of activities or transactions** during the audit period. #mostimportant
4. Control Testing
5. Analytical Testing

**Compliance testing and substantive testing**:
- CT - verification of process : ST - verification of data or transactions
- CT - checks for presence of controls: ST - Checks for completeness, accuracy and validity of data.
- CT- Attribute sampling: ST - Variable Sampling.
- In any given scenario compliance testing will be performed first.
- Result/outcome of compliance testing will be form basis for substantive testing. Strong CT strong internal controls -- ST can be waived.
	
**Types of RISKs** #typesofrisks #inherentrisk #residualrisk #controlrisk #compliancerisk:
1. **Inherent Risk** - **Risk is high** due to n**umber of users and business areas** that may be affected. **Inherent risk is risk level or exposure** **without considering the actions** that **management has taken** or might take. --- **GROSS RISK or RISK BEFORE CONTROLS**
2. Compliance Risks - Due to nonconformity of the laws
3. Control Risks - issues with the implementation of the controls. Risk that a misstatement could occur but may not be detected or corrected or prevented
4. Residual Risks - risks which are left after control implementation
5. Detection Risk - Risk that **auditor** fails to detect.**IS auditor certifying existence of system without inadequate control** is **Detection Risk**
6. **Audit RISK = Inherent * Control * Detection**
	
**Risk Treatment**
- Risk mitigation
- Risk transfer
- Risk avoidance
- Risk acceptance
	
**EDI - electronic data interchange** #functionalacknowledgements #EDI
1. **RISK** - **Lack of authorization transactions**
2. Acting as an audit trail for edi **functional acknowledgements** are one of the main controls used in **data mapping**

**Sampling and its type** #sampling
1. **Stratified Random Sampling** - Most appropriate for testing automated invoice authorization controls to ensure that **exceptions are not made for specific users**. **Stratification** is the process of **dividing a population** into **sub population** with **similar characteristics explicitly defined**, so that each **sampling unit can only belong to only one stratum**.This method of sampling ensures that all sampling units in each subgroup have a known, non zero chance of selection. #sampling
2. **Attribute Sampling** -- Compliance testing -- To check compliance of the control. If requests are not approved, then attribute sampling and compliance testing to be done. **CA** - compliance attribute and **SV** - Substantive Variable. #attributesampling ---- **Attribute sampling is a sampling model that is used to estimate the rate of occurrence of a specific quality (attribute)**
3. **Variable Sampling** -- Used in **Substantive testing** situations and **deals with population characteristics that vary such as Monetary values and weights**
4. **Stop or Go** - When expected occurrence rate is extremely low
5. Judgement Sampling - Based on the judgement of Auditor
	
**Audit Charter**  -- Establishes the role of the information systems audit function. Charter should describe overall **authority, scope and responsibilities** of the audit function. Should be approved by highest level or **Audit committee** . #auditcharter
- Static document
- Authority and responsibility of Audit Function
- Approved by top management
	
**Engagement Letter** - Objective and scope of each IS audit should be agreed on engagement letter. Manages the audit exercise.

**CAAT - Computer assisted auditing techniques** -- Assessing and analyzing digital data to collect relevant audit evidences. **CAATs are tools** used for **accessing data** in an electronic form from **diverse s/w environments, record formats, etc.** CAATs serve as **useful tools for collecting and evaluating audit evidence** according to audit objectives and can create efficiencies for collecting this evidence.

**Control Self Assessment**  --> Success of CSA depends on Line managers assuming a portion of **responsibility for control monitoring** . Role of Auditor - facilitator. #CSA

**Continuous Audit - Detective** in nature (not preventive) - CAD --> **Frauds can be detected** more quickly in continuous audit.

**Types of Audits:**
- **Forensic Audit** -- Primary purpose is to **systematic collection and analysis of evidence after a system irregularity** -- PCI DSS forensic breach analysis. #typesofaudits

**Data Mining and Auditing Software Tool** - Accurately capture data from organization system without causing performance problems.

**Sampling doesn't give enough assurance** - develop alternate test procedure #sampling

Efficiency imp but **design as per the policy and procedures** is critical for compliance test

**Generalized Audit Software** - Include mathematical computations, stratifications, stat analytics, sequence checking, duplicate checking and re-computations. Auditor can use GAS s/w for payroll recompute #generalizedauditsoftware

**Evidences obtained from independent third-party** is more relevant

Tracing a transaction back is a part of reconcilliation

**Corrective action take by auditee, IS auditor should include in the final report still**

**Best way for data accuracy - verify input forms of payroll reports**

**When selecting audit procedures** - IS auditor should use professional judgement to ensure that -->  **Sufficient evidences will be collected**

**Substantive Testing** - it includes **gathering of evidences to evaluate the integrity** - **completeness, accuracy and validity of individual transactions,** data or other information. **Conducting a physical count of the tape inventory** is a substantive test. #substantivetest

After initial investigation - Auditor **believe fraud** may be present --> Next action -->  **Expand the activities**

**User performs IT and account function performed by one user -- Compensating control --** reviews of conducted by users supervisor **best compensating control is to review computer log files that show individual transactions** .

**System developer moves into audit department to be IT auditor** -- when he performs audit in dev that might be considered as a **self-audit**

Analyze audit trails on critical servers to discover **potential anomalies in user or system behavior** --- **Trend/Variance Tools** (Behavior Trend - BT) #trendvariancetools

**Heuristic scanning tools** - **virus scanning type** tools looking for **infected** traffic

**FIRST Step** -- performed **prior to creating a risk ranking** for the annual internal IS audit plan --> **Auditor must define the audit universe by considering the IT strategic plan, org structure and authorization matrix**. #audituniverse

**Business process identified**  Next process is what? -- **Identify Control Objectives and Activities**

**External IS auditor -- discovers that systems in scope were implemented by an associate-- What should auditor do?**  --- **Disclose the issue to client**

**First step in audit planning stage** -- Development of **risk assessment**.

Auditor reviewing **risk and controls of a banks wire transfer system**. To ensure banks **financial risk is properly addressed**, IS auditor will most likely review -- **Wire Transfer Procedures -- Because it includes SOD**. This prevent fraud, as one person initiate, approve and wire. Hence procedures to be reviewed

**Audit manager reviews the staff audit papers** --> **Professional Standards** as ISACA requires **supervision** of audit staff.

**Centralized AV installed on each PC** has **latest signatures** files and installs latest **signatures before allowing a PC to connect** to the network - **Corrective control**

**Best control** to check the **effectiveness of controls** related to calculation --> **Reperformance**

IS Auditor finds **DRP doesn't cover all systems for critical businesses** --> **Alert and evaluate impact**.

**Table Look up is preventive control** where auditor **checks input data** against predefined tables

**Auditee disagrees with auditor --> Next action is to discuss with IT auditors manager.**

The **audit universe ideally lists all of the processes** that may be considered for audit. Each of these processes may undergo a qualitative or quantitative risk assessment by evaluating the risk in respect to defined, relevant risk factors. The risk factors are those factors that influence the frequency and/or business impact of risk scenarios.

The audit plan can then be constructed to include all of the processes that are rated “high,” which would represent the ideal annual audit plan.

Transaction authorization is the biggest EDI risk.

Controls should ensure that all inbound EDI transactions are accurately and completely received (communication phase), translated (translation phase),passed to an application (application interface phase), and processed only once.

Perform edit checks to identify erroneous, unusual or invalid transactions prior to updating an application.

Use control totals on receipt of transactions to verify the number and value if transactions to be passed to each application; reconcile totals between applications and with trading partners.

Use control techniques in the processing of individual transactions such as check digits (appended to data to ensure that the original data have not
been altered and used to detect transposition and transcription errors) on control fields, loop or repeat counts.

The significance to an IS auditor is the high number of systems and applications using these technologies. The larger the scale of integration, the more IS auditor attention is required. Highly integrated CIM projects require the same attention from an IS auditor as the ERPs previously mentioned in this chapter.

Decision trees—Use of questionnaires to lead the user through a series of choices, until a conclusion is reached. Flexibility is compromised because the user must answer the questions in an exact sequence.

Semantic nets—Use of a graph in which the nodes represent physical or conceptual objects and the arcs describe the relationship between the nodes. Semantic nets resemble a data flow diagram and make use of an inheritance mechanism to prevent duplication of dat

A control measure is defined as an activity contributing to the fulfillment of a control objective. Both the control objective and control measure serve the
decomposition of the strategic-level goals into such lower-level goals and activities that can be assigned as tasks to the staff.

One critical success factor (CSF) is to conduct a meeting with the business unit representatives (including appropriate and relevant staff and management) to identify the business unit’s primary objective—to determine the reliability of the internal control system.

Continuous auditing—Enables an IS auditor to perform tests and assessments in a real-time or near-real-time environment. Continuous
auditing is designed to enable an IS auditor to report results on the subject matter being audited within a much shorter time frame than under a traditional audit approach

Continuous monitoring—Used by an organization to observe the performance of one or many processes, systems or types of data. For example, real-time antivirus or IDSs may operate in a continuous monitoring fashion.

Continuous auditing aims to provide a more secure platform to avoid fraud and a real-time process aimed at ensuring a high level of financial control.

It is important to validate the source of the data used for continuous auditing and note the possibility of manual changes

Continuous auditing has an intrinsic edge over point-in-time or periodic auditing because it captures internal control problems as they occur, preventing negative effects. Implementation can also reduce possible or intrinsic audit inefficiencies such as delays, planning time, inefficiencies of the audit process, overhead due to work segmentation, multiple quality or supervisory reviews, or discussions concerning the validity of findings

Full top management support, dedication, and extensive experience and technical knowledge are all necessary to accomplish continuous auditing, while minimizing the impact on the underlying audited business processes.

**An IS auditor should consider the purpose of the sample:**
- Compliance testing/test of controls—An audit procedure **designed to evaluate the operating effectiveness of controls** in preventing, or detecting and correcting, material weaknesses.
- Substantive testing/test of details—An audit procedure designed to detect material weaknesses **at the assertion level**
- A substantive test **substantiates the integrity of actual processing**. It provides evidence of the validity and integrity of the balances in the financial statements and the transactions that support these balances. An IS auditor could use **substantive tests to test for monetary errors directly affecting financial statement balances or other relevant data of the organization**. Additionally, an **IS auditor might develop a substantive test to test the
completeness and accuracy of report data**. To perform this test, the IS auditor might use a statistical sample, which will allow the IS auditor to develop a conclusion regarding the accuracy of all of the data.
- A direct correlation exists between the level of internal controls and the amount of substantive testing required. If the results of testing controls (compliance tests) reveal the presence of adequate internal controls, then minimizing the substantive procedures could be justified.

Statistical sampling permits an IS auditor to quantify the probability of error (confidence coefficient).