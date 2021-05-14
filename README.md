# reimagined-design-patterns

Give a summary description of Four design patterns that you choose from the following design patterns: **Adapter,  Builder, Composite, Decorator, Observer, Interpreter, State, Mediator, Memento, Prototype, Proxy**. In your summaries say:

- what kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example
- how the pattern works, what the basic idea of the pattern is
- what the main advantage and what the the main disadvantage is of using this pattern
- Write a short summary for each of the four patterns, about half a page for each pattern (rather less than more). 

> Do not add diagrams, and do not try to give a complete description of the patterns as found in the books. Rather think of how you would explain the essential ideas of these patterns in a few sentences to a colleague while drinking coffee.

**Adapter**

_Summary : _

A structural design pattern type that acts as a bridge  to  collaborate incompatible(different type ) interfaces

_A real world example :_

In real time ,we can relate many examples .
  -> How a micro USB charger can be used in Type c port Mobile ?
           Here Micro USB to Type C converter acts a Adaptor  

   -> How a person who knows only German  can communicate to English speaking guy ?
           Here a translator acts as an Adaptor  

_Where it can be applied ? _

  In case of existing class needs to be used with new class which has  different interface then adaptor class helps here 

_Advantages :_

	1. Reusability  of existing code/data
  2. Adaptability as per client need. Adaptor class can be modified  without modifying existing code 

_Drawbacks :_
  
  1. Increase in code size and complexity 
  2. Many adaptions in Adaptor class  might required to meet requirement

