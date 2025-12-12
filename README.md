# What Affects the Efficiency of Coding Agents?

With the rapid evolution of software engineering, the integration of autonomous coding agents is becoming a larger part of our software workflows. This GitHub repository explores the efficiency of coding agents and what affects that efficiency.

All the analyses in this report and repository are drawn from the AIDev dataset introduced by Li et al. (2025), which provides large-scale empirical data on how autonomous coding agents operate across more than 456,000 pull requests authored by major agentic systems such as Codex, Devin, GitHub Copilot, Cursor, and Claude Code.

To evaluate efficiency, we used two distinct measures:
1. The elapsed time from PR creation to PR closing.
2. The number of iteration cycles involved, including commits, reviews, and requested changes.

## Project Structure

This repository is organized into the following notebooks, each addressing a specific research question:

- **[rq_1.ipynb](rq_1.ipynb)**: **Hypothesis 1: Coding Agent vs. Efficiency**. Analyzes how different coding agents (e.g., Copilot, Devin) compare in terms of PR efficiency.
- **[rq_2.ipynb](rq_2.ipynb)**: **Hypothesis 2: Reviewer Type vs. Efficiency**. Examines how the reviewer type (human, bot, or hybrid) influences the efficiency of AI-generated pull requests.
- **[rq_3.ipynb](rq_3.ipynb)**: **Hypothesis 3: Feedback Tone vs. Efficiency**. Investigates how review feedback tone (positive, neutral, negative) impacts PR efficiency.
- **[supplementary_analysis.ipynb](supplementary_analysis.ipynb)**: **Interaction Effects**. A 3-Way ANOVA analyzing the combined effects of Agent, Reviewer Type, and Sentiment on efficiency.
- **[experiment.ipynb](experiment.ipynb)**: Initial data exploration and experimental analysis.

## Getting Started

To run the analyses, you will need the following dependencies:

```bash
pip install pandas matplotlib seaborn pyarrow fastparquet huggingface_hub
```

Ensure you have access to the Hugging Face datasets used in the notebooks.
