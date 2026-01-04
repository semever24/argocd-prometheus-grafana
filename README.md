# Application Monitoring with Prometheus & Grafana on Kubernetes

This repository demonstrates a complete application monitoring setup on Kubernetes using Prometheus and Grafana. The solution provides real-time visibility into application health, performance, and resource utilization.

---

## 🚀 Architecture Overview

- Kubernetes cluster running on Amazon EKS
- Monitoring stack deployed using kube-prometheus-stack (Helm)
- Prometheus scrapes application and cluster metrics
- Grafana visualizes metrics using default and custom dashboards
- GitOps-based deployment using Argo CD

---

## 🛠 Tech Stack

- Amazon EKS
- Kubernetes
- Prometheus
- Grafana
- kube-prometheus-stack
- Helm
- Argo CD

---

## 📊 Key Features

- Application metrics scraping using Prometheus
- Preconfigured Grafana dashboards for application health
- Monitoring of CPU, memory, pod availability, and request latency
- Namespace-based monitoring (monitoring namespace)
- Scalable and production-ready observability setup

---

## 📂 Components Deployed

- Prometheus Server
- Alertmanager
- Grafana
- Node Exporter
- kube-state-metrics
- Application Service & Metrics Endpoint

---

## 🔍 Monitoring Capabilities

- Application health status
- Pod and container resource usage
- Kubernetes cluster state visibility
- Faster incident detection and troubleshooting
- Improved reliability and operational insight

---

## 📌 Use Cases

- Production Kubernetes monitoring
- SRE and DevOps observability practices
- Performance tuning and capacity planning
- Proactive incident detection

---

## 📖 Getting Started

1. Provision an EKS cluster
2. Install kube-prometheus-stack using Helm
3. Deploy application exposing metrics endpoint
4. Access Grafana dashboards to monitor application health

---

## 📎 Notes

- All monitoring resources are deployed in the `monitoring` namespace
- Default Grafana dashboards are enabled via kube-prometheus-stack
- The setup follows Kubernetes and cloud-native best practices

---

## 🤝 Contributions

Contributions and improvements are welcome. Feel free to raise issues or submit pull requests.

---

## 📬 Contact

For queries or collaboration:  
📧 senthilkumarrajan1209@gmail.com
