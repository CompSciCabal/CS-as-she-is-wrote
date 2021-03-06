# CS As She Is Wrote

Subjects for which we ought to have lists of papers along with accrued accoutrements. Adapted from https://en.wikipedia.org/wiki/Outline_of_computer_science

## Mathematical foundations

### Game theory
*Useful in artificial intelligence and cybernetics.*

### Graph theory
*Foundations for data structures and searching algorithms.*

### Mathematical logic
*Boolean logic and other ways of modeling logical queries; the uses and limitations of formal proof methods*

### Number theory
*Theory of the integers. Used in cryptography as well as a test domain in artificial intelligence.*


## Algorithms and data structures

### Algorithms
*Sequential and parallel computational procedures for solving a wide range of problems.*

### Data structures
*The organization and manipulation of data.*
- [Ideal Hash Trees](http://lampwww.epfl.ch/papers/idealhashtrees.pdf)
- [Stream fusion: from lists to streams to nothing at all](https://cdn.rawgit.com/CompSciCabal/reading-material/af23849e/pdfs/stream-fusion.pdf)


## Artificial intelligence
*The implementation and study of systems that exhibit an autonomous intelligence or behavior of their own.*

### Automated reasoning
*Solving engines, such as used in Prolog, which produce steps to a result given a query on a fact and rule database, and automated theorem provers that aim to prove mathematical theorems with some assistance from a programmer.*
- [μKanren](https://cdn.rawgit.com/CompSciCabal/reading-material/af23849e/pdfs/mukanren.pdf)

### Computer vision
*Algorithms for identifying three-dimensional objects from a two-dimensional picture.*
[Geometric Approach to tracking mechanical motion](http://authors.library.caltech.edu/28008/1/97-03.pdf)

### Machine learning
*Automated creation of a set of rules and axioms based on input.*

### Evolutionary computing
*Biologically inspired algorithms.*

### Natural language processing
*Building systems and algorithms that analyze, understand, and generate natural (human) languages.*

### Robotics
*Algorithms for controlling the behaviour of robots.*
[Geometric Approach to tracking mechanical motion](http://authors.library.caltech.edu/28008/1/97-03.pdf)

## Communication and security

### Networking
*Algorithms and protocols for reliably communicating data across different shared or dedicated media, often including error correction.*

### Computer security
*Practical aspects of securing computer systems and computer networks.*
- [Stealthy Dopant Level Hardware Trojans](https://cdn.rawgit.com/CompSciCabal/reading-material/af23849e/pdfs/stealthy_trojans.pdf)


### Cryptography
*Applies results from complexity, probability, algebra and number theory to invent and break codes, and analyze the security of cryptographic protocols.*


## Computer architecture
*The design, organization, optimization and verification of a computer system, mostly about CPUs and Memory subsystem (and the bus connecting them).*

## Operating systems
*Systems for managing computer programs and providing the basis of a usable system.*


## Computer graphics
*Algorithms both for generating visual images synthetically, and for integrating or altering visual and spatial information sampled from the real world.*

### Image processing
*Determining information from an image through computation.*

### Information visualization
*Methods for representing and displaying abstract data to facilitate human interaction for exploration and understanding.*


## Concurrent, parallel, and distributed systems

[Practical Foundations of Programming Languages (PFPL)](https://cdn.rawgit.com/CompSciCabal/reading-material/af23849e/pdfs/pfpl2.pdf)

### Parallel computing
*The theory and practice of simultaneous computation; data safety in any multitasking or multithreaded environment.*
- [PFPL]((https://cdn.rawgit.com/CompSciCabal/reading-material/af23849e/pdfs/pfpl2.pdf)) chapter ?? TODO

### Concurrency (computer science)
*Computing using multiple concurrent threads of execution, devising algorithms for solving problems on multiple processors to achieve maximal speed-up compared to sequential execution.*
- [PFPL]((https://cdn.rawgit.com/CompSciCabal/reading-material/af23849e/pdfs/pfpl2.pdf)) chapter ?? TODO

### Distributed computing
*Computing using multiple computing devices over a network to accomplish a common objective or task and thereby reducing the latency involved in single processor contributions for any task.*
- [PFPL]((https://cdn.rawgit.com/CompSciCabal/reading-material/af23849e/pdfs/pfpl2.pdf)) chapter ?? TODO

## Databases

### Relational databases
*the set theoretic and algorithmic foundation of databases.*

### Structured Storage
*non-relational databases such as NoSQL databases.*

### Data mining
*Study of algorithms for searching and processing information in documents and databases; closely related to information retrieval.*


## Programming languages and compilers

### Compiler theory
*Theory of compiler design, based on Automata theory.*
- [A gentle introduction to multi-stage programming](http://www.cs.rice.edu/~taha/publications/journal/dspg04a.pdf)
- [DSL Implementation in MetaOCaml and Template Haskell and C++](http://doc.effective-modeling.org/p/publications/journal/dspg04b.pdf)
- [The Design and Implementation of BER MetaOCaml](http://okmij.org/ftp/meta-programming/ber-design.pdf)
- [Go Meta!](https://www.dropbox.com/s/6m5x71kk0ak7f6f/rompf-snapl15.pdf?dl=0)
- [The Mystery of the Tower Revealed](https://cdn.rawgit.com/CompSciCabal/reading-material/af23849e/pdfs/secrets-of-the-tower.pdf)
- [Boehm Thesis](https://www.itu.dk/~sestoft/boehmthesis/boehm.pdf) (and in the [original French](https://www.research-collection.ethz.ch/bitstream/handle/20.500.11850/132662/eth-32719-02.pdf))

### Programming language pragmatics
*Taxonomy of programming languages, their strength and weaknesses. Various programming paradigms, such as object-oriented programming.*
- [Open, extensible object models](http://piumarta.com/software/cola/objmodel2.pdf)
- [Strachey: Fundamental Concepts in Programming Languages](http://www.itu.dk/courses/BPRD/E2009/fundamental-1967.pdf)
- [Wilson: Uniprocessor GC Techniques](http://www.cs.rice.edu/~javaplt/311/Readings/wilson92uniprocessor.pdf)
- [Bacon et al: A Unified Theory of Garbage Collection](http://researcher.watson.ibm.com/researcher/files/us-bacon/Bacon04Unified.pdf)
- [How to make ad-hoc polymorphism less ad-hoc](http://people.csail.mit.edu/dnj/teaching/6898/papers/wadler88.pdf) (and accompanying [notes](http://okmij.org/ftp/Computation/typeclass.html))
- [KLEE: Unassisted and Automatic Generation of High-Coverage Tests for Complex Systems Programs](https://cdn.rawgit.com/CompSciCabal/reading-material/af23849e/pdfs/klee-osdi-08.pdf)

### Formal semantics
*rigorous mathematical study of the meaning of programs.*
- [Propositions as Types](http://homepages.inf.ed.ac.uk/wadler/topics/history.html#propositions-as-types)
- [Theorems for Free](http://ttic.uchicago.edu/~dreyer/course/papers/wadler.pdf)
- [Practical Foundations of Programming Languages (PFPL)](https://cdn.rawgit.com/CompSciCabal/reading-material/af23849e/pdfs/pfpl2.pdf)

### Type theory
*Formal analysis of the types of data, and the use of these types to understand properties of programs — especially program safety.*
- [Cardelli & Wegner: On Understanding Types, Data Abstraction, and Polymorphism](http://phobos.ramapo.edu/~ldant/oop/cardelli_wegner.pdf)
- [Cardelli: Basic Polymorphic Typechecking](http://lucacardelli.name/Papers/BasicTypechecking.pdf)
- [Milner, A Theory of Type Polymorphism in Programming](http://web.cs.wpi.edu/~cs4536/c12/milner-type-poly.pdf)
- [Practical Foundations of Programming Languages (PFPL)](https://cdn.rawgit.com/CompSciCabal/reading-material/af23849e/pdfs/pfpl2.pdf)
- [Type Systems for Optimizing Stack-based Code](https://cdn.rawgit.com/CompSciCabal/reading-material/af23849e/pdfs/bytecode07.pdf)
- [On the expressive power of programming languages](https://cdn.rawgit.com/CompSciCabal/reading-material/af23849e/pdfs/expressive_power.pdf)
- [The Design of Terralang](https://cdn.rawgit.com/CompSciCabal/reading-material/af23849e/pdfs/design_terra.pdf)

## Scientific computing

### Computational science
*constructing mathematical models and quantitative analysis techniques and using computers to analyze and solve scientific problems.*

### Numerical analysis
*Approximate numerical solution of mathematical problems such as root-finding, integration, the solution of ordinary differential equations; the approximation of special functions.*

### Symbolic computation
*Manipulation and solution of expressions in symbolic form, also known as Computer algebra.*

### Computational physics
*Numerical simulations of large non-analytic systems*

### Computational chemistry
*Computational modelling of theoretical chemistry in order to determine chemical structures and properties*

### Bioinformatics and Computational biology
*The use of computer science to maintain, analyse, store biological data and to assist in solving biological problems such as Protein folding, function prediction and Phylogeny.*

### Computational neuroscience
*Computational modelling of neurophysiology.*


## Software engineering
*The principles and practice of designing, developing, and testing programs, as well as proper engineering practices.*


### Testing programs
*Approaches, principles and pragmatics of verifying programs*
- [KLEE: Unassisted and Automatic Generation of High-Coverage Tests for Complex Systems Programs](https://cdn.rawgit.com/CompSciCabal/reading-material/af23849e/pdfs/klee-osdi-08.pdf)

### Formal methods
*Mathematical approaches for describing and reasoning about software design.*
- [Practical Foundations of Programming Languages (PFPL)](https://cdn.rawgit.com/CompSciCabal/reading-material/af23849e/pdfs/pfpl2.pdf)

### Algorithm design
*Using ideas from algorithm theory to creatively design solutions to real tasks.*

### Computer programming
*The practice of using a programming language to implement algorithms.*

### Human–computer interaction
*The study and design of computer interfaces that people use.*

### Reverse engineering
*The application of the scientific method to the understanding of arbitrary existing software.*


## Theory of computation

### Automata theory
*Different logical structures for solving problems.*

### Computability theory
*What is calculable with the current models of computers. Proofs developed by Alan Turing and others provide insight into the possibilities of what may be computed and what may not.*
- [Breaking through the normalization barrier: a self-interpreter for F-omega](https://cdn.rawgit.com/CompSciCabal/reading-material/af23849e/pdfs/f_omega_norm.pdf)
- [A self-intepreter for System T](https://via.hypothes.is/https://cdn.rawgit.com/CompSciCabal/reading-material/0fec1d70/pdfs/self-interpreter-for-T.pdf)

### Computational complexity theory
*Fundamental bounds (especially time and storage space) on classes of computations.*

### Quantum computing theory
*Explores computational models involving quantum superposition of bits.*


### TODO
*Interesting, but as yet uncategorized papers*
- [Incommensurability](https://cdn.rawgit.com/CompSciCabal/reading-material/af23849e/pdfs/Incommensurability.pdf)
- [Out of the Tar Pit](https://cdn.rawgit.com/CompSciCabal/reading-material/af23849e/pdfs/out-of-the-tar-pit.pdf)
- [Marble Mingling](https://cdn.rawgit.com/CompSciCabal/reading-material/master/pdfs/curtis2003.pdf)
- [Practical Coinduction?](https://cdn.rawgit.com/CompSciCabal/reading-material/6c8e42d0/pdfs/Practical%20Coinduction.pdf)
