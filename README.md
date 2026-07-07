# System Design Playground

> Learning by building, breaking, measuring, and improving real-world distributed systems.

This repository is my hands-on journey into **System Design**, **System Architecture**, **Distributed Systems**, and **Backend Engineering**.

Unlike traditional interview repositories that focus only on diagrams or theory, this project is built around **working implementations** using small, isolated examples inspired by real production challenges I've encountered while building platforms such as **RentFlow** and other full-stack systems.

The goal is simple:

> Learn every concept by implementing it first, then understanding the engineering trade-offs behind it.

---

## Philosophy

I strongly believe in **learning by doing**.

Most concepts here were problems I solved before I knew their official names.

This repository documents those concepts using practical examples, architecture diagrams, and production-inspired implementations.

---

# Repository Roadmap

## Foundations

* Monolith vs Microservices
* Layered Architecture
* Dependency Injection
* Repository Pattern
* SOLID Principles
* Clean Architecture

---

## Communication

* REST APIs
* WebSockets
* Server-Sent Events
* gRPC
* Event-Driven Communication
* Pub/Sub

---

## Background Processing

* Workers
* Queues
* Retry Strategies
* Dead Letter Queues
* Scheduled Jobs

---

## Databases

* PostgreSQL
* PostGIS
* Redis
* Database Indexing
* Transactions
* Optimistic Locking
* Connection Pooling

---

## Scalability

* Vertical Scaling
* Horizontal Scaling
* Load Balancing
* Caching
* CDN
* Stateless Services

---

## Reliability

* Health Checks
* Monitoring
* Logging
* Metrics
* Tracing
* High Availability
* Replication
* Disaster Recovery

---

## Architecture Patterns

* CQRS
* Saga Pattern
* Circuit Breaker
* Outbox Pattern
* Event Sourcing
* API Gateway
* BFF (Backend For Frontend)

---

## Security

* Authentication
* Authorization
* RBAC
* JWT
* Rate Limiting
* SQL Injection Prevention
* XSS Prevention
* CORS
* Secure API Design

---

## Cloud & DevOps

* Docker
* Docker Compose
* Kubernetes (Basics)
* CI/CD
* Blue-Green Deployments
* Rolling Deployments

---

## Interview Practice

Each topic will include:

* The problem it solves
* Why it exists
* Trade-offs
* Alternative solutions
* Working NestJS implementation
* Real-world use cases
* Common interview questions

---

# Technologies

* TypeScript
* NestJS
* PostgreSQL
* PostGIS
* Redis
* Docker
* RabbitMQ (planned)
* WebSockets

---

# Inspiration

Many examples are inspired by engineering decisions made while building production systems, especially:

* Multi-tenant SaaS platforms
* Fleet management
* Real-time GPS tracking
* Booking systems
* AI-assisted automation
* Event-driven workflows

---

# Goal

The objective is not to collect design patterns.

The objective is to become a better Systems Engineer by understanding **why** engineering decisions are made, the trade-offs they introduce, and how they behave in real production environments.

Every example in this repository should answer one simple question:

> **"What problem does this solve?"**

If a concept cannot answer that question, it probably doesn't belong in production.
