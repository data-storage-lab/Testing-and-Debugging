# Testing and Debugging

- Model Checking
    - [EXPLODE: a Lightweight, General System for Finding Serious StorageSystem Errors](https://web.stanford.edu/~engler/explode-osdi06.pdf) (OSDI'06)
    - [Jaaru: Efficiently Model Checking Persistent Memory Programs](https://web.cs.ucla.edu/~harryxu/papers/jaaru-asplos21.pdf) (ASPLOS'21)
- Fault Injection
    - [Service-Level Fault Injection Testing](https://dl.acm.org/doi/10.1145/3472883.3487005) (SoCC'21)
    - [Fuzzing Error Handling Code using Context-Sensitive Software Fault Injection](https://git.ece.iastate.edu/data-storage-lab/papers/fault-injection/-/blob/master/paper/sec20-jiang.pdf) (Security'20)
    - [PMTest: A Fast and Flexible Testing Framework for Persistent Memory Programs](https://git.ece.iastate.edu/data-storage-lab/papers/fault-injection/-/blob/master/paper/pmtest-asplos2019.pdf) (ASPOS'19)
    - [PFault: A General Framework for Analyzing the Reliability of High-Performance Parallel File Systems](https://git.ece.iastate.edu/data-storage-lab/papers/fault-injection/-/blob/master/paper/2018_ICS_PFault.pdf) (ICS'18)
    - [Redundancy Does Not Imply Fault Tolerance: Analysis of Distributed Storage Reactions to Single Errors and Corruptions](https://git.ece.iastate.edu/data-storage-lab/papers/fault-injection/-/blob/master/paper/fast17-ganesan.pdf) (FAST'17)
    - [Torturing Databases for Fun and Profit](https://git.ece.iastate.edu/data-storage-lab/papers/fault-injection/-/blob/master/paper/osdi14-paper-zheng_mai.pdf) (OSDI'14)
    - [Automated Vulnerability Discovery in Distributed Systems](https://dslab.epfl.ch/pubs/AVD.pdf) (HotDep '11)
    - [IRON File Systems](https://git.ece.iastate.edu/data-storage-lab/papers/fault-injection/-/blob/master/paper/05-iron-sosp05.pdf) (SOSP'05)
- Debugging 
    - [Witcher: Systematic Crash Consistency Testing for Non-Volatile Memory Key-Value Stores](https://www3.cs.stonybrook.edu/~dongyoon/papers/SOSP-21-Witcher.pdf)(SOSP’21)
    - [Argus: Debugging Performance Issues in Modern Desktop Applications with Annotated Causal Tracing](https://www.usenix.org/system/files/atc21-weng.pdf) (ATC'21)
    - [Lossless Instruction-to-Object Memory Tracing in the Linux Kernel](https://dl.acm.org/doi/pdf/10.1145/3456727.3463767) (SYSTOR'21)
    - [Reverse Debugging of Kernel Failures in Deployed Systems](https://www.usenix.org/system/files/atc20-ge.pdf) (ATC'20)
    - [You can’t debug what you can’t see: Expanding observability with the OmniTable](https://dl.acm.org/doi/pdf/10.1145/3317550.3321428) (HotOS'19)
    - [REPT: Reverse Debugging of Failures in Deployed Software](https://www.usenix.org/system/files/osdi18-cui.pdf) (OSDI'18)
    - [LAVA: Large-scale Automated Vulnerability Addition](http://css.csail.mit.edu/6.858/2018/readings/lava.pdf) (S&P'16)
    - [Failure Sketching: A Technique for Automated Root Cause Diagnosis of In-Production Failures ](https://git.ece.iastate.edu/data-storage-lab/papers/static-and-dynamic-program-analysis/-/blob/master/paper/15_failure_sketching.pdf) (SOSP'15)
    - [Using likely invariants for automated software fault localization](https://dl.acm.org/doi/pdf/10.1145/2499368.2451131)(ASPLOS‘13)
    - [Hardware Breakpoint (or watchpoint) usage in Linux Kernel](https://www.kernel.org/doc/ols/2009/ols2009-pages-149-158.pdf) (Proceedings of the
Linux Symposium 2009)
    - [Guest Operatiing System Debugging](https://git.ece.iastate.edu/data-storage-lab/dsl-techhub/fault-injection/-/blob/master/paper/01x10-David_Hildebrand-Guest-operating_system_debugging.pdf)
- Empirical Study
    - [What bugs cause production cloud incidents?](https://git.ece.iastate.edu/data-storage-lab/papers/fault-injection/-/blob/master/paper/19_survey.pdf) (HotOS'19)
    - [Coccinelle: 10 Years of Automated Evolution in the Linux Kernel](https://www.usenix.org/system/files/conference/atc18/atc18-lawall.pdf) (ATC'18)
    - [Why Does the Cloud Stop Computing? Lessons from Hundreds of Service Outages](https://www.ece.iastate.edu/~mai/docs/papers/2016_SoCC_COS.pdf) (SoCC'16)
    - [Systems Approaches to Tackling Configuration Errors: A Survey](https://tianyin.github.io/pub/csur.pdf) (CSUR'15)
    - [Understanding Issue Correlations: A Case Study of the Hadoop System](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.727.7837&rep=rep1&type=pdf) (SoCC'15) 
    - [Simple Testing Can Prevent Most Critical Failures: An Analysis of Production Failures in Distributed Data-Intensive Systems](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-yuan.pdf) (OSDI'14)
    - [Why does cryptographic software fail? A case study and open problems](https://pdos.csail.mit.edu/papers/cryptobugs:apsys14.pdf) (APSys'14)
    - [A Study of Linux File Systems Evolution](https://www.usenix.org/system/files/conference/fast13/fast13-final75_0.pdf) (FAST'13)
    - [Do Not Blame Users for Misconfigurations](https://cseweb.ucsd.edu/~tixu/papers/sosp13.pdf) (SOSP'13)
    - [Linux kernel vulnerabilities: State-of-the-art defenses and open problems](https://pdos.csail.mit.edu/papers/chen-kbugs.pdf) (APSys'11)
    - [An Empirical Study on Configuration Errors in Commercial and Open Source Systems](http://opera.ucsd.edu/paper/sosp11-yin.pdf) (SOSP'11)
    - [A Study of the Internal and External Effects of Concurrency Bugs](https://www.cs.purdue.edu/homes/pfonseca/papers/dsn2010-concurrencybugs.pdf) (DSN'10)
    - [Learning from Mistakes — A Comprehensive Study on Real World Concurrency Bug Characteristics](http://web1.cs.columbia.edu/~junfeng/10fa-e6998/papers/concurrency-bugs.pdf) (ASPLOS'08)
    - [Taxonomy of Linux Kernel Vulnerability Solutions](https://spectrum.library.concordia.ca/7809/1/report.pdf) (Tech Report)
    - [Vulnerability Type Distributions in CVE](https://cve.mitre.org/docs/vuln-trends/vuln-trends.pdf) (Tech Report)
    - [An Empirical Study of Operating Systems Errors](https://people.engr.ncsu.edu/gjin2/Classes/591/Spring2017/case-os-errors.pdf) (SOSP'01)
    - [Checking System Rules Using System-Specific, Programmer-Written Compiler Extensions](https://www.usenix.org/legacy/events/osdi2000/engler/engler.pdf) (OSDI'00)
- Configuration Bug Detection
    - [Understanding and Discovering Software Configuration Dependencies in Cloud and Datacenter Systems](https://www.cs.cornell.edu/~legunsen/pubs/ChenETAL20CDep.pdf) (ESEC/FSE'20)
    - [Testing Configuration Changes in Context to Prevent Production Failures](https://www.usenix.org/system/files/osdi20-sun.pdf) (OSDI'20)
    - [PracExtractor: Extracting Configuration Good Practices from Manuals to Detect  Server Misconfigurations](https://www.usenix.org/system/files/atc20-xiang_0.pdf) (ATC'20)
    - [Understanding and Auto-Adjusting Performance-Sensitive Configurations](https://people.cs.uchicago.edu/~hankhoffmann/autoconf.pdf) (ASPLOS'18)
    - [Early Detection of Configuration Errors to Reduce Failure Damage](https://www.usenix.org/system/files/conference/osdi16/osdi16-xu.pdf) (OSDI'16)
    - [On Essential Configuration Complexity: Measuring Interactions in Highly-Configurable Systems](https://dl.acm.org/doi/pdf/10.1145/2970276.2970322 ) (ASE'16) 
    - [EnCore: Exploiting System Environment And Correlation Information for Misconfiguration Detection](https://dl.acm.org/doi/pdf/10.1145/2541940.2541983) (ASPLOS'14)
    - [Which Configuration Option Should I Change?](https://homes.cs.washington.edu/~mernst/pubs/confsuggester-icse2014.pdf) (ICSE'14)
    - [Mining Configuration Constraints: Static Analyses and Empirical Results](https://www.cs.cmu.edu/~ckaestne/pdf/icse14_mining.pdf) (ICSE'14)
    - [Configurations Everywhere: Implications for Testing and Debugging in Practice](https://cse.unl.edu/~myra/papers/icse14_config.pdf) (ICSE'14)
    - [Do Not Blame Users for Misconfigurations](http://cseweb.ucsd.edu/~tixu/papers/sosp13.pdf) (SOSP'13)
    - [CONFU: Configuration Fuzzing Testing Framework for Software Vulnerability Detection](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2964869/) (IJSSE'10)
    - [ConfErr: A Tool for Assessing Resilience to Human Configuration Errors](https://dslab.epfl.ch/pubs/conferr.pdf) (DSN'08)
    - [Hippodrome: Running Circles Around Storage Administration](https://www.usenix.org/legacy/publications/library/proceedings/fast02/full_papers/andersonHIP/andersonHIP.pdf) (FAST'02)
## Related git repos
- A list of resources on testing distributed systems curated by Andrey Satarin. https://github.com/asatarin/testing-distributed-systems#research-papers

