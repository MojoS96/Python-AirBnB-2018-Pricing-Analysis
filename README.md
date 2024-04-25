# Python-AirBnB-2018-Pricing-Analysis

![](https://github.com/MojoS96/Python_InstaCart_Analysis/assets/159794763/ec3f3ec0-3537-446a-8227-8c6ced6ac319)

### Overview:
This project revolved around finding relationships in AirBnB listing data that contribute towards determining pricing. I approached this analysis from the perspective of a Airbnb consultancy firm that would offer listing advise to a potential client. The final deliverable would not necessarily be for the client themselves, but for an internal agent to use as a initial pricing reference when approaching a potential new user that may want to start renting out their property with assistance from an agency.

Using Python, I was able to perform the necessary data consistency checks and wrangling steps to prep the Data for Analysis. New variables were generated after defining listing groupings and visualizations where generated in order to answer some of the key questions that I had initially set myself following the original EDA (exploratory data anlysis)

<details>
<summary> Key Questions: </summary>

- When does the rental market in Amsterdam peak each year? (In regards to availability, not revenue)
- Which months are the least expensive, or most heavily discounted?
- How does neighbourhood impact price? Is distance the main variable to take into consideration or are their other stronger determining factors?

</details>

### Project Folders Outline:

1. Project Management: Project Brief 
2. Data: (Not uploaded due to file size constraints)
     - Raw Data: Original dataframes prior to manipulation
     - Neighbourhoods GeoJSON - used for spatial analysis in Tableau & Python
     - Prepared Data: Data Frames that have been cleaned up and prepared for Analysis
3. Scripts: Jupyter Notebooks containing the all the code used from data consistency checks and wrangling to defining new variables and performing merges.
4. Visualizations: .png files for each of the generated Visualizations
5. Final Deiverables:
   -  Tableau Report: AirBnB 2018 - Competitor Pricing Analysis [https://public.tableau.com/app/profile/joseph.sharp3530/viz/AirBnB2018-CompetitorPricingAnalysis/Story]

### Toolset

The provided data was analyzed using Python via Jupyter Notebooks. The following libraries were imported to perform the analysis:
- Pandas
- NumPy
- Seaborn
- Matplotlib
- SciPy
- GeoPy
- statsmodels
- folium
- Sklearn
- PyLab

### DataSets

AirBnB data used for this analysis was obtain via Kaggle. The author, Erik Bruan, performed a web scrape on public AirBnB pages in December 2018 - It is accessible via the following [LINK] (https://www.kaggle.com/datasets/erikbruin/airbnb-amsterdam)

Data Dictionary: [HERE](https://gist.github.com/jeremystan/c3b39d947d9b88b3ccff3147dbcf6c6b)

The download package consists of the following data files (Not all of which were leveraged as part of the analysis):
- Calender.csv
- listings.csv
- listings_details.csv
- neighbourhoods.csv
- neighbourhoods.geojson
- reviews.csv
- review_details.csv

