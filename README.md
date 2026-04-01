## 🔗 Live Demo
# HCI-LAB-TASK
4 GROUP MEMBERS: SANA | SANIA | HUMAIMA | NEHA
# 🧩 Polyline Drawing Tool

## 📊 Phase 2: Task-Based Analysis

## 📌 Project Overview

The Polyline Drawing Tool is an interactive system that allows users to create, edit, and manage multiple polylines using mouse and keyboard interactions.

This analysis focuses on understanding user interaction and system behavior using structured HCI techniques.

## 🧠 Analysis Techniques Used

🔹 Task Decomposition
🔹 Knowledge-Based Analysis
🔹 Entity–Relation Analysis

# 🔍 1. Task Decomposition

Task decomposition breaks the main task into smaller, manageable subtasks.

## 🎯 Main Task: Create and Manage Polylines

### ▶️ Start Drawing Mode

* Press `b` to enter drawing mode
* System prepares a new polyline

### ➕ Add Points

* Click on canvas
* System records `(x, y)` coordinates
* Points are connected automatically

### 🔄 Finish & Start New Polyline

* Press `b` again
* Ends current polyline
* Starts a new one

### ✋ Move Point

* Press `m`
* Select nearest point
* Drag to reposition
* Real-time update

### ❌ Delete Point

* Press `d`
* Click on a point
* Point is removed
* Polyline updates automatically

### 🔃 Refresh Canvas

* Press `r`
* System redraws all polylines

### 🚪 Exit (Optional)

* Press `q`

# 📘 2. Knowledge-Based Analysis

This defines what the user must know to use the system effectively.

### 🧾 Drawing Behavior

* `b` → Start drawing
* Click → Add points
* `b` again → Finish & start new polyline

### 🎛️ Modes

* Draw mode → `b`
* Move mode → `m`
* Delete mode → `d`
  👉 Only one mode active at a time

### 🖱️ Interaction

* Click → Add / Select
* Drag → Move
* Keys → Control system

### ⚙️ System Behavior

* Points connect automatically
* Multiple polylines supported
* Editing affects selected points only

# 🧱 3. Entity–Relation Analysis

### 🧩 Entities

* 👤 User
* 📍 Point (x, y)
* 📏 Polyline
* 🖼️ Canvas
* ⚙️ System

### 🔗 Relationships

* User → interacts with → Canvas
* Polyline → consists of → Points
* Multiple polylines → exist on → Canvas
* System → manages → polylines

### ⚡ Actions

* Create polyline
* Add points
* Move points
* Delete points
* Redraw canvas

# ⚠️ 4. Limitations & Risks

* 🎯 Closest-Point Selection
  Difficulty selecting correct point in dense areas

* 🔀 Polyline Separation Confusion
  Users may not realize `b` starts a new polyline

* ⚡ Accidental Actions
  Unintended deletion or movement

# 🏁 5. Conclusion

This task-based analysis provides a structured understanding of user interaction with the system. By applying HCI techniques, the design becomes more efficient, predictable, and user-friendly.

# 👤 My Contribution

I worked on the Analysis Phase of this project.
I applied task analysis techniques to break down user interaction, system behavior, and challenges.
I also contributed to logic understanding such as **nearest point detection and mode handling**.

# 📚 References

This analysis is based on concepts from:

* Alan Dix , *Human-Computer Interaction*, Chapter 15 (pp. 512–530)



