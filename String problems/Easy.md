<h1>🔵 EASY – LEVEL PROBLEM :</h1>

## Problem 1: Valid Palindrome II

**Description:** Given a string, write a function to determine if it is a valid palindrome. You may delete at most one character to make it a palindrome.

**Example 1:**

        Input: `"aba"`

        Output: `True`

**Explanation:** The string "aba" is already a palindrome.

**Example 2:**

        Input: `"abca"`

        Output: `True`

**Explanation:** By removing 'c', the string "abca" becomes a palindrome ("aba").

**Constraints:**
- The input string will consist of only lowercase letters.
- The length of the string will not exceed 5000.

---

## Problem 2: Longest Substring Without Repeating Characters

**Description:** Given a string, find the length of the longest substring without repeating characters.

**Example 1:**

        Input: `"abcabcbb"`

        Output: `3`

**Explanation:** The longest substring without repeating characters is "abc".

**Example 2:**

        Input: `"bbbbb"`

        Output: `1`

**Explanation:** The longest substring without repeating characters is "b".

**Constraints:**
- The input string will consist of only lowercase and uppercase letters.
- The length of the string will not exceed 10^4.

---

## Problem 3: Minimum Window Substring

**Description:** Given two strings, S, and T, find the minimum window in S, which will contain all the characters in T.

**Example 1:**

            Input: S = `"ADOBECODEBANC"`, T = `"ABC"`

            Output: `"BANC"`

**Explanation:** The minimum window containing all characters in T is "BANC".

**Example 2:**

            Input: S = `"a"`, T = `"aa"`
            Output: `""`

**Explanation:** There is no window containing all characters in T.

**Constraints:**
- The input strings will consist of only uppercase and lowercase letters.
- The length of the strings will not exceed 10^5.

---


---

## Problem 5: Group Shifted Strings

**Description:** Given a string array, group the strings that are shifted versions of each other.

**Example 1:**

        Input: `["abc", "bcd", "acef", "xyz", "az", "ba", "a", "z"]`
        Output: `[["abc","bcd","xyz"], ["az","ba"], ["acef"], ["a","z"]]`

**Explanation:** The strings "abc", "bcd", and "xyz" are shifted versions of each other.

**Example 2:**

        Input: `["abc", "am"]`
        Output: `[["abc"], ["am"]]`

**Explanation:** There are no shifted versions in this case.

**Constraints:**
- The input array will contain only lowercase letters.
- The length of the strings in the array will not exceed 100.

---

## Problem 6: Implement Trie (Prefix Tree)

**Description:** Implement a trie (prefix tree) with insert, search, and startsWith methods.

**Example 1:**

        Input:
        trie = Trie()
        trie.insert("apple")
        trie.search("apple") // Output: True
        trie.search("app") // Output: False
        trie.startsWith("app") // Output: True



**Example 2:**

    Input:
    trie = Trie()
    trie.insert("banana")
    trie.insert("bandana")

    trie.search("banana") // Output: True
    trie.startsWith("band") // Output: True
    trie.startsWith("banan") // Output: False



**Constraints:**
- The input strings consist only of lowercase letters.
- You must implement the trie without using built-in data structures.

---

## Problem 7: Valid Parentheses

**Description:** Given a string containing just the characters '(', ')', '{', '}', '[' and ']', determine if the input string is valid.

**Example 1:**

        Input: `"()"`
        Output: `True`

**Example 2:**

        Input: `"()[]{}"`
        Output: `True`

**Constraints:**
- The input string will only contain the characters '(', ')', '{', '}', '[' and ']'.
- The length of the string will not exceed 1000.

---

## Problem 8: Ransom Note

**Description:** Given two strings, ransomNote and magazine, return true if ransomNote can be constructed from the characters in the magazine, and false otherwise.

**Example 1:**

        Input: `ransomNote = "a", magazine = "b"`
        Output: `False`

**Example 2:**

        Input: `ransomNote = "aa", magazine = "aab"`
        Output: `True`

**Constraints:**
- The input strings will consist of only lowercase letters.
- The length of the strings will not exceed 1000.

---

## Problem 9: Longest Palindromic Substring

**Description:** Given a string s, find the longest palindromic substring in s. You may assume that the maximum length of s is 1000.

**Example 1:**

        Input: `"babad"`
        Output: `"bab"`

**Explanation:** "bab" is a palindromic substring of "babad".

**Example 2:**

        Input: `"cbbd"`
        Output: `"bb"`

**Explanation:** "bb" is a palindromic substring of "cbbd".

**Constraints:**
- The input string will consist of only lowercase and uppercase letters.
- The length of the string will not exceed 1000.

---

## Problem 10: ZigZag Conversion

**Description:** The string "PAYPALISHIRING" is written in a zigzag pattern on a given number of rows like this:

P A H N

A P L S I I G

Y I R


And then read line by line: "PAHNAPLSIIGYIR"

Write the code to convert a given string into a zigzag pattern with a given number of rows.

**Example 1:**

        Input: `s = "PAYPALISHIRING", numRows = 3`
        Output: `"PAHNAPLSIIGYIR"`

**Example 2:**

        Input: `s = "PAYPALISHIRING", numRows = 4`
        Output: `"PINALSIGYAHRPI"`

**Constraints:**
- The input string will consist of only uppercase and lowercase letters.
- The number of rows will be between 1 and 1000.