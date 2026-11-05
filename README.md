# n8n-ai-automation-portfolio
AI Automation Portfolio | n8n

A collection of AI-powered automation projects built with n8n, OpenAI, and external APIs to solve practical business problems through intelligent workflows.

This repository showcases three automation projects focused on customer support, appointment scheduling, and availability management.

---

📌 Projects Overview

1. AI-Powered Product Support Assistant

An AI-powered customer support assistant that retrieves product information from a structured data table and responds to customer inquiries about product prices and stock availability.

Key Features

- Automated customer message processing.
- Product information retrieval using n8n Data Tables.
- AI-generated responses based on available product data.
- Automated customer communication through Bale Messenger.

Technologies

- n8n
- OpenAI API
- AI Agent
- Data Tables
- Bale Bot API

Workflow:

"Customer Message → Data Retrieval → AI Agent → Response Generation → Bale Messenger"

---

2. AI-Powered Meeting Booking Agent with Cal.com

An AI-powered appointment booking assistant integrated with Cal.com API. It helps customers check available time slots and book meetings through conversational interactions.

Key Features

- Automated appointment scheduling.
- Availability checking through Cal.com API.
- Booking creation through API integration.
- Checking previously recorded reservations using n8n Data Tables.
- Handling unavailable or conflicting booking requests.

Technologies

- n8n
- OpenAI API
- AI Agent
- Cal.com API
- Data Tables
- Bale Bot API

Workflow:

"Customer Message → AI Agent → Availability Check → Booking Validation → Cal.com Booking → Confirmation"

---

3. AI-Based Availability Management & Booking System

An AI-powered scheduling assistant that manages appointment availability through structured data tables.

The system retrieves available time slots, presents them to customers, and updates reservation statuses after a customer selects a time.

Key Features

- Retrieving available time slots from a data table.
- Filtering reserved and available time slots.
- Presenting available appointments to customers.
- Updating reservation status after selection.
- Tracking reserved time slots to prevent repeated bookings.

Technologies

- n8n
- OpenAI API
- AI Agent
- Data Tables
- Bale Bot API

Workflow:

"Customer Message → AI Agent → Available Slots Retrieval → Customer Selection → Reservation Update → Confirmation"

---

🛠️ Technologies & Tools

Technology| Purpose
n8n| Workflow automation and orchestration
OpenAI API| Language model integration
AI Agents| Conversational processing and tool usage
HTTP Request| External API integration
JavaScript| Data processing and transformation
n8n Data Tables| Structured data storage and management
Cal.com API| Appointment availability and booking
Bale Bot API| Customer communication

---

📂 Repository Structure

n8n-ai-automation-portfolio/
│
├── 01-ai-product-assistant/
│   ├── workflow.json
│   ├── README.md
│   └── screenshots/
│
├── 02-ai-meeting-booking-calcom/
│   ├── workflow.json
│   ├── README.md
│   └── screenshots/
│
├── 03-ai-availability-booking/
│   ├── workflow.json
│   ├── README.md
│   └── screenshots/
│
└── README.md

---

🚀 Getting Started

To explore and run these workflows:

1. Clone or download this repository.
2. Open your n8n instance.
3. Import the desired "workflow.json" file.
4. Configure the required API credentials.
5. Set up the necessary Data Tables.
6. Configure the external services and API connections.
7. Test the workflow using your messaging bot.

Requirements

- An active n8n instance.
- OpenAI API credentials.
- Bale Bot API credentials.
- Cal.com API credentials (for Project 2).
- Properly configured n8n Data Tables.

---

🔐 Security Notice

API keys, access tokens, personal information, and private credentials are not included in this repository.

Configure your own credentials inside n8n before executing the workflows.

---

🎯 Purpose

These projects demonstrate practical applications of AI-powered workflow automation, AI Agent integration,

API connectivity, and structured data management.

The goal is to explore how AI automation can improve customer interactions and simplify business operations.

---

👩‍💻 Author

Maedeh Ferdowsinia

AI Automation | AI Agents | n8n | AI Engineering

"GitHub Profile" (YOUR_GITHUB_PROFILE_URL)

---

Built with n8n and AI-powered automation.
