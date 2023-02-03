# Interview project

## The user and a language

This section describes who the project would serve and why a language might be a
good way to meet their needs.

### What's the need?

_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help
them?_

I interviewed a chemistry student who has taken multiple HMC engineering courses,
and is currently in a chemistry focused engineering clinic project. As part of
this project, his group is given programs that create visualizations of
molecules. However, he expressed that it is confusing for chemists because
the programs need to be compiled, and he thought that it would be easier for
chemists to work with an interpreted programming language. He wanted the program
to be as easy and intuitive for chemists with minimal CS background to work with.

### Why a language?

_Why is a DSL appropriate for your user(s)? How does it address the need?_

Yes, the domain is focused on a programming language that creates visualizations
of molecules. It addresses the need by creating a program that is intuitive for
chemists and helps them create visualizations of molecules.

### Why you?

_What excites you about this idea? How did you come up with it?_

I am exicted by this idea because it would make programming more accessible to
scientists who themselves do not have a deep background in CS.
I came up with this idea by interviewing a student, and asking him questions
about why he and his teammates found the complication aspect of the molecule
visualization programs confusing.

### Domain

_Describe the project's domain in five words._

Interpreted molecule visualization programming language.

### Interface (syntax)

_How might the user interact with the language? What does programming look
like? Why is this the right way to interact with the problem domain?_

The user would be able to write in a coding language where they would define
a molecules by defining atoms, bonds and the connections between the atoms and
bonds. Then they could run the program and a visualization of the molecule would
be created. Additionally, there could be information given about the molecule
(maybe polarity, bond strength, etc.) after it is created. 

### Operation (semantics)

_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

When the program runs it will either have errors or create a visualization of
the molecule. There can only be runtime errors, and these would include if the
molecule was not defined correctly (issue with bonds and atoms connections not
matching up). They would be communicated to the user through error messages.

OR, there might be a way in which we could still visualize errors with the
creation of the molecule. Let's say an atom needs an additional bond, there
might be a way to show in the visualization that the atom is missing a bond and
tell the user that they should fix this. That way it would be easier to debug.
Then, there would still be runtime syntax errors.

### Expressiveness

_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

It should be easy to create visualizations of molecules and get basic information
about the molecules. It should be difficult to create molecules that can't
actually exist according to chemistry first principles.

### Related work

_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

Yes, there are programs that allow you to create molecules, we even used one
in the frosh core chemistry class. The type of programs that already exist
are very large, and as such can get very complicated and more difficult to use.

The project that we used in frosh chem is called crystal maker. While this one
is specifically focused on creating full crystals, it is a very large and
complicated program to use.
https://crystalmaker.com/

What is unique about this project, is that it is very focused, and should then
be a much simpler and more intuitve program for chemists to use.

## The Project

This section examines whether the idea makes for a good CS 111 project.

### Suitability

_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

I think the creator would get to spend a significant amount of time thinking
about what would be most intuitive for a chemist to create code with. I am
not sure how complex the visualization creation would be, but I would assume
that we could use aspects of a general purpose language to create these
visualizations. Outside of the visualization aspect, I do not think that there
would be systems aspects because the rest of the project would be focused
on creating the most intuitive language design for chemists.

### Scope

_How big an idea is this? How ambitious is this project?_

I do not have much experience with creating visualizations, and I have no
concept of how difficult this would be to create. If the visualizations was a
reasonable amount of work, I think this would pair well with the work to 
design the syntax for the language. There would also be a scalable amount of
work to add additional information about the molecules, which would make the
project more or less ambitious as is fit.

### Benefits and drawbacks

_Why might this be a good idea for a project? Why might this not be a good idea
project?_

This project might be good because it is very focused on one domain, and the
creator would get to focus on interviewing chemists to understand what
type of molecule visualization program would be most intuitive for them. But,
this might not be a good idea because you would have to understand the molecule
chemistry correctly, which would require a certain depth of understanding of
chemistry. It also might be very difficult to create high quality visualizations
in the scope of this class.
