# Group Assignment (15%): Electricity Allocation Using Linear Programming

## Overview
This group assignment formulates an electricity-allocation problem. Students need electricity for lighting, studying, cooking and charging devices. The model aims to minimise electricity use while meeting essential needs and respecting the available supply.

## Decision variables
- `x1` = electricity for lighting (kWh)
- `x2` = electricity for studying (laptop, computer and Wi-Fi) (kWh)
- `x3` = electricity for cooking (kWh)
- `x4` = electricity for charging electronic devices (kWh)

## Objective function
```text
Minimise Z = x1 + x2 + x3 + x4
```

## Constraints
Available electricity:
```text
x1 + x2 + x3 + x4 <= E
```
Minimum requirements:
```text
x1 >= L
x2 >= S
x3 >= C
x4 >= D
```
Non-negativity:
```text
x1, x2, x3, x4 >= 0
```

`E` is the total available electricity; `L`, `S`, `C` and `D` are the minimum requirements for the four activities.

## Assumptions
- Each essential activity has a minimum electricity requirement.
- Total electricity use cannot exceed the available supply.
- Electricity use cannot be negative.

## Recommended technique
The group recommends Linear Programming because the objective function and constraints are linear.

## What this demonstrates
Problem formulation, decision variables, objective functions, resource constraints, assumptions and selection of an optimisation technique.


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
This README summarises the submitted work; it is not a corrected answer key. Questions 2â€“4 should be checked against the original assignment question before treating every model as final. No optimal numerical solutions are claimed.

## Scope note
The submitted model does not provide numerical values for `E`, `L`, `S`, `C` or `D`, or a numerical optimal solution. This is group coursework; public credit should reflect the group and university requirements.
