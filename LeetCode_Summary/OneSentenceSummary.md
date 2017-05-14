# One Sentence Summary

| No.| Description | Summary |
| ------| ----------- | ----------- |
| 001   | Two Sum | O(N) and O(N): Hash Table <br> O(NlogN) and O(1): Sort and two pointers |   
| 015   | 3 Sum | Sort -> solve two sum using two pointers for each first element & avoid duplicated solutions |     
| 049   | Group Anagrams | Sort string -> convert list to tuple/string -> store in hash table as key, append original unsorted string as value | 
| 053   | Maximum Subarray | DP: maxEndingHere and maxSoFar |
| 122   | Best Time to Buy and Sell Stock II | Greedy: Buy/sell whenever profitable |
| 138   | Copy List with Random Pointer | Hash Table: key is old node and value is copied node, one pass to create new node, assign next and random |
| 219   | Contains Duplicate II | Hash Table: enumerate the array, key is the number and value if the index|
| 17    | Letter Combination of a Phone Number | Recursive: [x+y for x in self.fun(digits[:-1]) for y in self.fun(digits[-1])] or list(d[digits]); Iterative: two for loops for x+y


