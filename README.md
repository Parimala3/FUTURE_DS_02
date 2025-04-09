# customer-support-analysis

# 📊 Customer Support Ticket Analysis

## 📝 Problem Statement
This project analyzes customer support tickets to identify frequent issues, understand resolution timelines, evaluate customer satisfaction, and recommend process improvements.

## 📁 Dataset
- **File:** `customer_support_tickets.csv`
- **Size:** 8,469 rows × 17 columns
- **Key Fields:**
  - Ticket Type, Ticket Subject, Ticket Description
  - Ticket Priority, Ticket Channel
  - First Response Time, Time to Resolution
  - Customer Satisfaction Rating

## 🔍 Objectives
- Clean and analyze ticket descriptions
- Identify top issues by frequency
- Compute average resolution times by type
- Assess satisfaction by support channel
- Provide insights and recommendations

## 📊 Analysis Summary
- **Top Ticket Types:** Product Issue, Billing, Technical Support, Account Management, Feedback
- **Most Common Subjects:** Login Problems, Refund Requests, Feature Requests
- **Longest Avg Resolution:** Technical Support tickets
- **Lowest Satisfaction Channel:** Email

## 📈 Visualizations
- 📌 Bar chart of ticket types & subjects
- 📌 Word cloud of cleaned ticket descriptions
- 📌 Avg resolution time by ticket type
- 📌 Satisfaction rating by channel

## 🧠 Insights
- Technical Support tickets take significantly longer to resolve.
- Repeated issues like login and refund requests can be automated or added to FAQs.
- Email channel has the lowest satisfaction rating and may need process optimization.

## 🛠 Recommendations
- Automate common tickets using chatbot/self-help
- Prioritize high-resolution-time categories
- Improve team training on frequent technical issues
- Enhance support quality in the email channel

## 💡 Tech Stack
- Python (Pandas, Matplotlib, Seaborn)
- WordCloud for NLP visualization
- Jupyter Notebook for analysis

## 📂 Project Files
- `analysis.ipynb` – Full analysis notebook
- `customer_support_tickets.csv` – Raw dataset
- `report.md` – Summary report
- `wordcloud.png` – Word cloud image (optional)

---

### 👩‍💻 Author
Parimala Vuyyuru  
[GitHub](https://github.com/Parimala3) | [LinkedIn](https://www.linkedin.com/in/parimala-vuyyuru/)

---

### 📌 License
This project is licensed under the MIT License.


## ▶️ How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Parimala3/customer-support-analysis.git
   cd customer-support-analysis
Install dependencies (optional if using Jupyter):

bash
Copy
Edit
pip install pandas matplotlib seaborn wordcloud
Open the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook analysis.ipynb
bash
Copy
Edit




Open terminal and run:

bash
Copy
Edit
cd customer-support-analysis

# Initialize git if not already
git init

# Connect to your GitHub repo
git remote add origin https://github.com/Parimala3/customer-support-analysis.git

# Stage and commit all files
git add .
git commit -m "Initial commit - Customer Support Ticket Analysis"

# Push the code
git branch -M main
git push -u origin main



