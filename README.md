# HCDS_Final_Project
## Michael Grant
This repository contains the data, code and report for the HCDS 512 final project titled Veggie Tales. 

### License: MIT

The MIT license means that this work is open to use by anyone, just please credit me for the work. 

---

### Codebook
There were many iterations of data in the cleaning process which is all documents in the notebook at length. The final data used for analysis was a wide form which I will describe below.

* food_type: They type or variety of food, i.e. apply, banana, cherry etc.
* location: Where the price of that corresponding food type was collected.
* date: The date in which that price was collected.
* category: Whether the food was organic or conventional.
* price.organic: The price for the organic version of that food type.
* price.conventional: The price for the conventional version of that food type.
* price_diff: The difference in price.
* percent_diff: The percent increase, or premium, of the organic version above the conventional version.

---

### Data Source

The data for this project came from teh United States Department of Agriculture and can be found for downlaod following this [link](https://www.ers.usda.gov/data-products/organic-prices.aspx). The data can also be downloaded directly from this github account in the data folder, or by running the code contained withing the corresponding Final Project jupyter notebook. It has been setup to be as seemless as possible with the raw code from the download transforming into the cleaned data used for analysis. 

The license for this code is the CC-BY createive commons license allowing for sharing, copying and redistribution as long as the source is credited. 

---

### Reproducibility

Please follow along the steps contained withint the jupyter notebook. Each step of the data cleaning and analysis process is documented, annotated and commented thoroughly for reproductiong and transparency. If there are any questions and/or comments please feel free to contact me directly at (mrgrant@uw.edu). I would be happy to assist with anything you may have. 
