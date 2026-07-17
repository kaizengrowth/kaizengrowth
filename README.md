# Hi, I'm Katie Z. Albasi 👋

**Software engineer, AI researcher in training, technical consultant, and educator.** I build production AI for government and community programs, and I teach engineers to build them responsibly.

[![Website](https://img.shields.io/badge/kaizencode.art-portfolio-2ea44f?style=flat&logo=safari&logoColor=white)](https://kaizencode.art)
[![Email](https://img.shields.io/badge/email-kaitlin.zhang%40owasp.org-blue?style=flat&logo=gmail&logoColor=white)](mailto:kaitlin.zhang@owasp.org)
[![OWASP](https://img.shields.io/badge/OWASP-AI%20Red%20Teaming%20Guide-black?style=flat&logo=owasp)](https://owasp.org)

---

## 🔭 What I do

- **Production AI for government benefits**: document intelligence, multilingual conversational AI, fraud-signal detection, bias testing, and high-availability payments infrastructure for state benefits programs (Michigan, Colorado) at AidKit.
- **Evaluation & safety**: human-in-the-loop eval harnesses, agentic RAG observability, LLM red teaming (OWASP).
- **Technical education**: curriculum development and hands-on technical education, building labs with telemetry and custom AI-enabled production learning platforms, grounded in andragogy and heutagogy (backward design, constructive alignment, ATD, Kirkpatrick evaluation).

## 🌱 Current work & research

- **[What We Will](https://github.com/What-We-Will)**: building a community platform that connects laid-off workers to legal, healthcare, and job-search resources. Piloting an evaluated agentic RAG system for labor-law citations. Repo: [layoff-qa-pipeline](https://github.com/kaizengrowth/layoff-qa-pipeline).

- **AI safety research (in progress, first-author publication, 2026)**: measuring whether post-training quantization and GGUF compression widen the MultiJail high- vs low-resource jailbreak gap (Δ_HL) on open-weight models, under matched decoding and a dual-judge ASR protocol, alongside layer-localized safety interventions at the transformer-layer level. Repo: [quant-multilingual-safety](https://github.com/kaizengrowth/quant-multilingual-safety).

- **AI & labor policy research (in progress, 2026)**: collaborating with TechEquity on a study of survey data from tech workers about how generative AI is changing their roles, skills, and job quality.

## 📚 Learning lately

- **Newline AI Research Track**
  - Implementing decoder-only Transformers in PyTorch: multi-head self-/cross-attention, RMSNorm/LayerNorm residuals, SwiGLU FFNs, RoPE, and KV-cache; pretraining GPT-2 124M with DDP and gradient accumulation
  - PEFT instruction tuning with Hugging Face PEFT: LoRA/DoRA, BitFit, and prompt tuning for domain and format control
  - Embedding and multimodal adaptation: CLIP-style alignment, triplet and contrastive losses, and hard-negative mining
  - Preference and RL post-training: SFT into RLHF/PPO critic-actor loops, DPO, and GRPO / Dr. GRPO / GiGPO with group-relative advantages, KL-to-reference regularization, and Math-Verify-style verifiable rewards
  - Layer-localized safety methods: freeze-all-but-k GRPO with layer contribution C(k); Safety Layers / SPPFT (freeze middle refusal layers under capability fine-tuning); ESI/SET/SPA sparse safety-critical updates (~1% of weights); Arditi-style refusal-direction ablation and addition in the residual stream
  - Systems context for eval harnesses: MoE routing, agent tool-use loops, Graph and multi-hop RAG; retrieval stacks (Hugging Face, DSPy, LangGraph); production reliability (SRE SLOs, model orchestration mixing multi-model cloud and local LLMs for cost optimization)

## 📌 Featured repositories

| Repo | Details |
|---|---|
| [**What We Will**](https://github.com/What-We-Will) | Community platform for laid-off workers: resource matching, peer support, and an evaluated legal-citation chatbot. *TypeScript, agentic RAG, human-in-the-loop evals.* |
| [**CivicSpark AI**](https://github.com/kaizengrowth/CivicSpark_AI) | AI document assistant for Tulsa city government: parsing and translating ordinances, budgets, and Council minutes with SMS/email alerts. Built with the Tulsa City Auditor's Office; user-tested with 80+ city staff, community organizations, and local residents. *Python, RAG, civic tech.* |
| [**MultiAgentEDUstack**](https://github.com/kaizengrowth/MultiAgentEDUstack) | Eight-stage multi-agent curriculum pipeline that sources AI research and news, tiers credibility, and scaffolds digests, wiki pages, lessons, and labs to keep ahead of a fast-moving field. *Python, SQLite, Claude Code skills, Next.js desk.* |
| [**quant-multilingual-safety**](https://github.com/kaizengrowth/quant-multilingual-safety) | Measurement study on whether PTQ/GGUF widens MultiJail high- vs low-resource jailbreak ASR (Δ_HL), with layer-localized safety methods in scope. *Python, quantization, multilingual safety eval.* |
| [**evaStudio**](https://github.com/oslabs-beta/evaStudio) ⭐ | Apache Kafka monitoring tool for prototyping real-time streaming pipelines and testing parallelization of multi-stage ML models before production. *TypeScript, distributed systems, observability.* |

## 🎓 Background

M.S. Computer Science, **UPenn** · Post-grad certificate in Machine Learning & AI, **MIT** · MPA-BA Data Science for Public Policy, **NYU** (Reynolds Fellow) · A.B. Mathematics-Economics, **Columbia** (Centennial Scholar)

---

💬 Reach me at [kaitlin.zhang@owasp.org](mailto:kaitlin.zhang@owasp.org) or [kaizencode.art](https://kaizencode.art).
