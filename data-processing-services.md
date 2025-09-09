# ⚡ Google Cloud Data Processing Services

---

## 🔹 1. **BigQuery**

* **What it is:** Serverless data warehouse + analytics engine.
* **How it processes:** Uses SQL for large-scale analytics; supports batch & streaming ingestion.
* **Usage:**

  * Interactive analytics on terabytes/petabytes.
  * BI dashboards, data exploration.
  * Real-time log/event analysis.

---

## 🔹 2. **Dataflow**

* **What it is:** Fully managed stream + batch data processing (Apache Beam runner).
* **How it processes:** Pipelines built in Java/Python/Beam SDK; autoscaling; parallelized execution.
* **Usage:**

  * ETL (Extract, Transform, Load).
  * Real-time event stream processing.
  * Data enrichment before storing in BigQuery.

---

## 🔹 3. **Dataproc**

* **What it is:** Managed Apache Spark, Hadoop, Hive, and Presto.
* **How it processes:** Spins up clusters in minutes; integrates with GCS, BigQuery.
* **Usage:**

  * Legacy big data workloads (Hadoop jobs).
  * Spark MLlib machine learning jobs.
  * Batch analytics pipelines.

---

## 🔹 4. **Dataprep (by Trifacta)**

* **What it is:** Data wrangling and preparation tool.
* **How it processes:** Visual UI to clean, transform, and enrich data without writing code.
* **Usage:**

  * Data cleaning before machine learning.
  * Business analysts preparing datasets.

---

## 🔹 5. **Pub/Sub**

* **What it is:** Global messaging and event ingestion service.
* **How it processes:** Publishes messages (producers) → delivers to subscribers. Scales to millions of events/sec.
* **Usage:**

  * Event-driven apps.
  * Real-time streaming pipelines.
  * IoT telemetry ingestion.

---

## 🔹 6. **Composer (Managed Airflow)**

* **What it is:** Managed Apache Airflow for orchestration.
* **How it processes:** Schedules and orchestrates workflows across GCP services.
* **Usage:**

  * ETL job orchestration (Dataflow → BigQuery → ML).
  * Multi-step pipelines.

---

## 🔹 7. **Vertex AI Pipelines**

* **What it is:** Data & ML pipeline orchestration (Kubeflow Pipelines).
* **How it processes:** Builds repeatable ML/data pipelines.
* **Usage:**

  * Data preparation → model training → deployment.
  * MLOps automation.

---

## 🔹 8. **Data Fusion**

* **What it is:** No-code/low-code data integration service (built on CDAP).
* **How it processes:** Drag-and-drop UI to design ETL/ELT pipelines.
* **Usage:**

  * Business users integrating SaaS + on-prem data.
  * Simplifying pipeline creation without Dataflow coding.

---

## 🔹 9. **Looker (BI & Processing Layer)**

* **What it is:** Business intelligence & data modeling platform.
* **How it processes:** Connects to BigQuery and other sources, provides modeling (LookML) + visualization.
* **Usage:**

  * Dashboarding.
  * Self-service data exploration.
  * Embedded analytics.

---

## 🔹 10. **AI/ML Processing (Vertex AI)**

* **What it is:** Unified ML/AI platform.
* **How it processes:** Data processing, feature engineering, model training, serving.
* **Usage:**

  * ML pipelines.
  * Generative AI apps.
  * Predictive analytics.

---


| Service                 | Type                    | Best For                       |
| ----------------------- | ----------------------- | ------------------------------ |
| **BigQuery**            | Data warehouse          | SQL analytics at scale         |
| **Dataflow**            | Stream/batch processing | ETL, transformations           |
| **Dataproc**            | Hadoop/Spark            | Legacy big data workloads      |
| **Dataprep**            | Data wrangling          | Cleaning & preparing datasets  |
| **Pub/Sub**             | Messaging/eventing      | Real-time pipelines            |
| **Composer**            | Workflow orchestration  | Scheduling ETL jobs            |
| **Data Fusion**         | ETL/ELT integration     | No-code pipeline building      |
| **Vertex AI Pipelines** | ML orchestration        | MLOps pipelines                |
| **Looker**              | BI & visualization      | Dashboards & exploration       |
| **Vertex AI**           | AI/ML platform          | Training & deploying ML models |

