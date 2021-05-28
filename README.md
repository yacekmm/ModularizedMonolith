# ModularizedMonolith

Materials from my presentation on modularizing a monolith

# Abstract

Implement the monolith - the one well modularized

How many times did you hear: `Modularize the monolith, instead of doing microservices`? And maybe you see the point, but the next day you sit in front of your IDE wondering... How to actually implement it?

The title sounds like it was presented in the previous era, isn't it? Now everyone is doing Serverless. Possibly microservices in bit older systems. Or maybe it is very urgent topic to talk about, as all three architectures find their fit into particular case. Particularly the modularized monoliths are important when facing a decision of distributing your system.

The presentation is full of content - the Case Study based on a product that started as a Monolith, to become a Modularized Monolith. Shows the process of codebase modularization, starting with basic repackaging, defining modules in code up until the presentation of the tool that guards the modules' border for us automatically - the ArchUnit. Because we surely want to avoid manual rules checking.

On a presentation I assume that module boundaries are already defined on a business level. The focus is on implementing and enforcing them in the code.
