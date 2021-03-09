# Concurrency Paper

- **Survey/Review**
    - [Understanding Real-World Concurrency Bugs in Go (ASPLOS 2019)](https://songlh.github.io/paper/go-study.pdf)
    - [A systematic survey on automated concurrency bug detection, exposing, avoidance, and fixing techniques (SQJ 2018)](https://dl.acm.org/doi/10.1007/s11219-017-9385-3)
    - [Surveying concurrency bug detectors based on types of detected bugs (2017)](http://scis.scichina.com/en/2017/031101.pdf)
    - [A survey of race bug detection techniques for multithreaded programmes (2014)](https://onlinelibrary.wiley.com/doi/abs/10.1002/stvr.1564)
    - [Learning from Mistates: A Comprehensive Study on Real World Concurrency Bug Characteristics (ASPLOS 2008)](https://www.cs.columbia.edu/~junfeng/09fa-e6998/papers/concurrency-bugs.pdf)
    - [Understanding, Detecting and Exposing Concurrency Bugs (2003)](https://core.ac.uk/download/pdf/4820747.pdf)
    - [Notes on concurrency bugs](https://danluu.com/concurrency-bugs/)
    - [Slides: CS636: Testing Concurrent Programs - CSE-IITK - IIT Kanpur](https://www.cse.iitk.ac.in/users/swarnendu/courses/spring2019-cs636/Testing%20Concurrent%20Programs.pdf)
    
- **Maximal Causality Reduction**
    - [Speeding Up Maximal Causality Reduction with Static Dependency Analysis (ECOOP 2017)](https://huangshiyou.github.io/files/Huang-ECOOP-2017-16.pdf)
    - [Maximal Causality Reduction for TSO and PSO (OOPSLA 2016)](https://huangshiyou.github.io/files/mcr_relax-huang.pdf)
    - [Stateless Model Checking Concurrent Programs with Maximal Causality Reduction (PLDI 2015)](https://dl.acm.org/doi/pdf/10.1145/2813885.2737975)
    - [Maximal Sound Predictive Race Detection with Control Flow Abstraction (PLDI 2014)](http://fsl.cs.illinois.edu/FSL/papers/2014/huang-meredith-rosu-2014-pldi/huang-meredith-rosu-2014-pldi-public.pdf)

- **Verification**
    - [Compositional Non-Interference for Fine-Grained Concurrent Programs (S&P 2021)](https://arxiv.org/abs/1910.00905)
    - [Armada: Low-Effort Verification of High-Performance Concurrent Programs (PLDI 2020)](https://www.microsoft.com/en-us/research/uploads/prod/2020/06/armada.pdf)
    - [Finding rare concurrent programming bugs: An automatic, symbolic, randomized, and parallelizable approach (ICTAC2018)](https://eprints.soton.ac.uk/425836/)
    - [A Runtime Verification Tool for Detecting Concurrency Bugs in FreeRTOS Embedded Software (ISPDC 2018))](https://ieeexplore.ieee.org/document/8452035)
    - [Effective Stateless Model Checking for C/C++ Concurrency](https://plv.mpi-sws.org/rcmc/paper.pdf)
    - [Parallel Bug-finding in Concurrent Programs via Reduced Interleaving Instances (ASE 2017)](https://eprints.soton.ac.uk/413917/1/swarm_ASE2017.pdf)
    - [Inductive Data FLow Graph (POPL 2013)](https://www.cs.princeton.edu/~zkincaid/pub/popl13.pdf)
    - [Inspect: A Runtime Model Checker For Mulithreaded C Programs (2008)](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.142.6260)

- **Static Analysis/Detector**
    - [SmartTrack: Efficient Predictive Race Detection (PLDI 2020)](https://arxiv.org/pdf/1905.00494.pdf)
    - [Low-overhead deadlock prediction (ICSE 2021)](https://dl.acm.org/doi/10.1145/3377811.3380367)
    - [A True Positives Theorem for a Static Race Detector Extended Version (POPL 2019)](https://arxiv.org/pdf/1811.03503.pdf)
    - [ConPredictor: Concurrency Defect Prediction in Real-World Applications (TSE 2018)](https://ieeexplore.ieee.org/document/8252721)
    - [RacerD: Compositional Static Race Detection (OOPSLA 2018)](https://ilyasergey.net/papers/racerd-oopsla18-preprint.pdf)
    - [OWL: Understanding and Detecting Concurrency Attacks (DSN 2018)](http://www.cs.columbia.edu/~junfeng/papers/owl-dsn18.pdf)
    - [LOCKSMITH: context-sensitive correlation analysis for race detection (ACM SIGPLAN Notices)](https://dl.acm.org/doi/10.1145/1133255.1134019)

- **Dynamic Detector/Sanitizer**
    - [Dynamic Analysis Method for Concurrency Bugs in Multi-process/Multi-thread Environments (IJPP 2020)](https://www.x-mol.com/paperRedirect/1265038487945584640)
    - [Detecting Concurrency Memory Corruption Vulnerabilities (FSE 2019)](https://dl.acm.org/doi/pdf/10.1145/3338906.3338927?download=true)
    - [UFO: Predictive Concurrency Use-After-Free Detection (ICSE 2018)](https://ieeexplore.ieee.org/document/8453130)
    - [Finding Complex Concurrency Bugs in Large Multi-Threaded Applications (EuroSys 2011)](https://www.gsd.inesc-id.pt/~rodrigo/pike_eurosys11.pdf)
    - [ThreadSanitizer – data race detection in practice (2009)](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/35604.pdf)

- **Fuzzing**
    - [Muzz: Thread-aware Grey-box Fuzzing for Effective Bug Hunting in Multithreaded Programs (Usenix Sec 2020)](https://www.usenix.org/system/files/sec20-chen-hongxu.pdf)
    - [Krace: Data Race Fuzzing for Kernel File Systems (S&P 2020)](https://www.cc.gatech.edu/~mxu80/pubs/xu:krace.pdf)
    - [ConFuzz—A Concurrency Fuzzer (2019)](https://wcventure.github.io/FuzzingPaper/Paper/AISC19_ConFuzz.pdf)
    - [Razzer: Finding Kernel Race Bugs through Fuzzing (S&P 2019)](https://lifeasageek.github.io/papers/jeong-razzer.pdf)
    - [A Heuristic Framework to Detect Concurrency Vulnerabilities (ACSAC 2018)](https://dl.acm.org/doi/pdf/10.1145/3274694.3274718?download=true)
  
- **Dynamic Testing** 
    - [Learning-Based Controlled Concurrency Testing (OOPSLA 2020)](https://dl.acm.org/doi/pdf/10.1145/3428298)
    - [Symbolic Partial-Order Execution for Testing Multi-Threaded Programs (2020)](https://arxiv.org/abs/2005.06688)
	- [Efficient Scalable Thread-Safety-Violation Detection (SOSP 2019)](https://www.microsoft.com/en-us/research/uploads/prod/2019/09/sosp19-final193.pdf)
	- [*Adaptive Randomized Scheduling for Concurrency Bug Detection (ICECCS 2019) (JAVA)](https://ieeexplore.ieee.org/abstract/document/8882777)
	- [Partial Order Aware Concurrency Sampling (CAV 2018)](https://link.springer.com/chapter/10.1007%2F978-3-319-96142-2_20)
	- [Efficient Detection of Thread Safety Violations via Coverage-Guided Generation of Concurrent Tests (ICSE 2017) (JAVA)](https://ieeexplore.ieee.org/document/7985668)
	- [SKI: Exposing Kernel Concurrency Bugs through Systematic Schedule Exploration (OSDI 2014)](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-fonseca.pdf)
	- [Concurrency Testing Using Schedule Bounding: an Empirical Study (SCTBench) (PPoPP 2014)](https://www.doc.ic.ac.uk/~afd/homepages/papers/pdfs/2014/PPoPP.pdf) 
	- [Efficient Concurrency-Bug Detection Across Inputs (OOPSLA 2013)](https://dl.acm.org/doi/10.1145/2544173.2509539)
	- [*Multicore Acceleration of Priority-Based Schedulers for Concurrency Bug Detection (PLDI 2012)](https://dl.acm.org/doi/pdf/10.1145/2254064.2254128) -[[Slides]](https://www.cs.rutgers.edu/~santosh.nagarakatte/papers/PLDI2012-needlepoint-web.pdf)
	- [A Randomized Scheduler with Probabilistic Guarantees of Finding Bugs (ASPLOS 2010)](https://dl.acm.org/doi/pdf/10.1145/1736020.1736040)
	- [ConMem: Detecting Severe Concurrency Bugs through an Effect-Oriented Approach](http://pages.cs.wisc.edu/~shanlu/paper/asplos184-zhang.pdf)
	- [Effective Testing for Concurrency Bugs (Thesis)](https://www.mpi-sws.org/tr/2015-004.pdf)
	- [Concurrency: Testing isn’t good enough](http://www.contemplateltd.com/threadsafe/concurrency-testing-isnt-good-enough)
	- [Maple: a coverage-driven testing tool for multithreaded programs (OOPSLA 2012)](https://dl.acm.org/doi/10.1145/2384616.2384651)
 
- **Reproducing/Dubugging**
    - [D4: Fast Concurrency Debugging with Parallel Differential Analysis (PLDI 2018)](https://parasol.tamu.edu/people/jeff/academic/d4.pdf)
    - [CONCURRIT: A Domain Specific Language for Reproducing Concurrency Bugs (PLDI 2013)](https://people.eecs.berkeley.edu/~ksen/papers/concurrit.pdf) -[[Source]](https://code.google.com/archive/p/concurrit/)

- **Benchmark**
    - [Concurrency testing using controlled schedulers: An empirical study (TOPC 2016)](https://dl.acm.org/doi/pdf/10.1145/2858651?casa_token=k7L1hBjlQeUAAAAA:6ZqKKosLEax0SKgNvKUiDLWRPO3e2ExV4FakJs9s5ohhIMXxtgyOMce17A-KUh3cHrcRe2UXl_Is) -[[Source]](https://github.com/mc-imperial/sctbench)
    - [RADBench: A Concurrency Bug Benchmark Suite (USENIX HotPar 2011)](https://www.usenix.org/legacy/event/hotpar11/tech/final_files/Jalbert.pdf)
    - [Bugbench: Benchmarks for Evaluating Bug Detection Tools](https://github.com/lihebi/bugbench) -[[Source]](https://github.com/lihebi/bugbench)
    - [A Case for an Interleaving Constrained Shared-Memory Multi-Processor](http://web.eecs.umich.edu/~nsatish/papers/ISCA-09-CPC.pdf) -[[Source]](https://github.com/jieyu/concurrency-bugs)
    - [The PARSEC benchmark suite: characterization and architectural implications (2008)](https://dl.acm.org/doi/pdf/10.1145/1454115.1454128) -[[Source]](https://parsec.cs.princeton.edu/index.htm)
    - [Experience with a Concurrency Bugs Benchmark (2008) (JAVA)](https://personal.cis.strath.ac.uk/marc.roper/TESTBENCH08/Papers/tzoref.pdf)