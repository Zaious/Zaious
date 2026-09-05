<!--
  GitHub profile README for github.com/Zaious  (repo: Zaious/Zaious, file: README.md)
  Draft 2026-09-05 — every number/status below comes from the public dossier view
  (M:\ChronicleCore-Forge\dossier, view=public). Re-derive before editing; do not hand-tune facts.
  Deliberately absent: target journals of preprints, anything under anonymous review, Tier-3 surfaces.
  Ruling 2026-09-05: kinkref.org is NOT listed here — the ZAIOUS (Tier 2) profile must not link to Tier 3
  (dossier OPSEC_PSEUDONYMITY §1). Do not add it back even though the public dossier view carries the project.
  GitHub bio (settings page, owner-only) agreed 2026-09-05: "Building agent governance for multi-agent systems."
-->

<h1 align="center">Zaious · Meng-Han (Martin) Lee</h1>

<p align="center">
  Generative-AI solutions consultant by day · multi-agent systems researcher by conviction · Taiwan<br/>
  <sub>生成式 AI 解決方案顧問／多代理系統研究者——把自己運行的系統寫成論文，再拿論文回頭改系統。</sub>
</p>

<p align="center">
  <a href="https://zaious.dev">zaious.dev</a> ·
  <a href="https://www.linkedin.com/in/zaious-lee">LinkedIn</a> ·
  <a href="https://orcid.org/0009-0007-1685-0877">ORCID</a> ·
  <a href="https://scholar.google.com/citations?user=PksCWTMAAAAJ">Google Scholar</a>
</p>

> *Information flows endlessly. Chronicle anchors what matters.*

---

## What I'm building

Three private systems. None of them is on GitHub; what they produce is — each line ends with the public
evidence you can actually open.

