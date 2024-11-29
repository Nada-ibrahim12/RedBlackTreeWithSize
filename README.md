# RedBlackTreeWithSize

# Red-Black Tree Implementation in C++  

## Description  
This project is a C++ implementation of a **Red-Black Tree**, a self-balancing binary search tree that ensures logarithmic time complexity for insertion, deletion, and lookup operations. The implementation includes additional functionality, such as **OS_RANK** for order statistics and dynamic tree size tracking.  

### Features  
- **Insertion**: Add new nodes while maintaining Red-Black Tree properties.  
- **Deletion**: Remove nodes with adjustments to preserve balance.  
- **Search**: Look up values in the tree in logarithmic time.  
- **OS_RANK**: Efficiently retrieve the rank of a value in the tree (i.e., its position in sorted order).  
- **Select**: Retrieve elements based on their rank (order statistic).  
- **Tree Size**: Dynamically track and return the size of the tree.  

## Installation and Usage  

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-username/RedBlackTree-CPP.git
   cd RedBlackTree-CPP
2. **Build the Project**
   ```Use any C++ compiler (e.g., g++).
   g++ -o rbtree main.cpp
3. **Run the Program**
    ./rbtree
