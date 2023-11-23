# Process Scheduling Analyzer

The OS Process Scheduling Analyzer is a comprehensive software tool designed to empower users to assess and compare the performance of fundamental process scheduling algorithms. The supported algorithms include:

- First-Come-First-Serve (FCFS)
- Shortest Job First (SJF)
- Round Robin
- Longest Job First (LJF)
- Lottery Ticketing
- Priority Scheduling

The primary objective is to provide a user-friendly interface for inputting and simulating diverse sets of processes with varying burst times, priorities, and quantum times. By executing these scheduling algorithms and tracking key performance metrics, such as average waiting times, turnaround times, and response times, the tool facilitates in-depth analysis and informed decision-making regarding process scheduling choices.

## Getting Started

To get started with the OS Project, follow these steps:

**Clone the Repository:**

```bash
git clone https://github.com/TartejBrothers/Process-Scheduling-Analyzer.git
cd Process-Scheduling-Analyzer
```

- To compile

```bash

gcc `pkg-config --cflags gtk+-3.0` -o main main.c `pkg-config --libs gtk+-3.0`

```

- To run

```bash

./main

```

## Technologies Used

- **Frontend:** Gtk Gui

## Contribution Guidelines

We welcome contributions from the community! If you'd like to contribute to the project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and submit a pull request.

Happy networking!

Feel free to customize it further based on your project specifics.
