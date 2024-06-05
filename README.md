# Data Science Salary Analysis 2023 - Using Python

## Introduction
This repository contains an in-depth analysis of data science salaries for the year 2023. The analysis was conducted using Python and various libraries such as Seaborn, Plotly, and Pandas. The project is organized into different sections to provide a clear understanding of the process and results.

## Project Section
- *Introduction*: Provides a brief description of the project and a table describing the variables in the dataset.
- *Loading, Cleaning*, and Initial Exploration of the Dataset: Details the steps taken to load, clean, and perform initial exploration of the dataset.
- *Answering Key Questions*: Contains the analysis and visualizations that address specific questions related to data science salaries.

### Variables desciption
<table>
  <tr>
    <th>Column name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>work_year</td>.
    <td>The year in which the salary was paid</td>.
  </tr>
  <tr>
    <td>experience_level</td>
    <td>The level of experience on the job during the year.</td> </td>
  </tr>
  <tr>
    <td>employment_type</td>.
    <td>The type of employment for the role.
  </tr>
  <tr>
    <td>job_title</td>
    <td>The role performed during the year.
  </tr>
  <tr>
    <td>salary</td>
    <td>The total gross salary paid.</td> 
  </tr>
  <tr>
    <td>salary_currency</td>.
    <td>The currency of the salary paid as currency code ISO 4217.</td>
  </tr>
  <tr>
    <td>salaryinusd</td>
    <td>The salary in U.S. dollars (USD).</td>
  </tr>
  <tr>
    <td>employee_residence</td>.
    <td>The employee's primary country of residence during the work year as ISO country code 3166.</td>
  </tr>
  <tr>
    <td>remote_ratio</td>.
    <td>The total amount of work performed remotely.</td>
  </tr>
  <tr>
    <td>company_location</td>.
    <td>The country of the employer's head office or contracting branch office.</td>
  </tr>
  <tr>
    <td>company_size</td>
    <td>The median number of people that worked for the company during the year.</td>
  </tr>
</table>

### Dataset Loading, Cleaning, and Initial Exploration
In this section, we:
- Load the dataset into a Pandas DataFrame.
- Clean the dataset by handling missing values and correcting data types.
- Perform an initial exploration to understand the data distribution and key statistics.
- Create graphs to understand the categorical and numerical columns better.

### Answering Key Questions
Here, we address several key questions about data science salaries using visualizations and calculations:
- What is the average salary by experience level?
- How has the average salary changed over time (work_year)?
- What is the ratio of remote work between different job roles?
- Is there a relationship between company size and salary?
- Which country has the most remote workers?
- How has the proportion of remote work changed over time?
- Which country has the highest average salaries in USD?
- How are the job roles distributed across the different experience categories?
- How does the average salary vary between different types of employment, fulltime, partime, etc?
- Create a top10 with the most demanded jobs
- Create a top 10 of the most sought-after jobs

For example, this is the answer to: Is there a relationship between company size and salary?
<iframe width="800" height="600" src="https://tudominio.com/ruta/a/tu/visualizacion.html"></iframe>


## Libraries Used
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import plotly as px
import plotly.express as px
