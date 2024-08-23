2024-08-15 15:06

Status:

Tags: [[Data Structures]]

# Arrays
An array is a contiguous allocation of memory of an immutable size. Think of it like a ruler of a certain length, with each marked interval being a slot that you can store something in. 

In order to resize an array, you need to allocate an entirely new array in memory and blank out the old one after copying over the relevant information. This can be solved with [[Vectors]], which double in size every time they become half full, therefore serving as a less efficient data structure when the size is known.

# References