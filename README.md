# DeliveryNetwork_Optimization

I, with a classmate at Cornell Tech, optimized the delivery network of a digital platform specializing in City A's logistics. Our project focuses on minimizing delivery distances while addressing customer demand and resource constraints through a series of optimization tasks. The system includes \(|M|\) warehouses, \(|N|\) customers, and \(k\) delivery drivers, assuming locations lie in a 2D plane with Euclidean distances. The tasks involve the following key components:

1. **Single Delivery per Driver:** We minimize the total distance for drivers delivering one item each, formulating this as a linear program (LP) and solving it for \(k = 6\).
2. **Multi-Delivery Routing:** Extending this to drivers handling up to five customers per route, we model it as a min-cost flow problem, analyzing its effectiveness under unlimited drivers.
3. **Integer Programming:** Reformulating the flow problem with integer constraints to allocate \(k\) drivers optimally, assuming routes begin and end without revisiting warehouses.
4. **Driver Analysis:** Exploring how varying \(k\) from 4 to 10 impacts total distances, presenting results through trend analysis.

This README outlines the structure of the tasks and serves as a guide for implementing and interpreting the results. Here's an overview of the project's questions:

1. **Question 1:** How do we minimize delivery distances for single-delivery drivers, and what is the optimal schedule for \(k = 6\)?
2. **Question 2:** Can min-cost flow modeling provide an efficient delivery schedule under unlimited drivers, and what are its limitations?
3. **Question 3:** How do we adjust the problem to incorporate integer constraints for optimal multi-delivery routes with \(k = 6\)?
4. **Question 4:** What is the relationship between the number of drivers and total delivery distance when \(k\) varies from 4 to 10?
