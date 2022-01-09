---
title: "17th Workshop on Virtualization in High-Performance Cloud Computing"
featured_image: '/images/hamburg.png'
description: "held in conjunction with ISC-HPC, Hamburg, DE, May 29th - Jun 2nd 2022"
#omit_header_text: true
type: page
#menu: main
---

### Important Dates

Rolling abstract submission: Submission opens Feb 14th, 2022. Submit your abstract no later than April 12th, 2022

April 19th, 2022 Paper submission deadline (Springer LNCS)

May 3, 2022 - Acceptance notification

June 2th, 2022 - Workshop Day

July 10th, 2022 - Camera-ready version due

### Overview

Containers and virtualization technologies constitute key enabling factors for
flexible resource management in modern data centers, and particularly in cloud
environments. Cloud providers need to manage complex infrastructures in a
seamless fashion to support the highly dynamic and heterogeneous workloads and
hosted applications customers deploy. Similarly, HPC environments have been
increasingly adopting techniques that enable flexible management of vast
computing and networking resources, close to marginal provisioning cost, which
is unprecedented in the history of scientific and commercial computing. Most
recently, Function as a Service (Faas) and Serverless computing, utilizing
lightweight VMs-containers widens the spectrum of applications that can be
deployed in a cloud environment, especially in an HPC context. Here,
HPC-provided services can be become accessible to distributed workloads outside
of large cluster environments. 

Various virtualization-containerization technologies contribute to the overall
picture in different ways: machine virtualization, with its capability to
enable consolidation of multiple under­utilized servers with heterogeneous
software and operating systems (OSes), and its capability to live­-migrate a
fully operating virtual machine (VM) with a very short downtime, enables novel
and dynamic ways to manage physical servers; OS-­level virtualization (i.e.,
containerization), with its capability to isolate multiple user­-space
environments and to allow for their co­existence within the same OS kernel,
promises to provide many of the advantages of machine virtualization with high
levels of responsiveness and performance; lastly, unikernels provide for many
virtualization benefits with a minimized OS/library surface. I/O Virtualization
in turn allows physical network interfaces to take traffic from multiple VMs or
containers; network virtualization, with its capability to create logical
network overlays that are independent of the underlying physical topology is
furthermore enabling virtualization of HPC infrastructures.


### Topics of Interest

The VHPC program committee solicits original, high-quality submissions related
to virtualization across the entire software stack with a special focus on the
intersection of HPC, containers-virtualization and the cloud.

Major Topics: 
- HPC on Containers and VMs
- Containerized applications with OS-level virtualization
- Lightweight applications with Unikernels
- HP-as-a-Service

each major topic encompassing design/architecture, management, performance
management, modeling and configuration/tooling:

Design / Architecture:
- Containers and OS-level virtualization (LXC, Docker, rkt, Singularity, Shifter, i.a.)
- Hypervisor support for heterogeneous resources (GPUs, co-processors, FPGAs, etc.)
- Hypervisor extensions to mitigate side-channel attacks
 ([micro-]architectural timing attacks, privilege escalation)
- VM & Container trust and security models
- Multi-environment coupling, system software supporting in-situ analysis with HPC simulation
- Cloud reliability, fault-tolerance and high-availability
- Energy-efficient and power-aware virtualization
- Containers inside VMs with hypervisor isolation
- Virtualization support for emerging memory technologies
- Lightweight/specialized operating systems in conjunction with virtual machines
- Hypervisor support for heterogeneous resources (GPUs, co-processors, FPGAs, etc.)
- Novel unikernels and use cases for virtualized HPC environments
- ARM-based hypervisors, ARM virtualization extensions

Management:
- Container and VM management for HPC and cloud environments
- HPC services integration, services to support HPC 
- Service and on-demand scheduling & resource management
- Dedicated workload management with VMs or containers
- Workflow coupling with VMs and containers
- Unikernel, lightweight VM application management
- Environments and tools for operating containerized environments (batch, orchestration)
- Novel models for non-HPC workload provisioning on HPC resources

