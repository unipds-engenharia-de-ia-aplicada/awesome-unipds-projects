# Contributing — How to Submit Your Project

## Requirements

- The project must be your **own original work**.
- It can be inspired by course material, but **cannot be a copy of a class exercise or demo**.
- It must live in a **public GitHub repository**.
- The repository must include a `README.md` describing what the project does and how to run it.
- The project must be functional (it does not need to be production-ready, but it should run).

## Steps

1. **Fork** this repository.
2. Add your project to the correct category in `README.md`, following the entry format below.
3. Open a **Pull Request** with the title: `[Project] Your Project Name – Your GitHub Username`.
4. Wait for review — a maintainer will verify the submission and merge it once it meets the requirements.

> [!TIP]
> Not sure which category fits your project? Pick the closest one or use **Other**. Maintainers may suggest a better fit during review.

---

## Entry Format

Add your project to the relevant section in `README.md` using this format:

```markdown
- [your-username/repo-name](https://github.com/your-username/repo-name) `LANG` `SCOPE` – One sentence describing what the project does. **by [@your-username](https://github.com/your-username)**
```

**Example:**

```markdown
- [jsilva/weather-mcp](https://github.com/jsilva/weather-mcp) `📇` `☁️` – MCP server that fetches real-time weather data and answers natural language queries. **by [@jsilva](https://github.com/jsilva)**
```

**Language / runtime badges:**

| Badge | Meaning |
|-------|---------|
| `🐍` | Python |
| `📇` | TypeScript / JavaScript |
| `🏎️` | Go |
| `🦀` | Rust |
| `#️⃣` | C# |
| `☕` | Java |

**Scope badges:**

| Badge | Meaning |
|-------|---------|
| `☁️` | Calls external / cloud APIs |
| `🏠` | Runs fully locally |
| `🔗` | Integrates two or more services |

---

## PR Description Template

Copy and fill in the following when opening your Pull Request:

```markdown
## Project Submission

**Project name:** Your Project Name
**GitHub repo:** https://github.com/your-username/your-repo
**Short description:** One sentence explaining what your project does.
**Category:** MCP Servers | AI Agents | Integrations & Automations | Web Apps & Games | Tools & Utilities | Other
**Stack:** e.g. TypeScript, TensorFlow.js, Next.js

## What makes it original?
<!-- Explain how this project goes beyond the course material. What's your own idea or twist? -->

## Checklist

- [ ] The project is my own original work
- [ ] It is NOT a copy of a class exercise or demo
- [ ] The repository is public and has a README with setup instructions
- [ ] I followed the entry format described in this guide
```
