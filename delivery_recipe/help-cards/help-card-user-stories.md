# User Stories

When we are capturing the requirements for a feature we want to do it in a way that we can all \(developers and non-developers, client-side and supplier-side\) have a useful conversation about the need that the requirement addresses, and possible ways to deliver it.

We use a standard way to set out these needs, and we call the format a 'user story'.

Two words are key in this phrase — user, and story:

1. User: who actually needs this thing, our main character in the story
2. Story: telling a story about what they do and why

In this story we don't need to capture every single detail about the need this user has. The intention is for user stories to be a 'placeholder for a conversation'. We're capturing the need in its bare details, and we can then discuss it later when we come to plan its implementation in a sprint.

## Format

We write user stories in a standard format so that we can all quickly approach any of these written up needs, understand how they are expressed, and take part in a conversation about them.

At it's most basic this format is:

> As a &lt;who&gt; I want &lt;what&gt; so that &lt;why&gt;

Which can also be thought of as:

> As a &lt;user role&gt; I want &lt;need&gt; so that &lt;benefit&gt;

## Start With User Needs

User stories are not simply a new way for stakeholders to express the same stuff that would previously have gone in a big requirements spreadsheet. They are the output of a different way of approaching defining the needs of a project.

First comes the business goals. From that we identify what types of people the organisation needs to interact with to meet the goals. These are the user groups, and we need to understand their needs, in support of the business goals, and deliver them.

So we conduct user research, and user testing if there is an existing service, and it is from this that we gain the insights that we write as user stories.

## Writing good user stories

To write clear and useful user stories that are most likely to be delivered well, follow these tips:

* **Focus on a real end user:** We often see stories like 'As a product owner I want the site to be served via hhtps to ensure data is secure', which should be rewritten to focus on the end user as something like 'As a customer I want my activity and data on the site to be secured so that I can protect my privacy and security'. Your project should have user personas defined, which will allow you to be even more specific about defining who has the need. If it's too hard to rewrite these kinds of stories to be genuinely about the end users, then see the section below 'Be honest when things are not really a user story'.
* **Focus on why:** what is the real goal of the user? Too many people skip or skimp on the why when writing stories and might as well write 'A user wants X just because'. Understanding the goal is really important, spend time on writing the 'why' into your stories.
* **Keep it simple:** what is the smallest cheapest way to take a next step towards this need. Then validate that, and improve on it further later.
* **A full cake slice:** while you should make it as small as possible, each story should be a full slice of cake, including the icing. Don't just deliver a chunk of unappetising sponge and call it cake. That means you need to think of all layers of the story, not just technical, but also UX.
* **Don't write the 'how':** focus on writing the who, what and why. The team will figure out the how later. This means that you focus better on describing the problem to be solved, rather than steering the team into one possible solution. Instead of writing 'A user wants to have a search box so that they can find properties' you'd write instead 'A user wants to find properties that are in the right area and budget for them so they get to a shortlist more quickly.' That then allows the team to take a creative approach to delivering the solution to this using all their experience, and you may end up with a much better solution than just a search box.
* **Write in '**[**active voice**](http://www.dailywritingtips.com/active-voice/)**':** write what the user is doing and wants to do. Everything is from their perspective with them being active.
* **Avoid jargon:** Anyone taking a look at the user story, including the user it describes, should be able to roughly understand what it means.

## Meeting the INVEST test for user stories

Good user stories meet the [INVEST](https://en.wikipedia.org/wiki/INVEST_%28mnemonic%29) standard:

* **Independent:** a need that is expressed in a self-contained way that can be delivered by a cross-functional team without inherent dependencies outside the story.
* **Negotiable:** The story as written is not a contract, but the start of a conversation in which everyone can contribute to shape it. The story can be rewritten or even discarded as more information and more discussion sheds light on the need and its value.
* **Valuable \(and value-able\):** Every story must deliver clear value to stakeholders. That means the source of value needs to be understood, along with a way to measure it, and a target to achieve. The constraint of budget/time that's worth spending on this story to deliver that value can then be discussed.
* **Estimable:** The need must be expressed clearly enough, with supporting information available, to allow the team to get a rough estimate of how 'big' it is in terms of effort, risk, etc. 
* **Sized appropriately \(small\):** stories should be deliverable by a cross-functional team within roughly a week, otherwise they need to be broken into smaller stories that build on each other over a number of iterations. Otherwise you end up with huge iceberg user stories that float through months of work with titanic amounts of time crashing onto them.
* **Testable:** can you explain the steps that would be taken by a user to demonstrate that the story has been delivered correctly?

## Be honest when things are not really a user story

User stories are about expressing user needs. With the culture of defining needs in a project as 'user stories' people then try to jemmy everything into this format, which results in stories like 'as a sysadmin I want to have Jenkins autodeploy the codebase so I can save time'. There is no way to genuinely write this into a user need, so don't pretend. Have a separate category for technical requirements that are kept separate from, and written differently from, user stories, but can travel through the backlog in the same way.

