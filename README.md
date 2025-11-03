# 🧠 LRU Page Replacement Algorithm Visualizer

This is a **standalone, client-side web application** that provides a **real-time, interactive visualization** of the **Least Recently Used (LRU)** page replacement algorithm.  
This tool is designed to help students and developers understand how the LRU algorithm manages memory, handles page faults, and tracks page recency.

This project is built with **vanilla HTML, CSS, and JavaScript (ES6+)**, using the **Canvas API** for all rendering.  
It has **zero dependencies** and runs entirely in the browser.

🔗 **Link to Live Deployment:**  
👉 [Click here to try the visualizer live!](https://parth-05122005.github.io/LRU-Algorithm-Page-Replacement-Simulator/)

---

## ⚙️ Features

### 🎛 Interactive Simulation  
Input any number of frames and a custom reference string to see how the algorithm performs.

### ⏯ Step-by-Step Control  
Play, pause, step forward, and step backward through the entire execution trace.

### ⚡ Dynamic Speed Control  
Use the speed slider to watch the animation in real-time or slow it down to analyze each step.

### 📉 Timeline Scrubbing  
Jump to any point in the simulation by dragging the timeline slider.

### 🖥 Responsive Canvas  
The visualization is fully responsive and adapts to your screen size.

---

## 🎨 Clear Color-Coding

- 🟩 **Green:** Indicates a Page Hit.  
- 🟥 **Red:** Indicates a Page Fault and shows the replaced frame.  
- 🟦 **Blue:** Represents a standard, occupied frame.

Eviction Visualization: On a page fault, a clear **(Old Page → New Page)** graphic appears to show exactly which page was evicted.

---

## 📊 Detailed Statistics

Get instant feedback on:  
- Total Page Faults  
- Page Hits  
- Final Hit/Miss Ratio  

---

## 💾 Export Data

- **📸 Export Screenshot:** Download a `.png` of the current visualization.  
- **📜 Export Execution Trace:** Download a `.txt` file detailing the state of memory and the algorithm's actions at every single step.

---

## 💻 How to Use

This application runs locally in any modern browser.  
No server or setup is required.

### 🪜 Steps:

1️⃣ **Clone the Repository:**
```bash
git clone https://github.com/parth-05122005/LRU-Page-Replacement-Simulator.git
