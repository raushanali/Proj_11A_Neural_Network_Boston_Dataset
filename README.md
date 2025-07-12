# Proj_11A_Neural_Network_Boston_Dataset

## Project Introduction
This project is based on the Boston Housing Dataset and builds a neural network model to predict house prices. The dataset contains records of various features of houses and their prices in the Boston, MA area.

## Purpose
The purpose of this project is to use the given data to predict the price (MEDV) of a house. It uses 11 features, such as crime rate, zoning, nitric oxide levels, number of rooms, tax rate, etc.

## Main Features
- **Data Processing**: Data is prepared using scaling and train-test split.
- **Model Architecture**: A Sequential Neural Network is built with 3 hidden layers (128, 64, 32 neurons) using relu activation.
- **Model Training**: The model is trained for 150 epochs with a batch size of 10.
- **Evaluation**: Model performance is checked using Mean Squared Error (MSE) and R2 Score.
- **Visualization**: Training loss is visualized using Matplotlib.

## How to Use

 **Install Required Libraries**  
   Make sure the following libraries are installed on your system:
   ```
   pip install keras tensorflow scikit-learn pandas matplotlib
   ```

 **Place the Data File**  
   Keep the `BostonHousing.csv` file in the same folder as the code.

 **See the Output**  
   - Test set MSE and R2 score will be printed on the console.
   - Training loss graph will be displayed.
