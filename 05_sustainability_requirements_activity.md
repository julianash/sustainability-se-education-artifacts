# Sustainability-Oriented Requirements Activity

## Objective

The objective of this activity is to help students identify sustainability concerns in their software projects and transform them into non-functional requirements, acceptance criteria, and possible verification evidence.

In the educational experience, this activity was conducted after students had already worked on product vision, product backlog, and UML models. At this point, teams had enough information about their projects to revisit previous decisions and analyze the system beyond functional behavior.

The activity was designed to make sustainability more concrete and actionable in Software Engineering education, connecting sustainability dimensions to requirements, quality attributes, design decisions, and verification strategies.

## Learning goals

After completing this activity, students are expected to be able to:

- identify sustainability concerns in software projects;
- recognize sustainability as a multidimensional concern;
- distinguish functional requirements from non-functional requirements;
- connect sustainability concerns to quality attributes and socio-technical impacts;
- formulate sustainability-oriented non-functional requirements;
- define acceptance criteria for non-functional requirements;
- propose possible verification evidence;
- revisit existing Software Engineering artifacts through a sustainability-oriented lens;
- discuss how software decisions may affect users, stakeholders, organizations, and long-term system evolution.

## Activity context

Before this activity, each team should have produced or revised:

- product vision;
- product backlog;
- user stories;
- acceptance criteria;
- UML component diagram;
- UML activity diagram;
- UML state diagram.

These artifacts are used as input for identifying sustainability concerns and transforming them into requirements-related elements.

## Sustainability dimensions

Students should consider five sustainability dimensions:

| Dimension | Guiding idea |
|---|---|
| Technical | How can the system remain maintainable, evolvable, testable, interoperable, reliable, and understandable over time? |
| Social | How can the system affect inclusion, accessibility, equity, collaboration, trust, participation, and social practices? |
| Economic | How can the system affect costs, rework, productivity, resource allocation, long-term viability, and institutional sustainability? |
| Environmental | How can the system affect resource use, data storage, device use, energy consumption, material waste, and unnecessary processing? |
| Individual | How can the system affect users' autonomy, cognitive load, workload, well-being, privacy, attention, and digital fatigue? |

## Activity steps

Each team should complete the following steps.

### Step 1: Revisit existing artifacts

Teams should revisit their product vision, product backlog, acceptance criteria, and UML models.

They should look for sustainability concerns that may be explicit or implicit in these artifacts.

Guiding questions:

- Does the product vision reveal relevant users, stakeholders, risks, constraints, or assumptions?
- Do backlog items suggest quality concerns that are not yet explicit?
- Do UML diagrams reveal unnecessary steps, dependencies, states, responsibilities, or risks?
- Are there concerns related to maintainability, accessibility, workload, trust, privacy, resource use, or long-term viability?
- Are there relevant concerns that were not considered in the initial requirements?

### Step 2: Identify sustainability concerns

Teams should identify sustainability concerns related to one or more dimensions.

A sustainability concern may refer to a quality, constraint, risk, impact, or long-term consequence associated with the software system.

Examples of sustainability concerns include:

- maintainability of clinical or domain rules;
- cognitive burden caused by excessive notifications;
- accessibility barriers for users with different levels of digital literacy;
- duplicated data entry and rework;
- unnecessary storage of redundant files;
- privacy risks associated with sensitive health information;
- excessive dependency on a specific technology or external service;
- lack of interoperability with existing systems;
- professional workload increase;
- lack of clarity in critical workflows.

### Step 3: Select relevant concerns

Teams should select one or more concerns that are relevant to their project context.

The selected concerns should be specific enough to support discussion and refinement.

Students should avoid generic statements such as:

- "The system should be sustainable."
- "The system should be accessible."
- "The system should be easy to use."
- "The system should be good for users."

These statements may be useful as initial ideas, but they should be refined into more specific and assessable requirements.

### Step 4: Transform concerns into non-functional requirements

Each selected concern should be transformed into a non-functional requirement.

A non-functional requirement should express a quality, constraint, condition, or expected property of the system.

Students should consider:

- What quality should the system preserve?
- What constraint should the system respect?
- What impact should the system reduce or avoid?
- What should be improved in terms of usability, accessibility, maintainability, privacy, workload, reliability, or resource use?
- Is the requirement specific to the project context?
- Is the requirement discussable and reviewable?

