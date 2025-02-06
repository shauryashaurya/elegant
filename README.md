# *ELEGANT*  
Building **proof checkers** from scratch in Python and coq / rocq.  
  
<html> 
	<img src="./images/elegant-1024.png" width="90%" align="center" alt="Elegant: building proof checkers in python and coq, © Shaurya Agarwal" />  
</html>  
  
* Functional programming basics - concrete examples and no BS    
* Creating a proof checker from scratch - to grok how this stuff works    
* Exploring Coq and a bunch of other functional programming languages

The following is a *very sketchy* early stages outline, which is likely to evolve as I move forward:
  
  
## Proof Checking   
  
Formal systems, inference rules, axioms, the concept of syntactic proof vs. semantic proof, and the difference between proof checking and proof search.  
  
## Representing Mathematical Statements   
  
Formal languages, syntax trees (or abstract syntax trees—ASTs), logical symbols, variables, and how to parse them in code.  
  
## Inference Rules and Proof Systems   
  
Natural Deduction (or another simple proof system), derivation trees, premises vs. conclusion, checking validity step-by-step.  
    
## Designing a Simple Proof Checker in Python   
  
Data structures (for statements and proofs), Python implementations of inference checks, handling typical rules like “modus ponens,” “introduction and elimination rules,” etc.  
  
## Extending the Proof Checker to Handle More Complex Logic  
   
Handling quantifiers (∀ and ∃), equality, or other logical connectives beyond - ∧, ∨, →, ¬.  
    
## Grok Coq   
    
Overview of the Coq environment, the Calculus of Inductive Constructions (CIC), the “tactics” approach in Coq, and differences from our handcrafted checker.  
    
## Implementing a Minimal Checker in Coq   
     
Step-by-step coding of a minimal formal system in Coq, verifying correctness, and how to run proofs within Coq.  
     
## MOAR   
   
Proof automation, advanced type theories etc. etc.  
    
## REFERENCES    
  
