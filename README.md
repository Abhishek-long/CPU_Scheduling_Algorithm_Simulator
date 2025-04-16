# CPU Scheduling Algorithm Simulator

A web-based interactive simulator for visualizing and understanding various CPU scheduling algorithms commonly used in operating systems.

## Features

- Support for multiple CPU scheduling algorithms:
  - First Come First Serve (FCFS)
  - Shortest Job First (SJF)
  - Round Robin (RR)
  - Priority Scheduling

- Interactive visualization with:
  - Dynamic Gantt chart
  - Timeline visualization
  - Process management interface
  - Real-time performance metrics

## Performance Metrics

The simulator calculates and displays the following metrics:
- Average Waiting Time
- Average Turnaround Time
- Throughput
- CPU Utilization

## Usage

1. Select a scheduling algorithm from the dropdown menu
2. For Round Robin algorithm, specify the time quantum
3. Add processes using the "Add Process" button
4. For each process, specify:
   - Arrival Time
   - Burst Time
   - Priority (for Priority Scheduling)
5. Click "Submit" to visualize the scheduling
6. View the results in the Gantt chart and metrics table
7. Use "Clear All" to reset and start over

## Project Structure

- `index.html` - Main application structure and UI elements
- `styles.css` - Styling and layout definitions
- `script.js` - Core logic and algorithm implementations

## Getting Started

1. Clone the repository
2. Open `index.html` in a modern web browser
3. No additional setup or dependencies required

## Technical Requirements

- A modern web browser with JavaScript enabled
- No server-side components required
- Works completely client-side

## Contributing

Feel free to contribute to this project by:
1. Forking the repository
2. Creating a feature branch
3. Submitting a pull request

## License

This project is open source and available under the MIT License. 