---
layout: archive
title: "Projects"
permalink: /portfolio/
author_profile: true
---

My research investigates the mechanisms that govern efficiency and reliability in artificial intelligence systems — from how training quality shapes test-time reasoning in large language models, to how biologically-inspired architectures achieve robustness under perturbation. My most recent work, accepted as a sole-authored poster at NeurIPS 2026, establishes training quality as the primary determinant of reasoning efficiency across 50 language models. Earlier work extends this focus on resilience and adaptability into molecular property prediction, biomedical classification, and graph-structured data analysis, through architectures integrating homeostatic regulation, multi-scale temporal coordination, and self-repair mechanisms. Across both directions, my aim is the same: building AI systems that behave predictably, efficiently, and reliably under real-world conditions.

---

## Research Implementation

### Training Quality Determines Efficiency Boundaries in Test-Time Reasoning


**Accepted:** NeurIPS 2026, Main Track — Poster (Sole Author)

**Research Problem:** Scaling inference-time computation is widely assumed to improve reasoning in large language models, but it is unclear when additional inference tokens are actually beneficial, redundant, or actively harmful to accuracy.

**Key Findings:**
- Evaluated 50 language models (0.5B–685B parameters) across six reasoning benchmarks, totalling over 67,000 assessments
- Standard models show near-universal accuracy convergence at ~1,000 tokens, regardless of architecture, parameter count, or decoding strategy
- Causal intervention experiments show constraining generation length improves reasoning accuracy by 15.4 percentage points — identifying over-generation, not capacity exhaustion, as the primary efficiency bottleneck
- Among 19 reasoning-specialised models, training methodology alone produces a 5.0–18.8× efficiency gap at matched parameter scales — exceeding gains from ten-fold parameter increases
- Introduces a mechanistic framework isolating two orthogonal dimensions of training quality — quality control and decomposition efficiency — that independently predict inference-time efficiency

**Technical Implementation:** Large-scale model evaluation pipeline, causal intervention experiments, mechanistic profiling across model families

**Author:** MD Azizul Hakim (Sole Author)

