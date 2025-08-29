# 📊 Udemy Courses Data Analysis  (Python)

## 📌 Project Overview
This project analyzes the **Udemy Courses dataset**, which contains details about courses, pricing, subscribers, reviews, and categories.  
The analysis was performed using **Python (Pandas, Matplotlib, Seaborn)** and summarized in a **static dashboard**.

---

## 📂 Dataset Description
The dataset includes:

- **course_id** → Unique ID of each course.  
- **course_title** → Title of the course.  
- **url** → Udemy course link.  
- **is_paid** → Whether the course is Free or Paid.  
- **price** → Course price (converted to integer).  
- **num_subscribers** → Number of enrolled students.  
- **num_reviews** → Number of student reviews.  
- **num_lectures** → Total lectures in the course.  
- **level** → Difficulty level (Beginner, Intermediate, Expert, All Levels).  
- **content_duration** → Duration in hours.  
- **published_timestamp** → Date published.  
- **subject** → Course subject/category.  
- **clean_course_title** → Cleaned version of the course title.  

---

## 🛠️ Data Cleaning & Preparation
- Converted `price` to integer.  
- Converted `published_timestamp` to datetime.  
- Dropped irrelevant index column.  
- Handled missing values in `clean_course_title`.  

---

## 📊 Static Dashboard
The following visuals were created:

- **Pie Charts**  
  - Free vs Paid courses.  
  - Courses per subject.  
  - Subscribers per subject.  

- **Bar & Line Charts**  
  - Courses per level.  
  - Subscribers per level.  
  - Growth of subscribers by year.  

- **KPI Cards (Static)**  
  - Total Subscribers.  
  - Total Reviews.  
  - Total Profit (Paid Courses).  
  - Avg. Number of Lectures per Course.
 
- **Dashboard (Static)**
  <img width="1285" height="848" alt="Udemy Dashboard" src="https://github.com/user-attachments/assets/9ae6f1b1-1bf4-44b9-aee3-2b6ae0ef205d" />


---

## 🔑 Key Insights
- Most courses are **paid**, but free courses attract notable subscribers.  
- **Web Development** and **Business** dominate in subscribers.  
- **Beginner Level** has the highest share of courses and students.  
- Subscriber growth increased steadily year by year.  

---

## 🚀 Tools Used
- **Python**  
- **Pandas**  
- **Matplotlib**  
- **Seaborn**  

---
