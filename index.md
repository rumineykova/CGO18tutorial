### Organizers
Nobuko Yoshida: Professor at Imperial College London (UK)
Michael Kirkedal Thomsen: Assistant Professor at DIKU, University of Copenhagen (DK)

### Audience
Taught by experienced researchers, the tutorial is targeted at (under)graduate students, researchers, but also at practitioners and professionals interested in reversible computing, verified software and programming language development.

### Abstract
Implementing programs without errors are important for recovery, reliability, and security of software. Many approaches to this have over the years been developed, exemplified by numerous testing techniques, formal verification, and static program analysis. These techniques can be used identify problematic parts of programs or to some degree verify the correctness of them. However, achieving any guarantees is often impossible or (at the least) very cumbersome, which to some extend is due to the complexity of the conventional deterministic computation model. Using a more restricted computation model and from this generate code for the less restricted model has the potential to improve this.
In this tutorial we will examine two approaches to this. Common for these is the use of linearity to statically give guarantees that was previously not achievable. First approach is to make the step to a fully reversible computation model, with programming languages and tools developed for this. The second approach is to use session types to achieve it through a type system. As will be detailed below, both can be used to generate code for existing systems and therethrough improve recoverability and reliability.
#### Principles and practice of Reversible Programming
A way to achieve this is to use a computation model that has a notion of reverse execution. Here, the ability of compute from any reached state back to any previous state is the restriction over a deterministic model; but at the same time the restriction gives the possibility for better reasoning within the model.
The first tutorial introduces the principles and methods of programming using the reversible imperative language Janus. We illustrate clean reversible programming with examples, and show how static and dynamic data structures can be used in reversible programming. We discuss concrete tools such as program inverters, and introduce the syntax and semantics of Janus. Finally, we how we can generate C++ code from a Janus programs and its possible usage conventional applications.

#### Principles and practice of Session Types
The second part of the tutorial will feature a combination of principles and practice of session types, which have been intensively developed within different research communities (programming languages, concurrency theory, and software engineering) in the last 20 years. The first part of the tutorial will describe the latest developments on practical program verification based on session types, as available in the Scribble protocol language (http://www.scribble.org). 

### References
-- The Scribble language and code generation exercises (slides and repo)
-- Session types for Erlang (slides and repo) 
-- Session types for (slides and repo)
