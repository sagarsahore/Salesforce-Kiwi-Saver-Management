# 🥝 Salesforce KiwiSaver Management

## Overview
The **Salesforce KiwiSaver Management** is a custom-built CRM solution designed for sales and advisory teams handling KiwiSaver clients. It provides a structured workflow to qualify leads, book appointments, track KiwiSaver data, and monitor sales performance with integrated analytics and AWS Connect calling features.

## Purpose
This project was built to simulate a real-world Salesforce implementation for a financial services use case. It is intended to:
- Improve lead qualification and conversion tracking
- Enable appointment bookings with advisers (Face-to-Face, Phone, or Virtual)
- Track KiwiSaver fund type, provider, and account value per client
- Equip managers with dashboards to monitor team KPIs
- Provide a practical Salesforce + CI/CD portfolio project for career growth

---

## 🎯 Project Goals
- Centralize client and appointment data for better visibility
- Automate lead-to-client flows via Screen Flows and Record Types
- Streamline call scheduling using AWS Connect
- Visualize KPIs like calls, appointments, and conversions via dashboards
- Implement a commission calculator for sales representatives

---

## 👥 Team Roles

### 💻 Sagar Sahore – Salesforce Developer & Architect
- Led data model design (Lead, Appointment, Client objects)
- Built Screen Flows for lead intake and appointment booking
- Integrated Amazon Connect for outbound/inbound calls
- Designed management dashboards and reporting metrics
- Implemented version control using GitHub and Salesforce CLI
- Configured CI/CD with scratch org strategy (in progress)
- Assisted with business logic definition and user flows
- Helped map the sales pipeline stages
- Provided feedback on UI/UX and KPI tracking for stakeholders

---

## 🔧 Tech Stack

- **Salesforce Platform**: Sales Console App, Standard & Custom Objects, Flows, Reports & Dashboards
- **AWS Connect**: Integrated for call scheduling and tracking
- **Apex**: For automation and custom logic
- **GitHub**: Source control for metadata
- **Salesforce CLI + VS Code**: Development environment
- **CI/CD**: Scratch org setup and deployment pipeline (in progress)

---

## 🚀 Features

- Lead qualification with custom fields:
  - Status, Source, Contact Preference
  - KiwiSaver Provider, Fund Type
  - Appointment Type (F2F, Phone, Virtual)
- Screen Flow to capture lead information and callback requests
- Advisor Calendar Booking System (custom object)
- Client Tracking:
  - KiwiSaver Balance, Fund Type, Assigned Adviser
- Management Dashboard:
  - Calls Made, Appointments Set, Conversion Rate
- Commission Calculator (custom formula-based logic)
- AWS Connect Integration for Calling
- Queue & List View configuration for lead management

---

## 📦 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/sf-kiwisaver-management.git
   cd sf-kiwisaver-management
