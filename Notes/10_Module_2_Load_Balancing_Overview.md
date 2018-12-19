# Load Balancing

----
> Purpose of a **hardware load balancer** is to receive data at one IP address and redirect it to multiple servers.

### Load balancing **as a service** in GCP is much more **flexible** than a hardware load balancer.
* For example, load balancing in GCP can be configured to redirect sessions based on the geographic location of the requester, sending the traffic to the closest available server.
* GCP load balancing can be configured to send traffic to pools of servers with some pool serving as overflow capacity to others.
* This kind of flexibility and behavior comes with additional **configuration complexity**, which can all be easily configured using the GCP console.
* We can use load balancing to take more advantage of an augmented infrastructure.
* We've already configured networking between different virtual machines, but how are we going to route our traffic between multiple virtual machines? Load balancing is the first thing that comes into play.


----
## In this module, we will cover 
* managed instanced groups
* different types of load balancing that you can configure using GCP. 

----
## 5 types of load balancing
* HTTP(S), SSL Proxy, and TCP Proxy load balancing are **global services**
* network and internal load balancing are **regional**