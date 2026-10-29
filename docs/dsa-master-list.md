# DSA master list (88 problems)

One deduplicated list built from three sheets: **Core 70** (same as the 60-problem sheet), **Infosys SP/DSE 40** and **Amazon prep 45**.

**Rank** = how many sheets include the problem, then Amazon priority (P0 > P1 > P2), then Infosys block (1 > 4), then Core order. Solve in rank order when short on time.

Complexities are reference answers; write your own first.

| # | Problem | Level | Pattern | In sheets | Amazon | Time / Space | Practice |
|---|---|---|---|---|---|---|---|
| 1 | Two Sum | Easy | Complement Pattern | Core #15, Core #26, Infosys #6, Amazon #4 | P0 · High | `O(n)` / `O(n)` | [LC 1](https://leetcode.com/problems/two-sum/) |
| 2 | Kadane's Algorithm (Maximum Subarray) | Medium | DP Pattern | Core #17, Core #63, Infosys #8, Amazon #6 | P0 · High | `O(n)` / `O(1)` | [LC 53](https://leetcode.com/problems/maximum-subarray/) |
| 3 | Subarray Sum Equals K | Medium | Prefix Sum | Core #27, Core #70, Infosys #10, Infosys #40, Amazon #9 | P0 · Very High | `O(n)` / `O(n)` | [LC 560](https://leetcode.com/problems/subarray-sum-equals-k/) |
| 4 | Longest Substring Without Repeating Characters | Medium | Sliding Window (Expand–Shrink) | Core #30, Infosys #9, Amazon #11 | P0 · Very High | `O(n)` / `O(min(n,Σ))` | [LC 3](https://leetcode.com/problems/longest-substring-without-repeating-characters/) |
| 5 | Group Anagrams | Medium | Sorted Key | Core #33, Infosys #12, Amazon #8 | P0 · High | `O(n·k log k)` / `O(n·k)` | [LC 49](https://leetcode.com/problems/group-anagrams/) |
| 6 | Top K Frequent Elements | Medium | Frequency Bucket | Core #34, Infosys #13, Amazon #10 | P0 · High | `O(n)` / `O(n)` | [LC 347](https://leetcode.com/problems/top-k-frequent-elements/) |
| 7 | Next Greater Element | Easy | Monotonic Stack | Core #40, Infosys #15, Amazon #15 | P0 · High | `O(n)` / `O(n)` | [LC 496](https://leetcode.com/problems/next-greater-element-i/) |
| 8 | Sliding Window Maximum | Hard | Monotonic Queue | Core #44, Infosys #16, Amazon #17 | P0 · High | `O(n)` / `O(k)` | [LC 239](https://leetcode.com/problems/sliding-window-maximum/) |
| 9 | Binary Search | Easy | Divide & Conquer | Core #46, Infosys #17, Amazon #18 | P0 · High | `O(log n)` / `O(1)` | [LC 704](https://leetcode.com/problems/binary-search/) |
| 10 | Search in Rotated Sorted Array | Medium | Modified Binary Search | Core #47, Infosys #19, Amazon #19 | P0 · High | `O(log n)` / `O(1)` | [LC 33](https://leetcode.com/problems/search-in-rotated-sorted-array/) |
| 11 | Daily Temperatures | Medium | Monotonic Stack | Core #41, Infosys #36, Amazon #16 | P0 · High | `O(n)` / `O(n)` | [LC 739](https://leetcode.com/problems/daily-temperatures/) |
| 12 | Tree Traversals (DFS) | Easy | Recursion | Core #56, Infosys #31, Amazon #26 | P0 · High | `O(n)` / `O(h)` | [LC 94](https://leetcode.com/problems/binary-tree-inorder-traversal/) |
| 13 | Level Order Traversal | Medium | BFS + Queue | Core #57, Infosys #32, Amazon #27 | P0 · High | `O(n)` / `O(w)` | [LC 102](https://leetcode.com/problems/binary-tree-level-order-traversal/) |
| 14 | Height / Max Depth of Tree | Easy | Recursion Depth | Core #58, Infosys #33, Amazon #28 | P0 · High | `O(n)` / `O(h)` | [LC 104](https://leetcode.com/problems/maximum-depth-of-binary-tree/) |
| 15 | Longest Substring with K Distinct | Medium | Expand–Shrink | Core #31, Infosys #11, Amazon #12 | P1 · High | `O(n)` / `O(k)` | [LC 340 (Premium)](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/) · [GFG](https://www.geeksforgeeks.org/problems/longest-k-unique-characters-substring0853/1) |
| 16 | First and Last Position | Medium | Boundary Search | Core #48, Infosys #18, Amazon #20 | P1 · High | `O(log n)` / `O(1)` | [LC 34](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/) |
| 17 | Reverse Linked List | Easy | Pointer Reversal | Core #51, Infosys #30, Amazon #22 | P1 · High | `O(n)` / `O(1)` | [LC 206](https://leetcode.com/problems/reverse-linked-list/) |
| 18 | Detect Cycle in Linked List | Easy | Floyd's Cycle | Core #53, Infosys #29, Amazon #24 | P1 · High | `O(n)` / `O(1)` | [LC 141](https://leetcode.com/problems/linked-list-cycle/) |
| 19 | Majority Element | Easy | Moore Voting | Core #19, Infosys #20, Amazon #7 | P2 · Medium | `O(n)` / `O(1)` | [LC 169](https://leetcode.com/problems/majority-element/) |
| 20 | Minimum Window Substring | Hard | Shrink Until Valid | Core #32, Infosys #37, Amazon #13 | P1 · High | `O(m+n)` / `O(Σ)` | [LC 76](https://leetcode.com/problems/minimum-window-substring/) |
| 21 | Valid Parentheses / Balanced Brackets | Easy | LIFO Matching | Core #36, Core #43, Infosys #14, Amazon #14 | P2 · Medium | `O(n)` / `O(n)` | [LC 20](https://leetcode.com/problems/valid-parentheses/) |
| 22 | Climbing Stairs | Easy | Fibonacci Pattern | Core #62, Infosys #24, Amazon #36 | P2 · Medium | `O(n)` / `O(1)` | [LC 70](https://leetcode.com/problems/climbing-stairs/) |
| 23 | Merge Intervals | Medium | Sort + Merge | Infosys #21, Amazon #35 | P0 · High | `O(n log n)` / `O(n)` | [LC 56](https://leetcode.com/problems/merge-intervals/) |
| 24 | Second largest element | Easy | Two Variable Tracking | Core #2, Infosys #4 |  | `O(n)` / `O(1)` | [GFG](https://www.geeksforgeeks.org/problems/second-largest3735/1) |
| 25 | Missing Number | Easy | Math / XOR | Core #18, Infosys #5 |  | `O(n)` / `O(1)` | [LC 268](https://leetcode.com/problems/missing-number/) |
| 26 | Check Anagram | Easy | Frequency Counting | Core #20, Infosys #3 |  | `O(n)` / `O(1)` | [LC 242](https://leetcode.com/problems/valid-anagram/) |
| 27 | First non-repeating character | Easy | Frequency + Index | Core #29, Infosys #1 |  | `O(n)` / `O(1)` | [LC 387](https://leetcode.com/problems/first-unique-character-in-a-string/) |
| 28 | Best Time to Buy & Sell Stock | Easy | Greedy / One-pass | Core #16, Amazon #5 | P1 · Medium | `O(n)` / `O(1)` | [LC 121](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) |
| 29 | Remove N-th Node From End | Medium | Two Pointer Gap | Core #55, Amazon #25 | P1 · Medium-High | `O(n)` / `O(1)` | [LC 19](https://leetcode.com/problems/remove-nth-node-from-end-of-list/) |
| 30 | Longest Increasing Subsequence | Medium | LIS Pattern | Core #64, Infosys #26 |  | `O(n log n)` / `O(n)` | [LC 300](https://leetcode.com/problems/longest-increasing-subsequence/) |
| 31 | Subset Sum / Partition | Medium | 0/1 Knapsack | Core #65, Infosys #25 |  | `O(n·S)` / `O(S)` | [LC 416](https://leetcode.com/problems/partition-equal-subset-sum/) |
| 32 | Activity Selection | Easy | Sort by Finish Time | Core #66, Infosys #27 |  | `O(n log n)` / `O(n)` | [GFG](https://www.geeksforgeeks.org/problems/n-meetings-in-one-room-1587115620/1) |
| 33 | Minimum Platforms | Medium | Interval Overlap | Core #67, Infosys #28 |  | `O(n log n)` / `O(1)` | [GFG](https://www.geeksforgeeks.org/problems/minimum-platforms-1587115620/1) |
| 34 | Reverse an array | Easy | Two Pointer | Core #3, Amazon #1 | P2 · Medium | `O(n)` / `O(1)` | [LC 344](https://leetcode.com/problems/reverse-string/) |
| 35 | Check palindrome string | Easy | Two Pointer | Core #10, Amazon #2 | P2 · Medium | `O(n)` / `O(1)` | [LC 125](https://leetcode.com/problems/valid-palindrome/) |
| 36 | Move zeros to end | Easy | Two Pointer | Core #11, Amazon #3 | P2 · Medium | `O(n)` / `O(1)` | [LC 283](https://leetcode.com/problems/move-zeroes/) |
| 37 | Stock Span Problem | Medium | Monotonic Stack | Core #45, Infosys #35 |  | `O(n)` / `O(n)` | [LC 901](https://leetcode.com/problems/online-stock-span/) |
| 38 | Middle of Linked List | Easy | Fast & Slow Pointer | Core #52, Amazon #23 | P2 · Medium | `O(n)` / `O(1)` | [LC 876](https://leetcode.com/problems/middle-of-the-linked-list/) |
| 39 | LCA in BST | Medium | BST Property | Core #60, Infosys #39 |  | `O(h)` / `O(1)` | [LC 235](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/) |
| 40 | Prefix Sum – Range Queries | Easy | Cumulative Sum | Core #69, Infosys #34 |  | `O(1) query` / `O(n)` | [LC 303](https://leetcode.com/problems/range-sum-query-immutable/) |
| 41 | Koko Eating Bananas | Medium | Binary Search on Answer | Amazon #21 | P0 · Very High | `O(n log m)` / `O(1)` | [LC 875](https://leetcode.com/problems/koko-eating-bananas/) |
| 42 | Diameter of Binary Tree | Easy | Tree DFS / DP | Amazon #29 | P0 · Very High | `O(n)` / `O(h)` | [LC 543](https://leetcode.com/problems/diameter-of-binary-tree/) |
| 43 | Lowest Common Ancestor (Binary Tree) | Medium | Tree DFS | Amazon #30 | P0 · High | `O(n)` / `O(h)` | [LC 236](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/) |
| 44 | Number of Islands | Medium | BFS / DFS | Amazon #32 | P0 · Very High | `O(m·n)` / `O(m·n)` | [LC 200](https://leetcode.com/problems/number-of-islands/) |
| 45 | BFS Shortest Path (Binary Matrix) | Medium | BFS | Amazon #33 | P0 · Very High | `O(n²)` / `O(n²)` | [LC 1091](https://leetcode.com/problems/shortest-path-in-binary-matrix/) |
| 46 | Course Schedule | Medium | Topological Sort | Amazon #34 | P0 · High | `O(V+E)` / `O(V+E)` | [LC 207](https://leetcode.com/problems/course-schedule/) |
| 47 | Jump Game | Medium | Greedy Reach | Amazon #38 | P0 · High | `O(n)` / `O(1)` | [LC 55](https://leetcode.com/problems/jump-game/) |
| 48 | Kth Largest Element | Medium | Heap / Quickselect | Amazon #40 | P0 · High | `O(n log k)` / `O(k)` | [LC 215](https://leetcode.com/problems/kth-largest-element-in-an-array/) |
| 49 | Product of Array Except Self | Medium | Prefix / Suffix | Amazon #45 | P0 · High | `O(n)` / `O(1) extra` | [LC 238](https://leetcode.com/problems/product-of-array-except-self/) |
| 50 | Reverse Words in a Sentence | Medium | Split + Reverse | Infosys #2 |  | `O(n)` / `O(n)` | [LC 151](https://leetcode.com/problems/reverse-words-in-a-string/) |
| 51 | Count Pairs with Given Sum | Easy | Frequency Counting | Infosys #7 |  | `O(n)` / `O(n)` | [GFG](https://www.geeksforgeeks.org/problems/count-pairs-with-given-sum--150253/1) |
| 52 | Balanced Binary Tree | Easy | Tree DFS | Amazon #31 | P1 · Medium-High | `O(n)` / `O(h)` | [LC 110](https://leetcode.com/problems/balanced-binary-tree/) |
| 53 | House Robber | Medium | 1D DP | Amazon #37 | P1 · High | `O(n)` / `O(1)` | [LC 198](https://leetcode.com/problems/house-robber/) |
| 54 | Meeting Rooms | Easy | Sorting + Intervals | Amazon #39 | P1 · High | `O(n log n)` / `O(1)` | [LC 252 (Premium)](https://leetcode.com/problems/meeting-rooms/) · [GFG](https://www.geeksforgeeks.org/problems/attend-all-meetings/1) |
| 55 | Rotting Oranges | Medium | Multi-source BFS | Amazon #41 | P1 · High | `O(m·n)` / `O(m·n)` | [LC 994](https://leetcode.com/problems/rotting-oranges/) |
| 56 | House Robber III | Medium | Tree DP | Amazon #42 | P1 · High | `O(n)` / `O(h)` | [LC 337](https://leetcode.com/problems/house-robber-iii/) |
| 57 | 4Sum | Medium | Sorting + Two Pointers | Amazon #43 | P1 · Medium-High | `O(n³)` / `O(1)` | [LC 18](https://leetcode.com/problems/4sum/) |
| 58 | Connected Components / DSU | Medium | Union-Find | Amazon #44 | P1 · Medium-High | `O(n² α)` / `O(n)` | [LC 547](https://leetcode.com/problems/number-of-provinces/) |
| 59 | Longest Common Subsequence | Medium | 2D DP Table | Infosys #22 |  | `O(m·n)` / `O(m·n)` | [LC 1143](https://leetcode.com/problems/longest-common-subsequence/) |
| 60 | Coin Change | Medium | Unbounded Knapsack | Infosys #23 |  | `O(n·A)` / `O(A)` | [LC 322](https://leetcode.com/problems/coin-change/) |
| 61 | 0/1 Knapsack | Medium | 2D DP Table | Infosys #38 |  | `O(n·W)` / `O(W)` | [GFG](https://www.geeksforgeeks.org/problems/0-1-knapsack-problem0945/1) |
| 62 | Largest element in array | Easy | Single Traversal | Core #1 |  | `O(n)` / `O(1)` | [GFG](https://www.geeksforgeeks.org/problems/largest-element-in-array4009/1) |
| 63 | Check if array is sorted | Easy | Linear Scan | Core #4 |  | `O(n)` / `O(1)` | [LC 1752](https://leetcode.com/problems/check-if-array-is-sorted-and-rotated/) |
| 64 | Linear search | Easy | Sequential Search | Core #5 |  | `O(n)` / `O(1)` | [GFG](https://www.geeksforgeeks.org/problems/search-an-element-in-an-array-1587115621/1) |
| 65 | Count frequency of a number | Easy | Frequency Counting | Core #6 |  | `O(n)` / `O(1)` | [GFG](https://www.geeksforgeeks.org/problems/number-of-occurrence2259/1) |
| 66 | Find max & min in array | Easy | Single Traversal | Core #7 |  | `O(n)` / `O(1)` | [GFG](https://www.geeksforgeeks.org/problems/find-minimum-and-maximum-element-in-an-array4428/1) |
| 67 | Sum of digits (recursion) | Easy | Recursive Breakdown | Core #8 |  | `O(log n)` / `O(log n)` | [GFG](https://www.geeksforgeeks.org/problems/sum-of-digits1742/1) |
| 68 | Reverse a string | Easy | Two Pointer | Core #9 |  | `O(n)` / `O(1)` | [LC 344](https://leetcode.com/problems/reverse-string/) |
| 69 | Remove duplicates from sorted array | Easy | Two Pointer | Core #12 |  | `O(n)` / `O(1)` | [LC 26](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) |
| 70 | Rotate array by K positions | Medium | Reversal Algorithm | Core #13 |  | `O(n)` / `O(1)` | [LC 189](https://leetcode.com/problems/rotate-array/) |
| 71 | Merge two sorted arrays | Easy | Two Pointer Merge | Core #14 |  | `O(m+n)` / `O(1)` | [LC 88](https://leetcode.com/problems/merge-sorted-array/) |
| 72 | Longest Common Prefix | Easy | Horizontal Scanning | Core #21 |  | `O(n·m)` / `O(1)` | [LC 14](https://leetcode.com/problems/longest-common-prefix/) |
| 73 | Valid Palindrome (cleaned) | Easy | Two Pointer Cleaned | Core #22 |  | `O(n)` / `O(1)` | [LC 125](https://leetcode.com/problems/valid-palindrome/) |
| 74 | Longest word in string | Easy | Split + Traverse | Core #23 |  | `O(n)` / `O(1)` | — |
| 75 | Remove characters from string | Easy | Filtering | Core #24 |  | `O(n+m)` / `O(1)` | [GFG](https://www.geeksforgeeks.org/problems/remove-character3815/1) |
| 76 | String Compression | Medium | Count Consecutive | Core #25 |  | `O(n)` / `O(1)` | [LC 443](https://leetcode.com/problems/string-compression/) |
| 77 | Longest subarray with zero sum | Medium | Prefix Sum | Core #28 |  | `O(n)` / `O(n)` | [GFG](https://www.geeksforgeeks.org/problems/largest-subarray-with-0-sum/1) |
| 78 | Intersection of two arrays | Easy | Set Lookup | Core #35 |  | `O(m+n)` / `O(m)` | [LC 349](https://leetcode.com/problems/intersection-of-two-arrays/) |
| 79 | Min Stack | Medium | Auxiliary Stack | Core #37 |  | `O(1) per op` / `O(n)` | [LC 155](https://leetcode.com/problems/min-stack/) |
| 80 | Implement Queue using Stacks | Easy | Two Stack Transfer | Core #38 |  | `O(1) amortised` / `O(n)` | [LC 232](https://leetcode.com/problems/implement-queue-using-stacks/) |
| 81 | Implement Stack using Queues | Easy | Single Queue Rotation | Core #39 |  | `O(n) push` / `O(n)` | [LC 225](https://leetcode.com/problems/implement-stack-using-queues/) |
| 82 | Evaluate Reverse Polish Notation | Medium | Expression Evaluation | Core #42 |  | `O(n)` / `O(n)` | [LC 150](https://leetcode.com/problems/evaluate-reverse-polish-notation/) |
| 83 | Find Peak Element | Medium | Slope Check | Core #49 |  | `O(log n)` / `O(1)` | [LC 162](https://leetcode.com/problems/find-peak-element/) |
| 84 | Square Root using Binary Search | Easy | Search Space Reduction | Core #50 |  | `O(log n)` / `O(1)` | [LC 69](https://leetcode.com/problems/sqrtx/) |
| 85 | Merge Two Sorted Lists | Easy | Two Pointer Merge | Core #54 |  | `O(m+n)` / `O(1)` | [LC 21](https://leetcode.com/problems/merge-two-sorted-lists/) |
| 86 | Check identical trees | Easy | Recursive Compare | Core #59 |  | `O(n)` / `O(h)` | [LC 100](https://leetcode.com/problems/same-tree/) |
| 87 | Fibonacci (DP) | Easy | Memoization | Core #61 |  | `O(n)` / `O(1)` | [LC 509](https://leetcode.com/problems/fibonacci-number/) |
| 88 | Assign Cookies | Easy | Sorting + Greedy | Core #68 |  | `O(n log n)` / `O(1)` | [LC 455](https://leetcode.com/problems/assign-cookies/) |

