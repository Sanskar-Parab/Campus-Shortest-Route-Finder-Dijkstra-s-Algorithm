# 🎓 Campus Shortest Route Finder

A menu-driven **C programming project** that finds the shortest paths between campus locations using Dijkstra's Shortest Path Algorithm.

## 📌 Project Overview

Finding routes between buildings on a college campus can be difficult for new students and visitors. This project represents campus locations as vertices in a weighted graph and connections as edges with distances.

The program calculates the shortest distance from a selected source location to all other reachable locations and displays the corresponding paths.

## ✨ Features

- **Enter Campus Graph:** Add location names and connection distances.
- **Display Adjacency Matrix:** View the graph's distance matrix.
- **Select Source Location:** Choose the starting campus location.
- **Find Shortest Distance:** Calculate minimum distances using Dijkstra's algorithm.
- **Display Shortest Paths:** Show the route from the source to each destination.
- **Display Distance from Source:** Print the shortest distance to each location.
- **Menu-Driven Interface:** Navigate program features through a console menu.

## 📸 Screenshots

### 1. Main Menu

![Main Menu](images/Screenshot%202026-10-05%20143037.png)

### 2. Campus Graph Input

![Campus Graph Input](images/Screenshot%202026-10-05%20143052.png)

### 3. Shortest Route Calculation

![Shortest Route Calculation](images/Screenshot%202026-10-05%20143105.png)

### 4. Distance and Path Output

![Distance and Path Output](images/Screenshot%202026-10-05%20143111.png)

## 🛠️ Technologies Used

- **Programming Language:** C
- **Algorithm:** Dijkstra's Shortest Path Algorithm
- **Graph Representation:** Weighted adjacency matrix
- **Data Structures:** Arrays
- **Libraries:** `stdio.h`, `string.h`

## 🧠 How the Algorithm Works

1. Initialize all distances to infinity and the source distance to zero.
2. Find the unvisited location with the smallest known distance.
3. Mark that location as visited.
4. Update the distances of its connected locations if a shorter path is found.
5. Repeat until no more reachable locations remain.
6. Reconstruct each shortest path using the parent array.

## 🚀 Getting Started

### Prerequisites

Install a C compiler such as GCC or MinGW. You can use Visual Studio Code with a configured C compiler or Dev-C++.

### Clone the Repository

```bash
git clone https://github.com/Sanskar-Parab/Campus-Shortest-Route-Finder-Dijkstra-s-Algorithm.git
```

### Navigate to the Project Folder

```bash
cd Campus-Shortest-Route-Finder-Dijkstra-s-Algorithm
```

### Compile the Program

Save the source code as `main.c` and run:

```bash
gcc main.c -o campus_route
```

### Run the Program

**Windows:**

```powershell
.\campus_route.exe
```

**Linux/macOS:**

```bash
./campus_route
```

## 📋 Available Menu Options

| Option | Description                  |
| ------ | ---------------------------- |
| 1      | Enter Campus Graph           |
| 2      | Display Adjacency Matrix     |
| 3      | Select Source Location       |
| 4      | Find Shortest Distance       |
| 5      | Display Shortest Paths       |
| 6      | Display Distance from Source |
| 7      | Exit                         |

## 📍 Graph Input Format

- Enter the number of locations (maximum 20).
- Enter the name of each location.
- Enter the adjacency matrix containing the distances between locations.
- Enter `9999` to represent no direct connection.
- Enter `0` for the distance from a location to itself.
- Select a source location to calculate shortest paths.

**Note:** For an undirected graph, enter the same distance in both directions. All edge weights must be non-negative.

## ⏱️ Complexity Analysis

For this adjacency-matrix implementation:

- **Time Complexity:** \(O(V^2)\)
- **Space Complexity:** \(O(V^2)\)

Here, \(V\) represents the number of campus locations.

## 🎯 Applications

- College campus navigation
- Finding shortest walking routes between buildings
- Learning graph algorithms and data structures
- Understanding route optimization

## 🔮 Future Enhancements

- Develop a graphical user interface.
- Display campus locations on an interactive map.
- Add locations dynamically.
- Calculate estimated walking time.
- Provide alternative routes to destinations.

## 👨‍💻 Author

**Sanskar Parab**

