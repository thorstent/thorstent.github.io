---
title: Projects
---
Projects
========  


Liss (Language Inclusion-based Synchronisation Synthesis)
-----------

Liss is the implementation that accompanies our paper [1]. It is a synthesis tool that is given a concurrent C program and will insert synchronisation primitives until the behaviour of the concurrent version of the program is identical to the sequential version. It is currently a research prototype.  
[GitHub](https://github.com/thorstent/Liss)



Limi (Language Inclusion Modulo Independence)
---------------

Limi (Language Inclusion Modulo Independence) is a template library that implements the basic antichain algorithm [2] modulo an independence relation. The library takes as input two non-deterministic finite automata A and B with a shared alphabet and an independence relation *I* over the symbols of the alphabet. The independence relation determines for two symbols if they are independent. Two strings of the language are equivalent module independence if they are identical up to swapping independent symbols. The formal definition is given in our paper [1].  
[GitHub](https://github.com/thorstent/Limi)

The usage of the library is explained in detail on the [project page](http://thorstent.github.io/Limi).

TARA
----

TARA is the implementation that accompanies our paper [3].
The tool accepts concurrent traces in a custom language and returns a succinct error explanation in the form of a DNF over happens-before relations.
This can be used for synthesis or fault localisation.  
[GitHub](https://github.com/thorstent/TARA)


[1] Pavol Černý, Edmund C. Clarke, Thomas A. Henzinger, Arjun Radhakrishna, Leonid Ryzhyk, Roopsha Samanta, Thorsten Tarrach. From Non-preemptive to Preemptive Scheduling using Synchronization Synthesis. In CAV 2015

[2] Martin De Wulf, Laurent Doyen, Thomas A. Henzinger, Jean-François Raskin. Antichains: A New Algorithm for Checking Universality of Finite Automata. In CAV 2006

[3] Ashutosh Gupta, Thomas A. Henzinger, Arjun Radhakrishna, Roopsha Samanta, Thorsten Tarrach. Succinct Representation of Concurrent Trace Sets. In POPL 2015

