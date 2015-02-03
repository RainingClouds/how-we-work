RainingClouds Inc
# Arsenal

To make processes better, selecting better tools is of utmost importance. We have carefully evaluated different tools over the period of 3 years, to completed our suit of tools that we use for a project.

**This bit focuses on explaining the different tools we use during a project and how do we use them.
**

## Documentation
### API documentation
#### GitHub/BitBucket Wiki
We use WIKI provided by GitHub and BitBucket to maintain the documentation related with APIs in case of web services. We have found it easier for developers to create using markdown, and easier to maintain.
## Code Reviews
Code review is very very important inside RainingClouds. **Any code that goes into the master branch goes through at-least two different developers.**
### Asynchronous Reviews
Asynchronous reviews happens over every of the commit made by any developer. For this we follow **Pull request based model**. Anyone who has completed the development of any feature makes a pull request on the master branch, allocating a reviewer. As soon as the pull request is sent, the reviewer is notified about the pull request. Reviewer has to review the code and raise any of the issues that he has by EOD. Till then the developer can pick up the new feature and start with the development. **Each feature has a new branch**, so that nobody messes up with the code associated with one feature. And there are virtually no cases where more than one developer works on a particular story, and if there is any case where we require more than one developer then we split up the story so as to divide them between the two developers.
### Synchronous Reviews
This happens rarely, **when a developer is stuck or his last commit has a lot of issues. In this case two developer sit to develop / fix a piece of code on a single machine, so as to make sure the quality of the code.** Each of the synchronous review is counted inside the RainingClouds, and we make sure that the developers has the proper understanding of the project and the technology to avoid any kind of hindrance in the project development.
## Time logging
This is important in two ways, one obviously for invoicing but more than that to calculate the productivity of the developers. That's why we take time logging very seriously. We have an internal tool. called **"Tyme"** for measuring the time logs. 

This works in sprints of 2 hours. Once started you are supposed to continue it for approximately 2 hours. At the end of two hours, the tool shows a popup saying that your sprint ended, put the description of the work you have done and commit the code with its existing status. This comment is automatically pushed onto the internal slack channel. He can take a break or whatever after every sprint. This way we make sure that every developer spends the most productive and effective 2 hours on the project.