GitHub: [@Sanskar-Parab](https://github.com/Sanskar-Parab)

## 📂 Project Structure

```text
Campus-Shortest-Route-Finder-Dijkstra-s-Algorithm/
├── main.c
├── README.md
└── images/
    ├── Screenshot 2026-10-05 143037.png
    ├── Screenshot 2026-10-05 143052.png
    ├── Screenshot 2026-10-05 143105.png
    └── Screenshot 2026-10-05 143111.png
```

---

# 🎓 Campus Shortest Route Finder — Dijkstra's Algorithm

A menu-driven program developed in **C** to find the shortest routes between locations on a college campus using **Dijkstra's Shortest Path Algorithm**.

## 📌 Project Overview

The Campus Shortest Route Finder helps users calculate the shortest distance from a selected campus location to all other locations in the graph.

The campus is represented as a weighted graph using an adjacency matrix. Users can enter location names, define distances between locations, select a source location, and calculate the shortest distances and paths.

## ✨ Features

- **Enter Campus Graph:** Add campus locations and their connection distances.
- **Display Adjacency Matrix:** View the graph's distance matrix.
- **Select Source Location:** Choose the starting point from the list of locations.
- **Find Shortest Distance:** Calculate shortest distances using Dijkstra's algorithm.
- **Display Shortest Paths:** Show the route from the source to each reachable destination.
- **Display Distance from Source:** View distances from the selected source to every location.
- **Menu-Driven Interface:** Perform operations through a simple console menu.

## 🛠️ Technologies Used

- **Programming Language:** C
- **Algorithm:** Dijkstra's Shortest Path Algorithm
- **Data Structures:** Two-dimensional arrays and one-dimensional arrays
- **Graph Representation:** Weighted adjacency matrix
- **Header Files:** `stdio.h`, `string.h`

## 🧠 Algorithm Used

Dijkstra's algorithm finds the shortest paths from a single source vertex to other vertices in a weighted graph with non-negative edge weights.

### How It Works

1. Initialize all distances to infinity, except the source distance, which is set to zero.
2. Select the unvisited location with the smallest known distance.
3. Mark that location as visited.
4. Update the distances of its connected locations when a shorter path is found.
5. Repeat until all reachable locations have been processed.
6. Use the parent array to reconstruct and display the shortest paths.

## 🚀 Getting Started

### Prerequisites

Install a C compiler, such as GCC or MinGW, or use an IDE such as Dev-C++ or Visual Studio Code with a configured C compiler.

### Clone the Repository

```bash
git clone https://github.com/Sanskar-Parab/Campus-Shortest-Route-Finder-Dijkstra-s-Algorithm.git
```

### Navigate to the Project Directory

```bash
cd Campus-Shortest-Route-Finder-Dijkstra-s-Algorithm
```

### Compile the Program

Save the source code as `main.c`, then run:

```bash
gcc main.c -o campus_route
```

### Run the Program

**Windows:**

```powershell
.\campus_route.exe
```

**Linux/macOS:**

```bash
./campus_route
```

## 📋 Menu Options

| Option | Operation                    |
| ------ | ---------------------------- |
| 1      | Enter Campus Graph           |
| 2      | Display Adjacency Matrix     |
| 3      | Select Source Location       |
| 4      | Find Shortest Distance       |
| 5      | Display Shortest Paths       |
| 6      | Display Distance from Source |
| 7      | Exit                         |

## 📍 Graph Input Format

- Enter the number of campus locations.
- Enter each location's name.
- Enter the adjacency matrix containing distances between locations.
- Use `9999` to represent no direct connection.
- Use `0` for the distance from a location to itself.
- Select a source location to calculate shortest paths.

**Note:** For an undirected campus graph, enter the same distance in both directions.

## 📂 Project Structure

```text
Campus-Shortest-Route-Finder-Dijkstra-s-Algorithm/
│
├── main.c       # Main C source code
└── README.md    # Project documentation
```

## ⏱️ Complexity Analysis

For the adjacency-matrix implementation used in this project:

- **Time Complexity:** O(V²)
- **Space Complexity:** O(V²)

Here, `V` represents the number of campus locations.

## 🎯 Applications

- Finding routes between college buildings.
- Campus navigation for students and visitors.
- Learning graph representation and shortest-path algorithms.
- Understanding distance optimization in connected networks.

## 🔮 Future Enhancements

- Add a graphical user interface.
- Display campus locations on a visual map.
- Support dynamic addition and removal of locations.
- Display estimated travel time.
- Add support for alternative routes.

## 👨‍💻 Author

**Sanskar Parab**

GitHub: [@Sanskar-Parab](https://github.com/Sanskar-Parab)

---

⭐ If you find this project useful, consider starring the repository!
