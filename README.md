# Singly Linked List Operations 

## Overview
This README provides detailed descriptions of the singly linked list operations you can perform. A singly linked list is a linear data structure consisting of nodes where each node contains data and a reference to the next node in the sequence. The operations covered include appendNode(), prependNode(), insertNodeAfter(), deleteNodeByKey(), updateNodeByKey(), print(), and clearScreen().

## Singly Linked List Operations

### appendNode(newNode)
Adds a node to the end of the linked list.
- *Parameters:* 
  - newNode: The node to be added to the linked list.
- *Returns:* None
- *Description:* This method places the specified node at the end of the linked list. If the list is empty, the new node becomes the head.

### prependNode(newNode)
Adds a node to the beginning of the linked list.
- *Parameters:* 
  - newNode: The node to be added to the linked list.
- *Returns:* None
- *Description:* This method places the specified node at the beginning of the linked list. The new node becomes the head of the list.

### insertNodeAfter(existingNodeKey, newNode)
Inserts a new node after a specified node in the linked list.
- *Parameters:* 
  - existingNodeKey: The key of the existing node after which the new node should be inserted.
  - newNode: The new node to be inserted.
- *Returns:* None
- *Description:* This method inserts the new node after the node with the specified key. If the specified node is not found, an appropriate error or exception is raised.

### deleteNodeByKey(key)
Deletes a node from the linked list by its key.
- *Parameters:* 
  - key: The key of the node to be deleted.
- *Returns:* None
- *Description:* This method removes the node with the specified key from the linked list. If the node with the specified key is not found, an appropriate error or exception is raised.

### updateNodeByKey(key, newData)
Updates the data of a node identified by its key.
- *Parameters:* 
  - key: The key of the node to be updated.
  - newData: The new data to be updated in the node.
- *Returns:* None
- *Description:* This method updates the data of the node with the specified key. If the node with the specified key is not found, an appropriate error or exception is raised.

### print()
Prints all nodes in the linked list.
- *Parameters:* None
- *Returns:* A list of all nodes' data in the linked list.
- *Description:* This method traverses the linked list and prints the data of each node, providing a way to see the current state of the list.

### clearScreen()
Clears the screen or console output.
- *Parameters:* None
- *Returns:* None
- *Description:* This method clears the console output, providing a clean view for subsequent operations.

## Example Usage
Here's an example of how these singly linked list operations might be used in practice:

1. *Initialize the Linked List*
   - Create an empty linked list.
2. *Append Nodes*
   - Add nodes to the end of the linked list using the appendNode() method.
3. *Prepend Nodes*
   - Add nodes to the beginning of the linked list using the prependNode() method.
4. *Insert Nodes After Specific Nodes*
   - Insert a new node after a specified node using the insertNodeAfter() method.
5. *Delete Nodes by Key*
   - Remove nodes from the linked list by their key using the deleteNodeByKey() method.
6. *Update Nodes by Key*
   - Update the data of nodes identified by their key using the updateNodeByKey() method.
7. *Print the Linked List*
   - Print all nodes in the linked list using the print() method.
8. *Clear Screen*
   - Clear the console output using the clearScreen() method.

This README provides a clear understanding of the singly linked list operations and their purposes. Make sure to handle any potential errors or exceptions, especially when performing operations on non-existent nodes.
