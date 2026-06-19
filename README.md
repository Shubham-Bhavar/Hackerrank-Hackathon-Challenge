# Multi-Modal Evidence Review

An AI-powered claim verification system that evaluates damage claims for **cars**, **laptops**, and **packages** using image evidence, claim conversations, user history, and evidence requirements.

The system extracts the reported damage, analyzes submitted images, identifies visible issues and affected parts, assesses evidence sufficiency, and determines whether the claim is **Supported**, **Contradicted**, or **Insufficient Evidence**.

## Features

- Claim extraction from user conversations
- Image-based damage detection and classification
- Object part identification
- Evidence sufficiency evaluation
- Severity estimation
- Risk flagging (image quality, authenticity, mismatch, user history)
- Evidence-grounded justifications
- Automated CSV result generation

## Tech Stack

```text
Python
Pandas
OpenCV
PyTorch
Vision Language Models (VLMs)
Large Language Models (LLMs)
```

## Workflow

```text
Claim Conversation
        │
        ▼
 Claim Extraction
        │
        ▼
  Image Analysis
        │
        ▼
Damage & Part Detection
        │
        ▼
Evidence Evaluation
        │
        ▼
Risk Assessment
        │
        ▼
Decision Generation
        │
        ▼
     output.csv
```

## Output

Generates a structured `output.csv` containing claim decisions, supporting image IDs, severity levels, risk flags, and concise evidence-based justifications.
