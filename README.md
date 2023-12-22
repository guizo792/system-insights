# System-Insights

This project is a simple terminal-based application built with Rust and TUI (Text-based User Interface). It provides real time resources monitoring (RAM, CPU, Disk).

## Features : 
1. Real-time System Monitoring : The application provide real-time monitoring of system metrics, including CPU usage, memory utilization, and disk activity.
2. Process Information : ablity to view detailed information about running processes, such as process name, ID, memory usage, CPU usage, and disk activity.
3. User Interaction : The user interface support intuitive controls for navigation, process selection, and overall interaction with the application
4. Platform Independence : The application  is compatible with various operating systems.

## Running the Application

To run the application, follow the steps below:

### Prerequisites

Make sure you have the following tools installed on your system:

1. **Rust:**
   - Install Rust by following the instructions on the [official Rust website](https://www.rust-lang.org/tools/install).

2. **Cargo:**
   - Cargo is the official package manager and build tool for Rust. It is usually included with the Rust installation.

### Clone the Repository

Clone the project repository to your local machine:

  ```bash
  git clone https://github.com/yourusername/your-project.git
  ```
  ```bash
  cd your-project
  ```

## Build and Run
Build and run the application using the following commands:

  ```bash
  cargo build --release
  cargo run
  ```

## Locate the Executable
After a successful build, find the executable in the `target/release` directory within the project folder.

## Run the Executable
You can now run the executable from any location on your machine using the following command:

- On Unix-based systems:

  ```bash
  ./your_project_name
  ```

- On Windows:

  ```bash
  .\your_project_name.exe
  ```
