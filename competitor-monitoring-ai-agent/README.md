# Competitor Monitoring AI Agent

An AI-powered competitor monitoring workflow built in **n8n** as part of the Wayfair AI Agent Engineering Externship. The workflow collects product data across multiple retailers and uses LLM-powered analysis to identify pricing differences, assortment gaps, competitive positioning, and market opportunities.

## Overview

The agent takes a rug category as user input and automatically:

* Collects product data from **Wayfair, Amazon, and Walmart**
* Standardizes product information into a consistent format
* Compares pricing, assortment, ratings, reviews, and product features
* Identifies competitive strengths and market whitespace
* Generates strategic recommendations and supplier insights
* Compiles the analysis into a formatted competitor intelligence report

## Workflow

### 1. Input Parsing

The workflow interprets the user's selected rug category and optional focus keyword.

### 2. Product Data Collection

Product listings are retrieved from Wayfair, Amazon, and Walmart and reshaped into standardized data for comparison.

### 3. AI-Powered Analysis

Multiple AI analysis stages evaluate the collected product data, including:

* Executive summary and key findings
* Amazon-specific competitive insights
* Cross-retailer comparison
* Pricing and whitespace analysis
* Strategic recommendations
* Supplier and brand identification

The analysis workflow uses **Mistral** and models accessed through **OpenRouter**.

### 4. Report Generation

Outputs from each analysis stage are combined and formatted into an HTML competitor analysis report.

## Example: Area Rug Analysis

A sample run analyzed **30 products across Wayfair, Amazon, and Walmart** (10 products per retailer).

The report compared:

* Price positioning
* Product and brand assortment
* Customer ratings and reviews
* Product features
* Size options
* Competitive strengths
* Market whitespace
* Supplier opportunities

The analysis found distinct positioning across the three retailers, with Wayfair emphasizing more design-focused and branded assortments while Amazon and Walmart offered stronger representation in budget-friendly and functional rug options.

## Tools & Technologies

* **n8n** — workflow automation and orchestration
* **Mistral** — LLM-powered analysis
* **OpenRouter** — access to additional language models
* **HTTP / APIs** — product data retrieval
* **JSON** — product data processing and standardization
* **HTML** — automated report generation

## Sample Output

[View the full Area Rug Trend Report](./Competitor Analysis Report - Area Rug.pdf)
## Project Context

This project was completed as part of the **Wayfair AI Agent Engineering Externship** and explores how AI workflows can transform e-commerce product data into structured competitive intelligence and actionable category insights.
