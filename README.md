# 🚀 Kubernetes Platform Lab

![Kubernetes](https://img.shields.io/badge/Kubernetes-Platform-blue)
![DevOps](https://img.shields.io/badge/DevOps-Projects-orange)
![Cloud Native](https://img.shields.io/badge/Cloud%20Native-CNCF-brightgreen)
![Docker](https://img.shields.io/badge/Docker-Containers-blue)
![GitOps](https://img.shields.io/badge/GitOps-ArgoCD-red)
![License](https://img.shields.io/badge/License-MIT-green)

A **production-focused Kubernetes learning repository** containing **150 hands-on projects** designed to take you from **Kubernetes beginner → platform engineer**.

This lab explores **real-world cloud-native infrastructure patterns**, including deployments, networking, observability, CI/CD, GitOps, service mesh, and multi-cluster Kubernetes architectures.

---

# 📚 Learning Roadmap

```text
Beginner → Intermediate → Advanced → Expert → Pro
```

| Phase        | Days    | Focus                               |
| ------------ | ------- | ----------------------------------- |
| Beginner     | 1–30    | Kubernetes fundamentals             |
| Intermediate | 31–60   | Networking & storage                |
| Advanced     | 61–90   | Observability & security            |
| Expert       | 91–120  | CI/CD, GitOps, platform engineering |
| Pro          | 121–150 | Production distributed systems      |

---

# 📊 Project Progress

### Beginner Phase

| Day | Project                       |
| --- | ----------------------------- |
| 1   | Run first containerized app   |
| 2   | Multi-pod scalable deployment |
| 3   | Kubernetes YAML deployment    |
| 4   | ConfigMaps configuration      |
| 5   | Secrets management            |
| 6   | Resource limits & requests    |
| 7   | Liveness & readiness probes   |
| 8   | Labels and selectors          |
| 9   | Namespaces isolation          |
| 10  | Rolling updates               |

More projects coming daily…

---

# 🧠 Topics Covered

### Core Kubernetes

* Pods
* Deployments
* ReplicaSets
* Services
* ConfigMaps
* Secrets
* Namespaces

### Networking

* ClusterIP
* NodePort
* LoadBalancer
* Ingress
* Network Policies

### Storage

* Persistent Volumes
* Persistent Volume Claims
* StatefulSets
* Storage Classes

### DevOps & Automation

* Helm
* GitOps
* CI/CD pipelines
* Kubernetes operators

### Observability

* Prometheus
* Grafana
* Loki
* OpenTelemetry
* Jaeger

### Security

* RBAC
* OPA
* Kyverno
* Image scanning

### Platform Engineering

* Internal developer platforms
* Multi-cluster Kubernetes
* Service mesh
* Serverless platforms

---

# 📂 Repository Structure

```text
kubernetes-platform-lab
│
├── learning-roadmap
│   ├── kubernetes-learning-pyramid.md
│   └── 150-day-roadmap.md
│
├── beginner-projects
├── intermediate-projects
├── advanced-projects
├── expert-projects
├── pro-projects
│
├── helm-charts
├── gitops
├── observability-stack
├── scripts
└── diagrams
```

---

# ⚙️ Prerequisites

Before running the projects install:

### Kubernetes CLI

```
kubectl
```

### Local Kubernetes Cluster

```
Minikube
or
Docker Desktop Kubernetes
```

### Container Runtime

```
Docker
```

Verify installation:

```
kubectl get nodes
```

---

# 🚀 Running a Project

Example:

```
cd beginner-projects/day-03-yaml-deployment
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
```

Check cluster resources:

```
kubectl get pods
kubectl get svc
```

---

# 🧩 Kubernetes Architecture

```
User
 │
 ▼
Service (NodePort / Ingress)
 │
 ▼
Deployment
 │
 ▼
Pods
 │
 ▼
Containers
```

Kubernetes ensures:

* automatic scheduling
* self-healing
* load balancing
* horizontal scaling

---

# 🎯 Goals of This Repository

* Learn Kubernetes through **hands-on projects**
* Build **production-grade DevOps knowledge**
* Document real-world infrastructure patterns
* Create a **strong Kubernetes engineering portfolio**

---

# 📸 Screenshots

Each project includes screenshots of running applications and cluster resources.

Example:

```
screenshots/nginx-running.png
```

---

# ⭐ Support the Project

If you find this repository useful:

* ⭐ Star the repo
* 🍴 Fork it
* 📢 Share with others learning Kubernetes

---

# 👨‍💻 Author

Built as part of a **Kubernetes deep-dive learning journey** focused on DevOps, cloud-native infrastructure, and platform engineering.
