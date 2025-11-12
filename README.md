# Live _Citi Bike_ Hotspot Analysis
_Data Engineering Assignment 2_

**Team 3**: Lars Kerkhof, Ralf Geerts, Riccardo Festa, Vera Beerepoot, Yvette Garretsen 

Repository outline:

```
/your-project-name/
|
|-- .gitignore                  <-- VERY IMPORTANT for security and large files
|-- README.md                   <-- Your project's front page (I'll help you write this)
|
|-- data-architecture/
|   |-- docker-compose.yml      <-- The main file from Lab 6, defines all services
|   |-- .env.example            <-- A template for your secret keys and IP
|   |-- jupyter-all-spark-notebook-gcp/
|   |   `-- Dockerfile          <-- Dockerfile for the Jupyter container (from Lab 6)
|   `-- spark-bitnami-python3.11/
|       `-- Dockerfile          <-- Dockerfile for the Spark containers (from Lab 6)
|
|-- pipelines/
|   |-- pipeline_1_batch_goal.ipynb  <-- Your PySpark code for the batch pipeline
|   `-- pipeline_2_stream_goal.ipynb <-- Your PySpark code for the stream pipeline
|
|-- stream-producer/
|   |-- producer.py             <-- The Python script to "replay" your data into Kafka
|   `-- requirements.txt      <-- Lists libraries (e.g., kafka-python)
|
|-- data/
|   |-- .gitignore              <-- IMPORTANT: To block uploading large CSVs
|   `-- data_sample.csv         <-- A very small (10-100 rows) sample of your data
|
`-- report/
    `-- Assignment_2_Report.pdf   <-- Your final report

```