# SwapNodes
This description is copied from the Hacker Rank Swap Nodes Problem Description.

Swap operation:

We define depth of a node as follows:

The root node is at depth 1.
If the depth of the parent node is d, then the depth of current node will be d+1.
Given a tree and an integer, k, in one operation, we need to swap the subtrees of all the nodes at each depth h, where h ∈ [k, 2k, 3k,...]. In other words, if h is a multiple of k, swap the left and right subtrees of that level.

You are given a tree of n nodes where nodes are indexed from [1..n] and it is rooted at 1. You have to perform t swap operations on it, and after each swap operation print the in-order traversal of the current state of the tree.

Function Description

Complete the swapNodes function in the editor below. It should return a two-dimensional array where each element is an array of integers representing the node indices of an in-order traversal after a swap operation.

swapNodes has the following parameter(s): 
- indexes: an array of integers representing index values of each node[i], beginning with node, the first element, as the root. 
- queries: an array of integers, each representing a k value.

Input Format 
The first line contains n, number of nodes in the tree.

Each of the next n lines contains two integers, a b, where a is the index of left child, and b is the index of right child of ith node.

Note: -1 is used to represent a null node.

The next line contains an integer, t, the size of queries . 
Each of the next t lines contains an integer queries[i], each being a value k.

Output Format 
For each k, perform the swap operation and store the indices of your in-order traversal to your result array. After all swap operations have been performed, return your result array for printing.
