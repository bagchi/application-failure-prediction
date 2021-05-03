# Prediction of jobs submitted to one of Purdue's central computing clusters
This assignment deals with predicting failure of application executions (referred to as “job”) on Purdue ITaP’s central computing cluster. This is data that we have collected, collated, and analyzed as part of two projects from the National Science Foundation (NSF), one completed (“Computer System Failure Data Repository to Enable Data-Driven Dependability Research”, Project No. CNS-1513197) and one ongoing (“Open Computer System Usage Repository and Analytics Engine”, Project No. CNS-2016704).

For each job, we have data about the resources the job uses and whether the job succeeded or failed. The resources for which we have data are:
1.	Memory
2.	Network
3.	Local IO
4.	Network File System (NFS)

We are releasing the training data, which has about 8% failure data (this is referred to as the “positive class”). You will build Machine Learning models in Python to predict whether a job will fail or not, given the resource usage data. We will evaluate your model on some test data that we are not releasing now and that we will use later at the time of the evaluation. 

Two papers that explain and report on this dataset are:
* Kumar, Rakesh, Saurabh Jha, Ashraf Mahgoub, Rajesh Kalyanam, Stephen Harrell, Xiaohui Carol Song, Zbigniew Kalbarczyk, William Kramer, Ravishankar Iyer, and Saurabh Bagchi. "The Mystery of the Failing Jobs: Insights from Operational Data from Two University-Wide Computing Systems." In 2020 50th Annual IEEE/IFIP International Conference on Dependable Systems and Networks (DSN), pp. 158-171. IEEE, 2020.
* Jha, Saurabh, Archit Patke, Jim Brandt, Ann Gentile, Benjamin Lim, Mike Showerman, Greg Bauer et al. "Measuring congestion in high-performance datacenter interconnects." In 17th USENIX Symposium on Networked Systems Design and Implementation (NSDI), pp. 37-57. 2020.
