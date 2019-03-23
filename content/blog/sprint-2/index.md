---
title: Second Sprint 
date: "2019-03-23T13:01z"
description: Sprint 2 Of Labs - Integration and Connections.
---

### Individual Accomplishments this Sprint: 
This Sprint I spent the majority of my time working on the Authentication portion and this was a task that is in no way easy to conquer. One of the biggest hurdles ad had to overcome was trying to find a format and library that fit the scope of your project and had a lot of flexibility for developers. A lot of the process was just researching and finding the solution that worked the best. We ended up settling on Firebase from Google for Authentication and using Twitter, Google, Github, and the standard email that comes with Firebase for an option to sign up. I have also spent the last couple days working on the email API, which is still a work in progress but we are using Sendgrid or Nodemailer to complete this. We had some changes to our back-end as we were modifying it to accept the use of custom mutations, but now that the maintenance on that is complete, we can finish the email functions.

### Working on Firebase 
The firebase was the main ticket that I had pulled for this sprint. While it could have been broken down into many smaller tickets, however we did not realize how extensive authentication was going to be until we actually started working on it. In hindsight, I would have definitely broken this down into smaller tasks since the end product of this ticket was many hundred lines of code, and more than 10 files or so that needed to be completed. 

It was however, a very rewarding experience gaining some exposure to Google Firebase as it's a very nice platform to use. It comes with the security from Google, meaning that you don't have to worry about storing emails and passwords in a separate database. It's also nice since they work directly with oAuth providers and make the process of setting them up pretty decent as well. We also had to create the Context API for Firebase so that it could be used throughout the React application without needing to pass props to every component it was needed at. 

### Weekly Reflection
Forming a team and working with new members comes with its own set of challenges, but none that can't be overcome with a little bit of conversation and arriving at the best possible solution. There are bound to be some differences in opinion, but I think the biggest thing is to listen to everyone's viewpoint and arrive at the best decision that will benefit the team as a whole. Respecting someones viewpoint, even though they may not share the same opinion is best policy. Overall, we have had very few disagreements as a team and I believe they were resolved efficiently. It's been a fun first two sprints and I look forward to the next sprint.