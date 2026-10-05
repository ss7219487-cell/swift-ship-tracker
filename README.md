# Swift Ship Tracker

Salesforce-based Shipment Tracking and Delivery Management System for managing parcels, senders, receivers, deliveries, tracking, automation, and AI-based assistance.

# Swift Ship Tracker

An end-to-end Shipment Tracking and Delivery Management Platform designed to simplify parcel booking, tracking, delivery management, and status updates. Built using Salesforce, **Swift Ship Tracker** provides a centralized solution for customers, delivery agents, and administrators.

---

## 🚀 Features

- **Parcel Management:** Create and manage parcel-related information.
- **Sender Management:** Store and manage sender details.
- **Receiver Management:** Store and manage receiver details.
- **Delivery Management:** Manage delivery-related information and processes.
- **Parcel Tracking:** Track parcel and delivery information.
- **Delivery Status Updates:** Update and manage parcel delivery status.
- **Process Automation:** Automate parcel and delivery-related processes using Salesforce Flows.
- **AI-Based Assistance:** Provide conversational assistance using AgentForce AI.
- **Prompt-Based Functionality:** Use Prompt Builder for AI-related functionality.
- **User Access Management:** Manage user permissions using Salesforce Permission Sets.
- **Verification & Testing:** Verify AgentForce functionality, topics, flows, and Salesforce data.

---

## 👥 User Roles

### Customer
- Book parcels
- Provide sender and receiver information
- Track parcels
- View delivery information
- Get assistance through the AI agent

### Delivery Agent
- View delivery information
- Manage delivery details
- Update delivery status
- Access required parcel information

### Admin
- Manage parcel information
- Manage sender and receiver information
- Manage delivery information
- Monitor the overall system
- Manage user access and permissions

---

## 🛠️ Salesforce Technologies & Features

- **Salesforce**
- **Custom Objects**
- **Custom Tabs**
- **Fields & Relationships**
- **Salesforce Flows**
- **Prompt Builder**
- **AgentForce AI**
- **Permission Sets**

---

## 📦 Main Custom Objects

The system uses four main custom objects:

- **Parcel** – Stores parcel-related information.
- **Sender** – Stores sender information.
- **Receiver** – Stores receiver information.
- **Delivery** – Stores delivery-related information.

### Data Model

```text
                    Swift Ship Tracker
                           |
                         Parcel
                       /   |    \
                      /    |     \
                 Sender  Receiver  Delivery
