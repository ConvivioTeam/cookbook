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

Estimates, by their very nature, are not exact. What we're looking to do with user story estimates is give ourselves a reasonably accurate estimation of the work we can expect to complete in a sprint.

If, at the end of the sprint, not all user stories are finished (done-done) then this doesn't mean that the sprint has failed. What this does show is that we discovered a story to require more effort than expected, that a module didn't provide the input we expected or that there was some other influence that affected the sprint.

If we have incomplete stories at the end of a sprint then we push those back into the backlog and it's up to the Product Owner whether or not they're priority stories for the next sprint. What we need to do is understand if there were particular reasons why our estimates were not accurate and take action to avoid those happening again in future.

When you're delivering work on such a regular basis it quickly becomes apparent just how transparent the process is. People need to understand that when a sprint "slips" we discover that very quickly and are able to adapt and fix any issues very quickly. 

In reality, experience shows us that our accuracy over the course of a longer term assignment improves as we understand more about what we're delivering. The velocity also tends to increase as the team becomes more efficient. Tracking the estimates and velocity over time show that the agile approach delivers consistently, at a high velocity, with regular improvements and with the high quality we should all expect.

Next stage: [Sprint Review](delivery_recipe/sprint_review.md)