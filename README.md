<h1 align="center"> Air-Quality-Index-prediction- Using PM 2.5 value</h1>

<p align="center">
  <img width="400" src="https://user-images.githubusercontent.com/74568334/120612282-55761b80-c455-11eb-8b68-2afa01a0017e.jpg">
</p> 

 ### Demo of the app: 
 
 If wanted to see App Please click [here](https://air-quality-index-predictio.herokuapp.com/)
 
 ### Please Enter the value & clisk the predict button
 
 <p float="left">
  <img src="https://user-images.githubusercontent.com/74568334/120625928-709b5800-c462-11eb-8745-e847bf5cb661.png" width="450" />
  <img src="https://user-images.githubusercontent.com/74568334/120625936-71cc8500-c462-11eb-908e-4be22049962e.png" width="450" /> 
</p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/74568334/120625922-6e38fe00-c462-11eb-96b4-431352a5ed91.png" width="450" />
</p>
 
### 📁 Data Collection
Air quality data was collected from the  "http://en.tutiempo.net/climate". So, here I selected the India- Bangalore'sregion & collected  the independent features such as Average annual temperature(AT), Annual average maximum temperature(TM), Average annual minimum temperature(Tm), Rain or snow precipitation total annual(PP), Annual average wind speed(V), Number of days with rain(RA), Number of days with snow(SN) and dependent feature as PM 2.5 values has been colected from the "dhewdhjwdhjw"

The dataset used can be downloaded [Here](https://raw.githubusercontent.com/KrishArul26/End-to-End-Deployment-Air-Quality-Index-prediction/main/Dataset/Airquality_index.csv) from the 2013 to 2018.

### 🔑 Prerequisites
All the dependencies and required libraries are included in the file [requirements.txt](https://github.com/KrishArul26/End-to-End-Deployment-Air-Quality-Index-prediction/blob/main/requirements.txt)

### 🚀 Installation

1. Clone the repo

git clone https://github.com/KrishArul26/End-to-End-Deployment-Air-Quality-Index-prediction.git

2. Change your directory to the cloned repo

cd End-to-End-Deployment-Air-Quality-Index-prediction

3. Create a Python virtual environment named 'AQI' and activate it

pip install virtualenv

virtualenv AQI

AQI\Scripts\activate

4. Now, run the following command in your Terminal/Command Prompt to install the libraries required

pip install -r requirements.txt

### 💡 Working

Open terminal. Go into the cloned project directory and type the following command:

$ python app.py

### 🔑 Results 

For this project Support vector regressor(SVR), linear regressor, Extra tree regressor, decision tree regressor  and XGBoost regressor has  applied.By tuned hyperparameter for all algorithms finally received these evaluation parameters MAE, MSE & RMSE. Among them, the Extra tree regressor has the lowest MAE values. So, for further analysis, I used an Extra tree regressor.

### Linear Regressor: [Open In Colab](https://colab.research.google.com/drive/1NcUmCqjKPRPVkMVy8a4XpSckJQtf8Jbl)

### Evaluation Matrix
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
 
MAE: 43.50537218470877

MSE: 3335.4147056302113

RMSE: 57.75304931889061

### Support vector regressor(SVR): [Open In Colab](https://colab.research.google.com/drive/12h-d2312pKbSeoZdYr7koJR_gx_jbZ6w)

### Evaluation Matrix

MAE: 40.77491768583136

MSE: 3277.2711086212435

RMSE: 57.24745504056266

### Extra tree regressor: [Open In Colab](https://colab.research.google.com/drive/1dLHFSKFgN21r3mhxcD_KK1BKPPlj-eyk)

### Evaluation Matrix

MAE: 19.168948833985706

MSE: 1185.3475699794517

RMSE: 34.4288769781916

### Decission tree regressor: [Open In Colab](https://colab.research.google.com/drive/1AiufkqPVvz1lZZMrZCfQTi6z5XPbzcrP) 

### Evaluation Matrix

MAE: 26.917567224759008

MSE: 2440.952402192909

RMSE: 49.405995609773

### 👏 And it's done!

Feel free to mail me for any doubts/query ✉️ ragavan.arul26@gmail.com
