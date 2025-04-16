# To Infinity

There are a nearly infinite number of ways to solve any software problem.  Not all of these ways are created equal, though.  Some are objectively worse than others.  

For small software projects, it might not matter what way you go about solving the problems you encounter.  It might be enough for the program to "just work."  

As the project grows larger, and the number of people working on it increases, though, we start to run into issues.  It's no longer enough for something to work - it has to stand the test of time.  People will join the project, and leave the project.  The requirements will change.  The dependencies might undergo revisions.  We might want to reuse parts of one project in another project.  Most software lives a life, and we have to write software that will live a long time.

# Measuring Goodness

How do we measure one solution against another, to determine if one is 'better' than another?  Certainly we can pick out obvious examples of 'bad software.'  If something is overly complicated or obfuscated, that's pretty obviously bad.

But every software engineer who has written code for more than just a trivial project knows that opinions about software architecture are complicated and contentious.  I, myself, have spent countless hours debating the finer points of architecture with other engineers, and even occasionally changed my mind(!?)

# (Actually) Measuring Goodness

There are a few things that I tend to rely on when identifying the 'best' solution to a software problem:

### Does it meet the current requirements?

"Duh, the software has to work."  But that's not all it has to do.

One problem tends to be that the requirements are defined at a point in time before the software is fully finished.  Sure, Agile tries to address this by reassessing requirements periodically, and trying to track those alongside engineering deliverables.  But there's still a lag between "requirement communicated" and "requirement satisfied" - unless we are psychic or really, really lucky at guessing.  The "current requirements" are changing at the same time we are working.  Of the two, the requirements are often the ones changing *at a faster rate.*  

The software also has to be fast enough.  That can mean supporting the required number of concurrent users, fully utilizing the (probably expensive) hardware, and hit latency targets.  Oftentimes, software is released that technically does what it is supposed to, but takes so long that frustrating or pointless to use.

Good software can change direction quickly.  It has to not only work properly, but quickly, and flexibly.

### Is it easy to extend later?

This gets a little messy, since we're trying to predict the future.  If we have a perfect ability to predict the future, then we can accurately determine where we need to build in extensibility.

But back to the 'real world' - we do the best we can, and leave ourselves room for logical extension later.

Good software has more room to adapt to new things as they arise.  Version 1.1 or 2.0 is easy to create, because we left room for it.

### Is it easy to maintain?

Testing (unit + integration) probably come to mind here.  They're great for catching mistakes during maintenance that would otherwise slip through.  

There's more to maintenance than that, though.  Software needs organization.  When you open a project, it needs to be easy to find the parts of it that you care about today.  

As an extreme example, consider a project that is entirely in one file, or a function that is thousands of lines long.  If something needs to change, where is it?  Can you keep track of a few different parts of the project at the same time?  Can you manage the mental load of all the interacting parts for long enough to make the changes you need to make, efficiently?

Similarly, if a project is a million files with little to no useful code (ie, just filled with boilerplate), that's also a pain to keep straight.

Documentation is also a part of this - if we solve a problem, and close the file and don't think about it for six months, then need to make changes, how hard is that? 

Good software doesn't tax your brain when you go to modify it.  It's low risk to make changes.

### Is it simple enough?

Modern software design is often oriented around the concept of leveraging a lot of external libraries and dependencies.  Where we might write a quick script in the past, it's become all too easy to download thousands and thousands of lines of code, spin up containers or virual machines, etc in order to solve a problem 'faster.'  

These tools can increase our convienence factor by a lot, there's no denying it.  But including big software packages so that we can leverage a tiny fraction of what they provide, or because they *might* solve a problem we're having is the wrong choice.

Good software is only as complex as it absolutely must be.

# Philosophy & Surviving Reality

