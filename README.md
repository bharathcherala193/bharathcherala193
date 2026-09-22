# Hi, I am Bharathkumar 👋

###  About Me

I am an **AI/ML Engineer Student** specializing in B.Tech CSE (AI & ML). I build AI systems end-to-end—from data preprocessing and model fine-tuning to multi-agent architectures, Dockerized FastAPI microservices, and Streamlit demo UIs.

Instead of writing basic single-prompt wrappers, I design multi-stage RAG pipelines that route, retrieve, evaluate, and self-correct. When something fails in production, I find the root cause and confirm the fix with concrete metrics.

Most of my builds run entirely on local models or free-tier infrastructure—zero paid API costs, no rate limits, just Ollama, Groq, and PyTorch doing the heavy lifting on my machine.

---

###  Featured Builds

<table width="100%">
<tr>
<td>

###  01. [Production-RAG-Application](https://github.com/bharathcherala193/Production-RAG-Application)
> **Offline Contract RAG System with Source Attribution & CI Quality Gates**

Built a hybrid search RAG pipeline over 510 real legal contracts (CUAD dataset) combining BM25 keyword search + ChromaDB vector search with cross-encoder reranking (top 20 → top 5). Diagnosed vague uncited answers and model hallucinations, raising Ragas faithfulness from **0.77–0.82 to 1.00** and answer relevancy to **0.71**. Automated quality evaluation in GitHub Actions CI to break builds if scores drop—running at zero API cost with local Llama 3.1 8B via Ollama.

**Tech Stack:** `Python` `LangChain` `ChromaDB` `Ollama (Llama 3.1 8B)` `Ragas` `GitHub Actions` `Streamlit`

</td>
</tr>
</table>

<table width="100%">
<tr>
<td>

###  02. [Autonomous-Research-Report-Agent](https://github.com/bharathcherala193/Autonomous-Research-Report-Agent)
> **Multi-Agent LangGraph Pipeline with Claim-Checking Critic & Audit Logging**

Designed a 4-agent workflow (`Planner` → `Researcher` → `Writer` → `Critic`) in LangGraph where the Critic cross-checks every generated claim against raw Tavily web sources and sends drafts back for revision until unsupported claims are removed. Fixed research budget starvation and reasoning drift, adding human approval gates and full audit logging running on Groq free-tier LLMs.

**Tech Stack:** `LangGraph` `LangChain` `Groq (Llama/GPT-OSS)` `Tavily` `Streamlit` `Human-in-the-Loop`

</td>
</tr>
</table>

<table width="100%">
<tr>
<td>

###  03. [VisionInspect-AI](https://github.com/bharathcherala193/VisionInspect-AI)
> **Deep Learning Defect Detection Platform with Class-Imbalance Correction**

Built and deployed a ResNet50 visual inspection pipeline across 3 MVTec AD industrial categories, achieving **87–98%** test accuracy. Diagnosed a severe class-imbalance failure (model defaulting to majority normal class) and corrected it using weighted sampling and gradient clipping—boosting minority-class recall from **36% to 91%**. Shipped as a reproducible, Dockerized FastAPI microservice.

**Tech Stack:** `PyTorch` `ResNet50` `FastAPI` `Docker` `Scikit-learn` `MVTec AD`

</td>
</tr>
</table>

<table width="100%">
<tr>
<td>

###  04. [Faithfulness-Guard-Loop](https://github.com/bharathcherala193/Faithfulness-Guard-Loop)
> **Real-Time Automated Evaluation Loop Preventing LLM Hallucinations**

Developed a real-time evaluation guard loop using Ragas metrics to measure generation faithfulness on the fly, automatically re-routing low-confidence or uncited responses back to retrieval or outputting grounded fallbacks.

**Tech Stack:** `Python` `Ragas` `LangChain` `LLM Evaluation` `Prompt Engineering`

</td>
</tr>
</table>

<table width="100%">
<tr>
<td>

###  05. [Pharmaceutical-Inventory-Analysis](https://github.com/bharathcherala193/Pharmaceutical-Inventory-Analysis)
> **Data Processing Pipeline & Interactive Procurement Dashboard**

Analyzed large-scale pharmaceutical inventory datasets using Python & SQL to uncover procurement patterns and inventory optimization rules, building interactive Streamlit dashboards that reduced manual reporting overhead by **~80%**.

**Tech Stack:** `Python` `SQL` `Pandas` `Seaborn` `Streamlit`

</td>
</tr>
</table>

---

###  Tech Stack

<h4 align="center">Languages & Frameworks</h4>
<p align="center">
  <img src="https://img.shields.io/badge/PYTHON-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/FASTAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/STREAMLIT-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/LANGCHAIN-121212?style=for-the-badge&logo=chainlink&logoColor=white" />
  <img src="https://img.shields.io/badge/LANGGRAPH-15161e?style=for-the-badge&logo=diagramsdotnet&logoColor=38bdf8" />
</p>

<h4 align="center">AI/ML & Data</h4>
<p align="center">
  <img src="https://img.shields.io/badge/PYTORCH-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/TENSORFLOW-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/HUGGINGFACE-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/NUMPY-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/PANDAS-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/SCIKIT_LEARN-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
</p>

<h4 align="center">DevOps & Tools</h4>
<p align="center">
  <img src="https://img.shields.io/badge/DOCKER-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/GIT-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GITHUB_ACTIONS-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" />
  <img src="https://img.shields.io/badge/GROQ-F05032?style=for-the-badge&logo=fastly&logoColor=white" />
  <img src="https://img.shields.io/badge/JUPYTER-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
</p>

---

###  Contact & Resume

<p align="center">
  <a href="https://www.linkedin.com/in/bharath193/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;&nbsp;
  <a href="mailto:bharathcherala193@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/bharathcherala193" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

<p align="center">
  <a href="https://bharathcherala193.github.io/portfolio/resume.html" target="_blank">
    <img src="https://img.shields.io/badge/📄_DOWNLOAD_RESUME-2563EB?style=for-the-badge&logoColor=white" />
  </a>
</p>
