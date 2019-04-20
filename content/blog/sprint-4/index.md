---
title: Fourth Sprint  
date: "2019-04-20T12:00z"
description: Sprint 4 of Labs- User Testing and UX Planning
---

### Individual accomplishments this sprint
As an individual this week I pushed myself to continue finding bugs in the system and fixing them. This at times can be a challenge because you also need to catch the obscure ones and really try to break the app. Some of the challenges lied within once the bug was found, figuring out the root cause of the bug and then fixing it. However, the process of finding as many bugs as I could, prioritizing the bugs, and then going back and fixing them seemed to be a pretty good process. As I found the issues, I would open an issues ticket on Github and this worked well as a team. 

### Detailed Analysis of a Major Task

By far, the task that was most involved was the authentication piece bugs as I worked with a couple team members and we resolved them as a team. The issue we were experiencing was that if a user clicked sign in with Firebase, we don't always get the username and email from firebase because it's not always available such as Twitter, they require your app to have elevated privileges to get the email address, which we did not obtain for this project yet. So we created a form after sign in to capture the username and the preferred email of the user. However, the issue was if for some reason the user clicked sign in and did not complete the sign up, they were sort of in limbo between Firebase and our Prisma database. Firebase would think they are signed up, but in reality they were not signed up. We solved this by adding logic and queries to the Prisma database to ensure the user is indeed in the database using the UID from Firebase, or else if they weren't we would again attempt to obtain the information. So getting the databases talking to each other was a major task one one we completed successfully.

### Weekly Reflection

We had a good week as a team as I believe we made a lot of progress and caught up from where we were two weeks ago due to some bugs in Prisma were just causing us some setbacks. The goal over the last two weeks has been to finish up the functionality of the app and continue to work on the bugs in the app. Towards the end of the two weeks we started focusing more on UX and minor bug fixing and making sure the UX design is a design that a user would enjoy and understand perfectly what is going on with the app and know how to navigate the app. We are not quite done with styling and UX implementation, but this is a task we will continue working on through next week and by the end of next week we should be in a good spot to tackle the final bugs in the app and really polish it into a professional grade application. It's been a great two weeks and I am excited for the last sprint and the challenges that will come with it.