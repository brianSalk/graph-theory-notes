# Graph Notes
In graph theory, a graph is the simplest way to model a network.  Graphs consist of zero or more ***Nodes*** and ***Edges***.
## Vocabulary, Notation and Definitions
A graph $G$ consists of $2$ sets, a set of verticies $V$ and a set of edges $E$.  
**Multiedge**: an edge that appears more than once in a graph.  
**Multigraph**: a graph that contains at least one multiedge.  
**Loop**: an edge that connects a node to itself.  
**Simple Graph**: a graph with no loops or multiedges.  
Given an edge $e = \\{u,v\\}$, $u$ and $v$ are the **end verticies**.  $u$ and $v$ are **incident** with $e$.  $u$ and $v$ are adjacent to eachother and therefor neighbors.  
**Valency** or **degree**: the number of times a vertex appears as an end vertex in that graph, or the number of edges connected to that vertex. notated $d(v)$ or $deg(v)$
Graphs can be displayed as adjacency lists or as diagrams.  
**Subgraph**: A graph obtained by delting some nodes and/or edges from another graph.  
**Induced Subgraph**: A graph obtained by deleting some nodes and only the edges incident to the deleted node(s).  
**Complete Graph**: A simple graph where each vertex is adjacent to every other vertex in the graph.  Notated $K_n$  
**Compliment**: Graph $G1$ is a compliment ($G^c$ or $\overline{G}$) of $G2$ if the intersection of the two graphs edges is $\emptyset$, and the verticies are the same.  
**Handshake lemma**:
```math
\sum_{v \in V} d(v) = 2|E|
```
*note*: $|E|$ means the cardinality of $E$, or the number of elements in $E$.  
**Isomorphism**: When two or more graphs differ only in names of edges and/or verticies but are structurally identical.  Notated $\phi$. 
If two graphs are isomorphic, then they must have:
* the same $|V|$
* the same $|E|$
* The same valency of each $v \in V$

Proving the above alone does not prove that two graphs are isomorphic, but can disprove that they are isomorphic by failing to meet any of the above.  There is no known polynomial time verification that two graphs are isomorps.  

**Digraph** aka **directed-graph**: A graph that only permits traversing one-way along an edge, directions represented by arrows.  
**Out Valency** aka **Out Degree**: The number of edges going out from a vertex.  
**In Valency** aka **In Degree**: The number of edges going into a vertex.  
**Arc**: Edges of a digraph.  
**Walk**: The edges from $u$ to $v$ where $u$ and $v$ are verticies.  These verticies must belong to the same connected component.  
**Path**: A walk where each edge only appears once.  $P_n$ is a path of $n$ verticies.  
**Hamilton Path**: A path that contains every vertex in the graph.  
**Circuit**: A path that starts and ends at the same vertex.  
**Cycle**: A circuit that does not contain repeate edges.  
**Hamilton Cycle**: A cycle that visits every vertex in a graph.  
**Trail**: A walk there each edge appears only once *and* it starts and ends on a different vertex (open).  
**Euler Trail**: A trail that traverses each edge exactly once.  
**Euler Tour**: Euler trail that begins and ends on the same vertex (closed).  
**Tree**: connected graph with no cycles.  
**Forest**: Disconnected graph with no cycles.  
**Leaf**: A vertex of valency $1$, this applies to all graphs, not just trees.  The "root" may be considered a leaf.  
$\mathbf{C_n}$: cycle graph containing $n$ verticies.  









