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

## References 
1. Johnson, M. (2020, October 22). Dynamic Maze advance solution. Youtu.be. https://youtu.be/itAMR71XPWc?si=DXY5qUgSiyAa6O_-
2. VEX CS - Unit 5 - Detecting Walls from a Distance - Lesson 1: Distance Sensor. (2025). Vex.com. https://education.vex.com/stemlabs/cs/cs-level-1-vexcode-vr-blocks/detecting-walls-from-a-distance/lesson-1-distance-sensor
3. Johnson, M. (2020a, April 27). VEX VR Dynamic maze . Youtu.be. https://youtu.be/O-m_uFWfGq4?si=UAe5nH7H-lODBijt

## Video Presentation 🎥
https://youtu.be/r1bHhbinFms