### Step 5: Define acceptance criteria

For each non-functional requirement, teams should define at least one acceptance criterion.

The acceptance criterion should help assess whether the requirement is satisfied.

Students should consider:

- What observable condition would indicate that the requirement was addressed?
- What would be checked, tested, inspected, measured, or reviewed?
- Is the criterion specific enough to support evaluation?
- Is the criterion realistic in the context of the course project?

### Step 6: Propose verification evidence

For each requirement, teams should propose possible verification evidence.

Verification evidence may include:

- tests;
- inspections;
- checklists;
- metrics;
- log analysis;
- scenario-based evaluation;
- usability evaluation;
- accessibility review;
- expert review;
- stakeholder feedback;
- comparison between alternative workflows;
- review of data flows;
- review of storage rules;
- prototype evaluation.

The evidence does not necessarily need to be fully collected during the course. However, students should be able to explain what type of evidence could be used to assess the requirement.

### Step 7: Present and discuss results

Each team should present the sustainability concerns, non-functional requirements, acceptance criteria, and verification evidence identified during the activity.

The presentation should emphasize:

- the project context;
- the selected sustainability dimensions;
- the reasoning used to transform concerns into requirements;
- the connection with previous artifacts;
- difficulties encountered during the activity;
- possible improvements to the product vision, backlog, or UML models.

## Suggested template

| Dimension | Sustainability concern | Non-functional requirement | Acceptance criterion | Verification evidence |
|---|---|---|---|---|
| Technical, social, economic, environmental, or individual | Concern identified by the team in relation to the project | Requirement expressing a quality, constraint, or expected property of the system | Condition that helps assess whether the requirement is satisfied | Test, inspection, metric, log, review, checklist, or other evidence source |

## Guiding questions by dimension

### Technical sustainability

- Can the system be maintained and evolved over time?
- Are there risks of excessive technical debt?
- Are clinical, business, or domain rules separated from core application code?
- Is the system modular enough to support change?
- Is the system testable?
- Does the system need to interoperate with other systems?
- Are dependencies clearly identified?
- Could future maintenance be difficult because of design decisions?
- Are there risks related to reliability, availability, or data consistency?

### Social sustainability

- Does the system support different user profiles?
- Could the system exclude users with lower digital literacy?
- Does the system support accessibility?
- Could the system affect trust among users, professionals, or institutions?
- Could the system reinforce inequalities or barriers to access?
- Does the system support collaboration among stakeholders?
- Are communication and responsibilities clear?
- Could any group be negatively affected by the way the system is designed?

### Economic sustainability

- Could the system reduce or increase rework?
- Could it duplicate existing processes or data entry?
- Does the system require resources that may be difficult to sustain?
- Can the solution be maintained with realistic institutional resources?
- Could it support more efficient use of time or infrastructure?
- Are there costs related to deployment, training, maintenance, or support?
- Does the solution depend on technologies that may become expensive or unavailable?
- Could the system reduce waste of professional time or organizational effort?

### Environmental sustainability

- Does the system avoid unnecessary data storage?
- Does it reduce redundant files, records, or processing?
- Does the solution depend on devices or infrastructure that may generate avoidable waste?
- Are there opportunities to reduce paper use, unnecessary printing, or repeated data collection?
- Are logs, files, or records managed consciously?
- Could the system avoid unnecessary notifications, messages, or duplicated transactions?
- Could the system support more efficient use of computational resources?
- Are there lifecycle concerns related to devices, sensors, or hardware?

### Individual sustainability

- Could the system increase cognitive burden?
- Could it generate alert fatigue or notification overload?
- Does it support user autonomy?
- Does it protect privacy and reduce unnecessary exposure of sensitive information?
- Could it increase or reduce professional workload?
- Is the information presented clearly enough for the intended users?
- Could the system cause frustration, confusion, or dependence?
- Does the system respect users' attention, time, and well-being?
- Does the system support safe and understandable decision-making?

## Examples

