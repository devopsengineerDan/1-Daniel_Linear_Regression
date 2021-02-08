# Linear_Regression
 We can decide to use scikit-learn library
 
 Type this program in Linear Regression.ipynb
 
 from sklearn.linear_model import LinearRegression
 from sklearn.metrics import mean_squared_error
 
 #Cannot use Rank 1 matrix in scikit learn
 X = X.reshape(m,1)
 
 #Creating model
 reg = reg.fit(x,y)
 
 #Fitting training data
 reg = reg.fit(X,Y)
 
 #Y prediction 
 Y_pred = reg.predict(X)
 
 #Calculating RMSE and R2 score
 mse = mean_squared_error(Y,Y_pred)
 rmse = np.sqrt(mse)
 r2_score = reg.score(X,Y)
 
 print(np.sqrt(mse))
 print(r2_score)
