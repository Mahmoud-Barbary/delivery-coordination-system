![Hermes Express](https://github.com/user-attachments/assets/1cbd35a5-431b-4917-8964-602905dd082f)

# 📦 Delivery Coordination System (DCS)

A comprehensive delivery management web system designed for both individuals and businesses to seamlessly request, track, and manage deliveries. Built as part of an academic software engineering project, the DCS includes full architectural planning, UML modeling, user interface design, and system behavior documentation.

---

## 📌 Overview

The Delivery Coordination System is a robust online platform offering end-to-end shipment execution—from account creation to final delivery tracking. The system supports diverse delivery categories, multiple payment options, and integrates user-friendly interfaces for both desktop and mobile users.

### 🎯 Core Features

- **User Management**
  - Register/Login
  - Edit and delete account
  - View order history

- **Delivery Services**
  - Request delivery using categorized templates
  - Track delivery in real-time
  - Cancel delivery with rules depending on status

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

The component diagram outlines how these parts communicate through ports and APIs for modularity and scalability.

> 📄 See: `Deliverable II Report.pdf` – *Component Diagram & First Cut Class Design*

---

## 🗂️ Technical Documentation

All phases of design and development are covered through the following deliverables:

| Report | Content |
|--------|---------|
| 📘 **Deliverable I** | Use Case Diagrams, Domain Models, Sequence Diagrams, Activity Diagrams, UI Prototypes |
| 📘 **Deliverable II** | Component Diagram, First-Cut Class Diagram, CRC Cards, Communication Diagrams |
| 📘 **Deliverable III** | Final Class Design, Design Patterns (Singleton, MVC), Deployment Plan |

All three reports can be found in the [`/reports`](./reports) folder.

---

## 🖼️ UI/UX Design

Figma-based wireframes and storyboards illustrate the user flow across all interfaces:

### Desktop UI
- Homepage
- Delivery Request
- Customer Support

### Mobile UI
- Optimized for small screens
- Menu-driven navigation
- High contrast for readability

> 📁 View UI images in [`/ui-design`](./ui-design)

---

## 🧩 Diagrams & Models

- ✅ **Use Case Diagrams**
- ✅ **Domain Model**
- ✅ **Sequence Diagrams**
- ✅ **Activity Diagrams**
- ✅ **Component Architecture**
- ✅ **Communication Diagrams**
- ✅ **Final Class Diagram (Refined)**

Each diagram is organized by type under the [`/diagrams`](./diagrams) folder and corresponds to steps in the system's life cycle.

---

## ⚙️ Design Patterns Used

- **MVC (Model-View-Controller)** for separation of concerns
- **Singleton** for key controllers (e.g., DeliveryHandler)
- **Factory Method** for flexible instantiation of delivery categories and transport modes

---

## 🏁 Deployment Plan

The system is designed to be deployed as a web application with the following stack:
- **Frontend**: HTML/CSS/JS (future scope: React)
- **Backend**: Python or Java Spring Boot
- **Database**: MySQL or PostgreSQL
- **Payment Gateway**: External API integration (Stripe/PayPal)

---

## 👥 Authors

- **Mahmoud Ibrahim**  
- **Mennatallah Mohei Eldin**  
- **Gehad Mohamed**  
- **Mohamed Marwan**

---

## 📄 License

This project is intended for academic use only.

