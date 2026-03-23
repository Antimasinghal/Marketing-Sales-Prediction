📊 Machine Learning to Predict Marketing Sales

📌 Project Overview
This project is all about prediction of sales using machine learning techniques as well as studying what are the factors which affects sales performance. The aim is not just the build a predictive model but also to generate valuable business insights from the dataset.

🎯 Objective
- Predict sales using historical data
- Identify important features affecting sales
- Provide data-driven business recommendations

📂 Dataset Description
- The dataset has information about the products and outlets, which includes:
- Item_MRP (price of the product)
- Item_Visibility (how discoverable the product is in store)
- Outlet_Type (type of store)
- Outlet_Establishment_Year
- Other categorical and numerical features
- Target Variable:
- Item_Outlet_Sales

⚙️ Technologies Used
- Python 🐍
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- XGBoost

🧠 Feature Engineering
# To enhance the model performance, new features were created:
- Outlet_Age = Year of Corpus Base – Year of Construction
- Visibility_MRP = Item_Visibility × Item_MRP
- These characteristics are aimed at mimicking relationships that exist in the real world.

🤖 Models Used
- Linear Regression
- XGBoost Regressor

# Models were evaluated using:
- R² Score
- RMSE

📊 Key Insights
- Outlet type has the highest impact on sales, especially grocery stores
-I tem price (MRP) significantly influences revenue
- Store age plays an important role in sales performance
- Product visibility combined with pricing affects sales behavior

💡 Business Recommendations
- Focus on optimizing store formats (grocery vs supermarket)
- Implement effective pricing strategies
- Leverage older outlets for stable sales performance
- Improve product visibility to boost sales

📈 Future Improvements
- Add more advanced models (e.g., Random Forest, LightGBM)
- Include marketing data for deeper analysis
- Build an interactive dashboard (Power BI / Tableau)

🚀 Conclusion
This project demonstrates how machine learning can be used not only for prediction but also for generating actionable business insights. It highlights the importance of feature engineering and interpretability in real-world applications.
