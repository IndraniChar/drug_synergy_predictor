# 🔬 Drug Synergy Predictor with Gen-AI

[![R Version](https://img.shields.io/badge/R-4.5.2-blue)](https://www.r-project.org/)
[![Shiny](https://img.shields.io/badge/Shiny-1.8.0-green)](https://shiny.rstudio.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Open Source](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badge/)

---

## 🌐 LIVE DEMO

### 👉 **[https://indranichar.shinyapps.io/drug_synergy_predictor/](https://ls86l3-indranichar.shinyapps.io/drug_synergy_predictor/)** 👈

> **No installation needed!** Click the link above to try the app in your browser.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Live Demo](#live-demo)
- [Technical Architecture](#technical-architecture)
- [Run Locally](#run-locally)
- [Example Output](#example-output)
- [For Pharma & Biotech](#for-pharma--biotech)
- [Author](#author)

---

## 🎯 Overview

**Drug Synergy Predictor** is an AI-powered platform that predicts synergistic drug combinations for cancer treatment. It combines **machine learning**, **generative AI**, and **clinical trial data** to identify optimal drug pairs.

### What Problem Does This Solve?

| Challenge | Solution |
|-----------|----------|
| 10,000+ possible drug combinations | AI ranks top synergistic pairs |
| Unknown mechanisms of action | Gen-AI provides mechanistic explanations |
| Patient stratification needed | Biomarker recommendations included |
| Clinical evidence scattered | Integrated clinical trial database |

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| **Intelligent Prediction** | Predicts Loewe, Bliss, and ZIP synergy scores (0-100 scale) |
| **Gen-AI Explanations** | LLM-powered mechanistic insights for each combination |
| **Interactive Heatmaps** | Visualize drug interaction matrices |
| **Clinical Database** | Access to 350+ drug combinations with trial phases |
| **AI Assistant** | Ask questions about combinations, biomarkers, and trials |
| **Beautiful UI** | Pink/purple gradient theme with smooth animations |

---


### Technology Stack

| Component | Technology |
|-----------|------------|
| Frontend | R Shiny, shinydashboard |
| ML Engine | Ensemble learning (synergy scoring) |
| Gen-AI | LLM-powered mechanistic explanations |
| Visualization | ggplot2, plotly, interactive heatmaps |
| Database | Synthetic clinical trial data (350+ combinations) |
| Deployment | shinyapps.io + GitHub |

---

## 🚀 Run Locally

### Prerequisites

```r
# Install required packages
install.packages(c(
  "shiny", "shinydashboard", "tidyverse", 
  "ggplot2", "plotly", "DT"
))

 Performance Dashboard
After running the app, you can:

Explore top 20 synergistic combinations with scores > 35/100

View heatmaps showing interaction matrices

Ask AI assistant about mechanisms and biomarkers

Export data for further analysis
