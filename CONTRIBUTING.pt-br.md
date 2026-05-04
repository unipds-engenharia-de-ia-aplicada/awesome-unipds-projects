# Contribuindo — Como enviar o seu projeto

> 🌐 Idioma / Language: [English](./CONTRIBUTING.md) | [Português (BR)](./CONTRIBUTING.pt-br.md)

## Requisitos

- O projeto precisa ser **trabalho original seu**.
- Pode ser inspirado no material do curso, mas **não pode ser uma cópia de um exercício ou demo de aula**.
- Precisa estar em um **repositório público no GitHub**.
- O repositório precisa incluir um `README.md` descrevendo o que o projeto faz e como executá-lo.
- O projeto precisa ser funcional (não precisa estar pronto para produção, mas deve rodar).

## Passos

1. Faça um **fork** deste repositório.
2. Adicione o seu projeto à categoria correta em `README.md`, seguindo o formato da entrada abaixo.
3. Abra um **Pull Request** com o título: `[Project] Your Project Name – Your GitHub Username`.
4. Aguarde a revisão — um mantenedor vai verificar o envio e fazer o merge quando atender aos requisitos.

> [!TIP]
> Não tem certeza de qual categoria se encaixa o seu projeto? Escolha a mais próxima ou use **Other**. Os mantenedores podem sugerir um encaixe melhor durante a revisão.

---

## Formato da entrada

Adicione o seu projeto na seção relevante em `README.md` usando este formato:

```markdown
- [your-username/repo-name](https://github.com/your-username/repo-name) `LANG` `SCOPE` – One sentence describing what the project does. **by [@your-username](https://github.com/your-username)**
```

**Exemplo:**

```markdown
- [jsilva/weather-mcp](https://github.com/jsilva/weather-mcp) `📇` `☁️` – MCP server that fetches real-time weather data and answers natural language queries. **by [@jsilva](https://github.com/jsilva)**
```

**Selos de linguagem / runtime:**

| Selo | Significado |
|-------|---------|
| `🐍` | Python |
| `📇` | TypeScript / JavaScript |
| `🏎️` | Go |
| `🦀` | Rust |
| `#️⃣` | C# |
| `☕` | Java |

**Selos de escopo:**

| Selo | Significado |
|-------|---------|
| `☁️` | Chama APIs externas / na nuvem |
| `🏠` | Roda totalmente em ambiente local |
| `🔗` | Integra dois ou mais serviços |

---

## Modelo de descrição do PR

Copie e preencha o seguinte ao abrir o seu Pull Request:

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
