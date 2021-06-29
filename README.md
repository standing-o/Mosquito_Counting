# Prediction of # Mosquito with Regression
- Prediction of the number of mosquito with weather dataset
- Multiple Linear Regression, Polynomial Regression
- Jun. 11, 2020

### Midterm project for the ' AI for Non-major' Course
- Mosquitoes serve as a medium for various diseases. As the number of people infected with these diseases is on a steady rise, 
it is necessary to predict the number of mosquito.

| [Report](https://github.com/OH-Seoyoung/Prediction_of_the_number_of_Mosquito_with_Regression/blob/master/Report.pdf) |  

## Dataset
#### Independent Variable   
- Tempurature, Humidity  
#### Dependent Variable  
- The number of mosquito  

```
[1] https://data.kma.go.kr/data/grnd/selectAsosRltmList.do?pgmNo=36  
[2] https://data.kma.go.kr/stcs/grnd/grndTaList.do?pgmNo=70 
[3] http://news.seoul.go.kr/welfare/mos_dmsnblt2  
```
  
## Results
#### 1. Multiple Linear Regression  
|---|MAE|R2-Score|
|------|---|---|
|Train|769|0.46|
|Test|805|0.44|
  
#### 2. Polynomial Regression  
|---|MAE|R2-Score|
|------|---|---|
|Train|715|0.55|
|Test|828|0.46|

