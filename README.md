# AWS Analytics: End-to-End Data Pipeline Project

## 👤 Prepared by: [Sagar Naduvinkeri](https://www.linkedin.com/in/sagar-naduvinkeri/)

## 📌 Project Overview

This project showcases end-to-end proficiency in Amazon Web Services (AWS) for analytics. It covers the complete workflow — from secure data storage to automated schema detection, serverless querying, and interactive data visualization. The solution leverages AWS S3, Glue, Athena, and QuickSight to build a scalable and cost-efficient analytics pipeline.

---

## 🔧 Tools & Technologies Used

- **AWS IAM** – Secure, role-based access management  
- **Amazon S3** – Cloud data lake for raw Excel datasets  
- **AWS Glue & Glue Crawlers** – Automated schema discovery and table creation  
- **AWS Glue Data Catalog** – Centralized metadata store  
- **Amazon Athena** – Serverless SQL query engine for data in S3  
- **Amazon QuickSight** – Business intelligence and visualization

---

## 🧱 Project Workflow

1. **IAM & S3 Bucket Setup**  
   - Created a dedicated IAM user with limited permissions  
   - Uploaded Excel data to S3 in timestamped snapshot format for performance and historical tracking

2. **Metadata Discovery with AWS Glue**  
   - Configured a Glue Crawler to scan the S3 bucket  
   - Automatically inferred schema and created tables in the Glue Data Catalog

3. **Querying with Amazon Athena**  
   - Queried data directly from S3 using SQL  
   - Used partitioning and snapshot design to improve performance and reduce cost

4. **Data Visualization with Amazon QuickSight**  
   - Connected QuickSight to Athena  
   - Built interactive dashboards with charts, KPIs, and time-series trends

---

## 📊 Outcome

This project highlights the ease, power, and efficiency of building cloud-native analytics pipelines using AWS. All components worked together seamlessly to deliver business-ready insights with minimal infrastructure overhead.

---

## 🖼️ Workflow Diagram

> *(Insert your architecture diagram here)*  
> Replace this line with the image once uploaded to your repository.

---

## 📬 Contact

Feel free to connect or reach out:

**Sagar Naduvinkeri**  
🔗 [LinkedIn](https://www.linkedin.com/in/sagar-naduvinkeri/)
