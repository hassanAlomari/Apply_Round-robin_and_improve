# ⚙️ CPU Scheduling Optimization: Enhanced Round Robin Algorithm

![Python](https://img.shields.io/badge/Python-3.11-blue.svg)
![Operating Systems](https://img.shields.io/badge/OS-CPU%20Scheduling-orange.svg)
![Algorithms](https://img.shields.io/badge/Algorithms-Optimization-green.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-red.svg)

## 📌 Project Overview
This project focuses on Operating System (OS) process management, specifically targeting the **Round Robin (RR)** CPU scheduling algorithm. While standard RR ensures fairness in time-sharing systems, it often suffers from high context-switching overhead and increased average waiting times if the Time Quantum is not optimized.

In this repository, I implemented the standard Round Robin algorithm and proposed an **Enhanced/Modified Round Robin** approach designed to reduce the Average Waiting Time (AWT) and Average Turnaround Time (ATAT), improving overall CPU efficiency.

## 🎯 Objectives & Algorithmic Improvements
* **Standard Implementation:** Developed a robust baseline simulation of the classic Round Robin algorithm.
* **Algorithmic Enhancement:** Proposed a structural modification to the algorithm's logic (e.g., dynamic time quantum adjustment or intelligent queue sorting) to minimize idle time and reduce context switches.
* **Comparative Analysis:** Evaluated both algorithms using standard OS metrics, proving the efficiency of the proposed enhancement mathematically and programmatically.

## 📄 Detailed Report & Documentation
The theoretical foundation, mathematical proofs, and a detailed breakdown of the proposed improvement are thoroughly documented in the accompanying project report. 

Please refer to the `docs/os_word_Hassan_Alomari.pdf` file for the complete analytical breakdown and metric comparisons.

## 📂 Repository Structure

```text
├── docs/
│   └── os_word_Hassan_Alomari.pdf       # Comprehensive project report and algorithmic breakdown
├── notebooks/
│   └── os_project_Hassan_Alomari.ipynb  # Python simulation for Standard and Enhanced RR
└── README.md                            # Project documentation
