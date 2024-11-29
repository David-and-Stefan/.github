# [PRESENTATION](https://github.com/user-attachments/assets/beb41224-92c6-48d8-a0cd-a23cc6178eaf)
# [DOCUMENTATION](https://docs.google.com/document/d/191n_tcpc6TPIFMr7cmXoymfvvwnRpZwr/edit?usp=sharing&ouid=102960516675733777589&rtpof=true&sd=true)



![SkillNet_600](https://github.com/user-attachments/assets/beb41224-92c6-48d8-a0cd-a23cc6178eaf)

## SkillNet Overview
SkillNet is a management system designed for private lessons, trainings, or other organizational activities. The platform enables organizers to manage their own organizations by subscribing to paid plans. Users can be employed within these organizations, and members can join various groups. The system also supports the management of complex organizational schedules, providing a comprehensive solution for handling memberships, employment, and scheduling.

### Technologies and Architectural Principles

- **Frontend**: Built with **Vite React**, **TypeScript**, and styled using **Tailwind CSS**.
- **Backend**: Implements **Domain-Driven Design (DDD)** and **Command Query Responsibility Segregation (CQRS)** for a scalable, maintainable monolithic architecture.
- **Database**: Uses **SQL Server** for relational data storage.
- **Storage**: **Azure Blob Storage** for file management.
- **Identity Management**: Secured with **Auth0** for authentication and authorization.
- **Payment Processing**: **Stripe** integration for subscription management.
- **Notifications**: Delivered in real-time via **Azure Functions**, **SignalR**, and **CosmosDB**.
- **Event-Driven Architecture**: Utilizes **Azure Service Bus** for publish/subscribe messaging.

## Cloud Solution

SkillNet leverages **Microsoft Azure** for a fully cloud-hosted, scalable, and reliable solution:

- **Landing Page and SPA**: Hosted on **Azure Static Web Apps** for fast and secure delivery.
- **Monolith API**: Deployed on **Azure App Service**, ensuring high availability and scalability.
- **Notifications**: Powered by **Azure CosmosDB for MongoDB**, **Azure SignalR**, and **Azure Functions** for real-time updates and event processing.
- **Main Database**: Uses **Azure SQL** for relational data management.
- **Storage**: **Azure Blob Storage** is utilized for storing and managing images and files.
- **Service Bus**: Implements **Azure Service Bus** for event-driven communication using the publish/subscribe model.

### Architecture Diagram

![SkillNet-Diagram](https://github.com/user-attachments/assets/5e5a7d94-1d8b-4efe-929f-7c0702b07277)
