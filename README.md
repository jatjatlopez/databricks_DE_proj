## Databricks_DE_Proj
End-to-end Data Lakehouse project built on Databricks, following the Medallion Architecture (Bronze, Silver, Gold). Covers real-world data engineering and analytics workflows using Spark, PySpark, SQL, Delta Lake, and Unity Catalog.

---
🏗️ Architecture <br>
---
This project follows the Medallion Architecture:<br>

<strong>🥉 Bronze Layer<br></strong>
- Raw data ingestion<br>
- Schema inference and storage as Delta tables<br>

<strong>🥈 Silver Layer<br></strong>
- Data cleaning and standardization<br>
- Type casting and validation<br>

<strong>🥇 Gold Layer<br></strong>
- Dimensional Data Model (Business Transformation)<br>
- Ready for BI and analysis<br><br>


---
🛠️ Technologies Used
---
- Databricks<br>
- Apache Spark<br>
- PySpark<br>
- Spark SQL<br>
- Delta Lake<br>
- Unity Catalog<br><br>
---
📂 Project Structure
---
├── datasets/           # Sample raw data files<br>
├── script/             # Databricks Notebooks (.ipynb / .py)<br>
│   ->├── 01_Bronze.py    # Raw Ingestion & Delta Table creation<br>
│   ->├── 02_Silver.py    # Cleaning, Type-casting & Validation<br>
│   ->└── 03_Gold.py      # Dimensional Modeling (Business Logic)<br>
└── README.md           # Documentation<br><br>

---
🏁 Getting Started
---
- Clone the repo: git clone https://github.com/jatjatlopez/databricks_DE_proj.git

- Import to Databricks: Upload the notebooks in the script/ folder to your Databricks Workspace.

- Configure Catalog: Ensure Unity Catalog is enabled and update the catalog/schema names within the notebooks.

- Run: Execute notebooks sequentially (Bronze → Silver → Gold).
