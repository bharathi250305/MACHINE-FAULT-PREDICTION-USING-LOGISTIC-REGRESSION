# Machine Fault Prediction Using Logistic Regression

This project demonstrates how logistic regression can be applied in an industrial automation scenario to predict whether a machine is in a **normal** or **faulty** condition based on **temperature** and **vibration** sensor data.


##  Objective
To build a simple predictive model that can detect potential machine faults using real-time sensor inputs.


##  Features Used
- Temperature (°C)
- Vibration Level (mm/s)

A machine is labeled as **FAULTY** if:
- Temperature > 60°C  OR  
- Vibration > 7 mm/s

Otherwise, it is **NORMAL**.

##  Technologies Used
- Python  
- pandas, numpy  
- scikit-learn (LogisticRegression)  
- matplotlib (optional for visualization)


##  Model Workflow
1. Generate synthetic sensor data.
2. Label data based on fault rules.
3. Train a Logistic Regression model.
4. Evaluate model accuracy.
5. Test real-time predictions from user input.


## 🧩 Example Output
