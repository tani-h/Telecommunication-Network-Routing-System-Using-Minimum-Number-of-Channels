# **Telecommunication Network Routing System Using Minimum Number of Channels**

## **Project Overview**
This project aims to optimize the routing of transmission demands in a telecommunication network, ensuring that the **minimum number of channels** are used between nodes while fulfilling the transmission requirements. The application utilizes **Local Search Algorithms** for pathfinding and **Bin Packing Algorithms** for packet distribution. By implementing these algorithms, the system achieves **45% higher accuracy** than traditional **Greedy Approach** algorithms, providing an efficient solution for managing network traffic.

## **Key Features**
- **Efficient Routing**: Optimizes routing paths by minimizing the number of transmission channels used.
- **Multiple Paths**: Supports multiple possible paths for each transmission demand, ensuring flexibility.
- **Accurate Packet Distribution**: Uses Bin Packing Algorithm to distribute packets efficiently across available channels.
- **Higher Efficiency**: Achieved **45% higher accuracy** compared to the traditional **Greedy Approach**.
- **Python Application**: Built using Python, the system leverages advanced algorithms to optimize network performance.

## **Problem Assumptions**
- **Connected Network**: The optical network is modeled as a connected graph, ensuring there is always a path between source and destination.
- **Undirected Edges**: The network graph edges are undirected, allowing bidirectional transmission.
- **Multiple Demands**: The system can handle multiple transmission demands, even between the same source and destination.
- **Bandwidth Constraints**: Demand size will always be less than the available bandwidth of the channels.
- **Path Flexibility**: There can be multiple paths available for each transmission demand.

## **Technologies Used**
- **Python**: The primary programming language for implementing the algorithms.
- **Local Search Algorithm**: Used for optimal pathfinding in the network.
- **Bin Packing Algorithm**: Used for efficient packet distribution across available channels.
- **Google Colab**: For running and sharing the Jupyter Notebook.

## **Repository Contents**
1. **Project Presentation (.pdf)**: A detailed overview of the project, its algorithms, and results.
2. **Colab Notebook (.ipynb)**: A fully functional notebook containing the code for the routing system, including pathfinding and packet distribution using Local Search and Bin Packing Algorithms.
3. **Project Raw Presentation (.pptx)**: The raw PowerPoint presentation file for the project.

