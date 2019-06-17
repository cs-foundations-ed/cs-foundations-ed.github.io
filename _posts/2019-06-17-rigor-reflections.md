---
layout: post
title: "Mathematical Rigor in Computing Foundations"
author: Peter-Michael Osera
categories: rigor
---

As my sabbatical wraps up, I have begun to think about the courses I'll be coming back to next academic year.
I am currently slotted to teach both ends of our theoretical pipeline here at Grinnell---discrete mathematics and theory of computation---which has given me the opportunity to reflect on what I'd like to refine in our foundations courses.
One point of tension that I'd particularly like to resolve is the amount of *mathematical rigor* that I put into these courses.
Over the next few blog posts, I'd like to reflect on this amorphous term, mathematical rigor, and try to suss out what it means for me, my students, and my pedagogy.

---

How much mathematical rigor should we inject into our computing foundations courses?
For some, the answer to this question is obvious: mathematical rigor is a hallmark of an undergraduate computer scientist's education.
And for others, the answer is obvious, just in the other direction: mathematical rigor, in particular proofs, have no real applications for the undergraduate computer scientist outside of the classroom.
In an ideal world, we would have an infinite amount of time to explore the foundations of computing in full mathematical rigor.
After all, being more familiar and comfortable with rigorous mathematical thinking can't make you a worse computer science (probably).

However, in the real world we don't have an infinite amount of time in our courses.
On top of that, we have a myriad of topics that we need to cover in our foundations courses and prioritization becomes our primary concern.
Is it more important our students see a wide variety of algorithms at the level of implementation or should they exposed to a narrow set of algorithms but understand them in a theoretically deep sense?

For example, suppose we discuss merge sort in a data structures course.
Two properties of merge sort we might consider are its *complexity* and *correctness*.
For each of these properties we might ask ourselves:

* Do we state anything about these properties?
* Do we informally discuss why these properties hold?
* Do we formally prove these guarantees?

On top of these properties, we must determine our expectations for students.
Invoking Bloom's taxonomy, do we expect students to merely understand the arguments we put forth or should they be able to create new kinds of arguments based on what we show them?

These pedagogy choices are, of course, contextual in nature:

* Where are the goals of the course?
    A data structures course situated as a CS2 is likely more focused on programming concerns rather than the rigor of the theoretical arguments that it makes, if any.
    In contrast, a data structures course found further in the curriculum might want to develop more sophisticated arguments as a pre-cursor to algorithmic analysis.
* What is the background of the students?
    Students with only calculus I experience may not be at the level where they can readily digest rigorous mathematical arguments.
    But students with more background, either acquired through the curriculum or pre-requisites outside of the computer science department, might expect such a discussion.
* What are my priorities at this point in the course?
    Even if the instructor's goals and the expertise of the students allow for more rigorous arguments, it may not be appropriate for the data structure currently being studied.
    For example, an instructor might provide rigorous proofs for lists but elide proofs for more complicated structures due to time or desire to focus on other things, *e.g.*, in-depth programming examples or applications.

In the past, when I've tackled these questions, I've answered them "from the gut", so to speak.
My research expertise lies primarily in programming language theory, so part of me naturally bends towards infusing as much rigor into my courses as possible.
After all, the whole point of my research agenda is weaponizing logic and formal verification so developers can build software easier and with more confidence.
However, the more pragmatic side of me continually asks *to what end*?

Educators I have talked to have touted the vague benefits of mathematical rigor for students.
With this line of thinking, students who "get" mathematical rigor are more efficient problem solvers and are capable of naivagting higher levels of abstraction, *e.g.*, to be able to see connections between disparate problems.
I have personal antecedotes that affirm this line of thinking, but is it true in general?
Could we be presenting the foundations of computing in a way that is not so mathematical rigorous but more attuned towards the precise needs of our students?