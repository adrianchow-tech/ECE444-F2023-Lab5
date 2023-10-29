# ECE444-F2023-Lab5
Test function written for group project: https://github.com/ECE444-2023Fall/project-1-web-application-design-group20-commitcartel/blob/main/tests/app_test.py#L14-L26

**Pros of TDD**
1. TDD could allow for improved code quality. This is because TDD encourages developers to think about what they want the test results to be and how they can write their code to get the desired result. Additionally, because the developers are writing their tests first, they are forced to think about the different interfaces, expected behaviors, and the design of their code. This could lead to cleaner code in general
2. TDD could serve as a good tool for pseudo-documentation. This is because anyone who looks at the test cases are able to understand the system's behavior and requirements
3. TDD helps with catching bugs early in the development process so that any issues that could arise early on are addressed early on
4. TDD also helps with regression testing as we would know if new code breaks existing functionality after running the test suite
5. TDD allows for developers to have confidence when refactoring code. This is because they will know that the core functionliaty will not be broken after testing out their changes

**Cons of TDD**
1. TDD could be time consuming as it could slow down initial code development because the team will be writing unit tests instead.
2. Overtesting could occur since there is an over-arching focus on ensuring that the tests pass. This could lead to a messy codebase as there could be an excessive number of tests
3. Test cases need to be updated as the code base evolves which could be very labor intensive, especially if code refactoring is happening
4. TDD could induce a false sense of security as passing the tests might not translate over to the system working as intended
