# Boston-House-Price-Prediction
The problem that we are going to solve here is that given a set of features that describe a house in Boston, our machine learning model must predict the house price. To train our machine learning model with boston housing data, we will be using scikit-learn’s boston dataset.

In this dataset, each row describes a boston town or suburb. There are 506 rows and 13 attributes (features) with a target column (price).
Given a list of attributes of the household, the goal is to predict the monetary value of any house located in Boston city. The features can be summarized as follows:

 CRIM: This is the per capita crime rate by town<br>
 ZN: This is the proportion of residential land zoned for lots larger than 25,000 sq.ft.<br>
 INDUS: This is the proportion of non-retail business acres per town.<br>
 CHAS: This is the Charles River dummy variable (1 if tract bounds river; 0 otherwise)<br>
 NOX: This is the nitric oxides concentration (parts per 10 million)<br>
 RM: This is the average number of rooms per dwelling<br>
 AGE: This is the proportion of owner-occupied units built prior to 1940<br>
 DIS: This is the weighted distances to five Boston employment centers<br>
 RAD: This is the index of accessibility to radial highways<br>
 TAX: This is the full-value property-tax rate per $10,000<br>
 PTRATIO: This is the pupil-teacher ratio by town<br>
 B: B =1000(BK — 0.63)², where BK is African American people proportion descent by town<br>
 LSTAT: This is the percentage lower status of the population<br>
 MEDV: This is the median value of owner-occupied homes in $1000s (Target Variable) <br>
 (Build using : Python, Jupyter Notebook, Pandas, Matplotlib, Scikit Learn)

insert into VDBMasterFaceData
select id, CustId, SiteId, Source, Embeddings, ImageName, ImageURL, Time, CreatedBy, UpdatedBy, CreatedAt, UpdatedAt, 0, 0, RoiName, 0 from MasterFaceData where CustId = 'ec31bced-abca-4888-a501-f41a9318bafa'
