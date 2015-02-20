# Team Allocation

This is initiated once we are done with finalizing the technology stack that we are going to use for the project. 

##Team structure 
```
                +--------+ 
    +---------->| Client |<-------------+
    |           +--------+              |
    |                                   |
    |                                   |
    V                                   V
+---+-----------+                  +----+-------+
| Project Owner |<---------------->| Technology |
+---------------+                  | Manager    |
       ^                           +------------+
       |                                ^
       |          +------------+        |  +---------+
       |          | Developers |<-------+->| Testers |
       |          |  (1..N)    |           | (1..N)  |
       |          +------------+           +---------+
       |                                        ^
       +----------------------------------------+
```
### Project Owner

Project owner is the main communication point. He will be in constant touch with client, and discussing about the project status, issues, next iteration planning.

#### Responsibilities

1. Understanding the business of the client.
2. Understanding the use case of the project.
3. Understanding the customers of the project and studying the competition.
4. Deciding the features in the current iteration along with the client.
5. Creating backlog (list of stories) for the finalized iteration.
6. Getting approval on the current sprint plan from client.
2. Daily communication with the client about progress of the project
2. Daily communication with the Technology Manager about the issues, bottlenecks, dependencies.
3. Resolving conflicts, if there are any, about the business needs and the technological capability.
4. Resolving conflicts, if there are any, about the time estimations related to any part of the project.
5. Helping Project Owners and Developers about the confusions related with business logic of the project. And also getting a word from the client if he is not sure about something.
5. Communicating changes from client to the Technology Manager till it gets approved for development by the client and Technology manager.
6. Getting approval from client on the delivery of the sprint.
7. Approving test cases created by tester and getting it approved from client.

### Technology Manager

Technology manager takes up the entire technology ownership starting from the IDEs that developers use for development, the small libraries that are being used to major decisions like using Heroku vs AWS, using Scala/Java1.8/Golang. He plays the key role in the initial iterations of the project where everything is heating up. 

As he has the key role to play for the development, he usually communicates more with Project Owner about the issues, changes in the technology stack. Project owner is the one who has the responsibility of communicating this to the client. If at all, there are any conflicts then Client, Project Owner and Technology owner hop on a call and resolve it. All these things are expected to be documented and pushed onto the Basecamp as either a page, or a discussion.

Technology manager rarely codes in the project. He mainly act as a reviewer and maintains the quality of the product.

#### Responsibilities

1. Technology ownership
2. Communicating the technical issues related with implementation of business logic to Project Owner.
3. Estimating each story in the backlog and prioritizing the cards with the help of Client and Project Owner.
4. Finalizing sprint plans with Project owner. And also helping him to get approval.
5. Making sure about the progress of the project and updating the project owner daily about it.
6. Resolving any conflicts in the developers related to the business logic or implementation.
7. Code reviews.
8. He daily checks onto the commits, code quality, tester outputs.
9. Approving test cases created by testers.

### Developers

Developers are the key factor of this entire team. And thats why we have kept the least amount of overhead (or manual processes) for the developer. Any of the bottleneck for developers is resolved on high priority. Be it related with coding or business logic or exceptions. 

#### Responsibilities
1. Implementation is the main responsibility
2. Maintaining the speed of the development, reporting back to the Technology manager if there are any discrepancies in the estimation and actual case of any form.
3. Pushing pull request at the end of every feature implementation.
4. Updating the issue management tools.
5. Communicating with testers about the nightly or feature releases.
6. Writing unit tests, covering at least 90% the code.  Writing functional and instrumentation test cases whenever possible.

### Testers 

Testers are as important as developers for any project. They have to understand the technology as well as the business logic of the application. Thats why they are in constant touch with Developers, Technology owner and Project owner to understand all the aspects of the project.

#### Responsibilities
1. Creating test cases for project and getting it approved.
2. Doing the functional testing of the nightly releases, feature releases and sprint releases and raising the issues on functional issue management tool.
3. For web applications, doing the load testing, browser compatibility testing, writing selenium scripts for automated testing and reviewing the monitoring tools like New Relic, BugSnag to find out code related bugs.
4. For mobile applications, testing on different form factors, testing on different devices, orientation related testing, and then reviewing logs for Garbage collector related issues. Also doing instrumentation test for finding out drawing, CPU and memory related issues.

