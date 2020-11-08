---
title: Exam 2 Study Guide
mathjax: true
lessons: "https://zeno.boisestate.edu/classes/m333-fall2020/lessons.html"
---

# Exam 2 Study Guide
{:.no_toc}

* TOC
{:toc}

## Exam 2 Topics

+ This exam covers weeks 7 through 11 of class. See
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

## Exam 2 Summary

Here is a summary (partial list) of things you should know and be able to do.
Use the above links for the full list.

+ Know what a [system of first order differential equations](https://zeno.boisestate.edu/notes/333/desystems.html) is.

+ Know how to identify [linear systems of differential equations](https://zeno.boisestate.edu/notes/333/desystems-linear.html)
  and be able to [write linear systems in matrix form](https://zeno.boisestate.edu/notes/333/desystems-linear.html#writing-linear-de-systems-in-matrix-form).
  Know that if a system is not linear, it is called nonlinear.

+ Be able to identify if a linear system is **homogeneous** or **nonhomogeneous**.

+ Know that solutions to [linear homogeneous systems](https://zeno.boisestate.edu/notes/333/desystems-homogeneous.html)
  form a vector space. This means solutions are found as follows:

  - Find a set of fundamental solutions.
    
    $$ \vec{\mathbf{s}}_1(t), \vec{\mathbf{s}}_2(t), \dotsc, \vec{\mathbf{s}}_n(t) $$
    
  - Fundamental solutions must be linearly independent.
    The [Wronskian](https://zeno.boisestate.edu/notes/333/desystems-homogeneous.html#linear-independence-and-the-wronskian)
    can be used to test for linear independence.

  - The general solution is the linear combination of the fundamental solutions.
    
    $$ \vec{\mathbf{s}}(t) = c_1 \vec{\mathbf{s}}_1(t) + c_2 \vec{\mathbf{s}}_2(t) + \dotsb + c_n \vec{\mathbf{s}}_n(t) $$

+ Know that fundamental solutions to linear homogeneous systems
  with constant coefficients are found using
  the [eigenvalues and eigenvectors](https://zeno.boisestate.edu/notes/333/desystems-homogeneous.html#linear-independence-and-the-wronskian)
  of the matrix \\( A \\).
  Know the [three cases for the eigenvalues and eigenvectors](https://zeno.boisestate.edu/notes/333/desystems-summary.html#three-cases-for-the-eigenvalues).

  - [Two Distinct Real Eigenvalues](https://zeno.boisestate.edu/notes/333/desystems-homogeneous.html#two-distinct-eigenvalue-case)
    \\( \lambda_1 \neq \lambda_2 \\) with eigenvectors
    \\( \vec{\mathbf{v}}_1 \\) and \\( \vec{\mathbf{v}}_2 \\):
    
    $$\begin{align*}
      \vec{\mathbf{s}}_1(t) &= e^{\lambda_1 t} \vec{\mathbf{v}}_1 \\
      \vec{\mathbf{s}}_2(t) &= e^{\lambda_2 t} \vec{\mathbf{v}}_2
    \end{align*}$$
    
  - [Two Non-Real Eigenvalues](https://zeno.boisestate.edu/notes/333/desystems-complexev.html)
    \\( \lambda_{1,2} = \mu \pm i \nu \\)
    with eigenvectors \\( \vec{\mathbf{v}}_{1,2}=\vec{\mathbf{u}} \pm i \vec{\mathbf{w}} \\):
    
    $$\begin{align*}
      \vec{\mathbf{s}}_1(t) &= e^{\mu t} \left( \cos(\nu t)\vec{\mathbf{u}} - \sin(\nu t)\vec{\mathbf{w}} \right) \\
      \vec{\mathbf{s}}_2(t) &= e^{\mu t} \left( \sin(\nu t)\vec{\mathbf{u}} + \cos(\nu t)\vec{\mathbf{w}} \right)
    \end{align*}$$
  
  - [One Repeated Real Eigenvalue](https://zeno.boisestate.edu/notes/333/desystems-repeatedev.html)
    $$\lambda_1 = \lambda_2 = \lambda$$:
    
      + If $$\mathbf{A} = \lambda \mathbf{I}$$ is diagonal then:
        
        $$\begin{align*}
          \vec{\mathbf{s}}_1(t) &= e^{\lambda t} \begin{bmatrix} 1 \\ 0 \end{bmatrix} \\
          \vec{\mathbf{s}}_2(t) &= e^{\lambda t} \begin{bmatrix} 0 \\ 1 \end{bmatrix}
        \end{align*}$$
      
      + If $$\mathbf{A} = \lambda \mathbf{I}$$ is not diagonal then:
        
        $$\begin{align*}
          \vec{\mathbf{s}}_1(t) &= e^{\lambda t} \vec{\mathbf{v}} \\
          \vec{\mathbf{s}}_2(t) &= (t \vec{\mathbf{v}} + \vec{\mathbf{w}}) e^{\lambda t}
        \end{align*}$$
        
        where \\( \vec{\mathbf{v}} \\) is an eigenvector and \\( \vec{\mathbf{w}} \\)
        is a **generalized eigenvector** that satisfies the matrix equation
        
        $$ (\mathbf{A} - \lambda \mathbf{I}) \vec{\mathbf{w}} = \vec{\mathbf{v}} $$

+ Be able to use the eigenvalues and eigenvectors to
  [describe behavior of solutions in the phase plane](https://zeno.boisestate.edu/notes/333/desystems-summary.html#behavior-of-solutions)
  and determine the stability of the equilibrium solution at the origin.

+ Know what a [second order differential equation](https://zeno.boisestate.edu/notes/333/secondorderode.html)
  is and be able to identify if a second order differential equation is **linear** or **nonlinear**.

+ Be able to identify if a linear second order differential equation is **homogeneous**
  or **nonhomogeneous**.

+ Be able to write a linear second order differential equation as a
  [system of two first order differential equations](https://zeno.boisestate.edu/notes/333/secondorderode.html#writing-a-second-order-ode-as-a-system-of-first-order-odes)
  by using the substitution
  $$ \vec{\mathbf{s}} = \begin{bmatrix} x_1 \\ x_2 \end{bmatrix}
  = \begin{bmatrix} y \\ y' \end{bmatrix} $$

+ Know that solutions to linear homogeneous second order
  differential equations form a vector space.
  This means that solutions are found as follows:

  - Find a set of two fundamental solutions:
    
    $$ y_1(t) \text{ and } y_2(t) $$
  
  - Fundamental solutions are linearly independent,
    so their [Wronskian](https://zeno.boisestate.edu/notes/333/secondorderode.html#linearly-independent-solutions-and-the-wronskian)
    is non-zero.
    
    $$W(y_1,y_2) = \left| \begin{matrix} y_1 & y_2 \\ y'_1 & y'_2 \end{matrix} \right| $$

  - The general solution is a linear combination
    of the fundamental solutions:
    
    $$ y(t) = c_1 y_1(t) + c_2 y_2(t) $$

+ Be able to find fundamental solutions to
  [second order linear homogeneous differential equations with constant coefficients](https://zeno.boisestate.edu/notes/333/homogeneous-2nd-order.html):

  $$ a y'' + b y' + c y = 0 $$

  - First solve the **characteristic equation**:
  
    $$ a \lambda^2 + b \lambda + c = 0 $$

  - The fundamental solutions depend on the roots of the characteristic equation:

    + Two real roots $$ \lambda_1 \neq \lambda_2 $$:
      
      $$\begin{align*}
        y_1(t) &= e^{\lambda_1 t} \\
        y_2(t) &= e^{\lambda_2 t}
      \end{align*}$$

    + One repeated real root $$\lambda_1 = \lambda_2 = \lambda$$:

      $$\begin{align*}
        y_1(t) &= e^{\lambda t} \\
        y_2(t) &= t e^{\lambda t}
      \end{align*}$$

    + Two non real roots $$\lambda_{1,2} = \mu \pm i \nu$$:
    
      $$\begin{align*}
        y_1(t) &= e^{\mu t} \cos(\nu t) \\
        y_2(t) &= e^{\mu t} \sin(\nu t)
      \end{align*}$$

+ Know that solutions to
  [linear nonhomogeneous second order differential equations](https://zeno.boisestate.edu/notes/333/nonhomogenous-2ndorder-ode.html)
  are of the form
  
  $$ y(t) = y_h(t) + y_p(t) $$

  where \\( y_h(t) \\) is the general solution to the related homogeneous equation
  and \\( y_p(t) \\) is any particular solution to the nonhomogeneous equation.

+ Be able to find particular solutions to linear nonhomogeneous equations
  using either of the two methods:

  - [Undetermined Coefficients](https://zeno.boisestate.edu/notes/333/nonhomogenous-2ndorder-ode.html#particular-solutions)
    which guesses the form of the solution and checks it trying to find values of unknown constants to make it work.

  - [Variation of Parameters](https://zeno.boisestate.edu/notes/333/variation-of-parameters.html)
    which finds the particular solution using integration formulas.
    The particular solution to a DE written in the form
    
    $$ y'' + p(t) y' + q(t) y = g(t) $$
    
    is of the form
    
    $$ y_p(t) = u_1(t) y_1(t) + u_2(t) y_2(t) $$
    
    where \\( y_1(t) \\) and \\( y_2(t) \\)
    are fundamental solutions and \\( u_1(t) \\) and \\( u_2(t) \\)
    are found using the following formulas:
    
    $$\begin{align*}
      u_1(t) &= - \int \frac{y_2(t) g(t)}{W(y_1,y_2)} dt \\
      u_2(t) &=   \int \frac{y_1(t) g(t)}{W(y_1,y_2)} dt 
    \end{align*}$$

+ Be able to use systems of differential equations to work with
  and answer questions about
  [tank mixing problems with a system of two interconnected tanks](https://zeno.boisestate.edu/notes/333/desystems.html#setting-up-a-first-order-system-tank-mixing).

+ Be able to use second order differential equations
  to answer questions about both
  [unforced spring mass systems](https://zeno.boisestate.edu/notes/333/oscillations.html)
  and
  [forced spring mass systems](https://zeno.boisestate.edu/notes/333/forced-oscillator.html).



## Review / Study Tips

Here are some tips to help you study for the exam
in order of importance:

+ Review the old [quizzes]({{ "/quizzesexams" | relative_url }}).
  Rework any problem you had trouble with.

+ Read over all the learning goals on the
  [Daily Lessons]({{ page.lessons }}) page.

+ Complete the three exam review worksheets
  (these worksheets contain old exam questions).

+ Review the worksheets and their solutions.

+ Review the WeBWorK assignments. Rework the problems you had trouble with.


