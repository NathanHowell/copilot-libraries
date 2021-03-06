Overview
========
[copilot-libraries](http://hackage.haskell.org/package/copilot-libraries)
User-supplied libraries for Copilot, including linear-temporal logic,
fault-tolerant voting, regular expressions, etc.

Copilot is a stream (i.e., infinite lists) domain-specific language (DSL) in
Haskell that compiles into embedded C.  Copilot is similar in spirit to
languages like Lustre.  Copilot contains an interpreter, multiple back-end
compilers, and other verification tools.

Examples
=========
Please see the files under the Examples directory in the
[Copilot](http://hackage.haskell.org/package/copilot) for a number of examples
showing the syntax, use of libraries, and use of the interpreter and back-ends.
The examples is the best way to start.

Installation
============
The Copilot library is cabalized. Assuming you have cabal and the GHC compiler
installed (the [Haskell Platform](http://hackage.haskell.org/platform/) is the
easiest way to obtain these), it should merely be a matter of running 
     
         cabal install copilot-libraries

However, we strongly recommend you install Copilot, which installs
copilot-libraries and other packages automatically.  Execute

         cabal install copilot

Dependencies
=============
copilot-libraries depends on the
[Atom](http://hackage.haskell.org/package/copilot-cbmc) to generate hard
real-time C code.

Resources
=========
[copilot-libraries](http://hackage.haskell.org/package/copilot-libraries) is
available on Hackage.

**Sources** for each package are available on Github as well.  Just go to
[Github](github.com) and search for the package of interest.  Feel free to fork!

Copyright, License
==================
Copilot is distributed with the BSD3 license. The license file contains the
[BSD3](http://en.wikipedia.org/wiki/BSD_licenses) verbiage.

Thanks
======
We are grateful for NASA Contract NNL08AD13T to [Galois,
Inc](http://corp.galois.com/) and the [National Institute of
Aerospace](http://www.nianet.org/), which partially supported this work.
