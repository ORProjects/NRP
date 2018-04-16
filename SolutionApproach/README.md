[ABSTRACT](/README.md) | [OVERVIEW](/Overview/README.md)  | [SOLUTION APPROACH](/SolutionApproach/README.md)  | [INSTANCES](/Instances/README.md)  | [COMPUTATIONAL RESULTS](/ComputationalResults/README.md)
------------- | ------------- | ------------- | ------------- | -------------

`SOLUTION APPROACH`
====================
## The Hybrid Algorithm

<p align="justify"> The approach can be examined in two sections. The first section is where only the F&R heuristic is used for generating initial solutions. The last part is when initial solutions are improved by the F&O and SA algorithms.


1. ### Initial Solution Generation Phase
   
   In this phase, instances are examined and decomposition decisions are made. For smaller instances, generally week decomposition is used. For larger instances, nurse decomposition is utilized.

1. ### Improvement Phase
   1. A nurse can only have one shift per day.







</p>

![alt text](https://github.com/ORProjects/Trial/blob/master/SolutionApproach/Images/OverallAlgorithm.PNG)

## Neighborhoods

<p align="justify">Personnel scheduling is not a new area of study for the Operations Research community. It has been studied since 1950s. But Today's problem is fairly different than its original version. Planners must consider many elements before developing a schedule. Employees have part-time and full-time opportunities. Planners must also account for employees' preferences in this planning process.</p>

![alt text](https://github.com/ORProjects/Trial/blob/master/SolutionApproach/Images/Neighborhoods.png)
