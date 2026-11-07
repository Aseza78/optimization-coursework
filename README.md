# Individual Assignment (15%): Linear Programming Formulation

## Overview
The handwritten individual assignment contains four LP formulation questions.

## Question 1: Study-table and computer-table production
Decision variables:
- `x` = study tables produced per week
- `y` = computer tables produced per week

Submitted objective:
```text
Maximise Z = 100x + 160y
```
Submitted labour constraints:
```text
2x + 2y <= 228
2x + 5y <= 418
x, y >= 0
```
The written working describes 228 skilled-worker hours and 418 semi-skilled-worker hours as weekly capacities.

## Question 2: Demand and worker costs
The assignment defines `x` and `y` as weekly production of study tables and computer tables. It states:
```text
x >= 40
y >= 45
```
It also carries forward the labour constraints:
```text
2x + 2y <= 228
2x + 5y <= 418
```
The explanation describes a fixed workforce (6 skilled and 11 semi-skilled workers) and a fixed worker cost. However, the written objective/model notation is not fully consistent with that explanation, so this is not presented here as a verified final cost model.

## Question 3: Advertising allocation
Decision variables:
- `x` = number of TV advertisements
- `y` = number of radio advertisements
- `z` = number of newspaper advertisements

Submitted objective:
```text
Maximise Z = 30000x + 18000y + 10000z
```
Submitted budget constraint:
```text
10000x + 5000y + 3000z <= 1500000
```
The scan appears to include minimum advertising quantities, but the exact notation is not clear enough to reproduce confidently.

## Question 4: Crop planning
Decision variables:
- `x` = acres used to grow wheat
- `y` = acres used to grow potatoes

Submitted objective:
```text
Maximise Z = 400x + 550y
```
The handwritten model includes a 100-acre land limit and labour/fertiliser constraints. Some coefficients and inequality signs are not sufficiently clear in the scan to reproduce confidently.

## Skills demonstrated
Defining decision variables, writing objective functions, translating resource limits and demand requirements into constraints, and applying non-negativity restrictions.

## Accuracy note
This README summarises the submitted work; it is not a corrected answer key. Questions 2–4 should be checked against the original assignment question before treating every model as final. No optimal numerical solutions are claimed.
