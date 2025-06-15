---
layout: page
title: Experience
permalink: /experience/
weight: 4
---

Machine Learning Consultant
**Compnay:** Solver Minds Solution  
**Role:** Machine Learning Consultant  
**Duration:** Jan 2025 – Present

Description

---

### Machine Learning Engineer  

**Role:** Machine Learning Engineer  
**Company:** Vosyn, Toronto, Canada (Remote)  
**Duration:** Nov 2024 – May 2025  

As a Machine Learning Engineer, I worked on cutting-edge multilingual speech synthesis and transcript analysis systems, focusing on modularity, performance, and deployment at scale.

{% include elements/collapse.html title="# Multilingual, Multispeaker TTS Model Development"
content="
<br>

###### Project Goal:

Develop a modular multilingual and multispeaker Text-to-Speech (TTS) system capable of:

- Translating any supported language text into high-quality audio.  
- Supporting speaker accent replication and diverse voice characteristics.  
- Enhancing speech naturalness, fidelity, and intelligibility.  
- Integrating into scalable cloud production pipelines with cost optimization.

###### My Role: 
  As the lead intern on this module, I contributed to both core modeling and team leadership by enhancing architecture, optimizing deployment, and guiding junior contributors.

  **Architecture Enhancement:** 
  - Modified the original VITS architecture to include a custom synthesizer layer.  
  - Enabled multilingual and multispeaker support from combined datasets of diverse languages, phonemes, and speaker profiles.

  **Data Preparation:**  
  - Created a 10GB custom dataset by aggregating and preprocessing open-source datasets.  
  - Ensured data compatibility through audio-transcript alignment and phoneme annotation.

  **Training Infrastructure:**  
  - Trained on Google Vertex AI using T4 GPUs (n1-standard-16).  
  - Isolated environments using Docker for reproducible training and testing.  
  - Automated end-to-end training with Vertex AI Pipelines.

  **Evaluation & Optimization:**  
  - Used Mean Opinion Score (MOS) and Word Error Rate (WER) for evaluation.  
  - Improved MOS by 6.7% over the baseline.  
  - Introduced checkpoint-based fine-tuning, cutting cloud training costs by ~15%.

  **Team Leadership:**  
  - Mentored and managed 5 junior engineers.  
  - Reviewed code, led sprint planning, and facilitated knowledge sharing sessions.

###### Teck Stack

**Modeling & ML:** PyTorch, Modified VITS, NumPy, SciPy, Librosa  
**Data Engineering:** FFmpeg, Pandas, phoneme extraction scripts  
**Cloud:** Google Cloud Platform (Vertex AI, Firestore, Cloud Storage), Docker  
**Evaluation:** MOS, WER, Phoneme Sequence Error (PSEQ)  
**DevOps:** Git, Docker, CI/CD Pipelines  
**Collaboration:** Notion, code reviews, team mentorship  

"%}

{% include elements/collapse.html title="📺 Multilingual YouTube Transcript Summarization & Search System"
content="

<br>

###### Project Goal:
Build a multilingual system to process and summarize YouTube content with search and playback features:

- Extract transcripts in any language.  
- Summarize long-form video transcripts via chunk-based analysis.  
- Store semantic embeddings for searchable video playback.  
- (Planned scope) Translate and generate synchronized audio overlays.

###### My Role: 
As the system's primary designer and developer, I led all components from architecture to cloud deployment.

  **Framework Design & Transcript Pipeline:**  
  - Used YouTube API to fetch metadata and multilingual transcripts.  
  - Handled video lengths up to 1 hour with transcripts spanning hundreds of lines.

  **Multilingual Summarization with Gemini 3:**  
  - Integrated Google Gemini 3 for summarization.  
  - Chunked transcripts and mapped each to its corresponding video timecode.  
  - Generated frame-aligned summaries with duration metadata.

  **Semantic Search via Vector DB:**  
  - Generated embeddings using Sentence-Transformers.  
  - Stored vectors in a FAISS database for semantic search and segment retrieval.

  **Metadata Mapping:**  
  - Mapped summaries to video frame ranges and durations.  
  - Prepared for future translation and synced playback integration.

  **Cloud Deployment:**  
  - Deployed using Google Vertex AI (T4 GPU, n1-standard-16).  
  - Each pipeline stage containerized via Docker and orchestrated using Vertex AI Pipelines.

  **Team Collaboration:**  
  - Worked independently with architectural feedback from senior engineers.  
  - Contributed documentation and shared insights across platform teams.

###### Tech Stack:
**Transcript & Video:** YouTube API, Pytube, Whisper (fallback), FFmpeg  
**Summarization:** Google Gemini 3, LangDetect, text chunking  
**Semantic Search:** Sentence-Transformers, FAISS, cosine similarity  
**Cloud:** Google Cloud (Vertex AI, Pipelines, Firestore, Cloud Storage), Docker  
**Backend:** Python, FastAPI, modular microservice architecture  
"%}

---

## Software Engineer  
**Role:** Software Engineer  
**Company:** eInfochips Pvt Ltd., Ahmedabad, Gujarat, India  
**Duration:** June 2019 – July 2022  

As a Software Engineer with 3 years of experience, I worked on diverse backend technologies and played key roles in software development and testing across multiple domains.


{% include elements/collapse.html title="🌐 Web Portal for Multi-School Education"
content="

<br>

##### Project Goal:  
Developed a school web portal to manage records for schools, students, teachers, and extracurricular programs. A similar version was also adapted for a pharmaceutical company to manage employee records, products, and industrial machinery data.

##### My Role: 
- Redesigned the entire MySQL database structure with over 100 interrelated tables.  
- Handled missing values, inconsistent data types, and complex relationships.  
- Created optimized procedures, views, and advanced queries for data retrieval.  
- Developed RESTful APIs using Node.js to support frontend interactions (Angular-based UI).  
- Ensured scalability and consistency in backend architecture.

##### Tech Stack:  
Node.js, JavaScript, MySQL, Angular, CI/CD, JIRA, Jenkins, GitHub
"%}

{% include elements/collapse.html title="🖥️ Desktop Application Verification for Automotive Systems"
content="
<br>

##### Project Goal:
Automate the verification of a desktop application used for analyzing in-car entertainment systems in four-wheelers. The testing covered UI interaction, log file analysis, remote control systems, and report validation.

##### My Role: 
- Acted as the lead developer and was responsible for requirement gathering, architecture design, and documentation.  
- Designed 60+ test cases covering various modules.  
- Developed a robust testing framework using Node.js, Jest, and Selenium.  
- Incorporated NLP-based log verification using spaCy to validate system messages and interactions.  
- Developed custom modules to test graph rendering and interactive UI elements.

##### Tech Stack:
Node.js, Jest, Selenium, Python (spaCy), GitHub, Jenkins, Excel, Confluence, Kanban Boards
"%}


{% include elements/collapse.html title="🔧 Linux-Based Component Development & Hardware Verification"
content="
<br>

##### Project Goal: 
Develop software components and verify hardware for a new smart soundbar model, part of a suite of smart audio devices (e.g., speakers, headphones) integrated with voice assistants like Alexa, Google Assistant, and Siri.

##### My Role:  
- Developed a new software component using C++ and Linux shell scripts for a lightweight OS.  
- Built a modular architecture compatible with the existing device ecosystem.  
- Enabled module reusability, efficient communication between UI and app, and device-to-device interactions.  
- Configured and extended an existing automation testing framework (in Python & Pytest) for the new hardware.  
- Specialized in debugging, fixing integration issues, and optimizing performance.

##### Tech Stack:
Linux, C++, Python, Pytest, Selenium, Jenkins, GitHub, JIRA, Confluence, Excel, Wiki, Kanban Boards

"%}
---
