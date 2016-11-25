# Story Lifecycle

Each story has a unique lifecycle depending on its complexity and requirements. We’ve tried to capture the general lifecycle of a story here, but like most things it can be subject to change.

## Wireframing

A high level overview of each user facing interface. What information do users need to see and what elements do they interact with to progress in their journey?

## Technical Research
There are always multiple ways to build a piece of functionality so when a developer picks up a ticket their first job is to find the best tools to start the task. We encourage developers [not to re-invent the wheel](/delivery_recipe/technical-delivery/code-quality/README.md#dont-write-code-write-new-code-only-when-everything-else-fails), so initial research is always important when starting off.

Sometimes, in hindsight, the technical choices made initially may prove not to be the best approach, and improvements are made through re-evaluation and peer review.

## Implementation

This is the 'getting stuff' done stage, sitting down and turning key strokes into deliverable code. Throughout this process a developer is constantly thinking about [best practices](/delivery_recipe/technical-delivery/README.md) and [code quality](/delivery_recipe/technical-delivery/code-quality/README.md).

## Visual Design

The output is reviewed by a designer and the look and feel are adapted for good usability and brand consistency.

## Local Testing

Once functionality has been implemented it’s time to test it out locally. 

- Does it match the acceptance criteria?
- Does it pass any edge-case requirements?
- Are there any PHP notices or warnings? and so on.

Most of these should be addressed before code leaves a developers machine.

## Code Review

Once a developer is happy with their code it gets sent for code review by another developer or the tech lead on the project. This stage gives people the chance to look over the code and spot any obvious errors or mistakes. These problems can then be ironed out before delivery.

Code review can happen in a number of different ways, depending on the scale of additions made.

Smaller-scale changes might need only a visual check over the code for the quality of what's been written.

At the other end of the spectrum, larger-scale changes may demand that the reviewer checks the code out locally and gives it a thorough going-over to check the viability and stability of the additions, maybe running functional or integration tests locally in the process.

## Regression Testing

Now that the code has passed review we run a sequence of automated tests. These make sure that the new additions still function with all the upstream work that’s gone on since we started the story. New functionality mustn't break anything others have built along the way.

## Demo Recording

This is our proof of life. The demonstration acts both as a record that we’ve produced the functionality and as a self-documenting user reference on how the new functionality works. As more and more demos are created we amass a library of material that can be used both for reference and for training purposes.

## Quality Assurance

Before the code is released to the live production system, a stage of quality assurance is usually required. This is often a combined effort of internal and client team members, often non-technical users, who are able to spot errors and omissions that automated testing tools and technical teams who're 'too close' to the code may miss.

Many times an embarrassing error is caught by an eagle-eyed quality assurance review!

## Delivery

Now that the story is complete we can deploy it to production, ready for use. High five!

## Usability testing

Some stories may require validation after delivery. Do they solve the problem as effectively as we anticipated? Did we introduce any problems that we didn't identify before?
