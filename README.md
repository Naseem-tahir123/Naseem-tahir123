<div align="center">

<img src="./banner.svg" width="100%" alt="Naseem Tahir, AI Engineer. Animated hybrid retrieval pipeline: query, vector and BM25 search, Reciprocal Rank Fusion, answer.">

<br>

<a href="#ask-my-profile">Ask my profile</a> &nbsp;·&nbsp;
<a href="#stack">Stack</a> &nbsp;·&nbsp;
<a href="#project-explorer">Projects</a> &nbsp;·&nbsp;
<a href="#experience">Experience</a> &nbsp;·&nbsp;
<a href="#github-stats">Stats</a> &nbsp;·&nbsp;
<a href="#contact">Contact</a>

</div>

<br>

I build production LLM applications: **hybrid-search RAG pipelines**, **guardrailed enterprise chatbots**, and **voice and OCR-based AI assistants**, served through FastAPI backends. Currently an AI Engineer at **Arcana Info** in Islamabad.

---

## Ask my profile

Click a question to expand the answer.

<details>
<summary><b><code>&gt; what do you build?</code></b></summary>

<br>

Production LLM applications. That includes RAG chatbots with hybrid search, voice agents, OCR-based assistants and content-generation pipelines, usually with a FastAPI backend.

</details>

<details>
<summary><b><code>&gt; what are you working on right now?</code></b></summary>

<br>

Since March 2026 I have been an AI Engineer at **Arcana Info**, working on two systems: **Arca AI**, a secure internal HR chatbot backend, and the **TBB Travel Assistant**, a RAG system for travel agents.

</details>

<details>
<summary><b><code>&gt; how do you improve retrieval quality?</code></b></summary>

<br>

By combining two retrieval methods instead of relying on one. I pair **vector similarity (pgvector)** with **full-text / BM25 search** and merge the ranked results with **Reciprocal Rank Fusion**.

</details>

<details>
<summary><b><code>&gt; how do you secure an LLM app?</code></b></summary>

<br>

With layers. For the HR chatbot I built a **3-layer guardrail system**: role-based access control (RBAC), PII redaction and prompt-injection defense. On the API side I add JWT authentication, request-ID middleware, rate limiting and structured error handling.

</details>

<details>
<summary><b><code>&gt; what have you shipped before?</code></b></summary>

<br>

