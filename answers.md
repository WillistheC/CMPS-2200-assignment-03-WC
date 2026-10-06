# CMPS 2200 Assignment 3
## Answers

**Name:** Will Cunningham


Place all written answers from `assignment-03.md` here for easier grading.


**1: Searching Unsorted Lists**

- **1b.** Work and span of `isearch` implementation

Work: for L with length $n$, iterate is called $n$ times executing one comparison

This is linear work, so $W(n) = O(n)$

Span: iterate is able to work in parallel, meaning L can be split into $k$ pieces

This makes the longest chain of dependency the length of the longest branch

If the branches are split equally into $k$ pieces, the length of the branch is $h = log{k}{n}$

So, $S(n) = O(n)$

- **1d.** Work and span of `rsearch` implementation


- **1e.** Work and span of `rsearch` using `ureduce`


**3: Parenthesis Matching**

- **3b.** Recurrences and Big-Oh solutions for `parens_match_iterative`


- **3d.** Work and Span for `parens_match_scan`


- **3f.** Recurrences and Big-Oh solutions for `parens_match_dc_helper`
