# Automated Data Cleaning and Visualization Pipeline

## 📌 Project Overview
This project is designed to automate the cleaning and analysis of raw business datasets. Using Python, it streamlines the process of identifying data inconsistencies, handling missing values, and generating visual reports. This ensures that data is "analysis-ready" without manual intervention.

## 🛠 Tech Stack
* **Language:** Python
* **Libraries:** 
    * **Pandas:** For data manipulation and cleaning.
    * **Seaborn & Matplotlib:** For creating high-resolution data visualizations.
    * **NumPy:** For handling numerical operations and null values.
* **Platform:** Google Colab / Jupyter Notebook

## 🚀 Automation Features
The pipeline performs the following tasks automatically:
1. **Data Ingestion:** Reads raw data from CSV files.
2. **Preprocessing & Cleaning:**
   - **Duplicate Removal:** Identifies and deletes redundant rows to prevent skewed results.
   - **Handling Missing Values:** Automatically fills missing 'Sales' entries using the mean (average) of the column.
3. **Exploratory Data Analysis (EDA):**
   - Generates a **Bar Chart** to compare total revenue across different categories.
   - Generates a **Histogram (with KDE)** to show the distribution and density of sales.
4. **Professional Export:** Exports the final, cleaned dataset into a professional Excel (.xlsx) format for easy sharing.

## 📁 Repository Structure
* `Automation_Project.ipynb`: The main notebook containing the Python code and generated charts.
* `data.csv`: The sample raw dataset used for testing the automation.
* `README.md`: Project documentation.

## 💻 How to Run
1. Open the `.ipynb` file in **Google Colab**.
2. Upload your `data.csv` when prompted by the script.
3. The code will execute, display the visual reports, and automatically trigger a download for the cleaned Excel file.

---
**Developed by a Computer Science student focused on Software Development and Algorithmic Analysis.**
