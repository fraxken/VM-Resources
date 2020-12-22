> Note: ⚠️ feel free to PR new links! It becomes quite difficult to find interesting resources.

# JavaScript
Several links, articles and blogs to understand how modern JavaScript compilers work and optimize our codes. Also includes various resources on ECMAScript and object-oriented programming.

## High-level resources
Different articles and tools dealing with more or less important notions:

- [Setting up prototypes in V8](https://medium.com/@tverwaes/setting-up-prototypes-in-v8-ec9c9491dfe2)
- [What's up with monomorphism (from Vyacheslav Egorov)](https://mrale.ph/blog/2015/01/11/whats-up-with-monomorphism.html)
- [JavaScript engine fundamentals: Shapes and Inline Caches](https://mathiasbynens.be/notes/shapes-ics)
- [JavaScript engine fundamentals: optimizing prototypes](https://mathiasbynens.be/notes/prototypes)
- [JavaScript performance pitfalls in V8](https://ponyfoo.com/articles/javascript-performance-pitfalls-v8)
- [Wormholes in JavaScript (from Mathias Buus)](https://www.nearform.com/blog/wormholes-in-javascript/)
- [Dr. Axel Rauschmayer Blog](http://2ality.com/) - Really a lot of topics that have been covered over time. Feel free to use the search bar.

### Benchmark
- [Dangers of cross language benchmark games](https://mrale.ph/blog/2011/05/12/dangers-of-cross-language-benchmark-games.html)
- [The trap of the performance sweet spot](https://mrale.ph/blog/2011/11/05/the-trap-of-the-performance-sweet-spot.html)
- [Performance tuning as the art of weather forecast](https://mrale.ph/blog/2013/04/29/performance-tuning-as-weather-forecast.html)
- [The Black Cat of Microbenchmarks](https://mrale.ph/blog/2014/02/23/the-black-cat-of-microbenchmarks.html)
- [JavaScript MicroBenchmarks (from Benedikt Meurer)](https://github.com/bmeurer/js-micro-benchmarks) - Real example of how to make a benchmark code

> Vyacheslav Egorov has written many more interesting articles (I recommend you to read them all).

### Tools
- [JavaScript (engine) Version Updater](https://github.com/GoogleChromeLabs/jsvu#readme) - Very cool when you want to run your code on several implementation (for a benchmark for example).
- [eshost CLI](https://github.com/bterlson/eshost-cli) - Run ECMAScript code uniformly across any ECMAScript host

## Virtual Machine, Interpreter, Compiler

### Chakra Core

- [ChakraCore Resources](https://github.com/Microsoft/ChakraCore/wiki/Resources)

### V8 Engine

- [V8 Engine Docs](https://v8.dev/docs) - I highly recommend the documentation on: Ignition, TurboFan, Torque
- [V8 Engine Blog](https://v8.dev/blog)
- [Egorov V8 resources](https://mrale.ph/v8/resources.html) - An extension of this repo 
- [Understanding V8’s Bytecode](https://medium.com/dailyjs/understanding-v8s-bytecode-317d46c94775)
- [v8-perf](https://github.com/thlorenz/v8-perf);

### JSCore (from the blog)

- [JavaScript core Speculation](https://webkit.org/blog/10308/speculation-in-javascriptcore/)
- [A New Bytecode Format for JavaScriptCore](https://webkit.org/blog/9329/a-new-bytecode-format-for-javascriptcore/)
- [Concurrent JavaScript: It can work!](https://webkit.org/blog/7846/concurrent-javascript-it-can-work/)
- [JSC Love ES6](https://webkit.org/blog/7536/jsc-loves-es6/)

---

#### Blogs 

- [Benedikt Meurer](https://benediktmeurer.de/)
- [Vyacheslav Egorov](https://mrale.ph/)
- [Mathias Bynens](https://mathiasbynens.be/)
- [Franziska Hinkelmann](https://fhinkel.rocks/)

#### V8 Shared documents on different performance issues

- [Surface engine signals via Tracing in V8](https://docs.google.com/document/d/1xHl4qF2olKtDEPQFkci8g_wF3oTA-NBoJ6z5cpw1PWk/preview)
- [Fast string concatenation in Javascript](https://docs.google.com/document/d/1o-MJPAddpfBfDZCkIHNKbMiM86iDFld7idGbNQLuKIQ/preview)
- [Faster calls with arguments mismatch](https://docs.google.com/document/d/156nh17BpyLNmDmONyC_ZQUbi0h6goNysds2DLXcAzVc/preview)
- [In-place field representation changes](https://docs.google.com/document/d/10CbqmRs-i8Jy0IE3ToEP25_FD8gj2kEHvfd3N0icN3g/preview)
- [Faster JS to WASM Calls](https://docs.google.com/document/d/1sOIGJ5IRbOPqrgN6hqvEOOu44tiyrxDF0o9AHLAovSk/edit)
- [Array destructuring for multi-value returns (in light of React hooks)](https://docs.google.com/document/d/1hWb-lQW4NSG9yRpyyiAA_9Ktytd5lypLnVLhPX9vamE/edit)
- [Constant field tracking for arrays](https://docs.google.com/document/d/1r2GAvdi_wudDS6iRUfdPw0gxWMfV-IX1PqKgwW47FyE/edit)
- [Fast frozen & sealed elements in V8](https://docs.google.com/document/d/1X6zO5F_Zojizn2dmo_ftaOWsY8NltPHUhudBbUzMxnc/preview)
- [Compressed pointers in V8](https://docs.google.com/document/d/10qh2-b4C5OtSg-xLwyZpEI5ZihVBPtn1xwKBbQC26yI/edit#heading=h.x1cv1fi5g42q)
- [Fast C API in V8](https://docs.google.com/document/d/1nK6oW11arlRb7AA76lJqrBIygqjgdc92aXUPYecc9dU/edit)
- [Spread call performance](https://docs.google.com/document/d/1DWPizOSKqHhSJ7bdEI0HIVnner84xToEKUYqgXm3g30/edit)
- [Iterator builtins design document](https://docs.google.com/document/d/13z1fvRVpe_oEroplXEEX0a3WK94fhXorHjcOMsDmR-8/edit)

#### Papers and academic research
- [Revolutionizing Embedded Software](http://verdich.dk/kasper/RES.pdf)
- [Context Threading: A flexible and efficient dispatch technique for virtual machine interpreters](http://www.cs.toronto.edu/syslab/pubs/demkea_context.pdf)
- [Optimizing Indirect Branch Prediction Accuracy in Virtual Machine Interpreters](http://www.eecg.toronto.edu/~steffan/carg/readings/optimizing-indirect-branch-prediction.pdf)
- [Virtual Machine Showdown: Stack Versus Registers](https://www.usenix.org/legacy/events/vee05/full_papers/p153-yunhe.pdf)
- [A Generator of Effcient Virtual Machine Interpreters](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.16.7676&rep=rep1&type=pdf)
- [Branch Prediction and the Performance of Interpreters - Don’t Trust Folklore](https://hal.inria.fr/hal-00911146/document)
- [Loop-Aware Optimizations in PyPy's Tracing JIT](https://bitbucket.org/pypy/extradoc/src/98f94d389f25/talk/dls2012/licm.pdf)
- [Constant propagation with conditional branches](https://dl.acm.org/citation.cfm?id=103136)

> Most of them are referenced in the V8 documents.

---

## Language, Principles and Specifications

### Grammar
- [BNF Grammar Example](http://www.cs.utsa.edu/~wagner/CS3723/grammar/examples2.html)
- [The language of languages (BNF, EBNF, ABNF ...)](http://matt.might.net/articles/grammars-bnf-ebnf/)

### Related to ECMAScript
- [ECMAScript archives](https://www.ecma-international.org/archive/ecmascript/)
- [Understanding ECMAScript Spec by V8 Team](https://v8.dev/blog/tags/understanding-ecmascript)
- [Document prior art / common finalizer pitfalls (WeakRef)](https://github.com/tc39/proposal-weakrefs/issues/78)
- [TC39 - Forum](https://es.discourse.group/)

### Data Abstraction, Object Oriented etc

- (**recommanded**) [How Data Abstraction changed Computing forever | Barbara Liskov](https://www.youtube.com/watch?v=_jTc1BTFdIo)
- (**recommanded**) [Proposal for Simplified, Modern Definitions of "Object" and "Object Oriented](https://wcook.blogspot.com/2012/07/proposal-for-simplified-modern.html)
- (**recommanded**) [On Understanding Data Abstraction, Revisited](http://www.cs.utexas.edu/~wcook/Drafts/2009/essay.pdf)
- (**recommanded**) [Programming Paradigms for Dummies: What Every Programmer Should Know](https://www.info.ucl.ac.be/~pvr/VanRoyChapter.pdf)
- [A Self Bibliography](https://sites.cs.ucsb.edu/~urs/oocsb/self/papers/papers.html)
- [Object-Oriented Programming Versus Abstract Data Types](http://www.cs.utexas.edu/~wcook/papers/OOPvsADT/CookOOPvsADT90.pdf)
- [Data Abstraction and Hierarchy](https://pdfs.semanticscholar.org/36be/babeb72287ad9490e1ebab84e7225ad6a9e5.pdf)
- [Object-Oriented Programming in Scheme](https://mumble.net/~jar/pubs/oopis.pdf)
- [A Denotational Semantics of Inheritance](https://www.cs.utexas.edu/~wcook/papers/thesis/cook89.pdf)
- [Inheritance Is Not Subtyping](http://www.cs.utexas.edu/~wcook/papers/InheritanceSubtyping90/CookPOPL90.pdf)
- [A Behavioral Notion of Subtyping](https://www.cs.cmu.edu/~wing/publications/LiskovWing94.pdf)
- [Representing Type Information in Dynamically Typed Languages](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.39.4394&rep=rep1&type=pdf)
- A theory of Objects by Martín Abadi, Luca Cardelli

### Others

- [Wirfs Brock blog](http://www.wirfs-brock.com/allen/)
- [ECMAlgol](https://www.ecma-international.org/publications/files/ECMA-ST-WITHDRAWN/ECMA-2,%201st%20Edition,%20April%201965.pdf)
