# DP-203-Lab11

# 🧪 Lab 11: Using Apache Spark Notebooks in a Pipeline

## 📌 Purpose

The purpose of this lab is to perform a data transformation process using **Azure Synapse Analytics**, both **interactively** (manually via notebook) and **automatically** (through a pipeline). The goal is to learn how to process data with Spark notebooks and make the process repeatable by integrating it into a pipeline.

## 🧠 Why This Lab?

In real-world scenarios, data engineers don’t just perform one-time analyses. Incoming data needs to be regularly cleaned, transformed, and prepared for analysis. Doing these operations manually is time-consuming and prone to errors. Therefore, it is essential to **automate** such workflows. This lab demonstrates how to integrate a Spark notebook into a pipeline to achieve automation.

## 🔧 What Are We Doing in This Lab?

1. **Setting up the Azure environment**  
   - Deploy a Synapse workspace using a PowerShell script and an ARM template (includes Spark pool and Data Lake connections).

2. **Exploring the data**  
   - Examine CSV files stored in the Data Lake to understand their structure.

3. **Transforming data with a Spark notebook**  
   - Split customer names into components  
   - Convert the data to Parquet format  
   - Save the transformed data back to the Data Lake

4. **Integrating the notebook into a pipeline**  
   - Parameterize the notebook (e.g., folder name)  
   - Call the notebook within a pipeline  
   - Dynamically run the notebook (e.g., generate a new folder on each run)

5. **Reviewing the results**  
   - Browse the generated Parquet files  
   - Query the transformed data using SQL

📸 Screenshots

<img width="1245" alt="1" src="https://github.com/user-attachments/assets/0206844a-f9e3-4fb3-97d9-8eeff5e803e4" />


<img width="1216" alt="2" src="https://github.com/user-attachments/assets/0410781b-a49a-4e1e-a786-8d02ad497251" />


<img width="1222" alt="5" src="https://github.com/user-attachments/assets/f64602fb-405f-4dda-bf14-320294dad34b" />


<img width="945" alt="6" src="https://github.com/user-attachments/assets/920879ff-fd27-4312-81ca-059f6912e7b7" />


<img width="1208" alt="7" src="https://github.com/user-attachments/assets/96c6ea99-088b-420c-b9f0-6cd2fab85f54" />


<img width="975" alt="8" src="https://github.com/user-attachments/assets/919940e5-add4-43de-b1de-ea49d6921acd" />


<img width="1085" alt="9" src="https://github.com/user-attachments/assets/aa6c7b16-18a1-4665-a718-cd24584940d9" />


<img width="1461" alt="10" src="https://github.com/user-attachments/assets/e04e79fb-0d2a-4a06-9177-c9e5b88b87f9" />
