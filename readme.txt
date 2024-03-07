Name: Haozhe Shu
References: w3school and lecture slides

1. In class, we talked about the fact that Uniform-cost and A* are both optimal search strategies, but Greedy best-first and BFS are not.
   How do your results agree (or not) with that distinction?

   My result agree with the statement. The results produced by ufc and astar are the path that have the lowest costs.

2. Which search strategy (one of BFS, Uniform-cost, Greedy best-first, or A*) does the most “work” – that is, processes the most states
   pulled from the frontier? Which does the least?

   In my result, bfs pulled from the frontier the most and greedy best-first pulled the least.

3. How is the performance of A* affected by the choice of heuristic? Can you explain why?

   The performance of astar-h3 generally take less space than h2 and h1 and performs better. Since h3 is the only algorithm that puts
   the cost of moving the tiles into the calculation, it provides more accurate estimation and therefore would not ignore potential 
   paths that h1 and h2 ignores. 
