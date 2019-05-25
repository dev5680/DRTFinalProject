# DRTFinalProject
IST718 Final Project for D &amp; R &amp; T
# Storyboard
## In Progress
- [ ] Create Our Yelp User csv from review.json
- [ ] Project checkpoint 2
- [ ] Create Our Yelp Tips csv from tips.json
- [ ] Add Sentiment and Authenticity Columns  to Yelp Reviews csv and Use predictive model to populate the columns

## ToDo
- [ ] Create Our Yelp Photo csv from photo.json
- [ ] Create Our Yelp Checkin csv from checkin.json
- [ ] Check for possible integration of restaurant revenue information to our base data
- [ ] Merge all yelp csv data into a single csv using their unique identifier. The final csv will  be used for EDA and Modeling
- [ ] EDA
- [ ] Understanding the spatial distribution effect: Location Advantage 
- [ ] Effect of location on yelp reviews sentiment and authenticity based on categories
- [ ] Relationship and correlation between all variables
       
- [ ] Modeling
- [ ] Reporting

       
- [ ] Presentation slides: Ppt
## Complete
- [X] Submitted document
* [Project checkpoint 1](https://github.com/richpatanalytics/DRTFinalProject/blob/master/b.2.1_41473_project_checkpoint_1_clean.pdf)
* [Project checkpoint 2](https://github.com/richpatanalytics/DRTFinalProject/blob/master/b.4.1_41474_project_checkpoint_2_clean.pdf)
       
- [x] Understanding yelp data

*  [notebook for initial exploration](https://github.com/richpatanalytics/DRTFinalProject/blob/master/DescribeYelpData.ipynb)
      
- [x] Create Our Yelp Business csv from business.json

*  [yelp business csv](https://github.com/richpatanalytics/DRTFinalProject/blob/master/ouryelpbusinesses.csv)
      
* [notebook for creating business csv](https://github.com/richpatanalytics/DRTFinalProject/blob/master/MakeOurYelpBusinesses.ipynb)
       
- [x] Create Our Yelp Reviews csv from review.json and OurYelpBusiness.csv

* [notebook for making yelp review csv](https://github.com/richpatanalytics/DRTFinalProject/blob/master/MakeOurYelpReviews.ipynb)
       
- [x] Create Our DBH Restaurants csv from source files downloaded from DBH

* [Source code](https://github.com/richpatanalytics/DRTFinalProject/blob/master/MakeOurDBHRestaurantData.rmd)
       
* [DBH Restaurants csv](https://github.com/richpatanalytics/DRTFinalProject/blob/master/DBHRestaurants.csv)
       
- [x] Create SVM and Bernolli model and Save it in Pickle object to be used for predicting Reviews sentiment and its authenticity
* [notebook for creating svm and Bernolli model for sentiment and authenticity](https://github.com/richpatanalytics/DRTFinalProject/blob/master/DRT_Reviews_Model_SVM_BNB.ipynb)
* [SVM pickle model](https://github.com/richpatanalytics/DRTFinalProject/blob/master/SVM-model-for-sentiment-classification-in-reviews.sav)
      
* [Vectorizer for SVM model pickle object](https://github.com/richpatanalytics/DRTFinalProject/blob/master/SVM-model-for-sentiment-classification-in-review-vectorizer.sav)
      
* [Bernolli pickle model](https://github.com/richpatanalytics/DRTFinalProject/blob/master/BNB-model-for-lie-detection-in-reviews.sav)
      
* [Vectorizer for bernolli model](https://github.com/richpatanalytics/DRTFinalProject/blob/master/BNB-model-for-lie-detection-in-review-vectorizer.sav)
      
