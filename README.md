# 📝 Medium Writers Filtering Pipeline

## 📌 Context
We run a publishing platform focused on **AI/ML and Data Science**.  
Writers apply to join, contribute articles, and get paid.  
To maintain quality, we built a **Python-based approval system** that filters applicants and tracks their performance.  

## 🎯 Purpose
- ✅ Approve only writers who meet **quality and consistency standards**  
- ⚡ Automate filtering instead of manual review  
- 📊 Track writer **KPIs** once they are onboarded  

## 🔄 Pipeline
- **Step 1:** 📂 Load and clean writer dataset (contacts, topics, metadata)  
- **Step 2:** 🔍 Apply eligibility criteria (subscriptions, recency, article quality, payment method, etc.)  
- **Step 3:** 🏆 Output final list of approved writers  
- **Step 4:** 💾 Save approved list + datasets for **KPI tracking**
   
## **✅ Approval Criteria**

1. **Medium Subscription**: Writers must have subscribed (paid to write) at least **2 times per year**.
2. **Consistency**: Writers should publish consistently with **no gap > 2 years** between articles.
3. **Article Requirements**:
    - Average article length ≥ **150 words**.
    - Articles must be **topic-relevant** (AI/ML/Data).
4. **Personal Projects**: Writers must have at least **5 personal projects**.
5. **Payment Method**: Only accept **Stripe** and **PayPal**.
