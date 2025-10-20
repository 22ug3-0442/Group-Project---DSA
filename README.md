🧩 Task 1 – Graph Data Structure (Member 1)
📘 Overview

In this task, the Graph class was designed and implemented to model the city’s transport network.
The graph uses an adjacency list representation to efficiently manage connections between city locations (vertices) and roads (edges).

⚙️ Features

Add Location: Insert a new vertex into the graph.

Remove Location: Delete an existing location and its connected roads.

Add Road: Create a two-way connection (edge) between two locations.

Remove Road: Delete a road between two connected locations.

Display Connections: Show all locations and their connected routes.

🛠️ Implementation Details

File Name: Graph.java

Data Structure Used: HashMap<String, List<String>> for adjacency list

Provides foundational methods for other modules to build upon (management, tree/list, and UI).

🧠 Purpose

This task forms the core logic of the Smart City Route Planner, enabling all other team members to manage and visualize transport connections effectively.
