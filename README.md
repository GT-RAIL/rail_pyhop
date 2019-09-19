# rail_pyhop

RAIL fork of the pyHOP planner (Hierarchical Ordered HTN Planner) with examples


## Concept Basics

- PyHOP represents state variables using binding to regular python variables instead of logic propositions. This makes
writing and working with the state VERY easy. 

- To write HTN operators and methods for PyHOP, you don't need to learn a specialized planning language. Instead, 
you write them as ordinary Python functions. The current state (e.g., s in the above example) is passed to them as an
 argument.


## Installation

```bash
$ git clone https://github.com/GT-RAIL/rail_pyhop.git
```


## HelloWorld

To run a basic example, see below:

```bash
$ cd rail_pyhop
$ python simple_travel.py
```


## To Do List
- Improve plan failure outputs
- Add unittesting
- Add partial planning
- Modify logging to use colored logger

## Repo Branch Structure
- master: used to release stable versions on rail_pyhop planners (must build and pass testing)
- dev: used to incrementally improve versions (must build)
- other(s): feature development and bug fix branches


## Acknowledgement
----

Based on the PyHOP planner released under Apache License, Version 2.0 at 
[Dana S. Nau's BitBucket](https://bitbucket.org/dananau/pyhop/)

----