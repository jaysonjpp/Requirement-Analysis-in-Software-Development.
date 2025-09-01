# Requirement-Analysis-in-Software-Development.

This repository provides a structured overview of requirement analysis in software development.  
It explains key concepts, importance, activities, types of requirements, and includes diagrams and examples to illustrate how requirements shape successful software projects.


## What is Requirement Analysis?

Requirement Analysis is the process of identifying, documenting, and managing the needs and expectations of stakeholders for a software system.  
It acts as a bridge between stakeholders and developers, ensuring that the final product aligns with the business goals.

Requirement Analysis is critical in the Software Development Life Cycle (SDLC) because:
- It clarifies what needs to be built.
- It prevents misunderstandings between clients and developers.
- It lays the foundation for design, implementation, and testing.

## Why is Requirement Analysis Important?

Requirement Analysis is important in SDLC because:

1. **Prevents Project Failures**  
   Clearly defined requirements reduce the chances of project delays, cost overruns, or incomplete features.

2. **Improves Communication**  
   It ensures all stakeholders (clients, developers, testers, managers) share the same understanding of the project goals.

3. **Saves Time and Resources**  
   By identifying issues early, Requirement Analysis reduces rework during development and testing.


## Key Activities in Requirement Analysis

The major activities involved in requirement analysis are:

- **Requirement Gathering**: Collecting needs from stakeholders through interviews, surveys, or observations.
- **Requirement Elicitation**: Digging deeper into the gathered requirements to uncover hidden or unclear needs.
- **Requirement Documentation**: Recording requirements in a structured format such as SRS (Software Requirement Specification).
- **Requirement Analysis and Modeling**: Analyzing relationships, dependencies, and modeling requirements using diagrams.
- **Requirement Validation**: Ensuring requirements are complete, consistent, feasible, and meet stakeholder expectations.


## Types of Requirements

### Functional Requirements
Functional requirements define **what the system should do**.  
They describe the behavior and functions of the system.

**Examples for Booking Management System:**
- Users can create an account and log in.
- Customers can search for available bookings by date.
- Users can make, cancel, or update a booking.
- Admin can manage available slots and confirm bookings.

### Non-functional Requirements
Non-functional requirements describe **how the system should perform** rather than what it should do.

**Examples for Booking Management System:**
- The system should handle at least 500 concurrent users.
- The booking response time should not exceed 2 seconds.
- The system must be available 99.9% of the time.
- User data must be encrypted to ensure security.


git add alx-booking-uc.png README.md
git commit -m "Added use case diagram image"
git push origin main


## Use Case Diagrams

Use Case Diagrams visually represent the interaction between users (actors) and the system.  
They help clarify system functionality at a high level.

Below is a sample Use Case Diagram for the Booking Management System:

![Use Case Diagram](./alx-booking-uc.png)

## Acceptance Criteria

Acceptance Criteria are the conditions that a software product must meet to be accepted by stakeholders.  
They define the boundaries of a user story or feature and ensure that the functionality works as intended.

### Importance of Acceptance Criteria
- Provides clear guidelines for developers and testers.
- Prevents ambiguity in requirements.
- Ensures stakeholder satisfaction when conditions are met.

### Example (Checkout Feature – Booking Management System)
**Acceptance Criteria:**
- The system must allow users to select a booking and proceed to checkout.
- Users must be able to enter payment details securely.
- The system should confirm payment and generate a booking confirmation within 5 seconds.
- If payment fails, the user should receive an error message and retry option.

