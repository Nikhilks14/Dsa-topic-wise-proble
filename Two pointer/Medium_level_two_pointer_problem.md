
<div style="color: blue;"><h1>🔵 MEDIUM – LEVEL PROBLEM :</h1></div>
<div ><h2>1. Problem: Trapping Rain Water</h2></div>
Given n non-negative integers representing an elevation map where the width of each bar is 1, compute how much water it can trap after raining.
Constraints:

The input array height is not empty.
<h3>Example 1:</h3>
Input: height = [0,1,0,2,1,0,1,3,2,1,2,1]
Output: 6

Explanation: The elevation map can trap 6 units of water.

<h3  >Example 2:</h3>
Input: height = [4,2,0,3,2,5]
Output: 9

Explanation: The elevation map can trap 9 units of water.

<div ><h2>2. Problem: Linked List Cycle II</h2></div>
Given a linked list, return the node where the cycle begins. If there is no cycle, return null.
Constraints:

The number of nodes in the list is in the range [0, 10^4].
-10^5 <= Node.val <= 10^5
<h3  >Example 1:</h3>
Input: head = [3,2,0,-4], pos = 1 (1-indexed)
Output: Node with value 2

Explanation: The linked list contains a cycle, and the cycle starts at node with value 2.

<h3  >Example 2:</h3>
Input: head = [1,2], pos = 0 (1-indexed)
Output: null

Explanation: The linked list does not contain a cycle.

 
<div ><h2>3. Problem: Container With Most Water II</h2></div>
Given an m x n grid representing an elevation map where the width of each cell is 1, compute how much water it can trap after raining.
Constraints:

m == grid.length
n == grid[i].length
1 <= m, n <= 100
0 <= grid[i][j] <= 100
<h3  >Example 1:</h3>
Input: grid = [[0,1,0,0],[1,1,1,0],[0,1,0,0],[1,1,0,0]]
Output: 3

Explanation: The elevation map can trap 3 units of water.

<h3  >Example 2:</h3>
Input: grid = [[1,2,3,4],[5,6,7,8],[9,10,11,12],[13,14,15,16]]
Output: 0

Explanation: The elevation map cannot trap any water.

<div ><h2>4. Problem: Longest Palindromic Substring</h2></div>
Given a string s, return the longest palindromic substring in s.
Constraints:

1 <= s.length <= 1000
s consist of only digits and English letters (lower-case and/or upper-case),
<h3  >Example 1:</h3>
Input: s = "babad"
Output: "bab" or "aba"

Explanation: Both "bab" and "aba" are valid longest palindromic substrings.

<h3  >Example 2:</h3>
Input: s = "cbbd"
Output: "bb"

Explanation: The longest palindromic substring is "bb".

 
<div ><h2>5. Problem: 3Sum Closest</h2></div>
Given an array nums of n integers and an integer target, find three integers in nums such that the sum is closest to target. Return the sum of the three integers.
Constraints:

3 <= nums.length <= 1000
-10^3 <= nums[i] <= 10^3
-10^4 <= target <= 10^4
<h3  >Example 1:</h3>
Input: nums = [-1,2,1,-4], target = 1
Output: 2

Explanation: The sum that is closest to the target is 2 (-1 + 2 + 1).

<h3  >Example 2:</h3>
Input: nums = [0,0,0], target = 1
Output: 0

Explanation: The sum that is closest to the target is 0 (0 + 0 + 0).

<div ><h2>6. Problem: Valid Palindrome II</h2></div>
Given a non-empty string s, you may delete at most one character. Judge whether you can make it a palindrome.
Constraints:

1 <= s.length <= 2 * 10^5
s consists only of printable ASCII characters.
<h3  >Example 1:</h3>
Input: s = "aba"
Output: true

Explanation: "aba" is already a palindrome.

<h3  >Example 2:</h3>
Input: s = "abca"
Output: true

Explanation: You can delete the character 'c' to make "abca" a palindrome.

 
<div ><h2>7. Problem: Longest Substring with At Most K Distinct Characters</h2></div>
Given a string s and an integer k, return the length of the longest substring of s that contains at most k distinct characters.
Constraints:

1 <= s.length <= 5 * 10^4
0 <= k <= 50
<h3  >Example 1:</h3>
Input: s = "eceba", k = 2
Output: 3

