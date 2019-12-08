# fuzzing
A collection of resources about fuzzing test.

***

## Book

- https://www.fuzzingbook.org/
- https://github.com/uds-se/fuzzingbook
- Fuzzing Brute Force Vulnerability Discovery
- 模糊测试-强制发掘安全漏洞的利器

## Paper
***
### Survey
- 2018(C&S)A systematic review of fuzzing techniques
- 2019(TSE)The Art, Science, and Engineering of Fuzzing: A Survey

### ASE
- 2018(ASE)ContractFuzzer Fuzzing Smart Contracts for Vulnerability Detection
- 2018(ASE)FairFuzz A Targeted Mutation Strategy for Increasing Greybox Fuzz Testing Coverage
- 2019(ASE)Learning-Guided Network Fuzzing for Testing Cyber-Physical System Defences

### CCS
- 2016(CCS)Coverage-based Greybox Fuzzing as Markov Chain
- 2017(CCS)Directed Greybox Fuzzing
- 2017(CCS)Designing New Operating Primitives to Improve Fuzzing Performance
- 2017(CCS)DIFUZE: Interface aware fuzzing for kernel drivers
- 2018(CCS)Evaluating Fuzz Testing
- 2018(CCS)Hawkeye Towards a Desired Directed Grey-box Fuzzer
- 2019(CCS)Matryoshka Fuzzing Deeply Nested Branches
- 2019(CCS)Different is Good_ Detecting the Use of Uninitialized Variables through Differential Replay
- 2019(CCS)Intriguer_ Field-Level Constraint Solving for Hybrid Fuzzing
- 2019(CCS)Learning to Fuzz from Symbolic Execution with Application to Smart Contracts

### FSE
- 2018(FSE)Singularity Pattern Fuzzing for Worst Case Complexity
- 2019(FSE)FUDGE_ Fuzz Driver Generation at Scale
- 2019(FSE)Cerebro_ Context-Aware Adaptive Fuzzing for Effective Vulnerability Detection
- 2019(FSE)Just Fuzz It_ Solving Floating-Point Constraints using Coverage-Guided Fuzzing

### NDSS
- 2016(NDSS)Driller Augmenting Fuzzing Through Selective Symbolic Execution 
- 2017(NDSS)VUzzer Application-aware Evolutionary Fuzzing
- 2018(NDSS)Enhancing Memory Error Detection for Large-Scale Applications and Fuzz Testing
- 2018(NDSS)IOTFUZZER  Discovering Memory Corruptions in IoT Through App-based Fuzzing
- 2018(NDSS)What You Corrupt Is Not What You Crash Challenges in Fuzzing Embedded Devices
- 2019(NDSS)CodeAlchemist Semantics-Aware Code Generation to Find Vulnerabilities in JavaScript Engines
- 2019(NDSS)Life after Speech Recognition Fuzzing Semantic Misinterpretation for Voice Assistant Applications
- 2019(NDSS)NAUTILUS Fishing for Deep Bugs with Grammars
- 2019(NDSS)PeriScope An Effective Probing and Fuzzing Framework for the Hardware-OS Boundary
- 2019(NDSS)REDQUEEN  Fuzzing with Input-to-State Correspondence
- 2019(NDSS)Send Hardest Problems My Way Probabilistic Path Prioritization for Hybrid Fuzzing

### ISSTA
- 2018(ISSTA)PerfFuzz_ Automatically Generating Pathological Inputs
- 2019(ISSTA)DeepHunter_ A Coverage-Guided Fuzz Testing 
- Frameworkfor Deep Neural Networks
- 2019(ISSTA)Deferred Concretization in Symbolic Execution via Fuzzing
- 2019(ISSTA)Semantic Fuzzing with Zest

### ICSE
- 2019(ICSE)DIFFUZZ  Differential Fuzzing for Side-Channel Analysis
- 2019(ICSE)REST-ler: Stateful REST API Fuzzing
- 2019(ICSE)SLF Fuzzing without Valid Seed Inputs
- 2019(ICSE)Superion Grammar-Aware Greybox Fuzzing
- 2019(ICSE)DifFuzz: differential fuzzing for side-channel analysis

### OOPSLA
- 2019(OOPSLA)Compiler Fuzzing_ How Much Does It Matter
- 2019(OOPSLA)FuzzFactory_ Domain-Specific Fuzzing with Waypoints

### PLDI
- 2016(PLDI)Coverage-Directed Differential Testing of JVM Implementations
- 2019(PLDI)Parser-Directed Fuzzing

### S&P
- 2010(SP)TaintScope_ A Checksum-Aware Directed Fuzzing Tool for Automatic Software Vulnerability Detection
- 2017(SP)NEZHA  Efficient Domain-Independent Differential Testing
- 2017(SP)Skyfire Data-Driven Seed Generation for Fuzzing
- 2018(SP)Angora Efficient Fuzzing by Principled Search
- 2018(SP)CollAFL Path Sensitive Fuzzing
- 2018(SP)T-Fuzz fuzzing by program transformation
- 2019(SP)Full-speed Fuzzing Reducing Fuzzing Overhead through Coverage-guided Tracing
- 2019(SP)Fuzzing File Systems via Two-Dimensional Input Space Exploration
- 2019(SP)NEUZZ Efficient Fuzzing with Neural Program Smoothing
- 2019(SP)ProFuzzer On-the-fly Input Type Probing for Better Zero-day Vulnerability Discovery
- 2019(SP)Razzer Finding Kernel Race Bugs through Fuzzing
- 2020(SP)SAVIOR_Towards Bug-Driven Hybrid Testing

### TSE
- 2018(TSE)Coverage-based Greybox Fuzzing as Markov Chain
- 2019(TSE)Smart Greybox Fuzzing

