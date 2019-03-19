---
title: "A Modular Heterogeneous Stack for Deploying FPGAs and CPUs in the Data Center"
collection: publications
permalink: /publication/2019-02-25-a-modular-heterogeneous-stack-for-deploying-fpgas-and-cpus-in-the-data-center
type: 'Conference Paper'
date: 2019-02-25
year: 2019
authors: 'Nariman Eskandari, Naif Tarafdar, Daniel Ly-Ma,  Paul Chow'
venue: 'Proceedings of the 2019 ACM/SIGDA International Symposium on Field-Programmable Gate Arrays'
paperurl: 'http://tarafdar.github.io/files/2019-02-25-a-modular-heterogenous-stack-for-deploying-fpgas-and-cpus-in-the-data-center.pdf'
location: "Monterrey, California"
---


In this work we present a heterogeneous deployment stack, called Galapagos, that includes the abstraction of individual nodes (FPGAs and CPUs), the communication protocols between nodes and the orchestration and connection of these nodes into clusters. 
The stack we create is also highly modular, allowing users to explore a design space in the implementation of their cluster such as different network protocols or communication layers. 
The communication layer we have currently implemented within our hardware stack, called HUMboldt, handles heterogeneous communication between multiple FPGAs and CPUs. 
We implement HUMboldt using High-Level Synthesis (HLS) to ensure functional portability of communicatingkernels, allowing us to prototype hardware kernels in software.
Our results have shown that our modular approach to this heterogeneous deployment stack has introduced very little area and latency overhead in the FPGAs and can still perform at line-rate, bottlenecked solely by the network links connecting the nodes. 
Our results also highlight the scalability of our design as our performance remains limited by the network links when the cluster size increases.




[Download paper here](http://tarafdar.github.io/files/2019-02-25-a-modular-heterogenous-stack-for-deploying-fpgas-and-cpus-in-the-data-center.pdf)
[Download slides here](http://tarafdar.github.io/files/2019-02-25-a-modular-heterogenous-stack-for-deploying-fpgas-and-cpus-in-the-data-center.pptx)

