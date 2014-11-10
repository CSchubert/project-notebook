# Design notebook for week ending November 9, 2014

## Description

**TODO:** Fill in this part with information about your work this week:
important design decisions, changes to previous decisions, open questions,
exciting milestones, preliminary results, etc. Feel free to include images
(e.g., a sketch of the design or a screenshot of a running program), links to
code, and any other resources that you think will help clearly convey your
design process.

## Questions

**What is the most pressing issue for your project? What design decision do
you need to make, what implementation issue are you trying to solve, or how
are you evaluating your design and implementation?**

We are working with plug-ins for sublime and trying to use that to create our 
language. We need to come up with an IR and make sure that we all understand
the sublime plug-in interface since we are not all familiar with that. 

**What questions do you have for your critique partners? How can they best help
you?**

Questions or ideas regarding scale or our choice of implementing our design
as a sublime plug-in would be useful. We have a good idea of what kinds of 
features we want to start out with, but we are trying something new by
having our project interface with sublime. 

**How much time did you spend on the project this week? If you're working in a
team, how did you share the labor?**

## Post-critique summary
The critique focused on the design portion of our language. Nick (who 
wrote the critique) noted that our language shouldn't be too simple nor
too verbose so that the final product was easy to use but also beneficial
to the user. 

## Post-critique reflection
After reading Nick's critique and also chatting with him in class, we decided
that we would form a three-person group because we were working in such
similar domains. We decided to merge our ideas and use TODO.txt-style 
syntax but create something that doesnt actually interact with the TODO.txt source
code. Instead of focusing only on dependencies, we decided to create a syntax
that allows us to have tasks with dependencies and other identifiers. 
