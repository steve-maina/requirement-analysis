# Requirement Analysis in Software Development.
This repo focuses on crafting a comprehensive foundation for software development by documenting, analyzing, and structuring requirements. Through a series of well-defined tasks, learners will create a detailed blueprint of the requirement analysis phase for a booking management system. This project simulates a real-world development scenario, emphasizing clarity, precision, and structure in defining requirements to set the stage for successful project execution.

## What is Requirement Analysis?
Requirement Analysis is a critical phase in the software development lifecycle (SDLC) where the project team gathers, analyzes, and defines the requirements of the software product to be developed. This process ensures that all stakeholders have a clear and mutual understanding of what the system should do and how it should perform.

## Why is Requirement Analysis Important?

- **Clarity and Understanding:** It helps in understanding what the stakeholders expect from the software, reducing ambiguity.
- **Scope Definition:** Clearly defines the scope of the project, which helps in preventing scope creep.
- **Basis for Design and Development:** Provides a solid foundation for designing and developing the system.
- **Cost and Time Estimation:** Facilitates accurate estimation of project cost, resources, and time.
- **Quality Assurance:** Ensures that the final product meets the specified requirements, leading to higher customer satisfaction.

## Key Activities in Requirement Analysis.

### 1. Requirement Gathering 🗂️
- **Interviews:** Conducting interviews with stakeholders to gather detailed information about their needs and expectations.
- **Surveys/Questionnaires:** Distributing surveys to collect requirements from a larger audience.
- **Workshops:** Organizing workshops with stakeholders to discuss and gather requirements.
- **Observation:** Observing end-users in their working environment to understand their needs.
- **Document Analysis:** Reviewing existing documentation and systems to understand current functionalities and requirements.
### 2. Requirement Elicitation ✍️
- **Brainstorming:** Conducting brainstorming sessions to generate ideas and gather requirements.
- **Focus Groups:** Holding focus group discussions with selected stakeholders to gather detailed requirements.
- **Prototyping:** Creating prototypes to help stakeholders visualize the system and refine their requirements.
### 3. Requirement Documentation 📚
- **Requirement Specification Document:** Creating a detailed document that lists all functional and non-functional requirements.
- **User Stories:** Writing user stories to describe functionalities from the user’s perspective.
- **Use Cases:** Creating use case diagrams to show interactions between users and the system.
### 4. Requirement Analysis and Modeling 📊
- **Requirement Prioritization:** Prioritizing requirements based on their importance and impact on the project.
- **Feasibility Analysis:** Assessing the feasibility of requirements in terms of technical, financial, and time constraints.
- **Modeling:** Creating models (e.g., data flow diagrams, entity-relationship diagrams) to visualize and analyze requirements.
### 5. Requirement Validation ✅
- **Review and Approval:** Reviewing the documented requirements with stakeholders to ensure accuracy and completeness.
- **Acceptance Criteria:** Defining clear acceptance criteria for each requirement to ensure they meet the expected standards.
- **Traceability:** Establishing traceability matrices to ensure all requirements are addressed during development and testing.

## Types of Requirements.
### Functional Requirements ⚙️
- **Definition:** Describe what the system should do.
- **Examples:** search hotels, booking a hotel, pay for a room.

### Non-functional Requirements 🛡️
- **Definition:** Describe how the system should perform.
- **Examples:** Performance, security, scalability, usability, reliability.

## Use Case Diagrams

Use case diagrams show how different users (actors) interact with the system to achieve specific goals (use cases).

### Creating Use Case Diagrams:

- Identify actors (e.g., guest, registered user, admin).
- Define use cases (e.g., search properties, book property, manage listings).
- Draw interactions between actors and use cases.

### Benefits of Use Case Diagrams:

- Provide a clear visual representation of system functionalities.
- Help in identifying and organizing system requirements.
- Facilitate communication among stakeholders and development team.

![Use Case Diagram Example](https://drive.google.com/uc?export=view&id=1XXrzffWoE4RFqShNE8CNqJqbHXJ32DJf)

https://drive.google.com/file/d/1XXrzffWoE4RFqShNE8CNqJqbHXJ32DJf/view?usp=drive_link

# Acceptance Criteria
Acceptance criteria are conditions that a feature must meet to be accepted by the stakeholders.

## Why Acceptance Criteria Matter in Requirement Analysis

1. **Clarifies Requirements**  
   AC removes ambiguity by translating high-level requirements into specific, testable conditions. This helps stakeholders, developers, and testers have a shared understanding of the feature.

2. **Guides Development**  
   Developers use AC to understand what exactly needs to be built and how success will be measured.

3. **Improves Testing**  
   QA teams rely on AC to create test cases. If a feature meets all its acceptance criteria, it can be confidently considered “done.”

4. **Enables Better Communication**  
   AC serves as a communication bridge between business stakeholders and the technical team, reducing misinterpretation of requirements.

5. **Facilitates Agile and Iterative Development**  
   In Agile frameworks like Scrum, AC is essential to defining "Done" for each user story in a sprint.

## Example: Acceptance Criteria for a Checkout Feature in a Booking Management System

**Acceptance Criteria**:

1. **AC1: Input Validation**  
   - All required fields (name, email, payment details) must be filled before proceeding.
   - The system should display error messages for missing or invalid inputs.

2. **AC2: Payment Processing**  
   - The system should securely process the payment via integrated payment gateways (e.g., Stripe or PayPal).
   - If payment fails, an error message should inform the user with possible next steps.

3. **AC3: Confirmation Page**  
   - After successful payment, a confirmation page must show the booking details, amount paid, and a confirmation number.

4. **AC4: Email Notification**  
   - The system must send a confirmation email to the user with booking and payment details within 5 minutes of checkout.

5. **AC5: Booking Record Creation**  
   - A new booking record must be created in the database upon successful checkout, with a unique booking ID.

6. **AC6: Mobile Compatibility**  
   - The checkout process should be responsive and fully functional on mobile devices.

