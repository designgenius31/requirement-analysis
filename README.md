# requirement-analysis
# Requirement Analysis in Software Development.

## Introduction
This repository explores the **Requirement Analysis** phase of Software Development, one of the most crucial steps in building successful software products.

It includes examples, documentation, and exercises related to:
- Gathering and analyzing user requirements  
- Modeling system requirements  
- Writing acceptance criteria  
- Understanding functional and non-functional requirements  

The goal of this repository is to serve as a learning resource and reference for anyone studying or practicing software requirement analysis.

## What is Requirement Analysis?

**Requirement Analysis** is a critical phase in the **Software Development Life Cycle (SDLC)** that focuses on understanding what a system should do and why it should do it. It involves gathering, analyzing, and documenting the needs and expectations of stakeholders to ensure the final product aligns with their goals.

### Purpose of Requirement Analysis
The main purpose of Requirement Analysis is to clearly define **functional** and **non-functional** requirements before development begins. This helps developers and designers understand the scope, features, and constraints of the system to be built.

### Importance in the SDLC
Requirement Analysis plays a vital role in ensuring project success by:
- **Defining clear objectives:** It provides a shared understanding of what needs to be built.  
- **Reducing ambiguity:** Ensures that stakeholders, developers, and testers are aligned.  
- **Improving design accuracy:** Well-defined requirements lead to more accurate system design and architecture.  
- **Saving time and cost:** Detecting requirement issues early helps avoid costly changes later in the development process.  
- **Supporting validation and testing:** Clear requirements serve as the foundation for test cases and acceptance criteria.

### Key Activities in Requirement Analysis
1. **Requirement Elicitation** – Gathering information from stakeholders through interviews, surveys, and workshops.  
2. **Requirement Modeling** – Representing requirements using diagrams or models.  
3. **Requirement Documentation** – Recording requirements in a clear, structured format.  
4. **Requirement Validation** – Ensuring requirements are correct, complete, and aligned with stakeholder needs.

In summary, Requirement Analysis bridges the gap between stakeholders’ expectations and the technical implementation, ensuring that the final software product is useful, usable, and successful.

## Why is Requirement Analysis Important?

Requirement Analysis is one of the most crucial stages in the **Software Development Life Cycle (SDLC)** because it sets the foundation for all subsequent development activities. When done effectively, it helps ensure that the final product meets user needs, aligns with business goals, and is delivered efficiently.

Here are three key reasons why Requirement Analysis is critical:

### 1. Ensures Clear Understanding and Alignment
By engaging with stakeholders early, Requirement Analysis ensures that **everyone involved — clients, developers, designers, and testers — shares a common understanding** of what the system should achieve. This minimizes miscommunication, confusion, and scope creep later in the project.

### 2. Reduces Development Costs and Rework
Identifying requirements errors or misunderstandings early in the SDLC is far less costly than discovering them after development or deployment. Proper Requirement Analysis helps **detect potential issues early**, saving time, effort, and resources in the long run.

### 3. Improves Quality and User Satisfaction
When requirements are well-defined and validated, the resulting software is **more aligned with user needs and expectations**. This leads to higher quality systems that are more usable, reliable, and satisfying for end users.

---

In summary, Requirement Analysis acts as the **blueprint** for software development — guiding teams toward building the right product, the right way, for the right users.

## Key Activities in Requirement Analysis

The Requirement Analysis phase involves several structured activities designed to understand, document, and validate what the system should do.  
Each activity contributes to ensuring that the software solution meets user needs and business objectives.

Here are the five key activities:

- **1. Requirement Gathering**  
  This is the process of **collecting information from stakeholders** about what they need and expect from the system.  
  It involves identifying user goals, business objectives, and system constraints. Common techniques include surveys, questionnaires, brainstorming sessions, and document reviews.

- **2. Requirement Elicitation**  
  Elicitation focuses on **actively engaging stakeholders** to extract detailed and accurate requirements.  
  Techniques such as interviews, focus groups, observations, and workshops are used to uncover both **explicit needs** (what users say) and **implicit needs** (what users might not express directly).
## Types of Requirements

### Functional Requirements  
Functional requirements describe **what the system must do** — the specific behaviours or functions of the booking management system.

For example, based on a hotel/property booking system:  
- A user must be able to **search** properties (by location, date, price, amenities). :contentReference[oaicite:0]{index=0}  
- A user must be able to view detailed **property listings** (photos, description, rating, availability). :contentReference[oaicite:1]{index=1}  
- A user must be able to **make a booking/reservation** for a selected property (check‐in, check‐out, number of guests). :contentReference[oaicite:2]{index=2}  
- The system must allow a property owner or manager to **register a property** and manage availability. :contentReference[oaicite:3]{index=3}  
- The system must send **confirmation notifications** once a booking is completed. :contentReference[oaicite:4]{index=4}  

