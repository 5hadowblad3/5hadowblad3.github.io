---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  # - /index.html
  # - index.html
---

Welcome to Heqing Huang's homepage!

I am an assistant professor at the Department of Computer Science, [City University of Hong Kong](https://www.cityu.edu.hk/)! Previously, I was a postdoc research fellow in the [AST Lab](https://ast.ethz.ch) at ETH Zurich, advised by [Prof. Zhendong Su](https://people.inf.ethz.ch/suz/). I am also fortunate to obtain my Ph.D. supervised by [Prof. Charles Zhang](https://cse.hkust.edu.hk/~charlesz/) at the Hong Kong University of Science and Technology. 

My research focuses on software security, especially leveraging program analysis techniques to ensure software security rigorously.
Specifically, my primary goal is to address the deficiencies in existing security analysis for diverse software systems by understanding program semantics. Hence, there are two main divisions of my research currently:

1. Enhancing the fundamental program analysis algorithm.  
2. Exploring the code representation/security specification in diverse scenarios.  

### **NEWS!**
 * Our paper on detecting false negative vulnerabilities on autonomous driving simulators has been accepted in [TDSC](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=8858)!
 * Our paper on studying the challenges of applying LLM for software vulnerability detection has been accepted in [CSUR](https://dl.acm.org/journal/csur)！
 * Our extension paper of GiantSan (ASPLOS'24 Best Paper) is accepted in [TOCS](https://dl.acm.org/journal/tocs) for less instrumentation overhead!  
 * Our paper on optimizing fuzzing with fine-grained scheduling feedback is accepted in [TOSEM](https://dl.acm.org/journal/tosem)!  
 * Our paper on parallel fuzzing is accepted in [ISSTA 25](https://conf.researchr.org/home/issta-2025)! 
 * Our paper on decoupling sanitizers from fuzzing is accepted in [ICSE 25](https://conf.researchr.org/home/icse-2025)! 
 * Our study for Android APP token privacy leakage issues has been accepted in [EMSE 25](https://link.springer.com/journal/10664)!
 * Our extension paper on Android testing is accepted in [ICSE 25](https://conf.researchr.org/home/icse-2025)!
 * Entering the finale of [DARPA AIxCC](https://aicyberchallenge.com)! All you need is a fuzzing brain!
 * Our work on fuzzing Android applications is accepted at [TSE](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=32)!
 * One [ASPLOS 2025](https://www.asplos-conference.org/asplos2025/) submission is accepted!
 * Received [ASPLOS 2024](https://www.asplos-conference.org/asplos2024/) Best Paper Award for GiantSan! Congratulations, Hao!
 * Two [ASPLOS 2024](https://www.asplos-conference.org/asplos2024/) submissions get accepted!
 * Another directed fuzzing work has been accepted by [S&P 2024](https://www.ieee-security.org/TC/SP2024/index.html) (again)!
 * Our multi-target directed fuzzing work has been accepted by [S&P 2024](https://www.ieee-security.org/TC/SP2024/index.html)!  
 * Received Google Research Paper award for our directed fuzzer published in [S&P 2022](https://5hadowblad3.github.io/files/Oakland22-Beacon.pdf)!   
 * Received Huawei distinguished collaborator award on deploying Pangolin ([S&P 2020](https://5hadowblad3.github.io/files/SP2020.pdf))!  


**I am looking for multiple Ph.D. and MPhil students as well as RAs. If you pursue making the program more secure and reliable, please feel free to send me an email.**

## Award
  * Finalist of [DARPA AIxCC](https://aicyberchallenge.com), 2024
  * ACM SIGARCH Best Paper Award (ASPLOS), 2024
  * Google Research Paper Award, 2022
  * Huawei Distinguish Collaborator, 2021


## Students
  I am fortunate to work with the following students: 
  * Zirui Lin (PhD, 2025)    
  * Haoyu Zhang (PhD, 2025, co-supervised with SLAI)   
  * Weiwei Fu (PhD, 2024, co-supervision)
  * Shuo Yang (PhD, 2024)   
  * Xiang Li (RA, 2024)  


## Publication
(* corresponding author)

### TDSC'25
[**ICSFuzz: Collision Detector Bug Discovery in Autonomous Driving Simulators**]()(To appear)   
Weiwei Fu, **Heqing Huang<sup>\*</sup>**, Yifan Zhang, Ke Zhang, Jin Huang, Weibin Lee, Jianping Wang.  
*IEEE Transactions on Dependable and Secure Computing*.
[[Artifacts]]()



### CSUR‘25
[**LLMs in Software Security: A Survey of Vulnerability Detection Techniques and Insights**](https://arxiv.org/abs/2502.07049)    
Ze Sheng, Zhicheng Chen, Shuning Gu, **Heqing Huang**, Guofei Gu, Jeff Huang.      
*ACM Computing Surveys*    


### TOCS'25
[**GIANTSAN: Efficient Operation-Level Memory Sanitization with Segment Folding**](https://dl.acm.org/doi/10.1145/3742426) [[Artifacts]](https://github.com/5hadowblad3/GiantSan-Artifact)    
Hao Ling, **Heqing Huang<sup>\*</sup>**, Chengpeng Wang, Yuandao Cai, Charles Zhang.   
*ACM Transactions on Computer Systems*  


### TOSEM'25
[**Efficient Fuzzing Infrastructure for Pointer-to-Object Association**](https://www.google.com/search?client=safari&rls=en&q=Efficient+Fuzzing+Infrastructure+for+Pointer-to-Object+Association&ie=UTF-8&oe=UTF-8)     
Hao Ling, **Heqing Huang<sup>\*</sup>**, Yuandao Cai, Charles Zhang.    
*ACM Transactions on Software Engineering and Methodology*    


### ISSTA'25 
[**KRAKEN: Program-Adaptive Parallel Fuzzing**](https://dl.acm.org/doi/10.1145/3728882)   
Anshunkang Zhou, **Heqing Huang<sup>\*</sup>**, Charles Zhang.    
*The 34th ACM SIGSOFT International Symposium on Software Testing and Analysis*.   


### ICSE'25
[**SAND: Decoupling Sanitization from Fuzzing for Low Overhead**](https://conf.researchr.org/details/icse-2025/icse-2025-research-track/227/SAND-Decoupling-Sanitization-from-Fuzzing-for-Low-Overhead)   
Ziqiao Kong#, Shaohua Li#, **Heqing Huang**, Zhendong Su (#Equal Contribution)    
*IEEE/ACM International Conference on Software Engineering*      


### ICSE'25
[**Mole: Efficient Crash Reproduction in Android Applications With Enforcing Necessary UI Events**](https://conf.researchr.org/details/icse-2025/icse-2025-journal-first-papers/29/Mole-Efficient-Crash-Reproduction-in-Android-Applications-With-Enforcing-Necessary-U)  
Maryam Masoudian, **Heqing Huang**, Morteza Amini, Charles Zhang.  
*IEEE/ACM International Conference on Software Engineering, Journal-First*  

### EMSE'25  
[**How Far are App Secrets from Being Stolen? A Case Study on Android**](https://dl.acm.org/doi/10.1007/s10664-024-10607-9)         
Lili Wei<sup>\*</sup>, **Heqing Huang<sup>\*</sup>**, Shing-Chi Cheung, Kevin Li.    
*Empirical Software Engineering*   

### ASPLOS'24
[**Manta: Hybrid-Sensitive Type Inference Toward Type-Assisted Bug Detection for Stripped Binaries**](https://dl.acm.org/doi/10.1145/3622781.3674177)   
Chengfeng Ye, Yuandao Cai, Anshunkang Zhou, **Heqing Huang**, Hao Ling, Charles Zhang.  
*ACM Conference on Architectural Support for Programming Languages and Operating Systems*  

### TSE'24
[**Mole: Efficient Crash Reproduction in Android Applications with Enforcing Necessary UI Events**](https://ieeexplore.ieee.org/document/10599338)    
 Maryam Masoudian, **Heqing Huang**, Morteza Amini, Charles Zhang.  
*IEEE Transactions on Software Engineering* 

### ASPLOS'24b
[**GIANTSAN: Efficient Memory Sanitization with Segment Folding**](https://5hadowblad3.github.io/files/asplos24-GiantSan.pdf) [[Artifacts]](https://github.com/5hadowblad3/GiantSan-Artifact)    
Hao Ling, **Heqing Huang<sup>\*</sup>**, Chengpeng Wang, Yuandao Cai, Charles Zhang.  
*ACM Conference on Architectural Support for Programming Languages and Operating Systems*  
🏆 <span style='color: red;'>**ACM SIGPLAN Best Paper Award**</span>

### ASPLOS'24a
[**Plankton: Reconciling Binary Code and Debug Information**](https://5hadowblad3.github.io/files/asplos24-Plankton.pdf)   
Anshunkang Zhou, Chengfeng Ye, **Heqing Huang<sup>\*</sup>**, Yuandao Cai, Charles Zhang.  
*ACM Conference on Architectural Support for Programming Languages and Operating Systems*   

### S&P'24b
[**Everything is Good for Something: Counterexample-Guided Directed Fuzzing via Likely Invariant Inference**](https://5hadowblad3.github.io/files/Oakland24-Halo.pdf)    
**Heqing Huang**, Anshunkang Zhou, Mathias Payer, Charles Zhang.    
*The 45th IEEE Symposium on Security and Privacy*.

### S&P'24a
[**Titan: Efficient Multi-target Directed Greybox Fuzzing**](https://5hadowblad3.github.io/files/Oakland24-Titan.pdf)    
**Heqing Huang**, Peisen Yao, Hung-Chun Chiu, Yiyuan Guo, Charles Zhang.    
*The 45th IEEE Symposium on Security and Privacy*.
[[Artifacts]](https://github.com/5hadowblad3/Titan)  

### TDSC'23
[**Balance Seed Scheduling via Monte Carlo Planning**](https://5hadowblad3.github.io/files/TDSC.pdf)   
**Heqing Huang**, Hung-Chun Chiu, Qingkai Shi, Peisen Yao, Charles Zhang.  
*IEEE Transactions on Dependable and Secure Computing*.
[[Artifacts]](https://github.com/5hadowblad3/Belieffuzz)

### S&P'22
[**BEACON: Directed Grey-Box Fuzzing with Provable Path Pruning**](https://5hadowblad3.github.io/files/Oakland22-Beacon.pdf)  
**Heqing Huang**, Yiyuan Guo, Qingkai Shi, Peisen Yao, Rongxin Wu, Charles Zhang.  
*The 43rd IEEE Symposium on Security and Privacy*.
[[Artifacts]](https://github.com/5hadowblad3/Beacon_artifact)  
🏆 <span style='color: red;'>**Google Research Paper Award**</span>
<!-- **[Acceptance rate: 24.5% (97/396)]** -->
<!-- [[PDF]]()  [[bib]]()  [[Artifacts]]() -->
<!-- [[PDF]](https://5hadowblad3.github.io/files/Oakland22-Beacon.pdf)    -->

### OOPSLA'21 
[**Program Analysis via Efficient Symbolic Abstraction**](https://5hadowblad3.github.io/files/oopsla-21.pdf)  
Peisen Yao, Qingkai Shi, **Heqing Huang**, Charles Zhang.  
*The 36th ACM SIGPLAN Conference on Object Oriented Programming, Systems, Languages and Applications*

### FSE'21 
[**Skeletal Approximation Enumeration for SMT Solver Testing**](https://5hadowblad3.github.io/files/FSE21.pdf)     
Peisen Yao, **Heqing Huang<sup>\*</sup>**, Wensheng Tang, Qingkai Shi, Rongxin Wu, Charles Zhang.  
*The 29th ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering*  


### ISSTA'21 
[**Fuzzing SMT Solvers via Two-Dimensional Input Space Exploration**](https://5hadowblad3.github.io/files/ISSTA20201.pdf)  
Peisen Yao, **Heqing Huang**, Wensheng Tang, Qingkai Shi, Rongxin Wu, Charles Zhang.  
*The 30th ACM SIGSOFT International Symposium on Software Testing and Analysis*.

### S&P'20
[**Pangolin: Incremental Hybrid Fuzzing via Polyhedral Path Abstraction**](https://5hadowblad3.github.io/files/SP2020.pdf)    
**Heqing Huang**, Peisen Yao, Rongxin Wu, Qingkai Shi, Charles Zhang.  
*The 41st IEEE Symposium on Security and Privacy*.
<!-- **[Acceptance rate: 24.5% (97/396)]** -->
<!-- [[PDF]]()  [[bib]]()  [[Artifacts]]() -->

### ISSTA'20 
[**Fast Bit-Vector Satisfiability**](https://5hadowblad3.github.io/files/ISSTA20-Trident.pdf)  
Peisen Yao, Qingkai Shi, **Heqing Huang**, Charles Zhang.  
*The 29th ACM SIGSOFT International Symposium on Software Testing and Analysis*.  




## Academic Service
### Chair
* Publicity co-chair, [SPLASH 2025](https://2025.splashcon.org)
* Program local co-chair, [SETTA 24](https://setta2024.cs.cityu.edu.hk/organization.php)

### Committe and Reviewer 
* Program committee, [CCS 26]()
* Program committee, [CCS 25](https://www.sigsac.org/ccs/CCS2025/)
* Program committee, [ISSTA 25](https://conf.researchr.org/home/issta-2025)
* Program committee, [CCS 24](https://www.sigsac.org/ccs/CCS2024/home.html)
* Program committee, [SANER 23 (Tool Track)](https://saner2023.must.edu.mo)
* Reviewer, [TDSC 25](https://www.computer.org/csdl/journal/tq)
* Reviewer, [TSE 25](https://www.computer.org/csdl/journal/ts)  
* Reviewer, [TIFS 24](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=10206)  
* Reviewer, [TSE 23](https://www.computer.org/csdl/journal/ts)  
* Reviewer, [TIFS 23](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=10206)
* Reviewer, [TDSC 22](https://www.computer.org/csdl/journal/tq)
* Reviewer, [TIFS 20](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=10206)

### Sub-/Co-reviewer
* [PLDI'23](https://pldi23.sigplan.org)
* [ASE'21](https://conf.researchr.org/home/ase-2021)
* [FSE'19](https://esec-fse19.ut.ee/calls/research-papers/)
* [ISSTA'19](https://conf.researchr.org/home/issta-2019) 
* [ASE'18](http://www.ase2018.com)


## Teaching Service
* CS2311 - Computer Programming (2024 Fall)
* CS3402 - Database System (2024 Spring)

## Funding and Cooperation
Our work **Pangolin** published in **S&P 2020** has been successfully deployed in the Huawei tool-chain
and detected more than **1000+** crashes/bugs!
We have thus received the **Huawei Distinguish Collaborator 2021** award! This is also reported by HKUST [CSE department](https://cse.hkust.edu.hk/News/Huawei2021/)!

## Bugs Hunting
Our self-built fuzzing framework (Integration of S&P'20, 22, 24, TDSC'23) has discovered more than 1000 bugs in the widely-used commercial and open-source projects, with over 100 of them assigned with CVE IDs and over $10K bounties. A partial of vulnerabilities detected can be found [here](https://outstanding-hydrogen-2d1.notion.site/Trophies-aef45e1245a64528bd8ec111b475e03b).
We also list the bugs found specifically for SMT theorem provers [here](https://smtfuzz.github.io).

## Miscs
  * [Tips on writting a research paper (Thomas Reps)](https://5hadowblad3.github.io/files/WritingResearchPapers.pptx)  
  * [How to write a technical paper or a research paper (Michael Ernst)](https://homes.cs.washington.edu/~mernst/advice/write-technical-paper.html)
