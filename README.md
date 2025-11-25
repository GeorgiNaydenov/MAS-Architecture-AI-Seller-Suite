# AI Seller – Multi-Agent Sales Architecture

[**View Live Presentation**](https://georginaydenov.github.io/MAS-Architecture-AI-Seller-Suite/) | [**View Repository**](https://github.com/GeorgiNaydenov/MAS-Architecture-AI-Seller-Suite)

This repository contains a browser-based, interactive presentation of the **AI Seller** multi-agent architecture for B2B sales automation, hosted via GitHub Pages.

---

## Contents

- **AI_Seller_Crew_Enhanced.html**  
  - Interactive slide deck (React + Tailwind via CDN)
  - Business value & KPIs
  - Core sales use cases (prospecting, outreach, meetings, negotiation, contracts, pipeline insights)
  - End-to-end sales funnel flows
  - Multi-agent (MAS / Crew) system architecture
  - Agent catalog and responsibilities
  - Data flows & storage (CRM, vector DB, ML)
  - RBAC & permission model
  - Security, compliance, and observability

---

## 💻 Presentation Tech Stack & UI/UX

### Zero-Build SPA

- No Node.js or backend required  
- Runs entirely in-browser  
- Optimized for static hosting (e.g., GitHub Pages)

### Front-End Technologies

- **Framework:** React 18.2.0 (CDN, UMD build)
- **JSX Compiler:** Babel Standalone 7.23.5 (browser-based)
- **Styling:** Tailwind CSS (via CDN)
- **Fonts:** Google Fonts (Inter)

### UI & UX

- Modern dark-mode design with glassmorphism and blur
- Keyboard navigation (arrows, spacebar)
- Clickable cards and interactive architecture diagrams
- Animated highlights and gradient effects
- Responsive (flex/grid via Tailwind)

---

## ⚙️ MAS System Architecture Tech Stack

The architecture described in the slides (11-14) is designed for scalability, security, and observability:

### AI & Orchestration

- **Orchestration Engine:** CrewAI (multi-agent task routing)
- **LLMs:** Large Language Models (intent classification, reasoning)
- **ML Models:** Custom forecasting, win-probability scoring

### Data & Memory

- **Vector DB:** Pinecone / Weaviate (embeddings, semantic search)
- **Operational DB:** PostgreSQL
- **Session Store:** Redis
- **Event Streaming:** Kafka / RabbitMQ

### Observability & Monitoring

- **Metrics:** Prometheus, Grafana
- **Logging:** ELK Stack (Elasticsearch, Logstash, Kibana) or Datadog
- **Tracing:** Jaeger, OpenTelemetry

### Security & Infrastructure

- **Encryption:** AWS KMS, AES-256 (at rest), TLS 1.3 (in transit)
- **Auth:** OAuth 2.0, SAML 2.0 (SSO), mTLS (agent comms)
- **API Gateway:** Rate limiting, request routing

---

## What the Deck Is For

- **Product & Sales:** Visualize value, business impact, and KPIs
- **Engineers & Architects:** Review MAS/Crew design, agent roles, integration patterns
- **Security / Compliance / Legal:** Inspect data handling, RBAC, and security controls
- **Clients / Prospects:** Understand how AI Seller works end-to-end

---

## How to View

### 1. Online (Recommended)

- [Open the live site](https://georginaydenov.github.io/MAS-Architecture-AI-Seller-Suite/)

### 2. Local File

```bash
git clone https://github.com/GeorgiNaydenov/MAS-Architecture-AI-Seller-Suite.git
````

* Open `AI_Seller_Crew_Enhanced.html` in any modern browser

If the deck doesn’t render locally due to browser restrictions, use:

```bash
python -m http.server 8000
# Then browse to http://localhost:8000/AI_Seller_Crew_Enhanced.html
```

```
```
