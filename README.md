# Hi, I'm Katie Z. Albasi 👋

**Software engineer, AI researcher in training, technical consultant and educator. I build production AI systems for government and community programs, and I teach engineers how to build them responsibly.**

[![Website](https://img.shields.io/badge/kaizencode.art-portfolio-2ea44f?style=flat&logo=safari&logoColor=white)](https://kaizencode.art)
[![Email](https://img.shields.io/badge/email-kaitlin.zhang%40owasp.org-blue?style=flat&logo=gmail&logoColor=white)](mailto:kaitlin.zhang@owasp.org)
[![OWASP](https://img.shields.io/badge/OWASP-AI%20Red%20Teaming%20Guide-black?style=flat&logo=owasp)](https://owasp.org)

---

## 🔭 What I do

My work sits at the intersection of **AI engineering, public-interest technology, and AI safety research**:

- **Production AI for government benefits**: document intelligence, multilingual conversational AI, fraud-signal detection, and high-availability payments infrastructure for state benefits programs (Michigan, Colorado) at AidKit, in partnership with OpenAI. 🏆 *Gold, "Best Use of Artificial Intelligence," 2025 Globee Awards for Impact; GitLab Foundation AI for Economic Mobility grantee.*

- **AI evaluation & observability**: human-in-the-loop evaluation harnesses, trace-level monitoring, llm redteaming, and continuous oversight for agentic RAG systems.

- **Technical education at scale**: designed and launched AI-engineering curricula as Managing Lead Instructor at Stride (team of 9) and as an enterprise AI consultant for Pluralsight. I've also taught and mentored adult learners at Per Scholas, Future Code, and other workforce programs. My practice is grounded in andragogy and heutagogy (self-directed, experience-driven learning) for working adults, using backward design, constructive alignment, and competency-based instructional design. Certified in pedagogy and curriculum design, with a focus on scaffolding complex technical skills, formative assessment, and transfer of learning into building custom telemetry-enabled cloud labs and AI-enabled learning platforms in production.

## 🌱 Current work & research

- **Founder/Senior Engineer, [What We Will](https://github.com/What-We-Will)**: a community platform to connect laid-off workers to legal and healthcare resources and job search supports. Building an evaluated agentic RAG system for labor-law citations and an AI upskilling program run by 38 volunteers.
- **AI safety research (in progress, 2026)**: measuring whether post-training quantization and GGUF compression widen the MultiJail high- vs low-resource jailbreak gap (Δ_HL) on open-weight models, alongside layer-localized safety interventions at the transformer-layer level. Repo: [quant-multilingual-safety](https://github.com/kaizengrowth/quant-multilingual-safety).
- **AI & labor policy research (in progress, 2026)**: collaborating on a study with TechEquity analyzing survey data from tech workers on AI-driven change in their roles.
## 📚 Learning lately

- **Newline AI Research Track**
  - Decoder-only Transformers from scratch in PyTorch: multi-head self-/cross-attention, RMSNorm/LayerNorm residuals, SwiGLU FFNs, RoPE, KV-cache, GPT-2 124M pretraining with DDP + gradient accumulation
  - PEFT instruction tuning: LoRA/DoRA, BitFit, prompt tuning via Hugging Face PEFT
  - Embedding / multimodal adaptation: CLIP alignment, triplet + contrastive loss, hard-negative mining
  - Preference / RL post-training: SFT → RLHF/PPO critic-actor loops, DPO, GRPO / Dr. GRPO / GiGPO group-relative advantages, KL-to-ref, Math-Verify-style verifiable rewards
  - Layer-localized safety methods: freeze-all-but-k GRPO with layer contribution C(k); Safety Layers / SPPFT (freeze middle refusal layers under capability FT); ESI/SET/SPA (SNIP-style safety-critical sparse updates ≈1% of weights); Arditi-style refusal-direction ablation/addition in the residual stream
  - Systems context for eval harnesses: MoE routing, agent tool-use loops, Graph/multi-hop RAG

- **Advanced retrieval & agentic systems**: multi-vector indexing, late-interaction retrieval, multimodal RAG over text/images/tables, tool-augmented reasoning, and AI-centric evaluation; production systems with Hugging Face, DSPy, LangChain, LangGraph, CrewAI, and Modal.

- **Production reliability**: Google's SRE canon (SLOs, error budgets, toil) and modern Java (17/21 records, sealed types, virtual threads) with Spring Boot slice testing and Testcontainers.

## 📌 Featured repositories

| Repo | Details |
|---|---|
| [**What We Will**](https://github.com/What-We-Will) | Production crisis-support platform for laid-off workers: resource matching, peer-support grouping, evaluated legal-citation chatbot. *TypeScript, agentic RAG, human-in-the-loop evals.* |
| [**CivicSpark AI**](https://github.com/kaizengrowth/CivicSpark_AI) | AI document assistant for Tulsa city government: parsing/translating ordinances, budgets, and Council minutes with SMS/email alerts. Built with the Tulsa City Auditor's Office; user-tested with 80+ government staff and residents. *Python, RAG, civic tech.* |
| [**MultiAgentEDUstack**](https://github.com/kaizengrowth/MultiAgentEDUstack) | Multi-agent curriculum pipeline that sources AI research/news, tiers credibility, and scaffolds digests, wiki, lessons, and labs at model speed. *Python, SQLite, Claude Code skills, Next.js desk.* |
| [**quant-multilingual-safety**](https://github.com/kaizengrowth/quant-multilingual-safety) | Does PTQ/GGUF widen Multilingual jailbreak ASR gaps across resource tiers? Phase A measurement study (MultiJail × precision arms). *Python, quantization, safety eval.* |
| [**machine_learning_projects**](https://github.com/kaizengrowth/machine_learning_projects) | ML coursework at M.I.T. with experiments in Python ML libraries. *Jupyter, scikit-learn, exploratory work.* |
| [**oulipo_package**](https://github.com/kaizengrowth/oulipo_package) | Python NLP library for constraint-based poetry (built for SFPC), packaged and published to GitHub Container Registry. *Python packaging, NLP, creative computation.* |
| [**evaStudio**](https://github.com/oslabs-beta/evaStudio) ⭐ 58 | Apache Kafka monitoring tool for prototyping real-time streaming pipelines and testing parallelization of multi-stage ML models pre-production. *TypeScript, distributed systems, observability.* |

## 🛠️ Toolbox

**AI/ML:** LLM evaluation harnesses · RAG & agentic workflows · MCP · OpenAI & Anthropic APIs · open-weight models (Ollama) · NLP (spaCy, NLTK) · audio ML (Librosa) · model quantization & distillation (GPTQ, AWQ, GGUF, LoRA/QLoRA) · fine-tuning & preference optimization (RLHF, DPO, PPO)

**Responsible AI & safety:** AI red teaming (OWASP) · adversarial probing & jailbreak testing · safety guardrails (input/output filtering, policy enforcement, layer-localized interventions) · bias & fairness testing · toxicity & harm evaluation · alignment & refusal behavior analysis · human-in-the-loop oversight · evaluation-driven development for nondeterministic systems

**Languages & frameworks:** Python · TypeScript/JavaScript · Java (Spring Boot) · React · FastAPI · Node

**Data & infra:** AWS (primary) · Docker · Pulumi · Jenkins & GitHub Actions CI/CD · Airflow · Kafka · Spark · Linux · payments infrastructure

**Practices:** TDD & pairing · human-centered design · Scrum Alliance certified · PMI trained · SAFe Agile · modular contracting · USDS/18F-style delivery · scenario-driven development · policy toggles / de-risking government software

**Compliance & accessibility:** FedRAMP (incl. AWS GovCloud) · ATO · FISMA · NIST SP 800-53 · NIST AI RMF · ISO 27001 · Section 508 / WCAG 2.1 AA · USWDS · HIPAA / PII / PHI · responsible AI governance

**Health IT & geospatial:** QRDA-III · QPP/MIPS · eCQM · OGC open geospatial standards


## 🎓 Background

M.S. Computer Science, **UPenn** · Post-grad certificate in ML & AI, **MIT** · MPA-BA Data Science for Public Policy, **NYU** (Reynolds Fellow) · A.B. Mathematics-Economics, **Columbia** (Centennial Scholar)

---

💬 Open to conversations about AI evaluation, gov-tech, responsible AI deployment, and technical education. Reach me at [kaitlin.zhang@owasp.org](mailto:kaitlin.zhang@owasp.org) or check out my personal blog at [kaizencode.art](https://kaizencode.art).
