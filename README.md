# Agent Laboratory: Autonomous LLM Agents for Scientific Discovery

## Name: Abhishek Darji

## ID: 019113471

## Overview

This repository provides an overview and resources related to the research paper "Agent Laboratory: Using LLM Agents as Research Assistants" by Schmidgall et al. (2025). The paper introduces a novel, fully autonomous framework designed to execute the entire scientific research lifecycle—from initial conception to final report—using collaborative Large Language Models (LLMs).

## Resources

| Resource Type | Status / Link |
|---------------|---------------|
| Original Article (arXiv) | https://arxiv.org/pdf/2501.04227 |
| Review Article (Medium) | https://medium.com/@abhishek.darji/automating-discovery-a-review-of-agent-laboratory-using-llm-agents-as-research-assistants-88aabd400d78 |
| Presentation Deck | https://docs.google.com/presentation/d/1x05eMc8ZiL1IqxzB52Utc5qJFgZRRAQvp_kseiVleEA/edit?usp=sharing |
| Explainer Video | (https://drive.google.com/file/d/1LPrJ5RPGZpx8gRruAG4DH6lCXjePZRL3/view?usp=sharing) |

## Paper Summary

The Agent Laboratory is a significant advancement in autonomous AI for science, successfully automating complex research tasks with minimal human intervention.

### 1. The Core Framework

The system is built on a modular, three-stage pipeline that simulates a real research team:

- **Phase 1: Literature Review**: Agents (e.g., "PhD Student") use external tools like the ArXiv API to gather and synthesize existing knowledge.
- **Phase 2: Experimentation**: Agents (e.g., "Postdoc," "ML Engineer") use an iterative mle-solver to generate, execute, and debug machine learning code, collecting empirical data and achieving state-of-the-art (SOTA) results.
- **Phase 3: Report Writing**: Agents (e.g., "Professor") use a paper-solver to compile the findings into a comprehensive, professionally formatted LaTeX research report and code repository.

### 2. Key Findings

- **SOTA Performance**: The autonomously generated machine learning code achieved competitive, state-of-the-art results on standard benchmarks (e.g., MLE-Bench), demonstrating research quality is comparable to human-led efforts.
- **Model Dependence**: The quality of the final research output is highly dependent on the underlying Large Language Model. The framework driven by the `ol-preview` model consistently generated the best research outcomes, underscoring the necessity of advanced reasoning capabilities.
- **Efficiency and Cost**: The framework offers unprecedented efficiency, drastically reducing the cost per generated paper (e.g., $2.33 using GPT-4o) and dramatically accelerating the research iteration loop.

### 3. Human-in-the-Loop (Co-Pilot Mode)

While fully autonomous execution is possible, the highest quality results are achieved when human researchers provide feedback and guidance at critical checkpoints. This "Co-Pilot Mode" resulted in reports that scored significantly higher in both quality and significance, positioning the Agent Laboratory as a powerful research accelerator rather than a replacement.
