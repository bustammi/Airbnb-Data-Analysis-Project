# Exploring Listings: Toronto vs. Vancouver (2022) - A Data Analyis Project using CRISP-DM Framework

This project aims to analyze and compare Airbnb (2022) listings in Toronto and Vancouver using the CRISP-DM framework. The project's primary aim is to provide valuable insights into the similarities and differences between Airbnb listings in both cities, identify key factors that impact the rental price, and create a time-series forecast for future Airbnb listings.

---
## Table of Contents

- [Exploring Listings: Toronto vs. Vancouver (2022) - A Data Analyis Project using CRISP-DM Framework](#exploring-listings-toronto-vs-vancouver-2022---a-data-analyis-project-using-crisp-dm-framework)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Data Sources](#data-sources)
  - [Business Understanding](#business-understanding)
    - [Business Questions:](#business-questions)
- [](#)
  - [Data Understanding](#data-understanding)
  - [Data Preparation](#data-preparation)
  - [Data Modeling and Evaluation](#data-modeling-and-evaluation)
  - [Conclusion](#conclusion)
  - [Technologies/Libraries Used](#technologieslibraries-used)
  - [How To Clone or Run the Repository](#how-to-clone-or-run-the-repository)
  - [Acknowlegements](#acknowlegements)

---

## Introduction
Airbnb has become a popular alternative to traditional hotels and accommodation, and it has grown rapidly over the years. Toronto and Vancouver are two of Canada's most popular tourist destinations, and they have a vast selection of Airbnb listings available for rent. Therefore, analyzing and comparing the Airbnb listings in both cities will provide valuable insights into the vacation rental market and its trends.

---

## Data Sources
The data used in this project was obtained from the [Inside Airbnb Website](http://insideairbnb.com/get-the-data/). We used the following datasets:
  - `listings.csv.gz` - (December 2022) This file contains detailed information about Airbnb listings in Vancouver and Toronto, such as the listing id, neighbourhood, room type, price, and availability, etc.

---

## Business Understanding
### Business Questions:

The project aims to provide insights into the Airbnb rental market in Toronto and Vancouver. The following business questions will be answered using data analysis and modeling:
#


**1. Are Airbnb listings in Toronto more expensive than Vancover?** 
- **H<sub>0</sub>:** There is no significant difference in listing prices between Toronto and Vancouver.
- **H<sub>A</sub>:** Listings in Toronto are more expensive than those in Vancouver. <br></br>

**2. Are there more Airbnb listings available in Vancouver than Toronto?**
- **H<sub>0</sub>:** There are no significant difference in the number of listings between Vancouver and Toronto
- **H<sub>A</sub>:** Vancouver has more listings avaialble than Toronto <br></br>
  
**3. Does the number of bedrooms significantly affect the listing price in both cities?**
- **H<sub>0</sub>:** The number of bedrooms does not signficantly affect the listing price in both cities.
- **H<sub>A</sub>:** The number of bedrooms significantly affects the listing price in both cities. <br></br>


**4: Are there any differences in the types of properties listed in Toronto vs. Vancouver?**
- **H<sub>0</sub>:** The distribution of property types is the same between Toronto and Vancouver
- **H<sub>1</sub>:** There a re signfiicant differences in teh distribution of peroperty types between Toronto and Vancouver. <br></br>

**5. Does being a superhost signficantly affect the bumber of reviews a listing receives in both cities?**
- **H<sub>0</sub>:** Being a superhost does not significantly affect the number of reviews a listing receives in both cities 
- **H<sub>1</sub>:** Being a superhost signfiicantly affects the number of reviews a listing receives in both cities. <br></br>

**6. Does the average review score differ signficiantly between Toronto and Vancouver?**
- **H<sub>0</sub>:** The distribution of property types is the same between Toronto and Vancouver
- **H<sub>1</sub>:** There a re signfiicant differences in teh distribution of peroperty types between Toronto and Vancouver. <br></br>
  
**7. Is there a relationship between the number of reviews a listing has and its occupancy rate in both cities?**
- **H<sub>0</sub>:** There is no significant relationship between the number of reviews a listing has and its occupancy rates in both cities.
- **H<sub>1</sub>:** The number of reviews a listing has is significantly related to its occupancy rate in both cities.<br></br>

**8. Do instant bookable listings receive more bookings than those are not instant bookable and non-instant bookable listings in both cities**
- **H<sub>0</sub>:** There is no significant difference in the booking rate between instant bookable and non-instant bookable listings in both cities
- **H<sub>1</sub>:** Instant bookable listings receive more bookings than non-instant bookable listings in both cities <br></br>

**9. Does the proximity of a listing to popular tourist attractions affect its occupancy rates in both cities?**
- **H<sub>0</sub>:** There is no significant relationship between the proximity of listing to popular tourist attractions and its occupancy rate in both cities.
- **H<sub>1</sub>:** The proximity of listing to popular tourist attractions is significantly related to its occupancy rate in both cities <br></br>

**10. Does the availability of certain amenities, such as Wi-Fi or parking, significantly affect the listing price in both cities?**
- **H<sub>0</sub>:** The availability of certain amenities does not significantly affect the listing prices in both cities
- **H<sub>1</sub>:** The availability of certain amentities significantly affects the listing price in both cities. 

---

## Data Understanding
`WIP`

## Data Preparation
`WIP`

## Data Modeling and Evaluation
`WIP`

## Conclusion
`WIP`

---
## Technologies/Libraries Used

- Python 3
- Jupyter Notebook
- Pandas
- Nupmy
- Matplotlib
- Seaborn
- Sci-kit learn


## How To Clone or Run the Repository
1. Clone the repository from GitHub: `git clone https://github.com/bustammi/Airbnb-Data-Analysis-Project.git`
2. Navigate to the project directory: `cd airbnb-analysis`
3. Install the necessary libraries: `pip install -r requirements.txt`
4. Open the Jupyter Notebook: `jupyter notebook`
5. Run the cells in the notebook to reproduce the analysis.

## Acknowlegements
I would like to acknowledge the following sources that were used in the preparation and compeltion of this Airbnb Data Analysis project:

1. [Inside Airbnb](http://insideairbnb.com/get-the-data/) - providing the raw data used in this project