Performance Measurements and Modeling:
- Performance improvements for or driven by unikernels
- Optimizations of virtual machine monitor platforms and hypervisors
- Scalability analysis of VMs and/or containers at large scale
- Performance measurement, modeling and monitoring of virtualized/cloud workloads
- Virtualization in supercomputing environments, HPC clusters, HPC in the cloud

Configuration / Tooling:
- Tool support for unikernels: configuration/build environments, debuggers, profilers
- Job scheduling/control/policy and container placement in virtualized environments
- Operating MPI in containers/VMs and Unikernels  
- Software defined networks and network virtualization
- GPU virtualization operationalization


The Workshop on Virtualization in High­-Performance Cloud Computing (VHPC) aims
to bring together researchers and industrial practitioners facing the
challenges posed by virtualization in order to foster discussion,
collaboration, mutual exchange of knowledge and experience, enabling research
to ultimately provide novel solutions for virtualized computing systems of
tomorrow.

The workshop will be one day in length, composed of 20 min paper presentations,
each followed by 10 min discussion sections, plus lightning talks that are
limited to 5 minutes.  Presentations may be accompanied by interactive
demonstrations.


### Organization

Michael Alexander (chair), BOKU Vienna <malexand@boku.ac.at>

Anastassios Nanos (co-chair), Nubificus Ltd. <ananos@nubificus.co.uk>

Tommaso Cucinotta (co-chair), Scuola Superiore Sant'Anna <tommaso.cucinotta@santannapisa.it>


#### Technical Program Committee 


Stergios Anastasiadis, University of Ioannina, Greece

Jakob Blomer, CERN, Europe

Eduardo César, Universidad Autonoma de Barcelona, Spain

Taylor Childers, Argonne National Laboratory, USA

Stephen Crago, USC ISI, USA

Tommaso Cucinotta, St. Anna School of Advanced Studies, Italy

Christoffer Dall, Columbia University, USA

Patrick Dreher, MIT, USA

Kyle Hale, Northwestern University, USA

Bob Killen, University of Michigan, USA

Brian Kocoloski, Washington University, USA

John Lange, University of Pittsburgh, USA

Giuseppe Lettieri, University of Pisa, Italy

Qing Liu, Oak Ridge National Laboratory, USA

Nikos Parlavantzas, IRISA, France

Kevin Pedretti, Sandia National Laboratories, USA

Amer Qouneh, Western New England University, USA

Carlos Reaño, Queen’s University Belfast, UK

Borja Sotomayor, University of Chicago, USA

Jonathan Sparks, Cray, USA

Joe Stubbs, Texas Advanced Computing Center, USA

Anata Tiwari, San Diego Supercomputer Center, USA

Kurt Tutschku, Blekinge Institute of Technology, Sweden

John Walters, USC ISI, USA

Yasuhiro Watashiba, Osaka University, Japan

Chao-Tung Yang, Tunghai University, Taiwan

Na Zhang, VMware, USA


### Paper Submission-Publication

Papers submitted to the workshop will be reviewed by at least two members of
the program committee and external reviewers. Submissions should include
abstract, keywords, the e-mail address of the corresponding author, and must
not exceed 10 pages, including tables and figures at a main font size no
smaller than 11 points. 

Submission of a paper should be regarded as a commitment that, should the paper
be accepted, at least one of the authors will register and attend the
conference to present the work. 

Accepted papers will be published in a Springer LNCS volume. The format must be
according to the [Springer LNCS
Style](ftp://ftp.springernature.com/cs-proceeding/llncs/llncs2e.zip). Initial
submissions are in PDF; authors of accepted papers will be requested to provide
source files

Submission link: https://edas.info/newPaper.php?c=29178

### Lightning Talks

Lightning Talks are non-paper track, synoptical in nature and are strictly
limited to 5 minutes.  They can be used to gain early feedback on ongoing
research, for demonstrations, to present research results, early research
ideas, perspectives and positions of interest to the community. Submit abstract
via the main submission link.


### General Information

The workshop is one day in length and will be held in conjunction with the
International Supercomputing Conference - High Performance (ISC) 2022, June 2,
Hamburg, Germany.

