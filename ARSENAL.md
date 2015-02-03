RainingClouds Inc
# Arsenal
To make processes better, selecting better tools is of utmost importance. We have carefully evaluated different tools over the period of 3 years, to completed our suit of tools that we use for a project.

**This bit focuses on explaining the different tools we use during a project and how do we use them.
**
## Project Management Tools
### Basecamp
Project management is mainly focused on the communication between the client and RainingClouds. So we have chosen the most generic tool called "Basecamp".

Basecamp is the place where all the asynchronous discussions will happen. So if anyone has to sync up with the latest development of the project, Basecamp will be the starting point of it.

Along with the normal discussions, we push out the weekly reviews of each project, that covers the overall progress made in that week, the problems we have faced, new things introduced and the stories that we are taking up for the next week. This will be created as a new discussion on Basecamp, and all the comments will be considered in amendment of the plan. The last comment will be the final plan if at all there are any changes in the plan.

#### For mobile projects

We use Basecamp to release mobile builds as well. Actually we have an internally developed tool (soon to be released in public) called **Distribit** which automatically posts new builds as soon as they are submitted to the tool by developer. 

All the exceptions that are happening are logged into the Distribit and all the developers are notified with that exception. 

##### Types of builds
###### Nightly builds
Nightly builds are the builds pushed at the end of feature implementation. These are mainly for testers. So no Basecamp messages will be pushed for these builds. But all the devices that have an installed version of the app will be notified using push notifications along with the description of the update.
###### Weekly builds
Weekly builds are the sprint release builds. These are stable builds and there will be a separate Basecamp message for each of the weekly builds. 
## Communication Tools
### Synchronous Communication
#### Slack
Slack is one of the most important tool that we use internally in the team as well as for communicating with the client in real-time. We usually have two different modes for each project, one channel for internal team, where we scold at each other if something is going wrong and one private group where we are neat and tidy, which is also participated by client.

**We use slack integrations extensively.** All of our tools like Trello, Pivotal, GitHub, Bitbucket, Distribit have ready slack integration. Any of the updates on any of these tools are pushed onto the private group. So that it becomes a central hub for all the real-time updates related to a project.
#### Google Hangouts
We **Google Hangouts** for daily or alternate day calls with the client. If we are working in different timezones then we decide a time that overlaps and is comfortable for both client as well as to us. We set up a calendar event associated with a Google Hangout link. 

### Asynchronous Communication
**We discourage emails for asynchronous communication**, as it really becomes difficult to point out some of the important decisions taken over emails. So once the project is kicked off, its a big NO for discussing anything about project on the emails.
#### Basecamp
As explained earlier along with project management, Basecamp becomes one of the important tool for all the asynchronous communication.
## Issue management
Issue management is kind of generic we feel. So we  split up the issue management into two things called Functional issue management and Code issue management. 
Functional issue management is more related to the issues in business logic of the application for example issues related application flow, payment, signup, login etc. 

Code issue management is more related to the issues in the code, for example application crashes, non fetal exceptions, time complexity, space complexity. 

**Why do we separate out these ?**

Functional issues does makes sense to everybody who is associated with the project. But coding issues are more of a developers thing. They are outcome of internal testing as well as code reviews. There style of description is different and hence they require different kinds of tools.

### Functional Issue management
#### Trello
**Trello** is one of the most favorite tool inside RainingClouds for functional issue management. **Minimal learning curve, easier to understand, real world feel** are few of the strengths of this tool. Unless client opts for more advanced tool like **Pivotal** we go with Trello for functional issue management.
#### Pivotal Tracker
**Pivotal Tracker** is much more advanced tool for Agile project management. We love Pivotal for cleaner UI, and agile methodology support. There is a small learning curve for starting to use Pivotal by client. 

If we are going with Pivotal, we take a hangout call with client for giving out a small talk on **"Introduction to Project Management with Pivotal"**. So that everybody is on the same page once the project kicks off.
### Coding Issue Management
#### GitHub Issues
We find **GitHub issues** apt for all the code related issue management. 

**Flow**
1. Either our monitoring tools, or code reviewer reports an issue. 
2. Developer works against that issue
3. Commits the code against the issue number, so that the commit gets attached with that issue.
4. Reviewer (same who has raised the issue, or someone else but not the coder) reviews that code and if he is satisfied closes the issue and code gets merged to the master branch.

## Code Repositories
### GitHub, BitBucket
We love **GitHub** for its intuitive and cleaner UI. Same is the case with **BitBucket**. We mainly go with GitHub unless client wants us to keep all repositories in BitBucket.
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
This is important in two ways, one obviously for invoicing but more than that to calculate the productivity of the developers. That's why we take time logging very seriously. We have an internal tool for measuring the time logs. 

This works in sprints of 2 hours. Once started you are supposed to continue it for approximately 2 hours. At the end of two hours, the tool shows a popup saying that your sprint ended, put the description of the work you have done and commit the code with its existing status. This comment is automatically pushed onto the internal slack channel. He can take a break or whatever after every sprint. This way we make sure that every developer spends the most productive and effective 2 hours on the project.




