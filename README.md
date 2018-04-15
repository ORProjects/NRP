[ABSTRACT](/README.md) | [OVERVIEW](Overview/README.md)  | [SOLUTION APPROACH](SolutionApproach/README.md)  | [INSTANCES](Instances/README.md)  | [COMPUTATIONAL RESULTS](ComputationalResults/README.md)
------------- | ------------- | ------------- | ------------- | -------------

`ABSTRACT`
====================
A hybrid mixed integer programming based heuristics and simulated annealing approach for solving nurse rostering problems
====================
Aykut Melih Turhanᵃ, Bilge Bilgenᵇ*

ᵃ Department of Industrial Engineering, The Graduate School of Natural and Applied Sciences, Dokuz Eylul University, Tinaztepe Campus, Buca, 35160 Izmir, Turkey

ᵇ Department of Industrial Engineering, Dokuz Eylul University, Tinaztepe Campus, Buca, 35160 Izmir, Turkey



Abstract
====================
<p align="justify">The Nurse Rostering Problem (NRP) is a complex scheduling problem in which nurses must be assigned to shifts according to a set of constraints. The NRP is difficult to solve to optimality due to its combinatorial structure. In this paper, we propose a hybrid solution algorithm that combines Mixed Integer Programming (MIP) based heuristics—namely Fix-and-Relax (F&R) and Fix-and-Optimize (F&O)—and Simulated Annealing (SA) to solve the NRP. In MIP-based heuristics, a problem is decomposed into a set of smaller problems and each problem is iteratively solved to optimality. In the hybrid approach, high-quality initial solutions are obtained via the F&R algorithm and fed to the SA part of the algorithm. When solutions can no longer be improved, the F&O algorithm is inserted into the SA algorithm. This enables the hybrid algorithm to diversify the search space and provide better solutions. To assess the quality and efficiency of the hybrid approach, we use 24 publicly available test instances recently introduced in literature in the field. Computational results show that the hybrid method outperforms other advanced solution techniques in most of the test data and seven new best-known results are reported.</p>

**Keywords:**
OR in health services, nurse rostering problem, fix-and-relax, fix-and-optimize, simulated annealing
***Corresponding author. Tel.**: +90 232 301 7615; **Fax**: +90 232 301 7608.
**E-mail address**: bilge.bilgen@deu.edu.tr.
