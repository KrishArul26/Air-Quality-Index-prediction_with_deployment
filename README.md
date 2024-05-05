<h1 align="center"> Air-Quality-Index-prediction- Using PM 2.5 value</h1>
India is one of the higher air pollution country. Generally, air pollution is assessed by PM value or air quality index value. For my further analysis, I have selected PM-2.5 value to determine the air quality prediction and India-Bangalore region. Also, the data was collected through web scraping with the help of Beautiful Soup.</p>

<p align="center">
  <img width="300" src="https://user-images.githubusercontent.com/74568334/120612282-55761b80-c455-11eb-8b68-2afa01a0017e.jpg">
</p> 

 ### Demo of the app: 
 
 * If wanted to see App Please click [here](https://air-quality-index-predictio.herokuapp.com/)
 
 ### Please Enter the value & clisk the predict button
 
 <p float="left">
  <img src="https://user-images.githubusercontent.com/74568334/120625928-709b5800-c462-11eb-8745-e847bf5cb661.png" width="400" />
  <img src="https://user-images.githubusercontent.com/74568334/120625936-71cc8500-c462-11eb-908e-4be22049962e.png" width="400" /> 
</p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/74568334/120625922-6e38fe00-c462-11eb-96b4-431352a5ed91.png" width="450" />
</p>

<h2 align="center"> Technologies Used </h2>
 
 ```
 1. IDE - Pycharm
 2. Linear Regression Model
 3. Ridge and Lasso Regression
 4. Support vector regressor(SVR)
 5. Extra tree regressor
 6. Decission tree regressor
 7. Google Colab - Trained ML model
 8. Flask- Rest API
 9. Postman - API Tester
10. Heroku
 
 ```
 
 
### 📁 Data Collection

* Air quality data was collected from the  "http://en.tutiempo.net/climate". So, here I selected the India- Bangalore'sregion & collected  the independent features such as Average annual temperature(AT), Annual average maximum temperature(TM), Average annual minimum temperature(Tm), Rain or snow precipitation total annual(PP), Annual average wind speed(V), Number of days with rain(RA), Number of days with snow(SN) and dependent feature as PM 2.5 values has been colected from the "dhewdhjwdhjw"

* The dataset used can be downloaded [Here](https://raw.githubusercontent.com/KrishArul26/End-to-End-Deployment-Air-Quality-Index-prediction/main/Dataset/Airquality_index.csv) from the 2013 to 2018.

<h3 align="left">Data Preprocessing</h3>
 
Data Preprocessing of the raw data [Google Colab For EDA Vist, Here](https://github.com/KrishArul26/Air-Quality-Index-prediction_with_deployment/blob/main/ML_Applied_Word/PreProcess/AQI_linear_regressor.ipynb)  
 
<p style= 'text-align: justify;'> 

               1.	Remove Unnecessary Columns

               2.	Feature Engineering Selection
                    
                                                  
                                                  * Correlation Analysis
  
                                                  * Hnadling Out layer - Capping using Percentile method (Winsorization )
                                                    
                                                  * Feature Importances
                                                

               3.	Finding The Null Values Present In The Dataset

               
               3.	Handle the NaN values
  
               6.	Missing Values Replace With Mean

               8.	Dimensionality Reduction Using  PCA

               9.	Remove Columns Which A Standard Deviation Of Zero

</p>

### 🔑 Prerequisites
* All the dependencies and required libraries are included in the file [requirements.txt](https://github.com/KrishArul26/End-to-End-Deployment-Air-Quality-Index-prediction/blob/main/requirements.txt)

### 🚀 Installation

1. Clone the repo
```
git clone https://github.com/KrishArul26/End-to-End-Deployment-Air-Quality-Index-prediction.git

```

2. Change your directory to the cloned repo

```
cd End-to-End-Deployment-Air-Quality-Index-prediction
```

3. Create a Python virtual environment named 'AQI' and activate it

```

 pip install virtualenv

 virtualenv AQI

 AQI\Scripts\activate
```

4. Now, run the following command in your Terminal/Command Prompt to install the libraries required

```
pip install -r requirements.txt
```

### 💡 Working

1. Open terminal. Go into the cloned project directory and type the following command:

```
python app.py
```

### 🔑 Results 

* For this project Support vector regressor(SVR), linear regressor, Extra tree regressor, decision tree regressor  and XGBoost regressor has  applied.By tuned hyperparameter for all algorithms finally received these evaluation parameters MAE, MSE & RMSE. Among them, the Extra tree regressor has the lowest MAE values. So, for further analysis, I used an Extra tree regressor.

### Linear Regressor: [Open In Colab](https://colab.research.google.com/drive/1NcUmCqjKPRPVkMVy8a4XpSckJQtf8Jbl)

### Evaluation Matrix
| Evaluation Parameter   | Value    |
| -------------          | ---------|
|       MAE              | 43.505   |
|       MSE              | 3335.414 |
|       RMSE             | 57.753   |

### Support vector regressor(SVR): [Open In Colab](https://colab.research.google.com/drive/12h-d2312pKbSeoZdYr7koJR_gx_jbZ6w)

### Evaluation Matrix

| Evaluation Parameter   | Value    |
| -------------          | ---------|
|       MAE              | 40.780   |
|       MSE              | 3277.271 |
|       RMSE             | 57.247   |

### Extra tree regressor: [Open In Colab](https://colab.research.google.com/drive/1dLHFSKFgN21r3mhxcD_KK1BKPPlj-eyk)

### Evaluation Matrix

| Evaluation Parameter   | Value    |
| -------------          | ---------|
|       MAE              | 19.348   |
|       MSE              | 1185.348 |
|       RMSE             | 34.429   |

### Decission tree regressor: [Open In Colab](https://colab.research.google.com/drive/1AiufkqPVvz1lZZMrZCfQTi6z5XPbzcrP) 

### Evaluation Matrix

| Evaluation Parameter   | Value    |
| -------------          | ---------|
|       MAE              | 26.92    |
|       MSE              | 2440.952 |
|       RMSE             | 49.406   |

### 🔑 Comparision 
      |----------------------------|------------------------|----------|
      |                            | Evaluation Parameter   | Value    |
      |----------------------------|------------------------| ---------|
      |  Linear Regressor          |       MAE              | 43.505   |
      |                            |       MSE              | 3335.414 |
      |                            |       RMSE             | 57.753   |
      |----------------------------|------------------------|----------|


### 👏 And it's done!

Feel free to mail me for any doubts/query ✉️ ragavan.arul26@gmail.com
