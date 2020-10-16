# Bachelor Thesis - Ideas

## Abstract

We examine arguments in weighted bipolar argumentations graphs and how to evaluate them using Semantics. 

We will compare different semantics and introduce corresponding axioms for each semantic.

## Introduction

- Talk about the why and what. 

- Define Argumentation and how to model it as a graph

- Define nature of arguments

- Define Semantics and why we are examining them

- States of an argument: accepted, undecided, rejected

- Define principles: 

  > "Such principles are useful
  > for deﬁning reasonable semantics, for a better understanding
  > of the design choices or foundations of each semantics, and
  > for comparing pairs of semantics." Amgoud 01

## Mathematical Definitions

- weighted bipolar argumentation graph = wag
- WAG = all wags
- Semantics
- Isomorphism between two wags
- Intrinsic strength of a wag
- overall strength of a wag

### Examples for Math stuff

<img src="Bachelor Thesis - Ideas.assets/image-20201016085646287.png" alt="image-20201016085646287" style="zoom:50%;" />

A wag example

## Principles for Semantics

Show and explain the different principles. What is their relevance in this context?

1. Anonymity
2. 

## Formal Analysis of existing Semantics

- Examine the 2 main families: extension semantics and gradual semantics
- Extension semantics will violate their axioms whenever either their support or attack relation is empty for a given wag
- Gradual semantics can be extended to acyclic graphs
- Define acyclic graphs for wags
- Define restricted semantics

### What is QuAD?

> "QuAD is a restricted semantics assigning a numerical value
> to every argument on the basis of its intrinsic strength, and the
> overall strengths of its attackers and supporters." Amgoud 04

- QuAD violates Weakening and Strengthening, thus it may behave irrationally.
- Show an example of irrational behaviour -> Amgoud 04

### What is DF-QuAD?

## Euler Based Semantics

- This is a novel restriced semantnic that satisfies all axioms

## Conclusion

- We have guidelines for defining semantics on wags
- There are existing semantics for wags, which are mostly problematic since they don't satisfy all axioms.
- Specifically extension semantics do not fully exploit support relations.
- Euler Based Semantics satisfies all axioms for non-cyclic graphs.
- There is yet no semantics that is complete and also supports cyclic graphs.

## Reference

- Amgoud, Leila *Weighted Bipolar Argumentation Graphs: Axioms and Semantics*