# 💼 Cloud Transformation Projects by Surya Pratap Singh

👨‍💻 About Me

Cloud Transformation Consultant | AWS | Data Infra | MBA | Ex-Ministry of Finance

I help public and private sector organizations modernize their data platforms using cloud-native solutions with a strong focus on ROI, scalability, and business outcomes.

# 📁 Project 2: Financial Intelligence Modernization for Government of India

Domain: Public Sector (Intelligence / Trade Surveillance)Client: Financial crime and smuggling prevention agency under Ministry of FinanceProblem: On-prem SQL + Excel pipelines, ingestion lag, fragmented cross-agency data

✅ Goals

Real-time ingestion from multiple agencies (airports, customs, SEZs)

Secure, auditable pipeline with IAM + monitoring

Faster case-building via unified dashboards

🛠️ Cloud Architecture

Ingestion: Lambda triggers on S3 uploads (Govt reports)

Storage: S3 (partitioned lake)

ETL: Lambda (Python) for schema cleaning + tagging

Catalog: AWS Glue

Query: Athena

Dashboard: Quicksight

Audit: IAM + CloudTrail

💡 Outcomes

Metric

Before

After

Ingestion Lag

24–48 hrs

<30 min

Analyst Productivity

Manual joins + VLOOKUP

2x faster casework

Traceability

Absent

IAM + CloudTrail enabled

