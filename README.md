
# Lab 7 - Using Delta Lake with Spark in Azure Synapse Analytics

## 📌 Objective  
The goal of this lab is to explore **Delta Lake integration with Apache Spark** in **Azure Synapse Analytics** for scalable data analytics and real-time data handling.

## 🧰 Technologies & Services Used
- Azure Synapse Analytics  
- Apache Spark  
- Delta Lake  
- Azure Data Lake Storage Gen2  
- Serverless SQL Pool  

## 📂 Implementation Steps

1. **Provisioned an Azure Synapse Analytics Workspace**  
   Set up a Synapse workspace from the Azure portal to perform the operations.

2. **Created Delta Tables**  
   Used Spark to define and initialize Delta tables for structured data storage.

3. **Explored Data in the Data Lake**  
   Examined the structure and contents of files stored in Azure Data Lake.

4. **Loaded File Data into a Delta Table**  
   Ingested file-based data (CSV/JSON) into a Delta table for further analysis.

5. **Created Catalog Tables**  
   Defined structured tables using Spark SQL for easier data access and querying.

6. **Created External and Managed Tables**  
   - *External Table:* Defined over existing data in the Data Lake.  
   - *Managed Table:* Data was moved and managed entirely by Spark.

7. **Compared External vs Managed Tables**  
   Highlighted the differences in storage, management, and performance behavior.

8. **Created a Table Using SQL**  
   Used Spark SQL commands to create and populate a new table.

9. **Used Delta Tables for Streaming Data (IoT Scenario)**  
   Simulated an IoT use case where streaming data was continuously written to a Delta table acting as a data sink.

10. **Queried Delta Table from Serverless SQL Pool**  
    Accessed and queried Delta tables directly using the serverless SQL pool within Synapse.

11. **Cleaned Up Resources**  
    Deleted all provisioned resources to avoid unnecessary Azure charges after completing the exploration.

## ✅ Conclusion  
This lab provided hands-on experience with integrating Delta Lake and Spark inside Azure Synapse Analytics. The exercise covered key data tasks like exploration, ingestion, transformation, real-time streaming, and querying—all within a cloud-scale environment.
