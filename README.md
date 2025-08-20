#  Student Placement Analysis

##  Introduction
The **Student Placement Analysis** project aims to study the factors that influence students' **final academic performance (G3 grade)**.  
The dataset contains demographic, family, and lifestyle information of students such as age, gender, address, parents' education level, study time, absences, and more.  

**Main goals:**  
- Explore the relationship between different features and students’ academic results.  
- Apply **Linear Regression** to predict the final grade (G3).  

---

##  Dataset
The dataset includes the following features:

- **school**: Student’s school  
- **sex**: Gender  
- **age**: Age of student  
- **address**: Address (Urban/Rural)  
- **famsize**: Family size  
- **Pstatus**: Parent’s cohabitation status  
- **Medu, Fedu**: Mother’s and father’s education level  
- **Mjob, Fjob**: Mother’s and father’s job  
- **reason**: Reason to choose school  
- **guardian**: Guardian of the student  
- **traveltime**: Home-to-school travel time  
- **studytime**: Weekly study time  
- **failures**: Number of past class failures  
- **schoolsup, famsup, paid, activities, nursery, higher, internet, romantic**: Various support and extracurricular activities  
- **famrel, freetime, goout, Dalc, Walc, health**: Family relationship quality, free time, social life, alcohol consumption, health status  
- **absences**: Number of school absences  
- **G1, G2, G3**: Grades in 1st, 2nd, and final period (G3 is the target variable)  

---

## ⚙Methodology
1. **Data Preprocessing**  
   - Handle missing values and encode categorical variables (One-Hot Encoding).  

2. **Exploratory Data Analysis (EDA)**  
   - Descriptive statistics and data distribution.  
   - Correlation heatmap to identify relationships between features and final grade (G3).  

3. **Modeling**  
   - Apply **Linear Regression** to predict G3.  
   - Evaluate model using: **MAE, MSE, RMSE, R² score**.  

##  Technologies Used
- **Python**  
- **Pandas, NumPy** (data handling)  
- **Matplotlib, Seaborn** (visualization & EDA)  
- **Scikit-learn** (Linear Regression, evaluation metrics)
---

##  Conclusion
- Academic-related factors such as **studytime and previous grades** have significant impact on students’ final results.  
- **Linear Regression** provides a simple and interpretable baseline model with decent accuracy.  
- Future work may explore more advanced models like **Random Forest, Gradient Boosting, or Neural Networks** for better performance.  

---

##  Visualization
(Insert correlation heatmap, scatter plots, or other EDA charts here)

---

## 👨‍💻 Author
- **Nguyen Huynh Phuong Loc** – Data Analyst / Machine Learning Enthusiast  
