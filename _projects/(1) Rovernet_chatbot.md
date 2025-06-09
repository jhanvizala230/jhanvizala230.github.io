---
name: RoverBot 
tools: [Detectron2, Llava 7B Mode, Pytorch, Streamlit, Python]
image: /assests/images/rovernet/link_image_resize.jpg
description: Martian terrain surface segmentation using instance segmentation and visual LLM-powered Q&A !
# external_url: https://github.com/jhanvizala230/Rovernet-chatbot
---


# 🚀 RoverBot
**Visual Question Answering with Detectron2 + LLM Integration**

[GitHub Repo](https://github.com/jhanvizala230/Rovernet-chatbot)

> Martian terrain surface segmentation using instance segmentation and visual LLM-powered Q&A

---

## 🧠 Project Overview

RoverNet is a Martian terrain surface segmentation and analysis system that classifies 8 unique regions — **soil, sand, rock, bedrock, sky, ridge, hole, and rover** — using a robust instance segmentation pipeline. It integrates **Mask R-CNN** through **Detectron2** (by Facebook Research) for pixel-level segmentation and combines it with **LLaVA 7B**, a visual question-answering model, to create an intelligent chatbot for terrain analysis.

The UI is developed using **Streamlit**, offering real-time image processing, conversational interaction, and dynamic results visualization.

---

## 🚧 Technologies Used

<div class="feature__wrapper">
  <div class="feature__item">
    <i class="fas fa-brain"></i>
    <h3>Computer Vision</h3>
    <p>Detectron2 + OpenCV for high-accuracy segmentation (98.5% mAP)</p>
  </div>
  <div class="feature__item">
    <i class="fas fa-comments"></i>
    <h3>Visual Q&A</h3>
    <p>LLaVA 7B for image-contextual conversations and analysis</p>
  </div>
  <div class="feature__item">
    <i class="fas fa-code"></i>
    <h3>Backend</h3>
    <p>FastAPI, PyTorch (CUDA 12.8), running 24 FPS @ 1080p</p>
  </div>
  <div class="feature__item">
    <i class="fas fa-laptop-code"></i>
    <h3>Frontend</h3>
    <p>Built with Streamlit – responsive in &lt;500ms</p>
  </div>
</div>

---

## 📷 Demo Gallery

| Interface | Processed Output |
|-----------|------------------|
| ![Home Screen](/assests/images/rovernet/initial_screen_resize.png) | ![Detection Results](/assests/images/rovernet/results_resize.png) |

| Q&A Flow | Mask-RCNN Output |
|----------|------------------|
| ![Chat Example](/assests/images/rovernet/results2_resize.png) | ![Detection](/assests/images/rovernet/detection_result_resize.png) |

---

## 🧩 System Stack

| Category | Stack |
|----------|-------|
| Frameworks | PyTorch, Detectron2, FastAPI, Streamlit |
| Models | Mask-RCNN, LLaVA 7B |
| Infrastructure | Docker, CUDA (12.8), Kubernetes |
| Dataset | COCO 2017 + Custom Martian Terrain Annotations |

---

## 🧪 Key Features

- ✅ Instance segmentation with Mask-RCNN using Detectron2
- ✅ Visual question answering with LLaVA 7B
- ✅ Live image upload and processed result display
- ✅ Streaming-based Q&A interface
- ✅ Docker-ready deployment

---

## 💬 Chatbot Highlights

```
User: What is the region under the rover?
Bot: Based on the segmentation output, it appears to be sandy terrain with embedded rock formations.
```

## 📎 Tags
<span class="badge">Detectron2</span>
<span class="badge">MaskRCNN</span>
<span class="badge">LLaVA</span>
<span class="badge">Visual QA</span>
<span class="badge">Streamlit</span>
<span class="badge">FastAPI</span>
<span class="badge">Computer Vision</span>