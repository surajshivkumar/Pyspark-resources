# Pyspark-resources


## Datasets
<pre>
├── 1800.csv
├── BostonHousing.csv
├── book.txt
├── fakefriends.csv
├── incident_event_log_reduced.csv
├── u.data
└── u.item
</pre>
## Notebooks
<pre>
├── 01-spark-install.ipynb
├── 02-pandas-and-spark.ipynb
├── 03-spark-sql-and-tables.ipynb
├── 04-accessing-existing-tables.ipynb
├── 05-friends_by_age.ipynb
├── 06-Max-Temperature.ipynb
├── 07-word-count.ipynb
├── 08-fake-friends.ipynb
├── 09-movie-database.ipynb
├── 10-movie-database-regression.ipynb
├── 11-incident-management-spark-SQL-operations.ipynb
├── 12-Incident_Management_Spark_Dataframe_Operations.ipynb
├── 13-incident_management_spark_ML_linear_regression.ipynb
├── 14-Incident_Management_Spark_ML_Logistic_Regression.ipynb
├── 15-Incident_Management_Spark_ML_Linear_SVC.ipynb
├── 16-Incident_Management_Spark_ML_MLP.ipynb
└── 17-Incident_Management_Spark_ML_Decision_Tree.ipynb
</pre>

### Dependecies
1. Ensure pip is Up to Date
```bash
python -m pip install --upgrade pip
```
2. Install PySpark
```bash
   pip install pyspark
```

### Test
- Inside of a jupyter notebook or interpreter run the following:
```python3
  from pyspark.sql import SparkSession
  spark = SparkSession.builder.appName("Example").getOrCreate()
```



