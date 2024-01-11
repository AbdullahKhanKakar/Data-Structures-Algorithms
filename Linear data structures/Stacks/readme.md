# Stacks:
In given notebook, I created stacks and also solve some problems related to stacks. These problems are given below:

### Q1: Reverse the given string?

**Sample Input:** Hello
**Sample Output:** olleH

### Q2: Stack Undo Redo?
Two inputs will be given; one consist of String, second consist of undo redo. Undo will remove the last item and Redo will return the last item.

**Sample Input:** String: "Hello", Undo_Redo: "uruur"
**Sample Output:** Hell

### Q3: Find Celebrity?
A square matrix will be given, we need to find **celebrity**. A celebrity is person who don't know anyone, but all peoples know them.

**Sample Input:**
  
----**A B C D**
  
**A** [0 0 1 1]

**B** [0 0 1 1]

**C** [1 0 0 1]

**D** [0 0 0 0]

Here, 0,1,2,3 are four peoples in form A,B,C,D. See in the matrix. A knows to C,D. B knows to C,D. C knows to A,D. D knows to no people.

**Sample Output:**
3

- Answer is 3 which represents D, because D know to no people but all other peoples A,B,C knows to D.

**Assumptions:**
- Only 1 celebrity is possible.
- It may possible that will be no celebrity.

### Q4: Check whether the brakets are both opened and closed. If yes, returns True otherwise False?

> I try me best to solve this brakets matching problem, but unable to solve it. If you will solve it, then share me on Linkedin inbox. 

**Sample Input:** {(a+b)+[b]}  
**Sample Output:** True

**Sample Input:** {(a+b+{b]}  
**Sample Output:** False
