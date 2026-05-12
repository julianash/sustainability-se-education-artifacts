# UML Modeling Activity

## Objective

The objective of this activity is to support students in modeling structural and behavioral aspects of the proposed software system and connecting these models to requirements-related artifacts.

In the educational experience, UML modeling was used after the product vision and product backlog activities. The models helped student teams reason about system structure, workflows, states, responsibilities, and consistency between requirements and design decisions.

## Learning goals

After completing this activity, students are expected to be able to:

- represent structural and behavioral aspects of a software system using UML diagrams;
- connect UML models to the product vision and product backlog;
- identify inconsistencies between requirements and design decisions;
- use models as communication and analysis tools;
- reason about system responsibilities, workflows, states, and components;
- identify missing requirements, ambiguities, risks, or quality concerns;
- revisit models from a sustainability-oriented perspective.

## Student task

Each team should produce UML diagrams representing relevant aspects of the proposed system.

The required diagrams are:

1. Component diagram
2. Activity diagram
3. State diagram

The diagrams should be coherent with the product vision and product backlog. They should not be treated only as notation exercises, but as artifacts that help the team analyze, communicate, and refine the proposed solution.

## Required diagram 1: Component diagram

The component diagram should represent the main software components of the system and their relationships.

Students should consider:

- main system modules or components;
- external systems, services, or APIs;
- databases or data repositories;
- dependencies among components;
- communication interfaces;
- responsibilities assigned to each component;
- possible integration points.

### Guiding questions

- What are the main components of the system?
- What is the responsibility of each component?
- How do the components communicate?
- Does the system depend on external services or systems?
- Where is data stored or accessed?
- Are the components coherent with the product backlog?
- Are there components that seem too broad or too vague?
- Are important responsibilities missing?

## Required diagram 2: Activity diagram

The activity diagram should represent a relevant workflow of the system.

Students should choose a workflow that is important for understanding the system behavior, user interaction, or process supported by the software.

Students should consider:

- start and end points;
- main activities;
- decision points;
- alternative flows;
- parallel flows, when relevant;
- actors or responsibilities, when applicable;
- exceptional or incomplete flows.

### Guiding questions

- Which workflow is being represented?
- Who initiates the workflow?
- What are the main activities?
- Are there decision points or alternative paths?
- Are there unnecessary or redundant steps?
- Is the workflow coherent with the product vision and backlog?
- Does the workflow reveal missing requirements?
- Could the workflow create excessive workload, confusion, or barriers for users?

## Required diagram 3: State diagram

The state diagram should represent the lifecycle of a relevant object, record, request, notification, appointment, task, or process in the system.

Students should choose an element whose behavior changes over time and whose states are important for understanding the system.

Students should consider:

- initial state;
- possible intermediate states;
- final state, when applicable;
- events that trigger transitions;
- valid and invalid transitions;
- exceptional states;
- responsibilities related to state changes.

### Guiding questions

- Which object, record, request, or process is being modeled?
- What is its initial state?
- What are the possible states?
- What events trigger transitions between states?
- Are there invalid or exceptional transitions?
- Are the states understandable and coherent?
- Does the state diagram reveal missing rules or requirements?
- Are there states that may affect user experience, workload, safety, privacy, or continuity of care?

## General modeling guidelines

Students should follow these general guidelines:

- Use clear and consistent names.
- Avoid excessive detail that makes the diagram difficult to understand.
- Represent the most relevant aspects of the system.
- Ensure that diagrams are coherent with each other.
- Ensure that diagrams are coherent with the product vision.
- Ensure that diagrams are coherent with the product backlog.
- Use diagrams to identify problems, not only to document decisions already made.
- Revise diagrams when inconsistencies or missing requirements are identified.

## Review questions

After creating the UML diagrams, each team should review them using the following questions:

- Are the diagrams consistent with the product vision?
- Are the diagrams consistent with the product backlog?
- Are the main components, workflows, states, or responsibilities represented?
- Are relationships, transitions, or flows clear?
- Do the diagrams help identify missing requirements?
- Do the diagrams reveal ambiguities or inconsistencies?
- Are there elements that are too generic or too detailed?
- Are the diagrams understandable to other team members?
- Could the diagrams support communication with stakeholders?
- Do the diagrams reveal quality concerns that should be considered later?

## Connection to sustainability-oriented requirements

The UML diagrams are used as input for the sustainability-oriented requirements activity.

Students should revisit their diagrams to identify sustainability concerns that may not have been explicit in the initial requirements.

For example:

- A component diagram may reveal maintainability, modularity, interoperability, or dependency concerns.
- An activity diagram may reveal unnecessary steps, duplicated work, accessibility barriers, or excessive professional workload.
- A state diagram may reveal risks related to incomplete processes, unclear responsibilities, user frustration, safety, privacy, or continuity of care.

By revisiting UML models through a sustainability-oriented lens, students are encouraged to understand modeling as part of a broader Software Engineering process that connects requirements, design, quality attributes, verification, and long-term socio-technical impacts.

## Common issues to avoid

Students should pay attention to the following issues:

- diagrams that are disconnected from the product vision;
- diagrams that do not correspond to backlog items;
- component diagrams that only show screens instead of system responsibilities;
- activity diagrams that omit important decision points;
- state diagrams that represent activities instead of states;
- unclear names for components, activities, states, or transitions;
- excessive technical detail without connection to requirements;
- diagrams that are too superficial to support analysis;
- inconsistencies among different diagrams;
- missing consideration of users, workflows, data, or external systems.

## Expected output

Each team should submit:

1. one UML component diagram;
2. one UML activity diagram;
3. one UML state diagram;
4. a brief explanation of how each diagram relates to the product vision and product backlog;
5. notes on inconsistencies, missing requirements, or quality concerns identified during modeling.

The diagrams may be revised after feedback and discussion.
