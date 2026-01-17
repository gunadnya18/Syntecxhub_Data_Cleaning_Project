# Syntecxhub Data Cleaning Project

## 📌 Project Overview
This project is part of my internship task at **Syntecxhub**.  
The objective was to perform **end-to-end data cleaning and exploratory analysis** on a customer dataset.

I used Python libraries such as **Pandas, Matplotlib, and Seaborn** to:
- Detect & handle missing values  
- Remove duplicates  
- Fix incorrect data types  
- Impute missing data  
- Visualize distributions & outliers  
- Prepare a clean dataset for further analysis  

---

## 📁 Repository Structure
```
Syntecxhub_Data_Cleaning_Project/
│── data/
│   └── cleaned_data.csv
│── notebook/
│   └── Data_Cleaning.ipynb
│── images/
│   └── boxplots, histograms, etc.
│── README.md
```

---

## 🛠️ Tools & Technologies Used
- Python  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- GitHub  

---

## 📊 Key Steps Performed

### 1️⃣ Data Loading  
- Loaded dataset into Pandas DataFrame  
- Checked dataset shape and datatype summary  

### 2️⃣ Data Cleaning  
✔ Removed duplicate rows  
✔ Corrected data types (Age, Dates, Amount etc.)  
✔ Handled missing values:  
   - Numerical → Median  
   - Categorical → Mode / “Unknown”  
✔ Imputed invalid entries (like “—”, “N/A”, blank spaces)  
✔ Fixed date columns using `pd.to_datetime()`  

### 3️⃣ Exploratory Data Analysis  
- Distribution plots  
- Boxplots  
- Missing value analysis  
- Outlier detection  
- Data summary statistics  

---

## 📈 Visualizations
Some of the visualizations included:  
- Boxplots for Age, Purchase Amount, Feedback Score  
- Histograms for numeric features  
- Countplots for categorical features  

(All images are stored in the **images/** folder.)

---

## 🧼 Final Clean Dataset
The final cleaned dataset is saved here:

➡ `data/cleaned_data.csv`

---

## 🚀 How to Run This Project

### **1. Clone the repository**
```bash
git clone https://github.com/YourUsername/Syntecxhub_Data_Cleaning_Project.git
```

### **2. Install dependencies**
```bash
pip install pandas matplotlib seaborn numpy
```

### **3. Open Jupyter Notebook**
```bash
jupyter notebook
```

### **4. Run the notebook**
Open:  
`notebook/Data_Cleaning.ipynb`

---

## ✨ Internship Information
This project is part of my ongoing internship with **Syntecxhub**, where interns complete weekly tasks to build hands-on data skills.  
Thank you Syntecxhub for the learning opportunity! 🙌

---

## 📬 Contact
If you'd like to connect or collaborate:  
**LinkedIn:** linkedin.com/in/gunadnya-joshi-9702582a2
