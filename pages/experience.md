---
layout: page
title: Experience
permalink: /experience/
weight: 4
---

### Machine Learning Consultant
**Compnay:** Solver Minds Solution  
**Role:** Machine Learning Consultant  
**Duration:** Jan 2025 – Present

Lead the design and deployment of advanced AI systems and generative agents using cutting-edge LLMs and vector databases.Manage cloud-native infrastructures, optimize model performance, and drive cross-team collaboration for scalable AI solutions.

{% include elements/collapse.html title="Roles & Technology"
content=" 

<br>

###### Roles & Responsibilities

- Lead the design and development of cutting-edge AI systems and Generative AI agents using advanced LLM technologies such as Hugging Face, VLLM, LLaMA/GPT models, embedding models, and vector databases (Chroma, Weaviate).  
- Architect and deploy robust AI pipelines combining Retrieval-Augmented Generation (RAG) architectures, vector storage for diverse content types (documents, images, tables, videos, SQL data), and seamless backend integrations.  
- Optimize model performance and fine-tuning using LoRA, 4-bit & 8-bit quantization, and prompt engineering to deliver context-aware responses efficiently.  
- Build and manage cloud-native deployments on Azure Kubernetes Service (AKS), ensuring scalability, security, and cost-effectiveness.  
- Implement Grafana-based monitoring and logging to maintain system reliability and provide performance insights.  
- Containerize AI services with Docker and oversee CI/CD pipelines to enable smooth project delivery and version control.  
- Lead cross-functional teams, manage project timelines, and facilitate collaboration across stakeholders to ensure successful project outcomes.

###### Tech Stack

- **Large Language Models & Frameworks:** Hugging Face Transformers, VLLM, LLaMA, GPT models  
- **Embedding & Vector DBs:** Chroma, Weaviate  
- **Model Optimization:** LoRA, 4-bit and 8-bit quantization, prompt engineering  
- **Cloud & Orchestration:** Azure Kubernetes Service (AKS)  
- **Monitoring & Logging:** Grafana  
- **Containerization & DevOps:** Docker, CI/CD pipelines  
- **Backend & Integration:** Python, REST APIs, microservices architecture  

"%}

---

### Machine Learning Engineer  

**Role:** Machine Learning Engineer  
**Company:** Vosyn, Toronto, Canada (Remote)  
**Duration:** Nov 2024 – May 2025  

As a Machine Learning Engineer, I worked on cutting-edge multilingual speech synthesis and transcript analysis systems, focusing on modularity, performance, and deployment at scale.

{% include elements/collapse.html title="Roles & Technology"
content="
<br>

##### Roles & Responsibilities
- Led core modeling, architecture design, and optimization for multilingual speech synthesis and video transcript systems.
- Designed pipelines for data preparation, training, evaluation, and deployment on Vertex AI.
- Implemented automated, reproducible ML pipelines using Docker and CI/CD best practices.
- Improved performance while optimizing costs and runtime on cloud infrastructure.
- Mentored and managed 5 junior engineers, handled sprint planning, code reviews, and shared technical insights across teams.

##### Tech Stack

- **Modeling & ML:** PyTorch, Modified VITS, NumPy, SciPy, Librosa, Google Gemini 3, Sentence-Transformers  
- **Data Engineering & Multimedia Processing:** FFmpeg, Pandas, phoneme extraction scripts, YouTube API, Pytube, Whisper (fallback), text chunking, LangDetect  
- **Cloud & Infrastructure:** Google Cloud Platform (Vertex AI, Pipelines, Firestore, Cloud Storage), Docker  
- **Vector Search & Semantic Retrieval:** FAISS, cosine similarity  
- **Backend & API:** Python, FastAPI, modular microservice architecture  
- **Evaluation Metrics:** Mean Opinion Score (MOS), Word Error Rate (WER), Phoneme Sequence Error (PSEQ)  
- **DevOps & Collaboration:** Git, Docker, CI/CD pipelines, Notion, code reviews, team mentorship  

"%}
<br>
**Check out my projects below for this role:**

{% include elements/collapse.html title="Multilingual, Multispeaker TTS Model Development"
content="

<br>

###### Project Goal:

Develop a modular multilingual and multispeaker Text-to-Speech (TTS) system capable of:

- Translating any supported language text into high-quality audio.  
- Supporting speaker accent replication and diverse voice characteristics.  
- Enhancing speech naturalness, fidelity, and intelligibility.  
- Integrating into scalable cloud production pipelines with cost optimization.

###### My Role in Project: 
- Developed a modular multilingual, multispeaker TTS system using a modified VITS architecture with a custom synthesizer layer.
- Supported speaker accent replication and diverse voice characteristics while enhancing naturalness and intelligibility of speech.
- Created and preprocessed a 10GB dataset, aligning transcripts and phoneme annotations for robust multilingual support.
- Trained on Google Vertex AI (T4 GPUs) with Dockerized, reproducible pipelines, reducing cloud training costs by ~15% using checkpoint-based fine-tuning.
- Improved Mean Opinion Score (MOS) by 6.7% over baseline, ensuring quality and cost-effective scalability for production deployment.

"%}

{% include elements/collapse.html title="Multilingual YouTube Transcript Summarization & Search System"
content="

<br>

###### Project Goal:
Build a multilingual system to process and summarize YouTube content with search and playback features:

- Extract transcripts in any language.  
- Summarize long-form video transcripts via chunk-based analysis.  
- Store semantic embeddings for searchable video playback.  
- (Planned scope) Translate and generate synchronized audio overlays.

###### My Role in Project: 
- Built a system to process and summarize YouTube videos, enabling semantic search with playback-linked retrieval.
- Integrated Google Gemini 3 for multilingual summarization, chunking transcripts while mapping summaries to video timecodes.
- Generated semantic embeddings with Sentence-Transformers, stored in a FAISS database for fast retrieval of relevant segments.
- Designed for future multilingual translation with synchronized playback integration.
- Deployed pipelines on Google Vertex AI with Dockerized stages for scalable cloud orchestration.

"%}

---

## Software Engineer  
**Role:** Software Engineer  
**Company:** eInfochips Pvt Ltd., Ahmedabad, Gujarat, India  
**Duration:** June 2019 – July 2022  

As a Software Engineer with 3 years of experience, I worked on diverse backend technologies and played key roles in software development and testing across multiple domains.

**Check out my projects below for this role:**

{% include elements/collapse.html title="🌐 Web Portal for Multi-School Education"
content="

<br>

###### Project Goal:  
Developed a school web portal to manage records for schools, students, teachers, and extracurricular programs. A similar version was also adapted for a pharmaceutical company to manage employee records, products, and industrial machinery data.

###### My Role: 
- Redesigned the entire MySQL database structure with over 100 interrelated tables.  
- Handled missing values, inconsistent data types, and complex relationships.  
- Created optimized procedures, views, and advanced queries for data retrieval.  
- Developed RESTful APIs using Node.js to support frontend interactions (Angular-based UI).  
- Ensured scalability and consistency in backend architecture.

###### Tech Stack:  
Node.js, JavaScript, MySQL, Angular, CI/CD, JIRA, Jenkins, GitHub
"%}

{% include elements/collapse.html title="🖥️ Desktop Application Verification for Automotive Systems"
content="
<br>

###### Project Goal:
Automate the verification of a desktop application used for analyzing in-car entertainment systems in four-wheelers. The testing covered UI interaction, log file analysis, remote control systems, and report validation.

###### My Role: 
- Acted as the lead developer and was responsible for requirement gathering, architecture design, and documentation.  
- Designed 60+ test cases covering various modules.  
- Developed a robust testing framework using Node.js, Jest, and Selenium.  
- Incorporated NLP-based log verification using spaCy to validate system messages and interactions.  
- Developed custom modules to test graph rendering and interactive UI elements.

###### Tech Stack:
Node.js, Jest, Selenium, Python (spaCy), GitHub, Jenkins, Excel, Confluence, Kanban Boards
"%}


{% include elements/collapse.html title="🔧 Linux-Based Component Development & Hardware Verification"
content="
<br>

###### Project Goal: 
Develop software components and verify hardware for a new smart soundbar model, part of a suite of smart audio devices (e.g., speakers, headphones) integrated with voice assistants like Alexa, Google Assistant, and Siri.

###### My Role:  
- Developed a new software component using C++ and Linux shell scripts for a lightweight OS.  
- Built a modular architecture compatible with the existing device ecosystem.  
- Enabled module reusability, efficient communication between UI and app, and device-to-device interactions.  
- Configured and extended an existing automation testing framework (in Python & Pytest) for the new hardware.  
- Specialized in debugging, fixing integration issues, and optimizing performance.

###### Tech Stack:
Linux, C++, Python, Pytest, Selenium, Jenkins, GitHub, JIRA, Confluence, Excel, Wiki, Kanban Boards

"%}
---
