# Employee Sentiment Analysis

## 📌 Objective
Analyze unlabeled employee messages to detect sentiment trends, rank employees, and identify potential flight risks.

## ✅ Summary of Results

### 🔝 Top 3 Positive Employees
- alice@corp.com
- john@example.com
- leena@company.com

### 🔻 Top 3 Negative Employees
- samir@corp.com
- deepa@support.com
- ravi@logistics.com

### 🚨 Flight Risk Employees
- rohit@company.com
- anita@admin.com
- shreya@support.com

## 📊 Key Insights
- Negative sentiment spikes often correlate with lower message volume and longer messages.
- Most flight risks showed consistent negativity within compressed 30-day periods.
- Regression model achieved **R² = 0.68**, **RMSE = 1.43**, and predicted within ±1 score for ~85% of data.

## 💡 Recommendations
- Monitor employees with frequent negativity closely to prevent attrition.
- Encourage more open communication from those with low message volume.
- Use sentiment trends to guide internal communication and HR outreach efforts.

## 🧠 Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- scikit-learn (Linear Regression)
- HuggingFace Transformers (for Sentiment Classification)

## 📂 Files in Repository
- `main_analysis.ipynb` – complete analysis code
- `final_report.docx` – formatted report for submission
- `visualization/` – saved EDA and model performance charts
- `outputs/` – calculated scores, flags, and model-ready data

## 👤 Author
**Kabir Kohli**  
Email: kabir.kohli@email.com  
Submitted to: jbirch@glynac.ai
