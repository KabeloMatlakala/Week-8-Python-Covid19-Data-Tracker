# 🌍 COVID-19 Global Data Tracker

This project is a data analysis notebook that explores global COVID-19 trends over time, including cases, deaths, and vaccinations. Using real-world data from [Our World in Data](https://github.com/owid/covid-19-data), it demonstrates how to clean, analyze, and visualize key metrics across multiple countries.

---

## Project Goals

- Import and clean global COVID-19 data
- Analyze trends in cases, deaths, and vaccinations
- Compare metrics across selected countries
- Visualize data with informative charts
- Communicate insights in a clear, reproducible notebook

---

## 🛠️ Tools Used

- Python 3.x
- pandas
- matplotlib
- seaborn
- Jupyter Notebook (via VS Code)

---

## 📁 File Structure
Covid-Data-Tracker/ 

├── covid_analysis.ipynb
     
    Jupyter notebook with code, plots, and insights  

├── owid-covid-data.csv 
 
    Dataset from Our World in Data 

├── .gitignore 
    
    Files to exclude from version control 

└── README.md  
    
    Project overview (this file)
    
---

## 📊 Sample Analyses

-  Total and daily new cases over time
-  Total deaths and death rate by country
-  Vaccination rollout and % of population vaccinated

Countries analyzed: **United States**, **India**, **Kenya**

---

## How to Run

1. Clone the repo:
   ```bash
    git clone https://github.com/KabeloMatlakala/Week-8-Python-Covid19-Data-Tracker.git
    cd Week-8-Python-Covid19-Data-Tracker
   ```
2. (Optional but recommended) Create and activate a virtual environment:
    ```bash
        python -m venv .venv

        source .venv/bin/activate  
        
        # On Windows: 
        .venv\Scripts\activate
    ```

3. Install dependencies:
    ```bash
        pip install pandas matplotlib seaborn jupyter
    ```

4. Open the notebook in VS Code or with:
    ```bash
        jupyter notebook
    ```

## Data Source

Data used: [Our World in Data – COVID-19 Data](https://ourworldindata.org/coronavirus)  
- Included file: `owid-covid-data.csv.zip` (compressed for size)
- Original uncompressed dataset: [owid-covid-data.csv](https://covid.ourworldindata.org/data/owid-covid-data.csv)

### How to Use the Zip File

After cloning this repo:

1. **Manually extract** `owid-covid-data.csv.zip` using your system’s unzip tool (right-click → Extract).
2. Place the extracted file `owid-covid-data.csv` in the project root (same folder as the notebook).
3. Then run the notebook.

Alternatively, you can extract it with Python:

```python
import zipfile

with zipfile.ZipFile("owid-covid-data.csv.zip", "r") as zip_ref:
    zip_ref.extractall()
```


