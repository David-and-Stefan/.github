
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

### Architecture Diagram

![SkillNet-Diagram](https://github.com/user-attachments/assets/5e5a7d94-1d8b-4efe-929f-7c0702b07277)
