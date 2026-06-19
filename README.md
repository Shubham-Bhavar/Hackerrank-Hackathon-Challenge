# Multi-Modal Evidence Review

A multimodal AI system for automated damage-claim verification. The platform combines computer vision, natural language processing, and risk assessment techniques to evaluate claims using image evidence, claim conversations, user history, and evidence requirements.

## Key Capabilities

- Claim extraction using NLP/LLMs
- Visual damage detection and classification
- Object-part localization and analysis
- Evidence sufficiency assessment
- Support / Contradict / Insufficient Evidence prediction
- Severity estimation
- Risk scoring and anomaly detection
- Structured CSV output generation

## Tech Stack

### Development
- Python
- VS Code
- Git
- GitHub
- OpenAI Codex
- Claude Code

### AI & Data Processing
- Pandas
- OpenCV
- PyTorch
- Vision Language Models (VLMs)
- Large Language Models (LLMs)

## Processing Pipeline

1. Extract damage claims from conversations.
2. Analyze submitted images using vision models.
3. Identify object type, affected part, and damage category.
4. Compare visual evidence with claim statements.
5. Evaluate evidence sufficiency and image quality.
6. Incorporate user-history risk indicators.
7. Generate claim decision, severity level, and justification.
8. Export structured results to `output.csv`.

## Output

Produces structured claim assessments containing:
- Claim Decision
- Damage Type
- Affected Part
- Severity Level
- Supporting Image IDs
- Risk Flags
- Evidence-Based Justification
