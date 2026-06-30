# Project-3-data-wrangling-project

Project-3-data-wrangling-project
&nbsp;
Project 3 — Data Wrangling & Retrieval
&nbsp;
&nbsp;

🧭 Introduction
&nbsp;
This project is part of the Data Wrangling and Retrieval module, where the goal is to collect, clean, structure, and analyze data from multiple sources.
&nbsp;
The project demonstrates the ability to:
&nbsp;

Use Python effectively (data types, structures, functions, flow control, error handling)
&nbsp;

Perform data wrangling, cleaning, and manipulation
&nbsp;

Collect data using APIs and Web Scraping  
&nbsp;

Combine datasets from different sources
&nbsp;

Conduct basic Exploratory Data Analysis (EDA)  
&nbsp;

Present insights clearly and visually
&nbsp;

&nbsp;
The topic chosen for this project is:
👉 PLACEHOLDER: Insert your topic here  
&nbsp;
&nbsp;

📁 Data Sources
&nbsp;
This project uses two independent data sources, as required:
&nbsp;

1. API Source
&nbsp;

Name: PLACEHOLDER

Endpoint(s) used: PLACEHOLDER

Description: PLACEHOLDER

Terms of Use: Confirmed and respected

Data collected: PLACEHOLDER
&nbsp;

2. Web Scraping Source
&nbsp;

Website: PLACEHOLDER

Scraping method: requests + BeautifulSoup

Structure inspected: HTML tags, classes, pagination

Robots.txt: Checked and respected

Data collected: PLACEHOLDER
&nbsp;

3. Optional Dataset
&nbsp;

Source: PLACEHOLDER

Description: PLACEHOLDER
&nbsp;
&nbsp;
&nbsp;

❓ Research Questions
&nbsp;
The project was guided by the following hypotheses and questions:
&nbsp;

PLACEHOLDER — Hypothesis 1  
&nbsp;

PLACEHOLDER — Hypothesis 2  
&nbsp;

PLACEHOLDER — Research Question 1  
&nbsp;

PLACEHOLDER — Research Question 2  
&nbsp;
&nbsp;
&nbsp;

🛠️ Methodology
&nbsp;

1. Data Collection
&nbsp;

API documentation reviewed (endpoints, rate limits, parameters)
&nbsp;

Functions created to fetch data and handle errors
&nbsp;

Web scraping script developed respecting website rules
&nbsp;

Data saved locally in /data/raw/  
&nbsp;

2. Data Wrangling & Cleaning
&nbsp;
At least five cleaning techniques were applied:
&nbsp;

Handling missing values (dropna, fillna)
&nbsp;

Removing duplicates
&nbsp;

Standardizing text (lowercase, trimming, replacing symbols)
&nbsp;

Converting data types (dates, numerics, categories)
&nbsp;

Creating new columns (flags, extracted fields)
&nbsp;

Formatting inconsistent values
&nbsp;

Grouping and restructuring data
&nbsp;

Merging datasets from different sources
&nbsp;

A main cleaning function was created to organize the workflow.
&nbsp;

3. Data Structuring
&nbsp;

Combining API + scraped data
&nbsp;

Creating pivot tables
&nbsp;

Aggregating values
&nbsp;

Filtering relevant subsets
&nbsp;

Preparing final cleaned dataset in /data/cleaned/  
&nbsp;

4. Exploratory Data Analysis (EDA)
&nbsp;
EDA included:
&nbsp;
&nbsp;
&nbsp;

Summary statistics
&nbsp;
&nbsp;
&nbsp;

Distribution plots
&nbsp;
&nbsp;
&nbsp;

Correlation checks
&nbsp;

Grouped comparisons
&nbsp;

Trend identification
&nbsp;

Visualizations using Matplotlib/Seaborn
&nbsp;
&nbsp;
&nbsp;

📊 Main Findings & Insights
&nbsp;
PLACEHOLDER — Replace with your actual insights, for example:
&nbsp;

The API data revealed that…
&nbsp;

The scraped data showed a pattern in…
&nbsp;

The combined dataset confirmed/refuted the hypothesis that…
&nbsp;

Unexpected insight: …
&nbsp;
&nbsp;

🔮 Further Questions & Next Steps
&nbsp;
&nbsp;

Additional data sources could improve…
&nbsp;

A deeper analysis could explore…
&nbsp;

Future work could include ML models, clustering, or time‑series forecasting
&nbsp;

More advanced visualizations could help communicate insights
&nbsp;
&nbsp;
&nbsp;

📌 Project Structure
&nbsp;

Code
data-wrangling-project/
│
├── data/
│   ├── raw/            # API + scraped data
│   └── cleaned/        # Final cleaned dataset
│
├── notebooks/
│   └── main.ipynb      # Main notebook with full workflow
│
├── src/
│   ├── api.py          # API functions
│   ├── scraping.py     # Web scraping functions
│   ├── cleaning.py     # Cleaning functions
│   └── utils.py        # Helper functions
│
└── README.md
&nbsp;
&nbsp;
&nbsp;

