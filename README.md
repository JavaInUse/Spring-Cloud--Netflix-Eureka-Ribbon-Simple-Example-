# Spring-Cloud--Netflix-Eureka-Ribbon-Simple-Example-

In this post we make use of Netflix Ribbon for Client Side Load Balancing. [In previous posts we made use of Netflix component Eureka for service registry and discovery](https://www.javainuse.com/spring/spring_eurekaregister).

In [previous posts we developed two services employee-producer and employee-consumer](https://www.javainuse.com/spring/spring_eurekaregister). Suppose other modules are also calling and consuming employee-producer module services. So the load at employee-producer is high. To deal with this we this we deploy multiple instances of employee-producer. Suppose two in this case. Now we will have to use a Load Balancer to route any incoming requests to either one of these two services.

![](https://www.javainuse.com/sprcloud_5-1.jpg)

This tutorial is explained in the below Youtube Video.<br>
![https://www.javainuse.com/netflix4-min.jpg](https://youtu.be/rsrYZ5cEySE)
