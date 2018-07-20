# Code Quality

Code quality is a way of referring to the quality of the product being built and the way that is being built – the product, the architecture, the design, the codebase, the technical team. It is a larger idea that covers many aspects of best practice when programming, when working in a technical team to develop products.

In that context, there's many best practices, methodologies, conventions and rules of thumb that we subscribe to here at Convivio.

## Don't Write Code \(write new code only when everything else fails\)

> This is the single most important lesson every developer needs to learn. The amount of duplicate, crappy code \(across projects\) that exists today is overwhelming. In a lot of cases developers don’t even bother to look around. They just want to write code.

\(**Source:** [Naresh Jain, 'Biggest Stinkers', _Managed Chaos blog_](http://blogs.agilefaqs.com/2009/10/19/biggest-stinkers/)\)

### Open source it

The manifestation of the 'Don't Write Code' mantra is that _we believe in _[_open source software_](https://opensource.com/resources/what-open-source)_ \(OSS\)_. By using OSS we are able to benefit from the uncountable hours of design and programming already invested by developers all over the world, and the only new code written is the necessary code.

We use OSS wherever possible, especially in product development, and consequently we participate in the open source community. Consequently and intentionally, we give back to the OSS community – sharing work, offering and reviewing patches for features or bugs, sharing knowledge, and so on.

We use [Drupal](https://www.drupal.org/) for many projects so our largest interaction is with the Drupal community, but we also participate in the wider PHP community, as well as the frontend Javascript technology communities and others.

## Quality matters

> When I hear "JUST BANG OUT CODE THAT WORKS" I think of all the apps I don't use anymore because they gradually lost the ability to iterate.

\(**Source:** [Avdi Grimm](https://twitter.com/#!/avdi/status/180747721852985344)\)

**working code &gt; not-working code**

_But_, it is better to work within the coding conventions of the technology you are using as this will tend towards high quality code. Coding conventions are there for good reasons:

* they make code run well;
* they make code readable when other developers come to use it;
* conventions are often hard-won through brutal experience of writing efficient, effective portable code.

For example, when working on Drupal projects we subscribe to the community-agreed [Drupal coding standards](https://www.drupal.org/docs/develop/standards).

Code changes should always be reviewed. This includes:

* peer review, through, for example, pull requests;
* design and UX reviews;
* [testing](testing.md), both:
  * automated testing, and
  * user testing.

### Version control is important

With a number of developers working on a software project it is important that changes to the codebase are managed effectively. A version control tool is vital. There are a number of options, of course, but we prefer to work with [Git](https://git-scm.com/) where possible.

There are also good disciplines for branching models and workflows in version control. [Gitflow](http://nvie.com/posts/a-successful-git-branching-model/) is what we usually prefer, but [other workflows](https://www.atlassian.com/git/tutorials/comparing-workflows/) may be more appropriate in certain circumstances.

If it is possible, we prefer to make our projects themselves open source.

## Don't do hard things, do easy things

* Simple is better than complex.
* Complex is better than complicated.
* Flat is better than nested.
* Readability counts.
* If the implementation is hard to explain, it's a bad idea.
* If the implementation is easy to explain, it may be a good idea.

\(**Source:** [The Zen of Python](http://www.python.org/dev/peps/pep-0020/)\)

## Never build large apps

> The secret to building large apps is never build large apps. Break your applications into small pieces. Then, assemble those testable, bite-sized pieces into your big application.

\(**Source:** [Brian Moschel, 'Organizing A jQuery Application'](http://blog.bitovi.com/organizing-a-jquery-application/)\)

By splitting an application or product up into reusable components the components are individually testable _and_ the application is testable as a whole. If we need to make a change, we can work on the component itself, test it, make changes, then regression test the whole application. \([Microservices](http://martinfowler.com/articles/microservices.html) – suites of independently deployable \[distributed\] services able to interact in a unified application – is the logical end of this approach.\)

## Programming is also teaching your team

> … a team of mediocre, inexperienced coders who work together and write for the benefit of the team has the capability to become a great team, and they can take that learning approach to create other great teams. It all comes down to whether the team sees its work as simply writing code... or writing with the goal of both code and learning."

\(**Source:** [Joe Ottinger, 'Programming is Also Teaching Your Team'](http://www.theserverside.com/tt/articles/article.tss?l=ProgrammingisAlsoTeachingYourTeam)\)

### The most important element of successful software development is learning

> … when the entire team meets a certain standard for competence, there is a very large learning surface exposed and the team is able to absorb more information.

\(**Source:** [Reginald Braithwaite, 'Which theory fits the evidence?'](http://weblog.raganwald.com/2007/06/which-theory-first-evidence.html)\)

#### Sources:

[Tim Oxley](https://github.com/timoxley), '[Best Practices](https://github.com/timoxley/best-practices)'

