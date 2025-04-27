agent :Entity that preceives its environment and acts upon that environment


State: A configuration of the agent and its environment 


Initial : The start configuration of agent 


Action: Choices that can be made in a state:


Actions: Set of all Actions


Transition model  : A description of what state results from performing any applicable action in any state


Result(s,a) returns the state resulting from pefroming action a in state s


Goal test: way to determine whether a guvewn state is a goal state 


path cost: numerical cost associatied with path cost 



Search Problem :
-initial state
-actions 
-transition model
-goal test 
-path cost function 



Optimal solution: a solution that has the lowest path cost among all solutions 



Node: a data structure that keeps track of:
-a state
-a parent(node that generated this node)
-an action (action applied to parent to get node)
-a path cost (from initial state to node)




Approach :
-start with a frontier that contains the initial state 
-Start with an empty explored set.
-Repeat:
       - If the frontier is empty , then no solution 
       - remove a node from the frontier
       - if node coontains goal state , return the solution 
       - add the notde to the explored set.
       - Expand node , add resulting node to the frontier if they aren't already in the frontier or the explored set.



Stack: Last-in first out (Depth first Search)


Queue : first in first out (Breadth first search)








  




