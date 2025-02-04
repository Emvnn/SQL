# Computing Concepts

## Computing Definitions from Lexicon

- **Airflow:** An open-source workflow management platform used to schedule data engineering tasks.
- **AWS (Amazon Web Services):** Amazon's cloud computing services.
- **Azure:** Microsoft's cloud services.
- **Big Data:** The systematic storage, management, and analysis of large datasets, characterized by Volume, Variety, Velocity, and Veracity.
- **Cloud Computing:** The use of remote servers hosted on the internet to store, manage, and process data instead of local servers or personal computers.
- **Database Schema:** The logical structure of a database, defining how data is stored and related.
- **Data Catalog:** A metadata management tool for organizing data within a system.
- **Data Engineering:** The process of transforming data into a format suited for analysis.
- **Data Ingestion:** The process of obtaining and importing data for storage or processing.
- **Data Lake:** A repository for storing raw and structured data in its natural format.
- **Data Pipeline:** A series of processing steps to move and transform data.
- **Data Processing:** The collection and manipulation of data to generate meaningful information.
- **Data Science:** The field of extracting knowledge and insights from data.
- **Data Warehouse:** A central repository of integrated data from multiple sources.
- **ETL (Extract, Transform, Load):** The process of moving data from one system to another.
- **Google Cloud:** Google's cloud computing platform.
- **Luigi:** An open-source workflow management platform used to schedule data engineering tasks.
- **NoSQL:** A type of database that stores data in a non-relational format.
- **Parallel Computing:** The simultaneous execution of multiple computations across different processors to solve problems faster.
- **Query:** A request for information from a database.
- **Redshift:** Amazon's data warehousing service.
- **S3:** Amazon's object storage service.
- **Scheduling:** The process of organizing and running jobs in a specific order in data engineering systems.
- **SQL:** Structured Query Language for managing relational databases.
- **Structured Data:** Data stored in a predefined format, typically in tables.
- **Unstructured Data:** Data that does not follow a predefined structure, such as text and media files.
- **View:** Output of a stored, frequent query on the data.

---

## **📌 Introduction**  
This document covers fundamental data concepts that are essential for data analysis, processing, and management. Whether you're a beginner or an advanced professional, understanding these concepts is crucial for working with data effectively.  

---

## **🔹 1. Core Data Concepts**  

### **1.1 Data**  
Unprocessed raw facts, numbers, or symbols that require interpretation.  
- **Example:** "120, Red, 56.7%"  

### **1.2 Information**  
Processed data that has context and meaning.  
- **Example:** "The temperature is 30°C today."  

### **1.3 Dataset**  
A structured collection of related data points.  
- **Rows (Records):** Represent individual observations.  
- **Columns (Attributes):** Represent features describing the observations.  

### **1.4 Structured vs. Unstructured Data**  
- **Structured Data:** Organized into tables (e.g., databases, Excel).  
- **Unstructured Data:** No predefined format (e.g., images, videos, text).  

### **1.5 Metadata**  
Data that describes other data (e.g., file size, creation date, author).  

---

## **🔹 2. Data Quality and Integrity**  

### **2.1 Data Quality**  
The reliability of data, measured by its:  
- **Accuracy** (free from errors)  
- **Completeness** (no missing values)  
- **Consistency** (no contradictions across datasets)  
- **Timeliness** (updated and relevant)  

### **2.2 Data Integrity**  
Ensuring data is accurate and consistent throughout its lifecycle.  

### **2.3 Data Governance**  
A set of rules and policies for managing data security and quality.  

### **2.4 Data Ethics & Privacy**  
Responsible handling of data to protect user rights (e.g., **GDPR, CCPA**).  

---

## **🔹 3. Data Preprocessing**  

### **3.1 Data Cleaning**  
The process of fixing errors and inconsistencies, such as:  
- **Handling missing values** (mean, median imputation, deletion)  
- **Removing duplicates**  
- **Correcting formatting issues**  

### **3.2 Data Transformation**  
Converting data into a usable format:  
- **Normalization:** Scaling data between 0 and 1.  
- **Standardization:** Adjusting values to have a mean of 0 and standard deviation of 1.  
- **Encoding:** Converting categorical data into numerical values.  

### **3.3 Data Reduction**  
Minimizing data volume while preserving key information:  
- **Feature Selection:** Keeping only relevant variables.  
- **Dimensionality Reduction:** Techniques like PCA to simplify data.  

