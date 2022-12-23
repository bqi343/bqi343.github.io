---
layout: post
title: "Problemsetting for the USACO"
---

The [USA Computing Olympiad](http://www.usaco.org/) hosts 3-problem, 4-hour contests for high school students. Contests are offered in four divisions (Bronze, Silver, Gold, and Platinum in increasing order of difficulty), four times a year. I've been a problemsetter for the USACO since December 2019.

## Problem Proposal FAQs

### Can I propose problems for the USACO?

Anyone, including current USACO contestants, can propose a problem. Though if you're a current USACO contestant, we probably won't use your problem if it's for the division you are currently in or the division above that.

### What sorts of problems can I propose?

The [International Olympiad in Informatics](https://ioinformatics.org/) has three main task types: batch, output-only,
and communication ([source](https://cms.readthedocs.io/en/v1.4/Task%20types.html#standard-task-types)). Usually, USACO monthly contests only feature batch
tasks since those are the easiest to prepare. Check the USACO website
for examples of recent tasks, and the [USACO Guide](https://usaco.guide/bronze/)
for an _unofficial_ list of topics for each division.

### How do I propose a problem for the USACO?

You can email me a proposal satisfying the requirements below.

### How do I prepare problems for the USACO?

If you are out of high school and would like to help write statements,
solutions, generators, validators, or analyses, please let me know.

## Problem Proposal Requirements

- (Required) Problem credits
- (Required) Anyone competing in USACO who has seen the problem and their divisions
- (Required) Expected division and difficulty
- (Required) A clear problem statement, preferably shared via Google Docs. [HackMD](https://hackmd.io/) works too, if you prefer markdown.
- (Required) Constraints on the input
- (Required) Sketch of the model solution
- (Preferred) At least one sample case and an explanation
- (Preferred) Code for the model solution
- (Preferred) Input and output format
- (Preferred) Scoring
- (Preferred) Code for slow or wrong solutions
- (Optional) Analysis (can be done after we decide to use the problem)
- (Optional) Test generator
- (Optional) Flavor text

### Common mistakes to avoid

- Typos
- Including flavor text that makes the problem more difficult to understand.
- Making the problem statement ambiguous enough to admit multiple possible interpretations and providing a sample case that doesn’t distinguish between them.
- Forgetting to include constraints on the input.
- \\(\LaTeX\\) mistakes:
  - Forgetting to enclose math in $...$.
  - Not including a backslash before operators such as $min$.
  - Not using `\left(`, `\right)` when larger parentheses are needed.
- Making every sentence its own paragraph or condensing too many sentences into a single paragraph.
  - When in doubt, follow the format of past USACO problems ([example](http://www.usaco.org/index.php?page=viewproblem2&cpid=1236)).
- Not being able to prove that the model solution works.

## How to come up with problem ideas

Here are some methods that have worked reliably for me:

- ~~Copy~~ Take inspiration from a past problem.
  - I didn't come close to solving [this problem](https://codeforces.com/contest/1392/problem/I) in-contest, but I came up with [Gregor and the Two Painters](https://codeforces.com/contest/1548/problem/E) as a result.
  - [Modern Art 3](http://www.usaco.org/index.php?page=viewproblem2&cpid=1114) arose naturally from [Modern Art 2](http://www.usaco.org/index.php?page=viewproblem2&cpid=743).
- Take inspiration from classes.
  - [Routing Schemes](http://www.usaco.org/index.php?page=viewproblem2&cpid=1141) was based on MIT 6.856: Randomized Algorithms.
  - [Pair Programming](http://www.usaco.org/index.php?page=viewproblem2&cpid=1234) was based on MIT 6.172: Software Performance Engineering.
  - [Paired Up](http://www.usaco.org/index.php?page=viewproblem2&cpid=1165) was based on MIT 21M.387: Fundamentals of Music Processing.
- Count \\(x\\) of \\(y\\) satisfying \\(z\\) property.
  - [Rectangular Pasture](http://www.usaco.org/index.php?page=viewproblem2&cpid=1063), [Square Pasture](http://www.usaco.org/index.php?page=viewproblem2&cpid=1067), [Balanced Subsets](http://www.usaco.org/index.php?page=viewproblem2&cpid=1142): count subsets of grid cells satisfying some property.
  - [Equilateral Triangles](http://www.usaco.org/index.php?page=viewproblem2&cpid=1021): count triples of grid cells satisfying some property.
  - [United Cows of Farmer John](http://www.usaco.org/index.php?page=viewproblem2&cpid=1140): count triples of array elements satisfying some property.
  - [Cowmistry](http://www.usaco.org/index.php?page=viewproblem2&cpid=1070): count triples of integers satisfying some property.

<!--  - (Unintentionally) copy a past problem.
   - [Equilateral Triangles](http://www.usaco.org/index.php?page=viewproblem2&cpid=1021) turned out to be identical to [this problem](https://atcoder.jp/contests/tenka1-2018/tasks/tenka1_2018_e). Sorry, making original problems isn't always easy ... -->

You can also find articles about problemsetting at the end of the [Codeforces catalog](https://codeforces.com/catalog).
