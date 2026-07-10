# Aegis
Aegis is a production-inspired financial crime intelligence platform that combines event-driven architecture, graph analytics, and artificial intelligence to detect suspicious financial activities in real time. The platform is designed to help investigators identify money laundering patterns, analyze relationships between entities, and make informed decisions with AI-assisted insights.

---

## Features

* Real-time transaction ingestion using Apache Kafka
* Rule-based and AI-assisted suspicious activity detection
* Relationship analysis using Neo4j graph database
* Interactive investigation dashboard
* AI-powered explanations with Retrieval-Augmented Generation (RAG)
* Risk scoring and case management
* Secure authentication and role-based access control
* Dockerized deployment
* Kubernetes-ready architecture

---

## Architecture

Aegis follows a **modular monolith** architecture, keeping the codebase simple, maintainable, and production-ready while leveraging asynchronous event-driven communication through Kafka.

```text
                   +--------------------+
                   |  React Frontend    |
                   +---------+----------+
                             |
                             v
                  +----------------------+
                  | Spring Boot Backend  |
                  +----------+-----------+
                             |
         +-------------------+-------------------+
         |                   |                   |
         v                   v                   v
    PostgresSQL          Apache Kafka         Neo4j Graph
         |                   |                   |
         +-------------------+-------------------+
                             |
                             v
                      AI Investigation Engine
```

---

## Tech Stack

### Backend

* Java 21
* Spring Boot
* Spring Security
* Spring Data JPA
* Apache Kafka
* PostgreSQL
* Neo4j
* Maven

### Frontend

* React
* TypeScript
* Vite
* React Router
* Material UI
* TanStack Query
* Axios

### Infrastructure

* Docker
* Kubernetes
* GitHub Actions

---

## Objectives

* Detect suspicious financial transactions in real time.
* Build an explainable AI system for financial investigations.
* Explore graph-based fraud detection techniques.
* Develop scalable event-driven backend systems.
* Experiment with distributed systems concepts and streaming architectures.

---

## Current Status

Aegis is currently under active development.

Planned milestones include:

* [ ] Authentication & Authorization
* [ ] Transaction Management
* [ ] Kafka Event Pipeline
* [ ] Rule Engine
* [ ] Neo4j Graph Integration
* [ ] Risk Scoring Engine
* [ ] Investigation Dashboard
* [ ] AI Investigation Assistant
* [ ] Docker Deployment
* [ ] Kubernetes Deployment
* [ ] CI/CD Pipeline

---

## Contributing

Contributions, suggestions, and discussions are welcome. Feel free to open an issue or submit a pull request.

---

## License

This project is licensed under the Apache-2.0 License.

---