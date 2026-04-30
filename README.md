# 🎯 Activity Selector — Greedy Visualizer

## 📌 Overview
Frontend-only web app to demonstrate **Activity Selection (Greedy Algorithm)**.  
Runs fully in browser (no backend).

---

## 🚀 Features
- Add/remove activities  
- Run greedy selection  
- Step-by-step visualization  
- Highlights selected/rejected  
- Shows total selected  

---

## 🧠 Algorithm
1. Sort by end time  
2. Pick first activity  
3. If `start ≥ last end` → Select else Reject  

---

## 💡 Greedy Strategy Explanation
The greedy approach makes the **best local choice at each step**.  
Here, we always pick the activity that **finishes earliest**, because it leaves maximum time for remaining activities.  

By doing this repeatedly, we ensure:
- More activities can fit without overlap  
- The final solution is **optimal (maximum number of activities)**  


---

## ⏱ Complexity
- Time: `O(n log n)`  
- Space: `O(n)`  

---

## 🖥 Tech Stack
HTML, CSS, JavaScript, SVG  

---

## ▶️ Run

```bash
git clone https://github.com/panthul-rahul/activity-selector.git
cd activity-selector

##Team members
1)Shaik Sadiq-AP24110011603
2)Panthul Rahul-AP24110011575
3)Balagi-AP24110011610
4)Om Prakash Reddy-AP24110011560
5)Katta Manoj-AP24110011600
Submitted to: CCC-SRM University
