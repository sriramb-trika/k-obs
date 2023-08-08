##### General Code Quality
- Code is complex
- Code linting is inconsistent
- Code is not logically structured and organised
- Consistent formatting and style throughout the codebase is not followed
- Code comments are clear, concise and used when necessary
- code is free of dead code, commented-out sections, and unused imports
- The codebase is properly version controlled
##### Code Review Process
- Was the code reviewed by another developer or a peer? 
- Were code review comments addressed, and was feedback incorporated? Yes
- Are input parameters validated and sanitised to prevent SQL injection, XSS, and other vulnerabilities?
- Are sensitive data (passwords, tokens, keys) handled securely?
- Is proper authentication and authorisation implemented?
- Are sessions managed securely to prevent session fixation and session hijacking?
- Is error handling implemented securely, without revealing sensitive information to users?
- Is the application structured in a modular and maintainable way?
- Are dependencies between components minimised to reduce coupling?
- Is separation of concerns maintained (e.g., business logic, presentation, data access)?
- Are design patterns (e.g., MVC, DAO) used appropriately?
- Is the application prepared for potential future enhancements or features?
- Are shared resources protected against concurrent access?
- Are thread safety issues (race conditions, deadlocks) addressed?
- Are unit tests in place for critical components?
- Is there appropriate code coverage, especially for critical paths?
- Are integration tests or end-to-end tests implemented where necessary?
- Are there clear and up-to-date documentation, including README files, API documentation, and inline comments explaining complex logic?
- Is the architecture and high-level design documented?
- Are exceptions caught and handled properly?
- Is logging in place for exceptions and errors?
- Are configuration settings separated from the codebase?
- Are environment-specific configurations managed effectively?
- Is there a clear deployment process and documentation?
- Are external libraries used judiciously, and are they up to date?
- Are licenses for third-party libraries reviewed and adhered to?

The recommendation or the check the list is given in [[Code Quality Tools]] 