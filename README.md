# dynamicmazeVEXcode
VEXcode VR Dynamic Maze-solving Robot 🤖	
## 📌 Overview
This project is a **dynamic maze-solving robot** programmed in **Python using VEXcode VR**.  
The robot navigates through a **dynamic maze**, detects walls, avoids obstacles, reaches a **goal tile (red)** and returns to **home**.  

It then **returns to its starting position**, drawing its path in different colours:  
- ** Blue** for the path towards the goal.  
- ** Green** for the return path.  

---

## 🎯 Features
✅ Uses a **wall-following algorithm** to explore the maze.  
✅ Avoids revisiting the same path using a **loop-detection mechanism**.  
✅ **Changes pen colour dynamically**:  
   - **Blue** when reaching the goal.  
   - **Green** when returning to the starting position.
   - It will print the total number of unique movements the robot has made since it started moving.  

---

## 🛠️ How It Works
1. The robot starts from **home** inside the maze.
2. It follows the **left-wall-following algorithm** to navigate.
3. The robot will explore the maze till it reaches a **red tile (goal)**.
4. It **draws its path in blue** while reaching the goal.
5. When returning back to home, **calculates the shortest way back** and **draws in green**.

---

## 📜 Installation & Setup
1. Open **VEXcode VR** at  ([[https://vr.vex.com/](https://vr.vex.com/)](https://vr.vex.com/)).
2. Click the **converted to text project**.
3. After that copy and paste the **Python code** that is provided.
4. Click **select playground** and select **dynamic wall maze** playground. 
5. When ready, click the start button **▶️** to execute the program.

---


