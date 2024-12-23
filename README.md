## **1. Introduction**
This report provides an analysis of the most-ordered dishes and the age distribution of users based on the dataset. The analysis aims to uncover trends in customer preferences, age demographics, and provide actionable business recommendations for optimizing the menu and marketing strategies.

---

## **2. Methodology**
- **Data Collection**: The dataset includes information on user sessions, orders, dish names, meal types, user ages, and ratings.
- **Tools Used**: 
  - **Python** for data analysis and visualization (Pandas, Seaborn, Matplotlib).
  - **Jupyter Notebooks** for data analysis and generating insights.
- **Techniques**: Descriptive statistics and visualizations were used to identify the most-ordered dishes and analyze the age distribution of users.

---

## **3. Findings**

### **3.1 Top 10 Most-Ordered Dishes**

The analysis of the dataset revealed the top 6 most-ordered dishes:

| Dish Name      | Order Count |
|----------------|-------------|
| Spaghetti      | 4           |
| Grilled Chicken| 4           |
| Caesar Salad   | 3           |
| Pancakes       | 2           |
| Veggie Burger  | 2           |
| Oatmeal        | 1           |

- **Spaghetti** and **Grilled Chicken** are the most popular dishes, with 4 orders each.
- **Caesar Salad** follows with 3 orders.
- **Pancakes** and **Veggie Burger** each received 2 orders.
- **Oatmeal** had the least number of orders with only 1.

### **3.2 Age Distribution**

The age distribution of users was analyzed, and the following descriptive statistics were calculated:

- **Average Age**: 32.7 years
- **Age Range**: 25 to 42 years
- **Standard Deviation**: 5.8 years (indicating moderate variability in ages)
- **25th Percentile**: 28 years
- **Median (50th Percentile)**: 30.5 years
- **75th Percentile**: 35.75 years

The **age distribution** histogram reveals that most users are between 25 and 42 years old, with a relatively even spread across this range.
---

## **4. Business Recommendations**

### **4.1 Promote Popular Dishes**
- **Spaghetti** and **Grilled Chicken** should be prominently featured on the menu, marketed as **"Customer Favorites"** or **"Chef's Specials"**.
- **Actionable Steps**:
  - Offer discounts or combo deals featuring these dishes.
  - Use social media to highlight customer reviews of these popular dishes.

### **4.2 Offer Customization for Popular Dishes**
- Allow customers to **customize** dishes like **Spaghetti** and **Grilled Chicken** by offering different sauces, toppings, or sides.
- **Actionable Steps**:
  - Introduce seasonal variations (e.g., different sauces or sides).
  - Provide options for upselling premium versions (e.g., gourmet toppings).

### **4.3 Revamp Low-Ordered Dishes (Oatmeal)**
- **Oatmeal** had the least orders. It’s essential to understand the reasons for its low popularity.
- **Actionable Steps**:
  - Investigate customer feedback to determine why oatmeal is less popular.
  - Offer promotions or bundle oatmeal with other dishes to increase its appeal.

### **4.4 Seasonal and Themed Menu Items**
- Dishes like **Pancakes** and **Veggie Burger** could be more popular during specific seasons or events.
- **Actionable Steps**:
  - Offer **seasonal pancakes** (e.g., pumpkin pancakes in fall).
  - Introduce limited-time offers or **holiday-themed dishes** to attract more customers.

### **4.5 Customer Segmentation and Targeted Marketing**
- Use the popularity of dishes to segment your customer base and target specific groups.
- **Actionable Steps**:
  - Offer **loyalty programs** for frequent customers of popular dishes.
  - Target health-conscious customers with dishes like **Veggie Burger** or **Caesar Salad**.

### **4.6 Menu Optimization**
- Regularly analyze the sales of dishes and adjust the menu based on performance data.
- **Actionable Steps**:
  - Remove or replace consistently low-selling dishes.
  - Use **dynamic pricing** for popular dishes based on demand.

### **4.7 Cross-Sell and Upsell Opportunities**
- **Spaghetti** and **Grilled Chicken** are excellent candidates for cross-selling and upselling.
- **Actionable Steps**:
  - Suggest side dishes or desserts when customers order popular dishes.
  - Offer **combo deals** that include these dishes with drinks or appetizers.

---

## **5. Conclusion**
The analysis of the top 10 most-ordered dishes and the age distribution of users provides valuable insights into customer preferences. By promoting popular dishes, revamping low-demand items, and optimizing the menu based on customer data, businesses can improve sales and customer satisfaction. These strategies will help businesses stay competitive and align their offerings with customer expectations.

---

## **GitHub Repository Structure**

To organize this project in a GitHub repository, the following structure is recommended:

```
Top-10-Most-Ordered-Dishes-Analysis/
│
├── data/                       # Folder to store dataset(s)
│   └── dataset.csv             # Raw dataset
│
├── notebooks/                  # Folder for Jupyter notebooks
│   └── analysis.ipynb          # Jupyter notebook with data analysis and visualizations
│
├── images/                     # Folder for images (e.g., charts, plots)
│   └── top_dishes_chart.png    # Chart image for the report
│   └── age_distribution.png    # Age distribution chart image
│
├── README.md                   # Project description and instructions
└── requirements.txt            # List of dependencies
```

### **README.md Example**
# Top 10 Most-Ordered Dishes Analysis

This project analyzes the most-ordered dishes based on user session and order data, as well as the age distribution of users. The goal is to provide insights into customer preferences and offer business recommendations to optimize menu offerings and marketing strategies.

## Project Structure

- `data/`: Contains the raw dataset used for analysis.
- `notebooks/`: Jupyter notebook with data analysis and visualizations.

## Setup

1. Clone the repository:
   ```
   git clone https://github.com/syedzameer18/Top-10-Most-Ordered-Dishes-Analysis.git
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Running the Analysis

1. Open the Jupyter notebook `analysis.ipynb` to view the data analysis and visualizations.
2. Generate the report by running the code in the notebook.

## License

This project is licensed under the MIT License.
```

### **requirements.txt**

```txt
pandas
seaborn
matplotlib
jupyter
```
