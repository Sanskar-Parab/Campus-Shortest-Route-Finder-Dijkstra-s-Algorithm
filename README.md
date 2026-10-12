# 🎓 Campus Shortest Route Finder

A menu-driven **C programming project** that finds the shortest paths between campus locations using Dijkstra's Shortest Path Algorithm.

## 📌 Overview

This project represents campus locations as vertices in a weighted graph and the connections between them as edges with distances. Users can select a source location and calculate the shortest distances and paths to other reachable locations.

## ✨ Features

- Enter campus locations and connection distances.
- Display the adjacency matrix.
- Select a source location.
- Calculate shortest distances using Dijkstra's algorithm.
- Display shortest paths to destinations.
- Display distances from the selected source.
- Simple menu-driven console interface.

## 🛠️ Technologies Used

- **Language:** C
- **Algorithm:** Dijkstra's Shortest Path Algorithm
- **Graph Representation:** Weighted adjacency matrix
- **Data Structures:** Arrays
- **Libraries:** `stdio.h`, `string.h`

## 📸 Screenshots

### 1. Main Menu

![Main Menu](images/Screenshot%202026-10-05%20143037.png)

### 2. Campus Graph Input

![Campus Graph Input](images/Screenshot%202026-10-05%20143052.png)

### 3. Shortest Route Calculation

![Shortest Route Calculation](images/Screenshot%202026-10-05%20143105.png)

### 4. Distance and Path Output

![Distance and Path Output](images/Screenshot%202026-10-05%20143111.png)

## 🚀 How to Run

### Prerequisites

Install GCC or another C compiler.

### Clone the Repository

```bash
git clone https://github.com/Sanskar-Parab/Campus-Shortest-Route-Finder-Dijkstra-s-Algorithm.git
cd Campus-Shortest-Route-Finder-Dijkstra-s-Algorithm
```

### Compile

Save the source file as `main.c`, then run:

```bash
gcc main.c -o campus_route
```

### Execute

On Windows:

```powershell
.\campus_route.exe
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

## 📍 Input Details

- Maximum supported locations: **20**
- Enter the distance between connected locations in the adjacency matrix.
- Use `9999` for no direct connection.
- Use `0` for a location's distance to itself.
- Use non-negative edge weights.
- For an undirected graph, enter the same distance in both directions.

## ⏱️ Complexity Analysis

- **Time Complexity:** \(O(V^2)\)
- **Space Complexity:** \(O(V^2)\)

Here, \(V\) is the number of campus locations.

## 🔮 Future Enhancements

- Interactive graphical campus map.
- Dynamic addition of campus locations.
- Estimated walking time.
- Alternative route suggestions.

## 👨‍💻 Author

**Sanskar Parab**

GitHub: [@Sanskar-Parab](https://github.com/Sanskar-Parab)

---

⭐ If you find this project useful, consider starring the repository!
