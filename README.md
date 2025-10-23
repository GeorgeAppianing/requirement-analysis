# 🧠 Requirement Analysis in Software Development

## 📘 Introduction
This repository explores **Requirement Analysis**, a key phase in the Software Development Life Cycle (SDLC). It focuses on understanding user needs, documenting them effectively, and ensuring the final software meets business goals and user expectations.

---

## 💡 What is Requirement Analysis?
Requirement Analysis is the process of **gathering, analyzing, and defining** what a software system should do. It involves close collaboration with stakeholders to understand both **functional** and **non-functional requirements**, ensuring the final product aligns with business objectives.

---

## 🚀 Why is Requirement Analysis Important?
Requirement Analysis helps to:
- Clearly define project goals and scope  
- Prevent **scope creep** and unnecessary feature expansion  
- Ensure all stakeholders share a common understanding  
- Improve **project planning**, estimation, and execution  
- Enhance **user satisfaction** by meeting expectations accurately  

Without proper requirement analysis, projects often face **delays, rework, and cost overruns** due to unclear or misunderstood requirements.

---

## 🔑 Key Activities in Requirement Analysis
1. **Requirement Gathering** – Collecting user needs through interviews, surveys, and observation.  
2. **Requirement Elicitation** – Refining and clarifying requirements using techniques like brainstorming and prototyping.  
3. **Requirement Documentation** – Creating detailed documents like Software Requirement Specifications (SRS) and Use Cases.  
4. **Requirement Validation** – Reviewing and confirming that requirements are correct, complete, and feasible.  
5. **Requirement Management** – Tracking changes and maintaining requirement consistency throughout the project.

---

## 🧩 Types of Requirements
### **1. Functional Requirements**
These describe **what the system should do**, including its features and operations.  
Examples:
- User registration and login  
- Property or room booking  
- Payment processing  
- Report generation  

### **2. Non-Functional Requirements**
These define **how the system should perform**, focusing on quality attributes.  
Examples:
- Performance (page load time under 2 seconds)  
- Security (two-factor authentication, data encryption)  
- Scalability (handling 10,000+ users concurrently)  
- Usability (responsive and accessible UI)

---

## 🎨 Use Case Diagram
Below is the Use Case Diagram for the ALX Booking System:

![ALX Booking System Use Case Diagram](./diagrams/alx-booking-uc.png)

---

## ✅ Importance of Acceptance Criteria in Requirement Analysis

**Acceptance Criteria** are the **conditions that a feature must satisfy** for stakeholders or product owners to accept it as complete.  
They act as a **bridge between requirements and testing**, ensuring that development and QA teams understand what “done” means for each feature.

### **Why Acceptance Criteria Matter**
- Define **clear expectations** for each feature  
- Prevent **misunderstandings** between stakeholders and developers  
- Support **test case creation** for verification and validation  
- Enable **consistent evaluation** of deliverables  
- Improve **quality assurance** and reduce rework  

---

## 🧾 Example: Acceptance Criteria for the “Checkout” Feature in the Booking System

**Feature:** Checkout Process in Booking Management System  

**Acceptance Criteria:**
1. The system must display a **summary of selected bookings** (property name, date, cost).  
2. The user must be able to **select a payment method** (credit card, PayPal, or mobile money).  
3. The system must **validate payment information** before proceeding.  
4. On successful payment, the user should **receive an email confirmation** with booking details.  
5. If payment fails, the system should **display an error message** and allow retry.  
6. The transaction must be securely handled using **HTTPS** and **encrypted data transfer**.  

✅ **Outcome:** The Checkout feature is considered complete when all above conditions are met successfully.
