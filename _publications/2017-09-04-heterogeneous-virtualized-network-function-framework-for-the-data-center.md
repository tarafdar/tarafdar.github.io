---
title: "Heterogeneous virtualized network function framework for the data center"
collection: publications
permalink: /publication/2017-09-04-heterogeneous-virtualized-network-function-framework-for-the-data-center
excerpt: 'We present a framework for creating heterogeneous virtualized network function (VNF) service chains from cloud data center resources...'
type: 'conf'
date: 2017-09-04
authors: 'Naif Tarafdar, Thomas Lin, Nariman Eskandari, David Lion, Alberto Leon-Garcia, Paul Chow'
venue: '2017 27th International Conference on Field Programmable Logic and Applications (FPL)'
paperurl: 'http://tarafdar.github.io/files/2017-09-04-heterogeneous-virtualized-network-function-framework-for-the-data-center.pdf'
location: "Ghent, Belgium"
---

We present a framework for creating heterogeneous virtualized network function (VNF) service chains from cloud data center resources. Traditionally, these functions are packaged in software images within a catalog of networking applications that can be loaded onto a virtual machine CPU, and can be offered to users as a service. Our framework combines the best of both software and hardware by allowing users to chain traditional software-based VNFs with hardware-based VNFs that the user provides as an IP to generate a bitstream or a pre-generated VNF as part of a library. To accomplish this, our framework first creates the hardware bitstreams and programs the FPGA VNFs, loads any software VNFs requested, and programs the network to daisy chain the VNFs together. Furthermore, this enables an incremental design flow where the user can start by implementing a chain of VNFs in software and incrementally substitute software VNFs for their hardware counterparts. Our paper investigates two case studies to show the ability to switch between hardware and software VNFs in our framework and to demonstrate the benefit of using hardware VNFs. The first study is signature matching at fixed offsets, similar to matching packet headers. In this case study, the CPU can keep up at line-rate using specialized networking drivers. The second case study involves string matching within a packet, which requires scanning through the entire frame. In this case, the CPU performance drops to approximately 20 percent of the input rate, whereas the FPGA can continue to keep up at line-rate.



[Download paper here](http://tarafdar.github.io/files/2017-09-04-heterogeneous-virtualized-network-function-framework-for-the-data-center.pdf)

[Download slides here](http://tarafdar.github.io/files/2017-09-04-heterogeneous-virtualized-network-function-framework-for-the-data-center.pptx)
