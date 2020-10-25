<!-- .slide: data-background="#111111" -->

# Tool-chain and environment

___
<!-- .slide: style="font-size:.88em" -->
## Tool-chain and environment

* <!-- .element: class="fragment fade-in" --> Is the project greenfield, recent or legacy <span style="font-style: italic;"></span>
* <!-- .element: class="fragment fade-in" --> What's the code-base size (in <a href="https://www.webopedia.com/TERM/K/KLOC.html">KLOC</a>) <span style="font-style: italic;">Bigger gets exponentially worse in legacy code. Small mean relatively new or redesigned project.</span>
* <!-- .element: class="fragment fade-in" --> Is continuous integration used? What tools are used to implement it? <span style="font-style: italic;">CI is standard nowadays, but note, that having build server does NOT equals to having CI.</span>
* <!-- .element: class="fragment fade-in" --> Is continuos delivery used? What tools are used to implement it? <span style="font-style: italic;">CD is a step towards from CI, needed to minimize human factors. Having real CD usually means good CI.</span>
* <!-- .element: class="fragment fade-in" --> Have automated tests? <span style="font-style: italic;">No automated testing usually means tightly coupled architecture with tons of errors lurking in a code... usually legacy code.</span>
  * <!-- .element: class="fragment fade-in" --> How many tests are there?
  * <!-- .element: class="fragment fade-in" --> How many <a href="https://www.webopedia.com/TERM/K/KLOC.html">KLOC</a> of tests vs. <a href="https://www.webopedia.com/TERM/K/KLOC.html">KLOC</a> of production? <span style="font-style: italic;">By the rule of thumb - 50:50 is usually nice.</span>
  * <!-- .element: class="fragment fade-in" --> What is the code coverage <span style="font-style: italic;">through the % does not guarantee anything, high % coverage may suggest ppl are really testing what they are doing.</span>
  * <!-- .element: class="fragment fade-in" --> What types of tests are implemented (UT, MT, IT, ST)? Which are automated, which manual?
* <!-- .element: class="fragment fade-in" --> Is there project documentation?
  * <!-- .element: class="fragment fade-in" --> Is it up to date?
  * <!-- .element: class="fragment fade-in" --> Who's updating it?
  * <!-- .element: class="fragment fade-in" --> How this documentation is done? <span style="font-style: italic;">Usually it's a god idea to keep it in VSC-friendly format like LaTeX or asciidoc in the same repo as the code, so that it can be easily updated to track changes in the code.</span>