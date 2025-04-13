* ```Destinations```: One or more goal nodes separated by semicolons.

# Usage
1. Make sure you have **Python 3** installed.

2. Place your graph input file (e.g., ```PathFinder-test.txt```) in the same directory.
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

3. Run the script using:
```
python main.py <filename> <method>
```
Available search methods:

* DFS
* IDDFS

# Running Test cases
In this project, 12 test cases have been generated, to run the test cases, use the following command:
```
python test_framework2.py
```
or you can run ```test_framework2.ipynb``` to have a clearer visualization of the testing
12 test cases:
* Test case 1: Basic path (same as example in the PDF)
* Test case 2: Multiple destinations with different costs
* Test case 3: One-way paths (directed edges)
* Test case 4: Disconnected graph
* Test case 5: Large graph
* Test case 6: Equal cost paths
* Test case 7: No solution
* Test case 8: Single node
* Test case 9: Cyclic paths
* Test case 10: Complex topology
* Test case 11: Dense graph (Reduced complexity slightly for clarity)
* Test case 12: Simple graph with clear optimal path
