<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=230&section=header&text=Berat%20Erkul&fontSize=62&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Java%20%7C%20Spring%20Boot%20%7C%20Microservices&descAlignY=54&descAlign=50" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=23&duration=2800&pause=900&color=2C5364&center=true&vCenter=true&width=680&lines=Junior+Backend+Developer+%40+Spring+Boot;Turning+monoliths+into+microservices%2C+one+repo+at+a+time;Currently+trading+layered+arch+for+DDD+%2B+Clean+%2B+Hexagonal;Docker+%C2%B7+AWS+%C2%B7+CI%2FCD+%C2%B7+repeat" alt="Typing SVG" />

<br/>

<a href="https://beraterkul.com.tr"><img src="https://img.shields.io/badge/🌐_Portfolio-beraterkul.com.tr-2C5364?style=for-the-badge" /></a>
<a href="https://www.linkedin.com/in/berat-erkul"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://medium.com/@beraterkul00"><img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" /></a>
<a href="mailto:beraterkul00@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>

<img src="https://komarev.com/ghpvc/?username=berat-erkul&label=Profile%20Views&color=2c5364&style=flat" />

</div>

<br/>

## 👋 About Me

I'm a **Junior Java Backend Developer** from Kocaeli, Türkiye — Software Engineering student at Fırat University, with an Erasmus+ exchange semester at Univerza v Mariboru, Slovenia 🇸🇮. I build backend systems with **Spring Boot**, break monoliths into **microservices**, and ship them with **Docker + AWS + CI/CD**.

I learn by rebuilding — every pattern in this profile started life as a project I tore down and reassembled just to understand *why* it exists.

```java
public class BeratErkul implements BackendDeveloper {

    private final String[] stack   = {"Java", "Spring Boot", "PostgreSQL", "Docker", "AWS"};
    private final String   focus   = "Migrating monoliths → microservices, one bounded context at a time";
    private       boolean  coffee  = true;

    @Override
    public void philosophy() {
        while (coffee) {
            write(cleanCode());
            test(everything());
            refactor(fearlessly());
        }
    }
}
```

<br/>

## 🧭 The Architecture Journey I'm On

For most of my hands-on work so far I've lived in **classic 3-layer / layered architecture** — Controller → Service → Repository, simple and effective. Right now I'm deliberately climbing out of that comfort zone for the first time, so consider this diagram a live status, not a finished résumé:

```mermaid
flowchart LR
    A["🧱 Layered Architecture<br/>(what I know well)"] -->|now learning| B["⬡ Hexagonal<br/>Ports & Adapters"]
    B --> C["🏛️ Clean Architecture"]
    C --> D["🧩 Domain-Driven Design"]
    D --> E["🔄 CQRS + Event-Driven<br/>+ Outbox Pattern"]

    style A fill:#2C5364,stroke:#0F2027,color:#fff
    style B fill:#203A43,stroke:#0F2027,color:#fff
    style C fill:#203A43,stroke:#0F2027,color:#fff
    style D fill:#203A43,stroke:#0F2027,color:#fff
    style E fill:#0F2027,stroke:#0F2027,color:#fff
```

> 🙋 Honest note: DDD, Clean and Hexagonal Architecture are brand new to me — I'm seeing them for the first time beyond theory. If you've walked this road, I'd genuinely love a code review or a pointer.

<br/>

## 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=java,spring,cs,cpp,postgres,mysql,redis,docker,aws,kafka,git,github,githubactions,idea&theme=dark" />

<br/><br/>

![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=for-the-badge&logo=keycloak&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2-4285F4?style=for-the-badge&logo=auth0&logoColor=white)
![Vault](https://img.shields.io/badge/Vault-FFEC6E?style=for-the-badge&logo=vault&logoColor=black)
![CircleCI](https://img.shields.io/badge/CircleCI-343434?style=for-the-badge&logo=circleci&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Zipkin](https://img.shields.io/badge/Zipkin-FF6C37?style=for-the-badge&logo=zipkin&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)

</div>

<br/>

## 🚀 Featured Work

<table>
<tr>
<td width="50%" valign="top">

### 🎫 Ticketing System — v1
**Layered Monolith**

The same product, rebuilt twice on purpose — this is the "before".

- Controller–Service–Repository layers
- Keycloak + Spring Security auth, password hashing
- AOP performance monitoring, global exception handling
- Dockerized → AWS EC2 + RDS
- CircleCI → AWS ECR pipeline

[`ticketing-project-data →`](https://github.com/berat-erkul/ticketing-project-data)

</td>
<td width="50%" valign="top">

### ⚙️ TicketinApp — v2
**Microservices Rewrite**

User / Project / Task services + Gateway + Eureka + Config Server — the "after".

- Netflix Eureka service discovery
- Spring Cloud Gateway + OpenFeign
- Centralized config + client-side load balancing
- Distributed tracing: Zipkin, Prometheus, Grafana
- Independent database per service

[`TicketinApp →`](https://github.com/berat-erkul/TicketinApp)

</td>
</tr>
</table>

```mermaid
flowchart TB
    subgraph Client
        U[User]
    end
    U --> GW["🚪 API Gateway<br/>Spring Cloud Gateway"]
    GW --> EU["🧭 Eureka<br/>Discovery Server"]
    GW --> US["👤 User Service"]
    GW --> PS["📁 Project Service"]
    GW --> TS["✅ Task Service"]
    US -.OpenFeign.-> PS
    PS -.OpenFeign.-> TS
    US --> UDB[(User DB)]
    PS --> PDB[(Project DB)]
    TS --> TDB[(Task DB)]
    US --> OBS["📈 Zipkin / Prometheus / Grafana"]
    PS --> OBS
    TS --> OBS

    style GW fill:#2C5364,stroke:#0F2027,color:#fff
    style EU fill:#203A43,stroke:#0F2027,color:#fff
    style OBS fill:#0F2027,stroke:#0F2027,color:#fff
```

<br/>

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=berat-erkul&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=berat-erkul&layout=compact&theme=tokyonight&hide_border=true" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=berat-erkul&theme=tokyonight&hide_border=true" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=berat-erkul&theme=tokyo-night&hide_border=true" width="100%"/>

</div>

<details>
<summary>🏆 Trophy Case (click to expand)</summary>

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=berat-erkul&theme=tokyonight&no-frame=true&row=1&column=7" />
</div>

</details>

<br/>

## 🎓 Background

```mermaid
timeline
    title Path so far
    2022 : Started B.Sc. Software Engineering — Fırat University
    2023 : OOP & Java certifications (Inspimo, Cambly)
    2024 : Spring Boot & Java bootcamps (Udemy, CYDEO)
    2025 : Erasmus+ exchange — Univerza v Mariboru, Slovenia
         : Spring Boot Backend Developer — Prodrom ICT Solutions
    2026 : Backend Intern (ASP.NET Core / C#) — TRTEK Yazılım
```

- 📜 Certified: **CYDEO** Backend/Spring Boot Developer Program, plus Udemy courses in Spring Boot, Java, C++ and Relational DB Design
- 🌍 English — B2 Professional Working Proficiency

<br/>

<div align="center">

## 🎸 Off the Keyboard

Guitar, singing, and an unreasonable amount of curiosity about why things break in production.

**Let's connect — especially if you know DDD, Clean or Hexagonal Architecture and have opinions.**

<a href="mailto:beraterkul00@gmail.com"><img src="https://img.shields.io/badge/Say_Hi-2C5364?style=for-the-badge&logo=maildotru&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/berat-erkul"><img src="https://img.shields.io/badge/Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,50:203A43,100:0F2027&height=110&section=footer" width="100%"/>

</div>
