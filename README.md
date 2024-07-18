# logic-teaching

This contains reusable files for teaching logic. Some of the work here is *not original*. I'll mention the original work first.

### logic-quiz-template.tex

This template for logic quizzes is optimized for online, anonymized, batch grading of scanned quizzes in Gradescope.[^1]

[^1]: <https://www.gradescope.com>.

### logic-test-template.tex

This template for logic tests is optimized for online, anonymized, batch grading of scanned tests through Gradescope.

### logic-slides-template.tex

This template for logic slides doesn't add much original; it's just a shell document for writing slides using the attractive [Amurmaple Beamer theme](https://ctan.org/pkg/beamerthemeamurmaple), but with my settings and logic commands made available using the following package.

### miniyyc.sty

Especially because I have been teaching using the *forall x: Calgary* textbook, — which is an open-access, open-source resource and so not only free to students but also tweakable — I want to type symbols and proofs that match its formatting. The textbook repository provides those in a file called `forallxyyc.sty`, but it bundles them in a file with other formatting files for producing the textbook. And that extra content breaks Beamer slides (and is unnecessary for using the above files). So, I need to pull out a subset of the symbol and rule definitions from that package and use that as input instead. This package is just selectively excerpted but otherwise just copied verbatim from the `forallxyyc.sty` file which is the work of P.D. Magnus, Richard Zach, Tim Button, and others, released under a Creative Commons Attribution 4.0 International License (CC:BY).



