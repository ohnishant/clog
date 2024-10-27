# Clog

A logging library for myself written in C. (probably a name already taken, I'm bad at this)

This is an experiment, I do not know how to do this I just want to play around with ideas and with pure C.
This project will probably get scrapped very soon, but if i come up with something that I can use
myself, for my basic use cases, it will be good enough :)


## Ideas/Thinking Ground

This area is meant to be for my design thought process since I barely know any C and need to
think of how I plan to implement the API's and semantics.

This section will remain unchanged to reflect my thoughts over time and retain any ideas that I thought of and then gave up


- Return a logger object that is a struct defining the rules for logging, levels, files etc.
For this we need a struct `Logger` and a function that initializes a basic logger.

- I would like to have a builder pattern for the logger to make it feel good probably?

- Also a copy thing that can maybe take a tyepcasted logger struct and overwrite/create an existing logger with that???
