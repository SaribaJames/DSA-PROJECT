# BinaryTree Implementation in C++

## Project Overview
This project implements a basic Binary Tree (BST) in C++ that supports the following operations:
- **Insertion**: Add new elements to the tree.
- **Deletion**: Remove elements from the tree.
- **Search**: Find elements in the tree.
- **Traversal**: Display the elements of the tree in Inorder, Preorder, and Postorder sequences.

The project also includes a user interaction system that allows the user to perform operations through a simple command-line interface.

## Features
1. **Insert**: Insert one or multiple values into the tree.
2. **Delete**: Delete a specified value from the tree.
3. **Search**: Search for a specific value in the tree and get feedback on whether it exists.
4. **Traversal**: Perform Inorder, Preorder, or Postorder traversal of the tree and display the result.
5. **User Interaction**: Interactive menu for performing the above operations.

## How to Use
### Compilation
To compile the program, use a C++ compiler such as `g++`. Run the following command in your terminal:
```bash
g++ -o binary_tree binary_tree.cpp

###Running the Program
Once compiled, run the program:

./binary_tree


You will be prompted with the following menu:
1. Insert
2. Inorder Traversal
3. Preorder Traversal
4. Postorder Traversal
5. Search
6. Delete
7. Exit
Enter your choice:


###Commands

Insert: You can insert multiple values by entering them separated by spaces. For example:

Enter values to insert (separated by spaces): 10 20 30


Inorder Traversal: Displays the tree elements in inorder (left, root, right).
Preorder Traversal: Displays the tree elements in preorder (root, left, right).
Postorder Traversal: Displays the tree elements in postorder (left, right, root).
Search: Enter a value to search in the tree. The program will output whether the value is found or not.
Delete: Enter a value to delete from the tree. The tree will be updated, and the value will be removed.
Exit: Terminates the program.


Example Session

Default values inserted: 23, 45, 56, 78, 65, 98

1. Insert
2. Inorder Traversal
3. Preorder Traversal
4. Postorder Traversal
5. Search
6. Delete
7. Exit
Enter your choice: 2
Inorder traversal: 23 45 56 65 78 98

Enter your choice: 5
Enter value to search: 45
Found

Enter your choice: 6
Enter value to delete: 45

Enter your choice: 2
Inorder traversal: 23 56 65 78 98

