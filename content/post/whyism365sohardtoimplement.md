---
title: "Why is M365 so hard to implement the \"right way\" ?"
date: 2023-09-06T23:36:50+02:00
draft: false
---

**Today I stumbled across the following tweet:**

![SCREENSHOT](/img/tweet_m365.png)

In the last few years I have conducted many migration projects in a wide variety of environments, from small and medium-sized companies to enterprise environments with several thousand employees from on-premise to M365.
Rarely did I have the chance to start from scratch. Most of the time, there was already an existing structure on-premise, or only a part was already used in M365.

## What I have observed over the last few years :


For those who were already using M365, the following patterns occurred repeatedly :

- Often, only Exchange on-premise was migrated to Exchange Online to save costs. The rest was not used.

- M365 was only used to license the office package.

- Through COVID, these companies then often still used Teams, since it was already included in the license. Exactly these enterprises had then however quite a proliferation of Teams, channels and content, as the service was deployed \"on the fly\".
- SharePoint was used as cloud storage, but not introduced in a structured way.

- Users continue to work \"as in the old world\" / on-premise. Example: Files are sent back and forth umpteen times as attachments. 
- in SharePoint there are deep folder structures, often complete fileshares were packed into a single document library and then synchronized to all clients via OneDrive, so that users do not have to change their way of working.
- Because of the latter point, many users are dissatisfied, as the synchronization causes problems every now and then.

## What I often hear from users from such companies :

- *\"SharePoint is bad, I can't find anything again and everything was faster and easier on the old file server\"*
- *\"Why should I use Teams when I have an email distribution list ?\"*
- *\"I can also map our KPIs in Excel. My colleague has already built something there\"*
- *\"It's only the office package in the cloud anyway\"*
- *\"And why is that so expensive ?\"*

## What I often hear from decision makers from such companies :

- *\"It just had to be done quickly, so we rolled out teams.\"*
- *\"We lack the time and expertise to evaluate what else we can do\"*
- *\"Why do I need all this cloud stuff just for the office suite ?\"*
- *\"We have other software in place for each of our core processes that already does everything, do we need M365 ?\"*
- *\"Our Exchange is now running in the cloud. So we can continue to use it as a file repository without buying on-premise storage. Great success \"*

## What does this mean for the statement in the tweet ?

Looking at my observations and experiences over the last few years, he is right : M365 unfortunately often ends after the migration from Exchange on-premise.
Probably more often in small businesses than in enterprise environments, but still, at least from what I've experienced, relatively common.
Things are resolved via third-party tools, even though tools are already in place via M365. Users create compliance issues as they share files via arbitrary
file sharing portals with external parties just because they don't know they can already do that securely via their own on-board tools.

## What can be the reason for this ?

Again, opinions will probably vary widely, but I personally think it's because of these factors :

1. the customer is not sufficiently informed to know what options he has.
2. the IT system house providing support does not have the expertise to provide extensive advice here (probably more common in the small-business segment)
3. the customer is not ready or does not have the budget to fully utilize the service.
4. the introduction of the services was only considered from a technical point of view.

In my (humble) experience, it has often been the combination of all three factors when adopting such a construct. 
It has often been helpful to make a rudimentary demo of the most important services, so that the customer is aware of what is included in his license.

In my personal opinion, the most important factor is often :

**The migration or introduction of M365 is not a pure technology project, but the focus should be on the users.**


This also aligns with Microsoft's mission statement : 

*\"to empower every person and every organization on the planet to achieve more.\"*

And this is where the cat bites the tail again, as this means that BEFORE we launch services, we first need to understand their way of working to enable them to help us as consultants in the design so that we can provide the best possible solution for them.

I've had so many a-ha moments with users in meetings when I've teased simple services from M365 that they didn't know about before, but directly rated them as very useful and were grateful for the advice.

## Am I surprised ? 

No, because M365 is an ecosystem with enormously fast growth and frequent changes. Let's be honest, we work with it every day and our focus is on it. 
Nevertheless, it happens again and again that a familiar menu is now in a different admin center, or a service has been renamed (cough...Entra), or simply a function that has been used for a long time has been discontinued. 
Yes, it's good that the platform is constantly and rapidly evolving. 
This is the cloud as we love it, but it's already hard for me as a consultant to stay on the ball and I can understand that this is almost impossible for \"normal\" users.

## Ok, but what can I do ? 


Companies and especially users can be so different, but this is why I believe that a successful implementation or migration to M365 is based on (at least those) two things :

- Empowerment of users through training
- After implementation / migration, a continuous process should be established in which new or existing capabilities are regularly evaluated and integrated.

## Companies like to save on user training.

*\"Anyone can operate Office\"* is something we've probably all heard many times before....
The challenge here is to convince companies that this investment is worthwhile and that they can even use it to create a competitive advantage. 
In the course of introducing M365, I always try to work closely with the departments and to document their way of working in profiles.
Kind of like setting up personas in marketing, for example. This helps me find the best solution and often results in added value for the company as they otherwise rarely have time in their core business to look at their current processes. 
The process analysis in turn gives impetus to ideas for automation and development of PowerApps prototypes.

## What helps me with this ?


**There is an incredible number of good resources on the net and the following things have helped me :**

- Microsoft offered a \"Microsoft Adoption Specialist\" certification a few years ago in cooperation with edx.org. I have also taken this and I can highly recommend it to every consultant and IT manager, because it covers the most important aspect for me - the users.
The course provides ideas and strategies for dealing with users during the introduction and operation of M365.

[LINK](https://www.edx.org/learn/computer-programming/microsoft-microsoft-service-adoption-specialist-2)

- There is the look book from Microsoft. Here there are SharePoint sample pages that can be easily deployed in existing clients. Either to get started directly
or for demonstration purposes.

[LINK](https://lookbook.microsoft.com/)

- Microsoft Adoption. 
  Adoption is key and for that Microsoft provides a bunch of information here to help us stay on the ball and empower users. It´s a great resource for materials to support and empower our users.

[LINK](https://adoption.microsoft.com)

- Aaron Dinnage has created a great page with an overview of all licenses and available services. This makes it easy to find your way through the license jungle, and it is easy to check which services are still usable in existing licenses.

[LINK](https://m365maps.com/)

- The **awesome** PnP Community provides help, advice and samples for you to use in your projects.

[LINK](https://pnp.github.io/)


If I think of any other relevant links, I will add them here. Feel free to send me your favorites via Twitter or mail, so I can include them here. I´m also curious what you think about this topic. 


**And above all: Listen to your end users, just as well as to the stakeholders and project sponsors. In the end, they are the ones who know best how work is done and it´s not unusual that this is different from what you read in some SOP documents some manager gave to you.**

Thank you for reading this and have a great day

Michael