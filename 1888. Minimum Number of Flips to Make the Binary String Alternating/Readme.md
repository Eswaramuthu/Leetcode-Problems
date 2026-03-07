<h2><a href="https://leetcode.com/problems/minimum-number-of-flips-to-make-the-binary-string-alternating/">1888. Minimum Number of Flips to Make the Binary String Alternating</a></h2><h3>Medium</h3><hr><div><p>You are given a binary string <code>s</code>. You are allowed to perform two types of operations on the string in any sequence:</p>
<ul>
	<li><strong>Type-1:</strong> Remove the character at the start of the string <code>s</code> and append it to the end of the string.</li>
	<li><strong>Type-2:</strong> Pick any character in <code>s</code> and flip its value, i.e., if its value is <code>'0'</code> it becomes <code>'1'</code> and vice-versa.</li>
</ul>
<p>Return the minimum number of type-2 operations you need to perform such that <code>s</code> becomes alternating.</p>
<p>The string is called <strong>alternating</strong> if no two adjacent characters are equal. For example, the strings <code>"010"</code> and <code>"1010"</code> are alternating, while the string <code>"0100"</code> is not.</p>
<p>&nbsp;</p>
<p><strong class="example">Example 1:</strong></p>
<pre><strong>Input:</strong> s = "111000"
<strong>Output:</strong> 2
<strong>Explanation:</strong> Use the first operation two times to make s = "100011". Then, use the second operation on the third and sixth elements to make s = "101010".
</pre><p><strong class="example">Example 2:</strong></p>
<pre><strong>Input:</strong> s = "010"
<strong>Output:</strong> 0
<strong>Explanation:</strong> The string is already alternating.
</pre><p><strong class="example">Example 3:</strong></p>
<pre><strong>Input:</strong> s = "1110"
<strong>Output:</strong> 1
<strong>Explanation:</strong> Use the second operation on the second element to make s = "1010".
</pre>
<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>
<ul>
	<li><code>1 &lt;= s.length &lt;= 10<sup>5</sup></code></li>
	<li><code>s[i]</code> is either <code>'0'</code> or <code>'1'</code>.</li>
</ul>
</div>

---

## Examples

**Example 1:**
```
Input: s = "111000"
Output: 2
Explanation: Use the first operation two times to make s = "100011".
Then, use the second operation on the third and sixth elements to make s = "101010".
```

**Example 2:**
```
Input: s = "010"
Output: 0
Explanation: The string is already alternating.
```

**Example 3:**
```
Input: s = "1110"
Output: 1
Explanation: Use the second operation on the second element to make s = "1010".
```

---

## Constraints

- `1 <= s.length <= 10⁵`
- `s[i]` is either `'0'` or `'1'`.