<div align="center">

[![Capsule Render](https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0F0A1E,50:6D28D9,100:7C3AED&text=CHANDAN%20HOWALE&fontColor=FFFFFF&fontSize=32&section=header&fontAlignY=55&animation=fadeIn)](https://github.com/chandan-howale)

# 👨‍💻 Chandan Howale

### Java Backend Developer · Spring Boot · Microservices · AWS

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=900&color=A78BFA&center=true&vCenter=true&width=680&lines=Building+scalable+microservices+with+Java;Spring+Boot+%26+Spring+Cloud+on+AWS;Payments+%7C+REST+APIs+%7C+Redis+%7C+MySQL;MCA+%2725+%7C+Open+to+Backend+%2F+SDE+roles)](https://git.io/typing-svg)

[![MCA '25](https://img.shields.io/badge/MCA%20'25%20%E2%80%A2%20CGPA%208.52-7C3AED?style=flat-square&logo=graduationcap&logoColor=white)](#)
[![Pune, Maharashtra](https://img.shields.io/badge/Pune%2C%20Maharashtra-6D28D9?style=flat-square&logo=googlemaps&logoColor=white)](#)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chandanhowale)
[![Email](https://img.shields.io/badge/Email-7C3AED?style=for-the-badge&logo=gmail&logoColor=white)](mailto:howalechandan@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-1F2937?style=for-the-badge&logo=github&logoColor=white)](https://github.com/chandan-howale)

[![Profile Views](https://komarev.com/ghpvc/?username=chandan-howale&style=flat-square&color=6366F1&label=Profile+Views)](https://github.com/chandan-howale)
[![Followers](https://img.shields.io/github/followers/chandan-howale?style=flat-square&color=7C3AED&label=Followers)](https://github.com/chandan-howale?tab=followers)
[![Total Stars](https://img.shields.io/github/stars/chandan-howale?style=flat-square&color=8B5CF6&label=Total%20Stars)](https://github.com/chandan-howale)

</div>

---

## ⚡ About Me

Software engineer focused on **backend systems** and **distributed architecture**. I design and build secure, scalable microservices — with a specialty in **payment integrations** — using Java, Spring Boot, and AWS.

During my internship at **HulkHire Tech**, I shipped a complete **PayPal payment orchestration system**: a service registry, an orchestrator, and a provider service communicating over REST, secured with OAuth 2.0, cached through Redis, and deployed on AWS. I care about clean architecture, reliable failure handling, and code that other engineers can pick up quickly.

> **Open To:** Backend Developer · Associate SDE · Microservices Engineer · Java Developer

---

## 🛠️ Tech Stack

### Languages
<div align="center">

![My Skills](https://skillicons.dev/icons?i=java&theme=dark)

</div>

### Backend & Databases
<div align="center">

![My Skills](https://skillicons.dev/icons?i=spring,mysql,redis&theme=dark)

</div>

### Cloud, DevOps & Tooling
<div align="center">

![My Skills](https://skillicons.dev/icons?i=aws,docker,kubernetes,git,github,maven,postman,linux&theme=dark)

</div>

---

## 🎯 Core Expertise

| Domain | Proficiency | Details |
|--------|-------------|---------|
| **Microservices Architecture** | Advanced | Netflix Eureka, REST, Circuit Breaker, service state machines |
| **Payment Integration** | Advanced | PayPal REST (Create/Capture Order), OAuth 2.0, lifecycle tracking |
| **Cloud Infrastructure** | Intermediate | AWS EC2, RDS (MySQL), ElastiCache (Redis), Secrets Manager |
| **Data & Caching** | Intermediate | MySQL, Redis, Spring Data JPA / Hibernate |
| **API Design & Security** | Intermediate | Swagger / OpenAPI, OAuth 2.0, centralized custom error codes |
| **Testing & Quality** | Intermediate | JUnit, Mockito, SonarQube, code coverage |

---

## 🚀 Featured Projects

<details open>
<summary><b>💳 Payment Integration System</b> — Spring Boot Microservices on AWS</summary>

The flagship project from my internship at **HulkHire Tech** — a production-style microservices architecture that orchestrates the complete PayPal payment lifecycle, from order creation through approval to final capture.

| Attribute | Details |
|-----------|---------|
| **Stack** | Java 17 · Spring Boot 3.4.2 · Spring Cloud 2024.0.1 · Netflix Eureka · MySQL (AWS RDS) · Redis (AWS ElastiCache) |
| **Scale** | 3 independently-deployable services + centralized service registry |
| **Performance** | Redis-cached OAuth tokens → **65% lower** token-fetch latency |
| **Security** | OAuth 2.0 Client Credentials · AWS Secrets Manager · centralized error codes |
| **Impact** | 100% payment lifecycle accuracy · fault tolerance via Circuit Breaker |
| **Repository** | [payment-integration-system](https://github.com/chandan-howale/payment-integration-system) |

**Repository Map** — each service in its own repository:

| Service | Repo | Role |
|---------|------|------|
| 🧭 **Eureka Service Registry** | [eureka-service-registry](https://github.com/chandan-howale/eureka-service-registry) | Service discovery backbone (port 8761) |
| 🔀 **Payment Processing Service** | [payment-processing-service](https://github.com/chandan-howale/payment-processing-service) | Orchestrator · lifecycle state machine · MySQL persistence · circuit breaker |
| 💳 **PayPal Provider Service** | [paypal-provider-service](https://github.com/chandan-howale/paypal-provider-service) | PayPal REST integration · OAuth token management · Redis cache |

</details>

<details>
<summary><b>🐾 Pet Shop Management System</b> — Desktop Java Application</summary>

A Java desktop application that streamlines pet shop operations — managing pets, categories, customers, users, and billing. Automates record updates, customer handling, and invoice generation with a secure login and a user-friendly interface.

| Attribute | Details |
|-----------|---------|
| **Stack** | Java |
| **Scale** | Desktop application |
| **Security** | Secure role-based login |
| **Impact** | Automates inventory, customer records & invoicing |
| **Repository** | [Pet-shop-management-system-java-project](https://github.com/chandan-howale/Pet-shop-management-system-java-project) |

</details>

<details>
<summary><b>🏍️ Bike Management System</b> — Full-Stack PHP + MySQL</summary>

A full-stack bike rental management system with separate user and admin panels, backed by a MySQL database. Includes booking workflows, admin dashboard, and session-based authentication.

| Attribute | Details |
|-----------|---------|
| **Stack** | PHP · MySQL · CSS · JavaScript |
| **Scale** | Full-stack web application (user + admin panels) |
| **Impact** | End-to-end rental booking & admin management |
| **Repository** | [Bike-Management-System-php](https://github.com/chandan-howale/Bike-Management-System-php) |

</details>

<details>
<summary><b>⛅ Weather App</b> — Android (Java)</summary>

An Android weather application built with Java that fetches current weather data by geolocation from the OpenWeatherMap API and renders it in a clean, simple UI.

| Attribute | Details |
|-----------|---------|
| **Stack** | Java · Android · OpenWeatherMap REST API |
| **Scale** | Mobile application |
| **Performance** | Lightweight JSON parsing (One Call API 3.0) |
| **Repository** | [WeatherApp-Android](https://github.com/chandan-howale/WeatherApp-Android) |

</details>

---

## 💼 Experience

### Java Developer Trainee
**HulkHire Tech** · Hyderabad, India — *Oct 2025 – Mar 2026*

Built the **PayPal Payment Integration** — Spring Boot microservices on AWS:

- Developed the **PayPal provider service** integrating PayPal REST APIs (Create Order & Capture Order) within a microservices architecture on **AWS EC2 + RDS**
- Secured API communication using **OAuth 2.0 (Client Credentials grant)** with **Redis caching** for access tokens — reducing token-fetch latency by **65%**
- Designed payment status tracking with **100% lifecycle accuracy** and centralized exception handling with custom error codes
- Applied **Circuit Breaker** for fault tolerance and distributed logging via **Micrometer**; used Factory & Builder patterns for modular architecture
- Deployed on AWS EC2/RDS with **Secrets Manager & ElastiCache**; maintained high code coverage with **JUnit & Mockito** in an Agile Scrum team

**Skills:** Spring Boot · Spring Cloud · AWS · Redis · MySQL · OAuth 2.0 · REST APIs · JUnit · Mockito · Agile

---

## 🏆 Achievements

<div align="center">

| Recognition | Details |
|-------------|---------|
| 🛡️ **GitHub Pull Shark** | Pull requests merged on GitHub |
| ⚡ **65% Latency Reduction** | Redis token caching on PayPal integration |
| ✅ **100% Payment Lifecycle Accuracy** | State-machine-driven payment status tracking |
| 🎓 **Academic Excellence** | MCA CGPA 8.52 · BSc CGPA 8.15 |
| ☁️ **Production Deployment** | Microservices deployed on AWS EC2 / RDS / ElastiCache |

</div>

---

## 📜 Certifications

### Infosys Springboard
[![Java Programming Fundamentals](https://img.shields.io/badge/Java%20Programming%20Fundamentals-7C3AED?style=for-the-badge&logo=infosys&logoColor=white)](#)

### NPTEL
[![Cloud Computing](https://img.shields.io/badge/Cloud%20Computing-6366F1?style=for-the-badge)](#)

### IBM
[![Web Development](https://img.shields.io/badge/Web%20Development-4F46E5?style=for-the-badge&logo=ibm&logoColor=white)](#)

---

## 📊 GitHub Analytics

<div align="center">

[![Chandan's GitHub Stats](https://github-readme-stats.vercel.app/api?username=chandan-howale&show_icons=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=E9D5FF&icon_color=7C3AED&rank_icon=github)](https://github.com/chandan-howale)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=chandan-howale&layout=compact&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=E9D5FF&langs_count=8)](https://github.com/chandan-howale)

[![GitHub Streak](https://streak-stats.demolab.com/?user=chandan-howale&theme=midnight-purple&hide_border=true&border_radius=8)](https://git.io/streak-stats)

</div>

---

## 🏅 GitHub Trophies

<div align="center">

[![Trophies](https://github-profile-trophy.vercel.app/?username=chandan-howale&theme=dark_lover&row=2&column=4&margin-w=15&margin-h=15)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## 📈 Contribution Activity

<div align="center">

[![Chandan's Contribution Graph](https://github-readme-activity-graph.vercel.app/graph?username=chandan-howale&theme=tokyo-night&hide_border=true)](https://github.com/chandan-howale)

</div>

---

## 🐍 Contribution Snake

<div align="center">

![snake](https://raw.githubusercontent.com/chandan-howale/chandan-howale/output/github-contribution-grid-snake-dark.svg)

</div>

---

## 🎯 Current Focus

```yaml
learning:
  - Spring Security & OAuth 2.0 deep dive
  - Kubernetes & Docker
  - System Design & Distributed Systems

building:
  - Scaling the Payment Integration System
  - Adding more provider integrations (Razorpay, Stripe)

exploring:
  - AWS Serverless (Lambda, API Gateway)
  - Observability (Micrometer, Prometheus, Grafana)

open_to:
  - Backend Developer roles
  - Associate SDE roles
  - Internship / Freelance opportunities
```

---

## 📫 Connect With Me

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-7C3AED?style=for-the-badge&logo=gmail&logoColor=white)](mailto:howalechandan@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chandanhowale)
[![GitHub](https://img.shields.io/badge/GitHub-1F2937?style=for-the-badge&logo=github&logoColor=white)](https://github.com/chandan-howale)

</div>

---

<div align="center">

> *"Clean architecture, secure payments, and scalable systems — one commit at a time."*

[![Capsule Render](https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:7C3AED,50:6D28D9,100:0F0A1E)](https://github.com/chandan-howale)

</div>
