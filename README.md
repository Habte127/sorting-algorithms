# Pointer-Based Bubble Sort

## Student Information

Name: Habtamu Ayele  
Student Id: RMNS-9485/-23  
Course: Data Structure and Algorithm  

## Algorithm  
1. Input: A vector of integers arr.  
2. Edge Case Handling: The code does not explicitly handle empty vectors. Ensure the input vector is non-empty.  
3. Pointer-Based Bubble Sort Implementation:  
   - Traverse the vector using nested loops.  
   - Use a pointer ptr to point to the current element during comparisons.  
   - Compare adjacent elements. If *ptr > arr[j + 1], swap them using pointer dereferencing.  
   - Repeat until the entire vector is sorted in ascending order.  

## How to Run the Code  
1. Clone the repository to your local machine.  
2. Open the terminal and navigate to the repository directory.  
3. Compile the C++ code:  
   `bash  
   g++ main.cpp -o main
