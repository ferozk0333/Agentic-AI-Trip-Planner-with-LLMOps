# Agentic AI Trip Planner with LLMOps

This project is an **Agentic AI-powered Trip Planner**, designed to plan trips for **any city worldwide using real-time data**. The system intelligently collaborates between multiple AI agents to fetch live weather, popular attractions, hotel costs, currency conversions, and generates a complete trip summary with an itinerary and total expense estimation.

It combines the power of **LangGraph-based AI agents**, **Large Language Models (LLMs)**, and real-time APIs, structured using modern **LLMOps principles**.

Agents are based on Reasoning + Action framework (source: https://arxiv.org/abs/2210.03629)

---

## Technical Flow Diagram

> A high-level architecture showing how the Agent Orchestration, API, Tools, Prompts, and external APIs interact.

![Screenshot 2025-06-29 230341](https://github.com/user-attachments/assets/e2d0de96-31a2-4b79-a644-a9426049c040)

---

## Key Features

- **Trip Planning:** For any city globally.
- **Weather Forecast:** Fetches real-time weather.
- **Attractions & Activities:** Discovers top places to visit.
- **Hotel Information:** Checks availability and pricing.
- **Currency Converter:** Real-time conversion rates.
- **Expense Estimator:** Calculates total trip cost.
- **Itinerary Summary:** Generates a downloadable plan with recommendations.

---

## Architecture Overview

- **Agent Orchestration:** Built using **LangGraph**, managing nodes (tools) and edges (workflow execution).
- **Modular Design:** Tools for weather, places, currency, expenses, and summaries are isolated and reusable.
- **Prompt Library:** Modular prompts power the LLM for generating human-like summaries.
- **API Layer:** Managed via **FastAPI** for handling user requests.
- **Deployment-Ready:** Supports CI/CD pipelines and deployment to cloud services like AWS or Render.

---

