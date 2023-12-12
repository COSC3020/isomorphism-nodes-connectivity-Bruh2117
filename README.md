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

Suppose graphs $A = (V_1, E_1)$ and $B = (V_2, E_2)$ have the same number of nodes and are completely connected, meaning every vertex is connected to every other vertex in the graph. 

Now suppose we have a function $f: A \rightarrow B$, such that $\forall$ vertices $u \in V_1$ and $v \in V_2$: 

$f(u_1) = v_1$, 

$f(u_2) = v_2$, 

...

$f(u_n) = v_n$ 

Where $n$ is the number of vertices in the graphs, which we noted are equivalent for both. 

This means that $f$ is onto and one-to-one since each vertex in one graphs is mapped to exactly one in the other, making it a bijective function. 

And since the graphs have the same number of nodes and are completely connected, that means that $A$ and $B$ have the same number of edges. 

So with the function $f$, not only will each vertex correspond to exactly one in the other graphs, but so will all of the vertex's edges, meaning
that every edge in one graph will correspond to exactly one edge in the other. 

Thus, we have showed are isomorphic to each other by defintion
