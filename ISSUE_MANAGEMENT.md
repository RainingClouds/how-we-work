# Issue Management

Issue management is kind of generic we feel. So we  split up the issue management into two things called Functional issue management and Code issue management. 
Functional issue management is more related to the issues in business logic of the application for example issues related application flow, payment, signup, login etc. 

Code issue management is more related to the issues in the code, for example application crashes, non fetal exceptions, time complexity, space complexity. 

**Why do we separate out these ?**

Functional issues does makes sense to everybody who is associated with the project. But coding issues are more of a developers thing. They are outcome of internal testing as well as code reviews. There style of description is different and hence they require different kinds of tools.

## Functional Issue management
### Trello
**Trello** is one of the most favorite tool inside RainingClouds for functional issue management. **Minimal learning curve, easier to understand, real world feel** are few of the strengths of this tool. Unless client opts for more advanced tool like **Pivotal** we go with Trello for functional issue management.
### Pivotal Tracker
**Pivotal Tracker** is much more advanced tool for Agile project management. We love Pivotal for cleaner UI, and agile methodology support. There is a small learning curve for starting to use Pivotal by client. 

If we are going with Pivotal, we take a hangout call with client for giving out a small talk on **"Introduction to Project Management with Pivotal"**. So that everybody is on the same page once the project kicks off.
## Coding Issue Management
### GitHub Issues
We find **GitHub issues** apt for all the code related issue management. 

**Flow**
1. Either our monitoring tools, or code reviewer reports an issue. 
2. Developer works against that issue
3. Commits the code against the issue number, so that the commit gets attached with that issue.
4. Reviewer (same who has raised the issue, or someone else but not the coder) reviews that code and if he is satisfied closes the issue and code gets merged to the master branch.