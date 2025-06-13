# Multiprogramming OS Simulator

This project simulates the core functionality of a multiprogramming operating system in two phases:

- **Phase 1**: Basic job loading and execution.
- **Phase 2**: Enhanced with memory management and multiprogramming features.

It demonstrates key OS concepts like process control, job scheduling, memory allocation, and interrupt handling in a simplified environment, ideal for educational understanding.

## 🧰 Features

- Job queue and execution management
- Simulated memory with paging/segmentation (Phase 2)
- Simple CPU cycle simulation
- Basic interrupt handling

## 🛠️ Technologies Used

- C / C++
- File I/O for job loading
- Terminal-based execution (no external dependencies)

## 📁 How to Run

1. Clone the repository.
2. Compile using a C++ compiler:
   ```bash
   g++ phase1.cpp -o phase1
   ./phase1
   g++ phase2.cpp -o phase2
   ./phase2
