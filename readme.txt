Haozhe Shu
References: w3school and lecture slides
Notes and warnings: The specific serie of 103425678 produces incorrect result. With this order, BFS will produce the most efficient path.

1. My result agree with the statement. The results produced by ufc and astar are the path that have the lowest costs.
2. In my result, bfs pulled from the frontier the most and greedy best-first pulled the least.
3. The performance of astar-h3 generally take less space than h2 and h1 but sometimes produces unoptmized path. Astar-h2 and astar-h1 
   performs similarly with h2 take slightly less space than h1 but they both reliably produce the optimized path. Among the three 
   heuristic methods, I think h2 estimate the heuristic closest to the actual priority. The algorithm for h3 will produce extremely 
   large estimation for tiles with larger number and thus may ignore some path involves moving tiles with large numbers. 
