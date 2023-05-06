Download Link: https://assignmentchef.com/product/solved-eecs340-assignment-7-graph-algorithms
<br>
<h1></h1>

There are <em>n </em>basketball teams in the world. The ranking of these teams from the previous year is available. This year, some of these <em>n </em>teams played against each other and the winner of each game was determined. There were <em>m </em>games in total. The International Basketball Association wants to introduce a new performance criterion, called “domination factor”, defined as follows: Team <em>i </em>is said to “dominate” team <em>j </em>if we can find a chain of games such that <em>j </em>was beaten by a team that was beaten by a team that was beaten by a team … that was beaten by <em>i </em>(observe that, according to this definition, domination can be bi-directional, i.e., <em>i </em>and <em>j </em>can dominate each other). Then, for each team <em>i</em>, the domination factor <em>z<sub>i </sub></em>is defined as the rank of the best team (that is, the highest ranked team according to last year’s rankings) that is dominated by team <em>i</em>.

<ul>

 <li>Describe an <em>O</em>(<em>m </em>+ <em>n</em>) time algorithm to compute the domination factor for all the <em>n </em> (<em>Hint: </em>Use Depth-First-Search)</li>

 <li>Prove that your algorithm is correct.</li>

</ul>

<h1>Problem 2</h1>

Prove or disprove the following statements:

<ul>

 <li>Let <em>G </em>= (<em>V,E</em>) be a directed graph. For any <em>uv </em>∈ <em>E</em>, if some run of Depth-First-Search (DFS) on <em>G </em>results in <em>f &gt; u.f</em>, then <em>uv </em>must be on a cycle.</li>

 <li>Consider any run of DFS on a directed graph <em>G </em>= (<em>V,E</em>). For any edge <em>uv </em>∈ <em>E</em>, if there is a path from <em>v </em>to <em>u </em>in <em>G</em>, then <em>uv </em>cannot be a cross edge.</li>

</ul>

<strong>Problem 3 – Removed</strong>

This problem was removed because Dijkstra’s algorithm has not yet been taught.

<h1>Problem 4</h1>

Please upload evidence of completion of course evaluation (a screenshot of the confirmation page will suffice). Note: This is 20% of assignment grade.