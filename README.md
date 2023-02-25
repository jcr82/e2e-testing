# Automation Testing

## Testing Foundations

### Testing Mindset
- Testing is a mindset before anything else.
- Developers need to think like QA professionals to write effective tests.
- Discussions about testing should involve engineers, QA, product owner, and UX teams.
- Even if QA is only doing manual testing, their input is valuable.
- If there is no dedicated QA team, the engineer team should discuss what kinds of tests are necessary.
- An effective way to approach testing is to start with the end goal and work backwards.
- For Agile, test cases can be captured in user stories as acceptance criteria.

### What to Test?
- Identifying what to test is a challenging task when learning to write tests for an existing application without any tests.
- Start by writing tests for the most "mission-critical" pieces of your application that cannot go down or break.
- Focus on testing user journeys, which are the essential paths that a user takes within the application.
- Testing user journeys also tests all layers of the tech stack and provides confidence that the application is behaving correctly.
- When implementing a new feature, start with the end goal in mind and break the feature down into small incremental steps, which can be translated into tests.
- Writing tests around any bug that appears in the application is highly recommended.
- Write a failing test around the bug before fixing it, and once fixed, the test should pass, verifying that the new code has eliminated the bug.

### Manual vs Automated Testing
- Manual testing involves a person interacting with an application
- Manual testing can be time-consuming and repetitive
- Continuous Integration (CI) and Continuous Deployment (CD) require automation to scale
- Automated testing is becoming the norm for most software engineering teams
- The "shift left" movement is pushing developers to become more involved in testing
- Test automation is integrated into the software development lifecycle from the beginning
- Teams can follow practices like Test Driven Development BDD
- Real World Testing with Cypress teaches how to write automated tests for both developers and QA professionals.
