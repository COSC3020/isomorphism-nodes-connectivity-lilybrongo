# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

If two graphs $A$ and $B$ are completely connected and have the same number of nodes, then they must be isomorphic. If a graph is completely connected then every pair of vertces in the graph is directly connected by an edge. Different from what we saw in the isomorphism connectivity exercise where not every vertex was connected, example: A was connected to B but there was no connection between A and C or B and C. In a completely connected graph, there are edges between A and B, B and C, and A and C. This is important becuase if two graphs are both complete and have the same number of vertices, then each graph will also have the same number of edges. Knowing this information we can look if the graphs are isomorphic or not. When two graphs are isomorphic we can rename the vertices of one of the graphs in order to match the other graph, while continuing to preserve the connections. By doing this, we can show that there is a one-to-one correspondence between the vertices of the two graphs. Since it is designated that A and B are both complete graphs with the same number of vertices, every vertex in A is connected to every vertex in B and vice versa. This also means that the edge structure is the same in both graphs. To show that these graphs are isomorphic, we can look at a one-to-one mapping or a bijection between the two, similar to what we looked at in the isomorphism nodes exercise. In order to do this we can assume that graph A contains (1,2,3) and graph B contains (4,5,6). We can map 1 to 4, 2 to 5, and 3 to 6. By doing this we are connecting the corresponding vertices, and since both grpahs are complete, every edge in A matches to an edge in B. Since both A and B are complete graphs and have the same number of nodes, their structures are overall identical and we will always be able to create a mapping between their vertices while preserving edges. This means that A and B must be isomorphic. 

References:

Used my responses to isomorphism-connectivity and isomorphism-nodes to help me come to this conclusion. Those exercises included sources from geeksforgeeks as well as videos I watched to get a better understanding of isomorphism. 

I certify that I have listed all sources used to complete this exercise, including the use
of any Large Language Models. All of the work is my own, except where stated
otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is
suspected, charges may be filed against me without prior notice.
