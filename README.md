![Hermes Express](https://github.com/user-attachments/assets/4ad70d60-f0a5-4335-96fc-4b977d3acb58)

# 📦 Delivery Coordination System (DCS)

A comprehensive delivery management web system designed for both individuals and businesses to seamlessly request, track, and manage deliveries. Built as part of an academic software engineering project, the DCS includes full architectural planning, UML modeling, user interface design, and system behavior documentation.

---
## 📌 Overview

**Hermes Express** is a robust online platform offering end-to-end shipment execution, from account creation to final delivery tracking. The system supports diverse delivery categories, multiple payment options, and integrates user-friendly interfaces for both desktop and mobile users.

### 🎯 Core Features

- **User Management**
  - Register/Login
  - Edit and delete account
  - View order history

- **Delivery Services**
  - Request delivery using categorized templates
  - Track delivery in real-time
  - Cancel delivery based on order status

- **Customer Support**
  - Submit complaints or feedback via form
  - Generate complaint IDs for follow-up

---

## 🧠 System Architecture

The system is composed of interconnected components managed via clear interfaces:

- **Customer Interface**
- **Account Management**
- **Delivery System**
- **Customer Support**
- **Subsystems:** Payments, Tracking, Logistics, Database

The component diagram illustrates how these modules interact through ports and APIs, emphasizing modularity, reusability, and scalability.

> 📄 See: `Phase 2 Report.pdf` – *Component Diagram & First-Cut Class Design*

---

## 🗂️ Technical Documentation

All phases of design and development are documented in the following reports:

| Report | Content |
|--------|---------|
| 📘 **Phase 1 Report** | Use Case Diagrams, Domain Models, Sequence Diagrams, Activity Diagrams, UI Prototypes |
| 📘 **Phase 2 Report** | Component Diagram, First-Cut Class Diagram, CRC Cards, Communication Diagrams |
| 📘 **Phase 3 Report** | Final Class Design, Design Patterns (Singleton, MVC), Deployment Plan |

All three reports are available in the [`/reports`](./reports) directory.

---

## 🖼️ UI/UX Design

Figma-based wireframes and storyboards illustrate the user experience on both desktop and mobile platforms:

### Desktop UI
- Homepage
- Delivery Request
- Customer Support

### Mobile UI
- Optimized for compact screens
- Menu-driven navigation
- High contrast for readability

> 📁 View UI mockups in [`/ui-design`](./ui-design)

---

## 🧩 Diagrams & Models

- ✅ Use Case Diagrams
- ✅ Domain Model
- ✅ Sequence Diagrams
- ✅ Activity Diagrams
- ✅ Component Architecture
- ✅ Communication Diagrams
- ✅ Final Class Diagram (Refined)

Each diagram is organized by type and iterations of each are present within each report phase.

---

## 🧩 Design Patterns Used

As part of **Phase 3**, our team implemented a suite of software design patterns in Java to align with the structural and behavioral needs of the Hermes Express system. These patterns are implemented in a separate companion repository:

🔗 [Delivery-System-Design-Patterns](https://github.com/Mahmoud-Barbary/Delivery-System-Design-Patterns)

Each pattern corresponds to a real subsystem or feature in Hermes Express and includes modular packages, supporting classes, and driver code for demonstration.

### 🧱 Patterns Implemented

| Pattern              | Application in Hermes Express                                                                 |
|----------------------|-----------------------------------------------------------------------------------------------|
| **Singleton**         | `Depot` class - ensures global control over depot instance creation                          |
| **Flyweight**         | `DeliverySettings` - reduces memory overhead by reusing common configurations                |
| **Adapter**           | `DeliverySystemAdapter` - bridges legacy and modern delivery system interfaces               |
| **Observer**          | `NotificationService` - dispatches delivery status updates to email/app subscribers          |
| **Strategy**          | `Payment` - encapsulates different payment types (e.g., card, PayPal) using behavior switching|
| **Iterator**          | `OrderHistory` - enables ascending/descending history viewing via controlled traversal        |
| **Abstract Factory**  | `DeliveryRequestFactory` - generates request objects based on standard or express categories |
| **Bridge**            | `VehicleType` - decouples customer permissions from vehicle types                            |
| **Mediator**          | Coordinates component interaction such as cancellation, logistics, and user flow handlers     |

All implementations are organized under the `/src/` folder of the linked repo with one folder per pattern:

```bash
/src/
├── AbstractFactory/
├── Adapter/
├── Bridge/
├── Flyweight/
├── IteratorPattern/
├── Mediator/
├── Observer/
├── Singleton/
└── Strategy/
```

---

## 🔧 Auto-Generated Code

To validate the domain model and design architecture, a portion of the system was auto-generated into Java using modeling tools. This includes:

- Entity classes like `Customer`, `Delivery`, `Business`, `Depot`
- Handler/controller classes like `AccountHandler`, `ManagementHandler`, and `DeliveryHandler`

While the codebase is not manually implemented or wired to a working backend, it reflects a **faithful translation of the class diagrams** into Java structure. It serves to:
- Demonstrate how the conceptual design maps to code
- Prove consistency between diagrams and actual implementation logic
- Offer a scaffold for future backend expansion or integration

> 📁 See: [`/domain-model-code`](./domain-model-code)

---

## 🏁 Deployment Plan

Hermes Express is architected as a full-stack web application with deployment-ready components:

- **Frontend**: HTML, CSS, JS (React recommended for future development)
- **Backend**: Java Spring Boot or Python Flask/Django
- **Database**: MySQL or PostgreSQL
- **Third-Party Services**: Payment APIs (Stripe, PayPal), optional email or SMS integration

---

## 👥 Authors

- **Mahmoud Ibrahim**  
- **Mennatallah Mohei Eldin**  
- **Gehad Mohamed**  
- **Mohamed Marwan**

---

## 📄 License

This project is intended for academic and demonstrative purposes.
