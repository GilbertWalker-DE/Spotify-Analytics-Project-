# 🎵 Spotify Analytics Project  
🚀 Beginner Project | AWS ETL Pipeline with Glue, Athena & QuickSight  

**Status:** ✅ Completed  

---

## 📄 Overview  

This project demonstrates an **end-to-end data pipeline** on AWS that extracts, transforms, and visualizes **Spotify data** for analytics and reporting.  

It leverages AWS-native services to build a **serverless and scalable** data workflow — from raw data ingestion to business insights visualization.

---

## 🏗️ Architecture Overview  

| ![Architecture Diagram](images/Diagram.png) |
|:--:|
| *Spotify Analytics Pipeline Architecture* |

**Workflow Summary:**  
1. **S3 (staging)** — Raw data uploaded to the staging bucket.  
2. **AWS Glue (ETL)** — Data cleaning and transformation process.  
3. **S3 (data warehouse)** — Transformed data stored in structured format.  
4. **Crawler** — Automatically catalogs data for querying.  
5. **Athena** — Runs SQL queries on the processed data.  
6. **QuickSight** — Visualizes KPIs and trends for analysis.  

---

## 🧰 Tools & Technologies  

| Layer | AWS Services |
|-------|---------------|
| Data Storage | S3 |
| Data Transformation | Glue |
| Data Catalog | Glue Crawler |
| Query Engine | Athena |
| Visualization | QuickSight |

---

## 📊 Dashboard Preview  

| ![Dashboard Preview](images/2025-10-19 16_51_48-datawarehouse analysis.png) |
|:--:|
| *Spotify Streaming Insights Dashboard (QuickSight)* |

---

## 🧠 Key Learnings  
- Built a **fully cloud-native ETL workflow** without local scripting.  
- Used **AWS Glue** to transform and manage data schemas efficiently.  
- Learned to query datasets with **Athena** and visualize metrics in **QuickSight**.  
- Strengthened understanding of **data lake architecture** on AWS.  

---

## 🪜 Next Steps / Improvements  
- Automate Glue ETL job triggers with AWS Lambda or EventBridge.  
- Integrate more Spotify datasets (artists, playlists, or regions).  
- Add partitioning strategies in S3 for improved query performance.  

---

## 🙌 Acknowledgment  
Project inspired by [Darshil Parmar’s AWS Data Engineering Walkthrough](https://www.youtube.com/watch?v=yIc5a7C8aHs).  
