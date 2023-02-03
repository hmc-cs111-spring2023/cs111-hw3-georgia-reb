# Free project 2

## The user and a language

This section describes who the project would serve and why a language might be a
good way to meet their needs.

### What's the need?

_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help
them?_

My idea is to do the "Re-design / re-implement an existing DSL" type of project
of the Harvey Mudd Miniature Machine (HMMM), the assembly language used in CS5
here at HMC.

Through this language, students in CS5 who are learning about how a computer
works are learning about the basics of assembly language by getting to use a
simplified version of the language themselves. If they did not have a language
to practice with, it would be much more difficult to learn how assembly works.

### Why a language?

_Why is a DSL appropriate for your user(s)? How does it address the need?_

Giving students in CS5 real assembly language would be very over-complicated,
there is a lot to learn in CS5 and it is probably best to keep the content
very focused and teach only aspects of assembly language that students must learn
about. It addresses this need by giving students a simplified assembly language
that they can run and debug.

### Why you?

_What excites you about this idea? How did you come up with it?_

I liked the idea of doing a re-implementation project described in the homework,
and I thought that this might be a unique project to apply the re-implementation
technique to. I came up with it because I was thinking about different smaller
programs that I might want to re-implement, thought of HMMM, read the
description page, and thought it would be a good fit!

### Domain

_Describe the project's domain in five words._

Assembly language for CS5 learning.

### Interface (syntax)

_How might the user interact with the language? What does programming look
like? Why is this the right way to interact with the problem domain?_

The user would be able to code in the assembly language, then have it be
assembled, and then run. There should also be a debugging interface, where the
user can walk through each line, and the program will show what information is
in the registers and the stack as each line is executed.

### Operation (semantics)

_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

When a program runs, the assembly language will be executed, and the output will
be shown to the user. Errors could include syntax errors, or jumps that go
to lines of code that do not exist. These errors would be communicated to the
user during compilation for synax errors, and at runtime if jumping to a line
that does not exist.

### Expressiveness

_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

It should be easy to write very simple assembly language programs, and it should
be easy to have access to visualizing the registers and stack so that students
can debug and understand the language. It should be difficult to create complex
programs, we also do not have a compiler that writes in HMMM so it would be
difficult to convert a program into HMMM.

### Related work

_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

Yes, this DSL already does exist because this is a re-implementation project.
https://www.cs.hmc.edu/~cs5grad/cs5/hmmm/documentation/documentation.html
http://writehmmm-hmccsstudio.pythonanywhere.com/

The language already does address the need very well, it already exists. I think
there could be additional room for debugging options for students, but also I
wouldn't want to make HMMM too easy for students to use by adding too many extra
debugging techniques.

## The Project

This section examines whether the idea makes for a good CS 111 project.

### Suitability

_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

This is somewhat unique becuase there is already syntax provided by copying the
language idea from the CS5 creators. However, I think that there would be
space for someone working on this project to think about additional debugging
options and the ways in which students would interface with the language.
Because this DSL is focused on teaching, the creator would be focusing on the
user of the language, not the systems aspects of the project. Additionally,
because none of the commands in HMMM are complex, there should not be a very
complciated systems aspects of the language implementation.

### Scope

_How big an idea is this? How ambitious is this project?_

I think that this project is not too ambitious, because the idea is already
well thought out and it is clear what each instruction in HMMM does. There is
then room to create more or less complicted debugging aspects of the project,
which could scale the project to be an appropriate amount of work.

### Benefits and drawbacks

_Why might this be a good idea for a project? Why might this not be a good idea
project?_

This would be a good idea for a project because you could focus on making a
DSL easy to debug and have early CS students work with. There would have to be
a clear focus on making the language with no unintuitive aspects and
few ways to create accidental bugs. It might not be a good idea because the
basic part of the language itself is already designed, and you would not have
much space to make additional design choices.
