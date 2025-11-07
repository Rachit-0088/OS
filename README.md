AI-Powered CPU Scheduling Simulator

An interactive web-based simulator designed to demonstrate and analyze various CPU scheduling algorithms through dynamic visualizations and AI-powered explanations.
Built using HTML, CSS, and JavaScript, the project provides real-time Gantt chart visualization, performance metrics, and intelligent insights powered by a Large Language Model (LLM) such as GPT.

🚀 Features

🎛️ Interactive Frontend Interface – User-friendly design for process input, algorithm selection, and simulation control.

⏱️ Supports Multiple Algorithms:

FCFS (First Come First Serve)

SJF (Shortest Job First)

Priority Scheduling

Round Robin (with adjustable quantum)

📊 Real-Time Gantt Chart Visualization – Dynamic charts that illustrate scheduling execution visually.

📈 Performance Metrics – Displays waiting time, turnaround time, and CPU utilization for each algorithm.

🤖 LLM Integration (AI Assistant) – Provides natural language explanations of scheduling behavior, suggests optimal algorithms, and generates test workloads automatically.

💡 Educational Focus – Ideal for students and educators to understand CPU scheduling concepts interactively.

🏗️ Project Architecture

The project uses a modular client-side architecture consisting of three main components:

Frontend Interface:
Built with HTML, CSS, and JavaScript for visualization, interaction, and control.

Simulator Module:
Handles process state management, execution trace generation, and Gantt chart rendering.

LLM Integration Module:
Connects to an AI model (e.g., GPT) to provide explanations, recommendations, and workload generation via structured JSON messages.

⚙️ How It Works

Add processes with arrival time, burst time, and (if needed) priority.

Select the scheduling algorithm from the dropdown menu.

Click Simulate to visualize the scheduling flow in the Gantt chart.

View calculated performance metrics in real time.

Ask the AI Assistant for explanations or suggestions on improving performance or choosing algorithms.

🧩 Technologies Used

Frontend: HTML, CSS, JavaScript

Visualization: Chart.js / Canvas API (for Gantt charts)

AI Integration: GPT-based LLM (via structured JSON API calls)

Version Control: Git & GitHub

✅ Testing and Validation

All algorithms and visualization modules were tested using multiple process sets to ensure correctness and efficiency.
Performance metrics were cross-checked with theoretical calculations.
LLM responses were validated for accuracy and contextual understanding.

📦 Project Deliverables

Fully functional web-based CPU Scheduling Simulator

Real-time Gantt chart visualization

Performance metrics and analytics

LLM-powered explanations and recommendations

Comprehensive documentation and report

🧠 Future Enhancements

Add more algorithms (e.g., Multilevel Queue, EDF).

Improve AI reasoning for deeper scheduling optimization.

Include performance comparison charts between algorithms.

Deploy as a hosted web application with interactive chat integration.
