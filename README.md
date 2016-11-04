# MLA-DCOS
# Master Less Architecture - Data Center Operating System


In the current world of distributed system, we have a master to control the data center or a cluster.

Issue: If master goes down, then we are clueless, solution for this been found with High Availibity concept. Currently Zookeeeper is used in mesos to make the data center to be highly available. If the Zookeeper itself can be down, to resolve this zookeeper qorum will be created to have even zookeeper to be available all the time.

If you think, if we have a architecture at the core level (operating system) which is SELF-Managed. That will be a great idea then, which is not depends on anything and which will not report to anyone. Now a days machines are so matured that can handle itself with the help of AI.

It does the given task, and sends back the result to the framework.

Here we may feel the issue that, each machine will be heavily loaded but we want the execution node should always be lighter. Which can be achieved with the help of demon based model.

There are couple of issues are there like how the load balancing will happen? what is the point of contact for data center? so many...

These issues will be addressed timely...

Load balancing can be done at the switch level only, which decides whom to connect.

Currently Citrix has product which does the load balancer (Netflix) at the switch (H/w) level to know the first point of contact. The application level load balancer is of light weight will be there in each node to delegate the work if it feels I am overloaded.

How to achive highly available node? We would be having a file which contains the list of private IP addresses, randomly let other few nodes (care-takers) watch me either I am alive rather that I send "I am alive". Let them fetch the info about What are the jobs I am executing/performing from whom (which frameworks).

Are we achieving the basic features of Data Center Operating System?
I belive YES... still it needs to be refined... 
   1. Scalability
   2. High Availibility
   3. Load Balancing - Can be achived at network switch level for point of contact, at application level, we need to have separate LB to delegate the over burdened tasks / time consuming task.
   4. High Performance - will not deligate the task and wait for the result

Any one can comment or give feedback.
