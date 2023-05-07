Download Link: https://assignmentchef.com/product/solved-eso207a-homework-3-basic-graph-algorithms
<br>
<table width="573">

 <tbody>

  <tr>

   <td width="371">             <strong>ESO207A:                    Data                   Structures</strong></td>

   <td width="202"><strong>and                   Algorithms</strong></td>

  </tr>

  <tr>

   <td width="371">Homework <em>3: Basic Graph Algorithms</em></td>

   <td width="202"> </td>

  </tr>

 </tbody>

</table>

<strong>Instructions.</strong>

<ol>

 <li>Solutions have to be submitted only on Gradescope and within the deadline. For this, eachproblem should start on a new sheet. If this is not followed then it would not be possible to grade your answers.</li>

 <li>For each problem, write your name, Roll No., problem number, the date and the names ofany students with whom you collaborated. Remember that you must write the answer and the algorithm in your own words.</li>

 <li>For questions asking for graph algorithms, give (a) a clear description of the algorithm inEnglish and/or pseudo-code, where, helpful, (b) a proof/argument of the correctness of the algorithm, and, (c) an analysis of the running time of the algorithm.</li>

 <li>You can refer to the standard algorithms covered in the class and use them as appropriatesub routines.</li>

 <li>For a graph <em>G </em>= (<em>V,E</em>), let <em>n </em>= |<em>V </em>| and <em>m </em>= |<em>E</em>|.</li>

</ol>

Full marks will be given only to correct solutions which are described clearly. Convoluted and unclear descriptions will receive <em>low marks</em>.

<strong>Problem 1. </strong>Given a directed graph <em>G </em>= (<em>V,E</em>) defined the graph <em>G<sup>R </sup></em>= (<em>V,E<sup>R</sup></em>) with all edge directions reversed, that is, <em>E<sup>R </sup></em>= {(<em>v,u</em>)|(<em>u,v</em>) ∈ <em>E</em>}.

<ol>

 <li>Suppose <em>G </em>is represented as an adjacency matrix. Give an <em>O</em>(|<em>V </em>|<sup>2</sup>) algorithm for finding the adjacency matrix representation of <em>G<sup>R</sup></em>. (4)</li>

 <li>Suppose <em>G </em>is represented as an adjacency list. Given an <em>O</em>(|<em>V </em>| + |<em>E</em>|) algorithm for finding the adjacency matrix representation of <em>G<sup>R</sup></em>. (4)</li>

 <li>A source vertex in <em>G </em>is a vertex <em>s </em>such that there is no vertex <em>v </em>∈ <em>G </em>such that (<em>v,s</em>) ∈ <em>E</em>. A sink vertex in <em>G </em>is a vertex <em>u </em>such that there is no vertex <em>v </em>∈ <em>G </em>such that (<em>u,v</em>) ∈ <em>G</em>. Relate the source and sink vertices of <em>G </em>and <em>G<sup>R</sup></em>. Relate the strong components of <em>G </em>with the strong components of <em>G<sup>R</sup></em>. (2+2)</li>

</ol>

<strong>Problem 2. </strong>A connected graph <em>G </em>= (<em>V,E</em>) is said to be bi-partite if <em>V </em>can be partitioned into two non-empty and disjoint partitions <em>V </em>= <em>V</em><sub>1 </sub>∪ <em>V</em><sub>2 </sub>such that any edge {<em>u,v</em>} in <em>E </em>has <em>u </em>∈ <em>V</em><sub>1 </sub>and <em>v </em>∈ <em>V</em><sub>2</sub>. That is, there are no edges among vertices in <em>V</em><sub>1 </sub>or among vertices in <em>V</em><sub>2</sub>. Consider the following test for bi-partition. Run BFS on <em>G </em>starting from vertex <em>s</em>. Let <em>u.d </em>be the shortest distance (as per BFS) from <em>s </em>to <em>u</em>.

<ol>

 <li>Show that <em>G </em>is bipartite iff for every edge {<em>u,v</em>} ∈ <em>E</em>, |<em>d </em>− <em>v.d</em>| = 1. (12)</li>

</ol>

1

<ol start="2">

 <li>Extend the BFS algorithm slightly to give an <em>O</em>(|<em>V </em>|+|<em>E</em>|) algorithm to test if <em>G </em>is bi-partite. (12)</li>

</ol>

<strong>Problem 3. </strong>Give an <em>O</em>(|<em>V </em>|+|<em>E</em>|) algorithm that takes a directed graph and a given edge <em>e </em>= (<em>u,v</em>) and tests if there is a cycle involving <em>e </em>in the graph. (20)

<strong>Problem 4. </strong>Given a graph <em>G </em>= (<em>V,E</em>), consider the following alternative outline for finding a topological order that repeatedly removes source nodes from <em>G</em>.

Repeat until the graph is empty

Find a source, output it and delete it.

Design an <em>O</em>(|<em>V </em>| + |<em>E</em>|) time algorithm to implement this (alternative) outline and prove your complexity.        (22)

<strong>Problem 5. </strong>Given a directed graph <em>G </em>= (<em>V,E</em>), design an algorithm to find a vertex <em>u </em>that has

paths to all vertices in <em>V </em>in <em>G</em>.                                                                                                                                                             (22)

2