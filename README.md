# Mobile-Price-Range-Prediction--Classification
The objective is to find out some relation between features of a mobile phone and its selling price. In this problem, we do have to predict price range indicating how high the price is.

# Data Description

##- <b>Dataset</b> - data_mobile_price_range.csv


- Battery_power - Total energy a battery can store in one time measured in mAh
- Blue - Has bluetooth or not
- Clock_speed - speed at which microprocessor executes instructions
- Dual_sim - Has dual sim support or not
- Fc - Front Camera mega pixels
- Four_g - Has 4G or not
- Int_memory - Internal Memory in Gigabytes
- M_dep - Mobile Depth in cm
- Mobile_wt - Weight of mobile phone
- N_cores - Number of cores of processor
- Pc - Primary Camera mega pixels
- Px_height - Pixel Resolution Height
- Px_width - Pixel Resolution Width
- Ram - Random Access Memory in Mega Byte
- Touch_screen - Has touch screen or not
- Wifi - Has wifi or not
- Sc_h - Screen Height of mobile in cm
- Sc_w - Screen Width of mobile in cm
- Talk_time - longest time that a single battery can last over a call
- Three_g - Has 3G or not
- Wifi - Has wifi or not
- Price_range - This is the target variable with value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost).


# Steps we performed

- Importing the libraries
- Treating Null values
- Exploratory Data Analysis - EDA
- Outliers Detection
- Sclaing and splitting of the data of data :-
- Modelling
   -Logistic Regression
   -Support Vector Classification
   -KNN- K- Nearest Neighbor
   -Naive bays classifiers 
   -Random Forest Classifiers
   -XGBoost
   -Feature Selection


# Conclusion
- From EDA we can see that here are mobile phones in 4 price ranges.
- RAM contributing more than any features for price ranges, and we can see that whenever we are increasing RAM price is linearly incresing.
- Half the devices have Bluetooth, and half don’t
- For Internal memory=34 price is sharply increases to Very high cost.
- Costly phones are lighter
- RAM, battery power, pixels played more significant role in deciding the price range of mobile phone.
- From all the above experiments we can conclude that logistic regression,Naive Bayes and, Random Forest Classifier with using hyperparameters we got the best results


