# A guide to my repositories

Since I have more than a hundred repositories now,
I thought it would be helpful to create a sitemap,
organized by topics.

Note that forks (for adding pull requests) are not included.
Also, a good part of these repositories are abandoned projects,
so don't expect that everything should work.

I'm pretty sure I won't update this after every new repo,
so some things may be missing.

First here are some of the projects that may be of general interest:

- [dfo](https://github.com/salvipeter/dfo):
  One-file C++ implementations of several derivative-free optimization algorithms.
  Select one and just drop it in your project.
- [libgeom](https://github.com/salvipeter/libgeom):
  A very lightweight C++ geometry library containing the esseentials - 2D & 3D points/vectors,
  2x2 and 3x3 matrices, B-spline curves & surfaces, triangle meshes.
- [geo-framework](https://github.com/salvipeter/geo-framework):
  An extensible 3D geometry visualizer in C++/Qt, suitable for testing out ideas.
  Includes interrogation methods such as contouring, mean curvature map, isophote lines etc.
- [qds-viewer](https://github.com/salvipeter/qds-viewer):
  A visualizer for a collection of (possibly trimmed) B-spline surfaces.
  Based on a predecessor of *geo-framework*.
  Supports exact normals and mean/Gaussian curvatures.
- [gyorstalpalo](https://github.com/salvipeter/gyorstalpalo):
  Very compact grammar summaries for a few natural languages (in Hungarian).
  Currently includes Swahili, Indonesian and Persian.
- [scanned-dictionary](https://github.com/salvipeter/scanned-dictionary/):
  A webpage that helps you search for a word in a scanned dictionary.
  Easily extensible (currently supporting R. S. McGregor's Hindi-English,
  H. Wehr's Arabic-English, M. Haas' Thai-English, 
  and the Aryanpur Concise Persian-English dictionaries).
  Note that scanned pages are not included for reasons of copyright.

---

Next comes the topic-based list:

## CAGD

This is by far the largest group, so it is divided further.

### Curve & surface fairing / aesthetic curves & surfaces

- [cl-nurbs-tests](https://github.com/salvipeter/cl-nurbs-tests/):
  Various fairing algorithm tests, based on CL-NURBS
- [class-a-curves](https://github.com/salvipeter/class-a-curves/):
  Testing various curve representations.
- [discrete-clothoids](https://github.com/salvipeter/discrete-clothoids/):
  Test implementation of discrete clothoid curves
- [ekcurves](https://github.com/salvipeter/ekcurves/):
  Epsilon-kappa curves
- [ksurf](https://github.com/salvipeter/ksurf/):
  Mesh-based surfaces using kappa-curves
- [pseudo-g2](https://github.com/salvipeter/pseudo-g2/):
  A testbed for experimenting with ribbon-based curves
- [quartic](https://github.com/salvipeter/quartic/):
  Quartic (and cubic) B-spline interpolation tests
- [trigo-basis](https://github.com/salvipeter/trigo-basis/):
  Surface tests with the generalized trigonometric basis

### Implicit curves & surfaces

- [csg-script](https://github.com/salvipeter/csg-script/):
  A simple implicit modeling test system scriptable in Scheme
- [dual-contouring](https://github.com/salvipeter/dual-contouring/):
  Minimal dual contouring library
- [dual-primal](https://github.com/salvipeter/dual-primal/):
  Dual/primal optimization of MarchingCubes meshes
- [implicit-curvature](https://github.com/salvipeter/implicit-curvature/):
  Curvature computation for implicit surfaces
- [implicit-fit](https://github.com/salvipeter/implicit-fit/):
  Experiments with fitting implicit surfaces on a loop of curves.
- [implicitize](https://github.com/salvipeter/implicitize/):
  Implicitization of polynomial surfaces
- [ipia](https://github.com/salvipeter/ipia/):
  Implicit Progressive-Iterative Approximation
- [ldni](https://github.com/salvipeter/ldni/):
  A CPU implementation of Layered Depth-Normal Images for experimenting
- [liming](https://github.com/salvipeter/liming/):
  Generalization of Liming-curves
- [marching](https://github.com/salvipeter/marching/):
  Marching cubes implementation
- [marching-surface](https://github.com/salvipeter/marching-surface/):
  Experiments with the marching surface idea
- [polygonizer](https://github.com/salvipeter/polygonizer/):
  A wrapper over Jules Bloomenthal's implicit surface polygonizer

### Multi-sided surfaces / transfinite interpolation / parameterizations

- [biharmonic-spatch](https://github.com/salvipeter/biharmonic-spatch/):
  Creating S-patches from Sabin nets
- [c0coons](https://github.com/salvipeter/c0coons/):
  Multi-sided C0 Coons patch with rational Bézier boundary curves
- [concave-gb](https://github.com/salvipeter/concave-gb/):
  Concave GB patches
- [curved-domain](https://github.com/salvipeter/curved-domain/):
  Curved domain tests
- [curved-patch](https://github.com/salvipeter/curved-patch/):
  N-sided surface with a curved domain
- [displacement](https://github.com/salvipeter/displacement/):
  Testbed for displacement patches
- [dual-surface](https://github.com/salvipeter/dual-surface/):
  Multi-sided dual surface representation
- [gb-center](https://github.com/salvipeter/gb-center/):
  Minimal library computing the center point of GB (and other) patches
- [gordon-wixom](https://github.com/salvipeter/gordon-wixom/):
  Gordon-Wixom C1 interpolation
- [harmonic](https://github.com/salvipeter/harmonic/):
  Harmonic coordinate computation library
- [libmec](https://github.com/salvipeter/libmec/):
  Minimal Entropy Coordinate library
- [manifold](https://github.com/salvipeter/manifold/):
  An n-patch-based construction similar to Zorin's
- [midpoint](https://github.com/salvipeter/midpoint/):
  Minimal library for MidPoint patches.
- [molihua](https://github.com/salvipeter/molihua/):
  Polyhedral modeling with CD-GB patches
- [multiloop](https://github.com/salvipeter/multiloop/):
  Test the parameterization of domains with multiple loops
- [natural-neighbors](https://github.com/salvipeter/natural-neighbors/):
  Framework for testing a natural neighbor based idea
- [nielson](https://github.com/salvipeter/nielson/):
  Nielson's triangular patch
- [permanence](https://github.com/salvipeter/permanence/):
  Permanence patch experiments
- [qgb](https://github.com/salvipeter/qgb/):
  Quadratic GB patch
- [sabin-multiloop](https://github.com/salvipeter/sabin-multiloop/):
  Transfinite patch handling multiple loops, based on Sabin's 1998 paper
- [sketches-plugins](https://github.com/salvipeter/sketches-plugins/):
  Surface plugins for the Sketches modeling system
- [spatch](https://github.com/salvipeter/spatch/):
  S-patch in Haskell
- [tensor-conversion](https://github.com/salvipeter/tensor-conversion/):
  Experiments on converting an n-sided patch to a trimmed tensor product surface
- [toric](https://github.com/salvipeter/toric/):
  Toric patch evaluator
- [transfinite](https://github.com/salvipeter/transfinite/):
  Transfinite interpolation surface library
- [xsolid](https://github.com/salvipeter/xsolid/):
  Framework for testing the ideas described in "The X construction"
- [zheng-ball](https://github.com/salvipeter/zheng-ball/):
  An implementation of the Zheng-Ball multi-sided surface

### General Bézier/B-spline utilities

- [bezier-bspapprox](https://github.com/salvipeter/bezier-bspapprox/):
  Approximate a Bézier curve with a B-spline of lower degree
- [bezier-extractions](https://github.com/salvipeter/bezier-extractions/):
  Computation of Bézier extraction matrices
- [bezier-reduction](https://github.com/salvipeter/bezier-reduction/):
  Optimal degree reduction for Bézier curves
- [bezier-triangle](https://github.com/salvipeter/bezier-triangle/):
  Minimal Bézier triangle evaluation
- [bspline-connect](https://github.com/salvipeter/bspline-connect/):
  Lightweight library for connecting BSpline patches with G1/G2 continuity
- [cl-nurbs](https://github.com/salvipeter/cl-nurbs/):
  A NURBS library in Common Lisp
- [clamp](https://github.com/salvipeter/clamp/):
  Periodic to clamped B-spline curve conversion
- [libgeom](https://github.com/salvipeter/libgeom/):
  Geometry library containing the essentials
- [minibb](https://github.com/salvipeter/minibb/):
  Minimal Bézier/B-spline curve library based on The NURBS Book
- [optimize-curve-depth](https://github.com/salvipeter/optimize-curve-depth/):
  Find the best depth given a 2D B-spline curve and a view direction

### Various fitting utilities

- [conic-fit](https://github.com/salvipeter/conic-fit/):
  Implicit conic fit on a polyline
- [fit-sphere](https://github.com/salvipeter/fit-sphere/):
  Fitting a sphere with fixed radius on noisy data points.
- [fit-test](https://github.com/salvipeter/fit-test/):
  B-spline surface fitting testbed
- [least](https://github.com/salvipeter/least/):
  Least polynomial interpolation
- [profile-fitter](https://github.com/salvipeter/profile-fitter/):
  Fit a polyline (maybe later some curve) on an unordered, noisy point cloud.
- [quadfit](https://github.com/salvipeter/quadfit/):
  Fit continuously connected B-spline surfaces on sampled points with boundary constraints
- [quadric-fit](https://github.com/salvipeter/quadric-fit/):
  Implicit quadric fit on a triangle mesh
- [vertebra-fit](https://github.com/salvipeter/vertebra-fit/):
  Fitting a closed B-spline on a series of points defining vertebrae

### Other

- [3dviz](https://github.com/salvipeter/3dviz/):
  3D animations demonstrating projections
- [geo-framework](https://github.com/salvipeter/geo-framework/):
  Basic framework for 3D geometry applications
- [isophotes](https://github.com/salvipeter/isophotes/):
  Isophote line texture generator
- [isoptic](https://github.com/salvipeter/isoptic/):
  Isoptic surface generation for meshes
- [jet-wrapper](https://github.com/salvipeter/jet-wrapper/):
  Jet fitting normals & curvatures (CGAL wrapper)
- [qds-viewer](https://github.com/salvipeter/qds-viewer/):
  Quad patch viewer
- [sample-framework](https://github.com/salvipeter/sample-framework/):
  A minimal 3D framework for creating simple applications (deprecated, see *geo-framework*)
- [sfview](https://github.com/salvipeter/sfview/):
  NURBS surface visualizer (old project, see *qds-viewer*)
- [strange-problem](https://github.com/salvipeter/strange-problem/):
  Strange fitting problem
- [subdivision](https://github.com/salvipeter/subdivision/):
  Exercises from Analysis and Design of Univariate Subdivision Schemes (by M. Sabin)
- [trimult](https://github.com/salvipeter/trimult/):
  Linux port of Ming Zou et al.'s 3D polygon triangulation library
- [weingarten](https://github.com/salvipeter/weingarten/):
  Testing (embedded) Weingarten maps

## Games

- [dosszioz](https://github.com/salvipeter/dosszioz/):
  Our SAYC-based bidding system
- [magic-keys](https://github.com/salvipeter/magic-keys/):
  Magic Keys Bot Competition
- [malom](https://github.com/salvipeter/malom/):
  A simple Nine Men's Morris game implementation
- [obake-meiro](https://github.com/salvipeter/obake-meiro/):
  A maze generator for my daughter
- [tetris](https://github.com/salvipeter/tetris/):
  A tetris implementation in Clojure

## Programming contests

- [advent](https://github.com/salvipeter/advent/):
  This is a meta-repo for my Advent of Code solutions, linking to the repositories below:
  - [advent2015](https://github.com/salvipeter/advent2015/) (in Common Lisp)
  - [advent2016](https://github.com/salvipeter/advent2016/) (mainly in Prolog)
  - [advent2017](https://github.com/salvipeter/advent2017/) (in Standard ML)
  - [advent2018](https://github.com/salvipeter/advent2018/) (in Common Lisp)
  - [advent2019](https://github.com/salvipeter/advent2019/) (in Prolog)
  - [advent2020](https://github.com/salvipeter/advent2020/) (mainly in Nim)
  - [advent2021](https://github.com/salvipeter/advent2021/) (mainly in Standard ML)
  - [advent2022](https://github.com/salvipeter/advent2022/) (mainly in AWK)
  - [advent2023](https://github.com/salvipeter/advent2023/) (in Tcl)
  - [advent2024](https://github.com/salvipeter/advent2024/) (in 25 different languages)
- [aqua](https://github.com/salvipeter/aqua/):
  AquaQ Challenge Hub solutions
- [icfp2014](https://github.com/salvipeter/icfp2014/):
  My submission to the ICFP '2014 contest
- [icfp2015](https://github.com/salvipeter/icfp2015/):
  My submission to the ICFP2015 contest
- [synacor](https://github.com/salvipeter/synacor/):
  My solution to the Synacor challenge

## Programming languages

- [core-forth](https://github.com/salvipeter/core-forth/):
  A minimal Forth system implementing the 2012 standard
- [lispkit](https://github.com/salvipeter/lispkit/):
  A Scheme implementation of the SECD virtual machine, and a LispKit Lisp compiler
- [ngaro-asm-x86](https://github.com/salvipeter/ngaro-asm-x86/):
  An x86 assembly implementation of the Ngaro Virtual Machine
- [minivm](https://github.com/salvipeter/minivm/):
  A minimal 8-bit virtual machine for didactic purposes

## Other Applications

- [erbi-practice](https://github.com/salvipeter/erbi-practice/):
  ErBi input method learning program
- [qanyulogus](https://github.com/salvipeter/qanyulogus/):
  A program for organizing all the videos, CDs / DVDs at home
- [scanned-dictionary](https://github.com/salvipeter/scanned-dictionary/):
  A webpage that shows a given page of a scanned dictionary
- [wubi-practice](https://github.com/salvipeter/wubi-practice/):
  WuBi input method learning program

## Writings (in Hungarian)

- [formalis](https://github.com/salvipeter/formalis/):
  A short summary of interesting topics in generative grammars & automata
- [gyorstalpalo](https://github.com/salvipeter/gyorstalpalo/):
  Grammar notes for a few natural languages
- [persian-poems](https://github.com/salvipeter/persian-poems/):
  Hungarian translation of Persian poems
- [programnyelv](https://github.com/salvipeter/programnyelv/):
  A tutorial on creating a functional programming language based on combinatoric logic
- [prolog-konyv](https://github.com/salvipeter/prolog-konyv/):
  Problem solving in Prolog for people new to programming
- [prolog-leckek](https://github.com/salvipeter/prolog-leckek/):
  Introductory programming lessons in Prolog

## Miscellaneous

- [bibtex](https://github.com/salvipeter/bibtex/):
  BibTeX entries of my publications
- [dfo](https://github.com/salvipeter/dfo/):
  Testing some derivative-free optimization algorithms
- [laser-pointer](https://github.com/salvipeter/laser-pointer/):
  A transparent window functioning as a laser pointer
- [magnify](https://github.com/salvipeter/magnify/):
  Magnifying glass effect
- [parse-args](https://github.com/salvipeter/parse-args/):
  A small Common Lisp utility library similar to `getopt`
- [progfun-assignments](https://github.com/salvipeter/progfun-assignments/):
  Assignments of the Coursera course Functional Programming Principles in Scala
- [sicp](https://github.com/salvipeter/sicp/):
  A CL translation of the examples/solutions in the Wizard Book
