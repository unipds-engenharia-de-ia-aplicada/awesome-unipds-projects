# Awesome UNIPDS Projects 🎓

A curated list of original projects built by students of the **[UNIPDS Software engineering with Applied AI](https://unipds.com.br/org-erick-wendel/?utm_source=awesomeunipdsprojects&utm_medium=github&utm_term=&utm_content=awesomeunipdsprojects)** postgrad course.

> [!IMPORTANT]
> This is a showcase of **original student work**. Projects inspired by course concepts are welcome, but must be brand new creations — not copies of exercises demonstrated in class.

Want to add your own? See [CONTRIBUTING.md](CONTRIBUTING.md).

---

## Table of Contents

- [Legend](#legend)
- [Projects](#projects)
  - [🔌 MCP Servers](#-mcp-servers)
  - [🤖 AI Agents](#-ai-agents)
  - [🌐 Web Apps & Games](#-web-apps--games)
  - [⚡ Integrations & Automations](#-integrations--automations)
  - [🛠️ Tools & Utilities](#-tools--utilities)
  - [📦 Other](#-other)

---

## Legend

**Language / runtime**
- `🐍` – Python
- `📇` – TypeScript / JavaScript
- `🏎️` – Go
- `🦀` – Rust
- `#️⃣` – C#
- `☕` – Java

**Scope**
- `☁️` – Calls external / cloud APIs
- `🏠` – Runs fully locally
- `🔗` – Integrates two or more services

---

## Projects

> [!NOTE]
> Projects are listed alphabetically within each category.

### 🔌 MCP Servers

MCP servers that extend AI assistants with new tools and capabilities.

<!-- Add your project here. See CONTRIBUTING.md for the entry format. -->
- [alvesribeirof/architecture-analysis-mcp](https://github.com/alvesribeirof/architecture-analysis-mcp) `#️⃣` `🔗` – MCP server for architectural code analysis focusing on SOLID principles, Design Patterns, and immediate feedback to the developer. **by [@alvesribeirof](https://github.com/alvesribeirof)**

- [s3b4hjr/philosophy-mcp](https://github.com/s3b4hjr/philosophy-mcp) `🐍` `☁️` - MCP server for a multilingual philosophy corpus — glossary, syntheses, thinker profiles, and articles in Portuguese, English, and Spanish. **by [@s3b4hjr](https://github.com/s3b4hjr)**

---

### 🤖 AI Agents

Autonomous agents that accomplish multi-step tasks using LLMs.

- [SyanCS/pokemon-training-center](https://github.com/SyanCS/pokemon-training-center) `📇` `🔗` – AI scheduling assistant that classifies natural-language intents via LangGraph + OpenRouter to manage Pokemon lesson enrollments, bookings, and recommendations. **by [@SyanCS](https://github.com/SyanCS)**
- [SyanCS/alvorada_real_estate](https://github.com/SyanCS/alvorada_real_estate) `📇` `🔗` – Real estate research platform with three LangGraph pipelines for feature extraction from notes, natural-language property ranking, and Neo4j GraphRAG similarity search. **by [@SyanCS](https://github.com/SyanCS)**
- [matheusmschaffer/entrevistador-implacavel](https://github.com/matheusmschaffer/entrevistador-implacavel) `TypeScript` `AI Agent` – LangGraph agent that conducts job interviews with four distinct personalities, evaluates answers silently, and delivers dramatic feedback. **by [@matheusmschaffer](https://github.com/matheusmschaffer)**
- [MarceloSoiber/credit-card-fraud-detection](https://github.com/MarceloSoiber/credit-card-fraud-detection) `🐍` `🔗` – Local credit card fraud detection platform with FastAPI, PostgreSQL, Docker, a web dashboard, model training workflows, sequence-based ML inference, transaction import, risk scoring, and optional LLM-powered fraud analysis. **by [@MarceloSoiber](https://github.com/MarceloSoiber)**
  
---

### 🌐 Web Apps & Games

Web applications and browser-based experiences powered by machine learning or AI.

- [Biaginibe/ML-nextjs-board-game](https://github.com/Biaginibe/ML-nextjs-board-game) `📇` `🏠` – Board game recommendation system using TensorFlow.js for server-side machine learning with Next.js. **by [@Biaginibe](https://github.com/Biaginibe)**
- [DiogoOrdine/game-eclipse-ai-agent](https://github.com/DiogoOrdine/game-eclipse-ai-agent) `📇` `🏠` – Adaptation of the Eclipse game integrating a YOLOv5n neural network running with TensorFlow.js inside a Web Worker. **by [@DiogoOrdine](https://github.com/DiogoOrdine)**
- [Douglas-sm/game-flapbird](https://github.com/Douglas-sm/game-flapbird) `📇` `🏠` – Pixel art Flappy Bird game with an AI that trains itself in the browser using Canvas 2D and TensorFlow.js. **by [@Douglas-sm](https://github.com/Douglas-sm)**
- [ElizioMartins/graphrag-poc](https://github.com/ElizioMartins/graphrag-poc) `📇` `☁️` `🔗` – Intelligent document search system with GraphRAG: reads PDF/XML files, creates knowledge graphs in Neo4j, and answers questions using semantic search + LLMs with automatic fallback across multiple free models. **by [@ElizioMartins](https://github.com/ElizioMartins)**
- [me-wsantos/classificacao-tensorflowjs](https://github.com/me-wsantos/AI-Engineer-UNIPDS/tree/75e2183198175ac8610399b1df2752fdef710f42/001-classificacao-tensorflowjs) `📇` `🏠` – Social class classifier neural network trained and executed entirely in the browser using TensorFlow.js, predicting socioeconomic tiers (A–E) based on user-provided attributes. [🌐 Live demo](https://ai-engineer-unipds.onrender.com/) **by [@me-wsantos](https://github.com/me-wsantos)**
- [rdiegoss/scout](https://github.com/rdiegoss/scout) `📇` `🏠` – AI-powered PWA for local service discovery that uses on-device TensorFlow.js embeddings to rank nearby providers (electricians, plumbers, mechanics) by semantic similarity, geographic proximity, and behavioral compatibility. **by [@rdiegoss](https://github.com/rdiegoss)**
- [SyanCS/dr_nala_breed_recommendation](https://github.com/SyanCS/dr_nala_breed_recommendation) `📇` `🏠` – AI-first dog breed recommendation app that trains a TensorFlow compatibility classifier, persists model artifacts in PostgreSQL, and serves ranked recommendations from a browser web worker with a rule-based fallback. **by [@SyanCS](https://github.com/SyanCS)**
- [SyanCS/the-speakeasy-chatbot](https://github.com/SyanCS/the-speakeasy-chatbot) `📇` `🏠` – 1920s barkeep chatbot that runs fully in-browser on Chrome's on-device Gemini Nano (Prompt API) — multimodal cocktail suggestions, substitutions, scaling, and drink fixes with no backend or API keys. **by [@SyanCS](https://github.com/SyanCS)**
- [thabata-marchi/portuguese-alphabet-game](https://github.com/thabata-marchi/portuguese-alphabet-game) `📇` `🏠` – Pre-literacy educational game for children that teaches the Portuguese alphabet using voice recognition and adaptive AI. **by [@thabata-marchi](https://github.com/thabata-marchi)**
- [wsantos-ai/classificador-socioeconomico](https://github.com/wsantos-ai/Classificador-Socioeconomico) `📇` `🏠` – Social class classifier neural network trained and executed entirely in the browser using TensorFlow.js, predicting socioeconomic tiers (A–E) based on user-provided attributes. [🌐 Live demo](https://ai-engineer-unipds.onrender.com/) **by [@wsantos-ai](https://github.com/wsantos-ai)**
- [wsantos-ai/GitHub-PII-Scanner](https://github.com/wsantos-ai/GitHub-PII-Scanner) `📇` `🏠` – Web tool for static analysis of GitHub repositories to detect exposure of personal data (PII) and sensitive credentials in source code.  [🌐 Live demo](https://git-hub-pii-scanner.vercel.app/) **by [@wsantos-ai](https://github.com/wsantos-ai)**

---

### ⚡ Integrations & Automations

Projects that connect services, automate workflows, or react to events.

- [mjunior/whatsapp-ai-pix-agent](https://github.com/mjunior/whatsapp-ai-pix-agent) `📇` `🔗` – An AI agent that charges my wife via PIX when she asks for favors on WhatsApp. **by [@mjunior](https://github.com/mjunior)**

- [iran-gregorio/project-aegis](https://github.com/iran-gregorio/project-aegis) `📇` `🔗` - An intelligent chatbot designed to analyze sentiment and handle aggression on WhatsApp. ** by [@iran-gregorio](https://github.com/iran-gregorio)**

- [nogueira-araujo/IReadThis.Recommender](https://github.com/nogueira-araujo/IReadThis.Recommender) `#️⃣` `🏠` – AI recomendation API totally developed in C# using the side-car pattern to acoplish into an existent legacy system. **by [@nogueira-araujo](https://github.com/nogueira-araujo)**

---

### 🛠️ Tools & Utilities

CLIs, libraries, helpers, and developer tools powered by AI.

<!-- Add your project here. See CONTRIBUTING.md for the entry format. -->
- [ElizioMartins/projeto-00-ibge-tensores](https://github.com/ElizioMartins/projeto-00-ibge-tensores) `📇` `🏠` – Population Predictor using IBGE demographic data and Machine Learning. **by [@ElizioMartins](https://github.com/ElizioMartins)**
- [ftonato/auris](https://github.com/ftonato/auris) `📇` `☁️` – Production-grade Node.js RAG system with hybrid retrieval, pluggable adapters, and OpenTelemetry tracing. **by [@ftonato](https://github.com/ftonato)**
- [lucas-figueiredo-m/radar](https://github.com/lucas-figueiredo-m/radar) `📡` `🪲` - An integrated React Native DevTools with console, networking, native metrics and more, powered with an MCP for AI-assisted debugging. **by [@lucas-figueiredo-m](https://github.com/lucas-figueiredo-m)**
- [ftuyama/scroll-closing-your-eyes](https://github.com/ftuyama/scroll-closing-your-eyes) `🐍` `🏠` – Hands-free scrolling driven by eye closure (left eye up, right eye down) using the webcam, MediaPipe Face Landmarker, and PyAutoGUI, with blink filtering and “look straight” gating. **by [@ftuyama](https://github.com/ftuyama)**
- [Brunoolliveira1993/code-review-ai](https://github.com/Brunoolliveira1993/code-review-ai) `📇` `🏠` - Analyzes GitHub Pull Requests,analyzes GitLab and GitLab Merge Requests, collects the PR/MR or commit diff, sends the code to AI via OpenRouter, and displays found issues and suggestions **by [@Brunoolliveira1993](https://github.com/Brunoolliveira1993)**
---

### 📦 Other

Anything that doesn't fit neatly into the categories above.

<!-- Add your project here. See CONTRIBUTING.md for the entry format. -->
*No projects yet — be the first to submit one!*

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for submission guidelines.  
Questions? Open an issue or reach out on the course community channel.

## Thanks

A special thanks to all our amazing contributors 💚🇧🇷

<a href="https://github.com/unipds-engenharia-de-ia-aplicada/awesome-unipds-projects/graphs/contributors"><img src="https://readme-contribs.as93.net/contributors/unipds-engenharia-de-ia-aplicada/awesome-unipds-projects" /></a>
