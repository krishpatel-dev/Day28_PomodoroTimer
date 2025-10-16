# 🐍 Pomodoro Timer - Day 28

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/krishpatel-dev/BasicPy4/graphs/commit-activity)

Welcome to Day 5 of the Python learning journey! 🚀 A simple yet effective Pomodoro Timer application built with Python and Tkinter. This application helps you manage your work sessions using the Pomodoro Technique, alternating between focused work sessions and short breaks.

## 📋 Table of Contents
- [Features](#-features)
- [Prerequisites](#-prerequisites)
- [Installation](#-installation)
- [Usage](#-usage)
- [How It Works](#-how-it-works)
- [Customization](#-customization)
- [Contributing](#-contributing)

## ✨ Features

- 🕒 25-minute work sessions followed by 5-minute short breaks
- ☕ 20-minute long break after every 4 work sessions
- ✅ Visual progress tracking with checkmarks
- 🎨 Clean and intuitive user interface
- 🖱️ Simple start/reset controls

## 🛠 Prerequisites

- Python 3.8 or higher
- Tkinter (usually comes with Python installation)

## 📥 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/pomodoro-timer.git
   cd pomodoro-timer
   ```

2. **Install dependencies**
   ```bash
   # No additional dependencies required if Tkinter is installed
   ```

## 🚀 Usage

1. Run the application:
   ```bash
   python Proj28_pomodoro_timer.py
   ```

2. Click the "Start" button to begin your first Pomodoro session.

3. Work for 25 minutes until the timer rings.

4. Take a 5-minute break when prompted.

5. After completing 4 work sessions, enjoy a longer 20-minute break.

## 🔧 How It Works

The Pomodoro Technique is a time management method that uses a timer to break work into intervals, traditionally 25 minutes in length, separated by short breaks. This application implements this technique with the following intervals:

- Work: 25 minutes
- Short Break: 5 minutes
- Long Break: 20 minutes (after 4 work sessions)

## 🎨 Customization

You can easily customize the timer durations by modifying these constants in the code:

```python
WORK_MIN = 25        # Work duration in minutes
SHORT_BREAK_MIN = 5  # Short break duration in minutes
LONG_BREAK_MIN = 20  # Long break duration in minutes
```

## 🤝 Contributing

Contributions are welcome! Here's how you can contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

<div align="center">
  Made with ❤️ and ☕ by <b>Krish</b>
</div>
