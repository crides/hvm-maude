# HVM semantics in Maude

Semantics of [HVM](https://github.com/HigherOrderCO/HVM) in the [Maude rewriting system](http://maude.cs.illinois.edu/w/index.php/The_Maude_System).

Part of a class project for CS524 Concurrent Programming Langauges at the University of Illinois (US).

This currently does the rule compilation and term rewriting on a syntax tree level. All the rewrite rules are either from [the (S)IC implementation in Kind2](https://github.com/HigherOrderCO/Kindex/blob/master/Apps/IntCalc/_.kind2) or [the corresponding parts of the HVM source](https://github.com/HigherOrderCO/HVM/tree/master/src/runtime/rule).

I'm very much a beginner in Maude, thus the current representation of the HVM langauge is pretty crap (see `test.fm` for examples).