Unsorted and in no order of preference or relevance.
    
    
#### enablers   
* [ROCQ](https://rocq-prover.org/)
* [The Coq Proof Assistant](https://coq.inria.fr/documentation)

    
#### videos   
* [Video tutorials for the Coq proof assistant](https://math.andrej.com/2011/02/22/video-tutorials-for-the-coq-proof-assistant/)  
* [DSSS17](https://www.youtube.com/playlist?list=PLovJjGVqXXf3RgVdCXH96pPwSjFLDhSri)  
* [Software Foundations in Coq](https://www.youtube.com/playlist?list=PLre5AT9JnKShFK9l9HYzkZugkJSsXioFs)  
* [COG250](https://www.youtube.com/playlist?list=PL4aJN35xvM_r3o1CqvBuk1948HYNPcqZK)  
* [CS221](https://www.youtube.com/playlist?list=PLoROMvodv4rOca_Ovz1DvdtWuz8BfSWL2), also [Logic Stanford](https://www.youtube.com/playlist?list=PLh7QmcIRQB-uiOS4GMlBbq0jkvtqhqtq0)  
* (useful?) [Formal Methods and Tools for Distributed Systems by Thomas Ball](https://www.youtube.com/watch?v=O4rrm6ZMbug)  
* [Engineering Ontology](https://www.youtube.com/playlist?list=PLyngZgIl3WTiUmcchT_Zf2peiEZwx72G_)
* [The Coq Proof Assistant](https://www.youtube.com/playlist?list=PLt7hcIEdZLAnO7AawDQkHwE7RtwPDOFEc)
* [Formal Analysis, Theory and Algorithms (FATA)](https://www.youtube.com/playlist?list=PL9HHN1wvmtonuhOHxgTvciWXo1YKMq8s7)
* [AI-Taxonomy & Ontology](https://www.youtube.com/playlist?list=PLdFtObdjKwAjC2YoxJqmhya4jaO8zVj-g)
* [UPM MOOC "Ontological Engineering"](https://www.youtube.com/playlist?list=PL8bSwVy8_IcPM7bIxaKtaP9PpkFjjzSuh)
* [2022 - Automation of Ontology Creation](https://www.youtube.com/playlist?list=PLHgX2IExbFou0fHCxmbcKkGa6ovfMYKy1)
* [Ontologies](https://www.youtube.com/playlist?list=PLE_gWmz1WTS6ikBbWTCpEwlD_pjkIDT_H)
* [Synthesis of Models and Systems](https://www.youtube.com/playlist?list=PLgKuh-lKre10UDqM_TGO298OwA1s2yLu-)
* [Formal Methods](https://www.youtube.com/playlist?list=PLPWHypujStMNB87pYMvipG98Rvhd2oWNL)
* [An Introduction to Multi Agent Systems](https://www.youtube.com/playlist?list=PLNZMKGYv14qJHHHYpcMIdiRk6E_sK2EoR)
* [Formal Methods in Mathematics](https://www.youtube.com/playlist?list=PLlF-CfQhukNkWwZt45vkNfWfuO-tBBqPN)
* [Recorded talks on Formal Methods](https://www.youtube.com/playlist?list=PLx4esQq8NnbPotkriJ3EkF-tp81f1mWSE)
* [Formal Methods for Software Engineering](https://www.youtube.com/playlist?list=PLGyeoukah9Nbd1yRDj3ridE7PtcL91-5u)
* [Formal Methods](https://www.youtube.com/playlist?list=PL9o9lNrP1luXgu97NZnQH4cxUkEGB5TJ_)
* [Formal Systems and Analytics](https://www.youtube.com/playlist?list=PLtL6mDL17xa_ERW8e1ZJIV-E2Hkfy714S)
* [what is mathematics and formal system](https://www.youtube.com/playlist?list=PLUEkrYDKvv7doEAQziE7oaKTQdwamyBWu)
* [formal systems](https://www.youtube.com/playlist?list=PL79T_6pcZAxx9WAK85QJGdpT-6GJ-E1PJ)
* [Formal Logic 1 Logic, Propositions, Compound Propositions, Operators, Logical Equivalence](https://www.youtube.com/watch?v=JxCTwQp2bBQ), [Formal Logic 2 Quantifiers And Arguments](https://www.youtube.com/watch?v=e67jDm8Av-0), [Argument Validator Implementation](https://www.youtube.com/watch?v=5L5Jnj7NwhM)
* [Formal Methods for the Informal Engineer: Tutorial #1 - The Z3 Theorem Prover](https://www.youtube.com/watch?v=56IIrBZy9Rc), [Formal Methods for the Informal Engineer: Tutorial #2 - The Coq Theorem Prover (2021)](https://www.youtube.com/watch?v=5e7UdWzITyQ), [Formal Methods for the Informal Engineer: Day 3 (2021)](https://www.youtube.com/watch?v=OlkYNDRo2YE)
* [Correctness proofs of distributed systems with Isabelle/HOL](https://www.youtube.com/watch?v=Uav5jWHNghY)
* [Leslie Lamport: Thinking Above the Code](https://www.youtube.com/watch?v=-4Yp3j_jk8Q)
* [finite state machines](https://www.youtube.com/playlist?list=PLLOaAE6VrtlRu6VI7gKVd9fw9ONRL3LJx)
* (useful?) [Emerging AGI](https://www.youtube.com/playlist?list=PLQ7kdul7PF0dNb7PBYNlBb23NQmHoC78O)
* (***Fun!***) [Godel Escher Bach](https://www.youtube.com/playlist?list=PLBEB6BD2E6633E0CB)
  
#### Books
  
The ROCQ / COQ sites are better resources for these.
* [Mathematical Components](https://math-comp.github.io/mcb/)
* [Programs and Proofs: Mechanizing Mathematics with Dependent Types](https://ilyasergey.net/pnp/)
* [Formal Reasoning About Programs](http://adam.chlipala.net/frap/), [GitHub](https://github.com/achlipala/frap)
* [Coq'Art Examples and Exercises](https://coq-community.org/coq-art/)
[]()  
[]()  
