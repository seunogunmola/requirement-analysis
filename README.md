# Requirement Analysis in Software Development

This repository is created to document the process and importance of Requirement Analysis in the Software Development Life Cycle (SDLC).  
It contains explanations, examples, diagrams, and key steps involved in gathering and analyzing software requirements for a booking system project.

## What is Requirement Analysis?

Requirement Analysis is the process of identifying, understanding, and documenting what a software system should do before any development begins. It involves gathering detailed information from stakeholders, such as clients, end-users, and project managers, to understand their needs and expectations for the software product.

This step ensures that everyone involved has a clear and shared understanding of the system’s goals, features, and limitations. By analyzing the requirements early, development teams can avoid costly mistakes, misunderstandings, and scope creep later in the project.

### Importance in the Software Development Lifecycle (SDLC)

Requirement Analysis is one of the most critical stages in the SDLC. It serves as the foundation for all other phases such as design, development, testing, and deployment. A well-done requirement analysis helps:

- Ensure that the final software meets the user’s needs.
- Define clear project scope and boundaries.
- Reduce development time and rework.
- Improve communication between stakeholders and developers.
- Make accurate cost and timeline estimations.

Without proper requirement analysis, the project is at risk of failure due to unclear goals, missed functionalities, or unexpected issues.

## Why is Requirement Analysis Important?

Requirement Analysis plays a vital role in the Software Development Life Cycle (SDLC). It helps teams build the right product by clearly defining what the software should do and how it should perform.

Here are three key reasons why it is important:

### 1. Prevents Miscommunication and Confusion
Requirement Analysis ensures that both developers and stakeholders are on the same page. It reduces the chances of misunderstandings by clearly documenting what is expected from the software.

### 2. Helps Define the Project Scope
By gathering and analyzing requirements, teams can set clear boundaries for what will be included in the project. This helps prevent scope creep, which is when extra features are added unexpectedly and cause delays or extra costs.

### 3. Enables Accurate Planning
With well-defined requirements, project managers can better estimate timelines, costs, and resources needed for the project. It lays the groundwork for creating realistic project plans and schedules.

### 4: Improves Product Quality
When requirements are clear and validated, the final product is more likely to meet the user’s needs and expectations, leading to higher customer satisfaction.

## Key Activities in Requirement Analysis

Requirement Analysis involves several important steps that help ensure the software meets user needs. Here are the five key activities involved:

- **Requirement Gathering:**  
  This is the process of collecting information from stakeholders (e.g., clients, users, managers) about what they want the software to do. Techniques include interviews, surveys, and observations.

- **Requirement Elicitation:**  
  This step goes deeper into understanding what stakeholders really need. It often involves discussions, brainstorming, and even creating prototypes to clarify expectations.

- **Requirement Documentation:**  
  After gathering and understanding the requirements, everything is written down clearly in documents like Software Requirement Specifications (SRS), user stories, or use case descriptions.

- **Requirement Analysis and Modeling:**  
  This involves reviewing the documented requirements to check for completeness, consistency, and feasibility. It may also include creating visual models like flowcharts, diagrams, or data models to better understand the system.

- **Requirement Validation:**  
  Finally, the requirements are reviewed with stakeholders to make sure everything is correct, clear, and agreed upon before development begins. This helps avoid mistakes and costly changes later.

## Types of Requirements

In software development, requirements are usually divided into two categories: Functional and Non-functional requirements. Both are essential to building a complete and successful system.

### Functional Requirements

Functional requirements describe **what the system should do**. They are the specific features or functions users can perform.

**Examples for a Booking Management System:**
- Users should be able to register and log into their accounts.
- Users should be able to search for available properties by location, price, and date.
- The system should allow users to book a property and receive a booking confirmation.
- Property owners should be able to upload and manage their listings.
- Admins should be able to view and manage all bookings.

### Non-functional Requirements

Non-functional requirements describe **how the system should perform**. These are the qualities or constraints of the system like speed, security, or user experience.

**Examples for a Booking Management System:**
- The system should load any page in under 2 seconds (Performance).
- User data should be protected using encryption (Security).
- The system should support up to 1000 users at the same time without crashing (Scalability).
- The platform should be easy to navigate for both desktop and mobile users (Usability).
- The system should be available 99.9% of the time throughout the year (Reliability).

## Use Case Diagrams

A Use Case Diagram is a visual tool used in Requirement Analysis to show how users (called *actors*) interact with the system. It helps identify the different ways the software will be used and ensures all functionalities are captured.

### Benefits of Use Case Diagrams:
- They give a clear, visual overview of system functionalities.
- They help developers understand user roles and interactions.
- They improve communication between technical and non-technical stakeholders.

### Example: Booking Management System Use Case Diagram

The diagram below shows key actors (users) and their interactions with the booking system:

![Use Case Diagram](./alx-booking-uc.png)

## Acceptance Criteria

Acceptance Criteria are specific conditions that a software feature must meet in order to be accepted by the user or stakeholder. They define what success looks like for a feature and help ensure that everyone—developers, testers, and users—understand the expected result.

### Why Acceptance Criteria is Important:
- It sets a clear definition of "done" for each feature.
- It helps testers know exactly what to check during testing.
- It reduces misunderstandings between developers and stakeholders.
- It ensures that the delivered product matches the user’s expectations.

### Example: Checkout Feature in a Booking Management System

**Feature:** Booking Checkout

**Acceptance Criteria:**
- The user must be able to select available dates for a property.
- The system should calculate the total cost based on selected dates.
- The user must be able to enter payment details and confirm the booking.
- After confirmation, the system should display a success message and send a confirmation email within 2 minutes.
- Booked dates should be marked as unavailable immediately.

