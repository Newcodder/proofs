## A Graph is bipartite if and only if it contains no circles of odd length. 
### Proposition 1: If \(G\) is bipartite, then \(G\) has no cycle of odd length.

**Proof:**

Let \(G = (V, E)\) be a bipartite graph, where \(V\) is the set of vertices and \(E\) is the set of edges in \(G\). By definition, \(V\) can be partitioned into two disjoint subsets \(U\) and \(W\) such that every edge in \(E\) connects a vertex in \(U\) to one in \(W\), with no edges connecting vertices within the same subset.

Assume, for the sake of contradiction, that there exists a cycle \(C\) in \(G\) with an odd length. Without loss of generality, begin traversing \(C\) from a vertex \(u \in U\). Since \(C\) is a cycle of odd length, the number of edges in \(C\) is odd. As we traverse each edge of \(C\), we alternate between vertices in \(U\) and \(W\). However, an odd number of alternations implies that we would return to a vertex in \(U\) (since we started in \(U\)), but on the same side as \(W\) if we were to consider one more step, which is a contradiction to the bipartite nature of \(G\). Therefore, \(G\) cannot contain a cycle of odd length.

### Proposition 2: If \(G\) has no cycle of odd length, then \(G\) is bipartite.

**Proof:**

Let \(G = (V, E)\) be a graph that contains no cycles of odd length. We aim to show that \(G\) is bipartite.

Consider an arbitrary vertex \(v_0 \in V\). Construct sets \(U\) and \(W\) as follows: for any vertex \(v \in V\), place \(v\) in \(U\) if the shortest path from \(v_0\) to \(v\) involves an even number of edges, and place \(v\) in \(W\) if the shortest path from \(v_0\) to \(v\) involves an odd number of edges.

We claim that this construction partitions \(V\) into two sets such that no edge connects two vertices within the same set. Assume, for contradiction, that there exists an edge \(e = \{v, w\}\) with \(v, w \in U\) or \(v, w \in W\). Without loss of generality, suppose both \(v\) and \(w\) belong to \(U\). This implies there are paths from \(v_0\) to \(v\) and \(v_0\) to \(w\) both consisting of an even number of edges. However, the edge \(e\) connecting \(v\) to \(w\) would create a cycle with an odd length when combined with these paths (since the two paths to \(v_0\) can be of the same parity, and adding the connecting edge \(e\) changes the total length to odd), which contradicts the assumption that \(G\) contains no cycles of odd length.

Therefore, by construction, \(V\) can be divided into two disjoint sets \(U\) and \(W\) where each edge connects a vertex in \(U\) to one in \(W\), which means \(G\) is bipartite.

This concludes the formal proof that a graph is bipartite if and only if it contains no cycles of odd length.
