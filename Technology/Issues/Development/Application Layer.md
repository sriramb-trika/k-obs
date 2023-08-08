###### Complexity
- Setting up and configuring OCP backend code is complex and time-consuming, especially for beginners.
- OCP involves multiple XML configuration files, which is difficult to manage as the application grows.
##### Performance
- OCP consumes more memory and processing power due to the overhead introduced by the various layers and abstractions.
- Such complexity can contribute to increased response times, impacting the overall performance of the application.
##### Maintenance and Updates
- Keeping up with different versions, updates and ensuring compatibility between different components and libraries in OCP can be challenging.
- It is difficult to maintain and modernize with latest plugin and tools.
##### Performance Tuning Complexity
- Fine-Tuning Optimising the performance of OCP require deep knowledge of the underlying technologies, making performance tuning complex
- The [[Code Quality]] is important, as it impacts the overall software quality.
##### Limited Flexibility
- Application Layer has to rely on the [[Data Layer]] and when a new DB has to be replaced, it requires lot of code rewrite which is impossible
- OCP is having  [[XML Dependency]] everywhere where the configuration is tedious to parse the data and DAO objects
- Being monolithic application, the core implementations cannot be exposed as service end points. The current code is confined to work only with in the application
##### Other Concerns
- The lack of [[Automated Unit Testing]] leads to more errors and repeated test cycles from the QA team
- The Project Object Model (pom.xml) dependencies are using the required versions of the dependencies or running old dependencies
- One of the dependencies identified is maven-surefire-plugin that is using 2.19.1 version where the latest is 3.1.2
- The authentication process uses a simple credential based authentication where the modern  [[Authentication]] mechanisms are advanced