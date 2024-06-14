# Flight Management System

Flight Management System is a console-based application that provides various functionalities related to flight operations, including finding shortest paths between airports, calculating minimum flight costs, determining the number of available flights between airports, and planning travel based on a budget.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Algorithms Used](#algorithms-used)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

This project implements various algorithms and data structures to manage flight-related information such as distances between airports, flight prices, and flight availability. It allows users to perform tasks like finding the shortest path between two airports, calculating the minimum cost to fly between them, and determining how many flights are available.

## Features

- **Shortest Path Calculation**: Uses Dijkstra's algorithm to find the shortest path (in terms of distance) between two airports.
- **Minimum Cost Calculation**: Computes the minimum cost of flying between two airports based on flight prices using Dijkstra's algorithm with a priority queue.
- **Flight Availability**: Determines the number of flights available between two airports using the Edmonds-Karp algorithm for maximum flow in a network.
- **Budget-based Travel Planning**: Helps users plan travel routes based on a specified budget, maximizing the distance traveled.

## Algorithms Used

- **Dijkstra's Algorithm**: Used for finding the shortest path between airports based on distance. It employs a priority queue to efficiently retrieve the shortest path.
  
- **Edmonds-Karp Algorithm**: Used to determine the maximum flow (number of flights) between airports, essential for determining flight availability between airports.

## Requirements

- C++ compiler (supporting C++11 standard)
- Standard C++ libraries (`iostream`, `climits`, `cstring`, `list`, `map`, `queue`, `string`, `vector`, `utility`)

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/menavipandey/Flight_management.git
   ```
2. Navigate to the project directory:
   ```
   cd Flight_management
   ```
3. Compile the source code:
   ```
   g++ -o flight_management main.cpp
   ```
   This will generate an executable file named `flight_management`.

## Usage

1. Run the executable:
   ```
   ./flight_management
   ```
2. Follow the on-screen menu to select various functionalities:
   - Option 1: Show available airports
   - Option 2: Find shortest path between airports
   - Option 3: Calculate minimum flight cost between airports
   - Option 4: Determine number of flights available between airports
   - Option 5: Plan travel destinations based on budget
   - Option 6: Exit the program

## Contributing

Contributions are welcome! If you find any issues or want to enhance the functionality, feel free to create a pull request.
