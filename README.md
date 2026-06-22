# Alex Ardent Lucero
linkedin.com/in/alex-ardent-lucero | github.com/aex-a | exabyte-extra.net     
**Cloud Operations & Observability Specialist** **|** **Infrastructure as Code (GCP/AWS)** **|**  **RHCSA**

RHCSA-certified Cloud Operations specialist focused on enterprise observability and infrastructure automation. I specialize in reducing MTTR by translating static monitoring into targeted alerts and directly driving incident response. Experienced in managing Linux systems and implementing Infrastructure as Code (OpenTofu, Ansible, GCP) alongside monitoring stacks (Dynatrace, Prometheus) to limit manual toil, map infrastructure dependencies, and reduce configuration drift.

### SKILLS
* **Linux & Systems Administration:** Red Hat - RHEL, openSUSE, Fedora, SELinux, systemd, LVM, LUKS, dnf/zypper
* **Infrastructure as Code & Automation:** OpenTofu, Terraform - GCS Backend, Ansible, Bash - Proficient, Git, GitHub Actions
* **Cloud & Networking:** AWS - EC2, ALB, CloudFront, WAF, IAM/SCP, GCP - VPC, Compute Engine, OpenWRT, firewalld, Wireguard, TCP/IP, DNS, Lynis Auditing
* **Containerization, Observability & Operations:** Kubernetes (K3s), Helm, Prometheus, Grafana, Podman, Python - Environment Management, venv, pipx, API Validation - curl, Incident Response, Root Cause Analysis - RCA, Dynatrace

### WORK EXPERIENCE

**Allegiant Travel Company**
*NOC Technician II* | MARCH 2024 - PRESENT
* **Incident Management:** Facilitated 11+ high-severity bridge calls over a 60-day period to mitigate enterprise-critical outages. Managed incident lifecycles in Jira Service Management, contributed to blameless RCAs to assist in improving MTTD and resiliency.
* **Observability Optimization:** Migrated actionable metrics from static dashboards to targeted Dynatrace alerts, reducing manual "eyes-on-glass" monitoring. Worked directly with SRE leadership to debug platform quota constraints by mapping and purging legacy configurations.
* **Cloud IAM Troubleshooting:** Troubleshot cloud access failures during a physical-to-cloud migration. Used the AWS IAM Policy Simulator to isolate permission boundaries, identify Service Control Policy (SCP) blocks, and route precise access requirements for IAM remediation.
* **Application Triage & Escalation:** Analyzed network routing using browser DevTools to triage downstream application failures. Isolated 500 Internal Server Errors to specific backend services, providing SRE teams with exact escalation coordinates to decrease MTTD.
* **IT Spotlight Awards:** Received two awards from enterprise leadership (Sep/Oct 2025) for developing proactive monitoring cadences that mitigated cascading infrastructure failures and improved alert validation.

**Palms Casino Resort**
*IT Technician* | JUNE 2023 - FEBRUARY 2024
* **VDI & Hardware Deployment:** Provisioned and managed production Virtual Desktop Infrastructure (VDI) environments via VMware Horizon to support enterprise operations.
* **Security Compliance:** Enforced and audited strict PCI compliance standards across managed infrastructure to secure casino network environments.
* **Incident Response:** Initiated vendor coordination and executed incident response protocols to address revenue-impacting service outages during on-call rotation, restoring critical services and returning infrastructure to baseline.

### INFRASTRUCTURE PORTFOLIO

**Bare-Metal Edge Architecture & Hypervisor Provisioning - libvirt-iac-relay** | *github.com/aex-a/libvirt-iac-relay*
* **Infrastructure as Code (IaC):** Implemented a declarative KVM/QEMU provisioning pipeline using OpenTofu and the `dmacvicar/libvirt` provider to manage Linux VMs across host network bridges and LVM block storage.
* **SRE Methodologies:** Authored Architecture Decision Records (ADRs) to document the migration from virtualized edge routing to a bare-metal OpenWrt appliance. This pivot restricted the failure domain and enforced a stricter separation of state.

**Kubernetes Observability Pipeline - k3s-observatory** | *github.com/aex-a/k3s-observatory*
* **Bootstrapping & Telemetry:** Bootstrapped an ephemeral, single-node K3s cluster on GCP using OpenTofu `metadata_startup_scripts`. Deployed the `kube-prometheus-stack` via Helm to execute synthetic Blackbox probes against external portfolio endpoints.
* **Architecture & Documentation:** Authored ADRs documenting zero-trust SSH port-forwarding constraints, MVP technical debt, and the roadmap for Traefik Ingress integration and declarative configuration management.

**Cloud Infrastructure Pipeline - ot-trek** | *github.com/aex-a/ot-trek*
* **Cloud Architecture:** Configured a modular cloud infrastructure on GCP using OpenTofu and Terraform. Enforced least-privilege VPC rules and minimized manual host provisioning through `metadata_startup_scripts`.
* **CI/CD Integration:** Implemented GitHub Actions to run automated `fmt` and `validate` checks on pull requests, establishing a baseline code quality to prevent configuration drift.

**Linux Automation & Configuration - tux-utils** | *github.com/aex-a/tux-utils*
* **Systems Engineering:** Deployed idempotent Ansible playbooks to standardize Linux server configurations and monitoring capabilities.
* **Configuration Management:** Engineered custom systemd-managed Bash daemons with graceful SIGINT/SIGTERM signal trapping for continuous queue analysis. Decoupled application logic from system variables via `/etc/` dynamic configurations using Jinja2 templating.

### CERTIFICATIONS & EDUCATION

* **Red Hat Certified System Administrator - RHCSA** | ID: 250-187-358 (Active until Dec 2028)
* **CompTIA Network+** | ID: ec18901b-3cf0-4c91-8756-7b3aba11af21 (Active until Oct 2027)
* **Associate of Arts - 3.71 GPA** | Lake Superior College (Graduated May 2018)
