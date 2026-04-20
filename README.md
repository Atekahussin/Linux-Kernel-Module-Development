# 🐧 Linux Kernel Module Development (C)

![OS](https://img.shields.io/badge/Course-Operating%20Systems-blue.svg)
![Language](https://img.shields.io/badge/Language-C-orange.svg)
![Platform](https://img.shields.io/badge/Platform-Linux-lightgrey.svg)
![KFU](https://img.shields.io/badge/University-King%20Faisal%20University-green.svg)

## 📌 Project Overview
This project focuses on the development and implementation of a **Linux Kernel Module (LKM)**. Unlike standard applications, this module operates within the kernel space, allowing direct interaction with the core of the operating system. The project serves as a practical demonstration of low-level system programming and kernel lifecycle management.

## 🛠️ Technical Implementation & Methodology
The project was developed in a controlled Linux environment to explore kernel-level operations. Key milestones documented in this repository include:
1. **Source Design:** Development of the module logic in C using kernel functions like `printk` for system logging.
2. **Compilation Workflow:** Automating the build process using a `Makefile` to generate kernel objects (`.ko`).
3. **Kernel Interaction:** - Inserting the module using `insmod`.
   - Managing system parameters and viewing real-time kernel logs via `dmesg`.
   - Safely removing the module using `rmmod`.

## 🚀 Key Learning Outcomes
- Understanding the difference between User Space and Kernel Space.
- Mastering Linux command-line tools for system administration and monitoring.
- Handling dynamic kernel module loading and unloading.

## 📁 Repository Structure
- `Documentation/`: Contains the full technical report (PDF) featuring the source code, compilation steps, and execution results from the Linux terminal.

## 👥 Developed By
- **Atekah Hussain Aljafar**
- *Part of the Operating Systems Course - King Faisal University.*

---
*Connect with me on LinkedIn for more projects!*
[https://www.linkedin.com/in/ateka-hussain/](https://www.linkedin.com/in/ateka-hussain/)