Explanation: The substring "ece" contains at most 2 distinct characters.

<h3  >Example 2:</h3>
Input: s = "aa", k = 1
Output: 2

Explanation: The substring "aa" contains at most 1 distinct character.

<div ><h2>8. Problem: Minimum Window Substring</h2></div>
Given two strings s and t, return the minimum window in s which will contain all the characters in t. If there is no such window in s that covers all characters in t, return the empty string "".
Constraints:

1 <= s.length, t.length <= 10^5
s and t consist of English letters.
<h3  >Example 1:</h3>
Input: s = "ADOBECODEBANC", t = "ABC"
Output: "BANC"

Explanation: The minimum window substring containing all characters in "ABC" is "BANC".

<h3  >Example 2:</h3>
Input: s = "a", t = "a"
Output: "a"

Explanation: The minimum window substring containing all characters in "a" is "a".

 
<div ><h2>9. Problem: Valid Palindrome III</h2></div>
Given a string s and an integer k, return true if s is a k-palindrome.
A string is k-palindrome if it can be transformed into a palindrome by removing at most k characters from it.

Constraints:

1 <= s.length <= 1000
s consists of only lowercase English letters.
1 <= k <= s.length
<h3  >Example 1:</h3>
Input: s = "abcdeca", k = 2
Output: true

Explanation: Remove 'b' and 'd' to get "aceca", which is a palindrome.

<h3  >Example 2:</h3>
Input: s = "x", k = 0
Output: true

Explanation: The string itself is a palindrome.

<div ><h2>10. Problem: Reverse Vowels of a String</h2></div>
Write a function that takes a string as input and reverse only the vowels of a string.
Constraints:

The vowels do not include the letter "y".
1 <= s.length <= 1000
<h3  >Example 1:</h3>
Input: s = "hello"
Output: "holle"

Explanation: The vowels in the string are 'e' and 'o'. Reverse them to get "holle".

<h3  >Example 2:</h3>
Input: s = "leetcode"
Output: "leotcede"

Explanation: The vowels in the string are 'e', 'o', and 'e'. Reverse them to get "leotcede".

 
<div ><h2>11. Problem: Longest Substring Without Repeating Characters</h2></div>
Given a string s, find the length of the longest substring without repeating characters.
Constraints:

The input string s consists of English letters, digits, symbols, and spaces.
<h3  >Example 1:</h3>
Input: s = "abcabcbb"
Output: 3

Explanation: The longest substring without repeating characters is "abc", with a length of 3.

<h3  >Example 2:</h3>
Input: s = "bbbbb"
Output: 1

Explanation: The longest substring without repeating characters is "b", with a length of 1.

<div ><h2>12. Problem: Squares of a Sorted Array</h2></div>
Given an integer array nums sorted in non-decreasing order, return an array of the squares of each number sorted in non-decreasing order.
Constraints:

The input array nums is not empty.
-10^4 <= nums[i] <= 10^4
<h3  >Example 1:</h3>
Input: nums = [-4, -1, 0, 3, 10]
Output: [0, 1, 9, 16, 100]

Explanation: The squares of the numbers are [16, 1, 0, 9, 100], which are sorted in non-decreasing order.

<h3  >Example 2:</h3>
Input: nums = [-7, -3, 2, 3, 11]
Output: [4, 9, 9, 49, 121]

Explanation: The squares of the numbers are [49, 9, 4, 9, 121], which are sorted in non-decreasing order.

 
<div ><h2>13. Problem: Merge Sorted Array</h2></div>
Given two sorted integer arrays nums1 and nums2, merge nums2 into nums1 as one sorted array.
Constraints:

The number of elements initialized in nums1 and nums2 are m and n, respectively.
You may assume that nums1 has a size equal to m + n such that it has enough space to hold additional elements from nums2.
<h3  >Example 1:</h3>
Input: nums1 = [1, 2, 3, 0, 0, 0], m = 3, nums2 = [2, 5, 6], n = 3
Output: [1, 2, 2, 3, 5, 6]

Explanation: Merge nums2 into nums1 as [1, 2, 2, 3, 5, 6].

<h3  >Example 2:</h3>
Input: nums1 = [1], m = 1, nums2 = [], n = 0
Output: [1]

Explanation: Merge nums2 into nums1 as [1].


