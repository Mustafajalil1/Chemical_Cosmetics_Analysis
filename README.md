## Project
this file contain the first project in python, using pandas library
## Analysis of chemical Hazards in Cosmetic Products Reported to the CSCP
---
## Project Overview
This project analyzes data from the California Safe Cosmetics Program (CSCP), which monitors cosmetic products sold in California that contain ingredients known or suspected to cause cancer, birth defects, or other reproductive harm. The primary objective is to uncover patterns in chemical usage, identify the most frequently reported hazardous substances, evaluate reporting trends over time, and compare discontinued products with those still on the market.

## Information about the dataset
### The dataset includes the following fields:
- ChemicalName: Name of the hazardous or potentially hazardous chemical ingredient.
- InitialDateReported: The date when the chemical was first reported in any product.
- DiscontinuedDate: Indicates if/when the chemical was discontinued from use in the product.
- ChemicalDateRemoved: The date the chemical was removed from the public CSCP listing.

## Summary and Key Findings 
- Identifies the number of products discontinued annually, highlighting reformulation trends or regulatory impact.
- Reveals which product subcategories are most represented in the dataset, indicating industry focus or consumer usage patterns.
- Lists the most frequently reported hazardous chemicals, showing which substances are most prevalent in cosmetic formulations.
- Highlights companies associated with the highest number of hazardous ingredient reports, useful for regulatory and consumer awareness.
- Determines which broader product categories have the highest presence of toxic ingredients.
  
## Dependencies: 
This project uses the following Python libraries:
- pandas – for data loading, cleaning, transformation, and analysis
- matplotlib – for creating visualizations and plotting trends in the data
  
## Data Sources
- https://data.chhs.ca.gov/dataset/596b5eed-31de-4fd8-a645-249f3f9b19c4/resource/57da6c9a-41a7-44b0-ab8d-815ff2cd5913/download/cscpopendata.csv
- https://www.google.com/url?sa=D&q=https://safecosmetics.cdph.ca.gov/search/&ust=1754469360000000&usg=AOvVaw2nEL4ejd2YoRkM-65E981u&hl=en
