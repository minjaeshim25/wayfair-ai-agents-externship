# Consumer Trend Discovery AI Agent

## Summary

An AI workflow that discovers consumer product trends from user-selected categories and returns structured product information for analysis.

## Technologies

- n8n
- JavaScript
- HTTP Requests
- JSON Processing
- Workflow Automation

## Workflow

1. User enters a product category.
2. The input is parsed and validated.
3. Product information is retrieved.
4. The response is cleaned and transformed into a structured JSON format.
5. The workflow returns product information that can be used for trend analysis and recommendation systems.

## Example Input
Area rug

## Example Output
```json
{
  "amazonProducts": [
    {
      "url": "https://www.amazon.com/dp/B0D91PWCRV",
      "name": "Black Farmhouse Washable 8x10 Area Rug...",
      "price": "107.99",
      "image_url": "https://m.media-amazon.com/images/...",
      "rating": "4.4 out of 5 stars",
      "review_count": "4"
    },
    {
      "url": "https://www.amazon.com/dp/B0DMNJW3NJ",
      "name": "8x10 Area Rugs Washable Rug...",
      "price": "73.99",
      "rating": "4.7 out of 5 stars"
    }
  ],
  "totalProducts": 10,
  "scrapedAt": "2026-05-23T11:35:58.402Z"
}
```
