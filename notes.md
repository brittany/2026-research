# Notes from Research Meetings 

## SoCG 2026

* Thursday
    - Alexander Munteanu, Simon Omlor, Jeff M. Phillips: Hardness of
      High-Dimensional Linear Classification

* Wednesday
    - Complements of Finite Unions of Convex Sets
    - On Computing the (Exact) Fréchet Distance with a Frog
    - Disproving two conjectures on the Hamiltonicity of Venn diagrams
    - On the maximum number of tangencies among 1-intersecting curves
    - Upward Book Embeddings of Partitioned Digraphs
    - On minimum Venn diagrams
    - Unavoidable patterns and plane paths in dense topological graphs

## Sunbethmath

* 10 Jan 2026
    - path spaces: metrizable, locally compact, homotopy type of a CW complexes
        - prodsimplicial approach of 13 May 2026
        - from Raussen "trace spaces in a pre-cubical complex"
            - trace spaces (path space up to reparameterization)
            - precubical: don't have xxx
    - Patel's directed PDs
        - we have: category of trace categories, prodcut is just the product of
          trace categories.
        - need: Grothendic group. WW: can use arclength? -> actually, we can't
          use the arclength
        - for G-group, we need from section 6.1 [a] is a dipath, the condition
          we need is: [a]+[b]=[a square b]

* 27 May 2026
    - continuous GH
    - isomorphism classes of our trace categories.

## Sush's Presentation on his SoCG Paper

* In R^1: there is a 5/4 approximation, but is it NP-hard to approximate better?
  (see Majhi, Vitter, Wenk "Approximating GH dist in Euclidean Space")
* Russian group, ivanov is actively working on some of the open problems.
* any length space can be approximated by a metric graph via an epsilon-net (in
  Gromov's book, I think). Any length space is quasi-isometric.

## HPC Request from John Sheppard

* Computations in the field of computational topology are often bottlenecked by
  memory usage. While proof-of-concepts can often be run locally on small
  examples, having access to large shared memory on an HPC is essential for
  running algorithms / experiments on real data.
* Some of the work at the intersection of computational topology and statistics
  requires running the same computation on a large number of small data sets.
  While individually these can be run off the HPC, the sheer number of things
  that needs to be computed necessitates the use of an HPC.
