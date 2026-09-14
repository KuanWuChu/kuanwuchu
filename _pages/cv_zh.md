---
layout: page
title: 履歷
page_id: cv
lang: zh-tw
permalink: /zh-tw/cv/
translation_url: /cv/
description: 以多模態 AI、電腦視覺、AI 系統與異常偵測為核心的研究與工程履歷。
---

## 簡介

目前就讀 **國立政治大學資訊科學研究所**，研究與工程經驗涵蓋 **多模態 AI、電腦視覺、影像復原、AI Agent、高效率推論與異常偵測**。過去曾在台積電、和碩與工研院參與 AI 系統開發、Agent tooling、模型加速與實際部署，也持續投入影像復原、多模態與視覺理解相關研究。

## 學歷

**國立政治大學（NCCU）**  
資訊科學研究所碩士 — 預計 2027 年 6 月畢業  
資訊科學系學士 — 2022–2025  
研究方向：多模態 AI、影像復原、電腦視覺

## 經歷

### Engineering Intern, TSMC, MDID — 2026/07–2026/08
- 結合時序基礎模型與專用異常偵測模型，建立 Oracle Database 效能異常偵測流程，並找出多個歷史事故時窗。
- 開發並部署 Job Dispatch / Queue 異常偵測系統至正式環境，在測試集達到 **97% detection accuracy**，且 **無 false-positive alerts**。
- 參與 **React + Spring Boot** 內部應用開發，累積 Full-stack 實務經驗。

### AI Agent Intern, PEGATRON, AI Competitiveness Center — 2026/03–2026/06
- 將瀏覽器自動化 Agent 封裝為可重複使用的 skills，供 tool-using LLM 與 agent workflow 使用。
- 研究 browser-use 等開源 browser-agent framework，並設計 skill interface、retry / error handling 與 evaluation flow。

### Research Intern, ITRI, Scene Understanding & Augmented Intelligence Dept. — 2025/08–2026/03
- 使用 **MMPose、MediaPipe、ByteTrack、Redis、TensorRT** 建立即時姿態追蹤與零售場域視覺分析 pipeline。
- 以 TensorRT FP16 最佳化 Jetson Orin 上的 **RF-DETR**：達到 **7.50× end-to-end throughput**、**4.03× model-only inference speedup**、**75.2% lower latency**，並維持近乎一致的 F1。
- 最佳化 production ViT image encoder：throughput 提升 **2.46×**、RAM 使用降低 **43.5%**，並維持 Top-1 accuracy。

### 其他研究與教學經歷
- **Teaching Assistant, Qualcomm Generative AI Lecture (Demos)** — 2025；以 AutoGen 設計 multi-agent demos，整合 tools、VLM 與 low-level image restoration。
- **Research Assistant, Taiwan Tech & NCCU (3D Text-in-the-Wild)** — 2024–2025；建立 3D-augmented synthetic scene-text dataset 與 evaluation standard，並參與 Syn3DTxt。
- **Research Assistant, NCCU Future Media Lab** — 2023–2024；開發多模態社交活動監測系統，成果延伸為第一作者 IEEE ICS 2024 論文與專利。
- **Research Assistant, AI Multimedia Systems Lab** — 2024–至今；建立 5K+ smoke dataset、CLIP + Fourier baseline，並 prototype VLM-driven adverse-weather restoration agent。

## 論文

1. Li-Syun Hsiung, Jun-Kai Tu, **Kuan-Wu Chu**, et al. (2025). *Syn3DTxt: Embedding 3D Cues for Scene Text Generation.* CVPR Workshops (SyntaGen). [論文頁面](https://openaccess.thecvf.com/content/CVPR2025W/SyntaGen/html/Hsiung_Syn3DTxt_Embedding_3D_Cues_for_Scene_Text_Generation_CVPRW_2025_paper.html)
2. **Kuan-Wu Chu**, Joanna Qiong-Yue Chen, et al. (2024). *Social Temperature: Real-Time Social Activity Monitoring Based on Deep Learning Methods.* IEEE ICS. [DOI](https://doi.org/10.1109/ICS64339.2024.00049)

## 專利

陳昭伶、陳芎月、**朱冠伍**、蘇胤翔，〈社交活躍度檢測系統以及方法〉，台灣發明專利 **I912159**，2026 年 1 月 11 日核准；美國專利申請中（U.S. patent pending）。  
[Google Patents](https://patents.google.com/patent/TWI912159B/en) · [政大人工智慧跨域研究中心](https://iaic.nccu.edu.tw/achievements?c=2) · [Future Media Lab](https://www.futuremedialab.tw/project)

## 技能

**Languages & Tools:** Python, C++, PyTorch, TensorRT, TRT-LLM, Linux, Git, Redis, Jetson Orin  
**AI Agents / Systems:** tool-calling LLM、browser automation、reusable skills、workflow design、evaluation  
**Time Series & Anomaly:** 時序模型、異常偵測、資料庫 / Queue 監測、視覺瑕疵偵測  
**CV / Multimodal:** YOLO, CLIP, Whisper, MMPose, ByteTrack, RF-DETR, image restoration