**ChronicleCore** — the whole thing: a governance-first multi-agent system I run daily, 39 specialist agents
under a five-pillar governance model (strategy / intelligence / aesthetics / execution / defence), with MCP as
the hard boundary between LLM reasoning and tool execution. Everything below runs inside it.
→ [architecture whitepaper](https://github.com/Zaious/ChronicleCore-Architecture) · [ASAF, the framework the operating experience became](https://doi.org/10.3389/fcomp.2026.1860996)

**Chronicle-Ark** — the multi-agent IDE the agents actually live in, including the *paper room* where research
gets written under explicit AI disclosure: core ideas from the human, execution delegated, boundary stated on
the page. → every paper and preprint under *Research* · [riftbound-chronicle](https://github.com/Zaious/riftbound-chronicle) was built there

**sovereign-dossier → biography** — a single source of truth for my own facts (roles, projects, papers, with
provenance and visibility rules), exported as a brief for agents and as a résumé pipeline, both over MCP.
→ every number and status on this page is derived from it, not typed in

[![ChronicleCore-Architecture](https://img.shields.io/github/stars/Zaious/ChronicleCore-Architecture?style=flat&label=ChronicleCore-Architecture%20%E2%98%85)](https://github.com/Zaious/ChronicleCore-Architecture)

## Open source

| | What it is | |
|---|---|---|
| **[Antigravity: Skills Chronicle](https://github.com/Zaious/Antigravity-Skills-Chronicle)** | VS Code extension — a visual dashboard for managing AI-agent skills. | ![stars](https://img.shields.io/github/stars/Zaious/Antigravity-Skills-Chronicle?style=flat) ![downloads](https://img.shields.io/open-vsx/dt/ChronicleCore/antigravity-skills-chronicle?style=flat&label=Open%20VSX) |
| **[translate-academic-paper](https://github.com/Zaious/translate-academic-paper)** | Turns a paper PDF into a self-contained bilingual HTML (original / 中文 / side-by-side), with OCR fallback and a verified glossary. | ![stars](https://img.shields.io/github/stars/Zaious/translate-academic-paper?style=flat) |
| **[journal-atlas](https://github.com/Zaious/journal-atlas)** | Submission advisor that reasons over real journal metadata (399 curated entries) instead of model recall. Also an agent skill. | ![stars](https://img.shields.io/github/stars/Zaious/journal-atlas?style=flat) |
| **[PhilosopherAtlas](https://github.com/Zaious/PhilosopherAtlas)** | Interactive map of 235 philosophers across history and cultures, bilingual. [Live](https://philosopheratlas.chroniclecore.com/) | ![stars](https://img.shields.io/github/stars/Zaious/PhilosopherAtlas?style=flat) |
| **[riftbound-chronicle](https://github.com/Zaious/riftbound-chronicle)** | Preparation-phase AI for the Riftbound TCG — deck coach, cited rules consult, and a human-confirmed Player 2 agent — on a sovereign rules core that fails closed on anything it can't model. Not a simulator, not a judge. [Live](https://riftbound-agent.chroniclecore.com/) | ![stars](https://img.shields.io/github/stars/Zaious/riftbound-chronicle?style=flat) |
| **[taiwan-md](https://github.com/Zaious/taiwan-md)** | Open-source curated knowledge base about Taiwan for LLMs — co-maintainer. [taiwan.md](https://taiwan.md) | ![stars](https://img.shields.io/github/stars/Zaious/taiwan-md?style=flat) |
| **[PTT-Alertor-Discord](https://github.com/Zaious/PTT-Alertor-Discord)** | Discord bot that watches PTT boards for keywords and posts rich embeds. | ![stars](https://img.shields.io/github/stars/Zaious/PTT-Alertor-Discord?style=flat) |

## Things people actually use

- **[Riftbound 編年史](https://riftbound.chroniclecore.com/)** — Taiwan's player intelligence site for the Riftbound TCG. 8–10k page views a day, ~1,150 daily clicks from search, most content drafted by an agent skill and curated by hand.
- **[Riftbound Agent](https://riftbound-agent.chroniclecore.com/)** — the rules-engine side of the same project as a free tool: card database with full rules text, deck builder with import and legality checking; rules assistant and deck coaching next. Built on riftbound-chronicle above, not on a chatbot.
- **[SummonLibrary 喚書者](https://summonlibrary.chroniclecore.com)** — book search across Taiwanese second-hand inventories, with an MCP server.
- **[AChanGer 朱藏](https://achanger.chroniclecore.com)** — anime merch intel and card-exchange tool.
- **[Journal Atlas](https://journal-atlas.chroniclecore.com)** — the hosted version of the submission advisor above.

## Research

One question, asked three ways: **how designed interaction constitutes the human** — a philosophy-of-interaction
axis, a sociology-of-interaction axis (agents as social actors), and a psychology axis. Practice first: I design,
deploy, and live inside the systems, then write the theory and check it against them.

- **Agentic Social Affordance Framework (ASAF)** — *Frontiers in Computer Science* (Human-Media Interaction), 2026. Agent identity design as the collaboration interface in multi-agent systems. [doi:10.3389/fcomp.2026.1860996](https://doi.org/10.3389/fcomp.2026.1860996)
- **Toward a Philosophy of Interaction** — preprint, Zenodo. [doi:10.5281/zenodo.21225988](https://doi.org/10.5281/zenodo.21225988)
- **Idiosyncratic Cognitive Amplification** — preprint, Zenodo. [doi:10.5281/zenodo.20436631](https://doi.org/10.5281/zenodo.20436631)
- **Before "How to Use It": Locating Generative AI in the Teaching-Learning Structure** — preprint, SSRN, co-authored with a philosopher of education. [doi:10.2139/ssrn.7278438](https://doi.org/10.2139/ssrn.7278438)
- **2026 conference papers (accepted):** two at the Taiwan Association for Information Society annual conference (companion-AI holding effects; accountability in human-in-the-loop multi-agent systems), one at the Taiwan Philosophical Association's "Technology, Craft, and Public Philosophy" (AI Philosophy in Taiwan panel), and one at IEEE BMEiCON 2026 on sensor-embedded props for elderly day care (second author).
- Earlier: VR metaverse podcasts, *IEEE ICCE-TW 2022*; M.S. Interaction Design, NTUT.

**How the writing gets done.** Under explicit disclosure, with a multi-agent AI collaboration setup I built myself.
The rule I hold to: core ideas must originate from the human author; execution may be delegated. It has passed
peer review with that disclosure on the page.

## Around since the early days

- **2016** — founded and moderated PTT's VR board the year the first Vive shipped; first individual member of Taiwan's VR/AR industry association (TAVAR).
- **2022** — founded PTT's AI_Art board the year ChatGPT launched, writing and enforcing the rules for generated content before any platform had them.
- **2023–** — generative-AI solutions consultant at dentsu Taiwan: 5+ enterprise PoCs, an AI-literacy programme for 1,000+ staff, government-approved lecturer under Taiwan's SME digital-transformation schemes.
- **2026–** — CTO at Lumo, an elder-care AIoT startup; the long-term-care papers above come from that line.

<!-- Optional stats card; remove if you'd rather keep the page static:
<p align="center"><img src="https://github-readme-stats.vercel.app/api?username=Zaious&show_icons=true&hide_title=true&hide_rank=true" alt="GitHub stats" /></p>
-->
