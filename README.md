# DRTFinalProject
IST718 Final Project for D &amp; R &amp; T
# Storyboard
## In Progress
- [ ] Exploring business categories by reviews and sentiment labels based on business location

## ToDo
- [ ] Check for possible integration of restaurant revenue information to our base data
- [ ] Merge all yelp csv data into a single csv using their unique identifier. The final csv will  be used for EDA and Modeling
- [ ] EDA
- [ ] Modeling
- [ ] Reporting     
- [ ] Presentation slides: Ppt
## Complete
- [X] Project Checkpoint
* [Checkpoint 1: word doc](https://github.com/richpatanalytics/DRTFinalProject/blob/master/Paterson_.Week5ProjectCheckIn.docx)
* [Checkpoint 2: word doc](https://github.com/richpatanalytics/DRTFinalProject/blob/master/Paterson_.Week7ProjectCheckIn.docx)
       
- [x] Understanding yelp data
* [notebook for initial exploration](https://github.com/richpatanalytics/DRTFinalProject/blob/master/DescribeYelpData.ipynb)

- [x] Create Our Yelp Photos csv from photo.json
* [Our Yelp Photos csv is in Watson](https://dataplatform.cloud.ibm.com/projects/d24d039e-b23d-44d8-9c5c-a3ac98951474/assets?context=wdp)
* [notebook for creating photos csv](https://github.com/richpatanalytics/DRTFinalProject/blob/master/MakeOurYelpPhotos.ipynb)

- [x] Create Our Yelp Checkins csv from checkin.json
* [Our Yelp Checkins csv is in Watson](https://dataplatform.cloud.ibm.com/projects/d24d039e-b23d-44d8-9c5c-a3ac98951474/assets?context=wdp)
* [notebook for creating checkins csv](https://github.com/richpatanalytics/DRTFinalProject/blob/master/MakeOurYelpCheckins.ipynb)

- [x] Create Our Yelp Tips by User csv and Create Our Yelp Tips by Business csv from tip.json
* [Our Yelp Tips by User csv is in Watson](https://dataplatform.cloud.ibm.com/projects/d24d039e-b23d-44d8-9c5c-a3ac98951474/assets?context=wdp)
* [Our Yelp Tips by Business csv is in Watson](https://dataplatform.cloud.ibm.com/projects/d24d039e-b23d-44d8-9c5c-a3ac98951474/assets?context=wdp)
* [notebook for making yelp tips csv](https://github.com/richpatanalytics/DRTFinalProject/blob/master/MakeOurYelpTips.ipynb)
      
- [x] Create Our Yelp Business csv from business.json
* [Our Yelp Businesses csv is in Watson](https://dataplatform.cloud.ibm.com/projects/d24d039e-b23d-44d8-9c5c-a3ac98951474/assets?context=wdp)
* [notebook for creating business csv](https://github.com/richpatanalytics/DRTFinalProject/blob/master/MakeOurYelpBusinesses.ipynb)
       
- [x] Create Our Yelp Users csv from user.json and OurYelpReviews.csv
* [Our Yelp Users csv is in Watson](https://dataplatform.cloud.ibm.com/projects/d24d039e-b23d-44d8-9c5c-a3ac98951474/assets?context=wdp)
* [notebook for making yelp users csv](https://github.com/richpatanalytics/DRTFinalProject/blob/master/MakeOurYelpUsers.ipynb)
       
- [x] Create Our Yelp Reviews csv from review.json and OurYelpBusiness.csv
* [Our Yelp Reviews csv is in Watson](https://dataplatform.cloud.ibm.com/projects/d24d039e-b23d-44d8-9c5c-a3ac98951474/assets?context=wdp)
* [notebook for making yelp review csv](https://github.com/richpatanalytics/DRTFinalProject/blob/master/MakeOurYelpReviews.ipynb)
       
- [x] Create Our IRS2016 by zip from source files downloaded from IRS website
* [IRS2016 Adjusted Gross Income csv](https://github.com/richpatanalytics/DRTFinalProject/blob/master/ourIRS2016byzip.csv)
* [notebook for creating IRS2016 AGI By Zip](https://github.com/richpatanalytics/DRTFinalProject/blob/master/MakeOurIRS2016Data.ipynb)
* [Data Dictionary for IRS2016 AGI Source Data Zip](https://github.com/richpatanalytics/DRTFinalProject/blob/master/16zpdoc.doc)
* [IRS2016 AGI Source Data Zip](https://github.com/richpatanalytics/DRTFinalProject/blob/master/16zpallnoagi.csv)

- [x] Create Our DBH Restaurants csv from source files downloaded from DBH
* [DBH Restaurants csv](https://github.com/richpatanalytics/DRTFinalProject/blob/master/DBHRestaurants.csv)
* [Source code](https://github.com/richpatanalytics/DRTFinalProject/blob/master/MakeOurDBHRestaurantData.rmd)  
       
- [x] Create SVM and Bernolli model and Save it in Pickle object to be used for predicting Reviews sentiment and its authenticity
* [notebook for creating svm and Bernolli model for sentiment and authenticity](https://github.com/richpatanalytics/DRTFinalProject/blob/master/DRT_Reviews_Model_SVM_BNB.ipynb)
* [SVM pickle model](https://github.com/richpatanalytics/DRTFinalProject/blob/master/SVM-model-for-sentiment-classification-in-reviews.sav)
      
* [Vectorizer for SVM model pickle object](https://github.com/richpatanalytics/DRTFinalProject/blob/master/SVM-model-for-sentiment-classification-in-review-vectorizer.sav)
      
* [Bernolli pickle model](https://github.com/richpatanalytics/DRTFinalProject/blob/master/BNB-model-for-lie-detection-in-reviews.sav)
      
* [Vectorizer for bernolli model](https://github.com/richpatanalytics/DRTFinalProject/blob/master/BNB-model-for-lie-detection-in-review-vectorizer.sav)

- [x] Add Sentiment and Authenticity Columns  to Yelp Reviews csv and Use predictive model to populate the columns
* [Notebook used in creating reviews sentiment label and review authenticity](https://github.com/richpatanalytics/DRTFinalProject/blob/master/DRT_Topic_Modeling.ipynb)
* [Our Review CSV with Sentiment and Lie Label in watson](https://dataplatform.cloud.ibm.com/projects/d24d039e-b23d-44d8-9c5c-a3ac98951474/data-assets/bae12619-39d0-407f-81f8-4236e30bf216/preview?context=wdp&label=true)

