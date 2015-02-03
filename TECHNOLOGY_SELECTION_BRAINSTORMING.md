# Technology Selection Brainstorming
Usually clients come up with a certain set of technologies in their mind. But sometimes they are really not fit for the product that we are developing. So we usually come up with an altered set of tools and technologies that we think are perfect for the product and obviously with detailed reasoning of the choices. **We aim to finish up this phase in a week or maximum 2 weeks.** 

***
**Case study : Kabzz**

For example, Kabzz, one of the product that we have developed. Client had LAMP stack in mind, but we came with the most recent and powerful stack. Kabzz team was amazingly responsive and agreed onto the stack we suggested. And we ended up using **GoLang at the web end along with RabbitMq, PostgresSQL, Redis**. 
***

**We choose our technology stack very carefully,But there are some cases where one of our decision goes wrong.** In that case we reach out to the client, explain the issues that we are facing, give out the alternative solutions and start with the integration. 

***
**Case study : Kabzz**

We were relying on GCM(Google Cloud Messaging) messages for one of the crucial notifications. Though we had speculated that this could be one of the problem, we went ahead with that (as we were developing an MVP for the client). But as soon as we moved onto the first release cycle, we switched over RabbitMQ to replace GCM.  
***