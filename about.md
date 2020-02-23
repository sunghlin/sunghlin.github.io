---
layout: article
titles:
  # @start locale config
      en      : &EN       About
      en-GB   : *EN
      en-US   : *EN
      en-CA   : *EN
      en-AU   : *EN
      zh-Hans : &ZH_HANS  关于
      zh      : *ZH_HANS
      zh-CN   : *ZH_HANS
      zh-SG   : *ZH_HANS
      zh-Hant : &ZH_HANT  關於
      zh-TW   : *ZH_HANT
      zh-HK   : *ZH_HANT
      ko      : &KO       소개
      ko-KR   : *KO
      fr      : &FR       À propos
      fr-BE   : *FR
      fr-CA   : *FR
      fr-CH   : *FR
      fr-FR   : *FR
      fr-LU   : *FR
  # @end locale config
#key: page-about
---

{%- include aboutme.html -%}

## Work Experience
- __Performance Analyst__, _NetApp_ <br/> October 2017 - Present
- __Teaching Assistant__, _CSci 402 - Operating Systems, Department of Computer Science, University of Southern California_ <br/> Fall 2012 - Summer 2017 
- __Intern__, _Teradata Labs_ <br/> June 2014 - August 2014
- __Intern__, _Fuji Xerox Palo Alto (FXPAL) Laboratory_ <br/> May 2013 - August 2013
- __Research Assistant (Adviser: Prof. Cheng-Fu Chou)__, _Communications and Multimedia Laboratory (CMLab), Department of Computer Science and Information Engineering, National Taiwan University_ <br/> October 2009 - July 2010
- __Research Assistant (Adviser: Prof. Zhao-Ming Gao)__, _Department of Foreign Languages and Literatures, National Taiwan University_ <br/> September 2006 - September 2007

## Project Experience

### Large-Scale Machine Learning

#### ONTAP AI <span class="default-span place-netapp">NetApp</span>

Built on a verified architecture that combines NVIDIA DGX-1 supercomputers, NetApp AFF storage, and Cisco networking supercharges your AI/DL environments.
- Scalable AI Infrastructure: Designing for Real-World Deep Learning Use Cases [[Technical Report]](https://www.netapp.com/us/media/nva-1121-design.pdf)

#### Large-scale Deep Learning in Shared Clusters <span class="default-span place-usc">USC - Research</span> <span class="default-span place-netapp">NetApp</span>

<span class="cite">Paper is published in IEEE MASCOTS 2018, with title __A Model-based Approach to Streamlining Distributed Training for Asynchronous SGD__</span>

We address two important problems for the application of this strategy to large-scale clusters and multiple, heterogeneous jobs. 
1. We propose and validate a queueing model to estimate the throughput of a training job as a function of the number of nodes assigned to the job; this model targets asynchronous Stochastic Gradient Descent (SGD), and requires only data from quick, two-node profiling. 
2. Throughput estimations are then used to explore several classes of scheduling heuristics to reduce response time in a scenario where heterogeneous jobs are continuously submitted to a large-scale cluster. These scheduling algorithms dynamically select which jobs to run and how many nodes to assign to each job, based on different trade-offs between service time reduction and efficiency (e.g., speedup per additional node). Heuristics are evaluated through extensive simulations of realistic DNN workloads, also investigating the effects of early termination, a common scenario for DNN training jobs.

### Cloud Computing

#### Resource Sharing for the Small Cloud <span class="default-span place-usc">USC - Research</span>

<span class="cite">Paper is published in IEEE ICDCS 2017, with title __Performance Driven Resource Sharing Markets for the Small Cloud__</span>

Approximated an exponential growth stochastic model via TransientAnalysis to estimate the number of virtual machines exchanged within the cloud federation; developed market-basedgame-theoretic model that converges to efficient virtual machine sharing decisions at market equilibrium

### Distributed System

#### Improve the performance of SQL-MR Execution Engine <span class="default-span place-teradata">Teradata - Intern</span>

I profiled the performance of SQL-MapReduce Execution Engine and re-designed the mechanism to reduce the data transmission and I/O time between user defined functions and databases. 
1. Aggregating the output: Instead of sending result row by row in the original design, I caches rows and send it once to reduce the I/O time. This improves the performance by at least 20%. 
2. Eager sending: Sending cached data immediately if it is available. This improves the performance by 10%. 

#### MediaWall Framework <span class="default-span place-fxpal"> FXPAL - Intern</span>
I designed and developed media wall framework which instantiates and controls virtual machines to enable diversified screen presentations that are not limited by pre-installed projectors. Since this system works in a network, I built a centralized system to manage network resources and handle interactions between remote machines and services to enhance the performance. Moreover, I developed APIs to provide programmatic access from web-enabled platforms. To provide access interface, I programmed Web-based Graphical User Interfaces to enable presenters to manage projected screens on walls

<!---
#### Speed up loading large data sets to a Facebook-like system on Cassandra <span class="default-span place-usc">USC - Research</span>
Built Cassandra clusters with small-scale OpenStack virtual machines suitable for Facebook-like social network. Designed mechanisms equally distributing the workload to all running virtual machines. Coded multi-thread systems to handle different kinds of inputs without leaving the system idle.
--->

<!---
#### Performance Analysis for the Speed-Sensitive Channel Assignment
Developed and simulated probability models to correctly analyse the performance of channel assignment with rapid cell phone hand-offs. Explored the effect of adopting random walk or human walk to probability models for assigning channels.
--->
### Networking / Peer-to-Peer (P2P)

#### Hybrid P2P Video Streaming <span class="default-span place-usc">USC - Research</span>

<span class="cite">Paper is published in IEEE/ACM IWQoS 2015, with title __Sustaining Ad-Driven P2P Streaming Ecosystems A Market-Based Approach__, following up a journal in IEEE Transactions on Multimedia with a title __On Market-Driven Hybrid-P2P Video Streaming__</span>

Re-designed sharing mechanisms to eliminate the problem of video playback pausesby up to 80% while providing sufficiently high quality of videos to peers; developed market-based game-theoretic modelthat uses advertisements as an incentive to satisfy all the market stakeholders.

#### Implemented a distributed large-scale Digital Signage system <span class="default-span place-ntu">NTU</span>
Implemented a distributed large-scale Digital Signage system. Developed partial storage systems for video contents and advertisements by combining Content Distribution Network and Peer-to-Peer technologies

#### Implemented a real P2P IPTV system <span class="default-span place-ntu">NTU</span>
Coded P2P Internet Protocol Television(IPTV) systems supporting channel browsing in Windows systems. Explored and measured effect of parameter settings for different network capability environments.

<!---
#### Exploit File Similarity in Peer-to-Peer Networks <span class="default-span place-ntu">NTU</span>
Explored probability of having the same chunks among files in eMule file-sharing environments. Developed sharing mechanism capable of using similar chunks to speed up peer-to-peer file downloading.
--->