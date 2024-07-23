# Project Overview
-	Implemented a robust cloud management system responsible for managing and monitoring a cluster of machines, enabling clients to host and execute jobs in a scalable and efficient manner.
- Utilized resource pods deployed on separate virtual machines (VMs) to simulate machine clusters. Each VM hosted a variable number of docker containers, which efficiently executed jobs of different workloads.
-	Implemented a Resource Manager (RM) as a key component to effectively manage and dynamically scale resources based on generated demand from end-user clients. The RM incorporated an Elasticity Manager, responsible for assessing and determining the optimal allocation of resources aligned with current demand and within the specified elastic scaling constraints set by cloud users. Additionally, integrated a Load Balancer, intelligently distributing incoming workloads across available servers to ensure efficient utilization.
- Designed and implemented RESTful APIs to seamlessly handle HTTP requests between clients and resource clusters, while concurrently developing a robust full-stack web application that delivered real-time metrics on resource usage and system performance.
- Implemented the project using Python and leveraged various frameworks and tools including Flask, Json, Pycurl and HAProxy to effectively simulate the cloud system.


## CMS Architecture
![Screenshot 2024-07-22 at 8 11 30 PM](https://github.com/user-attachments/assets/f3a00b83-f3bd-45a8-9c9c-84c63e49b7a9)


## Cloud Management System Dashboard
<img width="1440" alt="Screen Shot 2023-02-15 at 1 12 51 AM" src="https://user-images.githubusercontent.com/21010886/218947494-39f29c75-1c3e-4fe9-a4ce-a8ae197dc1e1.png">
<img width="1440" alt="Screen Shot 2023-02-15 at 1 13 32 AM" src="https://user-images.githubusercontent.com/21010886/218947572-917c0fc4-67cf-4d66-9418-dd3cca8542c9.png">
<img width="1440" alt="Screen Shot 2023-02-15 at 1 13 09 AM" src="https://user-images.githubusercontent.com/21010886/218947533-02afbbba-d065-4618-8da0-99944e7cffb4.png">


