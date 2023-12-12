[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=13159605&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

# Proof: 

Since both graphs $A$ and $B$ have the same number of nodes, that means it's possible for an onto an one-to-one function to exist between them. 

This would be mean that each vertex in $A$ would be mapped to exactly one vertex in $B$, and vice versa.

And since they have the same number of nodes and are completely connected, meaning every vertex is connected to all other vertices, we can say that 
they will have the same number of edges. 

With that, every edge of each vertex of the graphs would also be mapped such that $(u,v)\in E_1$ iff $(f(u),f(v)) \in E_2$

Thus, this satisfies for the graphs to be isomorphic by definiton, proving the theorem 
