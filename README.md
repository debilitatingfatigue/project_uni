# project_uni

Avar language corpus + morphological analyser

**The corpus**

Language materials for the corpus were provided by Linguistic Convergence Laboratory (NRU HSE). These are basically materials of a digitized dictionary of the Avar language. (tio be continued)

**lexd-compiler for morphological analysis**

The main tool for morphological analysis used in this work is a C++ compiler from Apertium based on deterministic finite automaton and transducer-technology.

**Interface**

An interface of this corpus was written with Django framework as it provides better security options and some convenient packages then, for intance, Flask module.

**Additional features**

In order to make this application even more convenient, we have added an Avar keyboard, which includes 13 unique graphemes.

**Multithreading**

Multithreading is organised using Golang tools.
