# Upskilling 

## Why?

The cost of software is aprox the cost of change. (Kent Beck https://medium.com/@kentbeck_7670/monolith-services-theory-practice-617e4546a879). 

We need to minimize the cost of software, so what should we do? 

"Software maintainability is the most important metric. Developers need to maintain the code
Software maintenance accounts for more than 90% of a software product’s lifecycle costs. Developers spend 70% of their time on understanding existing code." https://codescene.com/product/code-health#:~:text=Developers%20need%20to%20maintain%20the,time%20on%20understanding%20existing%20code.

## What? or what each developer needs to know

## Stategy

Simplicity (the opposite of complexity https://www.youtube.com/watch?v=SxdOUGdseq4 Ruch Hickey). We spent over 90% of our time bavigating through code, so simpler code (simple as having less options) will be easier to navigate, understand, debug & fix, change, extend. 

### Base knowledge

#### 1. Domain Driven Design

A developer today needs o undestand what the domain of an application is, and how to express that correctly - using types or specs. And even more imprtantly he needs to understand that domain means types and pure functions, and everything with side effects is not domain. Yes, that includes the database. 

[See more here](base/1.%20domain_driven_design/readme.MD)


#### 2. Architecture

Kent Beck: Coupling is when you have A and B, and whenever you change A you have to change B as well. 

So how can we design/architect systems, where we can most of the times change A without changing B.

[See more here](base/2.%20architecture/readme.MD)


#### 3. Test Driven Development

I am implementing a new feature. I have an idea. I write it down in the code. I run the test suite and break a few tests. Instant feedback. This now presents to me 2 possibilities: should I continue and change and repair the tests and add the ones missing or revert. This instant feedback can tell you *what the cost of a change is*. But how can we build such a system?

[See more here](base/3.%20test_driven_development/readme.MD)

### Extra knowledge

@todo
