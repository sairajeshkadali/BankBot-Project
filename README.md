# BankBot: AI Chatbot for Banking FAQs

This repository contains the source code for "BankBot," an intelligent, full-stack conversational AI project built as part of the **Infosys Springboard Virtual Internship**.

The application is designed to simulate a real-world banking assistant. It can understand and respond 24/7 to common user queries like balance checks, loan inquiries, and card blocking, with the goal of reducing operational costs and improving customer engagement.

## Key Features

* **Natural Language Understanding (NLU):** The core "brain" is built with **Rasa** to understand user intents (e.g., `check_balance`, `transfer_money`) and extract key entities (e.g., `amount`, `account_type`).
* **Full-Stack Architecture (3-Tier):**
    * **Frontend:** A clean, responsive chat interface built with **React (Vite)**.
    * **Backend:** A robust API gateway built with **Flask (Python)** to manage requests.
    * **AI Core:** The Rasa NLU and Dialogue Management (Core) servers.
* **Dialogue Management:** Uses a combination of rules and stories to manage multi-turn conversations and handle context.
* **Admin Panel (In-Progress):** A secure, JWT-protected admin dashboard for Conversation-Driven Development (CDD). This allows an administrator to view conversation logs, edit NLU training data, and trigger model retraining directly from the UI, as specified in the project milestones.

## Technology Stack

* **Conversational AI:** Rasa Open Source
* **Backend API:** Flask (Python)
* **Frontend UI:** React.js (Vite)
* **Core Language:** Python 3.9
* **Package Management:** `pip` (Python), `npm` (Node.js)

## Project Milestones

This project is being built according to the 8-week internship plan:
* **Milestone 1: NLU Engine:** Define intents and entities, and train a validated NLU model. (Completed)
* **Milestone 2: Dialogue Management:** Build conversation flows with rules, stories, and custom actions.
* **Milestone 3: UI Integration:** Connect the React frontend to the Flask & Rasa backend.
* **Milestone 4: Admin Panel:** Build the secure admin dashboard for maintenance and improvement.