## Sheets in original order

### Core 70

**Level 0 · Warmup**

1. Largest element in array · [GFG](https://www.geeksforgeeks.org/problems/largest-element-in-array4009/1)
2. Second largest element · [GFG](https://www.geeksforgeeks.org/problems/second-largest3735/1)
3. Reverse an array · [LC 344](https://leetcode.com/problems/reverse-string/)
4. Check if array is sorted · [LC 1752](https://leetcode.com/problems/check-if-array-is-sorted-and-rotated/)
5. Linear search · [GFG](https://www.geeksforgeeks.org/problems/search-an-element-in-an-array-1587115621/1)
6. Count frequency of a number · [GFG](https://www.geeksforgeeks.org/problems/number-of-occurrence2259/1)
7. Find max & min in array · [GFG](https://www.geeksforgeeks.org/problems/find-minimum-and-maximum-element-in-an-array4428/1)
8. Sum of digits (recursion) · [GFG](https://www.geeksforgeeks.org/problems/sum-of-digits1742/1)
9. Reverse a string · [LC 344](https://leetcode.com/problems/reverse-string/)
10. Check palindrome string · [LC 125](https://leetcode.com/problems/valid-palindrome/)

**Level 20 · Arrays & Strings**

11. Move zeros to end · [LC 283](https://leetcode.com/problems/move-zeroes/)
12. Remove duplicates from sorted array · [LC 26](https://leetcode.com/problems/remove-duplicates-from-sorted-array/)
13. Rotate array by K positions · [LC 189](https://leetcode.com/problems/rotate-array/)
14. Merge two sorted arrays · [LC 88](https://leetcode.com/problems/merge-sorted-array/)
15. Two Sum · [LC 1](https://leetcode.com/problems/two-sum/)
16. Best Time to Buy & Sell Stock · [LC 121](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)
17. Kadane's Algorithm (Maximum Subarray) · [LC 53](https://leetcode.com/problems/maximum-subarray/)
18. Missing Number · [LC 268](https://leetcode.com/problems/missing-number/)
19. Majority Element · [LC 169](https://leetcode.com/problems/majority-element/)
20. Check Anagram · [LC 242](https://leetcode.com/problems/valid-anagram/)
21. Longest Common Prefix · [LC 14](https://leetcode.com/problems/longest-common-prefix/)
22. Valid Palindrome (cleaned) · [LC 125](https://leetcode.com/problems/valid-palindrome/)
23. Longest word in string · —
24. Remove characters from string · [GFG](https://www.geeksforgeeks.org/problems/remove-character3815/1)
25. String Compression · [LC 443](https://leetcode.com/problems/string-compression/)

**Level 40 · HashMap / Sliding Window**

26. Two Sum · [LC 1](https://leetcode.com/problems/two-sum/)
27. Subarray Sum Equals K · [LC 560](https://leetcode.com/problems/subarray-sum-equals-k/)
28. Longest subarray with zero sum · [GFG](https://www.geeksforgeeks.org/problems/largest-subarray-with-0-sum/1)
29. First non-repeating character · [LC 387](https://leetcode.com/problems/first-unique-character-in-a-string/)
30. Longest Substring Without Repeating Characters · [LC 3](https://leetcode.com/problems/longest-substring-without-repeating-characters/)
31. Longest Substring with K Distinct · [LC 340 (Premium)](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/) · [GFG](https://www.geeksforgeeks.org/problems/longest-k-unique-characters-substring0853/1)
32. Minimum Window Substring · [LC 76](https://leetcode.com/problems/minimum-window-substring/)
33. Group Anagrams · [LC 49](https://leetcode.com/problems/group-anagrams/)
34. Top K Frequent Elements · [LC 347](https://leetcode.com/problems/top-k-frequent-elements/)
35. Intersection of two arrays · [LC 349](https://leetcode.com/problems/intersection-of-two-arrays/)

**Level 50 · Stack & Queue**

36. Valid Parentheses / Balanced Brackets · [LC 20](https://leetcode.com/problems/valid-parentheses/)
37. Min Stack · [LC 155](https://leetcode.com/problems/min-stack/)
38. Implement Queue using Stacks · [LC 232](https://leetcode.com/problems/implement-queue-using-stacks/)
39. Implement Stack using Queues · [LC 225](https://leetcode.com/problems/implement-stack-using-queues/)
40. Next Greater Element · [LC 496](https://leetcode.com/problems/next-greater-element-i/)
41. Daily Temperatures · [LC 739](https://leetcode.com/problems/daily-temperatures/)
42. Evaluate Reverse Polish Notation · [LC 150](https://leetcode.com/problems/evaluate-reverse-polish-notation/)
43. Valid Parentheses / Balanced Brackets · [LC 20](https://leetcode.com/problems/valid-parentheses/)
44. Sliding Window Maximum · [LC 239](https://leetcode.com/problems/sliding-window-maximum/)
45. Stock Span Problem · [LC 901](https://leetcode.com/problems/online-stock-span/)

**Level 60 · Binary Search**

46. Binary Search · [LC 704](https://leetcode.com/problems/binary-search/)
47. Search in Rotated Sorted Array · [LC 33](https://leetcode.com/problems/search-in-rotated-sorted-array/)
48. First and Last Position · [LC 34](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/)
49. Find Peak Element · [LC 162](https://leetcode.com/problems/find-peak-element/)
50. Square Root using Binary Search · [LC 69](https://leetcode.com/problems/sqrtx/)

**Level 70 · Linked List**

51. Reverse Linked List · [LC 206](https://leetcode.com/problems/reverse-linked-list/)
52. Middle of Linked List · [LC 876](https://leetcode.com/problems/middle-of-the-linked-list/)
53. Detect Cycle in Linked List · [LC 141](https://leetcode.com/problems/linked-list-cycle/)
54. Merge Two Sorted Lists · [LC 21](https://leetcode.com/problems/merge-two-sorted-lists/)
55. Remove N-th Node From End · [LC 19](https://leetcode.com/problems/remove-nth-node-from-end-of-list/)

**Level 80 · Trees**

56. Tree Traversals (DFS) · [LC 94](https://leetcode.com/problems/binary-tree-inorder-traversal/)
57. Level Order Traversal · [LC 102](https://leetcode.com/problems/binary-tree-level-order-traversal/)
58. Height / Max Depth of Tree · [LC 104](https://leetcode.com/problems/maximum-depth-of-binary-tree/)
59. Check identical trees · [LC 100](https://leetcode.com/problems/same-tree/)
60. LCA in BST · [LC 235](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/)

**Extra · DP (do ≥5)**

61. Fibonacci (DP) · [LC 509](https://leetcode.com/problems/fibonacci-number/)
62. Climbing Stairs · [LC 70](https://leetcode.com/problems/climbing-stairs/)
63. Kadane's Algorithm (Maximum Subarray) · [LC 53](https://leetcode.com/problems/maximum-subarray/)
64. Longest Increasing Subsequence · [LC 300](https://leetcode.com/problems/longest-increasing-subsequence/)
65. Subset Sum / Partition · [LC 416](https://leetcode.com/problems/partition-equal-subset-sum/)

**Extra · Greedy (do ≥3)**

66. Activity Selection · [GFG](https://www.geeksforgeeks.org/problems/n-meetings-in-one-room-1587115620/1)
67. Minimum Platforms · [GFG](https://www.geeksforgeeks.org/problems/minimum-platforms-1587115620/1)
68. Assign Cookies · [LC 455](https://leetcode.com/problems/assign-cookies/)

**Extra · Prefix / Math (do ≥2)**

69. Prefix Sum – Range Queries · [LC 303](https://leetcode.com/problems/range-sum-query-immutable/)
70. Subarray Sum Equals K · [LC 560](https://leetcode.com/problems/subarray-sum-equals-k/)

### Infosys SP/DSE 40

**Block 1 · Must Win (Q1 Killer)**

1. First non-repeating character · [LC 387](https://leetcode.com/problems/first-unique-character-in-a-string/)
2. Reverse Words in a Sentence · [LC 151](https://leetcode.com/problems/reverse-words-in-a-string/)
3. Check Anagram · [LC 242](https://leetcode.com/problems/valid-anagram/)
4. Second largest element · [GFG](https://www.geeksforgeeks.org/problems/second-largest3735/1)
5. Missing Number · [LC 268](https://leetcode.com/problems/missing-number/)
6. Two Sum · [LC 1](https://leetcode.com/problems/two-sum/)
7. Count Pairs with Given Sum · [GFG](https://www.geeksforgeeks.org/problems/count-pairs-with-given-sum--150253/1)
8. Kadane's Algorithm (Maximum Subarray) · [LC 53](https://leetcode.com/problems/maximum-subarray/)
9. Longest Substring Without Repeating Characters · [LC 3](https://leetcode.com/problems/longest-substring-without-repeating-characters/)
10. Subarray Sum Equals K · [LC 560](https://leetcode.com/problems/subarray-sum-equals-k/)

**Block 2 · High-Probability Medium (Q2 Core)**

11. Longest Substring with K Distinct · [LC 340 (Premium)](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/) · [GFG](https://www.geeksforgeeks.org/problems/longest-k-unique-characters-substring0853/1)
12. Group Anagrams · [LC 49](https://leetcode.com/problems/group-anagrams/)
13. Top K Frequent Elements · [LC 347](https://leetcode.com/problems/top-k-frequent-elements/)
14. Valid Parentheses / Balanced Brackets · [LC 20](https://leetcode.com/problems/valid-parentheses/)
15. Next Greater Element · [LC 496](https://leetcode.com/problems/next-greater-element-i/)
16. Sliding Window Maximum · [LC 239](https://leetcode.com/problems/sliding-window-maximum/)
17. Binary Search · [LC 704](https://leetcode.com/problems/binary-search/)
18. First and Last Position · [LC 34](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/)
19. Search in Rotated Sorted Array · [LC 33](https://leetcode.com/problems/search-in-rotated-sorted-array/)
20. Majority Element · [LC 169](https://leetcode.com/problems/majority-element/)

**Block 3 · SP Decider (Q3 Level)**

21. Merge Intervals · [LC 56](https://leetcode.com/problems/merge-intervals/)
22. Longest Common Subsequence · [LC 1143](https://leetcode.com/problems/longest-common-subsequence/)
23. Coin Change · [LC 322](https://leetcode.com/problems/coin-change/)
24. Climbing Stairs · [LC 70](https://leetcode.com/problems/climbing-stairs/)
25. Subset Sum / Partition · [LC 416](https://leetcode.com/problems/partition-equal-subset-sum/)
26. Longest Increasing Subsequence · [LC 300](https://leetcode.com/problems/longest-increasing-subsequence/)
27. Activity Selection · [GFG](https://www.geeksforgeeks.org/problems/n-meetings-in-one-room-1587115620/1)
28. Minimum Platforms · [GFG](https://www.geeksforgeeks.org/problems/minimum-platforms-1587115620/1)
29. Detect Cycle in Linked List · [LC 141](https://leetcode.com/problems/linked-list-cycle/)
30. Reverse Linked List · [LC 206](https://leetcode.com/problems/reverse-linked-list/)

**Block 4 · Quick Overview (Safety Net)**

31. Tree Traversals (DFS) · [LC 94](https://leetcode.com/problems/binary-tree-inorder-traversal/)
32. Level Order Traversal · [LC 102](https://leetcode.com/problems/binary-tree-level-order-traversal/)
33. Height / Max Depth of Tree · [LC 104](https://leetcode.com/problems/maximum-depth-of-binary-tree/)
34. Prefix Sum – Range Queries · [LC 303](https://leetcode.com/problems/range-sum-query-immutable/)
35. Stock Span Problem · [LC 901](https://leetcode.com/problems/online-stock-span/)
36. Daily Temperatures · [LC 739](https://leetcode.com/problems/daily-temperatures/)
37. Minimum Window Substring · [LC 76](https://leetcode.com/problems/minimum-window-substring/)
38. 0/1 Knapsack · [GFG](https://www.geeksforgeeks.org/problems/0-1-knapsack-problem0945/1)
39. LCA in BST · [LC 235](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/)
40. Subarray Sum Equals K · [LC 560](https://leetcode.com/problems/subarray-sum-equals-k/)

### Amazon prep 45

**Amazon prep list**

1. Reverse an array — P2, Medium likelihood, Understand + code · [LC 344](https://leetcode.com/problems/reverse-string/)
2. Check palindrome string — P2, Medium likelihood, Understand + code · [LC 125](https://leetcode.com/problems/valid-palindrome/)
3. Move zeros to end — P2, Medium likelihood, Understand + code · [LC 283](https://leetcode.com/problems/move-zeroes/)
4. Two Sum — P0, High likelihood, Brute force + Optimal + code · [LC 1](https://leetcode.com/problems/two-sum/)
5. Best Time to Buy & Sell Stock — P1, Medium likelihood, Brute force + Optimal + code · [LC 121](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)
6. Kadane's Algorithm (Maximum Subarray) — P0, High likelihood, Brute force + Optimal + code · [LC 53](https://leetcode.com/problems/maximum-subarray/)
7. Majority Element — P2, Medium likelihood, Optimal + code · [LC 169](https://leetcode.com/problems/majority-element/)
8. Group Anagrams — P0, High likelihood, Optimal + code (builds on #4 helps, not required) · [LC 49](https://leetcode.com/problems/group-anagrams/)
9. Subarray Sum Equals K — P0, Very High likelihood, Brute force + Optimal + code · [LC 560](https://leetcode.com/problems/subarray-sum-equals-k/)
10. Top K Frequent Elements — P0, High likelihood, Brute force + Optimal + code · [LC 347](https://leetcode.com/problems/top-k-frequent-elements/)
11. Longest Substring Without Repeating Characters — P0, Very High likelihood, Brute force + Optimal + code · [LC 3](https://leetcode.com/problems/longest-substring-without-repeating-characters/)
12. Longest Substring with K Distinct — P1, High likelihood, Optimal + code (builds on #11 pattern) · [LC 340 (Premium)](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/) · [GFG](https://www.geeksforgeeks.org/problems/longest-k-unique-characters-substring0853/1)
13. Minimum Window Substring — P1, High likelihood, Understand + Optimal code (builds on #11 helps) · [LC 76](https://leetcode.com/problems/minimum-window-substring/)
14. Valid Parentheses / Balanced Brackets — P2, Medium likelihood, Understand + code · [LC 20](https://leetcode.com/problems/valid-parentheses/)
15. Next Greater Element — P0, High likelihood, Brute force + Optimal + code · [LC 496](https://leetcode.com/problems/next-greater-element-i/)
16. Daily Temperatures — P0, High likelihood, Optimal + code (builds on #15 strongly helps) · [LC 739](https://leetcode.com/problems/daily-temperatures/)
17. Sliding Window Maximum — P0, High likelihood, Understand + Optimal code (builds on #15 helps) · [LC 239](https://leetcode.com/problems/sliding-window-maximum/)
18. Binary Search — P0, High likelihood, Concept + Optimal code · [LC 704](https://leetcode.com/problems/binary-search/)
19. Search in Rotated Sorted Array — P0, High likelihood, Optimal + code (builds on #18) · [LC 33](https://leetcode.com/problems/search-in-rotated-sorted-array/)
20. First and Last Position — P1, High likelihood, Optimal + code (builds on #18) · [LC 34](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/)
21. Koko Eating Bananas — P0, Very High likelihood, Brute force + Optimal + code (builds on #18) · [LC 875](https://leetcode.com/problems/koko-eating-bananas/)
22. Reverse Linked List — P1, High likelihood, Understand + code · [LC 206](https://leetcode.com/problems/reverse-linked-list/)
23. Middle of Linked List — P2, Medium likelihood, Understand + code · [LC 876](https://leetcode.com/problems/middle-of-the-linked-list/)
24. Detect Cycle in Linked List — P1, High likelihood, Optimal + code (builds on #23 helps) · [LC 141](https://leetcode.com/problems/linked-list-cycle/)
25. Remove N-th Node From End — P1, Medium-High likelihood, Optimal + code (builds on #23 helps) · [LC 19](https://leetcode.com/problems/remove-nth-node-from-end-of-list/)
26. Tree Traversals (DFS) — P0, High likelihood, All traversals + code · [LC 94](https://leetcode.com/problems/binary-tree-inorder-traversal/)
27. Level Order Traversal — P0, High likelihood, Optimal + code · [LC 102](https://leetcode.com/problems/binary-tree-level-order-traversal/)
28. Height / Max Depth of Tree — P0, High likelihood, Optimal + code (builds on #26) · [LC 104](https://leetcode.com/problems/maximum-depth-of-binary-tree/)
29. Diameter of Binary Tree — P0, Very High likelihood, Brute force + Optimal + code (builds on #28) · [LC 543](https://leetcode.com/problems/diameter-of-binary-tree/)
30. Lowest Common Ancestor (Binary Tree) — P0, High likelihood, Optimal + code (builds on #26) · [LC 236](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/)
31. Balanced Binary Tree — P1, Medium-High likelihood, Understand + code (builds on #28) · [LC 110](https://leetcode.com/problems/balanced-binary-tree/)
32. Number of Islands — P0, Very High likelihood, Concept + Optimal code (builds on #26 / #27) · [LC 200](https://leetcode.com/problems/number-of-islands/)
33. BFS Shortest Path (Binary Matrix) — P0, Very High likelihood, Optimal + code (builds on #27) · [LC 1091](https://leetcode.com/problems/shortest-path-in-binary-matrix/)
34. Course Schedule — P0, High likelihood, Understand + Optimal code (builds on #32 / #33) · [LC 207](https://leetcode.com/problems/course-schedule/)
35. Merge Intervals — P0, High likelihood, Optimal + code · [LC 56](https://leetcode.com/problems/merge-intervals/)
36. Climbing Stairs — P2, Medium likelihood, Understand + code · [LC 70](https://leetcode.com/problems/climbing-stairs/)
37. House Robber — P1, High likelihood, Brute force + Optimal + code (builds on #36) · [LC 198](https://leetcode.com/problems/house-robber/)
38. Jump Game — P0, High likelihood, Brute force + Optimal + code · [LC 55](https://leetcode.com/problems/jump-game/)
39. Meeting Rooms — P1, High likelihood, Optimal + code (builds on #35 helps) · [LC 252 (Premium)](https://leetcode.com/problems/meeting-rooms/) · [GFG](https://www.geeksforgeeks.org/problems/attend-all-meetings/1)
40. Kth Largest Element — P0, High likelihood, Heap optimal + code · [LC 215](https://leetcode.com/problems/kth-largest-element-in-an-array/)
41. Rotting Oranges — P1, High likelihood, Understand + code (builds on #27) · [LC 994](https://leetcode.com/problems/rotting-oranges/)
42. House Robber III — P1, High likelihood, Understand deeply + code (builds on #29 + #37) · [LC 337](https://leetcode.com/problems/house-robber-iii/)
43. 4Sum — P1, Medium-High likelihood, Optimal + code (builds on #4 / two-pointer) · [LC 18](https://leetcode.com/problems/4sum/)
44. Connected Components / DSU — P1, Medium-High likelihood, Understand + code · [LC 547](https://leetcode.com/problems/number-of-provinces/)
45. Product of Array Except Self — P0, High likelihood, Brute force + Optimal + code · [LC 238](https://leetcode.com/problems/product-of-array-except-self/)
