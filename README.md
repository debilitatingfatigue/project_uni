# project_uni

Avar language corpus + morphological analyser

_The corpus_

Language materials for the corpus were provided by Linguistic Convergence Laboratory (NRU HSE). These are basically materials of a digitized dictionary of the Avar language. (tio be continued)

_lexd-compiler for morphological analysis_

The main tool for morphological analysis used in this work is a C++ compiler from Apertium based on deterministic finite automaton and transducer-technology.

_Interface_

An interface of this corpus was written with Django framework as it provides better security options and some convenient packages then, for intance, Flask module.

_Additional features_

In order to make this application even more convenient, we have added an Avar keyboard, which includes 13 unique graphemes.

_Multithreading_

Multithreading is organised using Golang tools.
