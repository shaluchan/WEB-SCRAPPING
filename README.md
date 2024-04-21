# Job Data Scraping

## Overview
This repository contains Python code for scraping job data from various links. The scraping process is divided into two notebooks:

1. **Fetching job links**: In this notebook, job links are scraped from a given set of links. These links serve as the source for the subsequent scraping of job data.

2. **jobs scrapping**: This notebook focuses on scraping job data from the links obtained in the first step. It extracts relevant information such as job titles, descriptions, and requirements.

## Usage
To use the code in this repository, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/shaluchan/WEB-SCRAPPING.git
2.Install the required dependencies:

  
Requirements

    Python 3.x
    Jupyter Notebook
    BeautifulSoup
    requests
3.Run the notebooks in the following order:

    1_fetching_job_links.ipynb
    2_jobs_scrapping.ipynb


After running 2_jobs_scrapping.ipynb, you can access the fetched data either by viewing the output in the notebook or by locating the saved data files in the repository directory.

Follow the instructions provided in each notebook to execute the scraping process.

