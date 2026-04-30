# 🎯 Activity Selector — Greedy Algorithm Visualizer

## 📌 Overview

This project is a **frontend-only web application** that demonstrates the **Activity Selection Problem** using a **Greedy Algorithm**.

It allows users to input activities with start and end times, and then visually shows how the algorithm selects the maximum number of non-overlapping activities.

The application is fully interactive and runs entirely in the browser without any backend.

---

## 🚀 Features

* ➕ Add and remove activities dynamically
* ▶️ Run greedy algorithm to select optimal activities
* 📊 Timeline visualization using SVG
* 🔍 Step-by-step execution trace
* 🎯 Highlight selected and rejected activities
* 🧮 Displays total number of selected activities
* ⚡ Instant results (no server required)

---

## 🧠 Algorithm Used

### Greedy Activity Selection Algorithm

The algorithm works as follows:

1. Sort all activities based on their **end time**
2. Select the first activity
3. For each next activity:

   * If its start time ≥ last selected activity’s end time → **Select**
   * Otherwise → **Reject**

---

## ⏱ Time & Space Complexity

* **Time Complexity:** `O(n log n)` (due to sorting)
* **Space Complexity:** `O(n)`

---

## 🖥️ Tech Stack

* HTML5
* CSS3
* JavaScript (Vanilla JS)
* SVG (for visualization)

---

## 📂 Project Structure

```
project/
│── index.html
│── style.css
│── script.js
```

*(In this project, all code is combined into a single HTML file for simplicity.)*

---

## ▶️ How to Run

1. Download or clone the repository
2. Open the file:

```
index.html
```

3. Run it in any browser (Chrome recommended)

No installation or setup required.

---

## 📷 How It Works

1. Enter activity name, start time, and end time
2. Click **Add Activity**
3. Click **Run**
4. The system will:

   * Sort activities
   * Select optimal ones
   * Show step-by-step decisions
   * Display results visually on a timeline

---

## 🌍 Real-World Applications

* Meeting scheduling
* CPU task scheduling
* Event planning
* Resource allocation problems

---

## ⚠️ Limitations

* Only demonstrates greedy approach
* No backend or data persistence
* Works on manually entered data only

---

## 🔮 Future Improvements

* Add comparison with non-greedy approaches
* Auto-play animation for steps
* Save/load activity sets
* Add more algorithm visualizations

---

## 👨‍💻 Author

Developed as a frontend-based algorithm visualization project.

---

## 📌 Conclusion

This project effectively demonstrates how a **Greedy Algorithm** can be used to solve optimization problems efficiently, while also providing a clear visual understanding of each step in the process.
