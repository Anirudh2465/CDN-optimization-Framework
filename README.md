
#🚀 Dynamic Network Congestion Simulation and File Distribution 🌐
Welcome to Dynamic Network Congestion Simulation and File Distribution – an innovative network simulation tool designed to model real-time congestion and resource allocation across a dynamic network! This system manages file distribution, load-balancing, and shortest-path determination to give you a comprehensive view of network behavior under various loads.

##🌟 Features
Dynamic Congestion Simulation: Introduces congestion randomly to network nodes with flexible time intervals, simulating realistic network traffic conditions.
Adaptive File Distribution: Efficiently assigns files across subnetworks, adjusting based on current congestion and availability.
Real-Time Pathfinding: Uses intelligent pathfinding algorithms that adjust to real-time congestion levels to find the best routes for file access and retrieval.

##📚 Project Overview
This project simulates a network environment using Python and NetworkX, representing each node as a server or router. By continuously adjusting congestion and dynamically allocating files, this tool provides insights into the intricacies of load distribution and network optimization.

##🧰 Setup & Installation
Prerequisites: Ensure you have Python 3.x and NetworkX installed. We also recommend Matplotlib for 3D graph visualization if you’d like to see interactive congestion mapping.

Clone the repository and navigate to the project directory.
Install the necessary dependencies as listed in requirements.txt.
##🧩 Core Components
Here’s a breakdown of the key files and what each does:

main.py: The main driver file for setting up the network, distributing files, and initializing the congestion simulation.
subnetworks1.py: Contains essential helper functions for managing subnetworks, file assignments, and congestion levels.
Graph.py: Handles 3D visualization and interactive display, showing congestion and file distribution across the network nodes.

##🔍 How It Works
Graph Generation: Initializes a network graph with multiple nodes, each acting as a router or server.
Subnetwork Grouping: Nodes are grouped into subnetworks to better manage congestion and resource allocation.
File Distribution: Files are assigned to nodes based on current availability and congestion levels.
Dynamic Congestion Updates: Random congestion increments simulate fluctuating network loads, introducing bottlenecks at various points in real-time.
Optimal Pathfinding: On file requests, the system calculates the best route across the network, adapting to current congestion to ensure efficient retrieval.

##📊 Visualizations
A 3D graph displays congestion levels and file distributions across network nodes. Visual markers indicate congestion severity, making it easy to track network bottlenecks and available paths.



##🛠 Customizing the Simulation
For a deeper exploration, adjust parameters to simulate different network conditions:

Max Congestion: Control how much congestion each update introduces.
Update Delay: Set intervals for congestion updates, adding variability to the simulation.

##🤝 Contributing
We’re open to suggestions! If you have ideas for improved congestion modeling, smarter pathfinding, or enhanced file distribution, feel free to contribute. Fork the repo, create a feature branch, commit your changes, and open a Pull Request.

##📄 License
This project is distributed under the MIT License. See LICENSE for details.

##🎉 Dive Into Network Dynamics!
Whether you’re exploring network optimization, load balancing, or pathfinding, this simulation tool offers a hands-on way to engage with network dynamics.

Happy simulating! 🌐
