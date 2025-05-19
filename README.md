# 🐚 Mini Shell

A lightweight Unix-like shell developed in C as part of a systems programming project. This project was built to gain hands-on experience with low-level process management, command execution, and basic shell behavior.

---

## 📌 Table of Contents

- [🔧 Features](#-features)
- [📁 Installation](#-installation)
- [▶️ Usage](#-usage)
- [🎯 Learning Objectives](#-learning-objectives)
- [🚫 Not Yet Supported](#-not-yet-supported)
- [🧠 Challenges Faced](#-challenges-faced)
- [🚀 Future Improvements](#-future-improvements)
- [👤 Author](#-author)

---

## 🔧 Features

- Execution of external Unix commands (`ls`, `pwd`, `echo`, etc.)
- Built-in commands:
  - `cd` to change directories
  - `exit` to quit the shell
- Process creation and control using `fork()`, `execvp()`, and `wait()`
- Basic signal handling (`Ctrl+C`)
- Simple command line parsing

---

## 📁 Installation

### Requirements

- A Linux-based system with `gcc` and `make` installed.

### Steps

```bash
git clone https://github.com/eljanati9m/mini-shell-project.git
cd mini-shell-project
make
./minishell
