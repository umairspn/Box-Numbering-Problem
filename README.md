# Box-Numbering-Problem
This is a real-world box-numbering problem that I encountered in a technical coding interview (Interview Question). 

### Language Used
Python Programming Languge 

### Tool Used
Jupyter Notebook 


## Task Description 
Create an efficient algorithm that takes customer orders and calculate the Min. number of boxes that should be used to pack all the products requested by customers. The input and output of this problem is specified with a certain complexity.   

### Understanding the Problem
The problem at it's core is not too difficult, but requires some time to understand the flow of data within a bunch of hash within hash, and performing accurate calculations and returning them in the right format. 

### Complexity
Time Complexity: O(N * M) where N is the size of input (Products) and N is the size of input (Customer Order) 

Space Complexity: O(N * M) since we need to return both (Product Details) along with (Customer Order Details) as the output  

### Code Optimization/Cleaning 
The code is optimized to a certain extent though there is a lot of room for improvement. 
For starters, in this version, we sort the input dictionary evertime on the go, instead, we can simply sort the entire input once, and continue the operations. 
Secondly, for code readiness, using a separate function for every repititive step is very helpful and makes the code easy to read and understand. 

### Possible Extensions/Clarifications
This problem can be extended and has a very broad scope. Based on certain reqruiemetns, we can assume:
1. We can use a box for packing several times 
2. We can place restrictions on the order Size 
3. We need to check if we have a certain amount of boxes for a large order or not (Edge Case) 
4. The selection of boxes can be optimized further (Brainstorming currently) 
