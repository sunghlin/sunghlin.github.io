---
layout: article
titles:
  # @start locale config
      en      : &EN       Projects
      en-GB   : *EN
      en-US   : *EN
      en-CA   : *EN
      en-AU   : *EN
      zh-Hans : &ZH_HANS  
      zh      : *ZH_HANS
      zh-CN   : *ZH_HANS
      zh-SG   : *ZH_HANS
      zh-Hant : &ZH_HANT  專案
      zh-TW   : *ZH_HANT
      zh-HK   : *ZH_HANT
      ko      : &KO       
      ko-KR   : *KO
      fr      : &FR
      fr-BE   : *FR
      fr-CA   : *FR
      fr-CH   : *FR
      fr-FR   : *FR
      fr-LU   : *FR
  # @end locale config
show_title: true
title: Projects
aside:
  toc: true
#key: page-about
---

## Large-Scale Machine Learning

### ONTAP AI 

`NetApp`{:.success}

Built on a verified architecture that combines NVIDIA DGX-1 supercomputers, NetApp AFF storage, and Cisco networking supercharges your AI/DL environments.
- Scalable AI Infrastructure: Designing for Real-World Deep Learning Use Cases [[Technical Report]](https://www.netapp.com/us/media/nva-1121-design.pdf)

### Large-scale Deep Learning in Shared Clusters

`Research`{:.error} `USC`{:.success} `NetApp`{:.success}

We address two important problems for the application of this strategy to large-scale clusters and multiple, heterogeneous jobs. 
1. We propose and validate a queueing model to estimate the throughput of a training job as a function of the number of nodes assigned to the job; this model targets asynchronous Stochastic Gradient Descent (SGD), and requires only data from quick, two-node profiling. 
2. Throughput estimations are then used to explore several classes of scheduling heuristics to reduce response time in a scenario where heterogeneous jobs are continuously submitted to a large-scale cluster. These scheduling algorithms dynamically select which jobs to run and how many nodes to assign to each job, based on different trade-offs between service time reduction and efficiency (e.g., speedup per additional node). Heuristics are evaluated through extensive simulations of realistic DNN workloads, also investigating the effects of early termination, a common scenario for DNN training jobs.

Paper is published in IEEE MASCOTS 2018, with title __A Model-based Approach to Streamlining Distributed Training for Asynchronous SGD__
{:.warning}

## Cloud Computing

### Resource Sharing for the Small Cloud

`Research`{:.error} `USC`{:.success}

Approximated an exponential growth stochastic model via TransientAnalysis to estimate the number of virtual machines exchanged within the cloud federation; developed market-basedgame-theoretic model that converges to efficient virtual machine sharing decisions at market equilibrium

Paper is published in IEEE ICDCS 2017, with title __Performance Driven Resource Sharing Markets for the Small Cloud__
{:.warning}

## Distributed System

### Improving SQL-MR Execution Engine 

`Intern`{:.error} `Teradata`{:.success}

I profiled the performance of SQL-MapReduce Execution Engine and re-designed the mechanism to reduce the data transmission and I/O time between user defined functions and databases. 
1. Aggregating the output: Instead of sending result row by row in the original design, I caches rows and send it once to reduce the I/O time. This improves the performance by at least 20%. 
2. Eager sending: Sending cached data immediately if it is available. This improves the performance by 10%. 

### MediaWall Framework 

`Intern`{:.error} `FXPAL`{:.success}

I designed and developed media wall framework which instantiates and controls virtual machines to enable diversified screen presentations that are not limited by pre-installed projectors. Since this system works in a network, I built a centralized system to manage network resources and handle interactions between remote machines and services to enhance the performance. Moreover, I developed APIs to provide programmatic access from web-enabled platforms. To provide access interface, I programmed Web-based Graphical User Interfaces to enable presenters to manage projected screens on walls

<!---
#### Speed up loading large data sets to a Facebook-like system on Cassandra <span class="default-span place-usc">USC - Research</span>
Built Cassandra clusters with small-scale OpenStack virtual machines suitable for Facebook-like social network. Designed mechanisms equally distributing the workload to all running virtual machines. Coded multi-thread systems to handle different kinds of inputs without leaving the system idle.
--->

<!---
#### Performance Analysis for the Speed-Sensitive Channel Assignment
Developed and simulated probability models to correctly analyse the performance of channel assignment with rapid cell phone hand-offs. Explored the effect of adopting random walk or human walk to probability models for assigning channels.
--->
## Networking / Peer-to-Peer (P2P)

### Hybrid P2P Video Streaming

`Research`{:.error} `USC`{:.success}

Re-designed sharing mechanisms to eliminate the problem of video playback pausesby up to 80% while providing sufficiently high quality of videos to peers; developed market-based game-theoretic modelthat uses advertisements as an incentive to satisfy all the market stakeholders.

Paper is published in IEEE/ACM IWQoS 2015, with title __Sustaining Ad-Driven P2P Streaming Ecosystems A Market-Based Approach__, following up a journal in IEEE Transactions on Multimedia with a title __On Market-Driven Hybrid-P2P Video Streaming__
{:.warning}

<!---
### Implemented a distributed large-scale Digital Signage system 

`Research`{:.success} `NTU`{:.info}

Implemented a distributed large-scale Digital Signage system. Developed partial storage systems for video contents and advertisements by combining Content Distribution Network and Peer-to-Peer technologies
--->

### P2P framework for Vehicular Ad Hoc Networks

`Research`{:.error} `NTU`{:.success}

Due to the vehicle's movement and inherent characteristics of wireless channel, how to discover and retrieve the required contents has become a challenging issue in a hybrid network including vehicular ad hoc networks (VANETs) and the Internet. In this paper, we propose a social cluster-based P2P framework that estimates similarity and connection condition among peers to provide mobile peers efficient resource discovery and retrieval. The idea of our framework is to consider a mobile peer's preference and its connectivity such as the lifetime or the bandwidth for a wireless link. Specifically, there are two major components in our framework. First, a social cluster-based overlay structure and lifetime-aware flooding scheme enable mobile peers to discover resource through the Internet and VANETs. Second, a connectivity-aware retrieval scheme considers connection lifetime and bandwidth schedules and determines how to retrieve resource from available peers. The simulation results show that, compared with other existing P2P schemes, our social cluster-based P2P framework is able to quickly locate more available peers holding the required contents and achieve a higher retrieval ratio.

Paper is published in IEEE WCNC 2009, with title __A Novel Social Cluster-Based P2P Framework for Integrating VANETs with the Internet__
{:.warning}

### Implemented a real P2P IPTV system 

`Research`{:.error} `NTU`{:.success}

Coded P2P Internet Protocol Television(IPTV) systems supporting channel browsing in Windows systems. Explored and measured effect of parameter settings for different network capability environments.

<!---
#### Exploit File Similarity in Peer-to-Peer Networks <span class="default-span place-ntu">NTU</span>
Explored probability of having the same chunks among files in eMule file-sharing environments. Developed sharing mechanism capable of using similar chunks to speed up peer-to-peer file downloading.
--->