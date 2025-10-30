======================================================
⚡ Naruto: Nine-Tails Chakra Network Visualizer 🍥
======================================================

The ultimate tool for calculating and visualizing the shortest path of Chakra transmission through a network of allied Ninjas, utilizing Dijkstra's Algorithm.

--------------------
🌟 Features
--------------------

* Dijkstra's Algorithm Implementation: Calculates the shortest time (weight) for Chakra to travel from a source Ninja (Naruto) to all other Ninjas in the network.
* Interactive Canvas Visualization: Renders the network graph dynamically, showing the Ninjas (Nodes) and Chakra Links (Edges).
* Animated Chakra Flow: Visualizes the "activation" process, where Chakra particles traverse the links, illuminating the shortest paths calculated by the algorithm.
* Configurable Network: Easily adjust the number of Ninjas, connections, source, and query targets via the sidebar inputs.
* Animation Speed Control: A "Chakra Transmission Speed" slider allows you to control the visualization speed for detailed observation.
* Themed Design: A visually engaging theme inspired by the Naruto universe.

--------------------
🛠️ Technology Stack
--------------------

This project is a pure front-end application and uses VANILLA WEB TECHNOLOGIES:

* HTML5: For the page structure and user interface elements.
* CSS3: For styling and dynamic background/particle effects.
* Vanilla JavaScript (ES6+): For all application logic, including the Dijkstra's algorithm implementation and the Canvas animation engine.
* HTML5 Canvas API: Used for drawing the dynamic network graph and visualization effects.

No external dependencies or Node.js modules are required!

--------------------
🚀 How to Run
--------------------

Since this is a client-side web application, deployment is straightforward:

1. Clone or Download: Get the project files (index.html, style.css, script.js).
2. Ensure File Structure: Make sure all files are in the same directory:
    - index.html
    - style.css
    - script.js
3. Launch in Browser: Simply double-click the index.html file. It will open in your default web browser (Chrome, Firefox, Edge, etc.).

--------------------
⚙️ Usage and Configuration
--------------------

The sidebar allows you to define your Chakra Network graph.

FIELD: Number of Ninjas (N)
DESCRIPTION: The total number of nodes in the graph (e.g., 4). Ninjas are numbered 1 to N.

FIELD: Number of Connections (M)
DESCRIPTION: The total number of links/edges.

FIELD: Source Ninja (S)
DESCRIPTION: The node ID representing Naruto, the starting point for Chakra distribution (e.g., 1).

FIELD: Chakra Links (u v t)
DESCRIPTION: Defines a link between Ninja u and Ninja v with a Chakra transmission time (cost) of t. The graph is undirected. Input format is line-separated "u v t" triples.

FIELD: Query Targets
DESCRIPTION: A list of Ninja IDs whose minimum Chakra transmission time from the source you want to calculate. Input format is line-separated Ninja IDs.

CONTROLS:
* Visualize: Executes Dijkstra's algorithm, calculates the shortest paths, and starts the animated visualization.
* Reset: Clears the canvas and hides the results panel.
* Chakra Transmission Speed: Adjusts the multiplier for the animation speed.


======================================================
