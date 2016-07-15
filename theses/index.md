---
title: Theses
---
Theses
======== 

Doctor of Philosophy (PhD)
--------------------------

**Abstract.** Concurrent Systems are increasingly common and are also used in safety-
critical systems. The hardest part of programming concurrent programs
is to get the synchronisation right. Missing synchronisation typically
manifests itself in the form of subtle, hard to reproduce, errors.
These bugs are hard to find using traditional testing methods due to
their stochastic nature.

In my thesis we focus on two aspects of this problem: 1)
automatically finding potential concurrency bugs and 2) automatically
repairing the program by inserting synchronisation (e.g. locks) into
the code. We develop a technique that requires no user input other
than the source code (simplified C code) and will return the code with
the minimal number of locks that guarantee the concurrent program
calculates the same results as its sequential version would.

[Download PDF](phd_thorsten_tarrach.pdf)

Master
------

**Abstract.** This thesis investigates the relationship between a type system and a general-purpose verification tool. We aim to statically verify typing constraints for a first-order functional language featuring dynamic type-tests and refinement types by translating the code to a standard while language with assertions. Our translation generates assertions in such a way that they express the same constraints in the while program as the typing constraints in the original program. We use a generic verification condition generator together with an SMT solver to prove statically that these assertions succeed in all executions. We formalise our translation algorithm using an interactive theorem prover and provide a machine checkable proof of its soundness. Additionally, we provide a prototype implementation using Boogie (a generic verification condition generation back-end) and Z3 (an efficient SMT solver) that can already be used to verify a large number of test programs.

[Download PDF](master_thorsten_tarrach.pdf)

Bachelor
--------

**Abstract.** This thesis describes a new prototype tool that automatically generates a secure F# implementation of any protocol described in the Spi calculus. Type systems were previously proposed for analysing the security of both Spi calculus processes and F# implementations. The thesis investigates a formal translation from the Spi calculus to F# that is proved to preserve typability, and therefore the security properties of the original protocol are preserved.

[Download PDF](bachelor_thorsten_tarrach.pdf)
