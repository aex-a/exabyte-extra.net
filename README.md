# Alex Ardent Lucero 
alex.lu.ce9@proton.me | exabyte-extra.net  
linkedin.com/in/alex-ardent-lucero | github.com/aex-a   
**Cloud Operations & Observability Specialist** **|** **Infrastructure as Code (GCP/AWS)** **|**  **RHCSA**  

RHCSA-certified Cloud Operations and Incident Management professional specializing in enterprise observability and infrastructure automation. Proven track record of reducing MTTR by bridging the gap between proactive monitoring (Dynatrace, Prometheus) and incident orchestration. Passionate about Linux systems, combining enterprise incident management expertise with hands-on Infrastructure as Code (IaC) development using OpenTofu, Ansible, and GCP.

### SKILLS
* **Linux & Systems Administration:** Red Hat - RHEL, openSUSE, Fedora, SELinux, systemd, LVM, LUKS, dnf/zypper
* **Infrastructure as Code & Automation:** OpenTofu, Terraform - GCS Backend, Ansible, Bash - Proficient, Git, GitHub Actions
* **Cloud & Networking:** AWS - EC2, ALB, CloudFront, WAF, IAM/SCP, GCP - VPC, Compute Engine, OpenWRT, firewalld, Wireguard, TCP/IP, DNS, Lynis Auditing
* **Containerization, Observability & Operations:** Kubernetes (K3s), Helm, Prometheus, Grafana, Podman, Python - Environment Management, venv, pipx, API Validation - curl, Incident Response, Root Cause Analysis - RCA, Dynatrace

### WORK EXPERIENCE

**Allegiant Travel Company**
*NOC Technician II* | MARCH 2024 - PRESENT
* **Incident Management:** Reduced Mean Time To Resolution - MTTR for enterprise-critical outages by independently orchestrating 11+ high-severity bridge calls within a 60-day period, utilizing Jira Service Management to execute blameless Root Cause Analyses - RCAs and drive systemic infrastructure improvements.
* **Observability Optimization:** Eliminated "eyes-on-glass" operational toil by migrating actionable metrics from proposed static dashboards into targeted Dynatrace alerts, collaborating directly with SRE leadership to debug platform quota constraints by identifying and purging legacy inactive configurations.
* **Cloud IAM Troubleshooting:** Accelerated cloud access resolution during a physical-to-cloud migration by utilizing the AWS IAM Policy Simulator to isolate permission boundaries, successfully identifying Service Control Policy - SCP blocks and routing precise access requirements for IAM remediation.
* **Application Triage & Escalation:** Decreased Mean Time To Detection - MTTD for downstream application failures by utilizing browser DevTools to analyze network payloads, isolating 500 Internal Server Errors to backend services and providing the SRE team with exact escalation coordinates.
* **IT Spotlight Awards:** Recognized twice by enterprise leadership (Sep/Oct 2025) for developing proactive monitoring cadences that mitigated cascading infrastructure failures and for driving operational alert validation.

**Palms Casino Resort**
*IT Technician* | JUNE 2023 - FEBRUARY 2024
* **VDI & Hardware Deployment:** Maintained high availability and seamless endpoint deployment across the enterprise by provisioning and managing production Virtual Desktop Infrastructure - VDI environments via VMware Horizon.
* **Security Compliance:** Secured critical casino network environments by enforcing and auditing strict PCI compliance standards across all managed infrastructure.
* **Incident Response:** Ensured 24/7 uptime and minimal operational disruption by directing vendor coordination and incident response protocols during high-priority system outages.

### INFRASTRUCTURE PORTFOLIO 

**Kubernetes Observability Pipeline - k3s-observatory** | *github.com/aex-a/k3s-observatory* 
* **Orchestration & Telemetry:** Bootstrapped an ephemeral, single-node K3s cluster on GCP via OpenTofu `metadata_startup_scripts`, deploying the `kube-prometheus-stack` via Helm to execute synthetic Blackbox probes against external portfolio endpoints. 
* **Architecture & Documentation:** Authored Architecture Decision Records (ADRs) to formally document zero-trust SSH port-forwarding constraints, MVP technical debt, and the roadmap for Traefik Ingress and declarative configuration management. 

**Cloud Infrastructure Pipeline - ot-trek** | *github.com/aex-a/ot-trek*
* **Cloud Architecture:** Architected a highly secure, modular cloud infrastructure on GCP, achieving zero-drift configuration deployment and enforcing least-privilege VPC compliance, by developing a robust Infrastructure as Code - IaC pipeline utilizing OpenTofu/Terraform and `metadata_startup_scripts`.
* **CI/CD Integration:** Implemented GitHub Actions for automated `fmt` and `validate` checks on pull requests to enforce code quality and prevent configuration drift.

**Linux Automation & Configuration - tux-utils** | *github.com/aex-a/tux-utils*
* **Systems Engineering:** Enhanced Linux server network reliability and real-time monitoring capabilities through the deployment of idempotent Ansible playbooks, engineering custom systemd-managed Bash daemons with graceful SIGINT/SIGTERM signal trapping for continuous queue analysis.
* **Configuration Management:** Successfully decoupled application logic from system variables via `/etc/` dynamic configurations using Jinja2 templating.


### CERTIFICATIONS & EDUCATION

* **Red Hat Certified System Administrator - RHCSA** | ID: 250-187-358 (Active until Dec 2028)
* **CompTIA Network+** | ID: ec18901b-3cf0-4c91-8756-7b3aba11af21 (Active until Oct 2027)
* **Associate of Arts - 3.71 GPA** | Lake Superior College (Graduated May 2018)

