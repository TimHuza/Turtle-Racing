# 🐢 Turtle Racing Game

A fun and colorful command-line racing game built with Python's `turtle` graphics module. Players choose the number of racers (between 2 and 10), and watch them compete in a vertical race to the top!

## 🎮 Overview

- Launches a graphical window using the `turtle` module.
- You choose the number of turtles (racers).
- Each turtle moves forward randomly until one reaches the finish line.
- The winning turtle is announced in the terminal.

Example:

```
Enter the number of racers (2 - 10): 5

The winner is the turtle with color: green
```

## 🛠️ Installation

1. Make sure you have **Python 3** installed on your system.  
   You can check this by running:

   ```bash
   python --version
   ```

   To run the race:
   ```bash
   python turtle_racing.py
   ```

## 🚀 How to Run

### 1. **Clone the Repository**

```bash
git clone https://github.com/yourusername/turtle-racing.git
cd turtle-racing
```

### 2. **Run the Script**

```bash
python turtle_racing.py
```

> ✅ Make sure you have **Python 3** installed.

## 🎨 Features

* Randomized turtle colors and movement
* User input with input validation
* Real-time race animation using turtle graphics
* Clean and beginner-friendly Python structure

## 📁 Project Structure

```
turtle-racing/
│
├── turtle_racing.py
└── README.md
```

## 🎛️ Controls

* Just input the number of racers when prompted (between 2 and 10).
* Sit back and enjoy the race!

## 🧠 How it Works

* The user inputs the number of racers (validated to be between 2–10).
* Turtle objects are generated with different colors and placed at the bottom of the screen.
* Each turtle moves forward by a random amount each cycle.
* The first to reach the top of the screen wins.

**Enjoy the race! 🐢🏁**
