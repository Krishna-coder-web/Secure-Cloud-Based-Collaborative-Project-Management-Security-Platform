# 1. Primary Research Contribution
The primary expected contribution will be:

A security-focused architecture for cloud-based collaborative project management that integrates fine-grained access control, secure document sharing, audit logging, behavioural anomaly detection, and risk scoring within a unified environment.


# 2. Specific Expected Contributions

## Contribution 1: Integrated Security Architecture

We will design an architecture that combines:

```text
Authentication
      ↓
Fine-Grained Authorization
      ↓
Secure Resource Access
      ↓
Audit Logging
      ↓
Behavioural Analysis
      ↓
Risk Scoring
      ↓
Security Alert / Analysis
```

## Contribution 2: Fine-Grained Security Model for Collaboration

The project will apply authorization at more than simply the user-login level.

Access can depend on:

- User
- Organization/tenant
- Project
- Role
- Resource
- Permission


## Contribution 3: Security-Aware Behaviour Monitoring

The system will create and analyse security-relevant activity data.

For example:

**Normal login → normal project access → normal document activity**

versus:

**New device → unusual login time → access to multiple projects → large number of downloads**

The second pattern can be treated as potentially suspicious.

## Contribution 4: Risk-Based Security Assessment

Instead of merely recording:

**"User downloaded 20 files."**

The system can combine multiple indicators and produce something like:

**High Risk Activity**

with the underlying events contributing to that score.

## Contribution 5: Experimental Evaluation

**The project will evaluate:** 

- Unauthorized-access prevention
- Privilege-control effectiveness
- Tenant isolation
- Document-access controls
- Anomaly detection
- Risk classification
- False positives
- System performance


# 3. What We Are NOT Claiming

**We are not claiming:**

- We invented a new RBAC model.
- We invented a new encryption algorithm.
- We invented a new anomaly-detection algorithm.
- We created a replacement for enterprise SIEM.
- We can detect every cyberattack.
- The platform provides absolute security.
- AI can independently determine whether an activity is malicious.
- Our architecture is universally better than all existing approaches.

# 4. Final Research Contribution

**The expected contribution of this research is the design and evaluation of an integrated security architecture for cloud-based collaborative project management. The proposed architecture combines fine-grained authorization, secure document sharing, audit logging, behavioural anomaly detection, and risk scoring within a multi-tenant collaborative environment. The research will investigate whether integrating these security mechanisms can improve unauthorized-access prevention, security-event visibility, identification of abnormal user behaviour, and risk-based security monitoring.**