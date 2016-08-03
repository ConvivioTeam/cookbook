# The Sprint Cycle

The sprint a is two week period of activity by the delivery team to work on and deliver the stories taken into the sprint. It’s the job of the Product Owner and Scrummaster to keep noise and interruptions away from the delivery team during this time to allow them to focus on the priority stories.

During the sprint members of the delivery team will select stories from the sprint backlog. As stories are worked on their progress is recorded in our delivery tool (usually Rally or Pivotal or something similar) so that we can clearly report whether or not the sprint is on target.

## Daily Standup

Each day the team, together with the Product Owner will hold a daily standup. This is a meeting, time boxed to 15 minutes. During this short meeting each of the delivery team will briefly discuss what they’ve done since the last standup, what they have planned for today and they’ll raise any blockers or risks that need to be addresses. This meeting keeps the Product Owner up to date and it provides a natural break to raise any concerns or risks that might be affecting the sprint. The sooner we discuss an issue the sooner we can resolve it and the less chance it has to grow into something more difficult to tame.

At the end of the standup we’ll hold a separate meeting for any issues that need to be resolved and only involve those who need to be involved. Let people focus on delivering the sprint whenever possible.

## Driving Quality

Before a story can be marked as complete it has to go through various tests and checks to make sure that it meets certain criteria:

* Has the story been completed in the way expected by the Product Owner?
* Is it free from bugs?
* Does it function and display correctly on the array of desktop and mobile platforms and browsers?
* Has the code been well written and does it meet our standards and any other standards agreed?

To drive this quality we use a series of tools and people to carry out our QA:

* All code is peer reviewed to make sure it meets the required quality and security standards
* The client provides UAT to test the stories to make sure that the functionality, content and display is correct (cross browser testing)
* The “definition of done” is a list of requirements that all stories must meet
* Continuous integration requires developers to check code in regularly for automated testing, early detection of problems and regression testing
* Usability testing

If a user story doesn’t pass the tests then the failure is recorded and we pass that back to the delivery team to resolve and it goes back into the develop-test cycle until we’re happy that it can be deployed.

## Over or Under Estimating

There will be occasions when not all stories are completed within the sprint or the stories are completed early. The planning session provides estimates and not guarantees of what will be delivered. When the estimates are not accurate it’s important to take the reasons for this and discuss them in the sprint review and the sprint retrospectives so that we can learn and improve the next time. It’s also important to discuss this openly with the Product Owner so they understand the reasons for the inaccuracy because this promotes openness and helps develop trust and confidence. Experience shows that over time, particularly on longer phases of work, the peaks and troughs of estimation accuracy even themselves out. Where the customer benefits is where a team works together for longer they find naturally more efficient ways of working and velocity increases.

Next stage: [Sprint Review](delivery_recipe/sprint_review.md)