### Non-functional Requirements  
Non-functional requirements describe **how the system performs** — constraints on the system (quality attributes such as performance, security, scalability).

Examples for the booking system:  
- The system must provide **low latency** in search results (e.g., respond quickly when a user searches for available properties). :contentReference[oaicite:5]{index=5}  
- The system must be **highly scalable** to handle many users and many bookings concurrently. :contentReference[oaicite:6]{index=6}  
- The system must ensure **data consistency and prevent double-booking** of the same room/property for overlapping dates. :contentReference[oaicite:7]{index=7}  
- The system must provide **secure authentication and protect user data** (login, payment, personal information). :contentReference[oaicite:8]{index=8}  
- The system must be **highly available and reliable**, even under peak load. :contentReference[oaicite:9]{index=9}  

- **3. Requirement Documentation**  
  After gathering and eliciting requirements, they must be **organized and documented** in a clear, structured format.  
  Documentation ensures that all requirements are traceable, measurable, and understandable by both technical and non-technical team members.  
  Examples include Software Requirement Specification (SRS) documents, user stories, and use case diagrams.

- **4. Requirement Analysis and Modeling**  
  This step involves **analyzing the gathered requirements** to identify dependencies, conflicts, or inconsistencies.  
  Models such as **use case diagrams**, **data flow diagrams (DFDs)**, or **entity-relationship diagrams (ERDs)** are created to visualize system behavior and data interactions.  
  The goal is to translate user needs into precise, implementable specifications.

- **5. Requirement Validation**  
  The final step ensures that the documented requirements are **accurate, complete, consistent, and aligned** with stakeholder goals.  
  Validation may include reviews, walkthroughs, and prototyping sessions to confirm that the requirements reflect real user needs and business priorities.

---

Together, these activities ensure that the development team builds a product that is **well-understood, feasible, and valuable** to its intended users.
## Use Case Diagrams

### What are Use Case Diagrams?
**Use Case Diagrams** are visual representations that show the **interactions between users (actors)** and the **system’s functionalities (use cases)**.  
They help stakeholders understand what the system does from a user’s perspective, without going into technical details.

### Benefits of Use Case Diagrams
- Provide a **clear overview** of system behavior and user interactions.  
- Help identify **key functional requirements** early in the SDLC.  
- Promote **better communication** between stakeholders and developers.  
- Serve as a **foundation for test cases** and system design.

### Example: Booking Management System

The following Use Case Diagram represents a simplified version of the **booking management system**, showing interactions between Guests, Hosts, Admins, and the System.

![Use Case Diagram for Booking System](./alx-booking-uc.png)
## Acceptance Criteria

### What is Acceptance Criteria?
**Acceptance Criteria** are the specific, measurable conditions that a software feature must meet to be **accepted by stakeholders or product owners**.  
They define **what success looks like** for a feature and ensure that everyone has a shared understanding of the expected behavior and outcomes.

Acceptance Criteria are typically written in simple, clear language so that both technical and non-technical stakeholders can understand them.

---

### Importance of Acceptance Criteria in Requirement Analysis
- ✅ **Clarifies expectations:** Ensures developers, testers, and stakeholders agree on what “done” means for a feature.  
- 🧩 **Guides development and testing:** Provides a checklist that developers and QA teams can use to verify functionality.  
- 💬 **Reduces misunderstandings:** Helps avoid scope creep and vague requirements by defining clear boundaries.  
- 🧠 **Supports user-centric design:** Keeps development focused on delivering value that meets user needs.

---

### Example: Acceptance Criteria for the “Checkout” Feature in the Booking Management System

**Feature:** Checkout process for a booking system (completing a reservation and making payment).

**User Story:**  
> As a Guest, I want to securely complete my booking and make payment so that I can confirm my reservation.

**Acceptance Criteria:**
1. The user must be able to view a **summary of their booking details** (property name, dates, guests, and total price) before confirming.  
2. The system must support **multiple payment methods** (credit/debit card, PayPal, etc.).  
3. Payment processing must occur over a **secure, encrypted connection (HTTPS)**.  
4. On successful payment, the system must:  
   - Generate a **unique booking ID**.  
   - Send a **confirmation email or notification** to the user within 5 minutes.  
5. If payment fails, the system must display an **error message** and allow the user to **retry or cancel** the transaction.  
6. The booking details and payment status must be stored accurately in the **database** for future reference.  

---

In summary, **Acceptance Criteria** act as the **final validation step** in the Requirement Analysis process — turning high-level requirements into testable, measurable conditions that ensure the delivered product meets stakeholder expectations.
