# DS Project-2: Job Market and Data Science Analysis from HeadHunter

This project provides a thorough analysis of the job market with a special focus on the Data Science field, leveraging data from HeadHunter. It covers a wide spectrum of nearly 50,000 unique job vacancies from over 23,000 employers.

## Table of Contents

- [Features](#features)
- [General Job Market](#general-job-market)
- [Data Science Field](#data-science-field)
- [Conclusions](#conclusions)
- [Installation](#installation)
- [Usage](#usage)

## Features

- **Exploration** of nearly 50,000 unique job vacancies
- **In-Depth Analysis** of Data Science job market
- **Geographic and Salary Insights**
- **SQL Queries** for efficient data extraction
- **Beginner-Friendly** codebase

## General Job Market

- **49,000 Unique Vacancies**
- **23,000 Unique Employers**
- **Geographic Diversity**: 1,362 unique areas
- **Industry Diversification**: 294 unique industries

## Data Science Field

- **1,771 Vacancies** with titles that include 'data' or 'данн'
- **51 Junior Level Positions** requiring no experience
- **201 Vacancies** listing SQL or Postgres as key skills
- **351 Vacancies** mentioning Python as a key skill

## Conclusions

- **Dynamic Market**: Focus on major cities like Moscow and St. Petersburg
- **Salary Insights**: Range between 71K to 110K
- **Skill-Based Pay in Data Science**: Around 243K RUB for 3-6 years of experience

## Installation

### Prerequisites

- Jupyter Notebook

### Installation Steps

1. **Clone the Repository**

    ```bash
    git clone <https://github.com/TimurShamuradov/DS-Project-2.git>
    cd DS-Project_2
    ```
    
2. **Create Config File**

    Create a `config.txt` in the project folder with your database credentials.

    ```
    DBNAME = your_db_name
    USER = your_username
    PASSWORD = your_password
    HOST = your_host
    PORT = your_port
    ```
    
    ⚠️ **Important**: Never share your `config.txt` file.
    
3. **Install Libraries**

    ```bash
    pip install psycopg2-binary
    pip install sqlalchemy
    ```

## Usage

Open `DS_Project_2.ipynb` via Jupyter Notebook and run the cells to perform the analysis.



## Usage

1. Open `DS_Project_2.ipynb` via Jupyter Notebook.
2. Run all the cells to see the analysis.
