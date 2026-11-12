# Mateus Ferrari

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?color=00BFBF&size=24&center=true&vCenter=true&width=900&lines=Desenvolvedor+Full+Stack+%26+Engenharia+de+IA;TypeScript+%E2%80%A2+Node.js+%E2%80%A2+React+%E2%80%A2+Next.js;Engenharia+de+IA+%E2%80%A2+RAG+%E2%80%A2+LangGraph+%E2%80%A2+Agentes;FastAPI+%28Python%29+%E2%80%A2+PostgreSQL+%28pgvector%29+%E2%80%A2+AWS"/>

  <br/>

  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/3ateusferrari)
  [![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:mateusspier@gmail.com)
  [![Location](https://img.shields.io/badge/Florian%C3%B3polis-Brasil-107C41?style=flat-square&logo=google-maps&logoColor=white)](https://maps.google.com/?q=Florianopolis)
</div>

---

### 👨‍💻 Sobre Mim

Desenvolvedor **Full Stack** com mais de 3 anos de trajetória em tecnologia, sendo mais de 2 anos dedicados ao desenvolvimento e sustentação de sistemas críticos em produção utilizando **TypeScript, Node.js, NestJS, Next.js e React**.

- 🤖 **Engenharia de IA & Agentes:** Experiência prática com arquitetura de RAG proprietária, redução drástica de custos operacionais de IA (redução de até 92% na Dígitro), bancos vetoriais relacionais (`pgvector`), orquestração de agentes cíclicos com **LangGraph** e fluxos com **Human-in-the-Loop (HITL)**.
- ⚡ **Backend & Event-Driven:** Desenvolvimento de arquiteturas orientadas a eventos (BullMQ, Redis Pub/Sub e particionamento de cache), APIs RESTful resilientes, microsserviços, BFFs e integrações de alta confiabilidade.
- 🏛️ **Experiência Corporativa & Setor Público:**
  - **Dígitro Tecnologia:** Engenharia de IA, infraestrutura RAG para chatbots conversacionais e interfaces reativas em React/Next.js.
  - **Assembleia Legislativa de SC (ALESC):** Atuação como desenvolvedor principal no ciclo completo de software do Sistema de Consultoria Legislativa (NestJS, Next.js, SQL Server, BullMQ) e sustentação de sistemas críticos de licitações e contratos públicos.
- 🎓 **Formação:** Graduando em **Sistemas de Informação** pela **Universidade Federal de Santa Catarina (UFSC)** e Técnico em Telecomunicações pelo **IFSC**.

---

### 🚀 Projetos em Destaque

#### ⚖️ [Lexa — Assistente RAG de Legislação Brasileira & Editais](https://github.com/3ateusferrari/lexa)
> *Assistente jurídico inteligente desenhado para mitigar alucinações com citações auditáveis e recusa determinística fora de escopo.*
- **Chunking Semântico & Busca Híbrida:** Parser nativo de streams PDF/HTML com chunking estrutural (artigos e incisos) que elevou o Hit Rate@5 de 64,4% para 97,8%; busca híbrida RRF (`pgvector` + `tsvector`) combinada a Cross-Reranker (55/55 no benchmark de avaliação).
- **Streaming & Arquitetura Cloud:** Interface reativa em React consumindo streaming SSE (Server-Sent Events) com mapeamento dinâmico de fontes; ingestão assíncrona via AWS SQS + ECS Fargate, IaC com Terraform e suíte com mais de 80 testes automatizados (Vitest e Testcontainers).
- **Stack:** TypeScript, React 18, Express, Drizzle ORM, Zod, PostgreSQL (pgvector), Claude API (Anthropic), AWS (ECS, S3, SQS, CloudFront, Terraform).

#### 🛡️ [SQLPilot — Agente Text-to-SQL Corporativo com Human-in-the-Loop](https://github.com/3ateusferrari/sqlpilot)
> *Sistema corporativo Text-to-SQL para consultas analíticas seguras em PostgreSQL sob o modelo Defense in Depth.*
- **Orquestração Cíclica & HITL:** Grafo de estado em LangGraph (`StateGraph`) com auto-correção iterativa e suspensão nativa (`interrupt()`) integrada a uma interface em React, permitindo aprovação, edição e auditoria humana antes da execução de queries de alto risco.
- **Segurança em 5 Camadas & Observabilidade:** Validação sintática via AST com SQLGlot, estimativa de plano de custo via `EXPLAIN (FORMAT JSON)`, tracing completo com Langfuse e 272 testes automatizados (bloqueando 15/15 vetores de ataque em suíte de red-teaming).
- **Stack:** Python 3.12, FastAPI, LangGraph, Claude Haiku 4.5, PostgreSQL 16, SQLGlot, Langfuse, React 18, TypeScript, Tailwind CSS, Pytest.

---

### 🛠️ Competências Técnicas

| Categoria | Tecnologias & Ferramentas |
| :--- | :--- |
| **Engenharia de IA & Agentes** | Proprietary RAG, RAG Híbrido (`pgvector` + `tsvector` / RRF), LangGraph (StateGraph, HITL), Claude API, OpenAI API, Langfuse (Observabilidade / Tracing), SQLGlot (AST Parsing) |
| **Frontend** | TypeScript, JavaScript, React 19/18 (Hooks avançados, Context), Next.js 16 (App Router, Route Handlers), Tailwind CSS, Streaming SSE, React Testing Library |
| **Backend & Arquitetura** | Node.js, NestJS, Express, FastAPI (Python), APIs RESTful, BullMQ, Redis (Pub/Sub, Cache Particionado), Drizzle ORM, Zod, Arquitetura Limpa, SOLID |
| **Bancos de Dados** | PostgreSQL (`pgvector`, otimização com `EXPLAIN JSON`), SQL Server, MySQL |
| **Cloud, DevOps & Testes** | AWS (ECS Fargate, S3, SQS, CloudFront, Terraform), Docker, GitHub Actions (CI/CD), Vitest, Pytest, Playwright, Testcontainers |

---

### 📜 Certificações & Extensões

- ☁️ **AWS Academy Graduate** — AWS Academy Cloud Architecting (Amazon Web Services)
- 🏛️ **Formação Boas Práticas em Desenvolvimento, SOLID, Clean Code e Design Patterns** — Alura
- 📊 **Escola Regional de Banco de Dados (ERBD)** — Sociedade Brasileira de Computação (SBC)

---

### 📬 Contato

<p align="left">
  <a href="mailto:mateusspier@gmail.com"><img src="https://img.shields.io/badge/Email-mateusspier%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://linkedin.com/in/3ateusferrari"><img src="https://img.shields.io/badge/LinkedIn-in%2F3ateusferrari-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/3ateusferrari"><img src="https://img.shields.io/badge/GitHub-3ateusferrari-181717?style=flat-square&logo=github&logoColor=white"/></a>
</p>

---

<div align="center">
  <img src="https://pokereadme.murilonoguez.com.br/api?user=3ateusferrari&pokes=1,4,7,25,133,94" alt="Equipe Pokémon" />
</div>
