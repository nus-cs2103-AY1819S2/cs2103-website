**Questions to discuss during tutorial:**

Whole team: do this question together, using the whiteboard:

<div class="indented">
  <include src="../../book/modeling/modelingStructures/objectOrientedDomainModels/q-courseDomainModel.md" />
</div>
<br>

<div class="indented">
  <include src="../../book/modeling/modelingBehaviors/activityDiagrams/q-modelWorkflowOfBurgerShop.md" />
</div>
<br>


Divide these questions among team members and get ready to answer them.

**Q1**
1. How does an _OO Domain Model_ differ from a class diagram?
1. What's the relationship between an OODM and a class diagram for a software? %%e.g., exactly the same?, one is a sub-set of the other?%%
1. Which diagram can we use to show ~~class~~object structures in a problem domain?


**Q2**
1. What’s a _design pattern_?
1. When do you use the _Singleton_ pattern, _Facade_ pattern, _Command_ pattern?
1. Which of the three patterns are used in AB4? Hint: See [[AB4 Learning Outcomes: LO-DesignPatterns]({{module_org}}/addressbook-level4/blob/master/docs/LearningOutcomes.adoc#apply-design-patterns-code-lo-designpatterns-code)]
1. When do you use _MVC_ pattern? Do we have MVC in AB4?
1. When do you use the _Observer_ pattern? Do we have the Observer pattern in AB4?


**Q3**
1. What is _Liskov Substitution Principle_?<br>
   Give an example from the project where LSP is followed and explain how to change the code to break LSP.


**Q4**
1. Explain how _Law of Demeter_ affects coupling<br>
   a. Add a line to this code that violates LoD
   ```java
   void foo(P p){
       //...
   }
   ```
1. Give an example in the project code that violates the _Law of Demeter_.
1. What’s the problem with the architecture diagram on the right?<br>
   <img src="{{baseUrl}}/book/architecture/architectureDiagrams/drawing/images/tip.png" height="190" /><br>
