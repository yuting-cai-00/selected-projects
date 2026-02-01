# Selected Projects — Yuting Cai

A curated set of projects that represent my work in power systems + ML/LLMs.

---

## OpenPowerBench (open-source contribution)
Open-source multi-task dataset + benchmark for power-system foundation models, spanning
topology-dependent tasks (e.g., power flow / OPF / contingency) and topology-independent tasks
(e.g., load forecasting / price prediction).  

**Repo:** https://github.com/OpenPowerBench/OpenPowerBench

**Quick run:**
```bash
git clone https://github.com/OpenPowerBench/OpenPowerBench
cd OpenPowerBench/topology_independent
pip install -r requirements.txt
# then follow the repo's demo scripts / configs
```

## LLM4Grid (research code / supplementary experiments)
A collection of notebooks/scripts exploring LLM use cases in power-systems tasks
(e.g., correlation analysis, forecasting, power flow-related tasks, hazard recognition, RAG-style doc analysis, etc.).

**Repo:** https://github.com/tamu-edu/LLM4Grid

**Work summary:**

- **Wildfire Risk Visualization**
  - Multimodal workflow that extracts wildfire regions from monthly maps and **overlays them on transmission line maps** for situational awareness.
  - Includes prompt-engineering experiments that reduce **code-generation variability** and improve reproducibility.

- **Document Analysis via Retrieval-Augmented Generation**
  - **Document summarization**: audience-conditioned summarization of power-system technical documents.
  - **RAG-based QA**: embedding + vector retrieval pipeline to ground answers in a curated knowledge pool, with analysis of when retrieval helps vs. when it can degrade multi-step reasoning.

- **Time-series Forecasting in Power Systems (Load & Price)**
  - Compares three LLM-enabled forecasting approaches:
    1. LLM-generated baseline forecasting code,
    2. “in-model” forecasting via text encoding of numeric sequences, and
    3. fine-tuning-based forecasting.
  - Evaluates results using standard forecasting error metrics and reproducibility artifacts.







