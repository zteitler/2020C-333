---
layout: page
title: Quiz 3
quiznum: 3
duedate: 2020-09-16
solutions: https://zeno.boisestate.edu/classes/m333-fall2020/solutions/quiz03-solutions.pdf
mathjax: true
---


## Quiz 3 Instructions

+ The purpose of this quiz is to support your learning by
    - offering you an opportunity to demonstrate your mastery of course material
    - providing feedback so that you can plan your studying
    - letting you see how your instructor writes quiz/exam questions, and grades them
    - ... in a low-stakes quiz, with plenty of time for you to make any needed adjustments before the first exam
    - letting you practice using computer software to graph slope fields and integral curves to visualize the behavior of solutions


+ This is a take home quiz:
    - The quiz will become available at **6:00am** on **Sunday, September 13**.
    - The quiz must be completed by **6:00pm** on **Wednesday, September 16**.
    - The close time is strict.

+ The quiz is completed using a combination of [WeBWorK](https://zeno.boisestate.edu/webwork2) and [BlackBoard](https://blackboard.boisestate.edu).
    - The quiz questions are given in WeBWorK. Submit your answers in WeBWorK.
      You can use unlimited submissions, but you will not receive feedback on the correctness of the answers when submitted.
      (The purpose of multiple submissions is in case you find a mistake, or type your answer wrong.)
    - In addition to answering the questions in WeBWorK, upload the written solutions to BlackBoard.


+ Solutions can be written by hand or using computer software, then create a .pdf document to upload.
    - **Handwritten:** Write the solutions in easy to read hand writing,
      then scan the result using a tool like GeniusScan to create a single .pdf document.
    - **Annotation Software:** Use annotation software to write up the solutions in easy to read writing.
      Then save the result as a flattened .pdf document.
    - **Typesetting Software:** Use computer software such as LaTeX or Word+MathType to type up the solutions,
      then save the result as a .pdf document.
    - ~~Solutions should be a single .pdf file with a filename of the form `333-quiz03-yourlastname.pdf`,
      for example `333-quiz03-Teitler.pdf`~~.

Well, actually, I'm not going to worry about the filename.
I would still prefer *single file* submissions if possible,
but I will not require it.
This is a change from the first two quizzes.
The brief explanation is that I originally planned to download all the files,
grade them on my iPad, and then upload the files with written feedback into BlackBoard.
Based on the first two quizzes, that is not going to be practical for me,
so I am going to grade them within BlackBoard.
And that means it doesn't really matter what the filenames are.
Having single files makes it easier for me, but I can handle multiple files if needed.

+ Quality of presentation of written work is a significant part of the grade. This includes:
    - **Neatness:** Sloppy work will score poorly, if it gets graded at all.
    - **Organization:** Work must be easy to find and easy to follow.
    - **Communication:** Work must show how you reached your answer, and must make correct use of mathematical notation.
    - Complete each question on a new page(s).
    - **You must show and explain your work. Use sentences.
      Your explanations have to make sense to a human being who is reading them.**
    - Please make sure that all of your scanned work is legible. That includes turning it to be oriented upright.

+ When working on the quiz **students may:**
    - Discuss the questions with other students and/or the learning assistant.
    - Ask their instructor for help.
    - Use any of the course resources, notes, videos, etc. on the course website, or similar style resources.
    - Use calculators or computers to do basic arithmetic.

+ When working on the quiz **students may not:**
    - Ask any person to complete any part of the quiz for them.
    - Copy another person's work and present it as their own.
    - Explicitly look up the solution to any problem online.
    - Aid another student in any of the above activities.
    - Commit any other infraction of the [Student Code of Conduct](https://www.boisestate.edu/policy/student-affairs/code-of-conduct/).


# Quiz 3 problems

1.  In WeBWorK you will be given a random differential equation of the form $$\frac{dy}{dt}=f(t,y)$$.
    You do not need to show any work on this problem.
    Instead follow the instructions below to create a slope field with multiple integral curves,
    and submit the final graph as your work.
    
    1.  Use [Bluffton University’s Slope Field App](https://homepages.bluffton.edu/~nesterd/apps/slopefields.html)
        to graph the slope field for this differential equation.
        
        * Use the default "One ODE" tab that is selected.
        * Use the `Variables:` drop down menu to choose `dy/dt`.
        * Set the range of the independent variable, \\(t\\), to the interval given in WeBWorK.
        * Set the range of the dependent variable, \\(y\\), to the interval given in WeBWorK.
        * Enter in the DE in the input box for `dy/dt=`
    
    2.  Using the "Plot Numerical Solution Curves" option,
        enter in various initial conditions or use the mouse to click on the slope field
        to draw multiple integral curves.
        Include enough integral curves to highlight the behavior of different solutions.
        
    3.  Answer the limit questions in WeBWorK that describe the behavior
        of different solutions as \\( t \to \infty \\).
        *Answers will either be integers (no decimals/fractions) or \\( \pm \infty \\).*
        
    4.  Provide a copy of the graph you created as follows:

        * Look for the statement, "To save the image, right-click this thumbnail:".
        * Right-click the thumbnail and select 'open image link in new tab' (or window).
        * Right-click the .png image in the new tab to save it.
        * Here is a [Video demonstration of adding an image to a .pdf in Windows 10](https://youtu.be/Deh05NtAMbw).
          And here is a [Video demonstration of adding an image to a .pdf in macOS](https://youtu.be/Deh05NtAMbw).

2.  The Logistic Growth differential equation is

    \\[ \frac{dP}{dt} = rP \left( 1 - \frac{P}{M} \right) \\]

    where \\( P \\) is the population size, \\( t \\) is time,
    \\( r > 0 \\) is the intrinsic population growth rate parameter,
    and \\( M > 0 \\) is the carrying capacity parameter.

    1.  Show that the function \\( P(t) = M \left( 1 + Ce^{-rt} \right) \\)
        is a solution to this differential equation by showing that the LHS and RHS
        both simplify to the same expression.
    
    2.  A rabbit population is growing according to the logistic growth equation.
        Use the randomized values of the parameters \\( r \\) and \\( M \\)
        in WeBWorK to to find the particular solution for the stated initial condition.
        Then answer the final question in WeBWorK about this rabbit population.

3. Answer the question in WeBWorK and show all work showing how you found the answer.
You work must include a reasonable amount of algebra and/or calculus steps.

4. Answer the question in WeBWorK, then provide a written statement justifying the answer you chose.
