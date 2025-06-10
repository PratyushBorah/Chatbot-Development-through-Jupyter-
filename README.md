# 📘 Financial Chatbot – Smart CSV-Based Financial Assistant

This project is a **Financial Chatbot** built entirely in **Python within a Jupyter Notebook**. It processes company financials from a CSV file (`financial_data.csv`) and intelligently responds to **natural-language questions** related to revenue, net income, and growth trends.

Whether you're analyzing data for **Apple**, **Microsoft**, **Tesla**, or other listed companies—this chatbot can answer questions in a conversational format.

---

## ✅ Features

- 💬 **Natural Language Understanding**: Ask questions like:
  - “What is Apple’s total revenue?”
  - “Show Tesla’s net income growth over time”
  - “Lowest net income of Microsoft?”
  - “Which company had the max revenue among Apple, Microsoft?”

- 🔎 **Fuzzy Matching**: Smartly handles **typos** or minor mismatches in company names or financial terms.

- 📊 **Financial Analysis Capabilities**:
  - Computes and returns **total**, **average**, **minimum**, **maximum**, and **year-wise trends** for:
    - `Total_Revenue`
    - `Net_Income`
    - Derived growth metrics

---

## ⚙️ How It Works

1. **Data Input**: Reads financial data from `financial_data.csv` using `pandas`.
2. **Preprocessing**:
   - Cleans column names and standardizes formats.
   - Computes growth percentages between years.
3. **Query Handling**:
   - Uses `fuzzywuzzy` to match user-input terms to the closest known column or company.
   - Categorizes the query into types: sum, average, min, max, trend.
4. **Response Generation**:
   - Processes user input dynamically and returns the appropriate numeric/statistical answer.

---

## 🧪 Example Questions You Can Ask

- `"Show me Tesla's average net income."`
- `"What is the total revenue for Apple?"`
- `"Give me the year-wise revenue growth for Microsoft."`
- `"Who has the highest net income?"`
- `"Min revenue of Tesla?"`

---
## ⚠️ Limitations
- Only works with companies present in the CSV file.
- Doesn’t handle multi-company or year-specific questions.
- Needs well-formatted data columns (e.g., Total_Revenue, Net_Income).

 ## 💬 Connect With Me

Created by **Pratyush Pr. Borah**  
📧 Email: pratyushborah23@gmail.com  
🔗 LinkedIn: [linkedin.com/in/your-profile] https://www.linkedin.com/in/pratyush-borah-9b89282a6/

