---
layout: post
title: Terms in Tech Industry
date: 2025-05-09 20:00:00
description:
tags: growth
categories: sample-posts
giscus_comments: true
related_posts: false
related_publications: true
---

Tech-related terms that I learned as a (new grad) software engineer:

1. **On-Premise**  
   Refers to software, infrastructure, or IT systems that are deployed and maintained within an organization’s own data center or physical location, rather than being hosted in the cloud.

2. **[Hadoop](https://www.databricks.com/glossary/hadoop#:~:text=Inspired%20by%20Google's%20MapReduce%2C%20a,after%20his%20son's%20toy%20elephant.)**  
   Apache Hadoop is an open-source, Java-based platform for big data analytics. It manages data processing and storage, enabling simultaneous real-time processing of large volumes of data.

3. **SaaS (Software as a Service)**  
   A cloud-based model for delivering software applications over the internet. Subscription-based and on-demand.

4. **CRUD**  
   Create, Read, Update, Delete—basic operations for persistent storage.

5. **OTS (Off-the-Shelf)**  
   Commercially available hardware or software, ready for immediate use.

6. **Kafka**  
   A distributed streaming platform for handling real-time data feeds. Used for data integration, event-driven systems, and processing pipelines.

7. **Service Degradation**  
   A drop in service performance without total failure.

8. **Regression**  
   A feature that stops working due to recent code changes.

9. **Latency Spike**  
   A sudden increase in response time.

10. **Throttling**  
    Intentional slowing of a service due to resource limits.

11. **Docker, Inc.**  
    Technology to package applications into containers (e.g., Databricks Runtime images).

12. **Remote Desktop Protocol (RDP)**  
    Microsoft protocol allowing remote control of another computer over a network.

13. **Data Clean Room**  
    a. Secure, privacy-centric environment for data collaboration  
    b. Used in marketing, analytics, and secure data sharing  
    c. Features: data encryption, anonymization, access control  
    d. Enables analysis without exposing raw data

14. **General Data Protection Regulation (GDPR)**  
    EU law for data privacy and protection across EU and EEA.

15. **Amazon Kinesis**  
    AWS service for collecting, processing, and analyzing real-time streaming data.

16. **VPC (Virtual Private Cloud)**  
    Isolated virtual network within the public cloud. AWS VPC offers on-premises-like control.

17. **OpenAPI Specification (OAS)**  
    a. Defines consistent REST API interfaces  
    b. Written in YAML or JSON  
    c. Standard for describing HTTP-based APIs, enabling machine- and human-readability

18. **TLS (Transport Layer Security)**  
    Protocol for securing data over networks via encryption and integrity checks.

19. **DBT (data build tool)**  
    Transforms raw data in a warehouse into clean, analysis-ready datasets.

20. **ERP (Enterprise Resource Planning)**
    Integrates core business processes into one system (finance, HR, supply chain, etc.).

21. **CIM (Confidential Information Memorandum)**  
    Document used in M&A to present a company to potential buyers or investors.

22. **CIM (Central Invoice Management)**  
    A unified, centralized approach to receiving, processing, and managing supplier invoices across an organization, typically using a digital platform.

23. **NUMA (Non-Uniform Memory Access)**  
    a. Each processor (or group of processors) has its own local memory  
    b. Access to local memory is faster than access to remote memory

24. **Prometheus**  
    a. an open-source monitoring and alerting system designed for reliability and scalability, especially in dynamic cloud-native environments like Kubernetes  
    b. Time-series database: Stores metrics as time-series data (value + timestamp)  
    c. Pull-based model: Scrapes metrics from targets (e.g., apps, services) via HTTP  
    d. PromQL: Powerful query language for analysis and alerting  
    e. Service discovery: Automatically finds targets via Kubernetes, Consul, etc.  
    f. Alertmanager: Sends alerts via email, Slack, PagerDuty, etc.

25. **PromQL(Prometheus Query Language)**  
    a. used to query time-series data stored in Prometheus  
    b. retrieve raw or aggregated metrics; define alerts; build dashbords (e.g. in Grafana)  
    c. Metrics | Labels | Time ranges

26. **Grafana**  
    an open-source data visualization and dashboarding tool commonly used with time-series databases like Prometheus, InfluxDB, and Loki

27. **OLTP, OLAP, Offline Database**

    - OLTP (Online Transaction Processing)
      - Use: Real-time, frequent read/write (e.g., banking, e-commerce)
      - Data: Highly normalized (split into multiple tables to avoid redundancy), up-to-date
      - Operations: INSERT, UPDATE, DELETE
      - Example: MySQL, PostgreSQL
    - OLAP (Online Analytical Processing)
      - Use: Complex queries, analytics, reports
      - Data: Historical, denormalized (data combined in one table)
      - Operations: SELECT with aggregations, GROUP BY
      - Example: Snowflake, BigQuery, Apache Druid
    - Offline Database
      - Use: Batch processing, not time-sensitive
      - Data: Often ingested from OLTP and stored for OLAP or ML
      - Operations: ETL jobs, large-scale joins/aggregations
      - Example: Hadoop HDFS, S3 + Presto

28. **PagerDuty**

    - severity, priority, urgency
    - event (something occurred)
    - alert (event normalized, contains SEVERITY value - critical, error, warning, info, unknown - based on preset rules)
    - incident (one or more alerts, high URGENCY or low URGENCY, and then notification and then assign PRIORITY - sev1 - sev5)
    - 3 states of an incident
      - triggered: no on-cal user has taken ownership of the incident yet
      - acknowledged:
      - resolved:

29. **ELK**
    ELK stands for Elasticsearch, Logstash, and Kibana. It refers to a stack of three open-source tools commonly used together for collecting, storing, searching, analyzing, and visualizing large volumes of data, especially logs and event data.

    Elasticsearch is a distributed search and analytics engine that stores and indexes data, making it easy to search and analyze large datasets in real time.

    Logstash is a data processing pipeline that ingests, transforms, and sends data from various sources to Elasticsearch (or other destinations).

    Kibana is a visualization tool that provides an interface for exploring, visualizing, and analyzing data stored in Elasticsearch.

    Together, the ELK stack is widely used for log management, infrastructure monitoring, security analytics, and business intelligence, giving organizations real-time insights into their systems and applications.

30. **SKU (Stock Keeping Unit)**
    Cloud providers borrowed the term because they sell products:
    VM, storage plan, database tier

31. **Pub/Sub**
    Publish-Subscribe messaging pattern
    Publisher sends messages to a topic
    Subscribers listen to that topic and receive any messages published there
    Common in event-driven architecture

32. **Kubernetes (K8s)**
    a container orchestration platform
    operating system for a cluster of machines
    Kubernetes Service: a stable network endpoint for accessing one or more pods

33. **Rest & gRPC and Armeria & Jetty**
    Rest and gRPC are API protocols
    Jetty and Armeria are Java server frameworks that can host those APIs
    Armeria is newer and designed to host both gRPC and REST together easily, while Jetty is more traditional for REST/HTTP.

34. **SDK (Software Development Kit)**
    a collection of tools, libraries, documentation, code samples, and utilities that a company or platform provides to help developers build applications that interact with their product or service

35. **DNS (Domain Name System)**
    e.g. translate google to 142.250.72.206

36. **PITR (Point-In-Time Recovery)**
    It’s a feature in databases (like PostgreSQL, MySQL, etc.) that lets you restore data to exactly a specific point in time, not just the last full backup.

37. **Data Clean Room**
    A data clean room is a secure, controlled environment where multiple organizations can collaborate and analyze data from different sources while maintaining strict privacy and security protections. These environments enable companies to share and analyze sensitive first-party data without exposing personally identifiable information (PII) or compromising data confidentiality.

38. **SLA (Service Level Agreement)**
    A formal contract or agreement between a service provider and a customer that defines the specific level of service, performance standards, and expectations to be delivered

39. **OKR (Objectives and Key Results)**
    A goal-setting framework used by companies to define measureable outcomes

40. **Third Normal Form**
    No non-prime attribute is functionally dependent on (that is, contains a fact about) any other non-prime attribute
