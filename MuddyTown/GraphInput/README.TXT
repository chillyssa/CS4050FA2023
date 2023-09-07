PROJECT TITLE: GraphInput - Graph Input Utility
PURPOSE OF PROJECT: Facilitate reading graph data from a file
VERSION: Fall 2023 (1)
AUTHOR: Dr. Jody Paul

DESCRIPTION:
Utility reads in text data for a weighted graph described by its edges and presents it as a list of edges.
Each line of the text represents a single edge.
Each edge in the data file is expected to be represented by a comma-delimited triple:
NameOfNode1, NameOfNode2, Weight
Can be used for directed and undirected graphs as subject to interpretation of the data.
This utility does not address graphs that contain isolated nodes (nodes of degree 0).

USAGE:
* API GENERATION
- Use javadoc to generate API for utility class File2Edges
javadoc -d docs File2Edges.java
xdg-open docs/index.html

* DEMONSTRATION
- Command-line driver class DemoMain demonstrates typical usage (no CLI parameters)
javac DemoMain.c
java DemoMain

* UNIT TESTING
- JUnit-based class File2EdgesTest has methods that generate test data and run basic tests
