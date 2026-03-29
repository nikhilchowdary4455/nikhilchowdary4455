# Nikhil Chowdary Bhathineni
**Full Stack Software Engineer | AI & Machine Learning Practitioner**
📍 Austin, TX | 📞 470-581-2817 | 📧 bhathineni.rc@gmail.com

---

## 👨‍💻 Professional Summary
I am a Full Stack Software Engineer with over 3 years of experience delivering scalable enterprise solutions in Fintech and E-commerce. I specialize in combining agile innovation with engineering discipline to build high-performance systems—such as a real-time Loan Origination System with sub-100ms latency.

This portfolio showcases my journey into **Artificial Intelligence and Machine Learning**, where I apply my background in scalable architectures to create safe, responsible, and human-centered AI solutions.

## Artifact 1: MedBuddy AI Assistant
**Topic:** Healthcare AI & Safety-First Design Thinking

### Overview
This artifact showcases the development of a functional AI assistant designed to help users organize health symptoms. 
**Artifact Description:** Developed a medically-grounded AI triage assistant using Design Thinking. The project involved synthesizing a knowledge base from MedlinePlus to ensure factual accuracy and programming custom guardrails to detect high-risk medical emergencies. This artifact demonstrates the ability to balance technical AI implementation with ethical safety standards.

### Development Process
1. **Empathize:** Identified user anxiety regarding "Google-diagnosing."
2. **Define:** Built a system to triage symptoms into "Self-Care" or "Professional Care."
3. **Prototype:** Developed using Chatbase with a custom medical knowledge base.
4. **Test & Iterate:** Refined the AI's tone to be more empathetic and bolded emergency warnings for clarity.

## 📊 Testing & Validation Results
To ensure MedBuddy provides safe and accurate guidance, I tested the assistant against three common medical scenarios.

### Scenario 1: Emergency Detection (Chest Pain)
**Objective:** Validate that the "Red Flag" guardrails trigger immediately.  
**Result:** The bot identified the high-risk symptom and provided emergency contact instructions without attempting to triage.

![Emergency Heart Test](./heartest1.png)

---

### Scenario 2: Symptom Triage (High Fever)
**Objective:** Test the assistant's ability to provide evidence-based care steps for a common illness.  
**Result:** MedBuddy provided clear instructions on monitoring temperature and staying hydrated based on MedlinePlus data.

![Fever Test Result](./fevertest1.png)
![Fever Test Result](./fevertest2.png)

---

### Scenario 3: Minor Ailment (Sore Throat)
**Objective:** Ensure the assistant provides comforting, non-diagnostic home remedies.  
**Result:** The assistant suggested salt-water gargles and tea, while reminding the user to check for difficulty swallowing.

![Sore Throat Test Result](./sorethroat1.png)
![Sore Throat Test Result](./sorethroat2.png)

### Personal Value Proposition
This project highlights my expertise in **Responsible AI**, showing that I can build tools that protect users while providing value.

### Documentation
[📄 Download MedBuddy Design & Planning Doc](./Doc.docx)

## Artifact 2: Information Integrity & Predictive Modeling
**Topic:** Machine Learning Pipelines & NLP

### Overview
In an era where digital misinformation spreads rapidly, this project addresses the critical challenge of distinguishing between genuine news and fabricated content. By combining **Natural Language Processing (NLP)** and **Machine Learning (ML)**, the system establishes a link between raw data and human linguistic patterns.

### 🏗️ The Engineering Process
I developed a structured pipeline to translate human language into data dimensions that a machine can accurately process:

**Data Strategy:** Utilized datasets to train the system on common misinformation patterns and addressed missing data
**Preprocessing:** Established a workflow involving rigorous data cleaning and specialized NLP tasks.
**Feature Extraction:** Implemented linguistic feature extraction to identify characteristics that distinguish real news from fake.
**Exploratory Data Analysis (EDA):** Performed distribution analysis showing a balanced dataset (52.3% real, 47.7% fake) and visualized temporal trends to identify spikes in misinformation.
**NLP Text Processing:** Engineered a cleaning pipeline using NLTK to remove stop words, digits, and punctuation, followed by **Word2Vec embedding** to capture semantic nuances.
**N-Gram Statistical Analysis:** Conducted Bi-gram and Tri-gram analysis to uncover thematic differences:
**Fake News:** Showed a high frequency of sensationalist phrases like "Donald Trump" (547 instances) and "Black Lives Matter".
**True News:** Demonstrated objective reporting patterns with phrases like "White House says" and "Factbox".
**Model Selection:** Evaluated Random Forest (RF), Decision Trees (DT), SVM, and Logistic Regression (LR) to find the highest accuracy.
**Deployment:** Integrated the final trained model into a functional **Web App** using Streamlit for real-time user interaction.


### 📊 Testing & Validation
The model provides a transparent probability score, allowing users to assess the reliability of a news segment instantly.

#### Scenario 1: Validating Authentic Reporting
* **Objective:** Confirm the model correctly identifies high-integrity, factual journalism.
* **Result:** When processing a Reuters report regarding political investigations, the system yielded a **99.83% probability of the news being real**.
* ![Real_News_Detection](./true.png)

#### Scenario 2: Detecting Fabricated Claims
* **Objective:** Validate the model's ability to catch sensationalized or false narratives.
* **Result:** When analyzing a fabricated story, the model successfully identified the risk, showing a **96.26% probability of the news being fake**.
* ![Fake_News_Detection](./fake.png)

**Personal Value Proposition:** While Artifact 1 focused on **Design Thinking**, this project highlights my technical proficiency in **Classification Algorithms** and **Feature Engineering**.

---

## 🛠️ Skills & Technologies
* **AI/ML:** Supervised Learning, NLP, Feature Engineering, Model Evaluation.
* **Frameworks/Tools:** Python, Scikit-Learn, TensorFlow, Chatbase, Pandas.
* **Software Engineering:** Full Stack Development, Scalable Architectures, API Integration.

## 📄 Documentation
[📄 Download Report Doc](./Report(1).docx)
[📄 Download Model Design & Planning Doc](./Doc.docx)
