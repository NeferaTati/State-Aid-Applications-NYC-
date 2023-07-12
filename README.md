# mini_cap

A template for a mini-capstone project. To get started, [fork this repository](https://docs.github.com/en/get-started/quickstart/fork-a-repo) to your GitHub profile.

This repository will entail a light analysis of some open-source datasets provided by [the city of new york](https://data.cityofnewyork.us/). The data folder contains timely CSV files on **education**, **employment**, **housing**, and **transportation**. 

You will propose an analysis question on these datasets and then complete a subsequent ETL, EDA, and CDA to address this question. Your analyses could focus on one data domain specifically, or address an intersection of data domains.

As this is an individual project, you will not work in sprints, but instead, tackle assigned issues that will be generated for you once you fork this project with regular check-ins from staff.

## data

### raw/education

* Midday Trips: https://data.cityofnewyork.us/Education/Midday-Trips/5ghg-dyn6
* Capacity Projects: https://data.cityofnewyork.us/Education/Capacity-Projects-by-School/a94k-kjys
* Project Public School Ratio: https://data.cityofnewyork.us/Education/Projected-Public-School-Ratio/n7ta-pz8k
* Graduation Rates: https://data.cityofnewyork.us/Education/2005-2019-Graduation-Rates-All/3vje-du8p
* MATH Exam: https://data.cityofnewyork.us/Education/2013-2019-New-York-State-MATH-Exam/365g-7jtb
* ELA Exam: https://data.cityofnewyork.us/Education/2013-2019-New-York-State-ELA-Exam/hvdr-xc2s

### raw/finance

* Application for State Aid: https://data.cityofnewyork.us/Education/Application-for-State-Aid/8gpu-s594
* Citywide Payroll Data (not downloaded due to size): https://data.cityofnewyork.us/City-Government/Citywide-Payroll-Data-Fiscal-Year-/k397-673e
* Electric Consumption & Cost (not downloaded due to size): https://data.cityofnewyork.us/Housing-Development/Electric-Consumption-And-Cost-2010-Feb-2023-/jr24-e7cr

### raw/health

* Student Vaccination Rates: https://data.cityofnewyork.us/Education/Student-COVID-Vaccinations-04-16-05-03-2022/cr7v-v529
* Leading Causes of Death: https://data.cityofnewyork.us/Health/New-York-City-Leading-Causes-of-Death/jb7j-dtam
* COVID-19 Daily Counts: https://data.cityofnewyork.us/Health/COVID-19-Daily-Counts-of-Cases-Hospitalizations-an/rc75-m7u3
* Popular Baby Names: https://data.cityofnewyork.us/Health/Popular-Baby-Names/25th-nujf
* SARS-CoV-2 Concentrations in NYC Wastewater: https://data.cityofnewyork.us/Health/SARS-CoV-2-concentrations-measured-in-NYC-Wastewat/f7dc-2q9f
* NYC Dog Licensing Dataset: https://data.cityofnewyork.us/Health/NYC-Dog-Licensing-Dataset/nu7n-tubp
* Dog Bite Data: https://data.cityofnewyork.us/Health/DOHMH-Dog-Bite-Data/rsgh-akpg
* Pregnancy-Associated Mortality: https://data.cityofnewyork.us/Health/Pregnancy-Associated-Mortality/27x4-cbi6

### raw/transportation

* Bicycle Counts (not downloaded due to size): https://data.cityofnewyork.us/Transportation/Bicycle-Counts/uczf-rk3c
* EZ Pass Reader (not downloaded due to size): https://data.cityofnewyork.us/Transportation/EZ-Pass-Readers-Tabular-/erdf-2akx
* Parking Lot Meters Location & Status: https://data.cityofnewyork.us/Transportation/Parking-Meters-Locations-and-Status/693u-uax6
* Bus Breakdown & Delays (not downloaded due to size): https://data.cityofnewyork.us/Transportation/Bus-Breakdown-and-Delays/ez4e-fazm

## code - etl

Our first step will entail completing a traditional Python `ETL` pipeline. View the `code/etl.ipynb` file to view the structure.

## code - eda

Our next step will entail completing `EDA`. View the `code/eda.ipynb` file to view the structure.

## code - cda

Our final step will entail completing `CDA`. View the `code/cda.ipynb` file to view the structure.

## presentation

After completing our `cda.ipynb`, you will create a presentation that describes:

* analysis question
* methodology
* eda findings
* final findings
* next actions

In a "powerpoint" format.

## README

This README is a temporary file to describe our next actions. After completing this project, you will replace your `README.md` file with the following template:

```
# Project Title

[summary]

## Methodology

[how did you develop/analyze your data?]

## Visualizations

[visualizations from EDA posted along with descriptions]

## Findings

[what did you discover from your cda]

## Next Steps

[what next steps can you take?]

```