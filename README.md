# Divisible-sum-pairs
Divisible Sum Pairs


You are given an array of n integers,ar=[ar[0],ar[1]..a[n-1]] , and a positive integer,k . Find and print the number of  pairs(i,j) where i<j and ar[i] + ar[j] is divisible by .

For example, ar=[1,2,3,4,5,6] andk=5 . Our three pairs meeting the criteria are[1,4],[2,3]  and[4,6] .

Function Description

Complete the divisibleSumPairs function in the editor below. It should return the integer count of pairs meeting the criteria.

divisibleSumPairs has the following parameter(s):

n: the integer length of array 
ar: an array of integers
k: the integer to divide the pair sum by
Input Format

The first line contains 2 space-separated integers, n and k. 
The second line contains n space-separated integers describing the values of[ar[0],ar[1],..ar[n-1]] .


Output Format

Print the number of(i,j)  pairs where i<j and ar[i] +ar[j]  is evenly divisible by k.

Sample Input

6 3
1 3 2 6 1 2

Sample Output

 5
