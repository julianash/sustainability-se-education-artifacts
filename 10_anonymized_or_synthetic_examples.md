# Anonymized or Synthetic Examples

## Purpose

This document provides anonymized, generalized, or synthetic examples related to the sustainability-oriented requirements activity.

The examples are intended to illustrate the type of reasoning expected from students when transforming sustainability concerns into non-functional requirements, acceptance criteria, and possible verification evidence.

These examples do not reproduce student artifacts in their original form. They were prepared to support double-anonymous review and possible adaptation by other educators.

## How to use these examples

Educators may use these examples to:

- introduce the sustainability-oriented requirements activity;
- show students how broad concerns can be refined;
- illustrate the difference between functional and non-functional requirements;
- discuss acceptance criteria and verification evidence;
- support classroom discussion about sustainability dimensions;
- help students review and improve their own requirements.

Students may use these examples as inspiration, but they should adapt the reasoning to their own project context.

---

# Example 1: Technical Sustainability

## Context

A digital health system includes rules or thresholds that may change over time, such as values used for alerts, classifications, priorities, or recommendations.

## Sustainability-oriented reasoning

| Element | Example |
|---|---|
| Dimension | Technical |
| Sustainability concern | Maintainability of domain rules |
| Non-functional requirement | The system should allow relevant rules or thresholds to be updated without changing core application code. |
| Acceptance criterion | It should be possible to update a rule or threshold through a configuration mechanism and apply it to new cases without redeploying the core application. |
| Verification evidence | Inspection of configuration mechanisms and scenario-based tests using updated rules. |

## Discussion

This example illustrates how technical sustainability can be connected to maintainability and evolvability. Instead of hard-coding rules that may change, the system should support future updates with lower maintenance effort.

---

# Example 2: Individual Sustainability

## Context

A system sends notifications to users or professionals. If notifications are too frequent, redundant, or poorly prioritized, they may increase cognitive burden and contribute to alert fatigue.

## Sustainability-oriented reasoning

| Element | Example |
|---|---|
| Dimension | Individual |
| Sustainability concern | Cognitive burden and alert fatigue |
| Non-functional requirement | The system should organize notifications to reduce redundant alerts and support prioritization by severity. |
| Acceptance criterion | Notifications should be grouped or prioritized so that users can distinguish urgent from non-urgent information. |
| Verification evidence | Interface review and tests with simulated alerts of different priorities. |

## Discussion

This example illustrates how individual sustainability can be connected to attention, workload, cognitive burden, and well-being. The concern is not only whether the system sends notifications, but how these notifications affect users over time.

---

# Example 3: Social Sustainability

## Context

A digital health system may be used by people with different levels of digital literacy, accessibility needs, or familiarity with digital services.

## Sustainability-oriented reasoning

| Element | Example |
|---|---|
| Dimension | Social |
| Sustainability concern | Accessibility and inclusion |
| Non-functional requirement | The system should support users with different levels of digital literacy in critical workflows. |
| Acceptance criterion | A user should be able to complete a critical workflow using clear labels, consistent navigation, and accessible interface elements. |
| Verification evidence | Usability inspection, accessibility checklist, and task-based evaluation. |

## Discussion

This example illustrates how social sustainability can be connected to inclusion, access, and equity. The system should not only provide functionality, but also reduce barriers for different user groups.

---

# Example 4: Economic Sustainability

## Context

A system requires users or professionals to enter the same information multiple times in different parts of the workflow.

## Sustainability-oriented reasoning

| Element | Example |
|---|---|
| Dimension | Economic |
| Sustainability concern | Reduction of rework and duplicated data entry |
| Non-functional requirement | The system should avoid duplicated data entry when information is already available in the system. |
| Acceptance criterion | Information previously registered should be reused in related workflows when appropriate. |
| Verification evidence | Review of data flows and tests checking reuse of existing records. |

## Discussion

This example illustrates how economic sustainability can be connected to productivity, efficient use of time, and reduction of rework. In digital health systems, duplicated work may affect professionals, organizations, and quality of service.

---

# Example 5: Environmental Sustainability

## Context

A system stores files, records, logs, or uploaded documents. Without appropriate rules, it may store redundant or unnecessary data.

## Sustainability-oriented reasoning

| Element | Example |
|---|---|
| Dimension | Environmental |
| Sustainability concern | Resource-conscious data handling |
| Non-functional requirement | The system should avoid unnecessary storage of redundant files or repeated records. |
| Acceptance criterion | The system should prevent duplicate uploads or repeated records when equivalent data already exists. |
| Verification evidence | Inspection of data storage rules and log analysis. |

## Discussion

This example illustrates how environmental sustainability can be connected to data storage, resource use, and unnecessary processing. Environmental concerns in software should not be reduced only to paper reduction.

---

# Example 6: Privacy as an Individual and Social Concern

## Context

A digital health system manages sensitive information about users, patients, professionals, or services.

## Sustainability-oriented reasoning

