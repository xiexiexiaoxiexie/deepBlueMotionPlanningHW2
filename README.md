- This is deep blue's motion planning homework2
- Main purpose of this homework is to :
    - Use different heuristic function in A* algorithm, for example Euclidean distance, Manhattan distance and Diagonal Heuristic. And compare their results
    - Add tie breaker to prevent expand too many nodes.
    - Finish the JPS(jumping point search) algorithm, compare JPS and A*.
- Compare result as follows:
    - Use Diagonal distance which is the true distance to goal node expand less nodes.
    - The tie breaker simply return slightly different hScore, and in simple environment, it has less
visted nodes.
    - In simple environment, the JPS takes less time to find path.However in complex environment, sometimes JPS takes more time than A∗.
- Running result:
 ![image](/image/complexenv.png)
- For more information, please check the report in this repo.