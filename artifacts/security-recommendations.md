# Security Recommendations (Client A – NDA Masked)

## Objective
Improve AWS security posture while maintaining operational stability and supporting cost optimization.

---

## Recommendations

### 1) MFA Enforcement
- Enable MFA for all IAM users
- Mandatory for privileged accounts

### 2) Access Key Hygiene
- Rotate keys regularly (e.g. 90 days)
- Remove unused access keys
- Prefer STS temporary credentials where possible

### 3) Least Privilege
- Review inactive users
- Reduce overly permissive IAM policies

### 4) Encryption
- Encrypt EBS volumes using AWS KMS

### 5) Network Controls
- Reduce public exposure
- Keep workloads in private subnets
- Enable VPC Flow Logs for visibility

---

## Notes
Sanitized security summary based on AWS best practices.
Client identity masked due to NDA.
