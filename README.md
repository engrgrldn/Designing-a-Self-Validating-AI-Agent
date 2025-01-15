# Self-Validating AI Agent

## Overview
This project demonstrates a self-validating AI agent designed to generate summaries of delivery performance based on customer feedback. The system ensures accuracy, relevance, and consistency of outputs through autonomous validation mechanisms.

## Assumptions
- Input data is structured as a list of customer feedback.
- The AI agent uses simple NLP techniques for summary generation.
- Validation criteria include accuracy (semantic similarity), relevance (keyword matching), and consistency (contradiction detection).

## Validation Strategy
1. **Accuracy**: Compare the summary with feedback using cosine similarity.
2. **Relevance**: Ensure the summary focuses on delivery-related topics.
3. **Consistency**: Detect contradictions in the summary.

## How to Run
1. Place customer feedback in `data_feedback.json`.
2. Run `main.py` to generate and validate summaries.
3. Review validation results and flagged summaries.

## Future Improvements
- Use advanced NLP models (e.g., BERT, GPT) for better summarization and validation.
- Implement a user-friendly interface for human feedback.
- Automate model retraining based on validation results.