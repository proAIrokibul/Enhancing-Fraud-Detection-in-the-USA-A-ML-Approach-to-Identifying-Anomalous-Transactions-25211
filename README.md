# Enhancing-Fraud-Detection-in-the-USA-A-ML-Approach-to-Identifying-Anomalous-Transactions-25211
## **Project Overview**
Fraudulent transactions can lead to significant financial losses, reputational damage, and erosion of trust for businesses, particularly in the financial sector. This project leverages advanced machine learning techniques to improve fraud detection systems by accurately identifying anomalous transactions. The dataset contains key features such as customer profession, income, credit card details, security codes, and fraud labels, which are preprocessed, analyzed, and modeled to deliver actionable insights.

---

## **Business Impact**
- **Cost Savings**: Early detection of fraudulent transactions minimizes financial losses for banks, credit card providers, and other financial institutions.
- **Enhanced Trust**: By implementing effective fraud detection systems, businesses can build stronger relationships with customers by ensuring their financial data remains secure.
- **Operational Efficiency**: Automating fraud detection using machine learning reduces manual intervention, improving efficiency and allowing fraud detection teams to focus on high-priority cases.
- **Scalability**: Machine learning models can process large volumes of transactions, making them scalable for enterprises handling millions of daily transactions.

---

## **Key Features**

### **1. Data Preprocessing**
- Categorical variables like `Profession` are encoded using Label Encoding for compatibility with machine learning algorithms.
- Numerical features (`Income` and `Security_code`) are standardized using StandardScaler to ensure uniform scaling across all features.
- A new feature, `Income Group`, is engineered to segment income levels into meaningful categories, enhancing interpretability and feature richness.

### **2. Modeling**
Developed and evaluated three robust classification models:
- **Logistic Regression**: A simple and interpretable baseline model.
- **Random Forest Classifier**: A tree-based ensemble model for high accuracy and feature importance insights.
- **Support Vector Machine (SVM)**: A powerful algorithm for handling complex, non-linear decision boundaries.

### **3. Performance Results**

#### **Logistic Regression**
- **Accuracy Score**: `0.4895`
- **Classification Report**:
  | Metric       | Class 0 | Class 1 |
  |--------------|---------|---------|
  | **Precision** | 0.48    | 0.49    |
  | **Recall**    | 0.30    | 0.68    |
  | **F1-Score**  | 0.37    | 0.57    |

#### **Random Forest**
- **Accuracy Score**: `0.4935`
- **Classification Report**:
  | Metric       | Class 0 | Class 1 |
  |--------------|---------|---------|
  | **Precision** | 0.49    | 0.49    |
  | **Recall**    | 0.50    | 0.49    |
  | **F1-Score**  | 0.50    | 0.49    |

#### **SVM**
- **Accuracy Score**: `0.502`
- **Classification Report**:
  | Metric       | Class 0 | Class 1 |
  |--------------|---------|---------|
  | **Precision** | 0.50    | 0.50    |
  | **Recall**    | 0.43    | 0.57    |
  | **F1-Score**  | 0.46    | 0.54    |

### **4. Model Comparison and Visualization**
- Performance metrics of all models were visualized using grouped bar charts for easy comparison.
- Confusion matrices were plotted for each model, highlighting their ability to correctly classify fraudulent and non-fraudulent transactions.


