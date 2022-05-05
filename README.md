# CMPE-275- RESEARCH-LAB3

# Scope:

The goal of Research Lab 3 (RL3) is to understand distributed frameworks in
other application domains. We will explore MPI-based application for parallel processing in the
High-Performance Computing (HPC) domain. While this domain traditionally supported
computational work in the science domains, it is/can be extended to other data intensive
applications.


# Technologies Used:

Open-MPI , C, C++

# MessagePassingInterface

The message passing interface (MPI) is a standardized means of exchanging messages between multiple computers running a parallel program across distributed memory. In parallel computing, multiple computers -- or even multiple processor cores within the same computer -- are called nodes.


![MPI](https://user-images.githubusercontent.com/89316938/166971521-1826c3c1-9159-4fe6-9f32-d7caa72a3a24.png)

MPI_REDUCE :

![mpi_reduce_1](https://user-images.githubusercontent.com/89316938/166974702-a3cf14d4-1258-4252-975d-34063ce527a9.png)

![mpi_reduce_2](https://user-images.githubusercontent.com/89316938/166974712-e4a44af8-4038-4704-af3a-f22fa5761f60.png)

MPI_ALLReduce :
![mpi_allreduce_1](https://user-images.githubusercontent.com/89316938/166974723-e6b4671e-6050-4d0a-81d3-29586ca1ad15.png)

Broadcastvsscatter :
![broadcastvsscatter](https://user-images.githubusercontent.com/89316938/166974765-30ff3a2f-0141-490a-97c2-78377043f5a1.png)

Gather :
![gather](https://user-images.githubusercontent.com/89316938/166974770-fe2bab2d-e548-4188-9426-1f09408fe347.png)

AllGather :
![allgather](https://user-images.githubusercontent.com/89316938/166974776-67200c09-dc7b-4d64-8038-78167aa3961d.png)
