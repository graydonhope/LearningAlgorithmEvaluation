# Evaluation Learning Algorithms
## Using Bias and Variance metrics / Analyzing Learning Curves 

This program studies models with different bias and variance properties. It uses learning curves to inform the developer how to enhance algorithm parameters to optimize performance.

### Uses a Cross Validation Set to Determine Regularization Parameter

## Plotting the training and cross validation error:
### Using linear regression on data with a non-linear pattern:
![image](https://user-images.githubusercontent.com/41659296/56093204-997fbe00-5e93-11e9-9de8-5ef4ae168ccb.png)

### Learning curve with high-bias
![image](https://user-images.githubusercontent.com/41659296/56093177-502f6e80-5e93-11e9-87c3-c3bcef76f9a5.png)

Showing high-bias which means the model is too simple to fit the dataset well.

### Using polynomial regression 
![image](https://user-images.githubusercontent.com/41659296/56093225-d350c480-5e93-11e9-9fdc-8761f879b9ea.png)

### Learning curve with high-variance
![image](https://user-images.githubusercontent.com/41659296/56093246-fda28200-5e93-11e9-95a5-1d80c7cb7f8a.png)

Showing the model has too many features and is overfitting the data.

### Selecting lambda value using cross validation set
![image](https://user-images.githubusercontent.com/41659296/56093281-596d0b00-5e94-11e9-96ab-18a3943b826b.png)



Program based on Stanford's online Machine Learning Course
