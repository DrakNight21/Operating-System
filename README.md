# 💻 Resource Manager in C++

A lightweight C++ program that simulates resource allocation and optimization across multiple running programs based on available **CPU** and **Memory** capacity. It automatically adjusts resource usage when limits are exceeded, ensuring efficient and fair distribution.

---

## 🔧 Features

- ✅ Dynamic program registration with CPU & memory requirements
- ✅ Automatic resource optimization when over-utilization occurs
- ✅ Clear console output showing real-time allocation
- ✅ Simple, modular object-oriented design

---

## 📦 Example Workflow

```bash
Enter total CPU capacity (%): 100
Enter total Memory capacity (MB): 1000
Enter number of programs: 2

Program 1 CPU usage (%): 60
Program 1 Memory usage (MB): 700

Program 2 CPU usage (%): 80
Program 2 Memory usage (MB): 500
```
Optimizing resources...

--- Current Allocation ---
Program 1: CPU = 42.86%, Memory = 583.33MB
Program 2: CPU = 57.14%, Memory = 416.67MB

📁 Project Structure
```
File	   Description
OS.cpp	Core source file with logic & execution
README.md	Documentation and usage guide
```
🚀 Getting Started
🔹 Prerequisites
 C++11 or later

Terminal or IDE with compilation support

🔹 Compilation
```
g++ -o OS.cpp
```
🔹 Execution
```
./resource_manager
```
🧠 Code Overview
🧩 Program Class
Represents a single program:

id

cpuUsage

memoryUsage

🧩 ResourceManager Class
Handles:

Adding programs

Checking total resource usage

Optimizing resources proportionally if limits are breached

Displaying final status

📚 Concepts Covered
Object-Oriented Programming (OOP)

Vectors & Classes in C++

Resource scaling & proportional allocation

Basic I/O and control flow

🪪 License
This project is licensed under the MIT License.
Feel free to use, modify, and share with proper attribution.

🙌 Acknowledgements
Developed as a demo for C++ resource management simulation and optimization.
Crafted with ❤️ by [Samridha].

