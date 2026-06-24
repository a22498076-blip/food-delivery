# 🍔 Food Delivery Data Analysis

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a Food Delivery Dataset containing 20,000 customer orders. The goal is to uncover valuable business insights related to customer preferences, delivery performance, order trends, and customer satisfaction.

Using Python, Pandas, and Matplotlib, the project analyzes order data and visualizes key metrics that can support business decision-making.

---

## 📊 Dataset Information

The dataset contains **20,000 food delivery records** with **31 features**, including:

- Order details
- Customer information
- Delivery information
- Food quality metrics
- Customer satisfaction ratings

### Key Features

| Feature | Description |
|----------|-------------|
| order_id | Unique order ID |
| restaurant_id | Restaurant identifier |
| food_item | Ordered food item |
| order_value | Total order amount |
| delivery_distance | Delivery distance |
| delivery_method | Walk, Bike, or Car |
| traffic_condition | Traffic status |
| weather_condition | Weather during delivery |
| customer_satisfaction | Satisfaction rating (1–5) |
| location | Customer city |
| route_efficiency | Route efficiency score |

---

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/food-delivery-analysis.git
cd food-delivery-analysis
```

Install required libraries:

```bash
pip install pandas matplotlib
```

---

## 🚀 Project Workflow

### 1. Load Dataset

```python
import pandas as pd

df = pd.read_csv("food_delivery_dataset.csv")
```

### 2. Data Exploration

```python
df.head()
df.info()
df.isnull().sum()
```

### 3. Analysis Performed

✔ Total Orders Analysis

✔ Popular Food Items Analysis

✔ Location-wise Order Analysis

✔ Order Value Distribution

✔ Delivery Method Analysis

✔ Customer Satisfaction Analysis

✔ Data Visualization

---

## 📈 Results

### Top 10 Most Ordered Food Items

| Food Item | Orders |
|------------|---------|
| Pasta | 1884 |
| Whole cake | 958 |
| Soup | 948 |
| Cup cake | 944 |
| Beef pie | 934 |

---

### Top Ordering Locations

| Location | Orders |
|-----------|---------|
| Ahmedabad | 2051 |
| Kolkata | 2032 |
| Delhi | 2027 |
| Pune | 2026 |
| Jaipur | 2013 |

---

### Average Order Value

```text
27.34
```

---

### Delivery Methods

| Method | Orders |
|----------|---------|
| Walk | 6830 |
| Bike | 6598 |
| Car | 6572 |

---

### Average Customer Satisfaction

```text
2.98 / 5
```

---

## 📊 Visualizations

The project includes the following visualizations:

- Bar Chart of Top 10 Food Items
- Pie Chart of Top Locations
- Histogram of Order Values
- Delivery Method Distribution
- Customer Satisfaction Ratings

---

## 💡 Business Insights

### 1. Popular Food Trends
- Pasta is the most ordered food item.
- Bakery products and fast-food items are highly popular.

### 2. High Demand Cities
- Ahmedabad, Kolkata, and Delhi generate the highest number of orders.

### 3. Customer Spending
- Average order value is approximately 27.34.
- Spending patterns are evenly distributed.

### 4. Delivery Operations
- Walk deliveries slightly exceed Bike and Car deliveries.
- Delivery methods are relatively balanced.

### 5. Customer Satisfaction
- Average satisfaction score is 2.98/5.
- Service quality improvements may increase customer retention.

---

## 🔮 Future Improvements

- Delivery Delay Analysis
- Traffic Impact Analysis
- Weather Impact Analysis
- Customer Segmentation
- Revenue Analysis
- Predictive Analytics
- Route Optimization
- Customer Satisfaction Prediction

---

## 📂 Project Structure

```text
Food-Delivery-Analysis/
│
├── food_delivery_dataset.csv
├── food_delivery_analysis.ipynb
├── README.md
└── images/
    ├── top_food_items.png
    ├── location_distribution.png
    ├── order_value_distribution.png
    ├── delivery_methods.png
    └── customer_satisfaction.png
```

---

## 📷 Sample Output

The analysis generates visual insights that help understand:

- Customer ordering behavior
- Food popularity
- Delivery preferences
- Location-based demand
- Customer satisfaction patterns

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

Feel free to fork the repository and submit a pull request.

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

## 👨‍💻 Author

Developed as a Data Analysis project using Python, Pandas, and Matplotlib.
