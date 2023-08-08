##### Performance
- JSP pages in OCP often incur runtime overhead due to the compilation of Java code into servlets.
- Such UI pages can consume more memory compared to other technologies due to the creation of multiple Java objects during execution.
-  The compilation process can slow down development and deployment.
##### Maintenance & Scalability 
- Mixing Java code with HTML can lead to complex and hard-to-maintain code.
- The pages often lack proper mechanisms for code reusability, leading to duplication of code.
- It might not be as scalable as other technologies for handling high user loads due to its potential memory and processing overhead.
##### Separation of Concerns
- JSP encourages mixing of presentation and business logic, violating the principle of separation of concerns
- Business logic mixed with presentation can make the codebase messy and less maintainable
- Tight coupling is identified between client layer JSP code and [[Application Layer]] java code
##### Limited Expressiveness
- For more complex applications, JSP might not offer the full expressive power that other modern web frameworks provide
- JSP might lack some modern features that newer web technologies and frameworks offer out of the box
##### Integration and Ecosystem
- **Limited Integration** - JSP might not integrate well with other frontend technologies and frameworks.
- The JSP ecosystem might be less active compared to other popular frontend technologies. Lots of legacy css and html code written
##### Debugging Complexity
Debugging issues in JSP pages can be challenging, especially when dealing with mixed Java and HTML code
##### Cross-Site Scripting (XSS)
If not properly sanitised, JSP pages can be vulnerable to XSS attacks due to the mixing of user input and HTML output.
##### Recommendation
Recommendation is to use react.js or next.js using [[Legacy modernisation]]