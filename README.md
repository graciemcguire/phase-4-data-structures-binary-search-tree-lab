# Binary Search Tree Lab

## Learning Goals

- Implement an `#insert` method in the `BinarySearchTree` class
- Implement a `#search` method in the `BinarySearchTree` class

## Introduction

Now that you have learned about Binary Search Trees, it's time to put your
knowledge to the test!

Fork and clone this lab; you'll be coding in the `lib` folder. You can
run the tests at any point using `learn test` to check your work.

## Instructions

Write a method `BinarySearchTree#insert` that inserts a new node into the tree, and
then returns the tree. The `#insert` method should insert nodes regardless of
the tree's existing size, and should not allow duplicate nodes to be inserted.

For example:

- Input: `BinarySearchTree.insert(5)`
- Output: ``

- Input:  `BinarySearchTree.insert(11)`
- Output: ``

Write a method `BinarySearchTree#search` that takes in a target value and
searches for that value in the tree. If the value is found it should return the
node with the target value, and if it is not found it should return `nil`.

- Input:  `BinarySearchTree.search(11)`
- Output: `<Node>.value == 11`

- Input:  `BinarySearchTree.search(100)`
- Output: `nil`