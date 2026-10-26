<!-- ============ HEADER ============ -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF6B00,50:FF9F1C,100:1E90FF&height=260&section=header&text=Utkarsh%20Ahirrao&fontSize=64&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Junior%20DevOps%20Engineer%20%7C%20Azure%20Cloud%20Engineer&descSize=22&descAlignY=60" width="100%"/>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=24&pause=1200&color=FF6B00&center=true&vCenter=true&width=800&height=50&lines=Hi%2C+I+am+UT+-+nice+to+meet+you;Junior+DevOps+Engineer+%40+Shell+Square+Solutions;Azure+%7C+Terraform+%7C+CI%2FCD+%7C+Kubernetes;Prometheus+%7C+Grafana+%7C+Monitoring+%26+Alerts;Believe+it!+Dattebayo!" alt="Typing animation" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure%20DevOps-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Based%20in-Pune%2C%20India-FF6B00?style=flat-square&logo=googlemaps&logoColor=white" />
  <img src="https://img.shields.io/badge/Hometown-Nashik-FF9F1C?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Open%20to%20DevOps%20%26%20Azure%20Cloud%20roles-1E90FF?style=flat-square" />
</p>

---

## 🍥 Ninja Info Card

> *"I'm not gonna run away, I never go back on my word. That's my nindo, my ninja way!"*
> I turn manual work into automated pipelines, and I like building cloud setups that stay clean, secure and easy to monitor.

| | |
|---|---|
| 🥷 **Role** | Junior DevOps Engineer at **Shell Square Solutions** (since June 2026) |
| ☁️ **Focus** | Azure infrastructure, Terraform, CI/CD with Azure Pipelines, RBAC, Azure Monitor |
| 📊 **Monitoring** | Prometheus + Grafana dashboards and alerts (CPU, disk, memory, node down, service alerts) |
| ☸️ **Containers** | Kubernetes / AKS cluster configuration, Docker |
| 🎓 **Education** | BE in Electronics and Telecommunication (Cyber Security Honors), Diploma in IT |
| 📍 **Location** | Pune, India (originally from Nashik) |

---

## 🌀 Jutsu Arsenal (Skills)

<p align="center">
  <img src="https://skillicons.dev/icons?i=azure,terraform,kubernetes,docker,git,github,githubactions,linux,bash,python,grafana,prometheus,nginx,cloudflare&perline=7" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Azure%20DevOps-Pipelines-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white" />
  <img src="https://img.shields.io/badge/YAML-Multi--stage%20Pipelines-FF6B00?style=for-the-badge&logo=yaml&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure-RBAC-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure-Monitor-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
</p>

| 🔥 Category | ⚡ What I use |
|---|---|
| **Cloud (Azure)** | Resource Groups, VNet, NSG, VM, Blob Storage, Load Balancer, Application Gateway, Bastion, AKS, RBAC, Azure Monitor |
| **Infrastructure as Code** | Terraform: parent/child modules (qa / dev / prod), remote state on Azure Storage backend, variables, outputs |
| **CI/CD** | Azure Pipelines multi-stage YAML, self-hosted agents, GitHub Actions, feature-branch + PR approval workflow, branch policies |
| **Security Scanning** | tfsec, tflint, TruffleHog, pipeline secrets for credentials |
| **Containers and Orchestration** | Docker, Kubernetes (master/worker nodes, pods, services, virtual services, Ingress gateway) |
| **Monitoring** | Prometheus, Grafana, alerting rules for infra health |
| **Scripting and OS** | Bash, Python, Linux, Nginx |
| **Version Control** | Git, GitHub, Azure Repos |

---

## 🏯 Mission Log (Experience)

| 🗓️ Period | 🎖️ Rank | 📜 What I did |
|---|---|---|
| **June 2026 - Present** | **Junior DevOps Engineer**, Shell Square Solutions | Set up Prometheus and Grafana monitoring with alerts for CPU, disk, memory and node down, and working on service alerts. Set up self-hosted agents for CI/CD on QA and Dev. Supporting Kubernetes / AKS cluster configuration and writing multi-stage YAML pipelines. |
| **April 2025 - March 2026** | **Azure Cloud Intern**, DevOps Insiders | Worked hands-on with the Azure portal (RG, VNet, VM, Blob), Load Balancer, Application Gateway and Bastion. Learned and built Terraform with NSG rules, storage redundancy, parent/child modules, remote state, and scanning with tfsec, tflint and TruffleHog. Used GitHub Actions with feature-branch and PR workflow. |

---

## ⚔️ Secret Techniques (Projects)

### 🎬 Netflix Demo Website: Full IaC + CI/CD Deployment
Deployed a demo Netflix-style website on Azure entirely through code.
- Terraform **parent/child modules** for the whole infrastructure
- **Azure DevOps multi-stage pipeline** with **tfsec** and **tflint** stages
- VM credentials stored as **pipeline secrets**
- **Branch policy** with PR and reviewer approval before anything gets deployed
- Traffic served through **Azure Application Gateway**, with a **Cloudflare A record** pointing to its public IP

`Terraform` `Azure DevOps` `Application Gateway` `tfsec` `tflint` `Cloudflare`

### 🚀 Azure DevOps + Terraform: Feature Branch to Live Website
- Pipeline triggered from a feature branch, then PR approval and merge
- Automatically created the VM, configured **Nginx**, and hosted a demo website

`Azure Pipelines` `Terraform` `Nginx` `Git`

### 🧱 Modular Terraform Project for Azure
- Reusable modules for resource groups, storage, networking and compute
- **Remote backend** state management on Azure Storage

`Terraform` `Azure` `Remote State`

### 🔄 Multi-Stage Azure Pipelines for Terraform
- Optional and independent **tfsec** and **tflint** stages controlled by boolean parameters
- Followed by install, init, validate, plan and apply stages
- Runs on a self-hosted agent pool

`YAML` `Azure Pipelines` `Terraform` `tfsec` `tflint`

### 📊 Monitoring Stack with Prometheus and Grafana
- Alerts for CPU, disk, memory and node down
- Service alerts for application health

`Prometheus` `Grafana` `Alerting`

---

## 🧭 Ninja Path (Currently Training)

- 🔥 Going deeper into **Kubernetes / AKS**
- 🔥 Advanced **Terraform** patterns
- 🔥 Better **observability** with Prometheus and Grafana

---

## 🍜 Ichiraku Ramen Fun Facts

- 🍥 Pipelines make me happy, manual deployments make me nervous
- 🍥 If a task is done twice, I try to automate it the third time
- 🍥 Favourite mantra: *"Hard work is worthless for those that don't believe in themselves."*

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1500&color=1E90FF&center=true&vCenter=true&width=700&lines=Open+to+Junior+DevOps+and+Azure+Cloud+roles;Let+us+build+something+great+together" alt="Closing animation" />
</p>

<!-- ============ FOOTER ============ -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1E90FF,50:FF9F1C,100:FF6B00&height=140&section=footer" width="100%"/>
