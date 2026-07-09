# 🚀 Round Robin Task Scheduler in C

A Round Robin Task Scheduler implemented in C that demonstrates cooperative multitasking without using a Real-Time Operating System (RTOS). This project simulates task scheduling using Task Control Blocks (TCBs), function pointers, and fixed time slices.

---

## 📌 Features

- ✅ Cooperative Round Robin Scheduling
- ✅ Task Control Block (TCB) Implementation
- ✅ Function Pointer-Based Task Management
- ✅ Simulated System Tick
- ✅ Yield Mechanism
- ✅ Fair CPU Time Allocation
- ✅ Modular C Programming

---

## 🛠 Technologies Used

- C Programming
- GCC Compiler
- Visual Studio Code / Code::Blocks

---

## ⚙️ How It Works

The scheduler stores multiple tasks in Task Control Blocks (TCBs). Each task is executed sequentially in a circular order. After completing its allocated time slice or yielding execution, the scheduler switches to the next task, ensuring fair CPU utilization.

---

## 📂 Project Structure

```
Round-Robin-Task-Scheduler-C
│── main.c
│── scheduler.c
│── scheduler.h
│── tasks.c
│── tasks.h
└── README.md
```

---

## 🎯 Applications

- Embedded Systems
- IoT Devices
- Robotics
- Industrial Automation
- Automotive Systems
- Smart Embedded Applications

---

## 📖 Learning Outcomes

Through this project, I learned:

- CPU Scheduling
- Cooperative Multitasking
- Task Control Blocks (TCBs)
- Function Pointers in C
- Embedded Software Design
- Modular Programming

---

## 🔮 Future Improvements

- Priority Scheduling
- Preemptive Scheduling
- Dynamic Task Creation
- Timer Interrupt Support
- RTOS-Based Implementation

---

## 🙏 Acknowledgement

This project was developed as part of my internship at **Aparaitech Software** to strengthen my understanding of embedded systems and operating system scheduling concepts.

⭐ If you found this project useful, consider giving it a star!
