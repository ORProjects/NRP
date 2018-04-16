[ABSTRACT](/README.md) | [OVERVIEW](/Overview/README.md)  | [SOLUTION APPROACH](/SolutionApproach/README.md)  | [INSTANCES](/Instances/README.md)  | [COMPUTATIONAL RESULTS](/ComputationalResults/README.md)
------------- | ------------- | ------------- | ------------- | -------------

`OVERVIEW`
====================
## Introduction
<p align="justify">Personnel scheduling is not a new area of study for the Operations Research community. It has been studied since 1950s. But Today's problem is fairly different than its original version. Planners must consider many elements before developing a schedule. Employees have part-time and full-time opportunities. Planners must also account for employees' preferences in this planning process.</p>
  
<p align="justify">When it comes to health care, the picture changes even more. Hospitals must care for patients throughout the year non-stop. Needless to say, nurses are one of the crutial parts of this chain. They work in pretty much at every part of the health care provision. But even Today, hospital planning departments or head nurses generate schedules manually. There is an opportunity for automated solutions that can consider hospital demand needs, nurses' preferences, and regulations while developing schedules. The NRP problem addresses these issues and aims to generate powerful schedules for better utilization of these critical and scarce nurse resources.</p>

<p align="justify">In this study, we develop a hybrid solution by integrating Mixed Integer Programming (MIP)-based Fix-and-Relax (F&R) and Fix-and-Optimize (F&O) heuristics with Simulated Annealing (SA). Initial solutions are found by F&R and then they are improved by F&O-SA combination.</p>

<p align="justify">The main contributions to the literature are:

1. To the best of our knowledge, this study is the first implementation of the both of the MIP-based heuristics to the NRP problem.
1. The integration of the MIP-based heuristics and the SA algorithm is very unique that both techniques support each other to progress towards the optimum.
1. New best-known results are reported and computational results outperform many of the state-of-the-art solution techniques studied in the literature.
</p>

## The NRP Model Characteristics

<p align="justify">The model has hard constraints (HC) and soft constraints (SC). HCs are those that must be satisfied to obtain feasible schedules. SCs can be violated with a cost of penalties.</p>

1. ### Hard Constraints
   1. A nurse can only have one shift per day.
   1. Certain shifts cannot follow others. For instance, morning shift cannot follow a night shift.
   1. In a planning horizon, number of total assignments of a shift to a nurse connot be more than allowed limit.
   1. In a planning horizon, nurses must work between certain number of hours.
   1. Nurses cannot be assigned to shifts consecutively more than limits agreed in their contracts.
   1. Nurses must work certain number of days before they can take day-offs.
   1. After working certain number of days, nurses must be granted minimum day-offs stated in their contracts.
   1. Nurses cannot be assigned weekent shift more than the limits in their contracts.
   1. A shift cannot be assigned to a nurse if that day is a vacation day for the nurse.
1. ### Soft Constraints
   1. It is ideal
   1. Item 3b

## Main References

<p align="justify">Below are the major references we base our study on and compare our results to. The NRP model we study in this paper first was introduced by Curtois and Qu (2014) and further studied by Rahimian et al. (2017).</p>

1. Curtois, T. , & Qu, R. (2014). Computational results on new staffscheduling benchmark instances. Technical Report 06-Oct-2014. ASAP Research Group, School of Computer Science, University of Nottingham.

1. Rahimian, E., Akartunali, K., & Levine, J. (2017). A hybrid integer programming and variable neighbourhood search algorithm to solve nurse rostering problems. European Journal of Operational Research, 258, 411-423.
