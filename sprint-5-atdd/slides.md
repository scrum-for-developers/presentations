<!-- .slide: data-background="img/background_title.jpg" data-state="intro" class="center" -->
![](img/cc_logo.png) <!-- .element: class="cc_logo" -->
## Scrum for developers - Sprint 4 <!-- .element: class="heading" -->
#### Acceptance Test Driven Development (ATDD)
 <!-- .element: class="heading" -->

#
#### Speaker: Simon Norra <!-- .element: class="heading" -->
#### March 14th, 2017 <!-- .element: class="heading" -->

---

### Agenda
* Why should we do acceptance testing?
* How can we get there?
* How can we do it?
* Definition of Done

---
<!-- .slide: data-background="img/background_title.jpg" class="center" -->
### Why should we do ATDD? <!-- .element: class="heading" -->

---

### Communication Problems

* Requirements are misunderstood
* Obvious things are not obvious
* Wrong assumptions
* Specification
  * does not reflect implementation
  * has gaps and is inconsistent
* The most important information in the business specification is ...

<div class="dodbox">
### The author‘s phone number <!-- .element: class="heading" -->

---

### Fail fast

* Requirements are not met every time
* Gain feedback as fast as possible
* Not met requirements or bugs should be discovered **before** a feature comes into production!

![](img/atdd-pipeline-intro.png)

---

## What if ... ?

<!-- tests are specified in business domain terms -->
* PO && Devs would speak the same language?

* PO could define his specification beforehand - in code!?

* Devs could reduce explorational testing by automated tests?

---
<!-- .slide: data-background="img/background_title.jpg" class="center" -->
### How can we get there? <!-- .element: class="heading" -->

---

### Agile Acceptance Testing

* Use real examples to build a common understanding and vocabular (DDD: "ubiquitous language")
* Choose a set of these examples for the specification and their acceptance tests
* Automate the verification of the acceptance tests
* Focus the software development on the "green" of the acceptance tests
* Use the set of acceptance tests to discuss future change requests

---

### What executable specifications are NOT

* No scripts
  * But Rules
* Do not **replace** exploratory testing
  * But allows you to invest more time into testing corner cases
* No UI Tests

---

### User stories and executable specification work hand in hand

* User Stories
  * Who? What? When?
  * Encourage discussion
* Executable specification
  * Result of the discussion
  * Common understanding of all participants (PO, Dev, QA, ...)

---
<!-- .slide: data-background="img/background_title.jpg" class="center" -->
### How can we do it? <!-- .element: class="heading" -->
#
#### Let us dig into the code! <!-- .element: class="heading" -->

---

### Definition of Done

<div class="dodbox">
**Definition of Done**
* acceptance tests get executed
* acceptance tests are green (blue)
* (sonar is green) <!-- .element: class="former" -->
* code is developed test first <!-- .element: class="former" -->
* automated database migration works <!-- .element: class="former" -->
* release notes are updated <!-- .element: class="former" -->
* release artifacts are deployed in artifactory <!-- .element: class="former" -->
* version number is incremented <!-- .element: class="former" -->
* stories are developed in (feature) branches <!-- .element: class="former" -->
