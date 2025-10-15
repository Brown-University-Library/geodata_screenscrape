# Python Screen Scraping Tutorial

This repo includes a Python 3 Jupyter Notebook that demonstrates how to download datasets by screen scraping a website. Click the green Code button and choose Download ZIP to download the notebook, or clone the repo if you're familiar with GitHub.
If you just want to preview the content, click on the ipynb notebook file to view it.

## Prerequisites

1. Install Python 3 (either directly from [python.org](https://www.python.org/) or via a distribution like [Anaconda](https://www.anaconda.com/products/distribution))

2. If they are not already prepacked with your distribution, use pip install or your distribution's package handler to install the 
   following modules: [Requests](https://docs.python-requests.org/en/latest/index.html) and [Beautiful Soup](https://beautiful-soup-4.readthedocs.io/en/latest/)

ALTERNATIVE: Brown University users can follow the instructions at the beginning of the notebook to copy and open the Notebook in Google CoLab

## Demonstrated Concepts

The notebook is designed to download all data and documentation associated with the [IRS SOI Exempt Organizations Business Master File Extract](https://www.irs.gov/charities-non-profits/exempt-organizations-business-master-file-extract-eo-bmf), a list of all US non-profit organizations that is updated monthly.

1. Setting variables

2. Using Beautiful Soup to parse HTML and identify links

3. Saving file names and links in a dictionary

4. Using Requests to download and save data files

5. Using the os module to create directories and navigate file paths

6. Savings web pages and metadata as files

## Screen Scraping Etiquette

1. Use screen scraping for saving open data and public information (pay attention to copyright)

2. Follow the terms of services for the website or app (pay attention to licensing)

3. Don't put undo pressure on the web server: for large downloads separate them into batches, incorporate pauses, and run scripts at off peak times

4. Don't repeat downloads unnecessarily: test code on small, sample requests, separate data downloading from data processing (once data is saved, work off the saved copies)
