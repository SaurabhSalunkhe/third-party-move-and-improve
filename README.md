# Oracle Cloud Infrastructure: Built to support Third-Party Apps

## Introduction
Oracle offers a complete portfolio of products, services, and differentiated capabilities to power your enterprise. For business users, Oracle offers ready-to-go networking options, server shapes, and enterprise-grade infrastructure that drives better business outcomes. With Oracle's Autonomous Database and Analytics tools, data scientists and application developers have a full suite of cloud services to build, deploy, and manage any type of solution. Machine learning is working behind the scenes in these products to automate security patching, backups, and optimize database query performance, which helps to eliminate human error and repetitive manual tasks so organizations can focus on higher-value activities.

This lab series is part of *Oracle Cloud Infrastructure's Third Party Move & Improve* workshop. This series will walk you through the process of migrating an existing eCommerce application from an on-prem environment to being natively deployed within the cloud. It will walk you through how to capture a custom image of this app and deploy it on OCI with necessary infrastructure like Networking, Security Lists and route rules. The lab will also walk you through the process of making the application highly-available in the case of disaster scenarios by leveraging Oracle's DNS services for traffic steering. Finally, the lab will leverage PaaS services such as Autonomous Data Warehouse (ADW), Oracle Analytics Cloud (OAC), and Oracle Integration Cloud (OIC) in order to show how you can gain even more insight into your application data.

Attached below is a sample architecture of the final solution:
![](/images/Architecture.png)

*Note:* This lab is intended to be a comprehensive full cloud showcase. As such, it is assumed a user going through this workshop will be provisioning resources and creating users from scratch. If you decide to use existing infrastructure or resources, be aware and keep note of your namings so resources don't overlap and conflict.

*Note:* Additionally, as much as possible, do not stray away from the naming conventions used for resources in this worshop. You may run into errors if you do. 

## Objectives
* Provision custom compute with OSCommerce Image
* Provision underlying infrastructure such as networking, security lists etc
* Make application Highly Available with Traffic Steering Policies and Active Failover
* Provision OAC, OIC, and ADW Instances
* Pull data from MySQL database into ADW
* Perform Analytics with OAC  
