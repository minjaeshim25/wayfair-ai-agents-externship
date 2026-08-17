# Consumer Trend Discovery AI Agent

## Summary

An AI-powered workflow built in n8n to explore consumer and product trends
across e-commerce, social media, and market research sources.

The workflow processes product and market data, identifies emerging trends,
and combines the resulting analyses into a structured consumer trend report.

## Technologies

- n8n
- JavaScript
- HTTP Requests / APIs
- JSON Processing
- OpenRouter
- Mistral
- Hugging Face
- AI Workflow Automation

## Workflow

The agent moves through several stages:

1. **Category Input & Validation**  
   Accepts a user-selected product category and validates the input.

2. **Data Collection & Processing**  
   Retrieves product and market information from multiple sources and
   organizes the results into structured data.

3. **AI Analysis**  
   Uses LLM-powered workflow steps to standardize product information and
   identify consumer and product trends.

4. **Visual Trend Analysis**  
   Analyzes visual and social trend information and generates supporting
   visual content.

5. **Trend Synthesis**  
   Combines product, market, social, and visual insights to generate trend
   assessments, risks, and recommendations.

6. **Report Generation**  
   Collects the generated sections, assembles them into an HTML report,
   validates the report structure, and produces the final trend report.

## Example Input

`Area Rug`

## Example Output

The Area Rug analysis generated a structured trend report covering:

- Market and consumer research
- Product attributes and pricing
- Emerging product micro-trends
- Visual and social trends
- Trend risks
- Product recommendations

[View the full Area Rug Trend Report](./area-rug-trend-report.pdf)

## Workflow Screenshots

### Full Workflow

![Consumer Trend Discovery Workflow](./consumer%20trend%20discovery%20ai%20agent%20workflow.png)

### API & Image Analysis

![Stage 2](./stage2-api-image-analysis.png)

### AI Processing

![Stage 3](./stage3-ai-processing.png)

### Image Generation

![Stage 4](./stage4-image-generation.png)

### Trend Analysis & Report Generation

![Stages 5 and 6 - First Half](./stage5&6-merge-and-report-first-half.png)

![Stages 5 and 6 - Second Half](./stage5&6-merge-and-report-second-half.png)

### Final Output

![Stage 7](./stage7-output.png)

### Final Area Rug Trend Report
[View the full Area Rug Trend Report](./area-rug-trend-report.pdf)
