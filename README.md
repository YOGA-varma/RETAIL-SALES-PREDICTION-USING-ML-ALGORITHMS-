# RETAIL-SALES-PREDICTION-USING-ML-ALGORITHMS-
This project focuses on building a Retail Sales Forecasting Web Application using Python, Streamlit, PostgreSQL, and Plotly. It allows users to visualize, compare, and predict retail sales based on historical data and input features such as fuel price, markdowns, temperature, and more.

 Project Overview
Retail businesses face challenges in understanding and forecasting sales due to various influencing factors. This application helps stakeholders to:

Explore and analyze historical sales data.

Compare sales trends across different time periods, stores, and departments.

Forecast weekly sales using a trained machine learning model.

 Features
 Interactive Dashboard: Visualize sales trends using bar charts, pie charts, and scatter plots.

 Top Stores/Departments: View the top-performing stores or departments based on sales for selected dates.

 Comparative Analysis:

Compare previous week vs current week.

Compare user-selected store with top/bottom 10 stores.

Manual comparison between any two store-department combinations.

 Sales Prediction: Predict weekly sales for a specific store and department using a regression model.

 SQL Integration: Backend database interaction via PostgreSQL for data migration and querying.

 Tech Stack
Frontend: Streamlit (for building UI)

Backend: Python, PostgreSQL

Visualization: Plotly, Streamlit Extras

Modeling: Scikit-learn (Pickle model used)

Libraries: pandas, numpy, psycopg2, warnings, streamlit-option-menu

 Folder Structure
bash
Copy
Edit
 Retail Sales Forecast
├── model/
│   └── model1_markdown.pkl  
├── df_sql.csv                
├── RETAIL SALES PREDICTION CODE.py 
├── Retail_Sales_Forecast PROJECT.ipynb  
 How to Run the App
Ensure you have PostgreSQL installed and create a database named retail_forecast.

Clone this repo and install the required Python packages.

Run the app:

bash
Copy
Edit
streamlit run "RETAIL SALES PREDICTION CODE.py"
Use the sidebar to explore features, visualize trends, and make predictions.

 Future Enhancements
Integrate user authentication for secure access.

Add support for uploading custom sales data.

Enable saving and exporting visual reports.

Incorporate time series models (e.g., ARIMA, LSTM) for better accuracy.
