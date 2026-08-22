# Wayfair AI Agent Engineering Externship

A collection of AI-powered workflows developed during the **Wayfair AI Agent Engineering Externship**, exploring how AI agents and workflow automation can support e-commerce use cases including product visualization, consumer trend discovery, and competitive intelligence.

## Projects

### Moodboard AI Agent

An AI-powered workflow that transforms user-defined design preferences into visual moodboards for home furnishing inspiration.

**Key features:**

* Processes user design preferences and prompts
* Uses generative AI to create visual design concepts
* Automates image generation through an n8n workflow

**Tools:** n8n, Gemini API, AI image generation

→ [`moodboard-agent/`](./moodboard-agent/)

---

### Consumer Trend Discovery AI Agent

A multi-stage AI workflow designed to identify and analyze emerging consumer trends across product and market data.

**Key features:**

* Collects and processes trend-related data
* Uses LLM-powered workflows to organize and analyze market signals
* Generates structured trend insights and visual outputs
* Explores how AI agents can support e-commerce trend discovery

**Tools:** n8n, OpenRouter, Mistral, APIs, JSON

→ [`consumer-trend-discovery-ai-agent/`](./consumer-trend-discovery-ai-agent/)

---

### Competitor Monitoring AI Agent

An AI-powered competitor intelligence workflow that collects and compares product data across **Wayfair, Amazon, and Walmart**.

**Key features:**

* Retrieves and standardizes multi-retailer product data
* Compares pricing, assortment, ratings, reviews, and product features
* Uses multiple LLM analysis stages to identify competitive positioning and market whitespace
* Generates strategic recommendations and supplier insights
* Automatically assembles findings into a formatted competitor analysis report

A sample Area Rug analysis evaluated **30 products across three retailers**.

**Tools:** n8n, Mistral, OpenRouter, HTTP/APIs, JSON, HTML

→ [`competitor-monitoring-ai-agent/`](./competitor-monitoring-ai-agent/)

---

## What I Explored

Across these projects, I gained hands-on experience with:

* Building and connecting multi-step workflows in **n8n**
* Integrating **LLMs and APIs** into automated workflows
* Structuring and transforming JSON data between workflow stages
* Designing multi-agent workflows for different analytical tasks
* Applying generative AI to e-commerce and product use cases
* Turning raw product and market data into structured business insights
* Generating automated visual and analytical outputs

## Repository Structure

```text
wayfair-ai-agents-externship/
│
├── moodboard-agent/
├── consumer-trend-discovery-ai-agent/
├── competitor-monitoring-ai-agent/
└── README.md
```

Each project folder contains additional documentation, workflow files, screenshots, and/or sample outputs where applicable.

## About the Externship

These projects were completed as part of the **Wayfair AI Agent Engineering Externship**, focused on exploring practical applications of AI agents, automation, and data-driven workflows in e-commerce.

> **Note:** This repository contains project work and sample outputs for portfolio purposes. Credentials, API keys, and other sensitive configuration information are excluded.
