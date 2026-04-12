# Data Engineering - WeThinkCode_ Upskill 2026


---

## Week 1 — ETL Pipeline 

### What I Built
In this assessment I have learned about the basic of ETL (Extract, Transform, Load) pipeline that 
processes grocery store sales data. The pipeline reads 
two CSV files (orders and users), joins them together, 
aggregates the total purchases per gender per day, 
and writes the final result to an output CSV file.

### What I Learned
- What an ETL pipeline is and how it works
- How to read CSV files using Pandas
- How to join two datasets using merge()
- How to group and aggregate data using groupby()
- How to write data to a CSV file
- How to use try/except for error handling
- Basic Git commands to push code

### Tools Used
- Python 
- Pandas
- Jupyter Notebook
- Git & GitLab

### Pipeline Flow
```
Extract → Transform → Load
   ↓           ↓         ↓
Read CSV    Join &    Write to
 files      Filter     CSV
```

### Output
A CSV file showing total purchases per gender per day:

| date_purchased | gender | total_purchases |
|---|---|---|
| 2000-01-01 | female | 73 |
| 2000-01-01 | male | 74 |
| 2000-01-02 | female | 4 |
| 2000-01-02 | male | 10 |

---

## Assessment Results

The assessment required building a fully functional ETL 
pipeline in Python using Pandas. The pipeline had to 
extract data from two CSV sources, transform it by 
joining and aggregating, and load the result to a CSV. 
The grader automatically cloned the repository, executed 
the notebook, and compared the output against the 
expected solution.

<div align="center">

| Git Push  | Grader Result  |
|---|---|
| ![Git Push](Data%20Engineering%20Week%201/git_push.jpeg) | ![Grader](Data%20Engineering%20Week%201/grader.png) | 


</div>

<br>

<div align="center">

| Extract Function  | Pipeline Results  |
|---|---|
| ![Extract](Data%20Engineering%20Week%201/extract.png) | ![Jupyter](Data%20Engineering%20Week%201/Jupyter.png) |

</div>

<br>

## Analyzing Unstructured Data with AI — PartyRock & Amazon Bedrock
<br>
This project demonstrates how to use AI-powered tools to analyze raw, unstructured CSV datasets extracting meaningful insights without writing a single line of code. Using PartyRock's Analyze Data feature, powered by Amazon Bedrock, I uploaded real-world datasets, queried them using natural language, and generated analysis tables.
This is a practical example of how Generative AI is transforming data engineering which enabling a faster exploratory data analysis (EDA) and insight generation from unstructured data sources.

<br>

<table>
  <tr>
    <td><img width="600" height="300" alt="Unstructured Data" src="https://github.com/user-attachments/assets/174a009f-e39b-48ca-9ee3-6777dce66379"  style="margin-right: 10px;" width="300"/></td>
    <td><img width="600" height="300" alt="Structured Data" src="https://github.com/user-attachments/assets/625b60c9-c8c9-4aed-926d-f30a78493640"   style="margin-right: 10px;" width="300"/></td>
    
  </tr>
</table

<br>

## Database Normalisation to Third Normal Form & ERD Design.
<br>
Week 3 I learned about database normalisation up to Third Normal Form (3NF) and how it improves data integrity by reducing redundancy. I worked on transforming raw data into structured tables and understanding relationships between entities. I also created an Entity Relationship Diagram (ERD) using Google Drawings to visually represent the database design. This helped me better understand how real-world database systems are structured.

<br>

<table>
  <tr>
    <td><img width="600" height="300" alt="PostgreSQL" src="https://github.com/user-attachments/assets/a4c0b09b-ff2c-40b6-ae29-26947d78229b"  style="margin-right: 10px;" width="300"/></td>
    <td><img width="600" height="300" alt="PostgreSQL2" src="https://github.com/user-attachments/assets/03e6e05d-1a15-4364-ad28-f18b3c8a8578"  style="margin-right: 10px;" width="300"/></td>
    
  </tr>
</table
