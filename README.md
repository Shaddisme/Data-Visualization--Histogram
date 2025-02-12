# 📊 Data Visualization with SQL and Python  

### **Overview**  
This project focuses on **data visualization** using **SQL queries, Pandas, and Matplotlib**. The dataset is stored in an **SQLite database**, and SQL queries are used to extract relevant information for analysis. The main objective is to explore the **distribution, relationships, composition, and comparisons** of various features using histograms.  

### **Tech Stack**  
- **Python** (Pandas, Matplotlib, SQLite3)  
- **SQL** (Querying and Data Extraction)  
- **Jupyter Notebook**  

---

## 📌 **Project Objectives**  
✅ **Visualizing Data Distribution**  
- Histogram of **Total Compensation (`CompTotal`)**  
- Histogram of **Years of Professional Coding Experience (`YearsCodePro`)**  

✅ **Exploring Relationships Between Features**  
- Comparing **Compensation by Age Group**  
- Histogram of **Time Searching for Information** by Age  

✅ **Understanding Data Composition**  
- Histogram of **Most Desired Databases (`DatabaseWantToWorkWith`)**  
- Histogram of **Preferred Work Locations (`RemoteWork`)**  

✅ **Comparing Different Data Groups**  
- Histogram of **Median Compensation (`CompTotal`) for Ages 45-60**  
- Histogram of **Job Satisfaction (`JobSat`) by Years of Coding Experience (`YearsCodePro`)**  

---

## 🚀 **Project Workflow**  
### **1️⃣ Setup & Database Connection**  
- Download the SQLite database file  
- Install required Python libraries (`pandas`, `matplotlib`, `sqlite3`)  
- Connect to the database and inspect table structure  

### **2️⃣ Data Extraction with SQL**  
- Use SQL queries to filter and retrieve necessary data  
- Convert SQL query results into Pandas DataFrames  

### **3️⃣ Data Visualization with Matplotlib**  
- Generate **histograms** to visualize the dataset  
- Customize **plots** (labels, legends, scales) for better insights  

---

## 📂 **Project Structure**  
```
📁 Data-Visualization-SQL-Python
│── 📜 README.md  
│── 📜 data-exploration.ipynb  # Jupyter Notebook with SQL queries and visualizations  
│── 📜 survey-data.sqlite  # SQLite database (not included in the repo)  
│── 📜 requirements.txt  # List of dependencies (Pandas, Matplotlib, SQLite3)  
```

---

## 🔧 **How to Run the Project**  
### **1️⃣ Install Dependencies**  
```bash
pip install pandas matplotlib sqlite3
```
### **2️⃣ Run the Jupyter Notebook**  
```bash
jupyter notebook data-exploration.ipynb
```
### **3️⃣ Follow the Notebook Instructions**  
- Load the dataset  
- Run SQL queries to extract data  
- Generate and analyze visualizations  

---

## 📊 **Sample Outputs**  
Below are some sample histogram visualizations from the project:  

🔹 **Total Compensation Distribution**  
🔹 **Years of Coding Experience**  
🔹 **Compensation vs Age Group**  
🔹 **Preferred Work Locations**  

(Insert images of your histograms here if possible 📌)  

---

## 🤝 **Contributing**  
Feel free to fork this repository and suggest improvements! 🚀  

---

## 🏷 **License**  
This project is open-source under the **MIT License**.  

