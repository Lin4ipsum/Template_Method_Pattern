# Template Method Pattern

#### to vary an algo, code the part that doesn't change as the base class (parent class) and encapsulate the variable parts in methods that are defined by subclasses

#### premise of this pattern is to separate things that change from things that stay the same. The child classes contain the code that changes and the parent class contains the code that doesn't change. 

#### A problem with this pattern is that it relies on inheritance. Subclasses will alway be tangled up with their superclass. 

#### In the Template Method pattern, the abstract base class controls the higher-level processing through the template method; the subclasses fill in the details.

#### In subclasses, the inherrited methods from the superclass can be overridden to do something different or they can accept the default implementation. Sometimes the parent class will have an empty method name to let the subclass know about them. 