[View Repository](https://github.com/logicsame/Training-Quality-Determines-Efficiency-Boundaries-in-Test-Time-Reasoning) | [Read Paper](/publication/2026-training-quality-efficiency-boundaries)

---

### Biologically Inspired Neural Network with Homeostatic Regulation

<div style="margin: 20px 0;">
  <img src="https://logicsame.github.io/md-hakim.github.io//images/biological_neuron.gif" alt="Biological Neural Network Visualization" style="width: 100%; height: 200; border-radius: 8px; display: block;">
</div>

**Published:** Scientific Reports (Nature Portfolio), 2025  
**DOI:** [10.1038/s41598-025-09114-8](https://doi.org/10.1038/s41598-025-09114-8)

**Research Problem:** Artificial neural networks suffer from brittleness under perturbation and lack the self-repair capabilities inherent to biological systems, limiting their reliability in real-world deployments.

**Solution Architecture:**
- **Homeostatic Regulation Layer** - Maintains network stability through biological feedback mechanisms
- **Adaptive Repair Mechanisms** - Self-healing capabilities for damaged or perturbed network components
- **Multi-Scale Coordination** - Integration across temporal scales for robust function
- **Biologically-Principled Design** - Grounded in neuroscience and evolutionary biology principles

**Validation Domains:**
- Molecular property prediction (AIDS, HIV, COX2 datasets)
- Protein analysis and classification
- Biomedical graph-structured data
- Drug discovery applications

**Key Contributions:**
- First implementation of homeostatic regulation in artificial neural network layers
- Demonstrated superior performance on critical biomedical benchmarks
- Established foundation for biologically-faithful AI architectures
- Validated self-repair mechanisms under various perturbation scenarios

**Technical Implementation:** PyTorch, Graph Neural Networks, Custom Layer Architecture

**Authors:** MD Azizul Hakim, Mohammad Ifazul Alam

[View Implementation](https://github.com/logicsame/bio-logical-self-healing-neural-system) | [Read Paper](https://doi.org/10.1038/s41598-025-09114-8)

---

## Engineering Applications

My engineering work translates research insights into production-ready systems, demonstrating practical applications of advanced AI technologies across diverse domains.

### Competitive Data Science

I actively compete on **Kaggle**, applying advanced machine learning techniques to complex real-world datasets. This work demonstrates expertise in statistical modeling, feature engineering, and predictive analytics.

**Core Competencies:**
- Advanced ensemble methods and model stacking
- Deep learning for computer vision and NLP tasks
- Feature engineering and dimensionality reduction
- Hyperparameter optimization and cross-validation strategies

[Explore Kaggle Profile](https://www.kaggle.com/hakim11)

---

### FounderAI - Executive AI Agent Platform
*Multi-Agent System for Startup Leadership*

**Problem Solved:** Early-stage founders lack resources for complete executive teams, limiting strategic execution across business functions.

**Solution Architecture:**
- **Multi-Agent Orchestration** - CrewAI and LangGraph coordination
- **Specialized Executive Agents** - CMO, CPO, CTO, COO personas with domain expertise
- **Model Context Protocol** - Seamless inter-agent communication
- **Tool Integration** - Market research, financial modeling, technical planning

**Agent Capabilities:**
- Market positioning and acquisition strategy
- Product roadmap and feature prioritization  
- Technical architecture and development planning
- Operations optimization and resource allocation
- Investor pitch and fundraising materials

**Technical Stack:** LangChain, LangGraph, CrewAI, FastAPI, Streamlit

[View Repository](https://github.com/logicsame/IIUC-Competition)

---

### AI-Driven Tourist Spot Finder
*Intelligent Travel Companion with Multi-Agent Architecture*

**Problem Solved:** Traditional travel planning lacks personalization and fails to integrate real-time contextual data.

**Solution Architecture:**
- **FastAPI Backend** - Production-grade REST API
- **ML Recommendation Engine** - Hybrid filtering with collaborative and content-based methods
- **LLM Integration** - GPT-powered destination insights
- **Real-Time Data Agents** - Weather, pricing, availability monitoring
- **MongoDB Storage** - User profiles and preference learning

**Key Features:**
- Personalized destination recommendations
- Dynamic itinerary generation with contextual awareness
- Multi-modal data integration (text, images, location)
- Real-time constraint satisfaction

**Technical Stack:** FastAPI, PyTorch, LangChain, MongoDB, Docker

[View Repository](https://github.com/logicsame/ai-agent-based-trip-guider-main-file)

---

### Health-Conscious Food Recommendation System
*Personalized Nutrition AI with OCR Integration*

**Problem Solved:** Individuals with health conditions struggle to make informed dietary choices from food labels and nutritional information.

**Solution Architecture:**
- **Advanced OCR Pipeline** - Mistral OCR for food label text extraction
- **Health Analysis Engine** - LLM-powered nutritional assessment
- **RAG System** - Medical dietary guideline integration
- **Personalization Engine** - Health condition-aware recommendations
- **MongoDB Storage** - User health profiles and food database

**Key Features:**
- Real-time food label analysis
- Medical condition-specific recommendations
- Nutritional database queries with constraints
- Personalized meal planning

**Technical Stack:** Mistral OCR, LangChain, RAG, MongoDB, Computer Vision

[View Repository](https://github.com/logicsame/health-recommendation-system)

---

### Bengali Text-to-Speech Synthesis
*Transformer-Based Language Model Fine-tuning*

**Problem Solved:** Limited accessibility tools for Bengali speakers due to lack of high-quality native TTS systems.

**Solution Architecture:**
- **Pegasus Model Fine-tuning** - Transformer optimization for Bengali
- **MLOps Pipeline** - Automated training and deployment
- **Custom Dataset Processing** - Bengali corpus preparation
- **Production Optimization** - Inference performance tuning

**Key Features:**
- Natural Bengali speech synthesis
- Scalable inference pipeline
- Continuous model improvement through MLOps
- Production API deployment

**Technical Stack:** Transformers, PyTorch, MLOps, Docker, Kubernetes

[View Repository](https://github.com/logicsame/train-pegasus-model-on-bengali-text-summarization-using-mlops)

---

## Technical Capabilities

**Machine Learning & Deep Learning:** PyTorch, TensorFlow, Keras, Scikit-learn, Custom Neural Architectures

**MLOps & Deployment:** MLflow, Docker, Kubernetes, CI/CD, Model Monitoring

**Cloud Infrastructure:** AWS (SageMaker, EC2, S3), Google Cloud Platform

**Specialized Domains:** Computer Vision, NLP, Graph Neural Networks, Generative AI

**AI Agent Systems:** LangChain, LangGraph, CrewAI, AutoGen, LlamaIndex, RAG, Vector Databases

---

## Connect

[GitHub](https://github.com/logicsame) | [Kaggle](https://www.kaggle.com/hakim11) | [Google Scholar](https://scholar.google.com/citations?user=jVyIovcAAAAJ&hl=en)