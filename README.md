# Manj_Portfolio
Portfolio web page
# [PROJECT 1 : Value Investor -  Time Series Forecasting of Stock Prices](https://github.com/ManjWeerapura/MyProject/blob/main/Project_5_Value_Investor/Value_investor_7.ipynb)
In this project, effectiveness of Time Series models to predict share prices were evaluated using Python. Using optimized parameters, an ARIMA (Auto Regressive Integrated Moving Average) model, ARIMAX (ARIMA with associated with an exogenous variable X) model, a simple Moving Average (MA) model or a Simple Exponential Smoothing (SES) model were used to predict next day’s share price for a particular stock. In a portfolio simulation, predicted share prices were then used to make informed trading decisions (Buy, Sell or Hold) on a daily basis based on its deviation from the trailing mean (Bollinger Bands method). Performance of the Time Series models were more profitable compared to a portfolio that only used uninformed (random) trading decisions daily. The latter approach generally resulted in a loss in the long term. Time Series models may prove as valuable tools in the investing sector focused on short-term profitability (e.g. day trading).

![](https://github.com/ManjWeerapura/Manj_Portfolio/blob/main/Value_investor.png?raw=true)

# [PROJECT 2 : Image Classification using OpenCV and Deep Learning](https://github.com/ManjWeerapura/MyProject/blob/main/Project_4_MonReader/MonReader_6.ipynb)
In this project, a Convolutional Neural Network model was created to correctly identify if an image from a document scanning technology (MonReader) shows the instance when a page is being flipped or not. The trained model was able to identify test images from the same platform with an overall accuracy of 80%.  The trained model was also generalized enough to correctly identifying custom images that were from a different source.

![](https://github.com/ManjWeerapura/Manj_Portfolio/blob/main/MonReader1.png?raw=true)
![](https://github.com/ManjWeerapura/Manj_Portfolio/blob/main/MonReader2.png?raw=true)

# [PROJECT 3 : Term Deposit Marketing –Data Analysis and Machine Learning to Predict Customer Subscription to a Term Deposit Account](https://github.com/ManjWeerapura/MyProject/blob/main/Project_4_MonReader/MonReader_6.ipynb)
Exploratory Data Analysis and several Machine Learning models were used to predict if a certain segment of bank customers were likely to subscribe for a term deposit account. The trained XGBoost model showed limited success in correctly identifying customers subscribing customers with an accuracy of about 36% (recall metric). Oversampling the training data using SMOTE slightly improved this accuracy metric to 46%. A balanced data set may help improving the model’s prediction accuracy.

![](https://github.com/ManjWeerapura/Manj_Portfolio/blob/main/term_deposit?raw=true)

# [PROJECT 4 : Covid-19 Epitope Prediction for in-silico Vaccine Design](https://github.com/ManjWeerapura/python_projects/blob/main/Covid19_epitope_prediction_for_vaccine_development/Covid19_antibody_prediction.ipynb)
In this project, I try to identify possible Covid-19 epitope candidates which can be used as starting points for vaccine development. Using various related and unrelated peptides with specific features as well as their ability to evoke neutralizing antibody responses, I evaluated a Logistic Regression Machine Learning model's ability to predict the induction of anti- Covid-19 antibodies.  Surprisingly, many of these ‘candidates’ align within a small region of the spike protein of the virus. The spike protein is presumed to bind to angiotensin-converting enzyme 2 (ACE2) receptors on the host cell membrane. This binding initiates virus internalization and hijacking of cellular machinery to replicate itself and release of new virus particles by exocytosis.  Antibodies binding to the spike protein can be expected to initiate destruction of the virus and may also prevent cell interaction and internalization.

      1130 <<<<<<<<<< amino acid pos. >>>>>>>>>>>>>>> 1181
      | ............................................... |
      IGIVNNTVYDPLQPELDSFKEELDKYFKNHTSPDVDLGDISGINASVVNIQ  <- SARS-COV2 spike protein
      ...................KEELDKYFKNHTSPD.................
      ..................FKEELDKYFKNHTSPD.................
      ................DSFKEELDKYFKNHTSP..................
      .................SFKEELDKYFKNHTSPD.................
      ...................KEELDKYFKNHTSPDVD...............
      ............QPELDSFKEELDKYFKNH.....................
      ................DSFKEELDKYFKNHTSPD.................
      ............QPELDSFKEELDKYFKNHT....................
      .............PELDSFKEELDKYFKNHTS...................
      ..............ELDSFKEELDKYFKNHTSP..................
      ...............LDSFKEELDKYFKNHTSPD.................
      ........YDPLQPELDSFKEELDKYFK.......................
      .........DPLQPELDSFKEELDKYFKN......................
      ............QPELDSFKEELDKYFKNHTS...................
      .............PELDSFKEELDKYFKNHTSP..................
      ..............ELDSFKEELDKYFKNHTSPD.................
      ................DSFKEELDKYFKNHTSPDVD...............

# [PROJECT 5: Abnormal Sickle Cell Identification Using OpenCV](https://github.com/ManjWeerapura/python_projects/blob/main/OpenCV_Sickle_cell_identification/sickle_cell_identification.ipynb)
OpenCV was used to process a microscopic image of a blood film to identify and mark abnormally-shaped sickle cells. The process of identification involved image thresholding, finding contours around all blood cells followed by using image moments to separate normal round blood cells from the abnormal sickle cells. It is hoped that sickle cell differentiation using OpenCV image moments can help in automating cell identification as well as determination of the severity of the anaemia.

![](https://github.com/ManjWeerapura/Manj_Portfolio/blob/main/sickle_cell_rs.png?raw=true)

# [PROJECT 6: Heart Failure Mortality Prediction](https://github.com/ManjWeerapura/python_projects/blob/main/Heart_Failure_Mortality_Prediction/heart-failure-mortality-predictions.ipynb)
In this project, the goal is to be able to predict, using Machine Learning models, the survival outcome in patients with congestive heart failure given the presence of various risk factors such as hypertension, diabetes, smoking and anaemia as well as blood markers such as serum creatinine, serum sodium and creatinine phosphokinase.

![](https://github.com/ManjWeerapura/Manj_Portfolio/blob/main/HF_mortality_risk.png?raw=true)

# [PROJECT 7: Coronary Artery Disease Prediction](https://github.com/ManjWeerapura/python_projects/blob/main/Coronary_Artery_Disease_Prediction/Heart_Disease_data_read.ipynb)
In this project, I explore the predictive capability of Machine Learning models to correctly identify if a patient suffers from coronary artery disease which is narrowing of the coronary arteries leading to reduced blood supply to the myocardium. The models use as features age, gender, various non-invasive parameters such as ECG and exercise stress test parameters as well as serum cholesterol and sugar levels.

![](https://github.com/ManjWeerapura/Manj_Portfolio/blob/main/Chest_pain_type.png?raw=true)
