<!-- HEADER BANNER -->
<p align="center">
  <img src="https://capsule-render.vercel.app/main?type=rect&color=0d1117&height=180&section=header&text=LIVESH%20JHA&fontSize=65&fontColor=00ff88&animation=fadeIn" />
</p>

<p align="center">
  <strong>🚀 AI Engineer | Machine Learning | Generative AI | LLMs & NLP</strong>
</p>

<p align="center">
  <a href="mailto:liveshjha.aieng.348@gmail.com"><img src="https://img.shields.io/badge/Email-liveshjha.aieng.348%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://linkedin.com/in/YOUR_LINKEDIN_URL"><img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="https://huggingface.co/YOUR_HF_USERNAME"><img src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Models%20%26%20Spaces-yellow?style=flat-square" /></a>
  <img src="https://img.shields.io/badge/Location-Imadol%2C%20Nepal-lightgrey?style=flat-square" />
</p>

---

### 🧠 Professional Summary
Ambitious AI/ML Systems Developer with proven technical expertise spanning Generative AI, MLOps, and Computer Vision. Combines strong engineering fundamentals—demonstrated by deploying low-latency CV models and high-accuracy ensemble classifiers—with cross-functional leadership of 50+ student researchers. Adept at managing the complete MLOps lifecycle from data engineering to live edge inference and monitoring. Looking to leverage production-deployment experience and strong collaborative skills within an engineering-first team.

---

### 🌐 End-to-End Edge & GenAI Infrastructure Architecture

```mermaid
graph TD
    %% Custom Styling
    classDef ai fill:#0d1117,stroke:#00ff88,stroke-width:2px,color:#fff;
    classDef ops fill:#0d1117,stroke:#38bdf8,stroke-width:2px,color:#fff;
    classDef edge fill:#0d1117,stroke:#fb923c,stroke-width:2px,color:#fff;

    A[Raw Data Ingestion / Data Engineering] -->|DVC Tracking| B(Preprocessing & Feature Normalization)
    B --> C{Pipeline Branching}
    
    %% GenAI Loop
    C -->|Text/Context Protocols| D[Transformers / LangChain Orchestration]:::ai
    D -->|Audio Latents| E[Neural Diffusion Pipeline]:::ai
    E -->|Model Evaluation| F[MLflow & Model Registry]:::ops

    %% Edge Loop
    C -->|Biomarker / Spatial Inputs| G[YOLO & Ensemble Classifiers]:::edge
    G -->|Post-Training Optimization| H[TFLite Quantized Engine]:::edge
    H -->|Local Hardware Execution| I[Sub-50ms Low-Latency Inference]:::edge
    I -->|CI/CD Actions Artifacts| F
    
    F --> J[Live Production Deployment]:::ops
