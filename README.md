<!-- Dynamic Typing Text Animation -->
<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=26&pause=1000&color=38BDF8&center=true&vCenter=true&width=700&lines=Hi%2C+I+am+Bharathkumar+%F0%9F%91%8B;AI%2FML+Engineer+Student;Building+Multi-Stage+RAG+Pipelines;Designing+LangGraph+Agentic+Systems;Made+to+work%2C+not+just+to+demo" alt="Typing SVG Animation" />
  </a>
</p>

<br>

###  About Me

I am an **AI/ML Engineer Student** specializing in B.Tech CSE (AI & ML). I build AI systems end-to-end—from data preprocessing and model fine-tuning to multi-agent architectures, Dockerized FastAPI microservices, and Streamlit demo UIs.

Instead of writing basic single-prompt wrappers, I design multi-stage RAG pipelines that route, retrieve, evaluate, and self-correct. When something fails in production, I find the root cause and confirm the fix with concrete metrics.

Most of my builds run entirely on local models or free-tier infrastructure—zero paid API costs, no rate limits, just Ollama, Groq, and PyTorch doing the heavy lifting on my machine.

<br>

<!-- Connect & Links Row -->
<p align="center">
  <a href="https://github.com/bharathcherala193" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" height="22" alt="GitHub" />
  </a>
  &nbsp;&nbsp;
  <a href="https://x.com/No1405Core" target="_blank">
    <img src="https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white" height="22" alt="X" />
  </a>
  &nbsp;&nbsp;
  <a href="https://bharathcherala193.github.io/portfolio/resume.pdf" download="Bharathkumar_Resume.pdf" target="_blank">
    <img src="https://img.shields.io/badge/Resume_PDF-2563EB?style=flat-square&logo=googledocs&logoColor=white" height="22" alt="Resume PDF" />
  </a>
  &nbsp;&nbsp;
  <a href="https://www.linkedin.com/in/bharath193/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" height="22" alt="LinkedIn" />
  </a>
  &nbsp;&nbsp;
  <a href="mailto:bharathcherala193@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white" height="22" alt="Gmail" />
  </a>
</p>

---

###  Tech Stack

<p align="center">
  <strong>Languages & Frameworks</strong><br>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" height="20" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" height="20" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" height="20" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" height="20" />
  <img src="https://img.shields.io/badge/LangChain-121212?style=flat-square&logo=chainlink&logoColor=white" height="20" />
  <img src="https://img.shields.io/badge/LangGraph-15161e?style=flat-square&logo=diagramsdotnet&logoColor=38bdf8" height="20" />
</p>

<p align="center">
  <strong>AI/ML & Data</strong><br>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" height="20" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" height="20" />
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black" height="20" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" height="20" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" height="20" />
  <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" height="20" />
</p>

<p align="center">
  <strong>DevOps & Tools</strong><br>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" height="20" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" height="20" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" height="20" />
  <img src="https://img.shields.io/badge/Groq-F05032?style=flat-square&logo=fastly&logoColor=white" height="20" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" height="20" />
</p>

---

###  Featured Builds

<table width="100%">
<tr>
<td width="50%" valign="top">

###  01. [Production-RAG-Application](https://github.com/bharathcherala193/Production-RAG-Application)
> **Offline Contract RAG with Source Attribution & CI Quality Gates**

Built a hybrid search RAG pipeline over 510 real legal contracts (CUAD dataset) combining BM25 keyword search + ChromaDB vector search with cross-encoder reranking (top 20 → top 5). Diagnosed vague uncited answers, raising Ragas faithfulness from **0.77–0.82 to 1.00** and relevancy to **0.71**. Automated quality gating in GitHub Actions CI at zero API cost via local Llama 3.1 8B on Ollama.

**Tech Stack:** `Python` `LangChain` `ChromaDB` `Ollama` `Ragas` `GitHub Actions` `Streamlit`

</td>
<td width="50%" valign="top">

###  02. [Autonomous-Research-Report-Agent](https://github.com/bharathcherala193/Autonomous-Research-Report-Agent)
> **Multi-Agent LangGraph Pipeline with Claim Critic & Audit Logging**

Designed a 4-agent workflow (`Planner` → `Researcher` → `Writer` → `Critic`) in LangGraph where the Critic cross-checks every generated claim against raw Tavily web sources and loops revisions until verified. Solved budget starvation and reasoning drift by isolating tasks, adding human approval gates and full audit logging running on Groq free-tier LLMs.

**Tech Stack:** `LangGraph` `LangChain` `Groq (Llama/GPT-OSS)` `Tavily` `Streamlit` `HITL`

</td>
</tr>
<tr>
<td width="50%" valign="top">

###  03. [VisionInspect-AI](https://github.com/bharathcherala193/VisionInspect-AI)
> **Defect Detection Platform with Class-Imbalance Correction**

Built and deployed a ResNet50 visual inspection pipeline across 3 MVTec AD industrial categories, achieving **87–98%** test accuracy. Diagnosed a class-imbalance failure and corrected it using weighted sampling and gradient clipping—boosting minority-class recall from **36% to 91%**. Shipped as a reproducible, Dockerized FastAPI microservice.

**Tech Stack:** `PyTorch` `ResNet50` `FastAPI` `Docker` `Scikit-learn` `MVTec AD`

</td>
<td width="50%" valign="top">

###  04. [Faithfulness-Guard-Loop](https://github.com/bharathcherala193/Faithfulness-Guard-Loop)
> **Real-Time Automated Evaluation Loop Preventing Hallucinations**

Developed a real-time evaluation guard loop using Ragas metrics to measure generation faithfulness dynamically on the fly. The pipeline automatically intercepts low-confidence or ungrounded outputs and re-routes them back to the retrieval phase or serves verified fallback responses.

**Tech Stack:** `Python` `Ragas` `LangChain` `LLM Evaluation` `Prompt Engineering`

</td>
</tr>
</table>