At Assort Tech (Jan – Sep 2025) I delivered **6 end-to-end AI products in 9 months**: a RAG chatbot widget, a voice scheduling assistant, a GitHub PR review bot, a news-to-podcast pipeline, an OCR-based educational assistant and an AI book-generation workflow. Details are in the [project explorer](#project-explorer).

</details>

<details>
<summary><b><code>&gt; what are you exploring next?</code></b></summary>

<br>

Computer vision, MLOps and cloud-based AI deployment.

</details>

---

## Stack

<div align="center">
<img src="./stack.svg" width="100%" alt="Technology stack: OpenAI API, Gemini, Groq, Cohere, Ollama, LangChain, LangGraph, RAG, Python, FastAPI, PostgreSQL, pgvector, Prisma, MongoDB, Redis, Supabase, Docker, Linux, Git, n8n, Playwright, TensorFlow, Keras, scikit-learn, PyTorch, YOLO, Flutter">
</div>

---

## Project Explorer

Click a project to expand it. Most of this work was built for employers, so the code is private.

### At Arcana Info · 2026

<details>
<summary><b>Arca AI</b> · secure HR chatbot backend</summary>

<br>

| | |
|:--|:--|
| **What it is** | Backend for an internal HR assistant |
| **Retrieval** | pgvector similarity + full-text search, merged with Reciprocal Rank Fusion |
| **Security** | 3-layer guardrails: RBAC, PII redaction, prompt-injection defense, integrated with Groq and Cohere |
| **Visibility** | 4 admin dashboard API modules: AI training progress, knowledge coverage, query resolution rate, announcement pulse |
| **Stack** | `FastAPI` `Prisma` `pgvector` `Groq` `Cohere` |
| **Code** | Company project, private |

</details>

<details>
<summary><b>TBB Travel Assistant</b> · RAG for travel agents</summary>

<br>

| | |
|:--|:--|
| **What it is** | Production RAG system giving travel agents real-time answers from FAQs and guides |
| **Retrieval** | Vector similarity + BM25 search on PostgreSQL |
| **Stack** | `PostgreSQL` `pgvector` `Cohere embeddings` |
| **Also solved** | Traced a cross-environment scraper failure to a subdomain mismatch across 2 staging environments, restoring Playwright-based content ingestion |
| **Code** | Company project, private |

</details>

<details>
<summary><b>Production hardening</b> · applied to both systems</summary>

<br>

Structured error handling, JWT authentication, request-ID middleware and rate limiting across all API endpoints of both systems.

</details>

### At Assort Tech · 2025

<details>
<summary><b>Company AI chatbot</b> · real-time chat widget</summary>

<br>

RAG over company content, using web scraping and GPT-4o-mini, deployed as a chat widget that resolves customer queries without manual intervention.

`RAG` `Web scraping` `GPT-4o-mini`

</details>

<details>
<summary><b>Voice scheduling assistant</b> · three channels, one interface</summary>

<br>

Unifies Google Calendar, email and SMS into one conversational interface with real-time speech-to-text and text-to-speech, built with the OpenAI Agents SDK.

`OpenAI Agents SDK` `TTS / STT`

</details>

<details>
<summary><b>GitHub PR review bot</b> · automatic code feedback</summary>

<br>

A webhook-based bot using Gemini that generates code feedback on every incoming pull request, shortening manual review turnaround from hours to minutes.

`Gemini` `Webhooks`

</details>

<details>
<summary><b>News-to-podcast pipeline</b></summary>

<br>

Fetches stories via SerpAPI, summarizes them with GPT-4 and converts them to audio with text-to-speech, turning a multi-step manual workflow into a single triggered pipeline.

`SerpAPI` `GPT-4` `TTS`

</details>

<details>
<summary><b>Educational AI assistant</b> · OCR-based</summary>

<br>

Uses Mathpix OCR to process academic documents and images, then generates summaries, quizzes and explanations with GPT-4o-mini.

`Mathpix OCR` `GPT-4o-mini`

</details>

<details>
<summary><b>AI book-generation workflow</b></summary>

<br>

An end-to-end pipeline covering chapter writing, cover design and editing.

`n8n` `Supabase` `Gemini`

</details>

### Personal repositories

[**FlutterResponsiveUI**](https://github.com/Naseem-tahir123/FlutterResponsiveUI) · Flutter, Dart &nbsp;·&nbsp; [All repositories](https://github.com/Naseem-tahir123?tab=repositories)

---

## Experience

<details open>
<summary><b>AI Engineer · Arcana Info</b> &nbsp;<sub>Mar 2026 – Present · Islamabad</sub></summary>

<br>

Hybrid RAG systems, layered LLM guardrails and production hardening for enterprise chatbots.

</details>

<details>
<summary><b>AI Engineer · Assort Tech</b> &nbsp;<sub>Jan 2025 – Sep 2025 · Lahore</sub></summary>

<br>

Delivered 6 end-to-end AI products over 9 months: RAG chatbots, voice agents, OCR-based assistants and content-generation pipelines.

</details>

<details>
<summary><b>AI Intern · NAVTTC</b> &nbsp;<sub>Jun 2024 – Dec 2024 · Islamabad</sub></summary>

<br>

Six-month AI/ML internship covering model development and prototyping under senior engineer mentorship.

</details>

<details>
<summary><b>Education</b> &nbsp;<sub>2019 – 2024</sub></summary>

<br>

BS Computer Science, Federal Urdu University of Arts, Science & Technology, Islamabad.

</details>

---

## GitHub Stats

<details open>
<summary><b>Live stats</b></summary>

<br>

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Naseem-tahir123&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&bg_color=0B1220&title_color=FB7185&text_color=CBD5E1&icon_color=FBBF24&border_radius=14" alt="GitHub stats">
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Naseem-tahir123&layout=compact&langs_count=8&hide_border=true&bg_color=0B1220&title_color=FB7185&text_color=CBD5E1&border_radius=14" alt="Most used languages">

<sub>Much of my professional work is in private company repositories, so public stats show only part of it.</sub>

</div>

</details>

---

## Contact

<div align="center">

<a href="https://www.linkedin.com/in/naseem-tahir-balti/"><img src="https://img.shields.io/badge/LinkedIn-Naseem_Tahir-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="mailto:naseemtahir507@gmail.com"><img src="https://img.shields.io/badge/Email-naseemtahir507@gmail.com-FB7185?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
<!-- Add once you have the URL:
<a href="YOUR_PORTFOLIO_URL"><img src="https://img.shields.io/badge/Portfolio-Visit-FBBF24?style=flat&logo=googlechrome&logoColor=black" alt="Portfolio"></a>
-->

<sub>Islamabad, Pakistan</sub>

</div>
