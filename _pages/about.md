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

I am a Postdoc research fellow in the [AST Lab](https://ast.ethz.ch) at ETH Zurich, advised by [Prof. Zhendong Su](https://people.inf.ethz.ch/suz/). I am also fortunate to obtain my Ph.D. supervised by [Prof. Charles Zhang](https://cse.hkust.edu.hk/~charlesz/) at the Hong Kong University of Science and Technology. My research focuses on application security, especially leveraging program analysis techniques to ensure software security rigorously.
Specifically, my research takes advantage of both static and dynamic techniques as complements to address deficiency problems in existing vulnerability detection methods, such as fuzzing (S&P'20, 22, 24, TDSC'23, FSE'21, ISSTA 21) and symbolic execution (OOPSLA'21, ISSTA'20).


* NEWS!  
  * Our multi-target directed fuzzing work has been accepted by [S&P 2024](https://www.ieee-security.org/TC/SP2024/index.html)!  
  * Received Google Research Paper award for our directed fuzzer published in [S&P 2022](https://5hadowblad3.github.io/files/Oakland22-Beacon.pdf))!  
  * Our work for improving seed scheduling in fuzz testing gets accepted by [TDSC 2023](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=8858)!  
  * Received Huawei distinguished collaborator award on deploying Pangolin ([S&P 2020](https://5hadowblad3.github.io/files/SP2020.pdf))!  


## Publication

### S&P'24
**Titan: Efficient Multi-target Directed Greybox Fuzzing** (https://5hadowblad3.github.io/files/Oakland24-Titan.pdf)    
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
 <span style='color: red;'>**Google Research Paper Award**</span>
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
(* corresponding author)

### ISSTA'21 
[**Fuzzing SMT Solvers via Two-Dimentional Input Space Exploration**](https://5hadowblad3.github.io/files/ISSTA20201.pdf)  
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

## Funding and Cooperation
Our work **Pangolin** published in **S&P 2020** has been successfully deployed in the Huawei tool-chain
and detected more than thousands of crashes/bugs!
We have thus received the **Huawei Distinguish Collaborator 2021** award! This is also reported by HKUST [CSE department](https://cse.hkust.edu.hk/News/Huawei2021/)!

## Bugs Hunting
Our self-built fuzzing framework (Integration of S&P'20, 22, 24, TDSC'23) has discovered more than 1000 bugs in the widely-used commercial and open-source projects, with over 100 of them assigned with CVE IDs and over $10K bounties. A partial of vulnerabilities detected can be found [here](https://outstanding-hydrogen-2d1.notion.site/Trophies-aef45e1245a64528bd8ec111b475e03b).
We also list the bugs found specifically for SMT theorem provers [here](https://smtfuzz.github.io).


## Award
  * Google Research Paper Award, 2022
  * Huawei Distinguish Collaborator, 2021


## Academic Service
* PC committee, [SANER'23 (Tool Track)](https://saner2023.must.edu.mo)
* Reviewer, [TSE'23](https://www.computer.org/csdl/journal/ts)
* Reviewer, [TIFS'23](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=10206)
* Reviewer, [TDSC'22](https://www.computer.org/csdl/journal/tq)
* Reviewer, [TIFS'20](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=10206)


### Sub-/Co-reviewer
* [PLDI'23](https://pldi23.sigplan.org)
* [ASE'21](https://conf.researchr.org/home/ase-2021)
* [FSE'19](https://esec-fse19.ut.ee/calls/research-papers/)
* [ISSTA'19](https://conf.researchr.org/home/issta-2019) 
* [ASE'18](http://www.ase2018.com)


## Teaching Service
* TA for COMP 3021 - Java Programming (Spring 2022).
* TA for COMP 6613B - Topics in Programming Languages: Semantics and Verification (Spring 2021).
* TA for COMP 3111 Software Engineering (Spring 2020).
* TA for COMP 3111 Software Engineering (Fall 2019).
* TA for COMP 3111 Software Engineering (Spring 2019).
