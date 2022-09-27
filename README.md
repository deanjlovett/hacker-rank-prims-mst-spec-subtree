# hacker-rank-prims-mst-spec-subtree


Hacker Rank


Prim's (MST) : Special Subtree


Author: pranav9413

Difficulty: ***Medium***

Max Score: 60

note: work in progress for a solution


https://www.hackerrank.com/challenges/primsmstsub/problem


Given a graph which consists of several edges connecting its nodes, find a subgraph of the given graph with the following properties:

- The subgraph contains all the nodes present in the original graph.
- The subgraph is of minimum overall weight (sum of all edges) among all such subgraphs.
- It is also required that there is exactly one, exclusive path between any two nodes of the subgraph.

#### Function Description

Complete the prims function in the editor below.

prims has the following parameter(s):

- int n: the number of nodes in the graph
- int edges[m][3]: each element contains three integers, two nodes numbers that are connected and the weight of that edge
- int start: the number of the starting node


#### Returns

- int: the minimum weight to connect all nodes in the graph


#### Input Format

The first line has two space-separated integers *n* and *m*, the number of nodes and edges in the graph.

Each of the next *m* lines contains three space-separated integers *u*, *v* and *w*, the end nodes of *edges[i]*, and the edge's weight.
The last line has an integer *start*, the starting node.


#### Constraints:

- 2 ≤ *n* ≤ 3000
- 1 ≤ *m* ≤ (*n* * (*n* - 1))/2
- 1 ≤ *u*,*v*,*start*, ≤ 3000
- 2 ≤ *w* ≤ 10<sup>2</sup>

There may be multiple edges between two nodes.

Sample Input 0

```
5 6
1 2 3
1 3 4
4 2 6
5 2 2
2 3 5
3 5 7
1
```

Sample Output 0

```
15
```
