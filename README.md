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
* The same valency

These facts alone do not prove that two graphs are isomorphic, but can disprove that they are isomorphic.  There is no known polynomial time verification that two graphs are isomorps.  