### **3.4 Handling Outliers**  
Detecting and managing extreme values using statistical methods like:  
- **Z-score method** (removing extreme standard deviations).  
- **Interquartile Range (IQR)** (filtering values outside the normal range).  

---

## **🔹 4. Data Storage & Management**  

### **4.1 Databases**  
A structured system for storing and retrieving data:  
- **SQL Databases** (Structured, relational) – MySQL, PostgreSQL.  
- **NoSQL Databases** (Flexible, scalable) – MongoDB, Firebase.  

### **4.2 Data Warehousing**  
A centralized repository for storing large datasets used in analytics.  

### **4.3 Data Lakes**  
Storage for raw, unstructured, and structured data, used in **Big Data** applications.  

### **4.4 Data Pipelines**  
Automated processes that move and transform data from sources to destinations (**ETL – Extract, Transform, Load**).  

---

## **🔹 5. Data Analysis & Visualization**  

### **5.1 Types of Data Analytics**  
- **Descriptive Analytics:** Summarizing past data (dashboards, reports).  
- **Diagnostic Analytics:** Identifying reasons for trends and patterns.  
- **Predictive Analytics:** Using historical data to forecast future trends.  
- **Prescriptive Analytics:** Suggesting actions based on data insights.  

### **5.2 Data Visualization**  
Presenting data in a visual format to aid interpretation:  
- **Line Charts** (trends over time)  
- **Bar Charts** (category comparison)  
- **Scatter Plots** (relationships between variables)  
- **Heatmaps** (pattern detection)  

### **5.3 Data Mining**  
Extracting patterns and insights from large datasets using statistical and machine learning techniques.  

---

## **🔹 6. Advanced Data Concepts**  

### **6.1 Big Data**  
Large-scale datasets that require specialized storage and processing. Defined by:  
- **Volume** (size)  
- **Velocity** (speed of data generation)  
- **Variety** (structured/unstructured formats)  
- **Veracity** (quality and reliability)  
- **Value** (business usefulness)  

### **6.2 Machine Learning (ML)**  
AI-based techniques that allow computers to learn patterns from data and make predictions.  

### **6.3 Artificial Intelligence (AI)**  
The broader field of creating systems that can reason, learn, and make decisions autonomously.  

---

## 🔹 7. Advanced Computing Concepts

### 7.1 Parallel Computing
**Definition:**  
Parallel computing is the simultaneous execution of multiple computations across different processors or cores to solve complex problems faster.

**Key Concepts:**  
- **Multi-threading:** Running multiple tasks within a single program.  
- **Multi-processing:** Using multiple CPUs or GPU cores.  
- **Distributed Computing:** Splitting tasks across multiple machines (e.g., Hadoop, Spark).  
- **SIMD (Single Instruction, Multiple Data):** Executes the same instruction on multiple data points simultaneously.  

**Applications:**  
- Large-scale simulations (weather forecasting, AI models)  
- Image & video processing  
- High-performance computing (HPC)  

---

### 7.2 Cloud Computing
**Definition:**  
Cloud computing provides on-demand access to computing resources (servers, storage, databases, networking) over the internet, allowing businesses and individuals to scale without managing physical infrastructure.

**Types of Cloud Computing:**  
- **Public Cloud:** Services provided by third-party providers (AWS, Google Cloud, Azure).  
- **Private Cloud:** Dedicated cloud infrastructure for a single organization.  
- **Hybrid Cloud:** A combination of public and private cloud resources.  

**Cloud Service Models:**  
- **IaaS (Infrastructure as a Service):** Virtual servers & networking (e.g., AWS EC2, Google Compute Engine).  
- **PaaS (Platform as a Service):** Development environments (e.g., Google App Engine, Heroku).  
- **SaaS (Software as a Service):** Cloud-based applications (e.g., Google Drive, Microsoft Office 365).  

**Benefits of Cloud Computing:**  
✅ **Scalability** – Scale resources up/down as needed.  
✅ **Cost-Efficiency** – Pay for what you use.  
✅ **Reliability** – Data backup & disaster recovery.  
✅ **Security** – Built-in encryption and access control.  

**Applications:**  
- Data storage & backup (Google Drive, Dropbox)  
- AI & Machine Learning (Google Cloud AI, AWS SageMaker)  
- Big Data processing (Hadoop, Spark on cloud)

