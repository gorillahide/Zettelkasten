2024-08-15 18:14
Status: #baby 
Tags: [[Computer Science]] 

# Sorting Problem
A problem in [[Computer Science]] which deals with how to sort.

### Definition

###### Input:  A sequence of $n$ numbers $\langle a_1, a_2, ..., a_n \rangle$
###### Output: A permutation (reordering)$\langle a_1 \prime, a_2 \prime, ..., a_n \prime \rangle$ of the input sequence such that  $\langle a_1 \prime \leq a_2 \prime \leq \ldots \leq a_n \prime \rangle$ .

That is, to say, it takes a possibly non ordered input and outputs a reordered permutation. For example, $\langle 36, 89, 57, 42 \rangle$ would be sorted to $\langle 36, 42, 57, 89 \rangle$. Such an input would be called an instance of the input. Generally speaking, an instance of a problem consists of the input satisfying whatever constraints are imposed in the problem statement needed to compute a solution to the problem. Notably, the numbers that we wish to sort are also known as [[keys]].

Because of sorting's importance as an intermediary step, we have a large number of good [[Sorting Algorithms]]. It is to be noted that there is no best sorting algorithm, as the best depends heavily on the use case and specifications. 

An algorithm is said to be correct, if for every input instance, it halts with the correct output. We say that a correct algorithm solves the given computational problem. [[Correctness (Computer Science)]] However, incorrect algorithms can still be of use if we can control their rate of error, which comes to light in sieving algorithms used to find [[Prime Numbers]].
# References
[[Introduction to Algorithms 3rd Edition]]
