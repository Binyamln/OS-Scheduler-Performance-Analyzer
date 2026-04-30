# OS Scheduler & Performance Analyzer

A desktop tool I built as a side project to simulate how an operating system schedules tasks and manages resources (CPU, memory, I/O).

**By Binyamin**

---

## About This Project

This is a personal project I developed to deepen my understanding of operating systems concepts, scheduling algorithms, and software design. It demonstrates my grasp of OS fundamentals through an interactive, visual simulation tool.

## What It Does

The application allows you to:

- **Create and manage tasks** with different priorities, arrival times, burst durations, and memory requirements
- **Run and compare** four major CPU scheduling algorithms:
  - First Come First Serve (FCFS)
  - Shortest Job First (SJF)
  - Priority Scheduling
  - Round Robin
- **Visualize execution** through Gantt charts and live timelines
- **Analyze performance** with metrics like waiting time, turnaround time, CPU utilization, and throughput
- **Compare algorithms** side-by-side with interactive charts

## Why I Built This

I wanted to:
- Solidify my understanding of OS scheduling concepts
- Practice building clean, modular software architecture
- Create something visual and interactive that demonstrates technical knowledge
- Have a portfolio piece that shows both algorithmic thinking and UI development skills

## Tech Stack

- **Frontend**: React + TypeScript + Vite
- **Styling**: Tailwind CSS + shadcn/ui
- **Charts**: Recharts
- **Icons**: Lucide React

## Key Features

### Task Simulation
- User-defined tasks with arrival time, duration, priority, and memory usage
- CPU-bound and I/O-bound task types
- Memory allocation with fixed partitioning

### Scheduling Algorithms
- FCFS, SJF, Priority, and Round Robin implementations
- Configurable time quantum for Round Robin
- Preemptive and non-preemptive variants

### Performance Metrics
- Average waiting time
- Turnaround time
- CPU utilization
- Throughput
- Fairness score

### Visualizations
- Gantt charts for task execution
- Live timeline with task states
- Memory partition visualization
- Algorithm comparison charts

## Running the Project

```bash
npm install
npm run dev
```

Then open `http://localhost:5173` in your browser.

## Building for Production

```bash
npm run build
```


**Built with curiosity and caffeine by Binyamin**
