# Technical Dialogue Analysis in Human-LLM Programming Interactions

This repository contains the code and data for the ACL 2024 submission "Mapping Cognitive Load in Human-LLM Programming Dialogues: A Multimodal Analysis of Technical Discourse Patterns".

## Overview

We present a multimodal analysis of human-LLM interactions in programming contexts, examining how dialogue complexity and user expertise influence cognitive processing patterns. The repository includes eye-tracking data, dialogue transcripts, and analysis code.

## Dataset Description

The anonymized dataset comprises 444 programming dialogues collected from university students, including:

### Eye-tracking Data
- Device: Professional-grade eye tracker, 60 Hz sampling rate
- Metrics: fixation counts, saccade patterns, dwell times
- Areas of Interest (AOIs): code interface, dialogue interface

### Dialogue Data
- Total interactions: 444
- Dialogue themes distribution:
  - Output Formatting 
  - Pattern Programming 
  - Logic Building
  - Data Structures
  - Debugging
  - Mathematical operations

### Participant Demographics
- Experience levels:
  - Novice (n=64)
  - Intermediate (n=168)
  - Advanced (n=192)
- Programming experience range: 0.5-6 years

## Code Structure

### Analysis Scripts
- `statistical_analysis.py`: Statistical tests implementation
- `visualization.py`: Figure generation

## Usage

1. Environment Setup:
    pip install -r requirements.txt

2. Analysis:
    python code/analysis/statistical_analysis.py
    python code/analysis/visualization.py

## Data Access

The anonymized dataset used in this study will be made publicly available upon paper acceptance.

## Note

This is an anonymous submission to ACL 2024. Author information and institutional affiliations will be added upon paper acceptance.