🧼 Coding Best Practices Followed
&nbsp;

Modularized code with reusable functions
&nbsp;

Clear naming conventions
&nbsp;

Removed unused imports and variables
&nbsp;

Added meaningful comments and documentation
&nbsp;

Logical organization of notebook sections
&nbsp;

Regular refactoring
&nbsp;

Respectful and legal data collection
&nbsp;


👩‍💻 Author
&nbsp;
Teresa Mendes Coelho  
&nbsp;
Shilpa Krish 
&nbsp;
Vildan Pirpiroglu




































































































Project 3 data-wrangling-and-Retrival



🧭 Introduction:

This project is part of the Data Wrangling and Retrieval module, where the goal is to collect, clean, structure, and analyze data from multiple sources.
The project demonstrates the ability to:

Use Python effectively (data types, structures, functions, flow control, error handling)

Perform data wrangling, cleaning, and manipulation

Collect data using APIs and Web Scraping

Combine datasets from different sources

Conduct basic Exploratory Data Analysis (EDA)

Present insights clearly and visually
The topic chosen for this project is:
👉 PLACEHOLDER: Insert your topic here (.........................................)

..............to complete/ improve..........






The project follows a structured workflow across five days, from data collection to presentation.
Our project includes:
Data from at least two different sources (APIs, web scraping, or datasets).
A README file with:
Title of the project
Introduction
Description of the data and data sources
Research questions and conclusions
Explanation of your methodology (cleaning, analysis, visualization)
Main findings and insights
Further questions and next steps
Links to data sources and your Kanban board (e.g., Trello)
..............to complete/ improve..........

The project follows a structured workflow across five days, from data collection to presentation.


📁 Data Sources
This project uses two independent data sources, as required:

1. API Source
Name: PLACEHOLDER

Endpoint(s) used: PLACEHOLDER

Description: Brief explanation of what the API provides

Terms of Use: Confirmed and respected

Data collected: PLACEHOLDER

2. Web Scraping Source
Website: PLACEHOLDER

Scraping method: requests + BeautifulSoup

Structure inspected: HTML tags, classes, pagination, etc.

Robots.txt: Checked and respected

Data collected: PLACEHOLDER

3. (Optional) Additional Dataset
If you used a CSV/Excel dataset:

Source: PLACEHOLDER

Description: PLACEHOLDER




❓ Research Questions
The project was guided by the following hypotheses and questions:

PLACEHOLDER — Hypothesis 1

PLACEHOLDER — Hypothesis 2

PLACEHOLDER — Research Question 1

PLACEHOLDER — Research Question 2

These questions shaped the cleaning, structuring, and analysis process.





2. Data Wrangling & Cleaning
At least five cleaning techniques were applied:

Handling missing values (dropna, fillna)

Removing duplicates

Standardizing text (lowercase, trimming, replacing symbols)

Converting data types (dates, numerics, categories)

Creating new columns (flags, extracted fields)

Formatting inconsistent values

Grouping and restructuring data

Merging datasets from different sources

A main cleaning function was created to organize the workflow, calling smaller cleaning functions in sequence.




3. Data Structuring
Combining API + scraped data

Creating pivot tables

Aggregating values

Filtering relevant subsets

Preparing final cleaned dataset in /data/cleaned/




4. Exploratory Data Analysis (EDA)
EDA included:

Summary statistics

Distribution plots

Correlation checks

Grouped comparisons

Trend identification

Visualizations using Matplotlib/Seaborn




📊 Main Findings & Insights
PLACEHOLDER — Replace with your actual insights, for example:

The API data revealed that…

The scraped data showed a pattern in…

The combined dataset confirmed/refuted the hypothesis that…

Unexpected insight: …

Summarize the most important conclusions clearly and concisely.



🔮 Further Questions & Next Steps
Additional data sources could improve…

A deeper analysis could explore…

Future work could include machine learning models, clustering, or time‑series forecasting

More advanced visualizations could help communicate insights





📌 Project Structure
Code
data-wrangling-project/
│
├── data/
│   ├── raw/            # API + scraped data
│   └── cleaned/        # Final cleaned dataset
│
├── notebooks/
│   └── main.ipynb      # Main notebook with full workflow
│
├── src/
│   ├── api.py          # API functions
│   ├── scraping.py     # Web scraping functions
│   ├── cleaning.py     # Cleaning functions
│   └── utils.py        # Helper functions
│
└── README.md
🧼 Coding Best Practices Followed
Modularized code with reusable functions

Clear naming conventions

Removed unused imports and variables

Added meaningful comments and documentation

Logical organization of notebook sections

Regular refactoring

Respectful and legal data collection

🎤 Presentation
Slides URL: PLACEHOLDER  
The presentation includes:

Topic overview

Data sources

Cleaning challenges

EDA insights

Conclusions

Next steps

Prepared according to the recommended 7–10 minute format.







📝 Authors
Teresa Mendes Coelho
Shilpa Krish 
Vildan Pirpiroglu

