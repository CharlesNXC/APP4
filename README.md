# APP4
Deterministic Finite Automata by Charles Nicolai, Simon Reynaud, Thomas Rolland, Adrien McPherson

# 🤖 RoboFSM Planner

A graphical Python application for planning, simulating, and exporting robotic mission plans using **Finite State Machines (FSMs)** — specifically designed for the RoboCup Small Size League (SSL).

This project was developed as part of the **Advanced Algorithmics 3** course (APP4) at ESME, following a Problem-Based Learning (PBL) methodology.

---

## 📌 Project Context

In RoboCup SSL, autonomous robots must perform coordinated soccer actions (passes, blocks, shots) based on centralized planning. FSMs help encode consistent, reactive behavior.

Our tool allows users to:
- Convert natural-language instructions into a sequence of elementary robotic actions.
- Dynamically generate FSMs from these tasks.
- Simulate the FSM to observe success/failure outcomes.
- Export the FSM and logs in JSON and TXT formats.

---

## ✨ Features

- ✅ Instruction parsing (e.g., "Pass and shoot")
- ✅ Action mapping to elementary tasks (e.g., GO_TO_BALL, PASS, SHOOT)
- ✅ Dynamic FSM generation with probabilistic transitions
- ✅ Step-by-step FSM simulation (with success/failure feedback)
- ✅ PyQt5 graphical user interface
- ✅ FSM text diagram
- ✅ Export to JSON and TXT (FSM + log)
- ✅ Built-in Help/Instructions panel

---

## 💻 Technologies

- Python 3
- PyQt5
- JSON
- FSM logic using OOP and structured state transitions

---

## 🧠 AI Contribution

This project was enhanced using **OpenAI's ChatGPT**, which assisted in:
- Designing the code architecture and FSM logic.
- Creating docstrings, modular structure, and comments.
- Writing this `README.md` and documentation.
- Debugging and improving the simulation flow.
- Designing the GUI layout and help window contents.

All AI-generated suggestions were reviewed, validated, and adapted by the project team to ensure relevance and correctness in the academic context.

---

## 🚀 Installation

### Requirements
```bash
pip install PyQt5
