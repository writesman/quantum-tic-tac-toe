# Quantum Tic-Tac-Toe

This project implements a **quantum-enhanced version** of the classic game, *Tic-Tac-Toe*. It utilizes the **Qiskit** framework to demonstrate the use of quantum computing for game state evaluation. The application leverages **Grover's Search Algorithm** to find the winning state (or lack thereof) from all possible game permutations on a quantum computer simulator.

---

## 💡 Project Overview and Motivation

This project explores the concept of designing and playing games whose underlying logic directly executes on **quantum computers**. The goal is not to seek a quantum computational advantage, but to offer an accessible platform for a wider audience to experiment with and learn quantum circuits.

### Research Progression

We first attempted a complex implementation of Quantum Chess based on theoretical designs. This encountered real-world obstacles due to its heavy dependence on resource requirements, specifically the high demand for **qubits** and **circuit depth** beyond the capacity of current NISQ (Noisy Intermediate-Scale Quantum) hardware devices.

In response, we moved to a simpler and more accessible game. We developed a **quantum oracle** that translates the board state to qubits and utilizes quantum logic (Grover's Algorithm) to efficiently search for winning conditions. This kept resource demands minimal while maintaining the spirit of quantum gameplay.

### Conclusion

Our research suggests that while complete, complex quantum games like chess are currently impractical due to hardware limitations. Reduced games like **Quantum Tic-Tac-Toe** provide an effective and accessible means of exploring the intersection between game development and quantum computing.

---

## 👨‍💻 Collaborators

- Ryan Prax
- Taylor Turner
- Marcus Writesman

---

## 🏫 Class Details

**Course**: CSC-4903 Introduction to Quantum Computing  
**Institution**: Tennessee Technological University  
**Semester**: Spring 2025  
**Instructor**: Dr. Muhammad Ismail  
