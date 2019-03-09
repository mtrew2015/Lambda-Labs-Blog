---
title: Week 1 Of Labs
date: "2019-03-01T12:02z"
description: Sprint 1 Of Labs - Initiation and Adjustments.
---

The first two weeks of labs were indeed very productive, but it also did not come without challenges either. Week one we spent the first half the week working on our T.D.D document for which stack we wanted to use. We ended up deciding on Gatsby JS for the front-end paired with Apollo Client and GraphQL, and then we decided on Apollo-Yoga and Prisma on the back-end with a MongoDb database.

Some of our accomplishments included getting the front-end deployed, and as of this moment we are very close to getting the back end deployed, and that will likely be completed before the end of the day.

One of the tickets that I spent a considerable amount of time on was setting up the initial structure of GatsbyJS. We got many of the main components that would be re-used, and the views in place, and then we decided as a group that upon learning more of the limitations of Gatsby JS, that it wasn't our best choice. That is because we were creating more of a complex app than what Gatsby is really good for. While a complex app can be built on Gatsby JS, the main purpose of Gatsby is a static page generator for content pages. Gatsby assumes your creating pages and doesn't give you many options for dynamically generating routes. When you try to break the page model, Gatsby can be quite limiting. 

We transferred all of the work that was created on Gatsby over to a vanilla create-react-app setup. Fortunately, thanks to forward thinking and planning we were able to change course from Gatsby JS over to a more standard React setup to avoid losing any work as Gatsby uses the same files as React in most-part.

When working on the TDD, much research needed to be done to find competitors, and see how they were doing things and then finding ways to improve based upon that. I looked at Yelp as a competitor because it has many of the same review features as ours will have, except they review local businesses and rate-my-diy is all about rating someones home improvement project and how they completed it. Taking note of how some of their components were shaped, I could draw a map of how the components would be connected within our application, and what tools we would need to achieve this goal. One thing we wanted to focus on was good usability, so we looked at the design documents specified, and tried to find a good balance so that the UX experience would be a positive one. 

Overall, it was a very successful two weeks as I believe we got a lot accomplished, made good decisions and avoided future roadblocks. Going forward, we will work on putting more of the pieces of the puzzle together in the next two weeks.
