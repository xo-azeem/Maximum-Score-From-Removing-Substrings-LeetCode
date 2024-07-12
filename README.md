# Maximum Score From Removing Substrings

LeetCode Q # 1717.

You are given a string s and two integers x and y. You can perform two types of operations any number of times.

- Remove substring "ab" and gain x points.</br>
&nbsp;&nbsp; - For example, when removing "ab" from "cabxbae" it becomes "cxbae".</br>
- Remove substring "ba" and gain y points.</br>
&nbsp;&nbsp; - For example, when removing "ba" from "cabxbae" it becomes "cabxe".</br>
- Return the maximum points you can gain after applying the above operations on s.

Example 1:

> Input: s = "cdbcbbaaabab", x = 4, y = 5</br>
> Output: 19</br>
> Explanation:</br>
> - Remove the "ba" underlined in "cdbcbbaaabab". Now, s = "cdbcbbaaab" and 5 points are added to the score.</br>
> - Remove the "ab" underlined in "cdbcbbaaab". Now, s = "cdbcbbaa" and 4 points are added to the score.</br>
> - Remove the "ba" underlined in "cdbcbbaa". Now, s = "cdbcba" and 5 points are added to the score.</br>
> - Remove the "ba" underlined in "cdbcba". Now, s = "cdbc" and 5 points are added to the score.</br>
> Total score = 5 + 4 + 5 + 5 = 19.</br>

Example 2:

> Input: s = "aabbaaxybbaabb", x = 5, y = 4</br>
> Output: 20

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/user-attachments/assets/e6a8ce25-5d9a-42f7-989f-ff62ce4812ea)

  Time complexity: O(n).</br>Space complexity: O(1).
</div>
