---
title: "Selected Projects"
description: "A selection of the platforms, products, and research programs CST has delivered for enterprise clients across Europe."
date: 2026-08-17T10:00:00+03:00
draft: false
---

# Selected Projects

A selection of the platforms, products, and research programs we have delivered for clients including Deutsche Telekom, T-Systems, SAP, IONOS, and Daiteap — spanning cloud and multi-cloud, Big Data, blockchain, and real-time communication.

## Cloud & Data Infrastructure

### GAIA-X Federation Services
*T-Systems International GmbH* · 2022–2023

Core federation services for the European GAIA-X ecosystem — a connected, open data infrastructure based on European standards and values. The services are distributed, decentralized, and designed for secure data transfer across cloud providers.

**Core components:** Identity & Trust · Federated Catalog · Sovereign Data Exchange · Compliance

**Key technologies:** Kubernetes, Helm, Docker, CI/CD

- Deployed multiple services on Kubernetes using CI/CD and Helm
- Implemented new services: Principal Creation, Invitation, DID Management, and Claim Mapper
- Automated service integrations and created Docker images for existing services

### ALTERNATIVE
*EU Horizon 2020* · 2021–2024

A platform that detects the cardiotoxicity of chemicals and their biotransformation products, helping regulators and industry identify and prevent cardiotoxic co-exposures. CST delivered the cloud data platform and web-based data exchange that power the research.

**Key technologies:** CKAN, JupyterHub, S3, OIDC/SSO, Keycloak, Kubernetes, Istio

- Developed a cloud data platform for deploying and operating machine-learning models
- Built a CKAN-based data exchange with custom extensions for OIDC/SSO, S3 storage, and theming
- Integrated JupyterHub, CKAN, and S3 with CI/CD automation

### Digital Experience Portal (DXP)
*SAP* · 2021–2022

An integrated developer portal (similar to Spotify Backstage) for managing the software development process — code repositories, release management, security, logging, and infrastructure monitoring. DXP extends the Kubernetes API with custom resources, operators, and controllers.

**Key technologies:** Golang, Kubernetes/Docker, GraphQL, Terraform, Angular, Dynatrace, AWS/GCP

- Implemented logging and monitoring with fluentbit, Kibana, and ElasticSearch/OpenDistro
- Built a Kubernetes operator automating GCP load-balancer and routing configuration
- Implemented secret management with External Secrets Operator, HashiCorp Vault, and Kubernetes

### Daiteap Multi-Cloud Platform
*Daiteap GmbH & Co. KG* · 2019–2023

Project management and technical architecture of a cloud-native multi-cloud orchestrator. The platform manages Kubernetes clusters, virtual machines, and S3 storage across AWS, GCP, Azure, Alicloud, on-premise, and IoT devices — with encrypted VPN interconnection.

**Key technologies:** AWS, GCP, Azure, Alicloud · Golang, Python/Django · Kubernetes, Docker, Cluster-API, Helm, CEPH, ArgoCD, Longhorn · Terraform, Ansible · Keycloak, PKI, OIDC · VueJS

- Integrated major public cloud provider APIs
- Designed network topology using VPN, IP routing, DNS, TLS, centralized IDM, and monitoring
- Implemented multi-tenant functionality and managed backend and frontend teams

### DataLab / HALO
*Deutsche Telekom AG* · 2015–2019

Big Data infrastructure as a service on Open Telekom Cloud. DataLab provided multi-tenant Hadoop environments, while HALO extended it with fully automated provisioning of cloud resources, Hadoop clusters, and security services.

**Key technologies:** Cloudera Enterprise, Hortonworks · HDFS, Hive, Spark, Impala, HBase, Kafka · Ansible, Terraform, OpenStack · Kerberos, LDAP

- Designed and implemented the software-as-a-service layer on OpenStack
- Automated Hadoop distribution installation, configuration, and user management
- Managed resource allocation, performance analysis, and monitoring

### Octave
*Octave IO* · 2018–2021

A cloud-based Big Data analytics platform based on Hortonworks Hadoop, hosted on OVH and GCP, with REST APIs for data ingest and access, SSO, identity management, logging, and monitoring.

**Key technologies:** Hortonworks, NIFI, HDFS, ELK stack, Kubernetes, Python/Django

- Implemented Python/Django functionalities to specification
- Packaged and deployed with CI/CD
- Maintained and bug-fixed production servers

## Blockchain & DLT

