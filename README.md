# Graduate-Admission-Prediction

🔍 Context:
This project is designed to predict Graduate Admissions from an Indian perspective, utilizing essential parameters considered during Masters Programs applications.

📊 Key Parameters in the Dataset:
- GRE Scores (out of 340)
- TOEFL Scores (out of 120)
- University Rating (out of 5)
- Statement of Purpose and Letter of Recommendation Strength (out of 5)
- Undergraduate GPA (out of 10)
- Research Experience (either 0 or 1)
- Chance of Admit (ranging from 0 to 1)

🛠 Tools and Techniques:
- Python (Pandas, NumPy)
- Scikit-Learn (train_test_split, Min-Max Scaling)
- Neural Network using Keras Sequential Model
- Loss Function: Mean Squared Error
- Optimizer: Adam

📈 Data Preprocessing:
- Cleaned the dataset (no duplicates)
- Dropped irrelevant columns (Serial No.)
- Split data into features (X) and target (y)
- Recognized the problem as regression (predicting probability scores for admission)

🔄 Data Splitting:
- Utilized train_test_split to divide data into training and testing sets

⚙️ Model Building:
- Constructed a neural network with one hidden layer initially
- Improved model performance by adding a second hidden layer
- Used "linear" activation for output in this regression problem

📉 Model Evaluation:
- Implemented Mean Squared Error as the loss function
- Optimized using the Adam optimizer
- Monitored and visualized training and validation loss for improvements
