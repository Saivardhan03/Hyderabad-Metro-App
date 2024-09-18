# Hyderabad-Metro-App
Overview:
The Hyderabad Metro App is a Java-based metro route finder that calculates the shortest distance and path between metro stations in the Hyderabad Metro network. It leverages Graph and Heap data structures along with Dijkstra, BFS, and DFS algorithms to provide commuters with efficient route recommendations and fare calculations based on the total distance traveled.

Features:
Shortest Route Calculation: Computes the shortest path between any two metro stations using Dijkstra’s algorithm.
Fare Calculation: Automatically calculates the fare based on the distance between the source and destination stations.
Metro Station Information: Includes all stations from Hyderabad Metro's Red, Blue, and Green Lines.
Graph-based Implementation: Metro stations are represented as nodes, and routes between them as edges, with distances and fares used to compute the optimal route.
User-Friendly Interface: Interactive console-based app that allows users to select a source and destination, view the route, and get the estimated fare.

Technologies Used:
Java: Core language for the app development.
Graph Data Structure: Stations are represented as graph nodes and connections as edges.
Heap: Used in Dijkstra's algorithm for efficient route calculation.
Algorithms: Dijkstra, BFS, DFS to calculate the shortest path and time.

Usage:
Run the app in your local Java environment.
Input the source and destination stations from the Hyderabad Metro.
The app will return the shortest path, distance, and fare for the trip.

Future Enhancements:
Integration of real-time data such as train timings.
Graphical user interface (GUI) for easier interaction.
Support for additional metro lines or cities.