### NOMAD
*Deutsche Telekom* · 2018–2022

A blockchain platform for signing roaming and mobile data contracts between mobile network operators worldwide, based on Hyperledger Fabric.

**Key technologies:** Hyperledger Fabric, PKI, HSM, SoftHSM, Kubernetes, OpenSSL, Golang/Node.js

- Architected the Hyperledger adaptation for the NOMAD use case
- Migrated the platform to Kubernetes and set up core and operator network components
- Supported MNO technical teams and participated in GSMA technical discussions

### DIMAS
*Deutsche Telekom* · 2021–2022

Self-sovereign identity (SSI) use cases built on decentralized identifiers (DIDs) — issuing, holding, verifying, and presenting verifiable credentials on a Hyperledger Indy ledger.

**Key technologies:** Node.js, ACA-py, k3s Kubernetes, Hyperledger Indy

- Built Kubernetes deployments and Docker images
- Automated deployment of organizations joining the network
- Set up and joined a demo organization network on AWS

### Nylon
*Deutsche Telekom* · 2022–2023

An environment for managing a stable coin used in payments between telecom operators, eliminating exchange-rate risk between currencies under telco contracts.

**Key technologies:** Celo Alfajores Testnet, Node.js, AWS EKS, ingress controller with cert management

- Prepared the AWS network environment and built Docker images
- Deployed the solution and its automation packages on AWS

### Telco-DLT
*Deutsche Telekom* · 2022–2023

Research of distributed ledger technologies (DLTs) — measuring performance and developing telco use cases for collecting, processing, and storing network data in real time.

**Key technologies:** Hyperledger Fabric, Celo, Hyperledger Caliper, JMeter, Kubernetes

- Built a Hyperledger Fabric test network with smart contract chaincode
- Ran distributed performance testing with Hyperledger Caliper
- Automated deployments on AWS

## AI & Big Data

### Digital Service Assistant (ELIZA / DSA)
*Deutsche Telekom AG* · 2016–2020

An AI customer-support assistant that automates parts of customer service by learning from user data and activity. Data is ingested into a Hadoop cluster, processed, and used to power AI use cases.

**Key technologies:** Python/Django, Kubernetes, Docker, NIFI, HDFS, HBase, Kafka, Solr

- Implemented the ELIZA AI assistant with data ingest and access paths based on NIFI and HBase
- Built microservice-based customer-service use cases on Kubernetes
- Implemented CI/CD pipelines for automated deployment

## Data Spaces & Energy

### IONOS Data Spaces (POSSIBLE, HEALTH-X, Marispace)
*IONOS* · 2023

Architecture consulting and DevOps for GAIA-X and IDS-based data space technologies across IONOS sub-projects — including healthcare (HEALTH-X) and maritime (Marispace) use cases.

**Key technologies:** GAIA-X, IDS, Eclipse Dataspace Connector (EDC), DAPS, Terraform, Kubernetes

- Designed architectures for the POSSIBLE data-space project
- Dockerized GAIA-X services (Federated Catalog) and automated infrastructure with Terraform
- Packaged and deployed the EDC Connector, IDS DAPS, and IoT OpenTwins platform

### Frodexim
*Frodexim Trade Ltd* · 2021–2022

An open-market system for exchanging electricity usage information on the Bulgarian energy market, implementing six modules per the ESO specification.

**Key technologies:** Docker, .NET Core 6.0, XML/XSD, REST API, Keycloak

- Implemented settlement, billing, metering, invoice, and data-exchange modules
- Built the user-management module with Microsoft Blazor
- Packaged and deployed the whole solution with docker-compose

## Communication & VoIP Heritage

Over the years CST has also delivered telecom and real-time communication platforms:

- **RCS-e / Joyn** (Deutsche Telekom, 2011–2012) — SIP-based backend and messaging platform for the RCS-e standard
- **PAYCALL** (Headstore AG, 2015–2016) — WebRTC voice and video calling platform on AWS
- **T-Voice** (Deutsche Telekom, 2008–2009) — unified messaging combining voicemail, email, SMS, and Skype
- **Soundcall** (Soundcall GmbH, 2012–2013) — IMS-integrated sound-mixing service for live calls
- **RingRTC** (2014–2015) and **Voiptester** (2012–2014) — in-house WebRTC and VoIP products
- **Voicemail-to-Text** (Deutsche Telekom, 2010–2011) — speech-to-text voicemail proof of concept

---

[Back to home](/)
