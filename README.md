# 🚀 Lab 2: Automated Infrastructure Monitoring
Part of my **40-Day Technical Lab Challenge (April 2026)**.

## 📋 Overview
An automated monitoring stack deployed on a **Dell Latitude E7440** running **Xubuntu**. This project uses **Ansible** to orchestrate a containerized environment for real-time hardware observability.

## 🛠️ The Stack
- **Ansible**: Infrastructure as Code (IaC) for one-click deployment.
- **Docker**: Containerization of all monitoring services.
- **Prometheus**: Time-series database for metric collection.
- **Node Exporter**: Hardware sensor for CPU, RAM, and Disk metrics.
- **Grafana**: Professional visualization using Dashboard ID 1860.

## 📸 Proof of Concept
![Grafana Dashboard](link-to-your-screenshot-here)
*Live monitoring of CPU Load and Memory usage on Xubuntu 24.04.*

## 🚀 How to Run
1. Clone this repo.
2. Ensure Docker and Ansible are installed.
3. Run: `ansible-playbook -i inventory.ini deploy_monitoring.yml -K`
