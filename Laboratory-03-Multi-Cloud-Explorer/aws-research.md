AWS Research

1. Brief Overview
Amazon Web Services (AWS) is a comprehensive, evolving cloud computing platform provided by Amazon. It offers over 200 fully featured services from data centers globally, enabling businesses to access infrastructure resources—such as compute power, database storage, and content delivery—on a pay-as-you-go basis without requiring upfront physical hardware investments.

2. Global InfrastructureAWS operates on a globally distributed infrastructure organized around Regions and Availability Zones (AZs):
AWS Regions: Physical geographic locations across the world where AWS clusters data centers.
Availability Zones (AZs): Each Region consists of multiple isolated and physically separate AZs connected through ultra-low-latency, high-throughput network links. Each AZ contains one or more discrete data centers with independent power, cooling, and security, allowing users to deploy redundant, highly available applications that remain resilient against local outages.

3. Cloud Management Console
The AWS Management Console is a web-based, user-friendly graphical interface used to access, create, monitor, and manage AWS resources. It provides tools for searching specific services, managing access policies, launching virtual instances, reviewing costs, and monitoring cloud infrastructure health from a single web browser interface.

4. Four Core Services
Amazon EC2
Amazon Elastic Compute Cloud (EC2) provides resizable, virtual computing servers (called instances) in the cloud. It allows developers to configure CPU, memory, storage, and networking capacity to run applications on demand with full control over the operating system environment.

Amazon S3
Amazon Simple Storage Service (S3) is an object storage service designed for high durability, scalability, and security. It stores data as objects within buckets, making it ideal for hosting static files, backing up system data, running data analytics, and serving media at scale.

Amazon RDS
Amazon Relational Database Service (RDS) is a managed relational database service that simplifies setting up, operating, and scaling databases in the cloud. It supports engines such as MySQL, PostgreSQL, MariaDB, Oracle, and SQL Server, handling complex tasks like automated backups, hardware provisioning, and software patching.

Amazon VPCAmazon Virtual Private Cloud (VPC) allows users to provision a logically isolated section of the AWS Cloud where they can launch AWS resources in a defined virtual network. Users maintain total control over their virtual networking environment, including IP address ranges, subnets, route tables, and network gateways.

5. Three Advantages
Scalability and Elasticity: Resources can quickly scale up or down automatically based on demand, eliminating capacity planning guesswork.
Cost Efficiency: Utilizes a pay-as-you-go pricing model, reducing capital expenditure by requiring payment only for the specific resources consumed.
High Reliability and Security: Built with robust global redundancy and enterprise-grade physical and digital security controls to meet strict compliance standard requirements.

6. Typical Enterprise Use CasesWeb Application Hosting and E-Commerce: Running scalable, multi-tier web platforms using EC2 for app servers, S3 for media assets, and RDS for backend database management.
Big Data Processing and Analytics: Storing massive unstructured datasets in S3 to process with machine learning or analytical tools without network bottlenecks.
Disaster Recovery and Data Backup: Replicating critical databases and system snapshots across isolated AWS Regions and AZs to ensure business continuity.
