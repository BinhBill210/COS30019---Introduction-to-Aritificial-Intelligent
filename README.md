# Graph Search Algorithms in Python
This project implements various graph search algorithms including:

* **Depth-First Search (DFS)**

* **Breadth-First Search (BFS)**

* **Greedy Best-First Search (GBFS)**

* **A*Search (AS)**

* **Custom Uninformed Search (CUS1)**: Iterative Deepening Depth-First Search (IDDFS)

It parses graphs from a structured text file and finds optimal or heuristic-based paths from a start node to one or more goal nodes.
# Contributing Members
* Minh Khanh Huynh
* Binh Thai Nguyen
* Upek Malankandalage
* Krishan Ramesh
# Features
* Flexible and extensible graph parsing from file

* Modular implementation of different search strategies

* Heuristic support using Euclidean distance for GBFS and A*

* Clear output of solution path, total cost, and nodes generated

* Easy to add more custom algorithms
# File Structure
```
├── search.py                  # Entry point of the program
├── PathFinder-test.txt        # Testing input for the program
├── requirements.txt           # Required libraries for python
├── example_input.txt          # Example graph input file
├── test_framework2.ipynb      # Test cases for project
├── test_framework2.py         # Test cases for project
├── README.file                # This file
├── COS30019-2025 S1-A2_A.pdf  # Project requirements
```
# Input File Format
The graph is described using a plain text file with the following structure:
```
Nodes:
1: (4,1)
2: (2,2)
3: (4,4)
4: (6,3)
5: (5,6)
6: (7,5)

Edges:
(2,1): 4
(3,1): 5
(1,3): 5
(2,3): 4
(3,2): 5
(4,1): 6
(1,4): 6
(4,3): 5
(3,5): 6
(5,3): 6
(4,5): 7
(5,4): 8
(6,3): 7
(3,6): 7

Origin:
2

Destinations:
5; 4
```
* ```Nodes```: Each line defines a node with its ID and (x, y) coordinate.

* ```Edges```: Each line defines an edge between two nodes and its cost.

* ```Origin```: The starting node.

* ```Destinations```: One or more goal nodes separated by semicolons.

# Usage

1. **Install Python 3**:
   - Make sure you have **Python 3** installed. You can download the latest version of Python from the official website:  
     [Python 3 Download](https://www.python.org/downloads/)

2. **Clone the Repository**:
   - Clone the repository to your local machine using the following command:
     ```bash
     git clone https://github.com/BinhBill210/COS30019---Introduction-to-Aritificial-Intelligent.git
     ```

3. **Install Required Libraries**:
   - After cloning the repository, navigate to the project directory and install the required libraries using `pip`:
     ```bash
     cd COS30019---Introduction-to-Aritificial-Intelligent
     pip install -r requirements.txt
     ```

4. **Prepare the Input File**:
   - Place your graph input file (e.g., `PathFinder-test.txt`) in the same directory as the script.

5. **Run the Script**:
   - Run the script using the following command:
     ```bash
     python main.py <filename> <method>
     ```
   - Replace `<filename>` with the name of the graph input file (e.g., `PathFinder-test.txt`) and `<method>` with the method you want to use.

Available search methods:

* DFS

* BFS

* GBFS

* AS

* IDDFS

# Running Test cases



