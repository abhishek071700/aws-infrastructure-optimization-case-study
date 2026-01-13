# EC2 Rightsizing Analysis (Client A – NDA Masked)

## Objective
Identify over-provisioned EC2 instances using CloudWatch utilization metrics and recommend appropriate instance types to reduce monthly AWS cost without impacting performance.

---

## Methodology
1. Reviewed EC2 inventory (instance families, OS, region).
2. Collected CloudWatch CPU utilization trends (~4 weeks).
3. Mapped utilization vs provisioned capacity.
4. Proposed rightsizing and modernization options based on pricing + operational risk.

---

## Key Findings

### 1) Production Workload (Linux)
- Observation: sustained low average CPU utilization (~20–25%)
- Conclusion: instance is over-provisioned for steady-state workload

✅ Recommendation:
- **m5.xlarge → m5.large**

Estimated monthly saving: **~$77.24**

---

### 2) Staging Workload (Linux)
- Observation: older generation burstable family

✅ Recommendation:
- **t2.medium → t3.medium**

---

## Validation Checklist
- Confirm peak CPU and memory requirements
- Review disk IOPS and EBS needs
- Run performance tests post-change
- Monitor CloudWatch metrics after cutover

---

## Notes
All resource names and identifiers are masked due to NDA.