---

# What is SQL?

**SQL (Structured Query Language)** is a powerful programming language designed to manage and interact with data in relational databases. It provides a wide range of functionalities, including:  
- **Accessing Data**: Retrieve specific data from databases efficiently.  
- **Manipulating Data**: Insert, update, and delete records as needed.  
- **Cleaning Data**: Refine and organize data for better usability.  
- **Analyzing Data**: Perform aggregations and generate insights directly from databases.  

SQL is an essential tool for managing, transforming, and analyzing data in various industries, making it a must-have skill for data professionals.  

![PNG](https://github.com/user-attachments/assets/f43116df-4d55-4bce-a693-0b35b9aa9913)

---

### Database vs. Schema  

- **Database**: The main container holding all data and objects (e.g., tables, indexes, stored procedures). It represents the complete data storage system.  

- **Schema**: A logical subdivision within a database that organizes data into specific groups or purposes.  

**Key Difference**: A database is the overall system, while a schema is a way to organize data inside it.  

![1_YejjU_69ffDyrC0z-X9jYQ](https://github.com/user-attachments/assets/df7ae5ec-350b-4c25-a8b1-af2848f20dcd)

---
### Data Pipelines
A data pipeline is a method where raw data is ingested from data sources, transformed, and then stored in a data lake or data warehouse for analysis.

<img width="896" alt="etl_pipeline" src="https://github.com/user-attachments/assets/a1b0e9fb-ebd2-41eb-b80c-0c59ed9fdfae" />

![etl-process-explained-diagram](https://github.com/user-attachments/assets/401fc3dd-bf76-4923-8530-6d0024763edb)

![65d3a069871456bd33730869_GC2xT1oWgAA1rAC](https://github.com/user-attachments/assets/5a8729c0-48f5-40e0-b618-f64ed33e575f)

--- 

## Key Differences

| Feature         | Structured Data        | Semi-Structured Data      | Unstructured Data      |
|---------------|----------------------|-------------------------|-----------------------|
| **Schema**     | Fixed and rigid       | Flexible, self-describing | No schema             |
| **Organization** | Rows and columns      | Tags, metadata, or markers | No organization       |
| **Queryability** | Easy (e.g., SQL)      | Moderate (e.g., JSONPath)  | Difficult             |
| **Storage**     | Relational databases  | NoSQL databases, files    | Files, object storage |
| **Examples**    | SQL tables, Excel     | JSON, XML, emails        | Text, images, videos  |


### **1. Based on Nature**  
#### **a. Qualitative (Categorical) Data**  
   - Descriptive, non-numeric data.  
   - **Types:**  
     - **Nominal:** Categories without a specific order (e.g., gender, colors).  
     - **Ordinal:** Categories with a meaningful order but no fixed difference (e.g., rankings, satisfaction levels).  

#### **b. Quantitative (Numerical) Data**  
   - Numerical values that represent measurable quantities.  
   - **Types:**  
     - **Discrete:** Countable values (e.g., number of students in a class).  
     - **Continuous:** Measured values with infinite possibilities (e.g., height, temperature).  

---

### **2. Based on Structure**  
#### **a. Structured Data**  
   - Organized in rows and columns (e.g., databases, Excel sheets).  
   - Examples: Customer records, sales data.  

#### **b. Unstructured Data**  
   - No fixed format or structure.  
   - Examples: Images, videos, social media posts.  

#### **c. Semi-Structured Data**  
   - Contains some structure but is not strictly organized.  
   - Examples: JSON, XML files, emails.  

---

### **3. Based on Source**  
- **Primary Data:** Collected directly by researchers (e.g., surveys, interviews).  
- **Secondary Data:** Collected from existing sources (e.g., reports, articles).  

---

![1721174296278](https://github.com/user-attachments/assets/e7725fcd-6844-49ff-9ee5-a30004d4f7e6)

---

# Data preprocessing
Data preprocessing can refer to manipulation, filtration or augmentation of data before it is analyzed,[1] and is often an important step in the data mining process. 

![Data-Preprocessing-in-Data-Mining](https://github.com/user-attachments/assets/6297383c-82cd-497b-b638-3f55affccd28)
---

![1711873124018](https://github.com/user-attachments/assets/0b55222d-2ee0-4fb0-8647-bfcf82ce0110)
