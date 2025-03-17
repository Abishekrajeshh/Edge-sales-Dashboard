# 📊 Edge Sales Power BI Dashboard

🚀 **Welcome to EdgeSalesPowerBI!** This repository contains an interactive Power BI dashboard designed to provide deep insights into Edge's sales performance. By leveraging **Python, Snowflake, and Power BI**, this dashboard enables efficient **data visualization** and **analysis** for business decision-making.

🔗 **View the Full Dashboard Here:**  
[Edge Analysis App Power BI Link](https://app.powerbi.com/view?r=eyJrIjoiMjI4N2ZkOTctZGJkYy00MWE0LThmMTQtNGEzMmUyZjllZjgyIiwidCI6IjE3ZjFhODdlLTJhMjUtNGVhYS1iOWRmLTlkNDM5MDM0YjA4MCIsImMiOjF9)

📸 **Dashboard Preview:**  
![Edge Dashboard](Dashboard.png)

---

## 📌 Overview
This **Power BI Sales Dashboard** provides real-time insights into:
- 📈 **Total Sales** - Analyze revenue trends.
- 💰 **Total Profit** - Understand profitability metrics.
- 🎟 **Total Discounts** - Track discount utilization.
- 📦 **Total Quantity Sold** - Monitor sales volume.
- 🌎 **Regional & State-Level Analysis** - Breakdown of sales performance by geography.
- ⏳ **Time Series Analysis** - Sales trends by **year, quarter, month, and day**.
- 🎯 **Segment Performance** - Sales insights by **customer segment and product categories**.

---

## 🔧 Data Pipeline & Architecture
✅ **Python Scripts** - Used for data extraction, transformation, and processing.  
✅ **Snowflake Database** - Serves as the data warehouse for efficient storage and retrieval.  
✅ **Power BI Integration** - Connects to Snowflake to generate interactive reports and dashboards.  

---

## 🛠️ Technology Stack
- **Python** - Data extraction and transformation.  
- **Snowflake** - Cloud-based data storage.  
- **Power BI** - Visualization and reporting.  

---

## 🔽 Installation & Setup
Before running the scripts, ensure the required libraries are installed:
```bash
pip install pandas
pip install snowflake-connector-python
```
📌 **Note:** If using a virtual environment, install dependencies in the correct environment to avoid conflicts.

---

## 🚀 How to Use
1️⃣ **Clone the repository**  
```bash
git clone https://github.com/abishekrajesh/EdgesalesPowerBI.git
```
2️⃣ **Set up your environment** - Ensure Python and required dependencies are installed.  
3️⃣ **Run Python scripts** - Process and upload sales data to Snowflake.  
4️⃣ **Connect Power BI to Snowflake** - Import and visualize relevant data.  
5️⃣ **Explore the dashboard** - Use interactive filters to analyze sales insights.  

---

## ⚠️ Troubleshooting & Considerations
- **Snowflake Credentials:** Ensure your Snowflake account credentials (user, password, account, warehouse, database, schema) are properly configured.
- **Error Handling:** Implement error handling in scripts to manage database connection failures.
- **Data Loading:** Use `pandas.DataFrame.to_sql()` or other efficient methods for uploading data to Snowflake.
- **Dependency Conflicts:** If you encounter installation issues, use:
  ```bash
  pip install -r requirements.txt
  ```

---

## 🤝 Contributing
We welcome contributions to improve the dashboard! Feel free to **fork** the repository, submit **pull requests**, or suggest enhancements.

---

## 📜 License
This project is licensed under the MIT License.  

🔹 **If you find this project useful, don’t forget to ⭐ star the repository!** 🚀
