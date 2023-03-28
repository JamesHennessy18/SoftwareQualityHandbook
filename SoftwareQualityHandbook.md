**Software Quality Handbook**

**Software Quality**
Software quality refers to the overall characteristics of developed software that make it fit for purpose, such as reliability,flexibility, usability, efficiency, testability, and protability. Software quality is determined by how well the software meets the requirements and needs of the users, and how well it performs in the intended environment. The software must meet customer or user needs and expectations.

![Software Quality](pics/SoftwareQuality.webp)

**What is Software Quality Assurance**

Software quality assurance is the process that ensures that software products and services meet the required quality standards and customer expectations. Software quality is not just about lack of defects but also the presence of value. The aim of SQA is to improve the software development process to ensure that the software that is being developed meets the required quality standard. Rather than fixing problems when they occur, we aim to prevent theses problems happening in the development process.

**Importance of Software Quality Assurance**

- It is important to ensure customer satisfaction with the end product in the hopes that customers will continue to use the software and also recommend it to others.
- Preventing defects early in the development process reduces the cost of fixing them later. With solid SQA, you can catch these defects early before they become larger issues.
- Productivity is majorly improved when these issues are caught early, it can reduce the time spent and effort needed to fix the issues further down the lin.
- Reducing risk is a major benefit to high standard software quality. Bad software quality can lead to security breaches and loss in data. SQA helps prevent these risks.

ISO/IEC 25010 is a standard that provides a framework for software quality requirements and evaluation. It is attempt to define quality that provides guidelines for software development.

Take a look: 

![ISO/IEC 25010](pics/SoftwareQualityProduct.png)

**Our Goals**
 The goal of the handbook is to establish best practices for the team to follow and create a more consistent approach to software development.
 This handbook will cover the following three topics:

 1. Task Estimation In Scrum
 2. Code Reviews
 3. Dev Ops

 When in doubt of anything related to Software Quality, we advise Software Engineers to refer to our Software Quality Handbook.

 Lets Begin:

**Task Estimation In Scrum**

Firstly, lets talk about what task estimation in scrum actually is. Task estimation in scrum is an essential part of the planning process. Scrum is one of the most popular Agile Methodologies and planning and estimating the time these tasks will take to complete in the upcoming sprint is a key element to have quality software. Task estimation involves the development team coming together to have a scrum planning meeting which is a scheduled meeting where the team will come together to estimate the amount of time it will take to complete each item in the product backlog. The team will generally estimate time for each item in the backlog using story points which are based on the complexity, effort and any other factor that might be involved. 

I found a great article that articulates the challenges of task estimation but also the different techniques and strategies for successfull task estimation.

Challenges of Task estimation in Scrum: 

- Uncertainty
- Complexity
- Lack of information/Experience
- Time pressure
- Cognitive biases

Techniques:
 
 1. Planning Poker
 2. Affinity Estimation
 3. Triangulation
 4. Bottom-Up Estimation
 5. Wideband Delphi

 These are all very well know techniques. To read more on these techniques and challenges, take a look at the below article: 
 [Tips for Effective Task Estimation in Scrum Planning Meetings](https://liuhongbo.medium.com/tips-for-effective-task-estimation-in-scrum-planning-meetings-c7a6af2c4966)

 As listed in the above article, cognitive biases is a challenge related to task estimation. What is this? Cognitive Biases are mental shortcuts that influence are thinking and decision making. People tend to overestimate their abilities and underestimate the time required to complete a task. In an blog post by David Tzemach, he mentions ego being a big challenge with time estimation in scrum. He mentions his own experience within a scrum team and how you can come across "experts" who thinks they know best voiding others opinion. We do not want this. 

 Key takeaways:
 - Every team members opinion matters. 
 - Do not over estimate your abilities, give yourself some breathing room.
 - Do not underestimate the tasks at hand
 - Leave the ego at home! 

 [Challenges with Estimations in Agile projects | David Tzemach](https://www.agilequalitymadeeasy.com/post/challenges-with-estimations-in-agile-projects-david-tzemach)

 Following the above takeaways, I have found a very interesting forum that I would like to share. The question is raised that in this persons personal experience, her team only estimates stories, not estimating tasks and bugs, is this the best practice?. The reason i mention this forum is because of a specific reply from a Thomas Owens. He says "The only important opinion is that of the team" and that "Estimates aren't for use by stakeholders outside of the team". What I have taken from this is that if you think your team should/shouldnt be estimating certain factors like bugs/smaller tasks that dont effect the customer. Raise this in the scrum meeting. Task estimation is very situational. As you can see their is a common theme in this section of the handbook. "Every team members opinion matters". To ensure the highest level of software quality, factors even as small as adding in extra time in the estimation for bugs can go along way for successful, on time delivery of the software.

 [To read more on this forum and see other responses to the question raised](https://www.scrum.org/forum/scrum-forum/58252/should-we-estimate-our-tasks)

 Is It Worth Estimating the Tasks of Scrum Teams in Hours?

 As mentioned before, task estimation in scrum is generally measured in Story points. There are many benefits to this such as the evaluation being relative, taking into account risks and uncertainties in the requirements, the whole team takes part and the teams average speed is taken into account. But what about measuring these story points in man hours? 

 According to Artem Slepets who is a project manager at Mad Devs, there are many pros and cons to Task estimation in hours and he gives a great overview of this planning technique which allows for his team to deliver a quality software product. Here are the key points i took from this article: 

- Task estimation in hours is most beneficial when working in short sprints of 1-2 weeks where there is no need to use techniques such as the above mentioned "planning poker"
- Task estimation in hours rather than story points enables the team to more accurately set a deadline for the project completion before it even begins. 
- In Artems experience it is more effective to plan short projects of only 2-3 months. Reasoning: "If we're going to estimate tasks in story points at the beginning, we won't know how many of   them the team will be able to close in one sprint, so after doing 1-2 iterations, the estimate will have to be adjusted.

The reason this article is mentioned as it essential to get the timing of a project as accurate as possible. By estimating tasks correctly, the team can ensure that they have enough time and resources to complete each task to a high standard of quality. Use this article to fall back on when initially deciding how you are going to estimate tasks in the planning process. 

[Is It Worth Estimating the Tasks of Scrum Teams in Hours?](https://maddevs.io/blog/task-estimation-in-hours-for-scrum-teams/)

On the other hand, some prefer estimating in story points. Mike McEwen says he prefers story points to hours, "Story points are approximate and relative estimates that a team makes together about the effort required to complete a story." He then goes into detail about the best practices for Estimating Agile Projects With Story Points.

- Use non-consecutive point values
- Stabilize the team
- Get inputs from everyone
- Make informed estimates
- Make informed estimates

To read more on these practices, check out this article. 
[6 Best Practices for Estimating Agile Projects With Story Points](https://www.linkedin.com/pulse/6-best-practices-estimating-agile-projects-story-points-mike-mcewen/)

![Check out this diagram](pics/hoursVSpoints.gif)

The reason I mention this article from Mike and also to conclude this section of the handbook, Is that Task estimation in scrum should not be a set and stone system you follow. Task estimation will differ depending on the project and also the team member and how they work best. For our team to have success and improve in the future on our task estimation, Refer to this section of our handbook.

