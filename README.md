<p align="center">
  <img src="./assets/trace.svg" alt="Animated OpenTelemetry-style trace waterfall of my profile" width="100%">
</p>

<h1 align="center">Hi, I'm Sneha 👋</h1>

<p align="center">
  <img src="./assets/typing.svg" alt="Making systems observable · Tracing requests across services · Turning p99 spikes into stories · Building reliable backends at scale" width="620">
</p>

<p align="center">
  <b>Senior Backend Engineer</b> · 5 years building distributed, event-driven systems on AWS<br>
</p>

---

### 🔭 `about.js` - About Me🙆🏻‍♀️

<p align="center">
  <img src="./assets/console.svg" alt="Terminal output of node about.js: an OpenTelemetry span named about-me with attributes role backend engineer, focus distributed systems, event-driven and observability, cloud aws, coffee.cups Infinity, and a published event about OpenTelemetry on Medium" width="100%">
</p>

---

### 🏗️ Building Backend
I build distributed, event-driven systems that scale to millions of users and stay observable from end to end.

```mermaid
flowchart LR
    C(["🌐 Client"]) --> G("🚪 API layer")
    G -- "✍️ commands" --> W("📝 Write service")
    G -- "🔎 queries" --> Q("📖 Read service")
    W --> WS[("💾 Write store")]
    W --> K[["📨 Kafka<br/>domain events"]]
    K --> P("⚡ Async consumers<br/>batch + fan-out")
    P --> RM[("🗄️ Read model<br/>DynamoDB")]
    Q --> RM
    T(["🔭 OpenTelemetry<br/>trace context on every hop"])
    T -.-> G
    T -.-> K
    T -.-> P

    classDef client fill:#fff3c4,stroke:#ffd23f,stroke-width:2px,color:#5c4a00;
    classDef api fill:#e6dcff,stroke:#a98bff,stroke-width:2px,color:#3b2a70;
    classDef write fill:#ffe0ec,stroke:#ff8fb8,stroke-width:2px,color:#5a2a3c;
    classDef read fill:#d9f7e8,stroke:#5fd0a0,stroke-width:2px,color:#1f5a45;
    classDef store fill:#ffe8d1,stroke:#ffab5e,stroke-width:2px,color:#5c3410;
    classDef stream fill:#d6f0ff,stroke:#5bb8f5,stroke-width:2px,color:#12496b;
    classDef worker fill:#fff0b8,stroke:#f5c400,stroke-width:2px,color:#5c4a00;
    classDef otel fill:#425cc7,stroke:#2f45a0,stroke-width:2px,color:#ffffff;
    class C client;
    class G api;
    class W write;
    class Q read;
    class WS,RM store;
    class K stream;
    class P worker;
    class T otel;
    linkStyle default stroke:#b39ddb,stroke-width:2px
    linkStyle 8,9,10 stroke:#425cc7,stroke-width:2px,stroke-dasharray:4 4
```

![Event-driven](https://img.shields.io/badge/Event--Driven-6E40C9?style=flat-square)
![CQRS](https://img.shields.io/badge/CQRS-1F6FEB?style=flat-square)
![Distributed batch processing](https://img.shields.io/badge/Distributed%20Batch%20Processing-0E8A16?style=flat-square)
![Access pattern design](https://img.shields.io/badge/Access%20Pattern%20Design-F5A800?style=flat-square)
![Infrastructure as code](https://img.shields.io/badge/Infrastructure%20as%20Code-FF4F8B?style=flat-square)
![Performance tuning](https://img.shields.io/badge/Performance%20Tuning-3FB950?style=flat-square)

---

### 📡 Pillars of my profile

<p align="center">
  <img src="./assets/signals.svg" alt="Three animated cards: Traces (Node.js HTTP tracing repo), Metrics (GitHub activity sparkline) and Logs (Medium articles about OpenTelemetry)" width="100%">
</p>

| 🔭 Traces | 📈 Metrics | 📝 Logs |
|:--|:--|:--|
| [nodejs-enhanced-default-http-tracing](https://github.com/thisissneha/nodejs-enhanced-default-http-tracing) | [All repositories](https://github.com/thisissneha?tab=repositories) | [OTel default HTTP instrumentation](https://medium.com/@sneha_99/opentelemetry-unlocking-powerful-performance-insights-with-default-http-instrumentation-4fd14d5f3e46) · [Track Every Request](https://medium.com/@sneha_99/track-every-request-a-guide-to-opentelemetry-5f3cb312015c) |

#### 🧭 How my ideas flow through the collector

```mermaid
flowchart LR
    subgraph R["📥 receivers"]
        A(["🐛 prod bugs"])
        B(["📚 things I read"])
        C(["💡 curiosity"])
    end
    subgraph P["⚙️ processors"]
        D(["📦 batch<br/>experiments"])
        E(["🧹 filter<br/>noise"])
        F(["🏷️ attributes<br/>add context"])
    end
    subgraph X["📤 exporters"]
        G(["🔭 GitHub repos"])
        H(["📝 Medium articles"])
    end
    A --> D
    B --> D
    C --> D
    D --> E --> F
    F --> G
    F --> H

    classDef recv fill:#ffe0ec,stroke:#ff8fb8,stroke-width:2px,color:#5a2a3c;
    classDef proc fill:#dfeaff,stroke:#7aa7ff,stroke-width:2px,color:#243b6b;
    classDef exp fill:#d9f7e3,stroke:#5fd08a,stroke-width:2px,color:#1f5a37;
    class A,B,C recv;
    class D,E,F proc;
    class G,H exp;
    style R fill:#fff5f9,stroke:#ff8fb8,stroke-width:2px,stroke-dasharray:6 4,color:#c2456f
    style P fill:#f4f8ff,stroke:#7aa7ff,stroke-width:2px,stroke-dasharray:6 4,color:#3d63c9
    style X fill:#f3fff7,stroke:#5fd08a,stroke-width:2px,stroke-dasharray:6 4,color:#2e8a57
    linkStyle default stroke:#b39ddb,stroke-width:2px
```

---

### 🏷️ Resource attributes

| Attribute | Value |
|:--|:--|
| `languages` | ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| `runtime` | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) |
| `cloud` | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white) ![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white) ![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white) |
| `streaming` | ![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) |
| `observability` | ![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white) ![New Relic](https://img.shields.io/badge/New%20Relic-008C99?style=flat-square&logo=newrelic&logoColor=white) |
| `delivery` | ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05033?style=flat-square&logo=git&logoColor=white) |

---

### 🔗 Export to

<p>
  <a href="https://medium.com/@sneha_99"><img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white"></a>
</p>
