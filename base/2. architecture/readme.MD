# Architecture

Big subject, but we'll delimit it to:

## Macro architecture

where you have a system composed of many different subsystems [Detailed in Distributed Systems](./distributed%20systems/transactional_writes.MD )

## Mini architecture

Delimit: How do you architect a single system that is the child of the macro architecture

- Clean 
- Hexagonal
- Plugs and adapters
- Side effects on the edges or Imperative Shell, Pure Core

Designing or architecting is the activity where you consiensly break down a bigger things, into carefully selected smaller pieces. If this division is well done, it will have great consequences. If not it will have disastrous ones, just like leaving it coupled

Kent Beck: Coupling is when you have A and B, and whenever you change A you have to change B as well. 

So our goal is to minimize the change we need to do in already existing code. By designing everything upront like in waterfall. Hell no! But we could always predict that external systems should be behind interfaces, so we could protect ourselves from the consequences of their changes or replacement.


