# binary_search_tree

BST is a collection of nodes arranged in a way where they maintain BST properties. Each node has a key and an associated value. While searching, the desired key is compared to the keys in BST and if found, the associated value is retrieved.

 ![alt text](https://www.tutorialspoint.com/data_structures_algorithms/images/binary_search_tree.jpg)


# Basic Operations

Following are the basic operations of a tree −  
Search − Searches an element in a tree.  
Insert − Inserts an element in a tree.  
Pre-order Traversal − Traverses a tree in a pre-order manner.  
In-order Traversal − Traverses a tree in an in-order manner.  
Post-order Traversal − Traverses a tree in a post-order manner.  


Node  
Define a node having some data, references to its left and right child nodes.

struct node {  
   int data;     
   struct node *leftChild;  
   struct node *rightChild;  
};
