# 📊 Udemy Courses Data Analysis  (Python)


## 📖 Overview  
This project explores the **Udemy Courses Dataset** to analyze online learning trends, pricing strategies, and student engagement.  
The analysis is done in **Python** using **pandas, matplotlib, and seaborn**, and results are presented in a **static dashboard**.  


---

## 📂 Dataset  
- **File:** `udemy_courses.csv`  
- **Rows:** ~3,600 courses  
- **Columns:**  

| Column               | Description |
|-----------------------|-------------|
| course_id            | Unique identifier for each course |
| course_title         | Title of the course |
| url                  | Link to the course on Udemy |
| is_paid              | Paid or Free |
| price                | Course price |
| num_subscribers      | Number of students enrolled |
| num_reviews          | Number of student reviews |
| num_lectures         | Number of lectures in the course |
| level                | Course level (Beginner, Intermediate, Expert, All Levels) |
| content_duration     | Course length (hours) |
| published_timestamp  | Course publication date |
| subject              | Subject area (Business, Web Dev, etc.) |
| clean_course_title   | Preprocessed course title |

---

## 🛠️ Tools & Libraries  
- Python 3  
- Jupyter Notebook  
- **Libraries:** pandas, matplotlib, seaborn  

---

## 📊 Analysis & Insights  
- **Total Subscribers:** 11.7M+  
- **Total Profit:** $884M+  
- **Avg. Course Price:** $66.01  
- **Paid vs Free:** 91.6% Paid vs 8.4% Free  
- **Most Popular Subject:** Web Development (≈68% of subscribers)  
- **Top Course:** *"Learn HTML5 Programming From Scratch"* (250K+ subscribers)  
- **Trend:** Strong growth until 2015, slight decline afterward  

---

## 📷 Dashboard  
A static dashboard was created to visualize:  
- Subscribers per level & subject  
- Distribution of course levels  
- Top 10 courses by subscribers  
- Yearly subscribers growth  
- Paid vs Free courses  
<img width="1285" height="848" alt="Udemy Dashboard" src="https://github.com/user-attachments/assets/e6efc8ac-97d2-43b9-8622-69e53731155b" />



---

## 🚀 How to Run  
```bash
git clone https://github.com/your-username/udemy-analysis.git
cd udemy-analysis
pip install -r requirements.txt
jupyter notebook Udemy_Analysis.ipynb
---
