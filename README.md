# Market Positioning Of Mobile Prediction
![download](https://user-images.githubusercontent.com/89068470/133894216-145de226-95b4-4f9d-a160-a27ef32e3072.jpg)

The price of a product is the most important attribute of marketing that product. 
One of those products where price matters a lot is a smartphone because it comes with a lot of features so that a company thinks a lot about how to price this mobile which can justify the features and also cover the marketing and manufacturing costs of the mobile. 

In the section below, I will introduce you to a k-nearest neighbors(knn) machine learning project on a mobile price classification model where I will train a model to classify the price range of mobiles using Python.

So, since our task is to classify the price range of mobile phones and not to predict the actual prices, so here I am going to train a classification model to classify the price range of mobile phones as:

0 (low cost)

1 (medium cost)

2 (high cost)

4 (very high cost)

# Methodology

## 1) Data Collection

The features of mobiles are collected fromhttps://www.kaggle.com

#### Category:
Id,Batterypower,bluetooth,clock_speed,dual_sim,Front Camera megapixels,four_g,int_memory,Mobile Depth incm,Weight of mobile phone,n_cores:Number of cores of processor, Primary Camera megapixels,px_height:Pixel ResolutionHeight,px_width:Pixel ResolutionWidth,ram:Random Access Memory inMegabytes,sc_h:Screen Height of mobile incm,sc_w:Screen Width of mobile incm,talk_time:longest time that a single batterycharge will last when youare,three_g,touch_screen,wifi

## 2) Data Analysis and Preparation 

Data preparation is the process of cleaning and transforming raw data before building predictive models.

Here, we analyze and prepare data to perform classification techniques:

1. Check data types. Ensure your data types are correct. Refer data definitions to validate

2. Check for missing values

3. Study summary statistics

4. Distribution of variable

5. Study correlation

6. Detect outliers

7. Check for missing values

## 3) Classification Model

Now let’s train the mobile price classification model using Python. As this is a problem of classification, I will be using the k-nearest neighbors(knn) Regression algorithm with ad without GridSearch.

## 4) Conclusion

1 Accuracy of KNN algorithm when n=3 is 91%

2 Accuracu is very low when Feature scaling is done

3 Accuracy of KNN algorithm with GridSearch is 93%

## Future Scope

To achieve maximum accuracy and predict more accurate, more and more instances should be added to the data set or we can try with Random forest algorithm and DT algorithm. And selecting more appropriate features can also increase the accuracy. So data set should be large and more appropriate features should be selected to achieve higher accuracy. 

