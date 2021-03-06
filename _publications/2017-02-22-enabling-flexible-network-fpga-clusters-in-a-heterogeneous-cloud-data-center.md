---
title: "Enabling flexible network FPGA clusters in a heterogeneous cloud data center"
collection: publications
permalink: /publication/2017-02-22-enabling-flexible-network-fpga-clusters-in-a-heterogeneous-cloud-data-center
excerpt: 'We present a framework for creating network FPGA clusters in a heterogeneous cloud data center...' 
type: 'Conference Paper'
date: 2017-02-22
year: 2017
authors: 'Naif Tarafdar, Thomas Lin, Eric Fukuda, Hadi Bannazadeh, Alberto Leon-Garcia, Paul Chow'
venue: 'Proceedings of the 2017 ACM/SIGDA International Symposium on Field-Programmable Gate Arrays'
paperurl: 'http://tarafdar.github.io/files/2017-2-22-enabling-flexible-network-fpga-clusters-in-a-heterogeneous-cloud-data-center.pdf'
location: "Monterrey, California"
---

We present a framework for creating network FPGA clusters in a heterogeneous cloud data center. The FPGA clusters are created using a logical kernel description describing how a group of FPGA kernels are to be connected (independent of which FPGA these kernels are on), and an FPGA mapping file. The kernels within a cluster can be replicated with simple directives within this framework. The FPGAs can communicate to any other network device in the data center, including CPUs, GPUs, and IoT devices (such as sensors). This heterogeneous cloud manages these devices with the use of OpenStack. We observe that our infrastructure is limited due to the physical infrastructure such as the 1~Gb Ethernet connection. Our framework however can be ported to other physical infrastructures. We tested our infrastructure with a database acceleration application. This application was replicated six times across three FPGAs within our cluster and we observed a throughput increase of six times as this scaled linearly. Our framework generates the OpenStack calls needed to reserve the compute devices, creates the network connections (and retrieve MAC addresses), generate the bitstreams, programs the devices, and Conference Paperigure the devices with the appropriate MAC addresses, creating a ready-to-use network device that can interact with any other network device in the data center.



[Download paper here](http://tarafdar.github.io/files/2017-02-22-enabling-flexible-network-fpga-clusters-in-a-heterogeneous-cloud-data-center.pdf)
[Download slides here](http://tarafdar.github.io/files/2017-02-22-enabling-flexible-network-fpga-clusters-in-a-heterogeneous-cloud-data-center.pptx)

