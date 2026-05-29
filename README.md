<div align="center">

# 🤖 100 AI Agent Projects

**From zero to autonomous — built with LangChain, LlamaIndex & Ollama.**
*100% free. 100% local. No API keys required.*

[![Stars](https://img.shields.io/github/stars/YOUR_USERNAME/100-ai-agents?style=flat-square&color=4ade80)](https://github.com/YOUR_USERNAME/100-ai-agents/stargazers)
[![Forks](https://img.shields.io/github/forks/YOUR_USERNAME/100-ai-agents?style=flat-square&color=60a5fa)](https://github.com/YOUR_USERNAME/100-ai-agents/network)
[![Progress](https://img.shields.io/badge/Progress-0%20%2F%20100-f59e0b?style=flat-square)](https://github.com/YOUR_USERNAME/100-ai-agents)
[![License](https://img.shields.io/github/license/YOUR_USERNAME/100-ai-agents?style=flat-square)](LICENSE)
[![Follow on X](https://img.shields.io/badge/Follow-%40YOUR__HANDLE-black?style=flat-square&logo=x)](https://x.com/YOUR_HANDLE)

</div>

---

## Why This Repo?

I'm building **100 AI agent projects in public** — starting from a simple CLI chatbot and ending with a fully autonomous meta-agent that builds its own projects.

Every project is:
- ✅ **100% free** — Ollama runs models locally, no OpenAI key needed
- ✅ **Beginner-readable** — clean code, explained in the project README
- ✅ **Progressively harder** — skills compound across all 5 tiers
- ✅ **Copy-paste ready** — clone and run any project in under 5 minutes

---

## Stack

| Tool | Role |
|------|------|
| [Ollama](https://ollama.ai) | Run LLMs locally (LLaMA 3, Mistral, etc.) |
| [LangChain](https://langchain.com) | Agent framework, tools, chains |
| [LlamaIndex](https://llamaindex.ai) | RAG, document indexing, knowledge bases |
| [LangGraph](https://langchain-ai.github.io/langgraph/) | Multi-agent stateful workflows |
| [ChromaDB](https://trychroma.com) | Local vector database |

---

## Quick Start

```bash
# Clone
git clone https://github.com/YOUR_USERNAME/100-ai-agents
cd 100-ai-agents

# Install base deps
pip install -r requirements-base.txt

# Pull a model (free, runs locally)
ollama pull llama3

# Run any project
cd tier1-starter/01-cli-chat-agent
pip install -r requirements.txt
python agent.py
```

→ Full setup guide: [docs/SETUP.md](docs/SETUP.md)

---

## Progress — 0 / 100

### 🟢 Tier 1 — Starter Agents (1–20)
*Single-purpose CLI agents · Stack: Ollama + LangChain basics*

| # | Project | Stack | Description | Status |
|---|---------|-------|-------------|--------|
| 1 | [CLI Chat Agent](tier1-starter/01-cli-chat-agent/) | `Ollama + LangChain` | Terminal chatbot with persistent memory | 📋 Planned |
| 2 | [Journal Summarizer](tier1-starter/02-journal-summarizer/) | `Ollama` | Mood analysis + weekly summary | 📋 Planned |
| 3 | [README Generator](tier1-starter/03-readme-generator/) | `Ollama` | Auto-generate GitHub READMEs | 📋 Planned |
| 4 | [Terminal File Q&A](tier1-starter/04-terminal-file-qa/) | `Ollama` | Ask questions about any local file | 📋 Planned |
| 5 | [Commit Message Writer](tier1-starter/05-commit-message-writer/) | `Ollama` | Clean conventional commits from git diffs | 📋 Planned |
| 6 | [Flashcard Generator](tier1-starter/06-flashcard-generator/) | `Ollama` | Study notes → Anki-style Q&A cards | 📋 Planned |
| 7 | [Recipe Suggester](tier1-starter/07-recipe-suggester/) | `Ollama` | Fridge contents → recipe ideas | 📋 Planned |
| 8 | [Email Tone Rewriter](tier1-starter/08-email-tone-rewriter/) | `Ollama` | Rewrite emails with chosen tone | 📋 Planned |
| 9 | [Debate Practice Bot](tier1-starter/09-debate-practice-bot/) | `Ollama` | Argues the opposite side of any topic | 📋 Planned |
| 10 | [Daily Standup Writer](tier1-starter/10-daily-standup-writer/) | `Ollama` | Input your work → clean standup | 📋 Planned |
| 11 | [Local Dictionary Agent](tier1-starter/11-local-dictionary-agent/) | `Ollama` | Define words fully offline | 📋 Planned |
| 12 | [Bug Explainer](tier1-starter/12-bug-explainer/) | `Ollama` | Paste traceback → plain-English fix | 📋 Planned |
| 13 | [CLI Trivia Agent](tier1-starter/13-cli-trivia-agent/) | `Ollama` | Endless trivia game in the terminal | 📋 Planned |
| 14 | [Code Comment Generator](tier1-starter/14-code-comment-generator/) | `Ollama` | Auto-add docstrings to Python files | 📋 Planned |
| 15 | [Meeting Notes Cleaner](tier1-starter/15-meeting-notes-cleaner/) | `Ollama` | Raw notes → summary + action items | 📋 Planned |
| 16 | [Poem Generator](tier1-starter/16-poem-generator/) | `Ollama` | Mood + theme → poem in chosen style | 📋 Planned |
| 17 | [Baby Name Advisor](tier1-starter/17-baby-name-advisor/) | `Ollama` | Criteria → name suggestions | 📋 Planned |
| 18 | [Local Text Classifier](tier1-starter/18-local-text-classifier/) | `Ollama` | Zero-shot classification into custom categories | 📋 Planned |
| 19 | [Tweet Thread Expander](tier1-starter/19-tweet-thread-expander/) | `Ollama` | Expand a tweet into a full thread | 📋 Planned |
| 20 | [Habit Tracker Coach](tier1-starter/20-habit-tracker-coach/) | `Ollama` | Log habits → weekly analysis | 📋 Planned |

### 🔵 Tier 2 — Tool-Using Agents (21–40)
*Agents that take real actions · Stack: LangChain Tools + LlamaIndex*

| # | Project | Stack | Description | Status |
|---|---------|-------|-------------|--------|
| 21 | [Local File Search](tier2-tools/21-local-file-search/) | `LangChain Tools` | Agent searches filesystem and answers questions | 📋 Planned |
| 22 | [PDF Q&A Agent](tier2-tools/22-pdf-qa-agent/) | `LlamaIndex + Ollama` | Upload PDF, ask anything | 📋 Planned |
| 23 | [Wikipedia Research](tier2-tools/23-wikipedia-research/) | `LangChain + Wikipedia` | Deep research using Wikipedia tool | 📋 Planned |
| 24 | [CSV Data Analyst](tier2-tools/24-csv-data-analyst/) | `LangChain + Pandas` | Upload CSV, get analysis and trends | 📋 Planned |
| 25 | [Web Scraper Agent](tier2-tools/25-web-scraper-agent/) | `LangChain + BS4` | Scrape any URL and summarize content | 📋 Planned |
| 26 | [Calculator Math Solver](tier2-tools/26-calculator-math-solver/) | `LangChain + Python REPL` | Solve math step-by-step with code | 📋 Planned |
| 27 | [Local SQL Agent](tier2-tools/27-local-sql-agent/) | `LangChain + SQLite` | Plain English → SQL on local DB | 📋 Planned |
| 28 | [News Digest Agent](tier2-tools/28-news-digest-agent/) | `LangChain + RSS` | Fetch RSS, cluster by topic, write digest | 📋 Planned |
| 29 | [GitHub Repo Explorer](tier2-tools/29-github-repo-explorer/) | `LangChain + GitHub API` | Ask questions about any public repo | 📋 Planned |
| 30 | [YouTube Transcript Summarizer](tier2-tools/30-youtube-transcript-summarizer/) | `LlamaIndex + Ollama` | Transcript → key takeaways | 📋 Planned |
| 31 | [Weather Report Narrator](tier2-tools/31-weather-report-narrator/) | `LangChain + Weather API` | Human-friendly weather narration | 📋 Planned |
| 32 | [Personal Finance Tracker](tier2-tools/32-personal-finance-tracker/) | `LangChain + Pandas` | Bank CSV → spending breakdown | 📋 Planned |
| 33 | [Job Description Analyzer](tier2-tools/33-job-description-analyzer/) | `LangChain` | Extract skills, red flags, fit score | 📋 Planned |
| 34 | [Recipe Nutrition Calculator](tier2-tools/34-recipe-nutrition-calculator/) | `LangChain` | Ingredients → full nutrition facts | 📋 Planned |
| 35 | [Book Club Agent](tier2-tools/35-book-club-agent/) | `LlamaIndex` | Generate discussion questions from books | 📋 Planned |
| 36 | [Code Review Agent](tier2-tools/36-code-review-agent/) | `LangChain` | Structured feedback on any code | 📋 Planned |
| 37 | [Image Alt Text Generator](tier2-tools/37-image-alt-text-generator/) | `LLaVA (Ollama)` | SEO-optimized alt text from images | 📋 Planned |
| 38 | [Unit Test Writer](tier2-tools/38-unit-test-writer/) | `LangChain` | Function → pytest unit tests | 📋 Planned |
| 39 | [Markdown Blog Publisher](tier2-tools/39-markdown-blog-publisher/) | `LangChain` | Plain text → polished .md blog post | 📋 Planned |
| 40 | [Meeting Scheduler Agent](tier2-tools/40-meeting-scheduler-agent/) | `LangChain + ICS` | Reads calendar, finds optimal slots | 📋 Planned |

### 🟡 Tier 3 — Memory & RAG Agents (41–60)
*Agents that learn and remember · Stack: LlamaIndex + ChromaDB / FAISS*

| # | Project | Stack | Description | Status |
|---|---------|-------|-------------|--------|
| 41 | [Personal Knowledge Base](tier3-memory/41-personal-knowledge-base/) | `LlamaIndex + ChromaDB` | Chat with your own second brain | 📋 Planned |
| 42 | [Long-Term Memory Chatbot](tier3-memory/42-long-term-memory-chatbot/) | `LangChain + ChromaDB` | Chatbot that remembers past conversations | 📋 Planned |
| 43 | [Resume Q&A Agent](tier3-memory/43-resume-qa-agent/) | `LlamaIndex` | Answers recruiter questions from your resume | 📋 Planned |
| 44 | [Codebase Q&A Agent](tier3-memory/44-codebase-qa-agent/) | `LlamaIndex + FAISS` | Ask architecture questions about any codebase | 📋 Planned |
| 45 | [Research Paper Digest](tier3-memory/45-research-paper-digest/) | `LlamaIndex` | Synthesize themes across 10+ papers | 📋 Planned |
| 46 | [Legal Document Analyzer](tier3-memory/46-legal-document-analyzer/) | `LlamaIndex` | Find risky clauses in contracts | 📋 Planned |
| 47 | [Customer FAQ Bot](tier3-memory/47-customer-faq-bot/) | `LlamaIndex` | RAG over product docs for support | 📋 Planned |
| 48 | [Personal Email Assistant](tier3-memory/48-personal-email-assistant/) | `LlamaIndex + ChromaDB` | Draft replies in your writing style | 📋 Planned |
| 49 | [Study Tutor Agent](tier3-memory/49-study-tutor-agent/) | `LlamaIndex` | Index textbook → adaptive quiz + tutor | 📋 Planned |
| 50 | [Podcast Knowledge Agent](tier3-memory/50-podcast-knowledge-agent/) | `LlamaIndex` | Cross-episode questions from transcripts | 📋 Planned |
| 51 | [Documentation Writer](tier3-memory/51-documentation-writer/) | `LlamaIndex` | Reads codebase → full API docs | 📋 Planned |
| 52 | [Competitive Research Agent](tier3-memory/52-competitive-research-agent/) | `LlamaIndex + Scraper` | Index competitors, answer strategy questions | 📋 Planned |
| 53 | [Changelog Generator](tier3-memory/53-changelog-generator/) | `LangChain + Git` | Git log + diffs → human-readable changelog | 📋 Planned |
| 54 | [Policy Compliance Agent](tier3-memory/54-policy-compliance-agent/) | `LlamaIndex` | Check docs against GDPR / HR policies | 📋 Planned |
| 55 | [Wikipedia Graph Agent](tier3-memory/55-wikipedia-graph-agent/) | `LlamaIndex + NetworkX` | Build knowledge graph from Wikipedia | 📋 Planned |
| 56 | [Personalized News Agent](tier3-memory/56-personalized-news-agent/) | `LlamaIndex + ChromaDB` | Learns your interests, curates news | 📋 Planned |
| 57 | [Code Migration Agent](tier3-memory/57-code-migration-agent/) | `LlamaIndex` | Reads old code + docs, helps migrate | 📋 Planned |
| 58 | [Multi-Doc Comparator](tier3-memory/58-multi-doc-comparator/) | `LlamaIndex` | Structured comparison of 2–5 documents | 📋 Planned |
| 59 | [Journal Therapist Agent](tier3-memory/59-journal-therapist-agent/) | `LlamaIndex + ChromaDB` | Identifies patterns and growth from journals | 📋 Planned |
| 60 | [Finetune Dataset Builder](tier3-memory/60-finetune-dataset-builder/) | `LlamaIndex` | Generates clean JSONL training data | 📋 Planned |

### 🟣 Tier 4 — Multi-Agent Systems (61–80)
*Agents coordinating with agents · Stack: LangGraph + LangChain Agents*

| # | Project | Stack | Description | Status |
|---|---------|-------|-------------|--------|
| 61 | [Research Writer Duo](tier4-multiagent/61-research-writer-duo/) | `LangGraph` | Researcher + Writer agents in pipeline | 📋 Planned |
| 62 | [Code Review Pipeline](tier4-multiagent/62-code-review-pipeline/) | `LangGraph` | Planner → Coder → Reviewer → Tester chain | 📋 Planned |
| 63 | [Startup Idea Validator](tier4-multiagent/63-startup-idea-validator/) | `LangGraph` | Market research + competitor + SWOT agents | 📋 Planned |
| 64 | [Blog Factory Pipeline](tier4-multiagent/64-blog-factory-pipeline/) | `LangGraph` | Outline → Draft → Edit → SEO pipeline | 📋 Planned |
| 65 | [Debate Team Simulation](tier4-multiagent/65-debate-team-simulation/) | `LangGraph` | Two agents debate, judge agent scores | 📋 Planned |
| 66 | [Data Analysis Crew](tier4-multiagent/66-data-analysis-crew/) | `LangGraph` | Analyst + Visualizer + Storyteller agents | 📋 Planned |
| 67 | [Job Application Agent](tier4-multiagent/67-job-application-agent/) | `LangGraph` | Tailors resume + cover letter per job | 📋 Planned |
| 68 | [Product Roadmap Builder](tier4-multiagent/68-product-roadmap-builder/) | `LangGraph` | Input → Research → Prioritize → Roadmap | 📋 Planned |
| 69 | [Software Architecture Advisor](tier4-multiagent/69-software-architecture-advisor/) | `LangGraph` | Agents debate architecture for your use-case | 📋 Planned |
| 70 | [Email Campaign Builder](tier4-multiagent/70-email-campaign-builder/) | `LangGraph` | Write + review + subject line variants | 📋 Planned |
| 71 | [Bug Hunt Pipeline](tier4-multiagent/71-bug-hunt-pipeline/) | `LangGraph` | Reader → Hypothesis → Fix → Test Writer | 📋 Planned |
| 72 | [Social Media Manager](tier4-multiagent/72-social-media-manager/) | `LangGraph` | One idea → X, LinkedIn, IG posts | 📋 Planned |
| 73 | [Interview Prep Coach](tier4-multiagent/73-interview-prep-coach/) | `LangGraph` | Interviewer + Evaluator agents with scoring | 📋 Planned |
| 74 | [Trip Planner Crew](tier4-multiagent/74-trip-planner-crew/) | `LangGraph` | Budget + Itinerary + Accommodation agents | 📋 Planned |
| 75 | [OSS Contribution Finder](tier4-multiagent/75-oss-contribution-finder/) | `LangGraph + GitHub API` | Finds GitHub issues matching your skills | 📋 Planned |
| 76 | [Financial Report Analyzer](tier4-multiagent/76-financial-report-analyzer/) | `LangGraph` | Extractor + Analyst + Risk Scorer agents | 📋 Planned |
| 77 | [Course Creator Agent](tier4-multiagent/77-course-creator-agent/) | `LangGraph` | Topic → Curriculum → Lessons → Quiz | 📋 Planned |
| 78 | [Grant Proposal Writer](tier4-multiagent/78-grant-proposal-writer/) | `LangGraph` | Research + Narrative + Budget + Review | 📋 Planned |
| 79 | [Product Hunt Launch Kit](tier4-multiagent/79-product-hunt-launch-kit/) | `LangGraph` | Tagline + description + first comment | 📋 Planned |
| 80 | [LangGraph State Machine](tier4-multiagent/80-langgraph-state-machine/) | `LangGraph` | Visual demo of stateful multi-agent workflow | 📋 Planned |

### 🔴 Tier 5 — Autonomous Agents (81–100)
*Self-directed, real-world capable · Stack: LangGraph + LlamaIndex + Custom Tooling*

| # | Project | Stack | Description | Status |
|---|---------|-------|-------------|--------|
| 81 | [Self-Healing Code Agent](tier5-autonomous/81-self-healing-code-agent/) | `LangGraph + Python REPL` | Writes code, runs it, fixes itself | 📋 Planned |
| 82 | [Autonomous Data Pipeline](tier5-autonomous/82-autonomous-data-pipeline/) | `LangGraph` | Designs and runs its own ETL pipeline | 📋 Planned |
| 83 | [GitHub PR Agent](tier5-autonomous/83-github-pr-agent/) | `LangGraph + GitHub API` | Clones repo, makes changes, creates PR | 📋 Planned |
| 84 | [ReAct Agent Framework](tier5-autonomous/84-react-agent-framework/) | `Custom` | Build your own ReAct loop from scratch | 📋 Planned |
| 85 | [AI Project Manager](tier5-autonomous/85-ai-project-manager/) | `LangGraph` | Breaks goal into tasks, assigns sub-agents | 📋 Planned |
| 86 | [Autonomous Research Synthesizer](tier5-autonomous/86-autonomous-research-synthesizer/) | `LangGraph + LlamaIndex` | Searches web, reads papers, writes report | 📋 Planned |
| 87 | [Personal AI OS](tier5-autonomous/87-personal-ai-os/) | `LangGraph` | Central agent routing to specialized sub-agents | 📋 Planned |
| 88 | [Self-Improving Prompt Agent](tier5-autonomous/88-self-improving-prompt-agent/) | `LangGraph` | Tests its own prompts, improves iteratively | 📋 Planned |
| 89 | [Open Interpreter Clone](tier5-autonomous/89-open-interpreter-clone/) | `LangGraph + Shell` | Executes Python, bash, file ops autonomously | 📋 Planned |
| 90 | [Local AutoGPT Clone](tier5-autonomous/90-local-autogpt-clone/) | `LangGraph + ChromaDB` | Goal-driven autonomous agent with memory | 📋 Planned |
| 91 | [AI SaaS Scaffolder](tier5-autonomous/91-ai-saas-scaffolder/) | `LangGraph` | Describe app → full project structure + code | 📋 Planned |
| 92 | [Automated Testing Agent](tier5-autonomous/92-automated-testing-agent/) | `LangGraph + Playwright` | Reads app, writes E2E tests, runs them | 📋 Planned |
| 93 | [Knowledge Graph Builder](tier5-autonomous/93-knowledge-graph-builder/) | `LlamaIndex + NetworkX` | Reads docs → entity-relationship graph | 📋 Planned |
| 94 | [Multi-Agent Debate Optimizer](tier5-autonomous/94-multi-agent-debate-optimizer/) | `LangGraph` | Agents refine answers until best result | 📋 Planned |
| 95 | [AI Business Analyst](tier5-autonomous/95-ai-business-analyst/) | `LangGraph + LlamaIndex` | Weekly BI reports from company data | 📋 Planned |
| 96 | [Recursive Summarizer](tier5-autonomous/96-recursive-summarizer/) | `LlamaIndex` | Handles book-length inputs with nested summaries | 📋 Planned |
| 97 | [Agentic RAG Self-Correction](tier5-autonomous/97-agentic-rag-self-correction/) | `LlamaIndex + LangGraph` | RAG that checks and reruns if wrong | 📋 Planned |
| 98 | [LLM Benchmark Runner](tier5-autonomous/98-llm-benchmark-runner/) | `Custom` | Auto-runs and compares local models on evals | 📋 Planned |
| 99 | [Agent Observatory Dashboard](tier5-autonomous/99-agent-observatory-dashboard/) | `LangGraph + Streamlit` | Real-time agent thoughts/tools/steps dashboard | 📋 Planned |
| 100 | [The Meta-Agent](tier5-autonomous/100-the-meta-agent/) | `LangGraph + LlamaIndex` | Reads this repo and builds the next project | 📋 Planned |

---

## Repo Structure

```
100-ai-agents/
├── tier1-starter/      # Projects 01–20 · Ollama + LangChain
├── tier2-tools/        # Projects 21–40 · LangChain Tools + LlamaIndex
├── tier3-memory/       # Projects 41–60 · RAG + ChromaDB / FAISS
├── tier4-multiagent/   # Projects 61–80 · LangGraph multi-agent
├── tier5-autonomous/   # Projects 81–100 · Autonomous agents
├── shared/             # Reusable helpers (LLM loader, memory, tools)
├── docs/               # Setup guide, contributing, roadmap
└── requirements-base.txt
```

Each project folder contains:
```
##-project-name/
├── agent.py         # Main agent code
├── requirements.txt # Project-specific deps
├── README.md        # What it does, how to run, demo
└── .env.example     # Env variable template
```

---

## Follow Along

I'm building this **one project at a time, in public.**

- 𝕏 Twitter: [@YOUR_HANDLE](https://x.com/YOUR_HANDLE) — daily build logs
- LinkedIn: [/in/YOUR_PROFILE](https://linkedin.com/in/YOUR_PROFILE) — weekly breakdowns
- GitHub: ⭐ Star this repo to follow progress

---

## License

MIT — use anything here freely. A star is appreciated! ⭐

---

<div align="center">
  <sub>Built with ❤️ and a lot of <code>ollama run llama3</code></sub>
</div>
