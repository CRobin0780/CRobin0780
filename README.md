# Chris Robinson

**Systems Administrator · Cloud Infrastructure · Cybersecurity**

U.S. military veteran working in DoD IT support. I build and document my own enterprise-style homelab, Fort Reign, to practice Windows Server and Active Directory administration, infrastructure automation, and security monitoring.

- **Clearance:** active Secret
- **Certifications:** CompTIA Security+ CE, Network+ and A+; Microsoft AZ-900; ITIL 4 Foundation
- **Studying:** AZ-104 (Azure Administrator)
- **Looking for:** Systems Administrator, Infrastructure Engineer, and cloud/security engineering roles

<!-- EDUCATION: add your degree or program, school and year here, exactly as on your resume. -->

---

## Experience

**Client Support Administrator, DoD program support** (current)
End-user and systems support in a cleared DoD environment.

**U.S. military: Logistics Officer** (4 years)
Supply chain management, resource planning and team leadership in operational settings.

---

## Fort Reign homelab

A self-built lab that models a small company's IT estate. I use it to practise the job I want, and I document both its current state and the target design.

| Area | Current state | Next |
|---|---|---|
| **Virtualization** | Three-node Proxmox VE cluster | Infrastructure as code (Terraform + Ansible) and a timed backup/restore drill |
| **Identity** | Windows Server 2022 Active Directory: DNS, DHCP, Group Policy. A separate administrative account and role-based admin groups, so day-to-day admin doesn't use Domain Admin. | Retire the legacy admin accounts, add a second domain controller, Tier-0 model |
| **Network** | Single flat subnet, with a documented segmentation design | Move to segmented VLANs and keep allow/deny test evidence |
| **Monitoring** | Wazuh with Sysmon on Windows endpoints, and custom Wazuh rules | Detection rules as code, with test events and ATT&CK mapping |
| **Hybrid identity** | Microsoft Entra Connect sync with a lab Entra ID tenant | Azure administration labs (AZ-104) with teardown scripts |
| **Service desk** | An ITIL ticket lifecycle and Help Desk ↔ SOC escalation model, documented | A ticketing system configuration and sample tickets |

---

## Projects

All of these are **private repositories** for now. I'm removing internal details from them and adding tests and screenshots before I publish them. Links will appear here when each one is public.

- **Fort Reign Control Plane:** a Proxmox inventory and configuration-drift monitor.
  - FastAPI, PostgreSQL, scheduled workers, alerts, Prometheus/Grafana.
  - CI with secret scanning. A fail-closed, manual deployment workflow with pre-migration backups and rollback is in review.
- **ReignForge:** a self-hosted cloud-engineering training platform and simulator (Next.js, TypeScript).
  - Around 7,900 unit tests and 342 end-to-end tests.
  - CI with secret scanning, dependency auditing, and container image scanning.
- **Fort Reign enterprise lab docs:** network and Active Directory design, an RBAC admin model with a PowerShell provisioning script, SOC monitoring design, and incident-response playbooks.
- **Cloud security engineering lab** *(planned)*: an AWS account baseline in Terraform, with GitHub OIDC (no stored keys), CloudTrail, GuardDuty and policy checks in CI.

---

## Skills

**Systems administration:** Windows Server 2022 · Active Directory · Group Policy · DNS/DHCP · PowerShell · Linux (Ubuntu) · Proxmox VE · Docker

**Cloud infrastructure:** Microsoft Entra ID · Entra Connect · Azure fundamentals · GitHub Actions · Terraform (learning)

**Cybersecurity:** Wazuh · Sysmon · MITRE ATT&CK · NIST SP 800-53 / 800-61 · secret scanning (Gitleaks) · vulnerability scanning (Trivy)

**Practices:** ITIL 4 · documentation and runbooks · Git

---

## Contact

[LinkedIn](https://www.linkedin.com/in/christionirobinson/)
