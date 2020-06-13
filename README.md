### Table of Contents

  1. [Installation](#installation)
  2. [Project Motivation](#motivation)
  3. [File Description](#files)
  4. [Results](#results)
  5. [Licensing and Acknowledgements](#licensing)
  
## Installation <a name = "installation"></a>

You will need the standard data science libraries found in the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

## Project Motivation <a name = "motivation"></a>
In this project, I aim to answer five business questions regarding house/apartment listsing on Airbnb in Seattle, WA, US: 
1. How has Airbnb listing price on average changed in year 2016? 
2. How do Airbnb prices respond to national holidays? How much do they differ from normal daily average? 
3. How do the prices differ across region (neighborhood and zipcode) and overtime? Which regions are the most expensive?
4. How long are the houses listed on Airbnb a year and how is that different across region and over time? This question allows us to tell whether there are any landlords that list their houses on Airbnb fulltime.
5. What types of homes are listed on Airbnb? Hotel, motel, single family homes, apartments or other types? 

## File Description <a name = "files"></a>

* `AirBnB_Project_1_Analysis.ipynb` is a notebook of the analysis performed following the CRISP-DM process.

* Data are from the original [Kaggle link](https://www.kaggle.com/airbnb/seattle). `listings` and `calendar` datasets were used for this analysis. 
  * The `listings` dataset contains home_id, address, home characteristics, date, availability, nightly price, and guest reviews.
  * The `calendar` data includes four fields: listing_id, date, available, price. 
The two datasets were merged together to conduct spatial analysis. 

## Results <a name = "results"></a>

The main findings of the analysis can be found at the [blog post available here](). 

## Licensing and Acknowledgements <a name = "licensing"></a>
  
Thanks to Airbnb and Kaggle for the data. The licensing for the data and other descriptive information can be found [here](https://www.kaggle.com/airbnb/seattle).
