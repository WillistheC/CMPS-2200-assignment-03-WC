# CMPS 2200 Assignment 3
## Answers

**Name:** Will Cunningham


Place all written answers from `assignment-03.md` here for easier grading.


**1: Searching Unsorted Lists**

- **1b.** Work and span of `isearch` implementation

Work: For L with length $n$, the lambda function is called $n$ times, executing one comparison in constant time

This is linear work, so $W(n) = O(n)$

Span: Since iterate works on an accumulation of results, it must be done sequentially

The function is linear, so the dependency chain has length $n$; $S(n) = O(n)$

- **1d.** Work and span of `rsearch` implementation


- **1e.** Work and span of `rsearch` using `ureduce`


**3: Parenthesis Matching**

- **3b.** Recurrences and Big-Oh solutions for `parens_match_iterative`


- **3d.** Work and Span for `parens_match_scan`


- **3f.** Recurrences and Big-Oh solutions for `parens_match_dc_helper`
