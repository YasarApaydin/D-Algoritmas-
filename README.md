# D-Algoritmas-

The D* Algorithm was introduced by Anthony Stentz in 1994. The name D* comes from the term "Dynamic A". Because Algorithm D behaves like A* while running, except that the arc costs can change.

The D* (Dynamic A) Algorithm can plan paths in partially known, unknown or changed areas. D and variants are widely used for mobile robot and autonomous vehicle navigation.

Execution of the D* Algorithm can be divided into initial planning and replanning phases. If the robot stops at the starting position, the first planning is done and if the robot detects the nodes with changing obstacles during its movement, re-planning is done.

The D* Algorithm is optimal. It is more efficient in large and complex areas. It avoids backward computation cost.

The D* algorithm falls under heuristic search algorithms.

Heuristic search algorithms, on the other hand, are algorithms that reduce the solution time by giving up searching for the best solution in order to become more efficient in the transition time. Heuristic algorithms do not guarantee that they will find the best result, but they do guarantee that they will find a solution within a reasonable time.

Heuristic search algorithms are a type of algorithm based mainly on the D* Lite algorithm.
 

 
 The worst-case runtime of the D* algorithm depends on the size of the graph and the number of changes to the graph during the search. In the worst case, the D* algorithm has a runtime of O(n^2), where n is the number of nodes in the graph. This is because in the worst case, each node may need to be updated multiple times during the search.

However, in practice, the D* algorithm is often much faster than its worst-case runtime suggests. This is because most graphs are sparse, meaning that they have relatively few edges compared to the number of nodes. Additionally, the number of changes to the graph during the search is often much smaller than the number of nodes in the graph. Therefore, the actual runtime of the D* algorithm depends on the specific characteristics of the graph being searched.

 In short, the D* algorithm is a pathfinding algorithm that calculates the shortest path between two points on a graph, taking into account obstacles and changes in the environment.
 
 
