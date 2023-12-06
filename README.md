# Predict Ethereum price using Neural Network

## Predicting Future Ethereum Prices with LSTM

Predicting future Ethereum prices with LSTM.

Latest: improved_prediction.ipynb

### Model Improvement (as of 2023-12-05)

The improved model now yields impressive results:

- Mean Absolute Error (MAE): 0.005368011520480294
- Mean Squared Error (MSE): 4.905895251991975e-05
- R-squared Score (R2): 0.9849546694121026
![Alt Text](https://github.com/BarriWen/deep_learning_cryptocurrency_prediction/blob/main/improved%20output.png)

These metrics demonstrate the accuracy and effectiveness of our neural network model in predicting Ethereum prices.

Stay tuned for further updates and enhancements to our Ethereum price prediction model.

## Setting up the Development Environment

To run this project, you will need Python 3.9 and access to a terminal. Follow these steps to set up your development environment:

1. **Create a Virtual Environment**:
   - Navigate to the project's root directory in your terminal.
   - Create a virtual environment using Python 3.9 with the command:
     ```
     python3.9 -m venv .venv
     ```

2. **Activate the Virtual Environment**:
   - Activate the virtual environment. The activation command differs depending on your operating system.
     - On macOS and Linux:
       ```
       source .venv/bin/activate
       ```
     - On Windows:
       ```
       .venv\Scripts\activate
       ```

3. **Install Required Packages**:
   - Install the project's dependencies by running:
     ```
     pip install -r requirements.txt
     ```

After following these steps, your development environment should be ready, and you can run the project's code.
