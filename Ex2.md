# Ex.No:2  
# Ex.Name: Minimum Cost to Connect All Houses (MST Approach)  

## Date:  

## Aim:  
To write a C++ function to add edges and weights of a graph (representing houses as 2D coordinates) and compute the **Minimum Spanning Tree (MST)** cost to connect all houses in a city.  
<img width="333" height="293" alt="image" src="https://github.com/user-attachments/assets/cf449b02-04be-47c5-9b74-66407b0cb90e" />


## Algorithm:  
1. Start the program.  
2. Input the number of vertices `N` and edges `E`.  
3. Represent the houses as graph vertices and roads between houses as weighted edges.  
4. Use **Kruskal’s Algorithm** (or Prim’s):  
   - Sort all edges in non-decreasing order of weights.  
   - Pick edges one by one, ensuring they don’t form a cycle (using Union-Find).  
   - Stop when `N-1` edges are chosen.  
5. Calculate the total cost of selected edges.  
6. Display the edges chosen in MST and the **Minimum Cost Spanning Tree** value.  
7. Stop the program.  

## Program:
```cpp
/*
class Graph {
	vector<vector<int> > edgelist;
	int V;

public:
	Graph(int V) { this->V = V; }
	*/
void addEdge(int x, int y, int w)
	{
	    
	    
	// Write your code here
	
	
	}

```
## Output:
```
Input:
4 5
0 1 10
1 3 15
2 3 4
2 0 6
0 3 5

Output:
2 3 4
0 3 5
0 1 10
Minimum Cost Spanning Tree: 19
```
## Result:
<img width="856" height="793" alt="image" src="https://github.com/user-attachments/assets/4d557e76-3257-4792-aa72-e9268a5d092f" />


