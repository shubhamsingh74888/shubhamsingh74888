---
# Shubham Singh — DevOps & Cloud Engineer

🎓 MCA 2026 · Garden City University, Bangalore · CGPA 8.5  
📍 Bangalore, India · Available immediately for DevOps / Cloud / SRE roles  
📧 shubhamsingh74888@gmail.com · [LinkedIn](https://linkedin.com/in/shubham-singh-aa858b35a) 
https://portfolio-webpage.shubhamsingh74888.workers.dev/

---

## 🛠️ Tech Stack

| Area | Tools |
|---|---|
| **Cloud** | AWS (EKS, EC2, S3, VPC, IAM, Route 53, CloudWatch, Lambda, DynamoDB) |
| **IaC** | Terraform (modular), Packer |
| **CI/CD** | Jenkins (Shared Library), ArgoCD, GitOps |
| **Containers** | Docker, Kubernetes (EKS, kubeadm, Helm) |
| **Security** | SonarQube, Trivy, OWASP |
| **Observability** | Prometheus, Grafana, CloudWatch |
| **Scripting** | Bash, Shell, Groovy |
| **Databases** | MySQL, MongoDB |

---

## 🚀 Featured Projects

### 🌍 [Wanderlust — Production DevSecOps on AWS EKS](https://github.com/shubhamsingh74888/Wanderlust-Mega-Project)
> MERN travel blog deployed on AWS EKS with a full DevSecOps pipeline across 4 repos

- **4-repo GitOps architecture** — app code · K8s manifests · Terraform infra · Jenkins shared library  
- **10-stage Jenkins pipeline** — build → SAST (SonarQube) → image scan (Trivy) → OWASP → push → deploy → verify  
- **41 AWS resources** provisioned via Terraform: EKS 1.34 · VPC · EC2 · EBS · S3 · DynamoDB · OIDC · IRSA  
- **Real incidents resolved** — MongoDB PVC stuck Pending (missing EBS CSI driver) · ArgoCD sync race condition · kubectl PATH via Packer AMI  
- **Serverless pipeline** — S3 → Lambda → DynamoDB for stock price ingestion (Terraform-managed)

→ [wanderlust-infra](https://github.com/shubhamsingh74888/wanderlust-infra) · [wanderlust-gitops](https://github.com/shubhamsingh74888/wanderlust-gitops) · [shared-lib](https://github.com/shubhamsingh74888/wanderlust-shared-lib)

---

### 🖥️ [portfolio-webpage — Personal DevOps Portfolio](https://github.com/shubhamsingh74888/portfolio-webpage)
> React/Vite + Nginx portfolio site · CI/CD pipeline · Kubernetes deployment on AWS EC2

- Deployed via Docker Compose on AWS EC2 · Migrated to Kubernetes (kubeadm, Calico CNI)  
- StatefulSets · HPA · PV/PVC · Ingress · zero-downtime rolling updates  
- Jenkins CI/CD pipelines (Jenkinsfile.ci + Jenkinsfile.cd)

---

## 📊 Activity

![Shubham's GitHub Stats](https://github-readme-stats.vercel.app/api?username=shubhamsingh74888&show_icons=true&theme=dark&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=shubhamsingh74888&layout=compact&theme=dark&hide_border=true)

---

## 📜 Certifications & Research

- 🏅 **DevOps with Multicloud** — NareshIT, Hyderabad · Dec 2025 – May 2026  
- ☁️ **AWS Cloud Practitioner CLF-C02** — In progress  
- 📄 **ICIEM-2026** — Presented *"Comparative Analysis of ML Models for Battery RUL Estimation"*

---

*304 contributions in 2026 · Building production-grade DevOps systems in public*
