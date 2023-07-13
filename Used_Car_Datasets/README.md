# Used Cars

The datasets in this folder come from two separate Kaggle competitions.

- German Used Cars: [https://www.kaggle.com/datasets/wspirat/germany-used-cars-dataset-2023](https://www.kaggle.com/datasets/wspirat/germany-used-cars-dataset-2023)
- Polish Used Cars: [https://www.kaggle.com/datasets/wspirat/poland-used-cars-offers](https://www.kaggle.com/datasets/wspirat/poland-used-cars-offers)

The two datasets have similar columns, but with different names and different units (especially for sale price).

Potential projects with these data:

- Joining the data together by car type, which requires aggregation.
	- Alternatively, one data set could supplement the other. For example, the horsepower for Mazda 3 should be the same for both countries, so the Polish data could be supplemented with the information about the cars in the German data.
- Fitting a model to each, then determining whether the resulting inferences agree
	- For example, is the relationship between sale price and mileage the same between the two brands, after controlling for the available covariates?
- Using one to extend the other (with a "Country" column to denote which data set it came from), then training a model that uses "Country" as a predictor to find the overall differences.
	- Requires interaction terms!

# Further Uses

There are at least 3 other data sets that could be used here:

- [US Used Cars](https://www.kaggle.com/datasets/ananaymital/us-used-cars-dataset)
	- Has many more measurements, and could be joined by make/model to add more information to the above information.
	- Important: US cars are build differently from EU cars (different regulations)
- [Pakistan Used Cars](https://www.kaggle.com/datasets/karimali/used-cars-data-pakistan)
	- This set is not well documented, but could be useful.
- [Belarus Used Cars](https://www.kaggle.com/datasets/slavapasedko/belarus-used-cars-prices)
	- This fits in well the the original two, and a larger assignment might include this one. 

A student might want to, say, try and gather further information about each car
