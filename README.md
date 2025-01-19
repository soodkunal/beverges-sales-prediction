# 📊 Beverage Sales Analysis

Analyze regional preferences, seasonal trends, and pricing strategies in the beverage industry using a versatile dataset. This repository provides tools and insights for exploring Business-to-Business (B2B) and Business-to-Consumer (B2C) sales patterns, customer segmentation, and pricing dynamics.

---

## 🚀 Features

- **Regional Preferences**: Uncover trends based on geographic regions.  
- **Seasonal Analysis**: Explore how seasons affect beverage sales.  
- **Pricing Strategies**: Analyze pricing and discounts to maximize revenue.  
- **Customer Segmentation**: Predict whether a customer is B2B or B2C.  
- **Predictive Modeling**: Forecast beverage pricing and optimize sales strategies.  

---

## 📂 Dataset Overview

This project uses the [Beverage Sales Dataset](https://www.kaggle.com/datasets/sebastianwillmann/beverage-sales/data), available for download [here](https://drive.google.com/file/d/1LCroYoIqObck-SCWcstuhEz358tU2qQy/view?usp=sharing). It highlights key factors in the beverage industry, including customer, product categories, and order details. However for this project we used local path you can replace it with your link to the data if fetching from [here](https://drive.google.com/file/d/1LCroYoIqObck-SCWcstuhEz358tU2qQy/view?usp=sharing)

### Dataset Columns  
| Column          | Description                                                                 |  
|------------------|-----------------------------------------------------------------------------|  
| **Order_ID**     | Unique identifier for each order. Groups multiple products within the same order. |  
| **Customer_ID**  | Unique identifier for each customer, distinguishing individual buyers.      |  
| **Customer_Type**| Indicates whether the customer is B2B or B2C.                              |  
| **Product**      | Name of the purchased product (e.g., "Coca-Cola", "Erdinger Weißbier").     |  
| **Category**     | Product category (e.g., "Soft Drinks", "Alcoholic Beverages").             |  
| **Unit_Price**   | Price per unit of the product.                                             |  
| **Quantity**     | Number of units purchased.                                                |  
| **Discount**     | Discount applied to the product (only for B2B customers).                 |  
| **Total_Price**  | Total price after applying discounts.                                      |  
| **Region**       | Geographic region of the customer (e.g., "Bayern", "Berlin").             |  
| **Order_Date**   | Date when the order was placed.                                           |  

---

## 🎯 Goals  

1. **Customer Type Prediction**  
   Build models to predict whether a customer is B2B or B2C based on their purchase behavior.  

2. **Price Prediction**  
   Use data features like product, quantity, and region to forecast the pricing of beverages.  

---

## 🛠️ Implementation  

We explored various machine learning models to achieve the goals and selected the best-performing models for each task. However, there is still room for improvement in model performance through advanced techniques or additional data preprocessing.  

### Models Used  

- Logistic Regression  
- Decision Trees  
- Random Forests  
- Gradient Boosting Machines  
- Neural Networks (for advanced tasks)  

---

## 🛠️ How to Use  

### Prerequisites  
1. Python 3.7+  
2. Install required libraries:  
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

### Running the Notebook  
1. Clone the repository:  
   ```bash
   git clone https://github.com/soodkunal/beverges-sales-prediction.git
   ```  
2. Navigate to the project directory:  
   ```bash
   cd beverges-sales-prediction
   ```  
3. Open the Jupyter notebook:  
   ```bash
   beverage-sales-prediction.ipynb
   ```  

---

## 📈 Example Visualizations  

- **Sales Trends by Region**: Identify top-performing regions for specific beverages.  
- **Seasonal Demand**: Visualize how sales vary across different seasons.  
- **Discount Impact**: Understand how discounts affect purchasing behavior for B2B customers.  

---

## 💡 Contribution  

Feedback, questions, and suggestions are always welcome! Feel free to open an issue or submit a pull request to help improve this project.  

---

## 📝 License  

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.  

---

Happy Analyzing! 🍹  
