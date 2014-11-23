# Design notebook for week ending November 23, 2014

## Description
This week we worked on getting a prototype ready for class on Monday. We
split the work into semantics, IR, and parser. The parser was challenging
with regards to parsing the datetime expressions within the task syntax, and
we are still working on how to handle that. We are also working on how to
have the sublime plugin interact with our scala code.

## Questions

**What is the most pressing issue for your project? What design decision do
you need to make, what implementation issue are you trying to solve, or how
are you evaluating your design and implementation?**
The most pressing issue right now is the error-handling, which is discussed later
in this notebook entry. We are also facing challenges regarding the interface between
our scala code and the sublime plugin.

**What questions do you have for your critique partners? How can they best help
you?**
Right now, we are struggling with error handling in the parser. The biggest problem
is parsing the datetime part of the task syntax.

**How much time did you spend on the project this week? If you're working in a
team, how did you share the labor?**
We spent 6 hours this week in team meetings in order to ensure that our separate tasks
will work well together. I also worked an additional 1.5 hours individually on the 
parser for our project and 1 hour on the critique. Lastly, I spent half an hour on this
entry for the project notebook. 

## Post-critique summary
There was not much to critique since we changed our language for our project midway
through the week, so a lot of Phil's comments were irrelevant. He was mostly concerned
with Nick's work on the semantics and the error handling in our code. 
## Post-critique reflection
The error-handling concerns that Phil had this week are definitely something 
that we still need to work on. We spent some time working with the parser
as a team and are running into problems regarding error handling in our testing
and we have yet to resolve this issue. We need to find the proper place to catch errors
when we are parsing our datetime for the tasks, but we also need to figure out
more generally where we will be doing error checks.
