Power Transformer
📌 Overview

This project demonstrates the use of Power Transformation in Machine Learning to transform skewed numerical features and make their distribution more suitable for machine learning algorithms.

Power transformations can help reduce skewness and stabilize variance, which can improve the performance of certain ML models.

🎯 Objectives
Understand why feature transformation is required.
Analyze skewed numerical features.
Apply Power Transformation to the data.
Compare the feature distributions before and after transformation.
Understand the effect of transformation on machine learning models.
🛠️ Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
🔑 Key Concepts
Feature Transformation
Skewness
Normal Distribution
Box-Cox Transformation
Yeo-Johnson Transformation
Data Preprocessing
📂 Project Structure
Power-transform-/
│
├── power_transform.ipynb
├── README.md
└── dataset/
🚀 How to Run

Clone the repository:

git clone https://github.com/Prabhat325/Power-transform-.git

Navigate to the project:

cd Power-transform-

Install the required libraries:

pip install numpy pandas matplotlib seaborn scikit-learn jupyter

Start Jupyter Notebook:

jupyter notebook

Open the notebook and run the cells.

📊 Transformation Methods
Box-Cox Transformation

Box-Cox is generally used when the data contains positive values only.

Yeo-Johnson Transformation

Yeo-Johnson can handle both positive and negative values, making it more flexible than Box-Cox.

📚 Learning Source

This project was implemented as part of my 100 Days of Machine Learning learning journey, based on concepts covered in the CampusX ML course.

👨‍💻 Author

Prabhat Dubey

GitHub: Prabhat325
