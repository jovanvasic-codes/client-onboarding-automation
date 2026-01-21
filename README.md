# Client Onboarding Automation Suite (n8n)

An event-driven automation system designed to streamline the client onboarding process by integrating CRM, scheduling, and project management tools.

## 🚀 Overview
This project automates the entire journey from a booked meeting to a fully set up CRM deal and project task, ensuring zero manual data entry and real-time synchronization.

### Integrated Tools:
* **Calendly**: Trigger for new discovery calls.
* **HubSpot CRM**: Contact management, automated deal creation, and status updates.
* **ClickUp**: Automatic task generation for the fulfillment team.
* **n8n**: The core engine managing logic, webhooks, and sub-workflow orchestration.

## 🛠️ Key Features
* **Intelligent Upsert**: Automatically checks for existing contacts in HubSpot to prevent duplicates.
* **Deal Logic**: Differentiates between new and existing business to route deals correctly.
* **Event-Driven Sync**: Uses Webhooks and Sub-workflows to resume processes based on external CRM triggers.
* **Data Transformation**: Custom JavaScript expressions used for complex data mapping between APIs.

## 📸 Workflow Preview
![Workflow Preview](workflow-preview.png)

## 📂 How to Use
1. Download the `.json` files from this repository.
2. Import them into your n8n instance.
3. Configure your credentials for HubSpot, Calendly, and ClickUp.
