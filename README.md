# JavaScript
A lot of documents and link to learn the story of JavaScript and how it work (and how VM/Compiler are implemented optimized too).

## High-level resources
Different resources and links about JavaScript or useful tools.

- [Setting up prototypes in V8](https://medium.com/@tverwaes/setting-up-prototypes-in-v8-ec9c9491dfe2)
- [What's up with monomorphism](https://mrale.ph/blog/2015/01/11/whats-up-with-monomorphism.html)
- [JavaScript engine fundamentals: Shapes and Inline Caches](https://mathiasbynens.be/notes/shapes-ics)
- [JavaScript engine fundamentals: optimizing prototypes](https://mathiasbynens.be/notes/prototypes)
- [Javascript performance pitfalls in V8](https://ponyfoo.com/articles/javascript-performance-pitfalls-v8)
- [Dr. Axel Rauschmayer Blog](http://2ality.com/)
- [JS Microbenchmarks](https://github.com/bmeurer/js-micro-benchmarks)

### Tools
- [JavaScript (engine) Version Updater](https://github.com/GoogleChromeLabs/jsvu#readme)

## Virtual Machine, Interpreter, Compiler

### Chakra Core

- [ChakraCore Resources](https://github.com/Microsoft/ChakraCore/wiki/Resources)

### V8 Engine

- [V8 Engine Ignition](https://v8.dev/docs/ignition)
- [V8 Engine TurboFan](https://v8.dev/docs/turbofan)
- [V8 Engine blog](https://v8.dev/blog)
- [V8 Torque (CSA)](https://v8.dev/docs/torque)
- [Egorov V8 resources](https://mrale.ph/v8/resources.html)
- [Understanding V8’s Bytecode](https://medium.com/dailyjs/understanding-v8s-bytecode-317d46c94775)
- [v8-perf](https://github.com/thlorenz/v8-perf);

#### Blogs 

- [Benedikt Meurer](https://benediktmeurer.de/)
- [Vyacheslav Egorov](https://mrale.ph/)
- [Mathias Bynens](https://mathiasbynens.be/)
- [Franziska Hinkelmann](https://fhinkel.rocks/)

#### Shared documents on different performance issues

- [Surface engine signals via Tracing in V8](https://docs.google.com/document/d/1xHl4qF2olKtDEPQFkci8g_wF3oTA-NBoJ6z5cpw1PWk/preview)
- [Fast string concatenation in Javascript](https://docs.google.com/document/d/1o-MJPAddpfBfDZCkIHNKbMiM86iDFld7idGbNQLuKIQ/preview)
- [Faster calls with arguments mismatch](https://docs.google.com/document/d/156nh17BpyLNmDmONyC_ZQUbi0h6goNysds2DLXcAzVc/preview)
- [In-place field representation changes](https://docs.google.com/document/d/10CbqmRs-i8Jy0IE3ToEP25_FD8gj2kEHvfd3N0icN3g/preview)
- [Faster JS to WASM Calls](https://docs.google.com/document/d/1sOIGJ5IRbOPqrgN6hqvEOOu44tiyrxDF0o9AHLAovSk/edit)
- [Array destructuring for multi-value returns (in light of React hooks)](https://docs.google.com/document/d/1hWb-lQW4NSG9yRpyyiAA_9Ktytd5lypLnVLhPX9vamE/edit)
- [Constant field tracking for arrays](https://docs.google.com/document/d/1r2GAvdi_wudDS6iRUfdPw0gxWMfV-IX1PqKgwW47FyE/edit)
- [Fast frozen & sealed elements in V8](https://docs.google.com/document/d/1X6zO5F_Zojizn2dmo_ftaOWsY8NltPHUhudBbUzMxnc/preview)
- [Compressed pointers in V8](https://docs.google.com/document/d/10qh2-b4C5OtSg-xLwyZpEI5ZihVBPtn1xwKBbQC26yI/edit#heading=h.x1cv1fi5g42q)

### Papers and academic research
- [Revolutionizing Embedded Software](http://verdich.dk/kasper/RES.pdf)
- [Context Threading: A flexible and efficient dispatch technique for virtual machine interpreters](http://www.cs.toronto.edu/syslab/pubs/demkea_context.pdf)
- [Optimizing Indirect Branch Prediction Accuracy in Virtual Machine Interpreters](http://www.eecg.toronto.edu/~steffan/carg/readings/optimizing-indirect-branch-prediction.pdf)
- [Virtual Machine Showdown: Stack Versus Registers](https://www.usenix.org/legacy/events/vee05/full_papers/p153-yunhe.pdf)
- [A Generator of Effcient Virtual Machine Interpreters](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.16.7676&rep=rep1&type=pdf)
- [Branch Prediction and the Performance of Interpreters - Don’t Trust Folklore](https://hal.inria.fr/hal-00911146/document)
- [Loop-Aware Optimizations in PyPy's Tracing JIT](https://bitbucket.org/pypy/extradoc/src/98f94d389f25/talk/dls2012/licm.pdf)
- [Constant propagation with conditional branches](https://dl.acm.org/citation.cfm?id=103136)

---

## Language, Principles and Specifications

### Grammar
- [BNF Grammar Example](http://www.cs.utsa.edu/~wagner/CS3723/grammar/examples2.html)
- [BNF & EBNF Grammar Video](https://www.youtube.com/watch?v=hl2NLbIaU7U)

### ECMAScript related
- [ECMAScript archives](https://www.ecma-international.org/archive/ecmascript/)
- [Document prior art / common finalizer pitfalls (WeakRef)](https://github.com/tc39/proposal-weakrefs/issues/78)

---

- [ECMAlgol](https://www.ecma-international.org/publications/files/ECMA-ST-WITHDRAWN/ECMA-2,%201st%20Edition,%20April%201965.pdf)
- [A Self Bibliography](https://sites.cs.ucsb.edu/~urs/oocsb/self/papers/papers.html)
- [Proposal for Simplified, Modern Definitions of "Object" and "Object Oriented](https://wcook.blogspot.com/2012/07/proposal-for-simplified-modern.html)
- [On Understanding Data Abstraction, Revisited](http://www.cs.utexas.edu/~wcook/Drafts/2009/essay.pdf)
- [Object-Oriented Programming Versus Abstract Data Types](http://www.cs.utexas.edu/~wcook/papers/OOPvsADT/CookOOPvsADT90.pdf)
- [Data Abstraction and Hierarchy](https://pdfs.semanticscholar.org/36be/babeb72287ad9490e1ebab84e7225ad6a9e5.pdf)
- [Programming Paradigms for Dummies: What Every Programmer Should Know](https://www.info.ucl.ac.be/~pvr/VanRoyChapter.pdf)
- [Wirfs Brock blog](http://www.wirfs-brock.com/allen/)
