# Nick Comeaux

Systems engineer at Boeing, with industrial engineering at Tesla before that. On
my own time I build software with AI to learn: systems that keep model judgment
behind deterministic code and a human approval step, so automation stays
reliable.

## Selected work

**[Holon](https://github.com/Ncomeaux3/holon)** - my personal operating system, a solo side project I use
every day. Claude reaches it through an MCP server I built, and every change the
model wants is held as a proposal with a diff and a confidence score until I
approve it. Hybrid search (pgvector embeddings plus full-text), and every model
call is logged and capped by monthly cost.

**Soltreya** - a solo side project (Mar to Jun 2026): AI quality management for
regulated manufacturers. No customers; I stopped building it in June. Architected the WAT framework (Workflows, Agents,
Tools): markdown SOP workflows + deterministic Python tools + a Claude orchestrator
that classifies each request and routes it to one of seven specialist agents. The
design keeps AI in a scoped reasoning role so chained model steps don't compound
error.

**Boeing Intelligence & Analytics** - Systems Engineer II. Designed the program's
Authoritative Data Source across three partner companies and cut executive
briefing-prep time by 67%. Shipped a live integration-risk dashboard used by chief
engineers across three companies and six government organizations.

**Tesla** - Industrial engineering. Identified dock-allocation and delivery-route
changes worth several million dollars in savings and OPEX reduction and freed
16,000 sq ft of floor space; built material-flow models for three shops covering
250+ parts.

## Featured

- **[bellwether](https://github.com/Ncomeaux3/bellwether)** - open archive of
  developer-infrastructure pricing, built in four days. A TypeScript pipeline
  collected 27 public pricing pages, Claude extracted structured prices, changes
  were confirmed across two observations, and Claude wrote a cited weekly
  digest. [Live board](https://bellwether-nicholas-projects-cdfeb046.vercel.app).
  Not running since August 2026.
- **[nickcomeaux-site](https://github.com/Ncomeaux3/nickcomeaux-site)** - source for
  my personal site (static, fast, 100 Lighthouse).
- **[wat-demo](https://github.com/Ncomeaux3/wat-demo)** - minimal reference
  implementation of the Workflows + Agents + Tools pattern.

## Stack

- **AI & agents:** Claude API (Anthropic), multi-agent orchestration, prompt
  engineering, Trigger.dev
- **Languages:** Python, TypeScript, SQL
- **Web:** Next.js, React, Vercel, Postgres (Supabase), Drizzle ORM
- **Systems & modeling:** systems engineering, Scrum/Agile, Qlik Sense; AutoCAD,
  Revit, Excel VBA

## Background

B.S. Industrial and Systems Engineering, Texas A&M University. Lean Six Sigma Green Belt.

## Contact

- Site: nicholascomeaux.com
- LinkedIn: linkedin.com/in/nicholas-comeaux
- Email: nicholascomeaux00@gmail.com
