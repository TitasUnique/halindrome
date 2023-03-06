Halindrome
Given a string S, divide it into two equal parts S1 and S2.
S is called a halindrome if at least any one of the following condition

1.S is a palindrome and length of S>=2.
2. S1 is a halindrome.
3. S2 is a halindrome.

Your task is to find and return the number of halindromes in an array string.
Note: In the case of an odd length string, the middle element is not present in both string then middle element is m, then, S1 = S [0, m-1] and S2 = S [m+1, SI-1].

Input Specification
input 1: An integer value denoting the number of strings (1<=input)
input 2: A string array of size input1 (2 <= length of each string <=1)

Output Specification -
Return the number of strings which are halindromes.

Example 1 -

input1: 4
input2: {hahshs,ccc,as,hah}

Output: 3

Explanation:
There are four strings.
String 1
1. String S = hahshs is not forming a palindrome.
2. String S1 = hah, is a halindrome.
As second condition is true, string1 is a halindrome.

String 2
1. String S = ccc is forming a palindrome.
Since the first condition is true, string2 is a halindrome.

String 3
1. String S = as, it is not forming a palindrome and we cannot check if length of string3 is 2. Therefore, string3 is not a halindrome.

String 4
1. String Shah is forming a palindrome.
As at least 1 condition is true, string4 is a halindrome.
Since three strings in the array are halindromes, 3 is returned as the output.
