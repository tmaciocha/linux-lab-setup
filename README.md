# Linux Lab Setup

This repository contains scripts, notes, and configuration files for my Linux Learning Environment and automation experiments

---

## Current Status
- **Main Workstation**: Kubuntu 24.04
- **Intalled Tools**:
  - Docker - container runtime
  - kind - Kubernetes in Docker
  - kubectl - Kubernetes CLI
  - Ansible - automation and provisioning
  - Git - version control
- **Current Use**:
  

---

## Planned Work
- Running local Kubernetes clusters for testing
- Create shell scripts to automate setup of Linux environment
- Install and configure Ansible for lab provisioning
- Simulate a small network of Linux VMs for advanced networking practice
- Automate package installation and configuration with Ansible
- Manage Git repositories for lab projects
- Monitor system resources during container workloads

### Extended Learning & Experiments
- **Log management & analisis**
  - Configure central logging with rsyslog or journalctl
  - Test Loki or ELK Stack (Elasticsearch, Logstash, Kibana)
- **Backup automation**
  - Write scripts for backup and restore of configuration and data
- **Security hardening**
  - Set up firewall rules
  - Automate SSH key creation and distribution
- **User & permision management**
  - Automate user/group creation
  - Configure sudoers securely
- **Networking lab**
  - Test DNS, DHCP, VLAN in virtualized environments
  - Simulate network outages and service recovery
- **Service deployment practice**
  - Deploy nginx/apache web server and configure reverse proxy
  - Test TLS/SSL certificates (e.g. Let's Encrypt in lab environment)
- **Performance testing**
  - Use `ab`, `wrk`, `iperf` for app and netowkr performance tests
- **Container orchestration experiments**
  - Create and test Helm charts
  - Experiment with K3s as a lightweight Kubernetes alternative
- 