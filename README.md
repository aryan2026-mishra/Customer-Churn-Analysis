# 📊 Customer Churn Analysis

An exploratory data analysis project focused on understanding customer churn behavior in the telecommunications industry. The project analyzes customer demographics, tenure, subscribed services, contract types, payment methods, and billing information to identify patterns associated with customer churn and generate actionable business insights.

---

## 📌 Project Overview

Customer churn is a major business challenge for subscription-based companies, particularly in the telecommunications industry. Understanding **why customers leave** and identifying the characteristics associated with churn can help businesses improve customer retention and make better data-driven decisions.

This project performs an end-to-end exploratory analysis of customer data to:

* Understand the structure and quality of the dataset
* Clean and prepare the data for analysis
* Explore customer demographics and service usage
* Analyze churn across different customer segments
* Identify patterns related to contracts, services, tenure, and payment methods
* Visualize customer behavior using charts
* Generate business-oriented insights from the analysis

---

## 🎯 Business Problem

A telecommunications company wants to understand customer churn and determine which customer characteristics and services are associated with customers leaving the company.

The analysis focuses on questions such as:

* What percentage of customers are churning?
* Does churn differ between male and female customers?
* How does churn vary by senior-citizen status?
* Which telecom services are commonly used by customers?
* How are customers distributed across different service categories?
* Which payment methods are associated with higher customer churn?
* What customer characteristics should the business monitor for retention strategies?

---

## 📂 Dataset

The dataset contains **7,043 customer records and 21 columns** covering customer demographics, account information, subscribed services, billing details, and the churn outcome.

### Main Features

| Feature            | Description                                               |
| ------------------ | --------------------------------------------------------- |
| `customerID`       | Unique customer identifier                                |
| `gender`           | Customer gender                                           |
| `SeniorCitizen`    | Indicates whether the customer is a senior citizen        |
| `Partner`          | Whether the customer has a partner                        |
| `Dependents`       | Whether the customer has dependents                       |
| `tenure`           | Number of months the customer has stayed with the company |
| `PhoneService`     | Whether the customer has phone service                    |
| `MultipleLines`    | Multiple-line subscription status                         |
| `InternetService`  | Type of internet service                                  |
| `OnlineSecurity`   | Online security subscription                              |
| `OnlineBackup`     | Online backup subscription                                |
| `DeviceProtection` | Device protection subscription                            |
| `TechSupport`      | Technical support subscription                            |
| `StreamingTV`      | Streaming TV subscription                                 |
| `StreamingMovies`  | Streaming movies subscription                             |
| `Contract`         | Customer contract type                                    |
| `PaperlessBilling` | Paperless billing status                                  |
| `PaymentMethod`    | Customer payment method                                   |
| `MonthlyCharges`   | Monthly customer charges                                  |
| `TotalCharges`     | Total charges accumulated by the customer                 |
| `Churn`            | Indicates whether the customer left the company           |

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook** – Analysis environment

---

## 🔄 Project Workflow

### 1. Data Loading

The customer churn dataset was loaded into a Pandas DataFrame for analysis.

### 2. Data Understanding

The dataset structure was examined using:

* `head()`
* `info()`
* `describe()`
* Column inspection
* Data-type analysis

The dataset contains 7,043 records and 21 variables.

### 3. Data Cleaning

The `TotalCharges` column initially contained blank values stored as strings. These values were handled and the column was converted into a numerical data type for analysis.

Additional data-quality checks were performed for:

* Missing values
* Duplicate records
* Data types
* Numerical distributions

The analysis found no remaining null values after the cleaning step and no duplicate records in the dataset.

### 4. Exploratory Data Analysis

Different customer characteristics were analyzed to understand churn patterns.

#### Customer Demographics

Churn was explored across:

* Gender
* Senior-citizen status

#### Customer Services

The project examined customer adoption of services including:

* Phone Service
* Multiple Lines
* Internet Service
* Online Security
* Online Backup
* Device Protection
* Technical Support
* Streaming TV
* Streaming Movies

#### Customer Account Information

The analysis also considers:

* Tenure
* Contract type
* Paperless billing
* Payment method
* Monthly charges
* Total charges

### 5. Data Visualization

Seaborn and Matplotlib were used to create visualizations such as:

* Count plots
* Churn comparison charts
* Percentage-based churn visualizations
* Service distribution plots
* Customer segment comparisons

---

## 📈 Key Analysis Areas

### Customer Demographics

The project compares churn behavior across different demographic groups, including gender and senior-citizen status.

### Telecom Services

The analysis shows the distribution of customers across different telecom services. Phone service and internet service represent major parts of the customer base, while services such as Online Security, Tech Support, Device Protection, and Online Backup have different adoption levels.

### Payment Methods

Payment methods were examined as another potential factor related to churn. The analysis specifically explores customer behavior across payment categories, including electronic check and automatic payment methods.

### Customer Service Adoption

Customers were compared based on the additional services they use. Understanding service adoption can help businesses identify opportunities for customer engagement and retention.

---

## 💡 Business Insights

The analysis provides a foundation for understanding which customer segments and service characteristics should receive greater attention in customer-retention strategies.

Key areas identified for further business investigation include:

* Customer tenure and retention behavior
* Contract type and customer commitment
* Payment method and churn behavior
* Internet service type
* Adoption of additional support and security services
* Differences in churn across demographic groups

These insights can help a business design more targeted customer-retention strategies instead of applying the same approach to every customer.

---

## 📊 Project Deliverables

* Data cleaning and preprocessing
* Dataset quality assessment
* Exploratory data analysis
* Customer segmentation analysis
* Churn-related visualizations
* Telecom service analysis
* Payment-method analysis
* Business insights
* Churn analysis summary report

---

## 📁 Repository Structure

```text
Customer-Churn-Analysis/
│
├── Customer Churn Analysis-Project.ipynb
├── Churn Analysis Summary.pdf
├── vertopal.com_Customer Churn Analysis-Project.pdf
└── README.md
```

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/aryan2026-mishra/Customer-Churn-Analysis.git
```

### 2. Navigate to the project directory

```bash
cd Customer-Churn-Analysis
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Customer Churn Analysis-Project.ipynb
```

and run the notebook cells sequentially.

---

## 🔮 Future Improvements

The current project focuses primarily on exploratory data analysis. Possible future extensions include:

* Building a customer churn prediction model
* Applying Logistic Regression and tree-based classification models
* Comparing model performance using accuracy, precision, recall, and F1-score
* Feature importance analysis
* Customer churn-risk segmentation
* Building an interactive Power BI dashboard
* Developing a Streamlit application for churn prediction
* Creating a retention recommendation system

---

## 👨‍💻 Author

**Aryan Mishra**

B.Tech – Computer Science and Engineering

[LinkedIn](https://www.linkedin.com/in/aryan-mishra-61561b298/)
[GitHub](https://github.com/aryan2026-mishra)

---

## ⭐ Project

If you find this project useful, feel free to explore the repository and connect with me on LinkedIn.
