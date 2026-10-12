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

| Option | Description |
|---|---|
| 1 | Enter Campus Graph |
| 2 | Display Adjacency Matrix |
| 3 | Select Source Location |
| 4 | Find Shortest Distance |
| 5 | Display Shortest Paths |
| 6 | Display Distance from Source |
| 7 | Exit |

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

⭐ If you find this project useful, consider starring the repository!