| Element | Example |
|---|---|
| Dimension | Individual and social |
| Sustainability concern | Privacy and unnecessary exposure of sensitive information |
| Non-functional requirement | The system should restrict access to sensitive information according to user roles and the minimum information needed for each task. |
| Acceptance criterion | Users should only access sensitive information required for their role and workflow. |
| Verification evidence | Role-based access inspection, permission tests, and review of access logs. |

## Discussion

This example illustrates that some concerns may relate to more than one sustainability dimension. Privacy may affect individual autonomy and well-being, while also influencing trust and social relations among users, professionals, and institutions.

---

# Example 7: Interoperability as Technical and Economic Sustainability

## Context

A system needs to exchange information with another system or reuse information already available in an institutional workflow.

## Sustainability-oriented reasoning

| Element | Example |
|---|---|
| Dimension | Technical and economic |
| Sustainability concern | Interoperability and reduction of duplicated work |
| Non-functional requirement | The system should support data exchange with relevant external systems to avoid manual re-entry of information. |
| Acceptance criterion | Information available in an external source should be imported, synchronized, or reused when technically and ethically appropriate. |
| Verification evidence | Review of data flows, interface specification, integration tests, or prototype demonstration. |

## Discussion

This example shows that sustainability dimensions may overlap. Interoperability can support technical sustainability by improving evolvability and integration, while also supporting economic sustainability by reducing rework.

---

# From Vague Concern to Refined Requirement

Students often begin with broad statements. These statements can be useful starting points, but they should be refined into specific, contextualized, and assessable requirements.

| Initial formulation | Problem observed | Refined formulation | Possible evidence |
|---|---|---|---|
| The system should be accessible. | Too broad and difficult to assess. | The system should allow users to complete a critical workflow using clear labels, consistent navigation, and without relying only on color cues. | Accessibility checklist and task-based evaluation. |
| The system should be sustainable. | Too generic and not connected to a quality attribute. | The system should avoid storing duplicate files when equivalent documents are already associated with the same record. | Inspection of storage rules and duplicate-upload tests. |
| The system should send notifications. | Functional rather than non-functional. | The system should group repeated notifications to reduce alert fatigue and prioritize critical alerts. | Simulated notification scenarios and interface review. |
| The system should be easy to use. | Too subjective and difficult to verify. | The system should allow users to complete the main registration workflow with consistent labels, visible feedback, and no unnecessary repeated fields. | Usability inspection and task-based evaluation. |
| The system should be safe. | Too broad and not connected to a specific risk. | The system should prevent users from confirming a critical action without reviewing the relevant information and receiving a clear warning. | Scenario-based tests and interface inspection. |
| The system should save time. | Too generic and not assessable. | The system should reuse previously entered information in related workflows to reduce duplicated data entry. | Workflow review and tests checking data reuse. |

---

# Functional versus Non-Functional Formulations

The activity asks students to move beyond functional behavior and identify quality-oriented concerns.

| Functional formulation | Sustainability-oriented non-functional formulation |
|---|---|
| The system should send reminders. | The system should prioritize reminders by urgency and avoid sending redundant notifications. |
| The system should register users. | The registration workflow should minimize unnecessary fields and provide clear feedback to reduce user effort. |
| The system should generate reports. | Reports should present information clearly enough to support decision-making without requiring manual reorganization of data. |
| The system should upload documents. | The system should prevent duplicate document uploads when an equivalent file is already available. |
| The system should display patient information. | The system should display only the information required for the user's role and current task. |

---

# Examples of Verification Evidence

The following table summarizes types of evidence that students may propose.

| Type of evidence | Possible use |
|---|---|
| Scenario-based test | Assess whether the system behaves as expected in a realistic situation. |
| Interface review | Inspect whether screens, flows, labels, and feedback support user understanding. |
| Accessibility checklist | Assess whether interface elements follow accessibility-oriented criteria. |
| Usability evaluation | Observe whether users can complete tasks effectively and with acceptable effort. |
| Log analysis | Check whether notifications, errors, duplicated records, or access events occur as expected. |
| Metric | Quantify aspects such as duplicated entries, number of steps, response time, storage use, or number of alerts. |
| Expert review | Obtain feedback from a domain expert, instructor, or stakeholder. |
| Data flow review | Analyze whether information is reused appropriately and whether duplicated data entry is avoided. |
| Permission test | Check whether users can access only the information allowed for their role. |
| Prototype demonstration | Show how a requirement could be addressed in a partial implementation or mockup. |

---

# Reflection Questions

Students may use the following questions after reviewing the examples:

- Which example is closest to the project being developed by the team?
- Which sustainability dimension is easiest to identify in the project?
- Which dimension is least obvious?
- Are the team's current requirements mostly functional or non-functional?
- Are there broad concerns that need to be refined?
- What type of evidence would be feasible to collect or simulate in the course context?
- Which previous artifact could help identify additional sustainability concerns?
