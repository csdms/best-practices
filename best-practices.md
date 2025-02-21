---
title: Best Practices in geoscientific software development
theme: moon
---

# Best Practices

in geoscientific software development

~

_Mark Piper and Eric Hutton_  

<a href="https://csdms.colorado.edu">
<img align="center" width="80px" style="margin:-10px 0 20px 0" src="./assets/CSDMS-logo-nocolor.png">
</a>

---

1
## Learn Python

\-

[*Programming with Python*](https://swcarpentry.github.io/python-novice-inflammation/)<br><small>[Software Carpentry]</small>

Note: It's the de facto standard in the geosciences, and in the physical sciences in general. 

----

* Dominant language in many scientific disciplines
* Heavily used [everywhere](https://www.tiobe.com/tiobe-index/), even outside of science
* Programming organizes thinking!

---

2
## Use version control

\-

[*Why should I use version control?*](https://stackoverflow.com/q/1408450)<br><small>[Stack Overflow]</small>

Note: Never lose code again.

----

* Never lose code again
* Track changes while developing code
* Coordinate [team projects](https://github.com/landlab/landlab/) effectively

---

3
## Use the command line

\-

[*Five reasons why researchers should learn to love the command line*](https://www.nature.com/articles/d41586-021-00263-0)<br><small>[Nature]</small>

Note: Boost your efficiency on file operations.

----

* Boosts your efficiency on file operations
* You can type faster than you can mouse and click
* Available on all operating systems

---

4
## Learn a text editor

\-

[*Text Editors and Development Environments*](https://github.com/csdms/ivy/tree/main/lessons/editors)<br><small>[CSDMS Ivy]</small>

Note: Pick one, it doesn't matter which.

----

* Text editors are used to write code; they include tools to write better/faster
* Pick one, it doesn't matter which
* Development environments include additional tools, with increased complexity

---

5
## Share code

\-

[*The Cathedral and the Bazaar*](https://en.wikipedia.org/wiki/The_Cathedral_and_the_Bazaar)<br><small>[Eric S. Raymond; Wikipedia]</small>

Note: This is an ongoing culture shift within the geosciences.

----

* There is an ongoing culture shift within the geosciences
* At CSDMS, we use other people's code (with attribution) all the time

---

## Summary

1. Learn Python
1. Use version control
1. Use the command line
1. Learn a text editor
1. Share code

Note: Extended recommendations follow, if students are interested.

---

6
## Test code

Note: Catch problems before they happen.

----

* Code should have tests to ensure it produces expected results
* Automatically catch problems
* Important for [team projects](https://github.com/landlab/landlab/tree/master/tests)

---

7
## Write documentation

Note: Documentation is as important as code.

----

* Documentation is as important as code
* Explain to others how your code works
* Write for your *future self*

---

8
## Use libraries

Note: Don't reinvent the wheel.

----

* Don't reinvent the wheel
* The other end of "share your code"
* Documentation is critical
* The [entire scientific software ecosystem](https://xkcd.com/2347/) is built on libraries (on libraries, on libraries, ...)

---

9
## Modularize

Note: Don't repeat code.

----

* Don't repeat code
* If you have to do something more than once, write a function

---

10
## "Premature optimization<br>is the root of all evil"

*-- Donald Knuth*

Note: First, make it work. Then, if needed, make it better.

----

* First, make it work
* Then, if needed, make it better

---

## Summary

6. Test code
1. Write documentation
1. Use libraries
1. Modularize
1. Make it work first

---

## Summary summary

Best practices in geoscientific software development

| Primary | Extended |
| ------- | -------- |
| <ol><li>Learn Python<li>Use version control<li>Use the command line<li>Learn a text editor<li>Share code</ol> | <ol start="6"><li>Test code<li>Write documentation<li>Use libraries<li>Modularize<li>Make it work first</ol> |
