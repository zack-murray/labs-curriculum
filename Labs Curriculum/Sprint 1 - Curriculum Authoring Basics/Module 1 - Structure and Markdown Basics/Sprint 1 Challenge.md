## Prompt 1 - Breaking down a release

**Describe your process of breaking your release into user stories.**

Our first release was shipping the entire judge facing side of the Hackathon Portal. In order to do this, we brainstormed the exact tasks that judges needed to do, and we came up with these three user stories:

- As a judge, I can login into the hackathon I am judging for.
- As a judge, I can view all the projects I need to score.
- As a judge, I can view the details of an individual project and score it.

We then validated these user stories with our stakeholder to make sure we were not missing any tasks. 

**Describe your process of breaking a user story into individual tasks.** 

I started with one user story:

- As a judge, I can view all the projects I need to score.

I'm a very visual person, so I decided to draw out a low-fidelity wireframe to see what this could look like.

- Here's the wireframe we came up with

After looking at this wireframe, we first brainstormed the data that we needed to store and came up with these tasks:

- [ ]  Map projects to judges in database
- [ ]  Map projects to their scores in database

Then, we looked into how we would get that data. We came up with this task:

- [ ]  Create an endpoint to retrieve projects and their scores given a judge ID

Finally, we focused on the frontend components and came up with these tasks:

- [ ]  Create and style project component
- [ ]  Create and style list of projects

**How long do you think the above user story will take to complete? Explain your reasoning.**

We estimated that this user story would take a week to complete. We have 6 developers on our team. We divided 3 people to focus on the frontend and 3 people on the backend. Since our database is already deployed, we just need to make schema changes and redeploy which should only take 1-2 days. Creating the endpoint should also only take a day. Since the frontend components are only displaying information, that should also only take a day. That shows a total of 3-4 days. I always like to leave at least an extra day for debugging.