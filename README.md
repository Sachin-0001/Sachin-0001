<div align="center">

# 🤗 &nbsp;Sachin-0001/sachin-suresh

**AI / ML Engineer** &nbsp;·&nbsp; Bengaluru, India

<br/>

![agentic-ai](https://img.shields.io/badge/agentic--ai-334155?style=flat-square)
![rag](https://img.shields.io/badge/rag-334155?style=flat-square)
![llm-infrastructure](https://img.shields.io/badge/llm--infrastructure-334155?style=flat-square)
![fine-tuning](https://img.shields.io/badge/fine--tuning-334155?style=flat-square)
![from-scratch](https://img.shields.io/badge/from--scratch-334155?style=flat-square)
![text-generation](https://img.shields.io/badge/text--generation-334155?style=flat-square)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://sachin11105.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sachin-0001)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sachin-suresh-06782b300/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sachin.samprit@gmail.com)

</div>

---

```yaml
name: sachin-suresh
role: ai-ml-engineer
location: bengaluru, india
base_model: cs-undergrad-dsce
license: open-to-collaborate

specializes_in:
  - agent runtimes and planning loops
  - retrieval pipelines with verifiable citations
  - parameter-efficient fine-tuning
  - serving and infrastructure for LLM systems

primary_stack: [python, pytorch, langgraph, fastapi, aws]
```

## Model Description

Writes the loop before reaching for the framework.

Most of the work sits where model behaviour meets systems engineering: how a reasoning loop actually terminates, why a retriever surfaces the wrong chunk, what a tool-calling agent does when the tool fails. Frameworks abstract away exactly the part worth understanding, so the default is to implement it once by hand, then decide whether the abstraction earns its place.


<div align="center"><sub>The loop behind <a href="https://github.com/Sachin-0001/Harness">Harness</a> — and the shape most of this work takes.</sub></div>

## Experience

| company | role | duration |
|:---|:---|:---|
| **Capmob Financial Services** | Lead AI Engineer Intern | Jun 2026 – Present |
| **XTrail Consulting Services** | Junior Developer Intern | Jan 2026 – Jun 2026 |


## Downstream Applications

<table>
<tr><td width="33%" valign="top">

### 🧩 Harness

**Agent runtime, no framework**

No LangGraph, no AutoGPT. Six tools — search, weather, calculator, sandboxed code exec, file I/O, email — in a bounded reasoning loop, with a second model screening inputs, tool calls, and outputs before anything runs. Two-tier memory: an LLM-distilled episodic log feeding a 384-dim FAISS index for cross-session recall.

`Python` `LangChain` `Groq` `FAISS`

[**Source →**](https://github.com/Sachin-0001/Harness)

</td><td width="33%" valign="top">

### 📄 UnBind

**Contract analysis, citation-verified**

PDFs, DOCX, and photographed contracts fan out into parallel clause-by-clause risk analysis streamed over SSE. Every Q&A answer anchors to character offsets in the source, so claims are checkable. HMAC-SHA256 payment verification and atomic quotas behind a 299-test CI gate. Ships as a web app and an npm CLI.

`Next.js` `FastAPI` `ChromaDB` `Groq`

[**Live →**](https://unbindai.vercel.app/) &nbsp;·&nbsp; [**Source →**](https://github.com/Sachin-0001/UnBind) &nbsp;·&nbsp; [**npm →**](https://www.npmjs.com/package/@sachin-0001/unbind)

</td><td width="33%" valign="top">

### 🔬 PEFT Runs

**7B adaptation on one GPU**

QLoRA on Mistral-7B-Instruct-v0.2 over an Alpaca-style instruction set: 41.94M trainable params, 0.57% of 7.28B, under 4-bit quantization, tracked end to end in MLflow. A second run applied LoRA at r=16 to Qwen2.5-1.5B-Instruct for conversational generation, touching 0.28% of params.

`PyTorch` `PEFT` `QLoRA` `MLflow`

</td></tr>
</table>

## Evaluation Results

| metric | value |
|:---|:---|
| tools wired into a hand-rolled agent loop | **6** |
| tests gating the UnBind pipeline in CI | **299** &nbsp;<sub>281 pytest · 18 vitest</sub> |
| deployable surfaces shipped from one codebase | **3** &nbsp;<sub>web · api · cli</sub> |
| trainable parameters at 4-bit, Mistral-7B | **0.57%** &nbsp;<sub>41.94M / 7.28B</sub> |
| upstream patches to a CNCF project | **4** |

## Training Data

**Formal**  
B.E. Computer Science, Dayananda Sagar College of Engineering, Bangalore &nbsp;·&nbsp; <sub>2023 – 2027</sub>

**Upstream**  
Contributing to **[headlamp-k8s/plugins](https://github.com/headlamp-k8s/plugins)**, the plugin ecosystem for the Kubernetes web UI, as part of LFX Mentorship Term 3. Patches so far cover cert-manager expiry display, secret redaction in the AI assistant plugin, and accessibility fixes to dashboard charts.

**Prior**  
Co-authored a paper on legal language simplification with LLMs. Runner-up at BotCraft 2024 among 100+ teams. [CodeChef](https://www.codechef.com/users/sachin_0111) 100-day streak, peak 1210 &nbsp;·&nbsp; [LeetCode](https://leetcode.com/u/_sachin_01_/) 50- and 100-day badges.

## Stack

| | |
|:---|:---|
| **languages** | Python · TypeScript · Go · C++ |
| **agentic / llm** | LangGraph · LangChain · LangSmith · HuggingFace · Groq · Ollama · n8n |
| **ml** | PyTorch · scikit-learn · NumPy · Pandas · OpenCV · PEFT/QLoRA · MLflow |
| **backend** | FastAPI · Pydantic · Next.js |
| **data** | PostgreSQL · MongoDB · Redis · ChromaDB · FAISS |
| **cloud** | AWS · Docker · GitHub Actions · Airflow · Vercel |

## Intended Use

Agentic systems, LLM infrastructure, and applied ML research. Open to collaboration and to roles in any of the three.

## Out-of-Scope Use

Known to over-invest in understanding a system before shipping it. Considered working as intended.

## Training Curves

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Sachin-0001&theme=github-compact&hide_border=true&area=true&bg_color=0d1117&color=a78bfa&line=7c3aed&point=e2e8f0" width="100%" alt="Contribution graph" />

<br/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Sachin-0001&theme=github_dark" height="170" alt="Stats" />
&nbsp;
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Sachin-0001&theme=github_dark" height="170" alt="Languages" />

</div>

## Citation

```bibtex
@software{suresh_2026,
  author  = {Suresh, Sachin},
  title   = {Agentic runtimes, retrieval systems,
             and the infrastructure underneath them},
  year    = {2026},
  url     = {https://github.com/Sachin-0001},
  contact = {sachin.samprit@gmail.com}
}
```

<div align="center">
<br/>
<sub>Build from scratch. Understand deeply. Ship with confidence.</sub>
</div>
