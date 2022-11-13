# ECE444-F2022-Lab6

This repo is replay 
the following example : https://github.com/mjhea0/flaskr-tdd 


## Pros and Cons of TDD
### Pros
- easy to maintain: when other developers build on the original code, the testers can make sure original functions are not impacted
- easy to test: unit test can help developers find the problems for single sections. There is no need to go through all the codes
- clear structure: the tests are separated into different sections, so developers will follow similar format when designing the codes. With separate sections, the code structure will be more clear

### Cons
- tests need to follow requirements: if the requirements changed or code structure changed, all the original test cases need to be reimplemented
- slow the process: for every single function written, there may be much more test cases to write and it takes longer time for a simple function implementation
- every team member needs to maintain their own tests: if one person leaves the team, it's hard to update the test cases because the writer knows which part of functionality is tested
