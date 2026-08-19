<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=220&section=header&text=Berat%20Erkul&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Java%20%7C%20Spring%20Boot%20%7C%20Microservices&descAlignY=58&descAlign=50" width="100%"/>

<a href="https://beraterkul.com.tr"><img src="https://img.shields.io/badge/🌐_Portfolio-beraterkul.com.tr-2C5364?style=for-the-badge" /></a>
<a href="https://www.linkedin.com/in/berat-erkul"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://medium.com/@beraterkul00"><img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" /></a>
<a href="mailto:beraterkul00@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=2C5364&center=true&vCenter=true&width=650&lines=Junior+Backend+Developer+%40+Spring+Boot;Building+RESTful+APIs+%26+Microservices;Currently+refactoring+a+monolith+into+microservices;Learning+DDD+%2B+Clean+%2B+Hexagonal+Architecture" alt="Typing SVG" />

</div>

---

### 👋 About Me

I'm a **Junior Java Backend Developer** from Kocaeli, Türkiye — currently a Software Engineering student at Fırat University (Erasmus+ exchange at Univerza v Mariboru, Slovenia 🇸🇮). I build backend systems with **Spring Boot**, break monoliths into **microservices**, and ship them with **Docker + AWS + CI/CD**.

I learn by building — every architecture pattern below started as a project I rebuilt from scratch to actually understand it.

```java
public class BeratErkul implements BackendDeveloper {

    private final String[] stack = {"Java", "Spring Boot", "PostgreSQL", "Docker", "AWS"};
    private final String currentFocus = "Migrating monoliths → microservices, one service at a time";

    @Override
    public void philosophy() {
        System.out.println("SOLID principles aren't optional. Neither is testing.");
    }
}
```

---

### 🧭 Currently Leveling Up

I've spent most of my career so far in **3-layer / layered architecture** (Controller → Service → Repository). Right now I'm deliberately stepping outside that comfort zone for the first time:

| Learning now | Coming from |
|---|---|
| 🧩 Domain-Driven Design (DDD) | Anemic layered models |
| 🏛️ Clean Architecture | Classic 3-layer architecture |
| ⬡ Hexagonal Architecture (Ports & Adapters) | Direct service→repository coupling |
| 🔄 CQRS & Event-Driven Design | Straightforward CRUD flows |
| 📦 Outbox Pattern | Best-effort dual writes |

> Honest note: these are brand new to me. If you've been down this road, I'd genuinely love feedback on my repos below.

---

### 🛠️ Tech Stack

<div align="center">

**Languages**
<br/>
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

**Backend & Architecture**
<br/>
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring%20Cloud-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)

**Data**
<br/>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**Security**
<br/>
![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=for-the-badge&logo=keycloak&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2-4285F4?style=for-the-badge&logo=auth0&logoColor=white)
![Vault](https://img.shields.io/badge/Vault-FFEC6E?style=for-the-badge&logo=vault&logoColor=black)

**DevOps & Cloud**
<br/>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![CircleCI](https://img.shields.io/badge/CircleCI-343434?style=for-the-badge&logo=circleci&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

**Observability**
<br/>
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Zipkin](https://img.shields.io/badge/Zipkin-FF6C37?style=for-the-badge&logo=zipkin&logoColor=white)

</div>

---

### 🚀 Featured Work

<table>
<tr>
<td width="50%" valign="top">

**🎫 Ticketing System — Monolith → Microservices**
<br/>
The same project, rebuilt twice, on purpose.

**v1 — Layered Monolith**
- Controller–Service–Repository layers
- Keycloak + Spring Security auth
- AOP performance monitoring, global exception handling
- Dockerized, deployed on AWS EC2 + RDS
- CircleCI → AWS ECR pipeline

[`ticketing-project-data →`](https://github.com/berat-erkul/ticketing-project-data)

</td>
<td width="50%" valign="top">

**⚙️ TicketinApp — Microservices Rewrite**
<br/>
User / Project / Task services + Gateway + Eureka + Config Server

- Netflix Eureka service discovery
- Spring Cloud Gateway + OpenFeign
- Centralized config, client-side load balancing
- Distributed tracing via Zipkin, Prometheus, Grafana
- Independent database per service

[`TicketinApp →`](https://github.com/berat-erkul/TicketinApp)

</td>
</tr>
</table>

---

### 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=berat-erkul&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=berat-erkul&layout=compact&theme=tokyonight&hide_border=true" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=berat-erkul&theme=tokyonight&hide_border=true" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=berat-erkul&theme=tokyo-night&hide_border=true" width="100%"/>

</div>

---

### 🎓 Background

- 🏫 **Fırat University** — B.Sc. Software Engineering (2022 – Present)
- ✈️ **Erasmus+** — Univerza v Mariboru, Slovenia (2025)
- 💼 **Prodrom ICT Solutions** — Spring Boot Backend Developer
- 💼 **TRTEK Yazılım** — Backend Intern (ASP.NET Core MVC / C#)
- 📜 Certified: CYDEO Backend/Spring Boot Program, Udemy Spring Boot & C++ courses, and more

---

<div align="center">

### 🎸 Off the keyboard

Guitar, singing, and an unreasonable amount of curiosity about why things break in production.

<br/>

**Let's connect — especially if you know DDD, Clean or Hexagonal Architecture and have opinions.**

<a href="mailto:beraterkul00@gmail.com"><img src="https://img.shields.io/badge/Say_Hi-2C5364?style=for-the-badge&logo=maildotru&logoColor=white" /></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,50:203A43,100:0F2027&height=100&section=footer" width="100%"/>

</div>
