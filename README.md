# Tower-of-Hanoi-Visualizer
Concept: Recursively solve Tower of Hanoi.


📌 Project Explanation

 This is a C++ program that solves the classic Tower of Hanoi problem using recursion.
  
The Tower of Hanoi is a mathematical puzzle where You have 3 rods (A, B, C).
  
You have n disks of different sizes stacked in decreasing size on rod A.
  
 The objective is to move all disks from rod A to rod C, following these rules:
   
 - Only one disk can be moved at a time. 
 - A disk can only be placed on top of a larger disk or on an empty rod. 
 - You must use the third rod (auxiliary rod) to assist. 

Your program uses recursion:
- Move n-1 disks from the source rod → auxiliary rod.
- Move the last (largest) disk from source rod → destination rod.
- Move the n-1 disks from auxiliary rod → destination rod.


📌 Features

✅ Implements recursion to solve Tower of Hanoi.

✅ Displays step-by-step moves required to solve the puzzle.

✅ Works for any number of disks (you can change N in main()).

✅ Very lightweight — uses only standard C++ (iostream & recursion).


📌 Example Output (for N = 3)
- Move disk 1 from rod A to rod C
  
- Move disk 2 from rod A to rod B

- Move disk 1 from rod C to rod B

- Move disk 3 from rod A to rod C

- Move disk 1 from rod B to rod A

- Move disk 2 from rod B to rod C

- Move disk 1 from rod A to rod C

This shows 7 moves, which matches the formula 2^N - 1 = 2^3 - 1 = 7.


📌 How to Run the Project

1. Save the Code

- Save the file as tower_of_hanoi.cpp.

2. Compile the Code

- Open a terminal and run:
 g++ tower_of_hanoi.cpp -o tower_of_hanoi

3. Run the Program
./tower_of_hanoi

4. Change Number of Disks

- int N = 3;   
