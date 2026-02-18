# Personal GitHub Pages Portfolio Guide (Senior Full-Stack Developer)

## Goal
Create a professional GitHub Pages site (`username.github.io`) that serves as a **portfolio + credibility hub**, showcasing expertise in **.NET, microservices, and distributed systems**.

---

# 1. Core Sections (Must Have)

## 1. Hero / Introduction
**Purpose:** Quickly communicate who you are and your value.

**Include:**
- Full Name - Arjay Tabangay
- Title Senior Full-Stack Developer
- Short value statement (1–2 lines)
- Key strengths (scalability, distributed systems, cloud)
- Call-to-action (GitHub, LinkedIn, Resume)

**Example:**
> Senior Full-Stack Developer with 9+ years experience building scalable microservices and distributed systems using .NET and cloud technologies.

---

## 2. About Me
**Purpose:** Professional narrative.

**Include:**
- Years of experience - 9+ years
- Types of projects (Logistics and Lead Management)
- Technical focus (microservices, APIs, performance)
- Current specialization

---

## 3. Skills / Tech Stack
Group skills clearly and avoid long unstructured lists.

**Backend**
- .NET (latest)
- ASP.NET Core
- Entity Framework Core
- REST APIs
- Messaging (RabbitMQ)

**Frontend**
- Vue / Vite / TailwindCSS

**Infrastructure**
- Docker
- Redis
- PostgreSQL / SQL Server
- CI/CD
- Azure

**Architecture**
- Microservices
- Distributed systems
- Event-driven design
- Clean Architecture

---

## 4. Featured Projects (Most Important Section)

### Loan Management System (LMS) — In Progress
- Type: Personal Project
- Status: Under Development

- Problem:
  Need a scalable system to manage loan applications, approvals, repayments, and user accounts.

- Solution:
  Designing a modular, microservices-based platform that handles loan lifecycle management with clear service boundaries.

- Tech Stack:
  - .NET (latest)
  - ASP.NET Core
  - Entity Framework Core
  - PostgreSQL
  - Docker
  - MassTransit/RabbitMQ
  - Redis
  - EventStoreDb
  - Vue/Vite/TailwindCSS

- Architecture:
  - CQRS
  - Microservices with database-per-service pattern
  - Event-driven communication (RabbitMQ)
  - API Gateway (YARP) for routing and aggregation
  - Containerized services using Docker Compose
  - Caching layer using Redis
  - Centralized configuration and environment-based settings

- Core Modules:
  - Loan Origination
  - Application intake
  - Underwriting decision
  - Approval / rejection
  - Offer generation
  - Loan activation
  - Loan Servicing
  - Amortization schedule
  - Interest accrual
  - Balance tracking
  - Status lifecycle
  - Payment Processing
  - Payment initiation
  - Payment confirmation
  - Allocation to principal/interest/fees
  - Idempotent reprocessing
  - Collections
  - Delinquency tracking
  - Dunning workflow
  - Penalty application
  - Ledger / Accounting
  - Double-entry style ledger
  - Immutable transaction history
  - Audit traceability
  - Customer Management
  - Borrower profile
  - Contact updates
  - Risk classification
  - Risk & Scoring (internal)
  - Risk evaluation results
  - Decision artifacts
  - Notifications
  - Event-triggered messaging
  - Identity & Access
  - Role-based access
  - Tenant isolation
  - Reporting & Projections
  - Read-optimized views
  - Aggregated reporting

- Focus Areas:
  - Scalability and service isolation
  - Consistent package versioning across services
  - Clean architecture and maintainability
  - Fault tolerance and retry mechanisms
  - High data integrity
  - Strict auditability
  - Idempotent processing
  - Event-driven integration
  - Multi-tenant readiness

- Key Highlights:
  - Designed for horizontal scaling
  - Asynchronous processing for critical workflows
  - Decoupled services via messaging

---

## 5. Experience Summary
Not a full resume—only highlights.

**Include:**
- DogstartDigital
- Senior Software Developer


## 6. Blog / Articles (Optional but Recommended)

Write about:
- .NET latest features
- Microservices patterns
- Docker setups
- Package version consistency across services

Purpose: Position yourself as a **senior engineer and thought leader**.

---

## 7. Contact
- Email - arjay.tabangay@gmail.com
- GitHub - https://github.com/ArjayTabangay
- LinkedIn  - https://www.linkedin.com/in/arjay-tabangay-859790165/

---

# 2. Optional (High Impact)

## Architecture Showcase
Create a dedicated section explaining how you design systems.

**Include:**
 - Concurrent payment submissions
 - No double processing
 - Strong consistency within aggregates
 - Eventual consistency across services
 - Full audit trail of state transitions
 - Zero secret-in-code policy
 - Observability-first design
 - Resilience patterns required
 - Fail-fast APIs
 - Async-first I/O model
 - Backward-compatible evolution

---

## Case Studies
Go deeper than project listings.

**Format:**
- Problem
- Constraints
- Solution
- Trade-offs

---

# 3. What NOT to Include
- Generic statements ("I love coding")
- Too many beginner projects
- Long, unfocused skill lists
- Irrelevant personal information

---

