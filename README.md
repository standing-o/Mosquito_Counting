# Prediction of # Mosquito with Regression (20200611)
- Prediction of the number of mosquito with weather dataset
- Multiple Linear Regression, Polynomial Regression

### Midterm project for the ' AI for Non-major' Course
- Mosquitoes serve as a medium for various diseases. As the number of people infected with these diseases is on a steady rise, 
it is necessary to predict the number of mosquito.

## Project Reprot
[[Report]]()

## Dataset
1. Independent Variable (Tempurature, Humidity)
- https://data.kma.go.kr/data/grnd/selectAsosRltmList.do?pgmNo=36
- https://data.kma.go.kr/stcs/grnd/grndTaList.do?pgmNo=70
2. Dependent Variable (# mosquito)
- http://news.seoul.go.kr/welfare/mos_dmsnblt2

## Architecture
1. Multiple Linear Regression
2. Polynomial Regression

## Result - MAE, R2-Score
1. Multiple Linear Regression
- Train MAE : 769, Test MAE : 805
- Train R2-Score : 0.46, Test R2-Score : 0.44

2. Polynomial Regression
- Train MAE : 715, Test MAE : 828
- Train R2-Score : 0.55, Test R2-Score : 0.46
