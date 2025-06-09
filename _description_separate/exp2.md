## Machine Learning Engineer  
**Role:** Machine Learning Engineer  
**Company:** Vosyn, Toronto, Canada (Remote)  
**Duration:** Nov 2024 – May 2025  

As a Machine Learning Engineer, I worked on cutting-edge multilingual speech synthesis and transcript analysis systems, focusing on modularity, performance, and deployment at scale.

---

<details>
<summary><strong>🗣️ Multilingual, Multispeaker TTS Model Development</strong></summary>

**Project Goal:**  
Develop a modular multilingual and multispeaker Text-to-Speech (TTS) system capable of:

- Translating any supported language text into high-quality audio.  
- Supporting speaker accent replication and diverse voice characteristics.  
- Enhancing speech naturalness, fidelity, and intelligibility.  
- Integrating into scalable cloud production pipelines with cost optimization.

**My Role:**  
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

**Tech Stack:**  
**Modeling & ML:** PyTorch, Modified VITS, NumPy, SciPy, Librosa  
**Data Engineering:** FFmpeg, Pandas, phoneme extraction scripts  
**Cloud:** Google Cloud Platform (Vertex AI, Firestore, Cloud Storage), Docker  
**Evaluation:** MOS, WER, Phoneme Sequence Error (PSEQ)  
**DevOps:** Git, Docker, CI/CD Pipelines  
**Collaboration:** Notion, code reviews, team mentorship  

</details>

---

<details>
<summary><strong>📺 Multilingual YouTube Transcript Summarization & Search System</strong></summary>

**Project Goal:**  
Build a multilingual system to process and summarize YouTube content with search and playback features:

- Extract transcripts in any language.  
- Summarize long-form video transcripts via chunk-based analysis.  
- Store semantic embeddings for searchable video playback.  
- (Planned scope) Translate and generate synchronized audio overlays.

**My Role:**  
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

**Tech Stack:**  
**Transcript & Video:** YouTube API, Pytube, Whisper (fallback), FFmpeg  
**Summarization:** Google Gemini 3, LangDetect, text chunking  
**Semantic Search:** Sentence-Transformers, FAISS, cosine similarity  
**Cloud:** Google Cloud (Vertex AI, Pipelines, Firestore, Cloud Storage), Docker  
**Backend:** Python, FastAPI, modular microservice architecture  

</details>
