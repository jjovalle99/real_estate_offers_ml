# Colombian Real Estate Analysis

Welcome to a comprehensive examination of Colombian Real Estate. This repository serves two primary objectives:

1. **Spatial Analysis of Bogota's Local Planning Units (UPLs)**: This section offers a detailed spatial analysis of real estate data from UPLs within Bogota. It's an effort to understand and visualize the spatial distribution and value of properties across the city.

   ![image](https://github.com/jjovalle99/real_estate_offers_ml/assets/70274018/64a0bf55-3820-4233-b8e3-178d234f33a7)

---

2. **Real Estate Price Prediction Using Machine Learning**: This section applies advanced machine learning algorithms, including cuML models, LightGBM (LGBM), and XGBoost (XGB) to predict real estate prices in Colombia. The objective is to compare the performance of different cuML algorithms on this task.

|index|Model|Encoder|RMSE|MAPE|
|---|---|---|---|---|
|2|RandomForestRegressor|CountEncoder|112886713\.93503477|0\.17366143998219882|
|17|RandomForestRegressor|TargetEncoder|114407377\.9065233|0\.1745764837871104|
|7|RandomForestRegressor|OrdinalEncoder|113812291\.78511655|0\.1749740745295431|
|12|RandomForestRegressor|CatBoostEncoder|116905648\.72170931|0\.17924782727884345|
|3|LGBMRegressor|CountEncoder|122536326\.41680773|0\.9433010197066174|
|8|LGBMRegressor|OrdinalEncoder|122568239\.34350301|0\.943577215130025|
|18|LGBMRegressor|TargetEncoder|122746589\.2103273|1\.022192559825529|
|13|LGBMRegressor|CatBoostEncoder|122799470\.68142268|1\.029640192124058|
|9|XGBRegressor|OrdinalEncoder|119053695\.60603538|1\.669367335838242|
|19|XGBRegressor|TargetEncoder|118784383\.40361884|1\.6975442573974686|
|4|XGBRegressor|CountEncoder|118863516\.56987615|1\.710678823184067|
|14|XGBRegressor|CatBoostEncoder|119676800\.82033098|1\.74528200032427|
|6|KNeighborsRegressor|OrdinalEncoder|187778458\.51562026|6\.693841283899329|
|5|LinearRegression|OrdinalEncoder|215786204\.44626233|23\.958934785041336|
|0|LinearRegression|CountEncoder|214863421\.4043423|24\.940286758933492|
|15|LinearRegression|TargetEncoder|216404101\.47722277|25\.091120206745277|
|10|LinearRegression|CatBoostEncoder|215719077\.57940412|25\.185707807309008|
|16|KNeighborsRegressor|TargetEncoder|411403909\.81820893|43\.06533086057974|
|1|KNeighborsRegressor|CountEncoder|337918407\.5716689|47\.01756504910527|
|11|KNeighborsRegressor|CatBoostEncoder|456319499\.9628125|92\.22310589444508|

---

I invite you to explore the Jupyter notebook in this repository and share your valuable feedback. Each insight helps in refining the analysis and improving the models.

😊 Happy Analyzing!
