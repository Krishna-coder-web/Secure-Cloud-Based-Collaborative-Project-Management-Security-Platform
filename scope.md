# Scope Statement
**The scope of this project is to design, develop, deploy, and evaluate a secure cloud-based collaborative project management platform that supports project, task, team, and document management while incorporating authentication, fine-grained authorization, multi-tenant isolation, secure document sharing, encryption, audit logging, security monitoring, behavioural anomaly detection, risk scoring, and AI-assisted security analysis. The research will focus on evaluating whether the integrated security architecture can improve protection, monitoring, and identification of potentially risky activities within a collaborative cloud environment. The project will not cover hardware/IoT systems, computer vision, blockchain, full-scale SIEM or SOC functionality, malware analysis, or enterprise-scale autonomous incident response.**

# 1. Scope of the Project

The project will cover the design, development, deployment, and evaluation of a secure cloud-based collaborative project management platform.

**The platform will provide two connected layers:**

## A. Collaborative Project Management

The system will allow users to:

- Register and authenticate
- Create and manage organizations
- Create projects
- Create and assign tasks
- Manage project teams
- Assign roles and permissions
- Track project progress
- Upload and manage project documents
- Share documents with authorized users
- Collaborate through project activities/comments
- View relevant project information through dashboards

The purpose is to provide the basic collaborative environment required for the security research.

## B. Security Architecture

Security will be built into the platform rather than added as a separate feature.

The scope includes:

### Authentication
- Secure user authentication
- Session management
- Authentication-event logging

### Authorization
- RBAC
- Fine-grained permissions
- Project/resource-level access control
- Least-privilege principles
- Tenant isolation

### Document Security
- Controlled document access
- Secure document storage
- Encryption
- Controlled sharing/download access

### Security Monitoring
- Audit logging
- Security-event recording
- Monitoring of important user activities
- Security dashboard

### Behavioural Analysis

The system will analyse relevant user activity such as:

- Login behaviour
- Failed authentication
- File access
- File downloads
- Project access
- Permission changes
- Other security-relevant activities

### Risk Assessment

The system will:

- Identify security-relevant events
- Analyse behavioural indicators
- Calculate a risk score
- Assign a risk level
- Generate appropriate alerts or recommendations

# 2. AI/ML Scope

AI/ML will be used specifically for the security-analysis component.

```text
User Activity
      ↓
Security Events
      ↓
Feature Extraction
      ↓
Anomaly Detection
      ↓
Risk Assessment
      ↓
Security Alert / Analysis
```

# 3. Cloud Scope

The system will be deployed as a cloud-based application.

The cloud component will cover:

- Cloud-hosted application
- Cloud database
- Cloud/object document storage
- Secure communication
- Application configuration and secrets
- Logging/monitoring
- Basic cloud infrastructure security

# 4.Research Scope

The research will evaluate:
Security

- Unauthorized access prevention
- Privilege misuse
- Tenant isolation
- Document access control
- API security
- Security-event visibility

## Behavioural detection

- Detection of abnormal activity
- Detection accuracy
- False positives
- Risk classification

## System performance

- Response time
- API latency
- Resource usage
- Behaviour under increasing activity/events

# 5. Scope Boundary
```text
                 OUR PROJECT
                     │
        ┌────────────┴────────────┐
        │                         │
 Project Management          Security Layer
        │                         │
 Projects                   Authentication
    │                             │
 Tasks                      Authorization
    │                             │
 Teams                      Document Security
    │                             │
 Documents                  Audit Logging
    │                             │
 Collaboration              Monitoring
        │                         │
        │                    Anomaly Detection
        │                         │
        │                    Risk Scoring
        └────────────┬────────────┘
                     │
               Cloud Deployment
```

# 6. Out Of Scope Things

Explicitly outside the current scope:

- IoT or hardware-based security
- Computer vision
- Face recognition
- Mobile application development
- Full enterprise SIEM replacement
- Full-scale SOC platform
- Antivirus/endpoint protection
- Malware analysis engine
- Network intrusion detection
- Penetration-testing framework
- Blockchain
- Cryptocurrency
- Building a new encryption algorithm
- Training a large/deep foundation model
- Autonomous incident response
- Supporting every cloud provider
- Enterprise-scale production deployment