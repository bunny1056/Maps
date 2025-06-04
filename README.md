# 🗺️ Google Maps Route Planner (DSA Project)

**A GPS-based shortest path visualizer using real-world coordinates, Dijkstra's Algorithm, and Python graph libraries.**

---

## 🚀 Project Overview

This project simulates a simplified version of **Google Maps routing**, where cities are represented as graph nodes with real GPS coordinates. The shortest path between two locations is computed using **Dijkstra’s Algorithm**, and the graph is visualized using `matplotlib` and `networkx`.

> 🔍 Designed to showcase strong grasp of **DSA fundamentals**, particularly graphs, heaps, and real-world extensions like the **Haversine formula** for geospatial distance.

---

## 🧠 Core CS Concepts Applied

| Concept                     | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| **Graphs (Adjacency List)** | Efficient representation of the map network                                 |
| **Dijkstra's Algorithm**    | Optimal shortest path computation for weighted graphs                        |
| **Priority Queue**          | Ensures minimum distance nodes are processed first (`heapq` in Python)       |
| **Haversine Formula**       | Calculates real-world distance using GPS coordinates                         |
| **HashMaps (dict)**         | Used for storing node coordinates, distances, and parent relationships       |

---

## 🌍 Real-World Extensions

- 📍 **GPS Coordinates**: Nodes are actual cities defined using latitude and longitude.
- 🧮 **Haversine Distance**: Edge weights reflect physical distances in kilometers.
- 📊 **Graph Visualization**: Plotted using `matplotlib` and `networkx`.

---

## 🧪 Sample Nodes and Cities

| Node | City       | Coordinates          |
|------|------------|----------------------|
| A    | Bangalore  | (12.9716, 77.5946)   |
| B    | Chennai    | (13.0827, 80.2707)   |
| C    | Hyderabad  | (17.3850, 78.4867)   |
| D    | Mumbai     | (19.0760, 72.8777)   |
| E    | Delhi      | (28.6139, 77.2090)   |
| F    | Kolkata    | (22.5726, 88.3639)   |

---

## 🛠️ How It Works

1. **Define Nodes**: Cities are added with their coordinates.
2. **Connect Edges**: Using either Haversine-based or default weights.
3. **Run Dijkstra**: To compute shortest paths from source to destination.
4. **Visualize**: Plot the graph and highlight the computed path.

---

## 🖼️ Sample Output

```text
Shortest path from A to F: ['A', 'B', 'D', 'E', 'F']
Total Distance: 2061.48 km
