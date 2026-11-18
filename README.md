# Port Status Checker

## Project Overview

Port Status Checker is a Python-based network utility developed as part of the Workora Internship Project.

It checks the status of TCP ports on a target host using Python's built-in socket library.

## Objective

To develop a simple utility that attempts TCP connections and identifies port statuses as OPEN, CLOSED, or FILTERED based on connection responses.

## Technologies Used

Python 3.12

Socket Library

Visual Studio Code

TCP Protocol

## Features

Accepts a target IP address.

Accepts starting and ending port numbers.

Validates user inputs.

Attempts TCP connections with a 1-second timeout.

Displays port number, service name, and status.

Handles common input and socket errors.

## How to Run

1. Install Python 3.12.

2. Download or clone this repository.

3. Open the project folder in VS Code.

4. Open the terminal.

5. Run the following command:

         python port_status_checker.py

6. Enter the target IP address and port range.

## Testing

The project was tested locally using the IP address 127.0.0.1.

Port             Service           Result

80                http              CLOSED

8000             Unknown             OPEN

8001             Unknown             CLOSED

Port 8000 was tested using a temporary Python HTTP server.

## Project Files

port_status_checker.py – Python source code.

Port_Status_Checker_Report.pdf – Project report.

Output screenshots – Execution results.

## Disclaimer

This project is intended for educational purposes and authorized network testing only. Scan only systems for which you have permission.
