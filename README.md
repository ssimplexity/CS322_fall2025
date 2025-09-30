Formal Languages and Automata (KAIST CS322), Fall 2025
====================


<span style="color:red">NEWS</span>
---------------------



LOGISTICS
---------------------
- Lecturer: Eunjung KIM (eunjung.kim@kaist.ac.kr)

- Teaching Assistans 
  - Gunwoo Kim (gunwoo.kim@kaist.ac.kr)
  - Seokbeom Kim (seokbeom@kaist.ac.kr)
  - Doyeop Kim (kimdoyeop@kaist.ac.kr)
  - Kiyun Park (axbyc@kaist.ac.kr)
  - Mamnoon Siam (mamnoon@kaist.ac.kr)
    
- Lecture Room: 1501 at E3-0
  
- Office hour with the lecturer: after each lecture or upon arrangement.
- Office hour with the TAs: Monday 17h-18h, Room 307 at KRAFTON x SoC building.
  

  
- Schedule: 
  - Lecture Schedule. Monday and Wednesday, 09:00-10:30.
  - All lectures will take place on-site.
  - No lecture during the week of 6-10 Oct (Korean Thanksgiving Holiday) and on 19th November.
     
- Grading: Homeworks, Participation, Quiz 30%, Midterm exam 35%, Final exam 35%
  
 
- Course policy:
  - The official language in the class is English. 
  - Homework assignments will be announced on KLMS. Expect an assignment at least every two weeks. Ideally, the solutions to homeworks should be written in English, either in latex / in a text editor, e.g. MS Word / or VERY CLEAN AND IMMEDIATELY READABLE handwriting. People who grade your homework will NOT spend time struggling to decifer your handwriting. No matter how great your solution is, if it's not readable EASILY, it gets exactly that much score. The assignment needs to be submitted before the indicated deadline on KLMS. 
  - A strict policy against dishonest behaviors will be applied; expect an "F" grade and be reported to the SoC board when you fail to follow the [honor code](https://cs.kaist.ac.kr/content?menu=309).
  - No retake of the course will be allowed regardless of your grade.
  - Class attendance is not taken into account for the grade.


Course Description
-------------------
We study ‘computer science’ and a computer is a computing machine. In this course, we study various notions and ideas which were developed since 1930’s in response to fundamental questions such as the following. 
- What do we mean by computing? 
- What is the object that a computing machine computes? Why do we call a programming language a ‘language’?
- Both computer scientists and linguists talk about ‘languages’. Are there something in common? How to formalize the link between them.
- Computers ranging from high-performance server, desktop, laptops to mobile phones, from a wide range of manufacturers are all ‘computers’. On which ground, do we treate them as if they are (essentially) equally powerful machines which are all called computers?
- Is there a problem which cannot be ‘computed’? How to tell if a problem is computable or not.
- Is there a problem we’d better give up finding an ‘efficient’ algorithm? How to tell if a problem is efficiently computable or not.
- Is the computer implemented as your iMac the only form of a computer? 

Recommended Prerequisite
- We assume that you have attended Discrete Mathematics (CS204) or have a sufficient background knowledge covered in similar courses. Introduction to Algorithms (CS300) is a plus. 
- To be successful in this course, you need certain, if not high, level of mathematical maturity. For example, competence in writing a formal proof and digesting abstract concepts in mathematical formalism are needed. 
We also assume that you have a moderate experience in programming, even though we do not do coding during the class.


Course Materials
-------------------
- Main Textbooks: any one of them will work! 
  - John E. Hopcroft, Rajeev Motwani, Jeffrey D. Ullman, Introduction to Automata Theory, Languages and Computation, 3rd Edition, 2006, Pearson/Addision-Wesley. 
  - Michael Sipser, Introduction to the Theory of Computation, 2nd Edition (International Edition), 2006, Course Technology. 

- Other useful materials
  - Peter Linz, An Introduction to Formal Languages and Automata, 6th Edition, 2017, Jones & Bartlett Learning.
  - Scott Aaronson’s lecture notes on Automata, computability and complexity. [Link](https://ocw.mit.edu/courses/6-045j-automata-computability-and-complexity-spring-2011/pages/lecture-notes/).
  - Mathematical Foundations of Computing (Summer 2025), Stanford University. [Link](https://web.stanford.edu/class/cs103/syllabus).
 
Course Plan (liable to be adjusted)
------------
- Week 1 (1-5 Sep): Introduction. Deterministic finite automata.
- Week 2 (8-12 Sep): Nondeterministic finite automata. Equivalence of DFA and NFA. Closure under regular operations. 
- Week 3 (15-19 Sep): Regular expression. Conversions between regular expressions and NFAs. Pumping lemma. State minimization of DFA (Peter Linz' textbook). 
-  Week 4 (22-26 Sep): Myhill-Nerode Theorem. MSO logic on strings (check [Lecture note](https://github.com/ssimplexity/CS492_spring2025/blob/main/01-02.Intro-MSO-DFA.pdf) and [Lecture note](https://github.com/ssimplexity/CS492_spring2025/blob/main/03-04.BuchiTheoremStrings.pdf) for formal treatment). Properties of Regular languages.
- Week 5 (29 Sep - 3 Oct): Properties of Regular languages continues. (check [Lecture note](https://github.com/ssimplexity/CS322_fall2025/blob/main/slides/%5BLec08%5DMyhill-Nerode-regularity.pdf) for a full proof of using Myhill-Nerode theorem for proving a language is regular, presented during the class.) Context-free grammar, derivation. Context-free language. Parse trees.  
- Week 6 (6-10 Oct): Korean Thanksgiving Holiday (no lecture).
- Week 7 (13-17 Oct): Ambiguity. Pushdown automata. Equivalence of pushdown automata and context-free grammars.
- Week 8 (20-24 Oct): Mid-term exam.
- Week 9 (27-31 Oct): Deterministic PDA. Properties of Context-free languages. Pumping lemma for CFL. CYK algorithm.
- Week 10 (3-7 Nov): Turing machines. Examples. Turing thesis. Turing machine variants. 
- Week 11 (10-14 Nov): Universal Turing Machine. Diagonal arguments. Decidable and undecidable languages. Recongnizability. Hierarchy of formal languages.
- Week 12 (17-21 Nov): Reducibility and more undecidable problems. No lecture on 19th Nov.
- Week 13 (24-28 Nov): Reducibility continues. 
- Week 14 (1-5 Dec): Limit of efficient computations. Class P and NP. Polynomial-time reduction and NP-completeness. Cook-Levin Theorem. Other NP-complete problems. Altenate lecturer.
- Week 15 (8-12 Dec): Space complexity. 
- Week 16 (15-19 Dec): Final exam.



