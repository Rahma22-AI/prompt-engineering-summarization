# Improving Movie Plot Summarization Using Prompt Engineering

This repository contains the code, prompts, and evaluation metrics used in the research paper:

**Improving Movie Plot Summarization Using Prompt Engineering**  
By Rahma Hamdy & Rowan Hany  
Faculty of Computer Science & Engineering, Alamein International University  
Course Code: AIE241 – Natural Language Processing

---

## Objective

Evaluate Few-Shot and Zero-Shot Prompt Engineering using:
- T5-small
- BART-large-cnn

on a subset of the CMU Movie Summary Corpus.

---

## Dataset

- **Source**: CMU Movie Summary Corpus  
- **Sample Size**: 5 movie plots  
- **Reference Summaries**: First two sentences of each plot  

---

## Models Used

- **Baseline**: T5-small with "summarize:" prefix  
- **Few-Shot**: T5-small with two example prompt pairs  
- **Zero-Shot**: T5-small with task instruction only  
- **BART**: BART-large-cnn with default summarization config  

---

## Setup

```bash
git clone https://github.com/yourusername/movie-plot-summarization-prompts.git
cd movie-plot-summarization-prompts
pip in stall -r requirements.txt
    
