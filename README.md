<div align="center">
  <h1> Ayoub Haj Abdallah. /h1>
  <h2>Architecting backend systems that scale, secure, and deploy themselves.</h2>
  <p>Computer Science (B.Sc.) at TU Dortmund • Focused on Server-Side Engineering, CI/CD & Industrial Monitoring</p>
</div>

### ⚙️ How I Build & Ship
Anyone can write code that works on `localhost`. I focus on building distributed, containerized systems that run reliably on real production infrastructure.

* **The Engine:** Java (Spring Boot), Python (FastAPI), Go, TypeScript
* **The Data:** PostgreSQL, structured relational modeling (JPA, SQLAlchemy)
* **The Pipeline:** Docker containerization, automated testing, GitHub Actions CI/CD
* **The Infrastructure:** AWS (EC2), Nginx, Linux (systemd), Bash

---

### 🏗️ What I'm Building

#### 🏭 [Forge Watch](https://github.com/ayoubhajabdallah/forgewatch) | *Industrial monitoring & synthetic data generation*
An industrial monitoring platform for tracking machine data and managing incidents.
* **The Clever Part:** Instead of relying on static test data, I built a custom **Go-based sensor simulator** that generates live, synthetic telemetry data and pushes it to the Spring Boot REST API for real-time threshold evaluation.
* **The Architecture:** Java 21, Spring Boot, Go, Angular, PostgreSQL, GitHub Actions.

#### ☁️ [AWS EC2 CI/CD Deployment](https://github.com/ayoubhajabdallah/aws-ec2-nginx-project) | *Bare-metal cloud infrastructure*
A fully automated continuous deployment pipeline running on Amazon EC2.
* **The Clever Part:** I didn't just use a simple cloud platform (like Vercel/Heroku). I provisioned an AWS EC2 instance, secured an Nginx web server, and configured a **Self-Hosted GitHub Runner as a Linux systemd service** to execute raw Bash deployment scripts automatically.
* **The Architecture:** AWS EC2, Nginx, Linux/Bash, GitHub Actions.

#### 🛡️ [Security Log Analyzer](https://github.com/ayoubhajabdallah/security-log-analyzer) | *Detecting anomalies before they become breaches*
A real-time authentication log analyzer to flag suspicious network activity.
* **The Clever Part:** Integrated an **Isolation Forest ML algorithm** (scikit-learn) for dynamic anomaly detection instead of relying purely on static regex rules.
* **The Architecture:** FastAPI backend, fully containerized with Docker Compose, PostgreSQL.

#### 🏢 [IT Service Desk API](https://github.com/ayoubhajabdallah/it-servicedesk) & [FlowOps](https://github.com/ayoubhajabdallah/Flow-Manager) | *Enterprise workflow management*
Two robust backends handling IT support ticketing, automated task classification, and webhook integrations.
* **The Clever Part:** Engineered strict JWT-based authentication, role-based authorization (Spring Security), and an event-history lifecycle. Both architectures mirror real enterprise backend patterns.
* **The Architecture:** Java (Spring Boot), Python (FastAPI), PostgreSQL, TypeScript/React.

---

### 📊 The Philosophy
Code should be strictly typed, infrastructure should be automated, and secrets should never touch the repository.

<div align="center">
  <a href="mailto:ayhajabdallah@gmail.com">Email</a> • <a href="https://linkedin.com/in/ayoubhajabdallah">LinkedIn</a>
</div>
