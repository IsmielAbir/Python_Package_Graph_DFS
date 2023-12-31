# PyGraph_DFS

PyGraph_DFS is a Python package that provides a straightforward and efficient way to perform Depth-First Search (DFS) on a graph. It is a versatile tool that can be used in various scenarios where graph traversal and exploration are necessary.

## Installation

You can install GraphDFS using pip, the Python package manager. Open your terminal or command prompt and run the following command:

```bash
pip install PyGraph_DFS
```
## Usage

After installing the package, you can use it in your Python scripts as follows:

```python

from PyGraph_DFS import GraphDFS

# Create a graph instance
my_graph = GraphDFS()

# Add edges to the graph
my_graph.add_edge("A", "B")
my_graph.add_edge("B", "C")
my_graph.add_edge("B", "D")
my_graph.add_edge("D", "E")

# Perform Depth-First Search (DFS)
visited_nodes = my_graph.dfs("A")

# Print the visited nodes
print(visited_nodes)
```
## Output
['A', 'B', 'C', 'D', 'E']
