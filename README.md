# Project 1: Marketing Campaign Optimization with Machine Learning

## 📝 Introduction
This project aims to apply Machine Learning techniques to optimize marketing campaigns based on **Return on Investment (ROI)**. The goal is to build a predictive model that helps companies **make more strategic decisions** regarding the allocation of their marketing budgets, identifying the most profitable channels to maximize results.  
The solution was developed with a focus on interpretability, reproducibility, and practical applicability in business environments.

## 📊 Data

The data used was extracted from a file named campaigns.CSV, containing:

- campaing_id
- budget (budget for each campaign)
- channel (channels through which the campaign runs)
- engagement
- ROI (return on investment)

Steps performed:

- Data cleaning and preprocessing
- Exploratory analysis with scatterplots
- Preprocessing for modeling
- Modeling

---

## 🤖 Modeling

Modeling was performed using the **Linear Regression** algorithm, with **"budget"**, **"channel"**, and **"engagement"** as predictor variables and **"ROI"** as the target variable.

📌 **Model Evaluation:**  
- **MSE**  
  0.008880675056313457

- **RMSE**  
  0.09423733366513219

- **MAE**  
  0.059717449408166846

As can be seen, all evaluation metrics for the **Linear Regression** model show that the model performed very well.

---

## 🛠️ Tools Used

The project was developed using the following tools:

- **Python** – Main language of the project
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical and vector operations
- **Scikit-Learn** – Predictive modeling and metric evaluation
- **Matplotlib** – Data visualizations
- **Google Colab** – Initial development and prototyping

---

## ✅ Results

- Strong correlation between marketing investments and sales as evidenced by the graphs.
- The model suggests that the **Google** channel is the most profitable of all, with an ROI of 1.60. That is, for every R$ 1.00 invested, the return is R$ 1.60, a 60% profit over the investment made.
- Highly capable model for predicting sales based on budget allocation per channel.
- Direct assistance in deciding where to invest for the highest ROI.

---

## 🧠 Conclusions

The project demonstrates how Machine Learning can:

- **Optimize the ROI** of advertising campaigns
- Support **strategic decisions** on budget allocation
- Identify the **most effective** marketing channels

---

## 🔄 Next Steps

- Collect more data to refine accuracy
- Test new algorithms and approaches
- Create a graphical interface (e.g., with Streamlit)
- Implement in a production environment (e.g., API or dashboard)

---

🧑‍💻 **Author and Contact**

Higor Roberto Coutinho Caetano

**Linkedin**: https://www.linkedin.com/in/higor-caetano-049521136/

**e-mail**: higorfct@gmail.com


