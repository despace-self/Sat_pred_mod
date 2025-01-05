# Sat_pred_mod
This is an exploratory research of the data set predict-the-positions-and-speeds-of-600-satellites on Kaggle

Background

Within the past two decades, the number of resident space objects (RSOs - artificial objects that are in orbit around the Earth) has nearly doubled, from around 11000 objects in the year 2000 to around 19500 objects in 2019. This number is expected to rise even higher as more satellites are put into space, thanks to improvements in satellite technology and lower costs of production. On the other hand, the increase in the number of RSOs also indirectly increases the risk of collision between them. The important issue here is the reliable and accurate orbit tracking of satellites over sufficiently long periods of time.

Failure to address this issue has led to incidents such as the collision between the active US Iridium-33 communication satellite, and the inactive Russian Kosmos-2251 communication satellite in February 2009. In fact, this accident increased the amount of space debris by 13%.

The original datasets were obtained from the International Data Analytics Olympiad 2020 (IDAO 2020) Competition, provided by the Russian Astronomical Science Centre. Being a competition

The aim is to use machine learning or other forecasting algorithms to predict the positions and speeds of 600 satellites in orbit around the Earth.

This model used random forest regressor algorithm model summary is as follows,

Best Parameters: {'n_estimators': 100, 'min_samples_split': 2, 'min_samples_leaf': 1, 'max_depth': 20}
R² score on training set: 0.9782429338237613
Mean Absolute Error on training set: 140.76300258091433
R² score on test set: 0.872794880710587
Root Mean Squared Error (RMSE) on test set: 3649.22083114595
Mean Absolute Error on test set: 1110.4222626297246
Predictions on test set:
[[ 7.55419408e+03  2.78730995e+04  1.57287509e+04 -1.42692279e+00
   1.06688361e+00 -3.01099582e+00]
 [ 3.40487567e+03  2.97974576e+04  6.82901473e+03 -1.47362047e+00
   7.25144156e-02 -3.45988549e+00]
 [-2.11988512e+03  2.69283413e+04 -4.69549424e+03 -1.31356026e+00
  -9.28633390e-01 -2.92299295e+00]
 ...
 [-2.33766135e+04 -4.17717256e+03  4.52500815e+03  1.89020702e-01
   3.25253970e+00 -1.76552769e-01]
 [-2.02457684e+04  2.92448634e+03  4.81337975e+03  9.99306170e-02
   2.15766494e+00 -2.81001605e-01]
 [-2.00433989e+04  7.79301592e+03  3.40564991e+03  1.79327168e+00
   2.89795165e+00 -4.66529419e-01]]

  This is my second ML Model. 
  Constructive feedbacks are highly appreciated

  Thank you.
