[ABSTRACT](/README.md) | [OVERVIEW](/Overview/README.md)  | [SOLUTION APPROACH](/SolutionApproach/README.md)  | [INSTANCES](/Instances/README.md)  | [COMPUTATIONAL RESULTS](/ComputationalResults/README.md)
------------- | ------------- | ------------- | ------------- | -------------

`COMPUTATIONAL RESULTS`
====================
## Comparison Between Studies

<p align="justify">Below table summarizes scores between studies in the literature. Bold and highlighted scores are the new best-known results we report in this study. The hybrid algorithm mainly outperforms the Ejection Chain, Gurobi, and Branch & Price algorithms. The IP & VNS Hybrid is also a powerful algorithm as seen in the tables.
  
  #### *10-minute runtime*
  
  Instances | IP&VNS Hybrid | Ejection Chain | Gurobi | Our Study
  --- | --- | --- | --- | --- 
  Instance 01 | 607 | 607 | 607 | 607
  Instance 02 | 828 | 923 | 828 | 828
  Instance 03 | 1,001 | 1,003 | 1,001 | 1,001
  Instance 04 | 1,716 | 1,719 | 1,716 | 1,716
  Instance 05 | 1,143 | 1,439 | 1,143 | 1,143
  Instance 06 | 1,950 | 2,344 | 1,950 | 1,950
  Instance 07 | 1,056 | 1,284 | 1,056 | 1,056
  Instance 08 | 1,364 | 2,529 | 8,995 | **`1,341`**
  Instance 09 | 439 | 474 | 439 | 439
  Instance 10 | 4,631 | 4,999 | 4,631 | 4,631
  Instance 11 | 3,443 | 3,967 | 3,443 | 3,443
  Instance 12 | 4,042 | 5,611 | 4,045 | 4,044
  Instance 13 | 3,109 | 8,707 | 500,410 | 3,200
  Instance 14 | 1,281 | 2,542 | 1,482 | 1,295
  Instance 15 | 4,144 | 6,049 | 78,144 | 4,420
  Instance 16 | 3,306 | 4,343 | 3,521 | **`3,253`**
  Instance 17 | 5,760 | 7,835 | 6,149 | 6,138
  Instance 18 | 5,049 | 6,404 | 7,950 | **`5,000`**
  Instance 19 | 3,974 | 6,522 | 29,968 | **`3,809`**

  #### *60-minute runtime*
  
  Instances | IP&VNS Hybrid | Ejection Chain | Gurobi | B&P | Our Study
  --- | --- | --- | --- | --- | --- | 
  Instance 01 | 607 | 607 | 607 | 607 | 607
  Instance 02 | 828 | 837 | 828 | 828 | 828
  Instance 03 | 1,001 | 1,003 | 1,001 | 1,001 | 1,001
  Instance 04 | 1,716 | 1,718 | 1,716 | 1,716 | 1,716
  Instance 05 | 1,143 | 1,358 | 1,143 | 1,160 | 1,143
  Instance 06 | 1,950 | 2,258 | 1,950 | 1,952 | 1,950
  Instance 07 | 1,056 | 1,269 | 1,056 | 1,058 | 1,056
  Instance 08 | 1,344 | 2,260 | 1,323 | 1,308 | **`1,322`**
  Instance 09 | 439 | 463 | 439 | 439 | 439
  Instance 10 | 4,631 | 4,797 | 4,631 | 4,631 | 4,631
  Instance 11 | 3,443 | 3,661 | 3,443 | 3,443 | 3,443
  Instance 12 | 4,040 | 5,211 | 4,040 | 4,046 | 4,040
  Instance 13 | 1,905 | 3,037 | 3,109 | – | 2,900
  Instance 14 | 1,279 | 1,847 | 1,280 | – | 1,280
  Instance 15 | 3,928 | 5,935 | 4,964 | – | 4,190
  Instance 16 | 3,225 | 4,048 | 3,233 | 3,323 | 3,225
  Instance 17 | 5,750 | 7,835 | 5,851 | – | 5,848
  Instance 18 | 4,662 | 6,404 | 4,760 | – | **`4,650`**
  Instance 19 | 3,224 | 5,531 | 5,420 | – | **`3,218`**

  >  Ejection Chain, Gurobi, and B&P by Curtois and Qu (2014)
  
  >  IP&VNS Hybrid by Rahimian et al. (2017)

## Final Schedules

<p align="justify">In this section, we present the final resulting schedules we have obtained by applying the hybrid algorithm for transparecy and validation purposes. As discussed, final schedules are printed to Excel files.</p>
