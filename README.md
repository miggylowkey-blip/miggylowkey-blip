<div align="center">
  <h1>John Miguel Sarmiento</h1>
  <h3>Backend & Cloud Solution Developer</h3>
  <p><i>Building secure, high-concurrency systems with a focus on infrastructure reliability.</i></p>
  
  <p align="center">
    <a href="mailto:miggylowkey@gmail.com">
      <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <a href="https://www.linkedin.com/in/miggy-zxc-32028139a/">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
  </p>
</div>

---

## About Me

I am a systems and infrastructure developer based in the Philippines. I specialize in bridging the gap between raw cloud compute and high-performance backend services. My approach centers on building reproducible environments, ensuring secure deployments, and maintaining code that is clean, concurrent, and highly observable.

Currently, I am diving deep into **AWS Identity & Access Management (IAM)** and network traffic monitoring to sharpen my focus on cloud security architecture.

---

## Developer Workflow: AWS Execution

* **Infrastructure Design:** I map out AWS resources (VPC, Subnets, Security Groups) to ensure network isolation before configuring compute.
* **Immutable Provisioning:** I use Terraform to define environments as code, ensuring development and production parity to eliminate "works on my machine" issues.
* **Pipeline Integrity:** My GitHub Actions pipelines enforce strict linting and automated security scans on Terraform HCL and Dockerfiles before any infrastructure is provisioned.
* **Containerized Backends:** I package Java and Go services into minimal Docker images, optimizing for fast cold starts and low memory overhead on AWS ECS/Fargate.
* **Observability & Logs:** I leverage structured logging and CloudWatch to ensure production issues are traceable back to specific commits or deployment versions.

---

## System Architecture & Tools

**Cloud & Orchestration**<br>
[![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/)
[![Terraform](https://img.shields.io/badge/terraform-%23623CE4.svg?style=for-the-badge&logo=terraform&logoColor=white)](https://www.terraform.io/)
[![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)](https://kubernetes.io/)

**Databases & Event Streaming**<br>
[![PostgreSQL](https://img.shields.io/badge/postgresql-4169e1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![DynamoDB](https://img.shields.io/badge/Amazon%20DynamoDB-4053D6?style=for-the-badge&logo=Amazon%20DynamoDB&logoColor=white)](https://aws.amazon.com/dynamodb/)
[![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-000?style=for-the-badge&logo=apachekafka)](https://kafka.apache.org/)
[![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)](https://redis.io/)

**Backend, Scripting & CI/CD**<br>
[![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)](https://go.dev/)
[![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.oracle.com/java/)
[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org/)
[![Mojo](https://img.shields.io/badge/Mojo-%23FF4500.svg?style=for-the-badge&logo=modular&logoColor=white)](https://www.modular.com/mojo)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://www.linux.org/)
[![Bash](https://img.shields.io/badge/bash-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)](https://www.gnu.org/software/bash/)
[![GitHub Actions](https://img.shields.io/badge/github%20actions-%232088FF.svg?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com/features/actions)

**Monitoring & Observability**<br>
[![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white)](https://prometheus.io/)

---

## Production Work

### Multi-Module Cloud Infrastructure Architecture
> **Tech Stack:** Terraform, AWS (VPC, EC2, ECR), GitHub Actions
* **Architecture:** A production-grade, multi-file IaC setup that provisions an isolated virtual network, secure firewalls, and scalable compute resources.
* **Automation:** Integrated with a live GitHub Actions CI/CD pipeline that enforces strict syntax validations and executes dry-run state plans on every commit.
* [**[ Cloud Infrastracture ]**](https://github.com/miggylowkey-blip/cloud-lambda-driven-infrastracture)

### Containerized Go API Gateway & Cloud Infrastructure Engine
> **Tech Stack:** Go (Golang), HashiCorp Terraform (HCL), Kubernetes, Docker, Trivy, Kubesec, GitHub Actions
* **Backend Core:** Engineered a production-grade Go REST API using standard project layouts (`cmd/api`, `internal`), managing structured micro-routing and automated SQL database migrations.
* **Infrastructure as Code (IaC):** Designed a modular Terraform architecture to safely provision automated environments, isolating compute resources and secure private container networks.
* **Orchestration & DevSecOps:** Packaged the service into lightweight Docker containers orchestrated via Kubernetes manifests. Implemented shift-left security scanning utilizing `Trivy` for filesystem audits and `Kubesec` for static analysis of Kubernetes security profiles.
* [**[ API ]**](https://github.com/miggylowkey-blip/API-MANAGEMENT)

---

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=miggylowkey-blip&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="GitHub Stats" />
</div>
