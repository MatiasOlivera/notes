are typical solutions to commonly occurring problems in software design. They are like pre-made blueprints that you can customize to solve a recurring design problem in your code.

## What does the pattern consist of?

Most patterns are described very formally so people can reproduce them in many contexts. Here are the sections that are usually present in a pattern description:

- **Intent** of the pattern briefly describes both the problem and the solution.
- **Motivation** further explains the problem and the solution the pattern makes possible.
- **Structure** of classes shows each part of the pattern and how they are related.
- **Code example** in one of the popular programming languages makes it easier to grasp the idea behind the pattern.

Some pattern catalogs list other useful details, such as applicability of the pattern, implementation steps and relations with other patterns.

- Book: Design Patterns: Elements of Reusable Object-Oriented Software

## Classification of patterns

Design patterns differ by their complexity, level of detail and scale of applicability to the entire system being designed. I like the analogy to road construction: you can make an intersection safer by either installing some traffic lights or building an entire multi-level interchange with underground passages for pedestrians.

The most basic and low-level patterns are often called _idioms_. They usually apply only to a single programming language.

The most universal and high-level patterns are _architectural patterns_. Developers can implement these patterns in virtually any language. Unlike other patterns, they can be used to design the architecture of an entire application.

In addition, all patterns can be categorized by their _intent_, or purpose. This book covers three main groups of patterns:

- **[[Creational patterns]]** provide object creation mechanisms that increase flexibility and reuse of existing code.
- **[[Structural patterns]]** explain how to assemble objects and classes into larger structures, while keeping these structures flexible and efficient.
- **[[Behavioral patterns]]** take care of effective communication and the assignment of responsibilities between objects.
