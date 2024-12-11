
# Domain Driven Design

A developer today needs o undestand what the domain of an application is, and how to express that correctly - using types or specs. And even more imprtantly he needs to understand that domain means types and pure functions, and everything with side effects is not domain. Yes, that includes the database. 



Book recommended: 

Videos to understand the 2 concepts:
- Domain modelling and DDD  https://www.youtube.com/watch?v=2JB1_e5wZmU
    * "Illigal state should not be representable" I am using types like childAge: Int. I guess - -77374 is a valid child age
- Domain architecture (think Hexagonal, Clean, Plugs/Adapters, Onion or PureCore&sideEffects on the edge) https://www.youtube.com/watch?v=P1vES9AgfC4
    * pure functions (domain)
    * functions with side effects (IO)
    * How should a feature look like (IO-domain-IO)
    * How do all these things get tested?