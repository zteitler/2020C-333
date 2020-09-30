---
title: Exam 1 Study Guide
mathjax: true
lessons: "https://zeno.boisestate.edu/classes/m333-fall2020/lessons.html"
---

# Exam 1 Study Guide
{:.no_toc}

* TOC
{:toc}

## Exam 1 Topics

+ The first exam covers weeks 1 through 6 of class. See
  the [Daily Lessons]({{ page.lessons }}) for a complete
  list of topics.

+ Each daily lesson contains a collection of resources
  you can use to review the lessons. In particular pay
  attention to:

  + __Learning Goals:__ Each lesson has a list of learning
    goals. Make sure you know/are able to do everything
    listed in those goals.

  + __Worksheet Solutions:__ The worksheets have both
    written and video solutions. These can be useful
    when going over the worksheets.

  + __Notes:__ The course notes contain the main
    information needed for each lesson. Most of
    the notes contain colored boxes which contain
    key information for that lesson.

## Exam 1 Summary

Here is a summary (partial list) of things you should know and be able to do.
Use the above links for the full list.

+ [Matrix Algebra]({{ page.lessons | append:"#matrices" }}): Know matrix
  addition/subtraction, scalar multiplication, and matrix multiplication.
  Know when it is possible and not possible to do the previous operations.

+ Be able to solve [Linear Systems]({{ page.lessons | append:"#linear-systems1" }})
  by writing the system as an augmented matrix and preforming
  elementary row operations to reduce the system to a simpler
  system (_Gaussian elimination_). Be able to solve systems
  a unique solutions, and an infinite number of solutions.
  Be able to determine if a system has no solution.

+ Be able to compute the [determinant]({{ page.lessons | append:"#determinants" }})
  of square matrices using cofactor expansion.

+ Know that an eigenvector $$\vec{\bf v}$$ is any vector such that
  $$A\vec{\bf v} = \lambda \vec{\bf v}$$ and $$\lambda$$ is the
  eigenvalue.
  Be able to find [Eigenvalues and Eigenvectors]({{ page.lessons | append:"#eigenvectors1" }})
  and [Non-Real Eigenvalues and Eigenvectors]({{ page.lessons | append:"#eigenvectors2" }}).

+ Know the
  [Derivative and Antiderivative Rules]({{ page.lessons | append:"#deriv-review" }}),
  the notation, and what they represent from Calculus.

+ Know the
  [Terminology, classifications, and vocabulary]({{ page.lessons | append:"#ode-intro" }})
  used in differential equations.

+ Know what it means to be a solution to a
  [differential equation]({{ page.lessons | append:"#ode-intro" }})
  and how you can verify a given formula
  is a solution by substituting it into the both RHS and LHS of the
  equation, then use algebra and calculus to show they both simplify
  to the same (equivalent) expression.

+ Be able to determine the order of a differential equation
  and determine if it is [linear]({{ page.lessons | append:"#linearde" }})
  or non-linear. In addition if a differential equation is linear,
  be able to state if it is homogeneous or nonhomogeneous.

+ Be able to identify if a first order differential equation
  is [autonomous]({{ page.lessons | append:"#auto1" }}).

+ Be able to to find and classify equilibrium solutions and draw a phase
  line graph for autonomous DEs. Be able to use the phase line graph to draw
  integral curves and answer questions about solution behavior.

+ Be able to use slope (directional) fields to graph integral
  curves and answer questions about solution behavior.

+ Be able to both recognize which method to use
  and to solve first order DEs using one of the three methods from class.
  In all three cases know how to calculus and algebra
  to rewrite the DE in the form:

  $$\frac{d}{dt}\Big(\text{formula}\Big) = \text{formula with only }t$$

  + Solve [separable equations]({{ page.lessons | append:"#separable" }}) using
    the chain rule.
  + Solve linear equations using an [integration factor]({{ page.lessons | append:"#int-factor" }})
    with the product rule.
  + Solve [exact equations]({{ page.lessons | append:"#exact" }}) using the
    multivariable chain rule.


+ Be able to work with models:

  + The examples that have come up so far have been
    exponential growth/decay, Newton's Law of Cooling,
    population dynamics (logistic growth), second order
    chemical reactions, and tank mixing problems.

  + Be able to setup an initial valued problem (IVP) for tank mixing problems.

  + Given an IVP for one of the above situations, be able
    to:

    + Use qualitative analysis to answer questions about
      solution behavior and limiting values.
    + Be able to solve the DE for an explicit solution.
    + Be able to use the solution to answer questions
      about the model.

## Review / Study Tips

Here are some tips to help you study for the exam
in order of importance:

+ Review the old [quizzes]({{ "/quizzesexams" | relative_url }}).
  Rework any problem you had trouble with.

+ Read over all the learning goals on the
  [Daily Lessons]({{ page.lessons }}) page.

+ Complete the four exam review worksheets
  (these worksheets contain old exam questions).

+ Review the worksheets and their solutions.

+ Review the WeBWorK assignments. Rework the problems you had trouble with.


