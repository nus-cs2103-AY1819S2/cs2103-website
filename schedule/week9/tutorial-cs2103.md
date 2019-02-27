**Questions to discuss during tutorial:**

Whole team: do this question together, using the whiteboard:

<div class="indented">
  <include src="../../book/modeling/modelingBehaviors/activityDiagrams/q-modelWorkflowOfBurgerShop.md" />
</div>
<br>

Divide these five questions among team members. Be prepared to answer questions allocated to you.

**Q1**
1. What is _unit/integration/system/acceptance_ testing?
1. How is each one done in AB4?
1. What’s the difference between _unit testing_ and _integration testing_?
1. What’s the difference between _system testing_ and _acceptance testing_?




**Q2**
1. What’s the difference between _validation_ and _verification_?<br>
   Acceptance tests are validation tests or verification tests?
1. Give an example of _static analysis_ being used in Intellij

**Q3**
1. Explain and justify: _testing should be efficient and effective_
1. Explain how _exploratory_ and _scripted_ testing is used in AB4/project
1. Give an example of a _negative_ test case in AB4/project
1. Explain _grey-box_ test case design

**Q4**
1. Explain: _Equivalence Partition_ improve E&E of testing
1. What are the EPs for the parameter `day` of this method
   ```java
   /**
    * Returns true if the three values represent a valid day
    */
   boolean isValidDay(int year, int month, int day){
   
   } 
   ```

**Q5**
1. Explain: _Boundary Value Analysis_ improves E&E of testing
1. What are the boundary values for the parameter `day` in the question above?
1. How can EP and BVA heuristics be used in AB4/project? Hint: See [[AB4 Learning Outcomes: LO-TestCaseDesignHeuristics]({{module_org}}/addressbook-level4/blob/master/docs/LearningOutcomes.adoc#apply-test-case-design-heuristics-code-lo-testcasedesignheuristics-code)]


**Q6**
<include src="../../book/combined/exercises/reviewCliAppCode.md" /><p/>