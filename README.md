# Starbucks Capstone Challenge

Dataset has 3 files namely

### Portfolio - This data provides informatiomn on the offers by starbucks
* id (string) - offer id
* offer_type (string) - type of offer ie BOGO, discount, informational
* difficulty (int) - minimum required spend to complete an offer
* reward (int) - reward given for completing an offer
* duration (int) - time for offer to be open, in days
* channels (list of strings)

### Profile - This data provides information about the customer profile
* age (int) - age of the customer
* became_member_on (int) - date when customer created an app account
* gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
* id (str) - customer id
* income (float) - customer's income

### Transcript - This data provides actual transactions done by the customers and also offers that starbucks sends to them
* event (str) - record description (ie transaction, offer received, offer viewed, etc.)
* person (str) - customer id
* time (int) - time in hours since start of test. The data begins at time t=0
* value - (dict of strings) - either an offer id or transaction amount depending on the record

## Data Unzipping
Data for this project has files over 25 MB in size and therefore it was possible only to add a zip file for the data folder.

Before running the code, please unzip the file data.zip and it will create a folder called data in the repository. Then you can run the code.

## Description

This project is the capstone project of Udacity Nanodegree and the objective of the project is to suggest which kind of offers should starbucks create in future, also what type of users should it target for these offers

This 1 python file -
* Inputs Data
* Processes and Cleans relevant information
* Combines all 3 datasets into 1 normalised dataset
* Analyzes data to provide target offers and target customers

## Getting Started

### Dependencies

* Windows, Mac, Linux
* Latest Python Release
* Libraries - pandas, numpy, matlibplot, math, json, sys, datetime (all these libraries can be installed using pip command)

### Installing

* This is public git project which can be downloaded or cloned
* Before executing make sure dependencies are installed and necessary files are downloaded
* Please keep the files in the folder called "data" or if you choose a different folder please change the path where files are being read in the code

## Help

If you need help or facing issues, you can write to wwdivij@gmail.com

## Authors

[@divijwadhawan](https://github.com/divijwadhawan)
[@blog](https://medium.com/@wwdivij/start-your-data-science-learning-with-airbnb-seattle-analysis-example-98798d29f778)
## Version History

* 0.1
    * Initial Release

## Acknowledgments
* [Udacity](https://classroom.udacity.com/)
* [Git Repo For Data](https://github.com/susmithagudapati/Starbucks-Capstone-Challenge/tree/master/data)
