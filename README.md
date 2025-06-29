# Requirement Analysis in Software Development

This repository was created to document the process and significance of Requirement Analysis within the Software Development Life Cycle (SDLC).
It includes detailed explanations, illustrative examples, diagrams, and the essential steps for effectively gathering and analyzing software requirements for a booking system project.

## What is Requirement Analysis?

Requirement Analysis is the process of identifying, understanding, and documenting what a software system should do before any development begins. It involves gathering detailed information from stakeholders, such as clients, end-users, and project managers, to understand their needs and expectations for the software product.

This step ensures that everyone involved has a clear and shared understanding of the system’s goals, features, and limitations. By analyzing the requirements early, development teams can avoid costly mistakes, misunderstandings, and scope creep later in the project.

### Importance in the Software Development Lifecycle (SDLC)

Requirement Analysis is a crucial phase in the Software Development Life Cycle (SDLC). It lays the groundwork for all subsequent stages—design, development, testing, and deployment.

A thorough and effective requirement analysis helps to:

✅ Align the final software with user needs and expectations

✅ Clearly define the project scope and constraints

✅ Minimize development time and avoid unnecessary rework

✅ Enhance communication between stakeholders and the development team

✅ Enable accurate estimation of cost, resources, and timelines




## Why is Requirement Analysis Important?
Requirement Analysis plays a vital role in the success of any software project. Here are five key reasons why it matters:

1. **Defines Clear Project Scope**  
   Helps outline what the system should and should not do, preventing scope creep.

2. **Ensures User Needs Are Met**  
   Captures user expectations early, reducing the risk of building the wrong solution.

3. **Improves Communication**  
   Serves as a bridge between stakeholders, developers, and project managers for better collaboration.

4. **Reduces Cost and Rework**  
   Identifying issues early helps avoid expensive fixes later in the development process.

5. **Enables Accurate Planning**  
   Provides a solid foundation for estimating time, budget, and resources effectively.


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

#### Actor: Customer (Registered User or Guest User)
#### Goal: To search, view, and book a hotel room successfully.
#### Primary Flow:
- User visits the platform (web or mobile app).
- User enters location, dates, and guest details into the search bar.
- System queries Elasticsearch for available listings.
- System returns a list of available hotels with prices, ratings, and photos.
- User filters and sorts results (by price, rating, distance, etc.).
- User selects a hotel and views the hotel details page.
- User reviews room options, amenities, policies, and availability.
- User clicks “Book Now” on a selected room.
- System asks the user to log in or continue as guest.
- User enters personal details (if not logged in).
- User selects payment method and confirms booking.
- System processes payment via integrated payment gateway.
- System sends booking confirmation via email/SMS/notification.


![image](https://github.com/user-attachments/assets/2c943a6c-642b-4c5b-af8d-b6f952066443)
![image](https://github.com/user-attachments/assets/8f79d467-3750-44f2-93dd-5bee63b4cfd0)



## Acceptance Criteria

Acceptance Criteria are specific conditions that a software feature must meet in order to be accepted by the user or stakeholder. They define what success looks like for a feature and help ensure that everyone—developers, testers, and users—understand the expected result.

### Why Acceptance Criteria is Important:
- It sets a clear definition of "done" for each feature.
- It helps testers know exactly what to check during testing.
- It reduces misunderstandings between developers and stakeholders.
- It ensures that the delivered product matches the user’s expectations.

# ✅ Acceptance Criteria: Hotel Booking User Flow (Customer)

## Feature: Hotel Room Booking

As a customer,  
I want to search, view, and book a hotel room,  
So that I can find accommodation that fits my needs.

---

### 🎯 Scenario 1: Visit Platform
- [ ] The customer can access the booking platform via web or mobile.
- [ ] The homepage loads successfully with a visible search bar.

---

### 🔍 Scenario 2: Search Hotels
- [ ] Customer can input location, check-in/out dates, and number of guests.
- [ ] System returns a list of available hotels based on search input.
- [ ] System shows hotel names, prices, ratings, and images.

---

### 🧰 Scenario 3: Filter and Sort Results
- [ ] Customer can filter results by price range, rating, distance, and amenities.
- [ ] Customer can sort results by price (low to high), rating, or proximity.
- [ ] Results update dynamically based on selected filters/sorting.

---

### 📄 Scenario 4: View Hotel Details
- [ ] Customer can click on a hotel to view its full details.
- [ ] Hotel detail page shows room types, amenities, cancellation policy, and photos.
- [ ] Availability is displayed per selected dates.

---

### 🛏 Scenario 5: Book Room
- [ ] Customer clicks “Book Now” on a selected room.
- [ ] If not logged in, the system prompts login or guest checkout.
- [ ] Customer proceeds with booking after authentication.

---

### 👤 Scenario 6: Enter Personal Details
- [ ] Customer provides name, email, phone number, and any required fields.
- [ ] Form validation prevents submission of incomplete/invalid data.

---

### 💳 Scenario 7: Select Payment Method
- [ ] Customer can select from available payment options (card, wallet, etc.).
- [ ] System displays total price and breakdown of charges.

---

### ✅ Scenario 8: Confirm Booking
- [ ] Customer reviews the summary and clicks “Confirm Booking.”
- [ ] Payment is processed securely via payment gateway.
- [ ] Booking status updates to "Confirmed" if payment succeeds.

---

### 📩 Scenario 9: Receive Confirmation
- [ ] Customer receives confirmation via email, SMS, and/or in-app notification.
- [ ] Confirmation includes hotel name, address, dates, and booking reference.

---

##
