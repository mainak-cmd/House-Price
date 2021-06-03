# predicting House-Price setps 
#..project.ipynb ##.
1.load lyberies#..
2.load data #..
3.remove features haveing more than 50% null value #..
4.one-hot encodeing of categorical features #..
5.prepare na-imputation stategy #..
6.Useing PCA dimentianality reduction #..
7.Use FFS useing linear model to selection of more  relavent features #..
8.create one ols and elastic net regression model #..
9.create pipeline to combine (na-imputation stategy,PCA(100), FFS useing linear model,ols) #..
  and  (na-imputation stategy,PCA(100), FFS useing linear model, elastic net) #..
10.validation both  pipeline object by cross-validation method(k=6).#..
11.combine both model with voteing regressor (final model) #..
12.validate model useing crossvalidation #..
13.model.fit(X,y) #..
14.import model as joblib file #..


#..prediction.ipynb#..
1)import file as clf #..
2)one-hot encodeing #..
3)clf.predict(test file) #..
4)datasets.to_csv('sample_submission1.csv',index=False) #..
 
