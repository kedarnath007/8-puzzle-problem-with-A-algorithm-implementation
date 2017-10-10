--------------------
Compiler
--------------------

javac           (compiler)

---------------------------------
Command Line Execution
---------------------------------
	  javac State.java 		(Compiling)
	  javac Solution.java 		(Compiling)

	  java Solution			 (Running)

---------------------------------
Input/Output
---------------------------------

Input: Initial and goal state. (The input should be a number between 1 to 8 and the blank tile is represented by a space. 
Each element in initial and goal state should be given in a different line.)

Output: All the expanded nodes with f(n), h(n) and g(n) values will be displayed. 
Additionally, total number of nodes expanded and total number of nodes genrated will also be displayed.

------------------------------
Steps for running the program
------------------------------

Input the initial and goal states. The elements should be valid (numbers between 1 to 8 and space for blank tile), 
else the program will display an error message and terminated.

------------------
Sample Output 
------------------

Please input the elements for initial state:
 
1
3
4
2
5
7
8
6
Please input the Goal state:
1
2
3
4
5
6
7
8

Below are the nodes expanded:
	1	3	
4	2	5	
7	8	6	

f(n) :4
h(n) :4
g(n) :0


1	 	3	
4	2	5	
7	8	6
	
f(n) :4
h(n) :3
g(n) :1


1	2	3	
4	 	5	
7	8	6
	
f(n) :4
h(n) :2
g(n) :2



1	2	3	
4	5	 	
7	8	6
	
f(n) :4
h(n) :1
g(n) :3


1	2	3	
4	5	6	
7	8
	 	
f(n) :4
h(n) :0
g(n) :4


Total Nodes expanded :5
Total Nodes generated:10
Time Taken in milli seconds: 6


