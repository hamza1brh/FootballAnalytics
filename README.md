
a data engineering project for football data pipelines and analytics

<p align="center">
<img height="150" width="300" src=""/>
</p>

## Overview
> [!NOTE]
> This repository is a personal project designed to showcase and enhance my data engineering skills. the project is designed to handle the extraction, transformation, and loading of data from diverse sources into different databases. I aim to expand and delve into various aspects of data engineering, including data acquisition, processing, and storage, while also adhering to good software practices to ensure scalability, reliability, and maintainability of the codebase.

> [!IMPORTANT]
> Many architectural choices and decisions in this project may not make the most efficent sense on purpose for the sake of practicing and learning.


## Infrastructure
### Tools & Services
![cloud] ![docker] ![prefect]

### Databases
![postgres](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![bigquery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)


### Data Pipelines



#### Data Pipeline 1
1. Data is extracted from multiple API sources with Python:
    * Data from the [Football Data API](https://www.football-data.org/) .
    * Data from the [NewsAPI](https://newsapi.org) 
    * Data from youtube API 
2. Python performs any necessary transformations and loads the data into BigQuery.
3. The prior steps are orchestrated with [Prefect](https://www.prefect.io).



#### Pipeline Diagram
