# Deployment Strategy

Not every project needs public deployment. Some projects are best shown through documentation, screenshots and reproducible instructions.

## Suggested Deployment by Project

| Project | Suggested Presentation |
|---|---|
| SaaS Support Intelligence Dashboard | Power BI Service or screenshots |
| Python Ticket Analytics Engine | GitHub with sample reports |
| API Integration Troubleshooter | GitHub documentation, optional local FastAPI/Render demo |
| Modern ETL Warehouse | GitHub docs, SQL scripts, sample outputs |
| Customer Churn Prediction | Notebook, metrics, optional FastAPI endpoint |
| PySpark Retail Analytics | Databricks notebook export and screenshots |
| AI Ticket Classification Assistant | Hugging Face Spaces or Render optional |

## Deployment Rules

- Never deploy secrets
- Never include private data
- Use `.env.example`
- Document limitations
- Provide screenshots if live demos are unavailable
