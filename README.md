# Parallel and Distributed Databases
This document provides an overview of the skills and concepts I developed through assignments in this DBMS course, focusing on SQL query optimization, parallel algorithms, and computational cost analysis.

Skills Acquired
1. SQL Query Execution and Optimization
- Execution Planning: Developed efficient SQL execution plans using memory optimization techniques to minimize I/O costs.
- Cost Estimation: Gained experience in estimating processing times based on the number of memory pages and data distribution within relations. This involved calculating the cost of various execution strategies, particularly when memory pages were limited.

2. Memory Management and Optimization Techniques
- Memory Page Constraints: Created strategies to execute queries with limited memory pages and computed the expected I/O cost.
- Impact of Additional Memory: Analyzed how additional memory pages can improve computational efficiency, reducing the I/O cost.

3. Parallel Algorithms in Distributed Systems
- Grace Hash Join Algorithm: Analyzed the Grace algorithm phases to perform parallel joins in a shared-nothing environment. I learned to estimate read and write costs across nodes, handling data skew and computational load balancing.
- ABJ Algorithm: Applied the ABJ (Asynchronous Bucket Join) algorithm, understanding its four phases in a distributed setting. This included computation of individual phase costs, such as read, write, and overall computational expenses, while accounting for data skew and load balancing.

4. Cost Analysis and Load Balancing
- Data Skew Management: Handled uneven data distribution across nodes, calculating costs under skewed workloads, and identifying the impact on total computation time.

