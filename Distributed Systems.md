# Distributed Systems

This page is my attempt to better understand distributed systems and why they are so important to modern software engineering.

Distributed systems are one of the most common concepts that appear across infrastructure engineering, databases, cloud computing, AI infrastructure, networking, and platform engineering.

The goal is not to become an expert.

The goal is to better understand the problems engineers are solving and the environments where strong technical talent often develops.

---

# What Is A Distributed System?

A distributed system is a collection of computers working together to achieve a common goal.

Instead of running everything on a single machine, work is distributed across multiple machines.

Examples include:

* Google Search
* Netflix
* Uber
* AWS
* Databricks
* Snowflake
* MongoDB

Most modern technology companies rely on distributed systems.

---

# Why Distributed Systems Exist

As software grows, a single server eventually becomes a bottleneck.

Companies need systems that can:

* Scale
* Remain available
* Handle failures
* Process large amounts of data
* Support millions of users

Distributed systems help solve these challenges.

---

# Core Concepts

## Scalability

The ability to handle increasing demand.

Questions:

* Can the system support more users?
* Can it support more data?
* Can it support more requests?

---

## Reliability

The ability to continue operating despite failures.

Examples:

* Server failures
* Network failures
* Hardware failures

Strong systems expect failures to happen.

---

## Availability

The ability for a system to remain accessible.

Examples:

* Uptime
* Service Availability
* Fault Tolerance

Common goal:

Keep services running even when parts of the system fail.

---

## Consistency

Ensures users see accurate and predictable data.

Examples:

* Banking Transactions
* Account Balances
* Inventory Systems

Consistency often requires tradeoffs.

---

## Latency

How long it takes for a system to respond.

Examples:

* Search Results
* API Responses
* Database Queries

Reducing latency is often a major engineering challenge.

---

# CAP Theorem

One of the most commonly referenced concepts in distributed systems.

A distributed system can only fully optimize for two of the following three properties:

* Consistency
* Availability
* Partition Tolerance

Engineers often make tradeoffs depending on business requirements.

---

# Common Distributed System Technologies

## Databases

* PostgreSQL
* MongoDB
* Cassandra
* CockroachDB
* Redis
* ClickHouse

## Streaming Systems

* Kafka
* Pulsar

## Containers & Orchestration

* Docker
* Kubernetes

## Cloud Platforms

* AWS
* Azure
* Google Cloud

---

# Companies Known For Distributed Systems Expertise

## Infrastructure

* Databricks
* Snowflake
* MongoDB
* Confluent
* Cockroach Labs

## Cloud

* AWS
* Google Cloud
* Microsoft Azure

## Product Companies

* Netflix
* Uber
* LinkedIn
* Airbnb
* Stripe

---

# Candidate Signals

Distributed systems experience often appears through:

* Infrastructure Engineering
* Platform Engineering
* SRE
* Backend Engineering
* Database Engineering

Examples:

* Building scalable systems
* Reliability improvements
* Performance optimization
* Large-scale data processing
* Distributed databases
* Streaming systems

---

# Why Recruiters Should Understand Distributed Systems

Many senior engineering roles involve distributed systems in some form.

Understanding the basics helps recruiters:

* Read resumes more effectively
* Conduct stronger intake meetings
* Ask better questions
* Understand candidate impact
* Differentiate between roles and skill sets

---

# Questions I'm Continuing To Explore

* What separates good distributed systems engineers from exceptional ones?
* How do companies approach scalability differently?
* Which technologies appear most often in high-performing teams?
* What skills become increasingly important as systems grow?
* How do distributed systems influence modern infrastructure engineering?
