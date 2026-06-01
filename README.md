<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=800&color=58A6FF&center=true&vCenter=true&width=600&lines=Venkata+Gaurav+Pampana;Java+%26+Spring+Boot+Engineer;Microservices+%7C+DevOps+%7C+AI+Integration" alt="Typing intro" />

<br/>

[![GitHub followers](https://img.shields.io/github/followers/gauravpv?style=for-the-badge&logo=github&color=181717)](https://github.com/gauravpv?tab=followers)
[![Repos](https://img.shields.io/badge/Public%20repos-4-58A6FF?style=for-the-badge&logo=github)](https://github.com/gauravpv?tab=repositories)

</div>

---

### About me

I'm **Gaurav** — a software engineer focused on **production-grade Java backends**: Spring Boot microservices, event-driven architectures, and operational tooling teams can run in real environments.

I care about the details that separate demos from systems you'd ship: async boundaries around slow APIs, caching and circuit breakers, structured LLM output, encrypted service layers, and dashboards that help operators see health and act quickly.

- 🔭 Currently building **[OpsConsole](https://github.com/gauravpv/OpsConsole)** — unified monitoring & admin for DevOps teams  
- 🧠 Recently shipped **[IntelliDesk](https://github.com/gauravpv/Intellidesk)** — AI ticket triage with Kafka, Redis, and Spring AI  
- 🛠️ Stack I reach for most: **Java 21 · Spring Boot 3 · Kafka · PostgreSQL · Redis · Docker**  
- 📫 Reach me: add your email or LinkedIn in [profile settings](https://github.com/settings/profile) (Website field works great for LinkedIn)

---

### Featured projects

| Project | What it does | Highlights |
|--------|----------------|------------|
| [**OpsConsole**](https://github.com/gauravpv/OpsConsole) | Enterprise DevOps operations dashboard | Health monitoring, SSH service control, RBAC, Azure AD, activity feed |
| [**IntelliDesk**](https://github.com/gauravpv/Intellidesk) | AI-powered support ticket triage | Spring AI structured output, Kafka pipeline, Redis cache, SSE live UI |
| [**UnifiedServiceLayer**](https://github.com/gauravpv/UnifiedServiceLayer) | Bureau / Dedupe caching API | AES-CBC envelopes, SHA-256 dedupe, MySQL, configurable downstream routing |

---

### Tech stack

<p align="center">
  <img src="https://img.shields.io/badge/Java-21-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring_Boot-3-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Spring_AI-1.0-6DB33F?style=flat-square&logo=spring&logoColor=white" alt="Spring AI" />
  <img src="https://img.shields.io/badge/Kafka-Event_Streaming-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Kafka" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white" alt="Maven" />
  <img src="https://img.shields.io/badge/Azure_AD-OAuth2-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure AD" />
</p>

---

### GitHub activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=gauravpv&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58A6FF&icon_color=58A6FF&text_color=c9d1d9" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=gauravpv&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58A6FF&text_color=c9d1d9" alt="Top languages" />

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=gauravpv&theme=tokyonight&hide_border=true&background=0D1117&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" alt="GitHub streak" />

</div>

---

### Architecture snapshot — IntelliDesk

```mermaid
flowchart LR
  UI[Dashboard] --> GW[API Gateway]
  GW --> TS[Ticket Service]
  TS --> K[(Kafka)]
  K --> AI[AI Service]
  AI --> OAI[Spring AI / OpenAI]
  AI --> R[(Redis)]
  K --> NS[Notification Service]
  TS --> PG[(PostgreSQL)]
```

---

<div align="center">

**Thanks for stopping by — star a repo if something here is useful.**

<img src="https://komarev.com/ghpvc/?username=gauravpv&label=Profile%20views&color=58A6FF&style=flat" alt="Profile views" />

</div>
