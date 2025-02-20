# CS292C Computer-Aided Reasoning for Software

This course is a graduate level introduction to automated reasoning techniques and their application in tools for the design, analysis, and construction of software. In the first half of the course, we will survey the logical foundations and algorithms behind SAT solvers and SMT solvers. In the second half of the course, we will apply these techniques to automatic bug finding, program verification, and program synthesis. As a student in this course, you will learn how solvers work, and how to use them to build cool programming tools!

# Office hour
Instructor : Yu Feng

Gitter: https://gitter.im/CS292C/community


| Date  | Topic                                         | Slides | Read | Out | Due |
|-------|-----------------------------------------------|--------|------|-----|-----|
| 10/5  | Introduction                                  |  [lec1](lectures/lecture1.pdf)      |      |     |     |
| 10/7  | Solver-Aided Programming I (Rosette)          |  [lec2](lectures/lecture2.pdf)      |  R1    |  HW1   |     |
| 10/12  | Solver-Aided Programming II (Neo)             |  [lec3](lectures/lecture3.pdf)      |  R2    |     |     |
| 10/14  | SAT Solving Basics                            |  [lec4](lectures/lecture4.pdf)     |      |     | R1    |
| 10/19 | A Modern SAT Solver                           |  [lec5](lectures/lecture5.pdf)      |      |     |     |
| 10/21 | Applications of SAT                           |  [lec6](lectures/lecture6.pdf)      |  R3    |     |  HW1,R2   |
| 10/26 | SAT Modulo Theories                           |  [lec7](lectures/lecture7.pdf)      |      |     |     |
| 10/28 | Combining Theories              | [lec8](lectures/lecture8.pdf)        |      |  [HW2]  |  R3   |
| 11/2 | The DPLL(T) Framework                             |  [lec9](lectures/lecture9.pdf)       |      |     |     |
| 11/4 | The DPLL(T) Framework II                       |  [lec10]       |  R4    |     |  Proposal (2 pages)   |
| 11/9  | Reasoning about Programs using Hoare logic I  | [lec11](lectures/lecture10.pdf)        |      |     |     |
| 11/11  | No class |        |      |     |     |
| 11/16  | Reasoning about Programs using Hoare logic II |        |      |     |  HW2   |
| 11/18 | Presentation: Group1 (20 mins including Q&A)                        |         |       | [HW3]    |   R4  |
| 11/23 | Presentation: Group2                 |        |      |     |     |
| 11/25 | Presentation: Group3        |         |      |     |    |
| 11/30 | Exploiting Android framework vulnerabilies. Sebastian and Alec (Google Security) |         |      |     |     |
| 12/2  | Autotuning for ML compiler optimizations. Mangpo Phothilimthana (Google Brain)                                 |        |      |     |  HW3  |
| 12/7  | Virtual Poster Session                                 |        |      |     |  Final Report (8 pages)  |


# Grading

1. Programming assignments: 15%
    1. 3 programming assignments, 5% each

2. Paper reviews: 20%
    1. 4 papers, 5% each
    
3. Paper presentation (30 mins): 10%
    
4. Final project: 50%
    1. Team formed by deadline: 5%
    2. 1-page project proposal: 15%
    3. Project presentation: 15%
    4. Final report: 15%
  
5. Class Participation: 5%

### Submission
1. Please submit your homework to gradescope: https://www.gradescope.com
2. All paper reviews should be in PDF.
3. Due at **9am** before the lecture starts.


# Homework

1. [Homework1](hw1/HW1.md)
2. [Homework2](hw2/HW2.md)
3. [Homework3](hw3/HW3.md)

# Presentation groups

### Group1 (11/18)
1. Yuke Wang, Chaofan Shou. Reluplex: An Efficient SMT Solver for Verifying Deep Neural Networks, CAV17
2. Roman Aguilera. Deepcoder: Learning to write programs. ICLR'16
3. Robert McLaughlin. Verx: Safety verification of smart contracts. S&P 2020
4. Scott Chow. Ringer: web automation by demonstration. OOPSLA 2016

