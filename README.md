## CASPAROV: Computer Algebra System using Reverse Polish Notation

### 1.0 Introduction

Computer Algebra System and Reverse Polish Notation, two terms that predates the birth of most programmers today.

John Harrison's HOL Light https://www.cl.cam.ac.uk/~jrh13/hol-light/ provides easy to follow instructions into the world of computer algebra system (CAS).

Reddit /r/Forth and Usenet newsgroup comp.lang.forth are the most active forums for the Forth programming language, the premier implementation of the reverse Polish nation (RPN) for over five decades. 

While Godot and Blender introduce most young programmers to the significance of algebraic equations in games and animation, few would venture into the niche field of computer algebra system, perhaps the pinnacle of programming and mathematics, the next level up from developing programming languages.

CASPAROV is here to fill the gap, combining the demand of ivory towers for CAS and the ease of use of RPN, as easy as the once legendary, but disappearing HP RPN calculators.

You may wonder, how is that possible? This is perhaps one of the most mysterious truth in human history, whose answer awaits exploration.

Perhaps the less demanding introduction to CAS would be Python Sympy. Yet, readers may judge for themselves the learning curve required to get into it.

CASPAROV is able to break down CAS to simple steps like the commutative, associative and distributive laws, which will serve as our introduction.



### 2.0 Line Plane Intersection

https://en.wikipedia.org/wiki/Line%E2%80%93plane_intersection

Line plane intersection is perhaps one of the most commonly used but under-appreciated equations in games and animation. It is used for collision detection, i.e. to calculate the time at which an object travelliing with a constant velocity hits a plane.

The Algebraic Form section https://en.wikipedia.org/wiki/Line%E2%80%93plane_intersection#Algebraic_form of the Wikipedia page gives a concise and clear solution to the problem.

The equations expressed in reverse Polish notation is given below:

```
p p0 - n = 0
p = d l + l0
find d

p = d l * l0 +
p p0 - n dot = 0


 d l * l0 + p0 - n dot = 0
 d l * l0 + n dot - p0 n dot = 0

d l *  n dot
 l0  n dot + = p0 n dot


d l *  n dot =
 p0  n dot  l0 n dot -

d =
 p0  n dot  l0 n dot -
 l  n dot  div
 ```

For the young programmers usually excited by topics on Reddit /r/programming and https://www.reddit.com/r/ProgrammingLanguages/ writing a program to derive the solution (after being) GIVEN the line and plane equations in RPN is perhaps no more difficult than a weekly assignment in a first year university programming course.

The most difficult part has already been done -- to know that algebraic equations CAN be solved using RPN.



### 2.1 Multitier Stack Machine (nSM)

http://5gl.epizy.com/nsm/fgl.html?i=1

Multitier Stack Machine (nSM) simply means "a stack machine within a stack machine .... (repeat up to N times)" . It is so named because the initial implementations of nSM are coded in PHP and JavaScript, whose interpreters are themselves stack machines.

The core JavaScript stack machine function F() is about 50 lines, not including repeated patterns and library code. It can do Ajax, with a PHP back end running an almost identical stack machine.

We have also implementations in Python, C, C++. The 5GL core should be portable to any programming language. We are working on Kotlin,  Haskell and Rust port now.

While the solution for the line plane intersection above can be implemented in any computer programming language of choice, we will be using a Forth like RPN language, to highlight the following:

(a) the programmer (YOU) can compare various issues amongst implementations in different programming languages
