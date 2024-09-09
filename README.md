
# Olist E-commerce Review Sentiment Analysis
## Overview

This project involves analyzing customer reviews from the Olist e-commerce platform to derive insights and sentiments. The analysis is conducted using advanced big data technologies and tools, including PySpark for data processing, sentiment analysis for understanding customer opinions, and Tableau for visualization.

## Features

- Data Extraction: Extract review data from the Olist e-commerce dataset.

- Data Processing: Utilized PySpark to handle and process large volumes of data efficiently.

- Sentiment Analysis: Build and train a sentiment analysis model to predict the sentiment of each review.

- Data Storage: Load the processed and predicted data into a SQL database.

- Visualization: Create interactive dashboards in Tableau to visualize sentiment trends and gain insights into customer feedback.


## Getting Started

### Prerequisites

- Python 3.x

- Apache Spark
  
- PySpark

- Libraries: pandas, nltk, scikit-learn, sqlalchemy
  
- MySQL Server

- Tableau Desktop or Tableau Public

### Setup

- Prepare the Dataset: Download the Olist e-commerce dataset and place it in the data directory. [[Data Source]](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

- Configure SQL Database: Open the MySQL command line or use a MySQL client (e.g., MySQL Workbench) to create a new database 

- Update Scripts to Use SQLAlchemy Engine: 
```bash
database_name = ""
table_name = ""
username = ""
password = ""
host = "localhost"
port = ""

# Create SQLAlchemy engine
engine = create_engine(f'mysql+pymysql://{username}:{password}@{host}:{port}/{database_name}')

```

- Set Up Tableau Data Source: Open Tableau Desktop or Tableau Public and open the Dashboards_new.twb Tableau workbook.Further connect the data source to the SQL database where the results have been loaded.

## Contributing

I welcome contributions to this project. Please submit a pull request for any improvements or new features. For major changes, consider opening an issue first to discuss the proposed modifications.

- Fork the repository.

- Create a new branch (git checkout -b feature/YourFeature).

- Make your changes and commit (git commit -am 'Add new feature').

- Push to the branch (git push origin feature/YourFeature).

- Create a new Pull Request.

**Project Contributor**

1. Pruthvi Patel (Myself)
2. Jatin Satija  [Profile](https://github.com/jatinsatija)
3. Utkarsh Kothari  [Profile](https://github.com/GodlikeAnalyst)
4. Zeel Patel
5. Oluwatomisin Ogedengbe
