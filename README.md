# effective_prompt_maker

## 📌 Project Overview

This repository contains the **core implementation** of the proposed approach.

The project is organized into several key modules, each corresponding to a specific stage of the pipeline.

---

## 📂 Directory Structure

### 🔹 Typicality / Uncertainty

The `Typicality` and `Uncertainty` directories provide the complete implementation of:

- Typicality computation  
- Uncertainty estimation  
- Intermediate steps involved in deriving these metrics  

These modules demonstrate how typicality and uncertainty are calculated and utilized within the framework.

---

### 🔹 Combine / Demos_generate

The `Combine` and `Demos_generate` directories focus on:

- Joint modeling of typicality and uncertainty  
- Sample determining strategies  
- Prompt construction under different decision strategies  

These components illustrate how samples are selected and combined to construct prompts based on different modeling strategies.

---

## 🧠 Model Preparation

Before running the code, please download the following models and place them in the corresponding subdirectories under `models/`:

- **Qwen model**  
- **Sentence-BERT model**

Ensure that the directory structure matches the expected paths used in the code.

---

## 📊 Evaluation

The `Evaluate` directory contains scripts for:

- Evaluating prompts constructed under different strategies  
- Comparing the effectiveness of various prompt-building approaches  

Please use the provided evaluation scripts to assess performance across different configurations.

---

## ✅ Notes

- Make sure all required dependencies are properly installed.  
- Verify that model paths are correctly configured before execution.
