## Tastify — Restaurant Management Automation System

**Tastify** is an end-to-end software system designed to automate day-to-day restaurant operations and improve the guest experience. The platform consists of a **backend REST API**, a **web application for administrators and staff**, and an **Android mobile application for guests**.

### What the system does

Tastify helps restaurants manage core workflows in one place:

* **Menu & products:** create and maintain a digital menu with items, categories, and product data.
* **Reservations & tables:** handle bookings, assign tables, and keep track of restaurant availability.
* **Orders:** support order management and operational flow for staff.
* **Inventory:** manage ingredients/products and track stock-related data.
* **Staff management:** maintain staff accounts and organize **work shifts**.

### Mobile app for guests (Android)

Guests can use the mobile app to:

* **Register / log in** and manage their profile.
* **Browse the restaurant menu** conveniently from the phone.
* **Create, update, and cancel reservations**.
* Use a **loyalty/bonus** feature (coupons/bonuses) to encourage repeat visits.

### Web app for admins & staff

The web application is focused on internal restaurant workflows:

* Admin/staff authorization and role-based actions
* Managing menu, reservations, tables, orders, inventory, and shifts
* A clear UI for day-to-day operational tasks

## Architecture, Tech Stack & Repository Structure

### Tech Stack
- **Backend:** ASP.NET Core (C#) REST API
- **Database:** MongoDB
- **Web:** HTML / CSS / JavaScript
- **Mobile:** Android (Kotlin)

### Repository structure
This repository is organized into task folders (university deliverables):
- **Task1 — Vision & Scope:** project idea, goals, requirements, and overall system scope.
- **Task2 — Backend (Server):** API implementation (core business logic, endpoints) using ASP.NET Core + MongoDB.
- **Task4 — Web App:** web client for administrators and staff workflows.
- **Task5 — Mobile App:** Android app for guests (menu browsing, reservations, profile, bonuses).

Tastify is built as a multi-component system where the backend API acts as the single source of truth and is consumed by both the web and mobile clients.
