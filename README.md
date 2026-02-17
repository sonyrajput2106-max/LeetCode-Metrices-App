# 🚀 LEETMETRIC — LeetCode Progress Tracker

**LEETMETRIC** is a web application that helps users track their **LeetCode problem-solving progress** by simply entering their LeetCode username.

The app fetches real-time user statistics using an API and displays progress in a clean and interactive dashboard.

---

## 🌟 Features

✅ Enter LeetCode username  
✅ Fetch user stats instantly using API  
✅ Display progress in a visual format  
✅ Shows solved problems count  
✅ Difficulty-wise breakdown (Easy / Medium / Hard)  
✅ Clean and responsive UI  

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **API Handling:** Fetch API / Axios  
- **UI Design:** Tailwind CSS / Custom CSS  
- **Platform:** LeetCode User Statistics  

---

## 📌 How It Works

1. User enters their **LeetCode username**
2. The app sends a request to the LeetCode Stats API
3. The API returns progress data such as:
   - Total problems solved  
   - Easy / Medium / Hard solved  
   - Ranking and submissions  
4. LEETMETRIC displays the progress in a dashboard

---

## 🔗 API Used

LEETMETRIC fetches user data from:

```txt
https://leetcode-stats-api.herokuapp.com/{username}