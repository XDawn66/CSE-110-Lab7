CSE 110 LAB 7
Teammate:
Zhenyu Jiang

1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

Within a Github action that runs whenever code is pushed would be the answer since we want everyone follow the same guideline as we test the code. As a result, set up the test to the Github action can automatically check our work as we update the branch so it won't cause a greater issue later.

2. Would you use an end to end test to check if a function is returning the correct output? (yes/no)
   No if only for simple task like return output, JUnit test will be better
