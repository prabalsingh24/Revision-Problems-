# Articulation Points
  * [read from here](https://cp-algorithms.com/graph/cutpoints.html) <br>
   Maintain two arrays `in[i]` and `low[i]` where `in[i]` represents entry time for each node in the `dfs` and `low[i]` is used to find whether there is a back-edge in the descendants of node i. If there is no back-edge ==> node i is the articulation point.
   Check implementation.