### Group2 (11/23)
1. Ryan Schroeder. Liquid Type. PLDI'08
2. Mara Downing. Specification and verification in the field: Applying formal methods to BPF just-in-time compilers in the Linux kernel. OSDI 2020
3. Alon Albalak. Bridging machine learning and logical reasoning by abductive learning. NIPS'2019
4. Rohan Bhatia. Network configuration synthesis with abstract topologies. PLDI'2017

### Group3 (11/25)
1. Lijuan Cheng. Visualization by Example. POPL'2020
2. Peter Boyland. Automating string processing in spreadsheets using input-output examples. POPL 2011
3. Ashley Bruce, David Weinflash. Synthesis of biological models from mutation experiments. POPL 2013
4. Aarti Jivrajani. SQLizer: query synthesis from natural language. OOPSLA 2017

# Reading assignments
1. A Lightweight Symbolic Virtual Machine for Solver-Aided Host Languages. Emina Torlak and Rastislav Bodik. PLDI'14.
2. Program synthesis using conflict-driven learning. Yu Feng, Ruben Martins, Osbert Bastani, and Isil Dillig.  PLDI'18. **Distinguished Paper Award** 
3. Scaling symbolic evaluation for automated verification of systems code with Serval. Luke Nelson, James Bornholt, Ronghui Gu, Andrew Baumann, Emina Torlak, and Xi Wang. SOSP'2019. **Best Paper Award**
4. C. A. R. Hoare. An axiomatic basis for computer programming. Communications of the ACM, vol. 12, no. 10. 1969. ACM DL. **Turing Award**


Tips for writing paper [reviews](REVIEW.md).

Tips for writing a project [proposal](PROPOSAL.md).

# Presentation list

- Rondon, Patrick M., Ming Kawaguci, and Ranjit Jhala. "Liquid types." PLDI'2008.

- Ali Sinan Köksal, Yewen Pu, Saurabh Srivastava, Rastislav Bodík, Jasmin Fisher, Nir Piterman. Synthesis of biological models from mutation experiments. Principles of Programming Languages (POPL). 2013. ACM DL

- Srivastava, Saurabh, Sumit Gulwani, and Jeffrey S. Foster. From program verification to program synthesis. POPL 2010.

- Jha, Susmit, et al. Oracle-guided component-based program synthesis. ICSE 2010.

- Gulwani, Sumit. Automating string processing in spreadsheets using input-output examples. POPL 2011.

- Phothilimthana, Phitchaya Mangpo, et al. "Scaling up superoptimization." ASPLOS 2016.

- Chandra, Kartik, and Rastislav Bodik. Bonsai: synthesis-based reasoning for type systems. POPL 2017.

- Bornholt, James, et al. Optimizing synthesis with metasketches. POPL 2016.

- Yaghmazadeh, Navid, et al. SQLizer: query synthesis from natural language. OOPSLA 2017. **Distinguished Paper Award**

- Deepcoder: Learning to write programs. Matej, et al. ICLR'16.

- Helgi Sigurbjarnarson, James Bornholt, Emina Torlak, and Xi Wang. Push-Button Verification of File Systems via Crash Refinement. OSDI 2016. **Best Paper Award**

- Shaon Barman, Sarah E. Chasins, Rastislav Bodik, Sumit Gulwani. Ringer: web automation by demonstration. OOPSLA 2016.

- Luke Nelson, Jacob Van Geffen, Emina Torlak, and Xi Wang. Specification and verification in the field: Applying formal methods to BPF just-in-time compilers in the Linux kernel. OSDI 2020.

- Chenming Wu, Haisen Zhao, Chandrakana Nandi, Jeff Lipton, Zachary Tatlock, Adriana Schulz. Carpentry Compiler. SIGGRAPH ASIA 2019.

- Permenev, Anton, et al. Verx: Safety verification of smart contracts. 2020 IEEE Symposium on Security and Privacy 2020.

- Chenglong Wang, Yu Feng, Ras Bodik, Alvin Cheung, Isil Dillig. Visualization by Example. POPL'2020.

- Beckett, Ryan, et al. Network configuration synthesis with abstract topologies. PLDI'2017.

- Dai, Wang-Zhou, et al. Bridging machine learning and logical reasoning by abductive learning. NIPS'2019.



