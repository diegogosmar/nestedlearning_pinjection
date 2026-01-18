# Nested Learning Prompt Injection

## Overview
This project documents a prompt-injection experiment in a “nested learning” setup with multiple agents (FrontEnd, Reviewer, KPI evaluator) and a multi-level memory cache (medium/slow). The goal is to observe how patterns and vulnerabilities propagate when prompts are repeated at fixed intervals within an evaluation pipeline.

## Experiment (in brief)
- **Dataset**: a base prompt list plus a set of replicated prompts inserted periodically.
- **Pipeline**: prompt execution on Ollama models defined in configuration.
- **Metrics**: tracking cache hits/misses, execution times, and vulnerability signals.

## Structure
- `NL_agentic_pinjection_300_OFP_Ollama.ipynb`: main notebook with setup, prompt definition, and pipeline.

## Requirements
- Python 3.10+
- Ollama installed locally
- Models referenced in the notebook available via `ollama run`

## Quick start
1. Open the notebook.
2. Check the model configuration section.
3. Run the cells in order.

## Notes
Prompts can be replaced with placeholders to avoid sharing sensitive or repetitive content.
