---
name: RoverBot 
tools: [Detectron2, Llava 7B Mode, Pytorch, Streamlit, Python]
image: /assets/images/rovernet/link_image_resize.jpg
description: Martian terrain surface segmentation using instance segmentation and visual LLM-powered Q&A !
# external_url: https://github.com/jhanvizala230/Rovernet-chatbot
---

# 🚀 RoverBot

**Visual Question Answering with Detectron2 + LLM Integration**

[GitHub Repo](https://github.com/jhanvizala230/Rovernet-chatbot)

> Martian terrain surface segmentation using instance segmentation and a visual LLM-powered Q&A chatbot.

---

## 🧠 Project Overview

**RoverBot** is a Martian terrain surface segmentation and analysis system that classifies **8 distinct regions** — *soil, sand, rock, bedrock, sky, ridge, hole, and rover* — using a robust instance segmentation pipeline.  
It combines **Mask R-CNN** via **Detectron2** (by Facebook Research) for pixel-level segmentation and integrates the **LLaVA 7B** visual question-answering model to deliver an intelligent chatbot for terrain understanding.

The user interface is developed with **Streamlit**, providing real-time image processing, conversational interaction, and dynamic visualization.

---

## ⚙️ Technologies Used

| **Category** | **Stack** |
|--------------|------------|
| **Frameworks** | PyTorch, Detectron2, FastAPI, Streamlit |
| **Models** | Mask R-CNN, LLaVA 7B |
| **Libraries** | OpenCV |
| **Infrastructure** | Docker, CUDA 12.8, Kubernetes |
| **Dataset** | COCO 2017 + Custom Martian Terrain Annotations |

---

## 🚧 System Features

- ✅ **Instance Segmentation** with Mask R-CNN and Detectron2  
- ✅ **Visual Q&A** with LLaVA 7B  
- ✅ **Real-time Image Upload & Processing**  
- ✅ **Conversational Interface** using Streamlit & FastAPI  
- ✅ **Containerized Deployment** ready for Docker/Kubernetes  

---

## 📷 Demo Gallery

| Interface | Processed Output |
|-----------|------------------|
| ![Home Screen](/assets/images/rovernet/initial_screen_resize.png) | ![Detection Results](/assets/images/rovernet/results_resize.png) |

| Q&A Flow | Mask-RCNN Output |
|----------|------------------|
| ![Chat Example](/assets/images/rovernet/results2_resize.png) | ![Detection](/assets/images/rovernet/detection_result_resize.png) |

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