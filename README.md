## 📖 Overview
This assignment demonstrates the use of Python libraries—**Pandas**, **Matplotlib**, and **Seaborn**—to analyze and visualize a real-world sales dataset.  
The dataset used is `supermarket_sales.csv`, which contains transactional data from a fictional supermarket across three cities.

## 🛠 Steps Performed
1. **Data Loading** – Read the CSV file and inspected its structure.  
2. **Data Cleaning** – Converted date columns and created a new `Total` column for transaction value.  
3. **Analysis** – Computed summary statistics and average sales per branch and product line.  
4. **Visualization** –  
   - 📈 Line chart showing daily sales trends  
   - 📊 Bar chart comparing average sales across product lines  
   - 📉 Histogram of rating distribution  
   - 🔵 Scatter plot showing relationship between unit price and quantity

## 📊 Key Insights
- Visualized **average total sales by product line** using a bar chart
- Identified top-performing categories such as **Electronics** and **Home & Lifestyle**
- Provided actionable insights for marketing and inventory decisions

## 📌 Key Findings
- **Electronics** and **Home & Lifestyle** had the highest average total sales, indicating strong customer demand and potential for strategic investment.
- **Accessories** and **Sports & Travel** showed lower performance, suggesting areas for promotional campaigns or product repositioning.
- The **variation in sales across categories** highlights opportunities for targeted marketing and inventory optimization.
- Data visualization revealed **clear performance trends**, making it easier to communicate insights to stakeholders.
- The project demonstrates how **data-driven storytelling** can support business strategy and improve operational efficiency.

## 📁 Project Structure
week7/ ├── sales_analysis.ipynb # Main notebook with data analysis and visualization 
       ├── supermarket_sales.csv # Dataset used for analysis 
       └── README.md # Project overview and instructions

  ## ▶️ How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/christinemirimba/python-week7-assignment.git
   cd python-week7-assignment
   
2. **Create a virtual environment (recommended)**
   python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows

3. **Install dependencies**
pip install pandas matplotlib seaborn jupyter

4. **Run the Jupyter Notebook**
jupyter notebook sales_analysis.ipynb

## 🛠 Requirements

Python 

Pandas

Matplotlib

Seaborn

Jupyter Notebook (VS Code)

## 👩‍💻 Author

Christine Kwamboka Mirimba


