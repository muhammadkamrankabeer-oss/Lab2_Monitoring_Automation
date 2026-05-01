# 🚀 Automated Infrastructure Observability

This project automates the deployment of a complete monitoring and alerting stack on a Linux host (tested on Xubuntu 24.04). Using **Ansible** and **Docker**, it transforms raw hardware data into actionable insights and proactive alerts.

## 🏗️ Architecture
- **Node Exporter**: Collects hardware metrics (CPU, RAM, Disk, Network).
- **Prometheus**: Time-series database that scrapes and stores metrics.
- **Alertmanager**: Handles alerts based on custom thresholds (e.g., High CPU usage).
- **Grafana**: Provides professional visualization (Dashboard ID: 1860).

## 🛠️ Tech Stack
- **Automation**: Ansible (Idempotent Playbooks)
- **Containerization**: Docker & Docker Compose
- **OS**: Xubuntu (Dell Latitude E7440)
- **Language**: YAML / Jinja2

## 🚀 One-Click Deployment
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/Lab2_Monitoring_Automation.git](https://github.com/YOUR_USERNAME/Lab2_Monitoring_Automation.git)
   cd Lab2_Monitoring_Automation
