# GarageFlow

**A workshop management system designed to centralize and organize automotive repair shop operations.**

GarageFlow is a full-stack application designed to manage the daily operations of an automotive repair shop, bringing customers, vehicles, services, parts, inventory, service orders, quotes, payments, and operational history into a single platform.

The project covers the complete software development process, from business rule definition and system architecture to REST API development and web application implementation.

---

## About the project

GarageFlow aims to replace fragmented workflows based on spreadsheets, messaging applications, and manual records with a centralized, structured, and traceable management system.

### Planned features

- User, group, and permission management
- Customer management
- Vehicle management
- Service catalog
- Parts catalog
- Inventory management and stock movements
- Service order management
- Quote creation and approval workflows
- Payments and financial adjustments
- Service interruption and regularization
- Operational history and auditability
- Vehicle delivery management

---

## Architecture

The application follows a decoupled architecture, with a React frontend communicating with a Django REST API and PostgreSQL database.

```text
┌─────────────────────┐
│                     │
│   React Frontend    │
│   TypeScript        │
│                     │
└──────────┬──────────┘
           │
           │ REST API
           ▼
┌─────────────────────┐
│                     │
│   Django Backend    │
│   Django REST       │
│   Framework         │
│                     │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│                     │
│     PostgreSQL      │
│                     │
└─────────────────────┘
```

---

## Repositories

### Backend

REST API responsible for business rules, authentication, authorization, data persistence, and application operations.

[GarageFlow Backend](https://github.com/GarageFlow-Gerenciamento-De-Oficinas/Backend)

### Frontend

Web application responsible for the user interface and interaction with the system.

[GarageFlow Frontend](FRONTEND_REPOSITORY_URL)

---

## Technology stack

### Backend

- Python
- Django
- Django REST Framework
- PostgreSQL
- Simple JWT
- drf-spectacular
- Docker

### Frontend

- React
- TypeScript
- Vite
- React Router
- Sass
- Vitest
- React Testing Library
- Mock Service Worker (MSW)

---

## Engineering challenges

GarageFlow places particular emphasis on business rules, data consistency, and system integrity.

Some of the main engineering challenges addressed by the project include:

- Group-based access control and permissions
- Immutable operational history and auditability
- Preservation of historical service and parts prices
- Inventory reservation and consumption workflows
- Concurrency control during stock reservations
- Quote approval and rejection workflows
- Complementary service orders
- Service interruption and regularization
- Financial control, including payments and adjustments
- Business rules ensuring consistency before vehicle delivery

These requirements influence the system architecture and guide the implementation of its backend and frontend components.

---

## Project status

**In active development**

GarageFlow is being developed incrementally. The backend currently provides the foundation for authentication, user management, and customer-related functionality, while the frontend is being integrated with the API.

Additional modules are planned as the project evolves.

---

## Documentation

Each repository contains its own documentation, including setup instructions, architecture details, technologies, and development guidelines.

- [Backend Documentation](BACKEND_README_URL)
- [Frontend Documentation](FRONTEND_README_URL)

---

## Author

**Jean França**

Software Developer

[LinkedIn](https://www.linkedin.com/in/jean-franca) · [GitHub](GITHUB_PROFILE_URL)
