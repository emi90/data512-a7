# DATA 512
# A7- Project Report
Emily Yamauchi


## Introduction

### Objective

The spread of the COVID-19 pandemic since early 2020 brought changes such as stay-home orders, social distancing, and travel restrictions, 
all which has impacted daily life including transportation behaviors. 
Public transportation is an indispensable mode of transportation especially in urban areas, and has been particularly 
impacted by the pandemic (Bliss et al., 2020), and the steep drop in ridership continues to have a significant impact on transit agencies. 
As cases soared local authorities enforced mobility restrictions, but what sort of relationships are there between 
daily COVID-19 cases and transportation behavior in Montgomery County?

### Data Source

Data is collected from two separate sources:   
- Daily confirmed cases comes from the `RAW_us_confirmed_cases.csv` file from the Kaggle repository of [John Hopkins University COVID-19 data](https://www.kaggle.com/antgoldbloom/covid19-data-from-john-hopkins-university?select=RAW_us_confirmed_cases.csv).
- Daily ridership data comes from WMATA's [COVID-19 Ridership Monitoring page](https://www.wmata.com/service/covid19/covid-19-public-information.cfm).   

Data used in the initial analysis but not included in the final report is collected from three additional sources:  
- The CDC dataset of [masking mandates by county](https://data.cdc.gov/Policy-Surveillance/U-S-State-and-Territorial-Public-Mask-Mandates-Fro/62d6-pm5i).
- The New York Times [mask compliance survey data](https://github.com/nytimes/covid-19-data/tree/master/mask-use).  
- [Montgomery County Crash Reporting- Incidents Data](https://data.montgomerycountymd.gov/Public-Safety/Crash-Reporting-Incidents-Data/bhju-22kf) provided by Montgomery County Department of Police.  

Where applicable, the data is filtered to just instances relating to Montgomery County. 

### Project Details  

- A4: Common Analysis  
	This report introduced the analysis of COVID-19 cases with masking mandates and masking compliance. The full analysis can be found [here](https://github.com/emi90/data-512-a4),
and the Notebook file is included in this repository.  
- A5: Extension Plan
	This report expanded on the previous A4 report, and introduced new datasets (public transportation ridership) and presented the plan for next steps.
The full analysis can be found in this [Google Doc](https://docs.google.com/document/d/1ncewJ_jhISrfV0zxzNAHPSnCO-JS-eQHTFnBO7XUkO8/edit), and the Notebook file
is included in this repository.  
- A6: Presentation
	A presentation of this entire project was given on Dec. 9, 2021. The presentation slides are included in this repository.  
- A7: Final Report  
	A summary report of this entire project is presented in this [Google Doc](https://docs.google.com/document/d/1E2qJsxM_37C3lO5YIHm1YiPvD4b7xUHO2w6kI1qZu0w/edit#) 


### Folder Structure

```
 data-512-a7
    ├── LICENSE
    ├── README.md
    ├── data_raw
    │   ├── 2021_ridership.csv
    │   ├── mont_county_crash.csv
    │   ├── RAW_us_confirmed_cases.csv
    │   └── RAW_us_confirmed_cases.csv.zip
    ├── data_clean
    │   ├── cases_clean.csv
    │   ├── crashes_data.csv
    │   ├── data1.csv
    │   ├── data2.csv
    │   └── transit_data.csv
    ├── presentation
    │   └── presentation.pptx
    ├── visualization
    │   ├── plot.png
    │   ├── plot_crash.png
    │   ├── plot_ridership.png
    │   └── wmata_ridership.png
    ├── A4-Common-Analysis.ipynb
    ├── A5-Exention-Plan.ipynb
    ├── a5-model.Rmd
    └── A7-Final-Report-EmilyYamauchi.pdf
```