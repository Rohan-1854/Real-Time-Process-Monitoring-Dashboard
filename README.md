# Real-Time-Process-Monitoring-Dashboard

Overview

The Real-Time Process Monitoring Dashboard is a Python-based application that provides real-time monitoring of system processes, CPU usage, and memory consumption. It helps administrators efficiently manage processes, identify system bottlenecks, and take necessary actions such as terminating or prioritizing processes.

Features

Real-Time Process Monitoring: Displays active processes, their CPU & memory usage, and process states.

Process Management: Allows administrators to terminate or change the priority of running processes.

Graphical Visualization: Live CPU and memory usage graphs.

Alerts & Notifications: Warns users when resource usage exceeds a threshold.

Cross-Platform Compatibility: Works on Windows, macOS, and Linux.

Modules

1. Process Data Collection (Backend)

Fetches real-time system data using psutil.

Provides details on process ID, name, status, CPU, and memory consumption.

Ensures efficient system monitoring with minimal resource overhead.

2. Graphical User Interface (GUI)

Displays process information in a structured table.

Provides interactive buttons for process management (Terminate, Change Priority).

Uses Tkinter or PyQt for an intuitive user experience.

3. Data Visualization & Alerts

Generates real-time CPU and memory usage graphs using Matplotlib or Plotly.

Implements threshold-based alerts for high resource consumption.

Logs system performance data for later analysis.

Technologies Used

Programming Language:

Python

Libraries and Tools:

psutil - Fetch system process details

Tkinter / PyQt - GUI framework

Matplotlib / Plotly - Data visualization

asyncio / multiprocessing - Background task handling

pyinstaller - Convert Python script to an executable

Other Tools:

GitHub - Version control and collaboration

PyInstaller - Create standalone executable

Task Scheduler/Cron Jobs - Automate execution

Installation & Setup

Clone the Repository:

git clone https://github.com/Rohan-1854/real-time-process-monitor.git
cd real-time-process-monitor

Install Dependencies:

pip install psutil matplotlib pyqt5

Run the Application:

python main.py

Create an Executable (Optional):

pyinstaller --onefile main.py

Execution Flow

Process Data Collection Module fetches system details in real-time.

GUI Module updates the process list dynamically.

Data Visualization Module generates CPU/memory usage graphs.

Users can manage processes (terminate, change priority).

System alerts trigger when resource usage crosses thresholds.

Future Enhancements

Web-based Dashboard using Flask & React.js.

Predictive Analytics for performance monitoring.

Historical Data Logging for trend analysis.

License

This project is licensed under the MIT License.

https://github.com/Rohan-1854
