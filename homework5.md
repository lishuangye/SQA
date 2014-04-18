
## My understanding of formal methods in general and model checking in particular.

### Formal methods 
Formal methods are a particular kind of mathematically based techniques for the specification, development and verification of software and hardware systems.When formal methods are used for software development, formal specifications are used upstream for requirement analysis and product specifications, and formal verifications or analyses are used downstream to verify the design and code before additional verification and validation activities are carried out. 

Formal methods contains formal specifications and formal verifications. 

Formal specification produces an unambiguous set of product specifications so that customer requirements, as well as environmental con- straints and design intentions, are correctly reflected, thus eliminating certain error sources and reducing the chance of accidental fault injections. 

Formal verification checks the con- formance of software design or code to these formal specifications, thus ensuring that the software is fault-free with respect to its formal specifications. And the basic idea of formal verification is to verify the correctness, or absence of faults, of some given program code or design against its formal specifications. Therefore, the existence of formal specifications is a prerequisite for formal verifications.

### Model checking
Model checking is such an approach that automatically or algorithmically checks certain properties for some software systems. It combines algorithmic checking of propositions through execution with formal assertions stated as the propositions with respect to software systems modeled as finite-state machines. And the model checker is a software that runs an algorithm to check the validity of the proposition. If it is checked to be true, a proof is said to be produced. Otherwise, a counterexample is given, much like a failed test case that can be analyzed further for defect fixing.