| Dimension | Sustainability concern | Non-functional requirement | Acceptance criterion | Verification evidence |
|---|---|---|---|---|
| Technical | Maintainability of domain rules | The system should allow relevant rules or thresholds to be updated without changing core application code. | It should be possible to update a rule through a configuration mechanism and apply it to new cases without redeploying the core application. | Inspection of configuration mechanisms and scenario-based tests using updated rules. |
| Individual | Cognitive burden and alert fatigue | The system should organize notifications to reduce redundant alerts and support prioritization by severity. | Notifications should be grouped or prioritized so that users can distinguish urgent from non-urgent information. | Interface review and tests with simulated alerts of different priorities. |
| Social | Accessibility and inclusion | The system should support users with different levels of digital literacy in critical workflows. | A user should be able to complete a critical workflow using clear labels, consistent navigation, and accessible interface elements. | Usability inspection, accessibility checklist, and task-based evaluation. |
| Economic | Reduction of rework | The system should avoid duplicated data entry when information is already available in the system. | Information previously registered should be reused in related workflows when appropriate. | Review of data flows and tests checking reuse of existing records. |
| Environmental | Resource-conscious data handling | The system should avoid unnecessary storage of redundant files or repeated records. | The system should prevent duplicate uploads or repeated records when equivalent data already exists. | Inspection of data storage rules and log analysis. |

## From vague concern to refined requirement

Students may initially formulate broad or vague concerns. These should be refined into more specific requirements.

| Initial formulation | Problem observed | Refined formulation | Possible evidence |
|---|---|---|---|
| The system should be accessible. | Too broad and difficult to assess. | The system should allow users to complete a critical workflow using clear labels and without relying only on color cues. | Accessibility checklist and task-based evaluation. |
| The system should be sustainable. | Too generic and not connected to a quality attribute. | The system should avoid storing duplicate files when equivalent documents are already associated with the same record. | Inspection of storage rules and duplicate-upload tests. |
| The system should send notifications. | Functional rather than non-functional. | The system should group repeated notifications to reduce alert fatigue and prioritize critical alerts. | Simulated notification scenarios and interface review. |
| The system should be easy to use. | Too subjective and difficult to verify. | The system should allow users to complete the main registration workflow with consistent labels, visible feedback, and no unnecessary repeated fields. | Usability inspection and task-based evaluation. |

## Review questions

After completing the table, teams should review their work using the following questions:

- Is the sustainability concern connected to the project context?
- Is the sustainability dimension clearly indicated?
- Is the requirement non-functional rather than merely functional?
- Is the requirement specific enough to be discussed and reviewed?
- Is the requirement aligned with the product vision, backlog, or UML models?
- Is there at least one acceptance criterion?
- Is the acceptance criterion assessable?
- Is there at least one possible source of verification evidence?
- Is the proposed evidence coherent with the requirement?
- Could the requirement influence design, testing, implementation, or future maintenance decisions?

## Common issues to avoid

Students should pay attention to the following issues:

- concerns that are too generic;
- requirements that only restate functional behavior;
- requirements that are disconnected from the project context;
- requirements that are not related to any sustainability dimension;
- acceptance criteria that are vague or subjective;
- evidence that does not actually help assess the requirement;
- focusing only on technical sustainability and ignoring human-centered dimensions;
- treating environmental sustainability only as paper reduction;
- proposing requirements that are unrealistic for the project context;
- failing to connect the activity to previous artifacts.

## Expected output

Each team should submit a completed table containing at least:

1. one sustainability dimension;
2. one sustainability concern;
3. one non-functional requirement;
4. one acceptance criterion;
5. one possible source of verification evidence.

Teams are encouraged to include more than one sustainability dimension when relevant.

Each team should also include a brief reflection explaining:

- which previous artifacts helped identify the concern;
- which sustainability dimension was easiest to address;
- which sustainability dimension was most difficult to address;
- whether the activity revealed missing or implicit requirements;
- whether the team would revise the product vision, backlog, or UML models after the activity.

## Connection to previous and later activities

This activity connects previous Software Engineering artifacts to sustainability-oriented reasoning.

The product vision helps identify users, stakeholders, risks, constraints, assumptions, and expected value.

The product backlog helps identify functional behavior that may involve implicit quality concerns.

The UML diagrams help identify workflows, components, states, responsibilities, dependencies, and possible design issues.

The sustainability-oriented requirements produced in this activity may support later discussions about design decisions, testing strategies, usability evaluation, accessibility, privacy, maintainability, and long-term system impacts.

By transforming sustainability concerns into non-functional requirements, acceptance criteria, and verification evidence, students are encouraged to understand sustainability not only as an abstract value, but as a practical concern that can influence Software Engineering decisions.
