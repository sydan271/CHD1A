# A Small Math Problem

**Nothing starts a story better than a betel leaf — or a small math problem.**

From the early days of Vietnamese competitive programming, Vuong Hai Thanh has been passionate about strange and beautiful math problems — ones related to the mysteries of teenage boys and girls... Though they're not mainstream, these legends were passed on to us by veteran programmers, and this one is said to come from the legendary T-s-x.

Here is the problem:

Given two numbers `n` and `k`, compute the result of:

```
((k - 1)^n + (k - 1) * (-1)^n) mod 6971
```

## Input

- The first line contains the number of test cases `T` (`T ≤ 50`).
- Each of the next `T` lines contains two integers `n` and `k` (`1 ≤ n`, `k ≤ 10^9`).

## Output

For each test case, print the result on one line.

## Sample

### Input
```
2
4 4
6 9
```

### Output
```
84
4225
```