### USENUX
- 2017(USENUX)kAFL Hardware-Assisted Feedback Fuzzing for OS Kernels
- 2018(USENUX)MoonShine Optimizing OS Fuzzer Seed Selection with Trace Distillation
- 2018(USENUX)Q SYM  A Practical Concolic Execution Engine Tailored for Hybrid Fuzzing
- 2019(USENIX)ANTIFUZZ_Impeding Fuzzing Audits of Binary Executables
- 2019(USENIX)EnFuzz_Ensemble Fuzzing with Seed Synchronization among Diverse Fuzzers
- 2019(USENIX)FIRM-AFL_High-Throughput Greybox Fuzzing of IoT Firmware via Augmented Process Emulation
- 2019(USENIX)FUZZIFICATION_Anti-Fuzzing Techniques
- 2019(USENIX)GRIMOIRE_Synthesizing Structure while Fuzzing
- 2019(USENIX)MOPT_Optimize Mutation Scheduling for Fuzzers
- 2019(USENIX)RVFUZZER_Finding Input Validation Bugs in Robotic Vehicles Through Control-Guided Testing
- 2019(USENIX)Understanding and Securing Device Vulnerabilities through Automated Bug Report Analysis

### Other
- 2016TreeFuzz_Learning to Fuzz Application-Independent Fuzz Testing with Probabilistic, - Generative Models of Input Data
- 2018Coverage-Guided Fuzzing for Deep Neural Networks
- 2018TensorFuzz Debugging Neural Networks with Coverage-Guided Fuzzing

### Tutorial & Practice
***
- [Exercises to learn how to fuzz with American Fuzzy Lop](https://github.com/mykter/afl-training)
- [Modern fuzzing of C/C++ Projects, libfuzzer-workshop](https://github.com/Dor1s/libfuzzer-workshop)
- [Google Fuzzing Forum](https://github.com/google/fuzzing)
- [Modern fuzzing of C/C++ Projects](https://github.com/google/fuzzer-test-suite)
- [Set of tests for fuzzing engines (including tutorial)](https://github.com/Dor1s/libfuzzer-workshop)
- [Fuzzing – how to find bugs automagically using AFL](http://9livesdata.com/fuzzing-how-to-find-bugs-automagically-using-afl/)
- [Java Bugs with and without Fuzzing](https://www.modzero.ch/modlog/archives/2018/09/20/java_bugs_with_and_without_fuzzing/index.html)
- [AFL 漏洞挖掘技术漫谈（一）：用 AFL 开始你的第一次 Fuzzing](https://paper.seebug.org/841/)
- [AFL 漏洞挖掘技术漫谈（二）：Fuzz 结果分析和代码覆盖率](https://paper.seebug.org/842/)
- [Fuzzing PHP for Fun and Profit](https://www.tripwire.com/state-of-security/vert/fuzzing-php-for-fun-and-profit/)
- [从零开始学Fuzzing系列：浏览器挖掘框架Morph诞生记](https://www.freebuf.com/sectool/89001.html)

### Awesome

***

- [A curated list of awesome Fuzzing(or Fuzz Testing) for software security](https://github.com/cpuu/awesome-fuzzing)
- [A curated list of fuzzing resources ( Books, courses - free and paid, videos, tools, tutorials and vulnerable applications to practice on ) for learning Fuzzing and initial phases of Exploit Development like root cause analysis.](https://github.com/secfigo/Awesome-Fuzzing)
- [Fuzzing-学习资源汇总](https://scubsrgroup.github.io/BinaryDatabase/Fuzzing-%E5%AD%A6%E4%B9%A0%E8%B5%84%E6%BA%90%E6%B1%87%E6%80%BB.html)

### Resource about compiler and program analysis
***
#### Tools
LLVM: a collection of modular and reusable compiler and toolchain technologies
https://llvm.org/

SVF: Pointer Analysis and Program Dependence Analysis for C and C++ Programs
https://github.com/SVF-tools/SVF

phasar: A LLVM-based static analysis framework
https://github.com/secure-software-engineering/phasar

soot: A Java optimization framework
https://github.com/Sable/soot

klee:  a symbolic virtual machine built on top of the LLVM compiler infrastructure
http://klee.github.io/

z3: Z3 Theorem Prover
https://github.com/Z3Prover/z3

COQ: a formal proof management system
https://github.com/coq/coq



#### Books
Compilers : principles, techniques, and tools

Engineering a Compiler

Advanced Compiler Design and Implementation

High-Performance Compilers for Parallel Computing

Optimizing Compilers for Modern Architectures

Data Flow Analysis Theory and Practice

Static Program Analysis

Principles of program analysis

Model Checking

Handbook of Satisfiability

Decision Procedures An Algorithmic Point of View

Getting Started with LLVM Core Libraries

LLVM Essentials

LLVM Cookbook


#### Courses
(Stanford) cs143 Compilers
http://web.stanford.edu/class/cs143/

(Simon Fraser University) CMPT 886: Program Analysis and Reliability
http://www.cs.sfu.ca/~wsumner/teaching/886/15/

(Harvard) CS 252r: Advanced Topics in Programming Languages
https://www.seas.harvard.edu/courses/cs252/2015fa/index.html

15-745 Optimizing Compilers for Modern Architecture
https://www.cs.cmu.edu/~15745/index.html

cscd70 COMPILER OPTIMIZATION
http://www.cs.toronto.edu/~pekhimenko/courses/cscd70-w18/index.html

CS 380C: Advanced Compiler Techniques
http://www.cs.utexas.edu/users/mckinley/380C/

CS6843: Program Analysis
http://www.cse.iitm.ac.in/~rupesh/teaching/pa/jan14/description.php
