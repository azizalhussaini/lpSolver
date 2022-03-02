# lpSolver

The software needs the following inputs from the user:

Variables:

	x1,x2,x3,x4,y1,y2,y3,y4

variables.
	
Objective Type:

	minimize
	
Objective Function:

	6x1+5x2+6x3+5x4+1000y1+600y2+600y3+600y4
	
Constraints:

	21x1+21x2+9x3+21x4>=12000
	 x1<=10000y1
	 x2<=10000y2
	 x3<=10000y3
	 x4<=10000y4
	 y1>=0
	 y2>=0
	 y3>=0
	 y4>=0
	 y1<=1
	 y2<=1
	 y3<=1
	 y4<=1
	 

side and the constant on the RIGHT hand side. Following symbols can be used for the constraints:
	
	==    for equal to type constraint
	
	<=    for less than or equal to type constraint
	
	>=    for greater than or equal to type constraint



The software gives the following output:

The LP model:

	On the left output panel, you will see the LP that was solved.
	
The LP status:

	Optimal, unbounded, undefined(or infeasible)
	
The LP solution: 

	On the right output panel, you will see the LP solution.

For any doubts or debugging, kindly email mnusyed AT gmail DOT com.

The "lpSolver" is a GUI developed using TKINTER package. The GUI takes input from user (with the help of SYMPY) that is required to solve an LP.
Internally, PULP package is called to develop an LP. Then the LP is solved via GLPK solver. 
All repositories used in this application are open source. You are allowed to modify and reuse the GUI. 
Kindly do not remove this note from the software. 
If you find any legal issues with the software, then kindly let me know. The issues will be resolved ASAP.
