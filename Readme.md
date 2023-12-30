# Microservices Patterns Book:
* monolithic hell
* Shantytowns --> big ball of mud
* Adapters invoke cloud services, inbound adapters, outbound adapters
* Hexagonal architecture is a pattern that uses the mechanism of ports and adapters to achieve separation of concerns and isolate external systems and other external code such as user interfaces and databases from the core application.
* overwhelming complexity
* edit-build-run-test loop
* (SaaS) applications is continuous deployment
* Amazon.com deployed a change into production every 11.6 seconds
* squads and uses two-week sprints
* build is frequently in an unreleasable state lengthy painful merges
* works on a particular functional area
* COMPLEXITY INTIMIDATES DEVELOPERS
* Continuous Integration (CI) server must run the
entire test suite
* Scaling is difficult: application modules have conflicting resource requirements
* fault isolation, because all modules are running within the same process
* Architecture matters to velocity of software delivery: maintainability, extensibility,
and testability
* microservice architecture as a service-oriented architecture composed of loosely coupled elements that have bounded contexts
* X-axis horizontal duplication, Y-axis functional decomposition,  Z-axis data partitioning
* Each instance is responsible for a subset of the users.
* FUNCTIONALLY DECOMPOSES AN APPLICATION INTO SERVICES
* service has a focused, cohesive set of responsibilities
* The microservice architecture uses services as the unit of modularity
* services are loosely coupled and communicate only via APIs having own db
* one service will
never be blocked because another service holds a database lock.
* multiple instances of each service.
* The API Gateway routes
requests from the mobile
applications to services.
* microservices architecture is not service oriented architecture
* Dumb pipes, such as a message
broker, or direct service-to-service
communication, using lightweight
protocols such as REST or gRPC
* Data model and database per service
* Smaller service
*  service is usually considered to have its own
domain model.
a SOA application usually consists of a few
large services, whereas a microservices-based application typically consists of dozens or
hundreds of smaller services. 
* better fault isolation in MS
CONTINUOUS DELIVERY AND DEPLOYMENT OF LARGE, COMPLEX APPLICATIONS Devops:
  * testability required by continuous delivery/deployment
  * deployability required by continuous delivery
  * enables development teams to be autonomous and loosely coupled
* quikly to market, reliability and Employee staisfaction
* EACH SERVICE IS SMALL AND EASILY MAINTAINED
* SERVICES ARE INDEPENDENTLY SCALABLE -->CPU-intensive vs. memory-intensive
* Drawbacks:
  * Finding the right set of services is challenging
  * Distributed systems are complex
  * careful coordination between services
  * FINDING THE RIGHT SERVICES IS                       
*  CHALLENGING-->distributed monolith
   * DISTRIBUTED SYSTEMS ARE COMPLEX --> challenge to implement transactions 
   *  
* Pattern: Client-side service discovery
* communicate with one another using asynchronous messaging
* Request/response
* async Request/response

