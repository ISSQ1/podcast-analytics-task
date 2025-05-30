# 🎧 Podcast Listening Analysis – Thamanyah Internship Task

This project was submitted as part of the technical assignment for a data internship with **Thamanyah**.  
The goal of this project is to analyze podcast listening behavior, generate insights, and implement a simple recommendation system.

---

## 📁 Files Included

- `main.ipynb` – Jupyter Notebook with all code, analysis, and visualizations.
- `users.csv` – User profile data.
- `episodes.csv` – Podcast episode metadata.
- `listens.json` – Listening activity log.
- `README.md` – This documentation file.

---

## 📊 Project Overview

### 1. Reading and Preparing the Data
- Loaded data from three different sources.
- Cleaned invalid values and removed rows with zero or negative listening durations.
- Merged all datasets on `user_id` and `episode_id` for unified analysis.

### 2. Data Analysis
- Identified the most listened-to podcast categories.
- Compared average listening durations between genders.
- Calculated the average number of episodes listened to per user.
- Proposed an additional analysis idea focusing on episode engagement depth.

### 3. Recommendations
- Built a simple function that recommends episodes to users based on their most frequently listened categories.
- Excluded episodes the user had already listened to.

---

## 🛠️ Libraries Used

- `pandas` for data manipulation.
- `matplotlib` for visualizations.

---

## 📨 Contact

Feel free to reach out if you have any questions or need clarification regarding the work.

---
