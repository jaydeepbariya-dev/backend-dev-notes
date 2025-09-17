### System Design Topics Roadmap (HLD + LLD)

## System Design Basics

Introduction to System Design

Types of system design: HLD vs LLD

Goals of system design: scalability, reliability, maintainability

Key concepts:

Scalability (vertical vs horizontal)

Availability, Reliability, Redundancy, Fault Tolerance

Consistency, Availability, Partition Tolerance (CAP theorem)

Load vs Latency vs Throughput

--
## High-Level Design (HLD)

Focus: Architecture and component-level decisions

2.1 Architecture Patterns

Monolithic vs Microservices

Client-Server, N-Tier Architecture

Event-Driven Architecture

Service-Oriented Architecture (SOA)

2.2 Scaling & Performance

Load balancers (L4 vs L7)

Caching strategies:

CDN, Redis, Memcached

Cache-aside, Write-through, Write-back

Database scaling:

Vertical vs Horizontal scaling

Replication & Sharding

Partitioning & Data Distribution

2.3 Storage Systems

SQL vs NoSQL overview

CAP theorem trade-offs

Indexing basics

Data modeling strategies

2.4 Messaging & Communication

Synchronous vs Asynchronous

Message queues (RabbitMQ, Kafka, SQS)

Pub/Sub architecture

Event sourcing basics

2.5 Reliability & Fault Tolerance

High Availability setups (Active-Active, Active-Passive)

Failover & Disaster Recovery

Health checks & monitoring

2.6 Designing APIs

REST API principles

gRPC / Thrift overview

Versioning and backward compatibility

--
## Low-Level Design (LLD)

Focus: Class-level, object-oriented design, and implementation details

3.1 Object-Oriented Design

Classes, Objects, Interfaces

Encapsulation, Inheritance, Polymorphism, Abstraction

Association, Aggregation, Composition

3.2 Design Principles

SOLID principles

DRY, KISS, YAGNI

Interface Segregation & Dependency Inversion

3.3 Design Patterns

Creational: Singleton, Factory, Builder

Structural: Adapter, Decorator, Composite, Proxy

Behavioral: Observer, Strategy, Command, State

Architectural: MVC, Layered Architecture, Event-Driven

3.4 UML & Modeling

Class diagrams

Sequence diagrams

Component diagrams

Deployment diagrams

3.5 Database & Persistence Layer

Entity design, relationships

Transaction management

Connection pooling

Caching integration

3.6 Concurrency & Threading

Multithreading concepts

Locks, synchronized blocks, volatile

Thread pools & Executors

3.7 API Implementation

Request handling

Error handling & retries

Logging & Metrics

Security (Auth & AuthZ)

--
## Performance, Reliability & Monitoring

Rate limiting & throttling

Circuit Breaker pattern

Bulkheads & fallback strategies

Monitoring & metrics collection

Alerting and SLAs

--
## Real-World Systems

Design exercises: incremental approach

URL Shortener

Online Payment System

Social Media Feed

Chat System / Messaging App

Ride-Hailing System

E-commerce System
