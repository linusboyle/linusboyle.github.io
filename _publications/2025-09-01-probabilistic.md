---
title: "Structural Abstraction and Refinement for Probabilistic Programs"
collection: publications
permalink: /publication/probabilistic
excerpt: 'In this paper, we present structural abstraction refinement, a novel framework for verifying the threshold problem of probabilistic programs. Our approach represents the structure of a Probabilistic Control-Flow Automaton (PCFA) as a Markov Decision Process (MDP) by abstracting away statement semantics. The maximum reachability of the MDP naturally provides a proper upper bound of the violation probability, termed the structural upper bound. This introduces a fresh ``structural'' characterization of the relationship between PCFA and MDP, contrasting with the traditional ``semantical'' view, where the MDP reflects semantics. The method uniquely features a clean separation of concerns between probability and computational semantics that the abstraction focuses solely on probabilistic computation and the refinement handles only the semantics aspect, where the latter allows non-random program verification techniques to be employed without modification.

Building upon this feature, we propose a general counterexample-guided abstraction refinement (CEGAR) framework, capable of leveraging established non-probabilistic techniques for probabilistic verification. We explore its instantiations using trace abstraction. Our method was evaluated on a diverse set of examples against state-of-the-art tools, and the experimental results highlight its versatility and ability to handle more flexible structures swiftly.'
date: 2025-10-01
venue: 'International Conference on Object-Oriented Programming Systems, Languages, and Application (OOPSLA) 2025'
---
