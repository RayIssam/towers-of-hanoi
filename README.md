# Towers Of Hanoi


# TOWER OF HANOI PROBLEM: AN ALGORITHMIC ANALYSIS
- The Tower of Hanoi is a classic problem in computer science and mathematics.
- Proposed by the French mathematician Edouard Lucas in 1883.
- This project focuses on the algorithmic analysis of solving the Tower of Hanoi problem.

 # PROBLEM STATEMENT
- Definition of the Tower of Hanoi problem:
  - Three pegs and a number of disks of different sizes.
  - The puzzle starts with the disks in a neat stack in ascending order of size on one peg, the smallest at the top.

#  Features
* Recursive Algorithm: Utilizes recursive logic to solve the Tower of Hanoi puzzle.
* Iterative Algorithm: Implements an iterative approach for Tower of Hanoi problem-solving.
* User Interface: Provides a graphical user interface to input the number of discs and select the solving algorithm.
  


# OBJECTIVE
- The primary objective:
  - Move the entire stack to another peg, obeying the following simple rules:
    1. Only one disk can be moved at a time.
    2. Each move consists of taking the upper disk from one of the stacks and placing it on top of another stack or an empty peg.
    3. No disk may be placed on top of a smaller disk.

# GUI screenshots 
* RECURSIVE APPROACH
<img width="319" alt="image" src="https://github.com/RayIssam/towers-of-hanoi/assets/105173457/37a7e609-adba-4ac4-a5d6-b563d8367c22">

* ITERATIVE APPROACH
<img width="318" alt="image" src="https://github.com/RayIssam/towers-of-hanoi/assets/105173457/651d61b9-39ad-4e15-8c70-39e68a076ec2">

# Usage
- To run the program:

1- Ensure Python 3 is installed.
2- Execute the script tower_of_hanoi.py.

# CONCLUSION OF THE PERFORMANCE COMPARISON

1. Performance Analysis

Small Values of n:
No significant differences observed between recursive and iterative approaches.
Large Values of n:
Iterative approach tends to be faster due to lower overhead.
Unexpected Findings:
In my experiments, the recursive approach often demonstrated slightly faster performance with large values of n.
