# Medical insurance fraud web scraping
This repository stores the Python scripts to scrape the United States medical insurance fraud claim cases reported on Office of Inspector General (OIG) pages. There are two separate Jupyter notebooks.
- For archived posts from 2009-2019: Executed under `OIG at HHS Data scraping 2009-2019 - Criminal and Civil Enforcement.ipynb`
- For the regular updates (appending lastest posts): Executed under `OIG at HHS Data scraping - Criminal and Civil Enforcement - Regular maintainence.ipynb`
  - Currently run at the end of every quarter manually
  - Future goal is to run automatically if possible.
 
 
## Steps in running the notebooks 
 1. `OIG at HHS Data scraping 2009-2019 - Criminal and Civil Enforcement.ipynb` (Run once only)
 2. `OIG at HHS Data scraping - Criminal and Civil Enforcement - Regular maintainence.ipynb`
 3. `Data cleaning stage 1 - Data sorting and re-classification.ipynb`
 4. `Data cleaning stage 2 - Geography and money parsing.ipynb`
