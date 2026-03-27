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

