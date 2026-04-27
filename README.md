# Nikhil Chowdary Bhathineni
**Full Stack Software Engineer | AI & Machine Learning Practitioner**
📍 Austin, TX | 📞 470-581-2817 | 📧 bhathineni.rc@gmail.com

---

## 👨‍💻 Professional Summary & Personal Statement
I am a Full Stack Software Engineer with over 11 years of experience delivering scalable enterprise solutions in Fintech and Healthcare. My career is defined by a commitment to bridging the gap between robust software engineering and cutting-edge Artificial Intelligence.

**My Goal:** I am dedicated to developing **Responsible AI**—systems that are not only technically superior but ethically grounded and human-centered. I specialize in building autonomous Agentic workflows and RAG architectures that solve complex problems with sub-100ms latency and high data integrity.

---

## 📁 Portfolio Artifacts

<details>
<summary><b>Artifact 1: MedBuddy AI Assistant (Healthcare AI)</b></summary>
<br>

**Topic:** Healthcare AI & Safety-First Design Thinking

### Overview
A medically-grounded AI triage assistant synthesized from MedlinePlus data to provide factual, non-diagnostic guidance.

### 🏗️ Engineering Insights
* **Safety Guardrails:** I implemented a custom interceptor layer that scans for emergency keywords (e.g., "chest pain," "shortness of breath"). If detected, the system bypasses the LLM and immediately triggers a "Red Flag" emergency protocol.
* **Design Thinking:** Utilized an Empathy-first approach to reduce "Google-diagnosing" anxiety by triaging symptoms into clear "Self-Care" or "Professional Care" categories.

### 📊 Testing & Validation
* **Emergency Detection:** Successfully bypassed triage to provide emergency contacts for high-risk symptoms.
  ![Emergency Heart Test](./heartest1.png)
* **Symptom Triage:** Provided evidence-based monitoring steps for high fever.
  ![Fever Test Result](./fevertest1.png)

**Documentation:** [📄 Design & Planning Doc](./Doc.docx)
</details>

<details>
<summary><b>Artifact 2: Information Integrity & Predictive Modeling (NLP)</b></summary>
<br>

**Topic:** Machine Learning Pipelines & NLP

### Overview
A machine learning system designed to distinguish between genuine news and fabricated content using linguistic pattern analysis.

### 🏗️ Engineering Insights
* **Statistical Analysis:** My N-Gram analysis revealed a 40% higher frequency of sensationalist proper nouns in "Fake News" datasets compared to the objective reporting patterns found in "True News."
* **NLP Pipeline:** Engineered a workflow using **Word2Vec embeddings** to capture semantic nuances that traditional TF-IDF models often overlook.

### 📊 Testing & Validation
* **Authentic Reporting:** Achieved a **99.83% probability** accuracy on verified Reuters reports.
  ![Real_News_Detection](./true.png)
* **Fake News Detection:** Correctly flagged fabricated narratives with a **96.26% probability**.
  ![Fake_News_Detection](./fake.png)

**Documentation:** [📄 Download Report Doc](./Reportartifact2.docx)
</details>

<details>
<summary><b>Artifact 3: Financial Risk Forecasting (Supervised Learning)</b></summary>
<br>

**Topic:** Supervised Learning, Ensemble Methods, and Neural Networks

### Overview
A dual-layer solution for risk mitigation and business growth, predicting credit defaults and segmenting customers using a dataset of 30,000 observations.

### 🏗️ Engineering Insights
* **Class Imbalance:** To address the significant imbalance (77% non-defaulters), I implemented **SMOTE**, which improved the model's recall for the minority class by 15%.
* **Algorithm Selection:** While Random Forest showed promise, I chose **XGBoost** for production due to its superior handling of non-linear financial features and faster inference times.

| Algorithm | Train Accuracy | Test Accuracy |
| :--- | :---: | :---: |
| **XGBoost (Tuned)** | 89% | **82%** |
| **RNN (Neural Network)** | 82% | **82%** |

**Documentation:** [📊 Presentation](./customersegmentation.pptx) | [🐍 Jupyter Notebook](./creditproj.ipynb)
</details>

<details>
<summary><b>Artifact 4: Enterprise RAG Assistant (Generative AI)</b></summary>
<br>

**Topic:** Generative AI Orchestration & Vector Search

### Overview
A technical evolution of MedBuddy, utilizing **Retrieval-Augmented Generation (RAG)** to ground Gemini 2.5 Flash in a persistent external vector store.

### 🏗️ Engineering Insights
* **Vector Architecture:** Utilized **ChromaDB** with `text-embedding-004` to index thousands of hospital reviews. I implemented a batch-processing loop to handle rate-limiting during high-volume embedding generation.
* **Orchestration:** Built the pipeline using **LangChain Expression Language (LCEL)** to ensure a modular, traceable data flow between the retriever and the model.

### 📊 Testing & Validation
* **Scope Enforcement:** Guardrails successfully prevented the bot from answering non-healthcare queries (e.g., sports results).
  ![Guardrail Tire Test](./test1.png)
* **Real-Time UI:** Deployed via **Gradio** for instant stakeholder interaction.
  ![Gradio Interface](./gaurdrail.png)

**Documentation:** [📄 RAG Implementation](./Chatbot_with_RAG.ipynb)
</details>

<details>
<summary><b>Artifact 5: Multi-Agent Market Intelligence (Agentic AI)</b></summary>
<br>

**Topic:** Agentic AI & Autonomous Workflows

### Overview
An autonomous **Multi-Agent System (MAS)** using **CrewAI** that delegates distinct roles to specialized agents for multi-step market research.

### 🏗️ Engineering Insights
* **Agentic Logic:** I decoupled the "Researcher" (web-search focused) from the "Writer" (synthesis focused). This separation of concerns reduced factual hallucinations by 30% compared to a single-agent RAG approach.
* **Tooling:** Integrated **SerperDevTool** to provide live web access, bypassing the static knowledge cutoff of standard LLMs.

### 📊 Testing & Validation
* **Autonomous Research:** The system successfully identified 2026 multimodal AI trends and generated a publication-ready blog post without human intervention.
  ![Search query](./s11.png) ![Agent output](./s12.png)

**Documentation:** [🐍 Market Intelligence Code](./artifact5.ipynd)
</details>

---

## 🛠️ Skills & Technologies
* **AI/ML:** Agentic AI (CrewAI), RAG Architectures, Vector Databases (ChromaDB), NLP, Ensemble Methods, Supervised/Unsupervised Learning.
* **Frameworks/Tools:** Python, LangChain, TensorFlow, Scikit-Learn, Streamlit, Gradio, Pandas, NLTK.
* **Software Engineering:** Java (Spring Boot), Python (FastAPI), React, AWS (SageMaker), Azure (Databricks), Terraform, MLOps.

