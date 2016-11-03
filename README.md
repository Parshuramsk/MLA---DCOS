# MLA-DCOS
Master Less Architecture - Data Center Operating System


In the current world of distributed system, we have a master to control the data center or a cluster.

Issue: If master goes down, then we are clueless, solution for this been found with High Availibity concept. Currently Zookeeeper is used in mesos to make the data center to be highly available. If the Zookeeper itself can be down, to resolve this zookeeper corum will be created to have even zookeeper to be available all the time.

If you think, if we have a architecture at the core level (operating system) which is SELF-Manged. That will be a great idea then, which is not depends on anything and which will not report to anyone.

It does the given task, and sends back the result to the framework.

Here we may feel the issue that, each machine will be heavily loaded but we want the execution node should always be lighter. Which can be achieved with the help of demon based model.

There are couple of issues are there like how the load balancing will happen? what is the point of contact for data center? so many...

These issues will be addressed timely... 

Any one can comment or give feedback.
