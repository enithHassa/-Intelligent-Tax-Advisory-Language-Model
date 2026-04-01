# AI Tax Advisory System

Standardized monorepo scaffold for final-year research on intelligent, explainable tax advisory.

## Research Components

1. Financial Transaction Semantic Reasoning and Taxable Income Inference
2. Tax Strategy Optimization and Explainable Decision Engine
3. Personalized Recommendation and Predictive Impact Modeling Engine
4. Intelligent Tax Advisory Language Model

## Standard Project Structure

```text
ai-tax-advisory-system/
├── backend/
│   ├── api-gateway/
│   ├── shared/
│   │   ├── schemas/
│   │   ├── utils/
│   │   └── config/
│   ├── comp-transaction-sementic/
│   ├── comp-tax-optimization/
│   ├── comp-personalized-recommendation/
│   └── comp-language-model/
├── frontend/
├── data/
│   ├── synthetic/
│   └── processed/
├── models/
│   ├── transaction-semantic/
│   ├── tax-optimization/
│   ├── personalized-recommendation/
│   └── language-model/
├── notebooks/
├── docker/
└── README.md
```

## Recommended Common Environment (for all users)

- OS: macOS, Linux, or Windows (WSL2 preferred for Windows)
- Python: 3.11+
- Node.js: 20 LTS+
- Package managers: `pip` and `npm`
- Container runtime: Docker Desktop (or Docker Engine + Compose)
- Git: 2.40+

## Quick Setup

```bash
# backend and ML environment
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip

# frontend environment (when UI code is added)
# npm install

# docker-based local services (when compose files are added)
# docker compose up -d
```
