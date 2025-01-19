# covid-uk-dashboard
This project is a data analysis and visualization tool for tracking COVID-19 cases and reinfections in England. It leverages the UK COVID-19 API to fetch real-time data and provides insights through interactive visualizations.

### Project Overview 
The COVID-19 UK Dashboard focuses on analyzing key metrics, including new cases and reinfections. Using Python and Jupyter Notebook, the project provides a detailed analysis of the pandemic's trends and patterns in England.

**Core Functionality**

***Data Access***: Retrieves COVID-19 data directly from the UK COVID-19 API for England.

***Key Metrics***:
- Rolling rates of new cases.
- Rolling rates of reinfections.

***Visualization***: Provides charts and graphs to make the data more accessible.

---
### Installation and Usage 
***Prerequisites***
- Python 3.8+
- Jupyter Notebook or JupyterLab
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `uk_covid19`

***Steps***
1. Clone the repository:
   ```bash
   git clone https://github.com/adinanabi/covid-uk-dashboard.git
   cd covid-uk-dashboard
2. Open the notebook [UK COVID analysis](./uk_covid_analysis.ipynb) in Jupyter Notebook or JupyterLab.
3. The notebook fetches data from the UK COVID-19 API. If the API is unavailable, it will use the included [covid data](./timeseries.json) file as a fallback.

---
### Data Analysis
The notebook processes the fetched data to:
- Clean and transform it into a structured format (e.g., Pandas DataFrame).
- Generate visualizations for rolling rates of cases and reinfections.
- Highlight trends over time.

---
### Insights and Findings
#### Key Visualizations and Analysis
1. <img src="./screenshots/cases_vs_tests.png" alt="**Time Series Analysis of COVID-19 Cases and Tests**" width="500" height="auto">
2. **COVID-19 Case Statistics**
3. <img src="./screenshots/percentage_change.png" alt="**Daily Percentage Change in Cases**" width="500" height="auto">
4.  <img src="./screenshots/events.png" alt="**Significant Events Impact on COVID-19 Cases**" width="500" height="auto">



#### Pandemic Trajectory Analysis
- **Initial Surge**: High case rates during early pandemic and winter periods
- **Vaccination Impact**: Gradual decline in cases post-vaccination program
- **Variant Challenges**: Noticeable changes during variant emergence periods

#### Limitations and Considerations
- Data represents rolling rates and may not capture absolute case numbers
- Influenced by testing availability and reporting mechanisms
- Reflects specific context of England's pandemic response

---
### License
This project is for educational purposes and is licensed under the [GNU GPLv3.0 or later.](./LICENSE).




