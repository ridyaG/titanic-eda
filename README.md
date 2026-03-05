# Titanic Exploratory Data Analysis (EDA)

## 📌 Objective

The objective of this project is to perform **Exploratory Data Analysis (EDA)** on the Titanic dataset to understand patterns, trends, and factors that influenced passenger survival.

This project analyzes the dataset using Python and visualization libraries to discover meaningful insights.

---

## 🛠️ Tools & Libraries Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook / VS Code
* Git & GitHub

---

## 📂 Dataset

The dataset contains information about Titanic passengers such as:

* Passenger class
* Gender
* Age
* Ticket fare
* Survival status

File used: **titanic.csv**

---

## 📊 Visualizations Created

### 1. Survival Count

Shows the number of passengers who survived versus those who did not.

### 2. Survival by Gender

Displays survival distribution between male and female passengers.

### 3. Survival by Passenger Class

Shows how survival rates differ across passenger classes (1st, 2nd, 3rd).

### 4. Age Distribution

Visualizes the distribution of passenger ages.

### 5. Fare Distribution

Shows how ticket fares are distributed among passengers.

All generated plots are stored in the **plots/** folder.

---

## 🔍 Key Findings

* Female passengers had a significantly higher survival rate compared to male passengers.
* Passengers in **1st class** had a much higher survival probability than those in 2nd or 3rd class.
* **3rd class passengers formed the majority** of the dataset but had the lowest survival rate.
* Younger passengers had slightly better survival chances than older passengers.
* Higher ticket fares were generally associated with higher survival probability.

---

## 📁 Project Structure

titanic-eda
│
├── eda_titanic.py
├── titanic.csv
├── README.md
└── plots/
  ├── survival_count.png
  ├── survival_by_gender.png
  ├── survival_by_class.png
  ├── age_distribution.png
  └── fare_distribution.png

---

## ▶️ How to Run the Project

### 1. Clone the Repository

git clone https://github.com/YOUR_USERNAME/titanic-eda.git

### 2. Navigate to the Project Folder

cd titanic-eda

### 3. Install Required Libraries

pip install pandas matplotlib seaborn

### 4. Run the Python Script

python eda_titanic.py

After running the script, the visualizations will be generated and saved inside the **plots/** folder.

---

## ✅ Conclusion

Exploratory Data Analysis helped uncover key patterns in the Titanic dataset. Factors such as **gender, passenger class, and fare** had a significant influence on survival outcomes.

This project demonstrates how data visualization and analysis can provide valuable insights from real-world datasets.
