<div align="center">

# Sachin Suresh

**AI / ML Engineer** &nbsp;·&nbsp; Bengaluru, India

<sub>Agentic runtimes, retrieval systems, and the infrastructure underneath them.</sub>

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-1e293b?style=flat-square&logo=github&logoColor=e2e8f0)](https://github.com/Sachin-0001)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-1e293b?style=flat-square&logo=linkedin&logoColor=e2e8f0)](https://www.linkedin.com/in/sachin-suresh-06782b300/)
[![Portfolio](https://img.shields.io/badge/Portfolio-1e293b?style=flat-square&logo=vercel&logoColor=e2e8f0)](YOUR_PORTFOLIO_URL)
[![Email](https://img.shields.io/badge/Email-1e293b?style=flat-square&logo=gmail&logoColor=e2e8f0)](mailto:sachin.samprit@gmail.com)

</div>

<br/>

---

<br/>

I write the loop before I reach for the framework. Most of what I build sits where model behaviour meets systems engineering: how a reasoning loop actually terminates, why a retriever surfaces the wrong chunk, what a tool-calling agent does when the tool fails. Frameworks abstract away exactly the part worth understanding, so I tend to implement it once by hand first.

```
llm systems
│
├─ agents ......... planning loops, tool calling, safeguard models
├─ retrieval ...... chunking, embeddings, reranking, citations
├─ models ......... fine-tuning, quantization, evaluation
├─ serving ........ FastAPI services, queues, streaming, tracing
└─ infra .......... containers, CI gates, cloud deploys
```

<br/>

---

<br/>

## projects

### Harness
**A tool-calling agent runtime, written without a framework.**

No LangGraph, no AutoGPT. Six tools (web search, weather, calculator, sandboxed code execution, file I/O, email) wired into a bounded reasoning loop, with a second model screening inputs, tool calls, and outputs before anything executes. Memory is two-tier: an LLM-distilled episodic log feeding a 384-dim FAISS index for recall across sessions.

`Python` · `LangChain` · `Groq` · `FAISS` · `HuggingFace`

[![Source](https://img.shields.io/badge/source-1e293b?style=flat-square&logo=github&logoColor=e2e8f0)](https://github.com/Sachin-0001/HARNESS_REPO)

<br/>

### UnBind
**Legal contract analysis with verifiable citations.**

Ingests PDFs, DOCX, and photographed contracts, then fans out clause-by-clause risk analysis in parallel with live progress over SSE. The Q&A engine anchors every answer to character offsets in the source document, so claims can be checked rather than trusted. Payments hardened with HMAC-SHA256 verification and atomic quota enforcement, behind a 299-test suite gated in CI by ruff, eslint, tsc, and secret scanning. Ships as a web app and an npm CLI.

`Next.js 15` · `FastAPI` · `MongoDB` · `ChromaDB` · `Groq` · `Razorpay`

[![Live](https://img.shields.io/badge/live-1e293b?style=flat-square&logo=vercel&logoColor=e2e8f0)](https://unbindai.vercel.app)
[![Source](https://img.shields.io/badge/source-1e293b?style=flat-square&logo=github&logoColor=e2e8f0)](https://github.com/Sachin-0001/UNBIND_REPO)
[![npm](https://img.shields.io/badge/npm-1e293b?style=flat-square&logo=npm&logoColor=e2e8f0)](https://www.npmjs.com/package/@sachin-0001/unbind)

<br/>

### Parameter-Efficient Fine-Tuning
**Adapting 7B models on a single GPU budget.**

QLoRA on Mistral-7B-Instruct-v0.2 over an Alpaca-style instruction set: 41.94M trainable parameters, 0.57% of 7.28B, under 4-bit quantization and tracked end to end with MLflow. A second run applied LoRA at r=16 to Qwen2.5-1.5B-Instruct for conversational generation, touching 0.28% of parameters.

`PyTorch` · `PEFT` · `QLoRA` · `MLflow` · `HuggingFace`

<br/>

---

<br/>

## open source

Contributing to **[headlamp-k8s/plugins](https://github.com/headlamp-k8s/plugins)**, the plugin ecosystem for the Kubernetes web UI, as part of LFX Mentorship Term 3. Work so far spans a cert-manager expiry display fix, secret redaction in the AI assistant plugin, and accessibility improvements to dashboard charts.

<br/>

---

<br/>

## stack

```
languages     Python · TypeScript · Go · C++

agentic/llm   LangGraph · LangChain · LangSmith · HuggingFace
              Groq · Ollama · n8n

ml            PyTorch · scikit-learn · NumPy · Pandas · OpenCV
              PEFT/QLoRA · MLflow

backend       FastAPI · Pydantic · Next.js

data          PostgreSQL · MongoDB · Redis · ChromaDB · FAISS

cloud         AWS · Docker · GitHub Actions · Airflow · Vercel
```

<br/>

---

<br/>

## experience

**Capmob Financial Services** — Lead AI Engineer Intern &nbsp;·&nbsp; <sub>Jun 2026 – Present</sub>

**XTrail Consulting Services** — Junior Developer Intern &nbsp;·&nbsp; <sub>Jan 2026 – Jun 2026</sub>

<sub>Both under NDA. Happy to discuss approach and trade-offs, not internals.</sub>

<br/>

---

<br/>

## background

**B.E. Computer Science**, Dayananda Sagar College of Engineering &nbsp;·&nbsp; <sub>2023 – 2027</sub>

Co-authored a paper on legal language simplification with LLMs. Runner-up at BotCraft 2024 among 100+ teams. CodeChef 100-day streak, peak 1210; LeetCode 50 and 100-day badges.

<br/>

---

<br/>

## activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Sachin-0001&theme=github-compact&hide_border=true&area=true&bg_color=0d1117&color=94a3b8&line=475569&point=e2e8f0" width="100%" alt="Contribution graph" />

<br/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Sachin-0001&theme=github_dark" height="170" alt="Stats" />
&nbsp;
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Sachin-0001&theme=github_dark" height="170" alt="Languages" />

</div>

<br/>

---

<br/>

<div align="center">

<sub>Open to work on agentic systems, LLM infrastructure, and applied ML research.</sub>

<br/><br/>

[![Email](https://img.shields.io/badge/sachin.samprit@gmail.com-1e293b?style=flat-square&logo=gmail&logoColor=e2e8f0)](mailto:sachin.samprit@gmail.com)

</div>
