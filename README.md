# ✈️ Airshow Animation using OpenGL

## 📌 Overview

Airshow Animation is a **Computer Graphics project** developed using **C++ and OpenGL (FreeGLUT)**.
The program simulates an **aerial airshow scene** where airplanes perform animated movements across the screen while interacting with obstacles such as buildings.

This project demonstrates concepts of:

* 2D Graphics Rendering
* Animation in OpenGL
* Transformation and motion
* Interactive graphics using GLUT

---

## 🎯 Features

* Animated **airplane movement**
* **Building obstacles** generated in the environment
* Continuous **scene rendering using OpenGL**
* Smooth animation using **GLUT display loop**
* Keyboard and timing based control
* Real-time graphics rendering

---

## 🛠️ Technologies Used

* **C++**
* **OpenGL**
* **FreeGLUT**
* **GLU Library**

---

## 📂 Project Structure

```
Airshow/
│
├── main.cpp
├── README.md
```

---

## ⚙️ Installation and Setup

### 1️⃣ Install FreeGLUT

For Windows (MinGW users), ensure these libraries are installed:

* freeglut
* opengl32
* glu32

---

### 2️⃣ Compile the Program

Use the following command:

```
g++ main.cpp -o main -lfreeglut -lglu32 -lopengl32
```

---

### 3️⃣ Run the Program

```
./main
```

A window will open displaying the **animated airshow scene**.

---

## 🧩 Code Explanation

The program uses structures and animation logic.

Example structure used for obstacles:

```cpp
typedef struct building
{
 float block_x, block_y;
 bool state;
 int no_floors;
} building;
```

This structure stores:

* **block_x** → X coordinate of building
* **block_y** → Y coordinate of building
* **state** → active/inactive building
* **no_floors** → height of the building

Buildings move across the screen to simulate a dynamic environment.

---

## 📊 Concepts Demonstrated

* 2D transformations
* Animation loops
* Object rendering
* Struct based object modeling
* Frame updates in OpenGL

---

## 🚀 Future Improvements

* Add **multiple airplanes**
* Add **smoke trail animation**
* Add **keyboard controls**
* Add **collision detection**
* Improve graphics with textures

---

## 👨‍💻 Author

**Anshu Kumar**
Computer Science & Engineering Student

GitHub:
https://github.com/AnshuKumar25

---

## 📜 License

This project is developed for **educational and learning purposes**.
