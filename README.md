# k8s-integrative

A Kubernetes project integrating various services, Helm charts, and persistent storage solutions.

## 📌 Features
- Deploys multiple services using Kubernetes manifests.
- Uses Helm for package management.
- Implements Persistent Volume Claims (PVC) for shared storage.
- Integrates Grafana for monitoring.
- Includes Ingress rules for external access.

## 🚀 Deployment Steps

### 1️⃣ Prerequisites
Ensure you have the following installed:
- **Kubernetes (kubectl) + Cluster**
- **Helm** (v3 recommended)
- **Git**

### 2️⃣ Clone the Repository
```sh
git clone https://github.com/TomerLevy743/k8s-integrative.git
cd k8s-integrative
```

### 3️⃣ Deploy Using Helm
```sh
helm install my-app ./helm-chart/
```

### 4️⃣ Verify Deployment
```sh
kubectl get pods -n <your-namespace>
kubectl get svc -n <your-namespace>
```

---
**Maintainer:** [Tomer Levy](https://github.com/TomerLevy743)

