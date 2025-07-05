---
name: Video Topic Extractor
tools: [SpeechRecognition, KeyBERT, Gensim LDA, MoviePy, NLTK, PyLDAvis, Python]
image: /assets/images/video_topic_extractor/wordcloud_topic_0.png
description: This project demonstrates an end-to-end workflow for transcribing videos, normalizing text, extracting key phrases, modeling topics using LDA, and visualizing them interactively.
# external_url: https://github.com/yourusername/video-topic-extractor
---


## 🎥Video Topic Extraction and Visualization using LDA Algorithm 

<br>

##### 📌 Project Description
This project demonstrates an end-to-end pipeline for analyzing video content. It covers:

Transcribing spoken content from video files.
Normalizing and cleaning the text data.
Extracting key phrases and relevant topics.
Visualizing the extracted topics with an interactive dashboard.
This workflow is useful for automatic topic discovery, content summarization, and data-driven insights from recorded videos.

 ---

##### ⚙️ Tech Stack

| Component | Technology |
|-----------|-------------|
| Programming Language | Python |
| Speech Recognition | Google Speech-to-Text via `SpeechRecognition` |
| Text Processing | NLTK, Regex, WordNet Lemmatizer |
| Keyphrase Extraction | KeyBERT |
| Topic Modeling | Gensim LDA |
| Visualization | pyLDAvis |
| Video Handling | MoviePy |
| Data Management | File system & Python standard libraries |

---

##### ✅ Key Strengths of this Approach
- ✔ Fully unsupervised — no need for labeled data.
- ✔ Uses powerful transformer embeddings (KeyBERT) for high-quality key phrases.
- ✔ Classical topic modeling (LDA) provides an interpretable summary.
- ✔ Interactive visualization helps validate and present results.

----

##### For your video analysis:

I discovered the main discussion themes without reading the whole text
and  can name each topic:

> Topic 0: Unstructured Data Challenges

> Topic 1: Big Data & Ads

> Topic 2: Structured Data & Supervised Learning

> Topic 3: Neural Networks for Vision

> Topic 4: NLP & Understanding Text

----

#### 📷 Demo Gallery

Below are sample visual outputs from the Video Topic Extraction:

Key Phrases Bar Chart 
![Key Phrases](/assets/images/video_topic_extractor/keyphrases.png) 

[pyLDAvis Dashboard](/assets/html/video_topic_extractor/video_topics.html)
![](/assets/images/video_topic_extractor/dashborad.png)

<!-- ###### 📑 Topic-wise Word Clouds

Each word cloud shows the most representative words for each discovered topic.


| Topic 0 | Topic 1 |
|---------|----------|
| ![Topic 0 Word Cloud](/assets/images/video_topic_extractor/wordcloud_topic_0.png) | ![Topic 1 Word Cloud](/assets/images/video_topic_extractor/wordcloud_topic_1.png) |

| Topic 2 | Topic 3 |
|---------|----------|
| ![Topic 2 Word Cloud](/assets/images/video_topic_extractor/wordcloud_topic_2.png) | ![Topic 3 Word Cloud](/assets/images/video_topic_extractor/wordcloud_topic_3.png) |

| Topic 4 |
|---------|
| ![Topic 4 Word Cloud](/assets/images/video_topic_extractor/wordcloud_topic_4.png) | -->

---

<!-- ### 📊 Dashboard Link

👉 **Explore the full interactive topic model:**  
[🔗 Open pyLDAvis Dashboard](./assets/html/video_topics.html) -->
