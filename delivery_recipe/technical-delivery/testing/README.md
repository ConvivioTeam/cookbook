# Testing

Testing is a vital part of software development.

> Every programmer knows they should write tests for their code. Few do. The universal response to "Why not?" is "I'm in too much of a hurry." This quickly becomes a vicious cycle- the more pressure you feel, the fewer tests you write. The fewer tests you write, the less productive you are and the less stable your code becomes. The less productive and accurate you are, the more pressure you feel. Programmers burn out from just such cycles. Breaking out requires an outside influence. We found the outside influence we needed in a simple testing framework that lets us do a little testing that makes a big difference.

(**Source:** [JUnit Test Infected: Programmers Love Writing Tests](http://junit.sourceforge.net/doc/testinfected/testing.htm))

There are numerous approaches to writing tests for applications. The two of most significance for technical delivery are unit testing and behavioural testing, but regression testing and integration testing are also important considerations and may be tackled within the rubric of unit and behavioural testing. These should be considered complementary, not either-or methodologies.
 
### Unit tests

Unit tests are short code fragments written to test individual units of code. In this sense, a 'unit' is the smallest testable part of an application. Unit tests grouped together can then test specific components _and_ the whole application.

The [PHPUnit manual](https://phpunit.de/) is really well written, and contains a great [guide for writing your first tests](https://phpunit.de/getting-started.html).

### Behavioural tests

[Behat](http://behat.org/en/latest/) or [Codeception](http://codeception.com/) are useful tools for testing the behaviour of an application or product and work well in a Behavior Driven Development approach to software development.

Tools like [Selenium](http://www.seleniumhq.org/) or [PhantomJS](http://phantomjs.org/) and services like [SauceLabs](https://saucelabs.com/) may be useful for behavioural testing.
 
## Writing tests

The product development lifecycle includes test writing at every stage, to ensure the product [quality]((delivery_recipe/technical-delivery/code-quality/README.md). 
 
## Running tests

Best practice determines that we run the application testing layer as part of the [automated processes for delivering new product features](delivery_recipe/technical-delivery/automation/README.md), though they are also useful for ad hoc testing or for developers to run locally as well.