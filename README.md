
# Olist E-commerce Review Sentiment Analysis
## Overview

This project focuses on performing sentiment analysis on customer reviews from the Olist e-commerce dataset. It involves natural language processing (NLP) to analyze the reviews, creating a sentiment model, and visualizing the results through Tableau to understand the dynamics associated with sentiments.

## Features

- Data Extraction: Extract review data from the Olist e-commerce dataset.

- Data Processing: Clean and preprocess the review text data using NLP techniques.

- Sentiment Analysis: Build and train a sentiment analysis model to predict the sentiment of each review.

- Data Storage: Load the processed and predicted data into a SQL database.

- Visualization: Create interactive dashboards in Tableau to visualize sentiment trends and gain insights into customer feedback.


## Getting Started

### Prerequisites

- Python 3.x

- Libraries: pandas, nltk, scikit-learn, sqlalchemy

- SQL Database (e.g., MySQL, PostgreSQL)

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
