## 9.1 

Consider each edge. It counts for one in-edge for a certain vertex and one out-edge for another vertex. Therefore, 

(sum of all in-degrees) == (sum of all out-degrees) == (edges count)

## 9.2 

This is shown in Fig 9.2

![alt text](figures/Cha9/9.2and9.3.jpg)

## 9.3

This is shown in Fig 9.3.

All the directions are in 9-3a1, 9-3a2, 9-3a3 and 9-3b1.

Explanation from relations:

Consider edge pointing from A to B means that A beats B.

Consider the relationship in 9-3a, which represents a round-robin tournament of tie of 3 players. We call this a "3-tie".

9-3a1 represents one 3-tie and another player beats all ones in the 3-tie.

9-3a2 represents one 3-tie and another player beaten by all from the 3-tie.

9-3a3 represents two 3-ties formed(ABC and ABD), in which case, ACD and BCD must be definite ranking as shown in figure 9-3b.


9-3b represents a definate ranking: B better than C, C better than A.

9-3b1 represents a definate ranking among four players: D better than B, B better than C, C better than A.

## 9.4

Fig 9-3b and Fig 9-3b1 are two examples of strict partial ordering.

---

Proof that strict partial ordering must be acyclic:

Suppose a circuit exists, from a1, going through, a2, a3, till ai and finally going back to a1.

Since the transitive rule, there must be an edge from a1 to ai directly. Since there is also one edge pointing from ai to a1, these two edges contradict the assumption that the graph is asymmetric. End.

---

Removing edge BA from Fig 9-3b, we get one acyclic graph, which is not strictly partial order since it does not satisfy the transitive rule. 


