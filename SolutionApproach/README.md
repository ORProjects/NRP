[ABSTRACT](/README.md) | [OVERVIEW](/Overview/README.md)  | [SOLUTION APPROACH](/SolutionApproach/README.md)  | [INSTANCES](/Instances/README.md)  | [COMPUTATIONAL RESULTS](/ComputationalResults/README.md)
------------- | ------------- | ------------- | ------------- | -------------

`SOLUTION APPROACH`
====================
## The Hybrid Algorithm

<p align="justify"> The approach can be examined in two sections. The first section is where only the F&R heuristic is used for generating initial solutions. The last part is when initial solutions are improved by the F&O and SA algorithms.


1. ### Initial Solution Generation Phase
   
   In this phase, instances are examined and decomposition decisions are made. For smaller instances, generally week decomposition is used. For larger instances, we use nurse decomposition.

1. ### Improvement Phase
   In this phase, the SA algorithm plays the central role and starts improving the initial solution by applying various neighborhoods. Better cost values are immediately accepted and worse ones are accepted in a probabilistic manner. What makes our implementation unique in this step is that when solutions can no longer be improved by applying these neighborhoods, the current schedule is send to the F&O algorithm and the power of integer programming solvers are utilized to further improve the solution. Even when the solution from the F&O heuritic is worse than the current solution due to time limits, it would still be valuable schedule because its earlier structure would be changed. This new structure re-enables the effectiveness of the neighborhoods and the SA algorithm continues to improve.
   
   When termination criterion is met, the result is reported and written to an Excel file. Below diagram shows the complete picture.

</p>

![alt text](https://github.com/ORProjects/Trial/blob/master/SolutionApproach/Images/OverallAlgorithm.PNG)

## Neighborhoods

<p align="justify">The SA part of the hybrid algorithm utilizes a variety of neighborhoods as shown below. Nurses, days, and shifts are randomly selected and swithed between eachother to generate different schedules. We propose a new neighborhood (Shift-On) where a shift is added to an off-day. The rest of the neighborhood are commonly found in the literature.

</p>

![alt text](https://github.com/ORProjects/Trial/blob/master/SolutionApproach/Images/Neighborhoods.png)
