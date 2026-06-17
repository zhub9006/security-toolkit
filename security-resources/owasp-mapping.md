# OWASP Mapping — Compliance-Driven Security Controls

## OWASP Top 10 (2021) → Clinical Trial Privacy Lessons

| OWASP Category | Clinical Trial Insight | Recommended Control |
|---------------|----------------------|-------------------|
| A01: Broken Access Control | Controlled-access repositories with DUAs | Implement RBAC + ABAC with regular access reviews |
| A02: Cryptographic Failures | PEP encryption methodology | Enforce encryption at rest and in transit; use strong key management |
| A03: Injection | N/A (clinical focus) | Parameterized queries, input validation, CSP headers |
| A04: Insecure Design | Privacy-by-design frameworks | Threat modeling with data privacy as a first-class requirement |
| A05: Security Misconfiguration | Data Protection Agency collaboration | Automated compliance scanning; infrastructure-as-code with security baselines |
| A06: Vulnerable Components | N/A (clinical focus) | SCA tools, dependency scanning, SBOM management |
| A07: Auth Failures | Multi-layered access management | MFA, adaptive authentication, session management |
| A08: Software/Data Integrity | De-identification validation | Data integrity checks, signed releases, sub-resource integrity |
| A09: Logging Failures | Audit trails for data access | Comprehensive audit logging, SIEM integration, anomaly detection |
| A10: SSRF | Federated architecture limits internal exposure | Network segmentation, allowlists, disable URL fetching |
