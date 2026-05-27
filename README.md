# Alexandre Caramaschi

**CEO da [Brasil GEO](https://brasilgeo.ai) · ex-CMO da [Semantix](https://www.linkedin.com/company/semantix-inc/) (Nasdaq) · cofundador da [AI Brasil](https://aibrasil.com.br) e da NAIA · pioneiro de GEO no Brasil**

![GEO](https://img.shields.io/badge/GEO-Generative_Engine_Optimization-0176d3?style=flat-square)
![Next.js](https://img.shields.io/badge/Next.js-16-000000?style=flat-square&logo=nextdotjs)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178c6?style=flat-square&logo=typescript)
![React](https://img.shields.io/badge/React-19-61dafb?style=flat-square&logo=react)
![Schema.org](https://img.shields.io/badge/Schema.org-32_types-2e844a?style=flat-square)
![llms.txt](https://img.shields.io/badge/llms.txt-v19.2-ff6b35?style=flat-square)
![Lines](https://img.shields.io/badge/Code-122K+_lines-8b5cf6?style=flat-square)
![Courses](https://img.shields.io/badge/Courses-35_free-0176d3?style=flat-square)
![Articles](https://img.shields.io/badge/Articles-27+long_form-0176d3?style=flat-square)
![Snapshot](https://img.shields.io/badge/Snapshot-27_maio_2026-22c55e?style=flat-square)

GEO Engineer — I build systems that make brands visible to AI. Generative Engine Optimization (GEO) is the discipline of structuring digital presence so that large language models accurately represent, cite, and recommend entities.

18+ years in tech, marketing, and sales. BSc in Computer Science (UFV), with executive education at Harvard Extension, Stanford, and FIA / Tongji. Pioneered GEO methodology and practice in Brazil. Cofounder of AI Brasil and of NAIA (AI agent for brands).

---

## Recognition · 2026

- **Gramado Summit 2026 (9ª edição)** — speaker em painéis sobre Generative Engine Optimization e Business-to-Agent. Frase que circulou: *"Hoje o CFO ainda olha o orçamento de mídia e enxerga 70% de SEO e SEM. Em 18 meses, a parcela alocada para presença em LLMs vai estar entre 5% e 15%."* Cobertura editorial em 5 veículos brasileiros (06–08 mai 2026).
- **AI Brasil · LLM Wiki (26 mai 2026)** — artigo autoral *"LLM Wiki: o bibliotecário que sua empresa não conseguiu contratar acaba de ficar de graça"*. Tese: RAG como camada contínua de memória institucional, conexão com o Memex de Vannevar Bush e práticas contemporâneas de GEO.
- **PwC · Ranking EXAME Negócios em Expansão 2026** — Brasil GEO submetida à avaliação anual, aguardando resultado.
- **18+ matérias** em E-Commerce Brasil, ND Mais, Call to Call, Inteligência Móvel, Brasil Inovador, Promoview, Starten, Baguete, Capital Digital, IT Forum, iMasters, Voz do Bairro, Jornal do Brás, Gazeta da Semana, Jornal do Belém, Portal Sala da Notícia, Coluna do Nenê.

## Research

- **Paper SSRN · Null-result** — *Citação de marcas brasileiras em LLMs: 7.052 respostas, 12 dias, replicação pré-registrada*. Estudo empírico com cohort versionado de prompts cross-LLM (ChatGPT, Claude, Gemini, Perplexity), metodologia v2 (NER v2, cohort 127, battery 192), janela ativa 23 abr → 21 jul 2026.
- **AutoGEO (ICLR 2026)** — leitura crítica e adaptação ao mercado brasileiro do framework de optimização generativa publicado.
- **CC-GSEO-Bench / SAGEO Arena / Answer Bubbles** — bases teóricas do GEO Score Checker v2.2.

## Current Focus

- **GEO Methodology** — frameworks abertos e auditáveis para Generative Engine Optimization
- **Educational Platform** — 35 cursos gratuitos (387 módulos) sobre IA, GEO, SEO, Python e desenvolvimento
- **Multi-LLM Orchestration** — pipeline de 5 LLMs (Claude, GPT-4o, Gemini, Perplexity, Groq) para geração e curadoria
- **llms.txt Advocacy** — promovendo o padrão llms.txt para descoberta por IA
- **Entity Consistency** — representações entitárias machine-readable usando Schema.org e knowledge graphs
- **B2A (Business-to-Agent)** — como organizações devem se apresentar a agentes autônomos
- **GEO Score Checker** — instrumento de medição com inferência estatística (Cohen / Fleiss kappa, bootstrap BCa) e calibração contra dataset empírico

## Platform: alexandrecaramaschi.com

Full-stack educational and consulting platform — 122.000+ linhas de TypeScript:

| Metric | Value |
|--------|-------|
| Courses | 35 gratuitos (387 módulos, gamificação, certificados) |
| Insights | 25 análises aprofundadas |
| Articles | 27+ long-form pieces |
| Components | 53 React components |
| API Routes | 12 endpoints |
| Schema.org | 32 types em JSON-LD |
| Auth | Supabase (e-mail + senha, PKCE, RLS) |
| Gamification | XP, 11 níveis, 13 badges, streaks, certificados |
| llms.txt | v19.2 (27 mai 2026) — non-Google declarado |

### Key Technical Features

- **Authentication**: Supabase Auth com PKCE confirmation, AuthProvider unificado, CSP-hardened
- **Gamification**: XP system (10 / módulo, 100 / curso), 13 achievements, streak tracking, dark mode dashboard
- **Progress Sync**: localStorage + Supabase merge strategy (zero perda de progresso no primeiro login)
- **Course Factory**: pipeline 5-LLM gera cursos automaticamente (Perplexity → GPT-4o → Gemini → Groq → Claude)
- **Semantic Search**: pgvector no Supabase, hybrid retrieval (dense + lexical + metadata) com RRF
- **GEO Infrastructure**: 32 Schema.org types, llms.txt v19.2, IndexNow, 16 AI crawlers permitidos

## GEO Score Checker · v2.2

Ferramenta gratuita em [alexandrecaramaschi.com/ferramentas/geo-score](https://alexandrecaramaschi.com/ferramentas/geo-score) — 5 de 6 fases em produção.

| Capability | Detail |
|--------|--------|
| Dimensões stage-aware | 8 (Retrieval → Geo-Personalization Robustness) |
| LLMs em paralelo | gpt-4o-mini · claude-haiku-4-5 · gemini-2.5-pro · sonar |
| Inferência estatística | Cohen / Fleiss kappa · bootstrap BCa · normal CDF/PPF (Acklam) |
| Calibração | Logit + 5-fold CV AUROC contra dataset empírico do Papers |
| FinOps | 6 camadas de defesa, custo ~US$ 0,04 free / US$ 0,13 PRO |
| Roadmap | [alexandrecaramaschi.com/ferramentas/geo-score/roadmap](https://alexandrecaramaschi.com/ferramentas/geo-score/roadmap) |

Cliente piloto em produção: Stone (Banco do Empreendedor, rebrand 15 mai 2026). Auditoria NAIA ao vivo em 25 mai 2026 cobriu 64 URLs de stone.com.br.

## Open-Source Repositories

| Repository | Description | License |
|---|---|---|
| [geo-checklist](https://github.com/alexandrebrt14-sys/geo-checklist) | Technical audit checklist for Generative Engine Optimization | MIT |
| [llms-txt-templates](https://github.com/alexandrebrt14-sys/llms-txt-templates) | Templates, spec, and Python validator for the llms.txt standard | MIT |
| [entity-consistency-playbook](https://github.com/alexandrebrt14-sys/entity-consistency-playbook) | 5-step playbook for building entity consistency across platforms | MIT |
| [geo-taxonomy](https://github.com/alexandrebrt14-sys/geo-taxonomy) | Structured vocabulary of 60+ GEO terms (JSON / CSV / Markdown) | CC BY 4.0 |
| [geo-orchestrator](https://github.com/alexandrebrt14-sys/geo-orchestrator) | Multi-LLM orchestrator (Claude, GPT-4o, Gemini, Perplexity, Groq) com adaptive routing, FinOps governance, auto-calibration. 140 tests, 53% coverage | — |
| [geo-finops](https://github.com/alexandrebrt14-sys/geo-finops) | Tracking centralizado de uso de LLMs para todos os projetos do ecossistema Brasil GEO. SQLite local + Supabase sync | — |
| [papers](https://github.com/alexandrebrt14-sys/papers) | Infraestrutura de coleta e análise para pesquisa empírica em GEO | — |
| [curso-factory](https://github.com/alexandrebrt14-sys/curso-factory) | Fábrica de cursos com pipeline de 5 LLMs, multi-tenant, quality gate em 5 camadas | — |

## Selected Private Repositories

| Repository | Description |
|---|---|
| [landing-page-geo](https://github.com/alexandrebrt14-sys/landing-page-geo) | alexandrecaramaschi.com — Next.js 16, 122K+ linhas, 35 cursos, 13 portais |
| [brasilgeo-worker](https://github.com/alexandrebrt14-sys/brasilgeo-worker) | brasilgeo.ai — Cloudflare Workers |
| [caramaschi](https://github.com/alexandrebrt14-sys/caramaschi) | Sistema de governança pessoal · WhatsApp 24/7 (Fly.io GRU) · 22 tabelas SQLite · pipeline determinístico keywords→SQLite→LLM |
| [datahub-geo](https://github.com/alexandrebrt14-sys/datahub-geo) | Datahub (grupo Nuvini NASDAQ NVNI) — pesquisa multi-LLM e roadmap GEO B2B |

## Clientes em produção (snapshot · maio 2026)

Operação multi-cliente da Brasil GEO — 5 contratos pagantes ativos:

- **Stone** — Projeto GEO Source Panel Rank (cliente piloto do checker)
- **IPOG** — GEO Psicologia (pós-graduação)
- **Dialetto** — contrato bilateral Source Rank · assinado ClickSign 13 mai
- **Sistema Pacto** — SaaS B2B fitness, 4 pilares GEO
- **Naia.today** — parceria de produto (AI agent for brands)

Em pipeline: Eli Lilly (negociação), UFG · CEIA · SEBRAE PD&I (setup), iMasters · Comunidade Vibe Coding.

## Automation

- **geo CLI** — workspace management: preflight, deploy, health, audit, metrics, status
- **Multi-LLM orchestrator** — 5 LLMs coordenados para research, writing, analysis, classification, review
- **curso-factory** — geração automatizada com quality gate (accent validation, HTML check, link check)
- **Metrics pipeline** — coleta de GA4, GSC, DEV.to, GitHub, sitemap em 11 fontes
- **caramaschi** — assistente operacional 24/7 via WhatsApp (Fly.io GRU) com 22 tabelas SQLite canônicas

## Publishing

| Platform | Profile |
|----------|---------|
| AI Brasil | [Coluna · alexandrecaramaschi](https://aibrasil.com.br/colunista/alexandrecaramaschi) — artigo *LLM Wiki* publicado 26 mai 2026 |
| Medium | [@alexandre.brt14](https://medium.com/@alexandre.brt14) |
| Hashnode | [geo-insider.hashnode.dev](https://geo-insider.hashnode.dev) |
| DEV.to | [alexandrebrt14sys](https://dev.to/alexandrebrt14sys) |
| Substack | [@alexandrecaramaschi](https://substack.com/@alexandrecaramaschi) |

## Ecosystem

| Property | Stack | Status |
|---|---|---|
| [alexandrecaramaschi.com](https://alexandrecaramaschi.com) | Next.js 16 + React 19 + Supabase | Production · 35 cursos · 25 insights · 122K+ linhas |
| [brasilgeo.ai](https://brasilgeo.ai) | Cloudflare Workers | Production · base institucional Brasil GEO |
| [aibrasil.com.br](https://aibrasil.com.br) | — | Coluna autoral ativa |
| [geo-orchestrator](https://github.com/alexandrebrt14-sys/geo-orchestrator) | Python + 5 LLMs | Active · multi-LLM pipeline (140 tests) |
| [curso-factory](https://github.com/alexandrebrt14-sys/curso-factory) | Python + Jinja2 | Active · course generation |
| [papers](https://github.com/alexandrebrt14-sys/papers) | Python + Supabase | Research · LLM citation study |
| [geo-checklist](https://github.com/alexandrebrt14-sys/geo-checklist) | Markdown | Open-source |
| [llms-txt-templates](https://github.com/alexandrebrt14-sys/llms-txt-templates) | Markdown + JSON + Python | Open-source |
| [geo-taxonomy](https://github.com/alexandrebrt14-sys/geo-taxonomy) | JSON + CSV + Markdown | Open-source · 60+ termos |
| [entity-consistency-playbook](https://github.com/alexandrebrt14-sys/entity-consistency-playbook) | Markdown | Open-source |

## Wikidata · Knowledge Graph

- **Person** · [Q138755507](https://www.wikidata.org/wiki/Q138755507)
- **Brasil GEO Tech LTDA (BRGEO LTDA)** · [Q138755989](https://www.wikidata.org/wiki/Q138755989)
- Brasil GEO Tech LTDA · CNPJ 66.051.295/0001-33 · sede Goiânia, GO · NF municipal ativa em NotaGoiânia / ISSNET desde 13 mai 2026

## Connect

- **Website:** [alexandrecaramaschi.com](https://alexandrecaramaschi.com)
- **Empresa:** [brasilgeo.ai](https://brasilgeo.ai) · BRGEO LTDA · Goiânia, GO
- **LinkedIn:** [/in/alexandre-caramaschi](https://linkedin.com/in/alexandre-caramaschi)
- **Coluna:** [AI Brasil](https://aibrasil.com.br/colunista/alexandrecaramaschi)
- **llms.txt:** [alexandrecaramaschi.com/llms.txt](https://alexandrecaramaschi.com/llms.txt) (v19.2)
- **Roadmap GEO Score:** [/ferramentas/geo-score/roadmap](https://alexandrecaramaschi.com/ferramentas/geo-score/roadmap)
- **Press kit:** [/imprensa](https://alexandrecaramaschi.com/imprensa)

---

*Last updated · 27 de maio de 2026*
