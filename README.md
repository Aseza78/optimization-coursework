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

## Scope note
The submitted model does not provide numerical values for `E`, `L`, `S`, `C` or `D`, or a numerical optimal solution. This is group coursework; public credit should reflect the group and university requirements.
