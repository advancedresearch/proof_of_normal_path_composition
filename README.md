# Proof of Normal Path Composition

A proof of normal path composition in path semantics using diagonal commuting square in Cubical Type Theory.

Uses [cubicaltt](https://github.com/mortberg/cubicaltt), an experimental implementation of [Cubical Type Theory](http://www.cse.chalmers.se/~coquand/cubicaltt.pdf).

For the full proof, see "proof.ctt".

### What is Path Semantics?

[Path Semantics](https://github.com/advancedresearch/path_semantics) is an extremely expressible language for mathematical programming, developed under the [AdvancedResearch](https://github.com/advancedresearch) organization, a research branch of [The Piston Project](https://www.piston.rs/).

### Why is This Proof Important?

Normal paths are fundamental for theorem proving in path semantics.
It is considered the most basic and most important technique.

However, despite normal paths being so important for path semantics,
they have been notoriously difficult to formalize in formal languages.

While the properties of normal paths are formalizable and has been studied in detail, the most important operation, composition in path-space,
has not before been proven in any formal language.

Normal dependent type systems,
such as [Coq](https://coq.inria.fr/) or [Idris](https://www.idris-lang.org/), run into problems when trying to prove composition in path-space for the
general case.

Recent advancements in Type Theory, due to the development of
[Homotopy Type Theory](https://homotopytypetheory.org/), is making progress,
up, towards modeling some parts of Path Semantics. In the mean time,
the research on Path Semantics is making progress from the opposite direction,
down, to less expressive mathematical languages.

Although it is still not possible to use normal paths in Homotopy Type Theory,
and the proof is more indirect than preferred,
this is the first time that composition of normal paths has been proven.
