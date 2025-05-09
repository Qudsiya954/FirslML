🎓 Placement Predictor using Linear Regression
This project predicts student placement outcomes using a Linear Regression model built with Python. It uses a small dataset with two key features: IQ and CGPA.

📌 Features
Predicts placement status (e.g., placed or not placed) based on IQ and CGPA

Achieves an accuracy of 0.8 (80%) on the test data

Dataset contains 100 samples with 2 features and 1 target

Uses scikit-learn for model building and evaluation

🧠 Technologies Used
Python

scikit-learn

Pandas

NumPy

Matplotlib (optional for visualization)
🧪 How to Run
Clone the repository:
```bash
git clone https://github.com/yourusername/placement-predictor.git
cd placement-predictor
```
Install dependencies:
```bash
pip install pandas numpy scikit-learn
```
Run the script:
```bash
python placement_model.py
```

📊 Sample Data Format
| IQ  | CGPA | Placed |
| --- | ---- | ------ |
| 120 | 8.0  | 1      |
| 100 | 6.5  | 0      |
| ... | ...  | ...    |

📈 Model Performance
Accuracy: 80%

Model: Linear Regression

Target: Placement (1 = Placed, 0 = Not Placed)
