<h1 align="center"> End-to-End--Deployment-Air-Quality-Index-prediction- Using PM 2.5 value</h1>

<p align="center">
  <img width="400" src="https://user-images.githubusercontent.com/74568334/120612282-55761b80-c455-11eb-8b68-2afa01a0017e.jpg">
</p>

 # Data Collection
Air quality data was collected from the  "http://en.tutiempo.net/climate". So, here we can select the which country's data and state in that country But this data does not contain the PM 2.5 value also, this value can be getting from "hjrferjfkjerfkjerfkjerkj". So, this data set contains the eight independent features such as Average annual temperature(AT), Annual average maximum temperature(TM), Average annual minimum temperature(Tm), Rain or snow precipitation total annual(PP), Annual average wind speed(V), Number of days with rain(RA), Number of days with snow(SN) and dependent feature as PM 2.5
 
 # How to run into the local computer
 1. open the terminal
 
 2. Create the virtual environmental
 
 3. pip install requirements.txt
 
 4. copy the IP address & paste it into the browser
 # Demo of the app: 
 APP: https://air-quality-index-predictio.herokuapp.com/
 
 #### Please Enter the value & clisk the predict button
 <p float="left">
  <img src="https://user-images.githubusercontent.com/74568334/120625928-709b5800-c462-11eb-8745-e847bf5cb661.png" width="400" />
  <img src="https://user-images.githubusercontent.com/74568334/120625936-71cc8500-c462-11eb-908e-4be22049962e.png" width="400" /> 
  <img src="https://user-images.githubusercontent.com/74568334/120625922-6e38fe00-c462-11eb-96b4-431352a5ed91.png" width="400" />
</p>


 
## For this project Support vector regressor(SVR), linear regressor, Extra tree regressor, decision tree regressor  and XGBoost regressor has  applied 
### Linear Regressor Evaluation Matrix

MAE: 43.50537218470877

MSE: 3335.4147056302113

RMSE: 57.75304931889061

### Support vector regressor(SVR)
MAE: 40.77491768583136

MSE: 3277.2711086212435

RMSE: 57.24745504056266

# Extra tree regressor

MAE: 19.168948833985706

MSE: 1185.3475699794517

RMSE: 34.4288769781916

# Decission tree regressor 

MAE: 26.917567224759008

MSE: 2440.952402192909

RMSE: 49.405995609773

## By tuned hyperparameter for all algorithms finally received these evaluation parameters MAE, MSE & RMSE. Among them, the Extra tree regressor has the lowest MAE values. So, for further analysis, I used an Extra tree regressor.
