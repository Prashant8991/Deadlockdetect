# 🛡️ Advanced Operating System Process & Deadlock Simulator

![Build Status](https://img.shields.io/badge/Build-Success-brightgreen)
![Version](https://img.shields.io/badge/Version-1.0.0-blue)
![React](https://img.shields.io/badge/React-18-61dafb)
![TypeScript](https://img.shields.io/badge/TypeScript-5.5-3178c6)
![Tailwind](https://img.shields.io/badge/Tailwind-3.4-06b6d4)
![Live Preview](https://img.shields.io/badge/Live_Preview-GitHub_Pages-success)

> A production-ready educational tool and interactive simulator for OS concepts visualization, process scheduling algorithms, and deadlock detection & avoidance (Banker's Algorithm).

🔗 **[Click Here for Live Interactive Preview](https://prashant8991.github.io/Deadlockdetect/)**

---

## 🎯 Overview

A comprehensive, fully-interactive Operating System simulator that visualizes and analyzes:

- 🛡️ **Deadlock Detection & Avoidance** (Banker's Algorithm with safe sequence discovery)
- ⏱️ **CPU Scheduling Algorithms** (FCFS, SJF, LJF, Priority, and Round Robin)
- 🎬 **Process Execution Simulation** (Animated Gantt chart with step controls)
- 📊 **Resource Allocation Graphs** (Canvas-based graph visualization with circular wait detection)
- 📈 **Performance Metrics & Comparisons** (Interactive charts and summary analytics)

---

## ✨ Key Features

### 🛡️ Deadlock Detection Module
- **Banker's Algorithm**: Detects deadlock conditions and finds ALL safe sequences.
- **Resource Allocation Graph**: Canvas visualization with process/resource nodes and circular wait highlighting.
- **Dynamic Configuration**: Configure 2-10 processes and 2-5 resources with real-time updates.
- **JSON Export**: Export complete state and analysis for reports or assignment documentation.

### ⏱️ CPU Scheduling Module
- **5 Scheduling Algorithms**: FCFS, SJF, LJF, Priority, and Round Robin.
- **Animated Gantt Chart**: Real-time step-by-step playback, speed control (0.5x to 2x), and process timeline.
- **Comprehensive Metrics**: Turnaround time, waiting time, CPU utilization, and algorithm comparison charts.

---

## 🚀 Live Demo & Deployment

### View Live on GitHub Pages
Visit the live interactive web demo directly at:
**[https://prashant8991.github.io/Deadlockdetect/](https://prashant8991.github.io/Deadlockdetect/)**

### Running Locally

```bash
# Install dependencies
npm install

# Run local development server
npm run dev

# Build production bundle for GitHub Pages
npm run build
```

---

## 🛠️ Technology Stack

- **Framework**: React 18.3 & TypeScript 5.5
- **Bundler**: Vite 5.4
- **Styling**: Tailwind CSS 3.4
- **Charts**: Recharts & HTML5 Canvas
- **Icons**: Lucide React

---

## 📄 License

This project is open-source under the MIT License.
