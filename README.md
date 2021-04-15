###	Predict CO2 Emission for each car(Linear regression, multiple, polynomial)
Dataset is related to fuel consumption and Carbon dioxide emission of cars. I built a model to predict produced co2 emission for each car.
## libraries
- numpy
- pandas
- matplotlib
- scikit learn
## algorithm and functions
- Simple Linear regression
- multiple Linear regression
- polynomial order 3 linear regression
## Analysis
![1](https://user-images.githubusercontent.com/56628918/87323327-ecc93c00-c52e-11ea-9252-53ae9877c621.png)
![2](https://user-images.githubusercontent.com/56628918/87323433-09657400-c52f-11ea-9dc9-cdf52217a162.png)
![3](https://user-images.githubusercontent.com/56628918/87323459-15e9cc80-c52f-11ea-9083-0c818e6f762a.png)
![4](https://user-images.githubusercontent.com/56628918/87323488-21d58e80-c52f-11ea-9c34-bfc51722728d.png)
![5](https://user-images.githubusercontent.com/56628918/87323535-33b73180-c52f-11ea-8d8f-33ee13b2c167.png)
![6](https://user-images.githubusercontent.com/56628918/87323568-3d409980-c52f-11ea-8f41-2c2261529157.png)

## Conclusion
After exploratory on data we found out which features have most strenght correlation on CO2EMISSIONS.Then we plotted each of them to see weather which model is better,linear model or non-linear ,it seemed a linear model can be good,so, I divided data to train and test,made a model with simple linear regression , I trained model with train data and tested model with test set(unseen data).It was resulted best R-squared equal to 0.80. Then I used multiple linear regression and obtained best R-squared equal to 0.86. Then I used a polynomial order 2 function in multiple regression and I trained model and tested on test data,R-squared becomes better equal to 0.89.then I tryied to find best order for this polynomial function and I founded order 3 with best R-squared equal to 0.91.so I can say best model for predict co2emissions is a polynomial order 3 multiple regression
