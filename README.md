# Project Overview

For this project, you will use regression modeling to analyze house sales in a northwestern county.(King's County)

### Dataset

This project uses the King County House Sales dataset, which can be found in  `kc_house_data.csv` in the data folder in this repo. The description of the column names can be found in `column_names.md` in the same folder.

• Price : House Sold price (78k $ to 3.07m $ )

• Bedrooms : House of bedrooms ( 3 to 10 )

• Square living feet : Footage of the house (370 to 13.540)

• Square lot feet: Footage of the lot ( 520 to 130.680)

• Waterfront: House which has a view to a waterfront

• View : House has been viewed

• Zipcode : Zip

• Condition: How good the condition is ( Overall )


## Model

Linear Regression Model used in this project to predict house price.

## Conclusion:

This model can **%1.3** wrong predict on average for a house price.


### Findings 

1. Square Feet Living :
For new house every 100 feet added square feet living , price increases 1.9%. We expect this to be the case where
house gets bigger , price also increase.
2. Condition:
5(star) Condition most impactful as expected. Model says if the house has 5 condition rate price will be increase 5.6% .
3. Location:
For location our model shows zipcode 98039 location are the highest impact on price. If the new house will be in this
zipcode price will be increase 13.2%.
4. View:
If the house has more views price will be increase. As our model says ; fourth times viewed house price will be
increase %3.5

## Future Work

For future work for this model could be work on location with latitude,longitude for precise location for better modeling. And gather more data on construction spendings that how those will effect on house building.
