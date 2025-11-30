# Stack Overflow Developer Trends Analysis – Capstone Project

This project analyzes data from the 2024 Stack Overflow Developer Survey, leveraging various data science techniques to derive insights into programming language trends, database usage, and developer employment status. The analysis includes visualizations using Python libraries such as Pandas, Matplotlib, and Seaborn, alongside a dashboard created in Cognos Analytics. The project highlights the growing importance of technologies like Python, SQL, and PostgreSQL, and offers predictions for future trends in the tech industry.

## 📑 Table of Contents
1. [Introduction](#-introduction)
2. [Dataset Background](#%EF%B8%8F-dataset-background)
3. [Tools](#-tools)
4. [Project Workflow](#%EF%B8%8F-project-workflow)
5. [About the Author](#-about-the-author)

## 📌 Introduction
This project presents a comprehensive analysis of developer trends based on the Stack Overflow 2024 Developer Survey. The goal is to explore key insights into the most popular and anticipated programming languages, databases, and technologies shaping the tech landscape. 

The report also includes job market analysis using external job-postings data and interactive dashboards to enrich understanding. 

The final output consists of a presentation (DataAnalystPresentation.pdf) summarizing all major insights using visualizations and narrative—every slide created in accordance with course instructions—along with the code used for the project (project code.ipynb) that details the process, tools used, and methodology.

## 🗃️ Dataset Background
This project is based on the 2024 Stack Overflow Developer Survey, a large-scale annual dataset crowdsourced from developers around the world. The survey reflects:

- Technologies developers currently use

- Tools and languages they want to adopt

- Job roles, learning paths, and preferences

- Demographic trends in the developer community

In addition to the main survey data, two supplemental datasets provided during the course were incorporated—one obtained via REST API and the other through web scraping—to support a broader analysis of job market trends and technology demand. Direct links to the datasets are included in the presentation.

## 🧰 Tools
All analysis and visualizations were developed using Python in Jupyter Notebooks. The following key packages were utilized:

`pandas` – data manipulation and cleaning

`matplotlib` – chart and plot creation

`seaborn` – enhanced visualizations

`collections.Counter` – frequency analysis for categorical data

`requests` – sending HTTP requests to access data from web APIs

`json` – parsing and handling JSON data format from APIs

`BeautifulSoup` – web scraping and extracting data from HTML content

Dashboard creation was completed using IBM Cognos Analytics, as part of the lab requirements.

## ⚙️ Project Workflow
The project began with data cleaning, including handling duplicates and missing values in key columns. DataFrames were constructed and manipulated using Pandas. 

After preparing the dataset, visualizations were created with Matplotlib and Seaborn to explore initial trends. 

A REST API was then used to retrieve additional data via requests and json, which was cleaned, sorted, and visualized. 

Finally, data was gathered through web scraping with BeautifulSoup, refined through custom cleaning and formatting steps, and further visualized to support the overall analysis.

## 👤 About the Author
I'm a physics graduate with a focus on data analysis and Python programming. 
I work with Python, data visualization, and building tools that simplify complex tasks.
___
<p align="left">
    <img src="https://skills.network/logos/SN_web_lightmode.png" alt="IBM Skills Network Logo" width="150" height="150"/>
</p>

<p align="left">
    <img src="https://cdn.worldvectorlogo.com/logos/ibm.svg" alt="IBM Logo" width="150" height="150"/>
</p>

<p align="left">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5f/Coursera_logo_%282020%29.svg/2560px-Coursera_logo_%282020%29.svg.png" alt="Coursera Logo" width="150" height="150"/>
</p>
