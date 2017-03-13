<!-- .slide: data-background="img/background_title.jpg" data-state="intro" class="center" -->
![](img/cc_logo.png) <!-- .element: class="cc_logo" -->
## Scrum for developers - Sprint 3 <!-- .element: class="heading" -->
----
### Mocking <!-- .element: class="heading" -->

---

### Agenda

* What is mocking?
* When should I use mocks?
* Live coding
* Definition of Done

---

### What is mocking?

"In object-oriented programming, mock objects are simulated objects that mimic the behavior of real objects in controlled ways." [Source: Wikipedia]

Frameworks in Java:

* [Mockito](http://mockito.org/)
* [Powermock](http://code.google.com/p/powermock/)
* [JMockit](http://code.google.com/p/jmockit/)
* [EasyMock](http://easymock.org/)
* ...

---

### When should I use mocks?

* for application parts that make the test indeterministic
* for application parts that have unwanted side effects 
* for application parts that make the test only run on a special environment
* for application parts that make the test extremely slow
     
---

### Live Coding

Write (unit-)tests for the class `StandardBookService`.

Idea shortcut to create test class (Windows/Linux): 

`Ctrl+Shift+T`

or 

1. `Alt+Enter` with cursor on the class we want to test
2. select "Create Test" and hit Enter

---

<div class="dodbox">
**Definition of Done**
* code is developed test first (mocks can be used where inevitable/reasonable)
* automated database migration works <!-- .element: class="former" -->
* release notes are updated <!-- .element: class="former" -->
* release artifacts are deployed in artifactory <!-- .element: class="former" -->
* version number is incremented <!-- .element: class="former" -->
* stories are developed in (feature) branches <!-- .element: class="former" -->
