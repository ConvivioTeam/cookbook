# Automation

We think of automation at several different levels, from the way a developer does their work to way we build and deploy applications. 

## Use better tools

We encourage our developers to use the most appropriate tools for their work. Modern integrated development environments (IDEs) – like PhpStorm or Netbeans for example – not only have excellent code hinting and code completion but also lots of plugins and extras for important things, like, for instance, [PHP Code Sniffer](http://pear.php.net/package/PHP_CodeSniffer) [integration](https://gist.github.com/klederson/ca43a0f7f5b2478c1d44) [in PhpStorm](https://www.jetbrains.com/help/phpstorm/2016.2/using-php-code-sniffer-tool.html) or [Xdebug](https://xdebug.org/) [integration in PHPStorm](https://www.jetbrains.com/help/phpstorm/2016.2/configuring-xdebug.html).

## Task runners and dependency managers

There are many [task runners](https://www.smashingmagazine.com/2016/06/harness-machines-productive-task-runners/) and [packager or dependency managers](https://github.com/showcases/package-managers) that both help to automate the developer's work _and_ aid in conforming to industry standards and best practices.

#### Frontend
Task runners such as [Grunt](http://gruntjs.com/), [Gulp](http://gulpjs.com/) are important and useful frontend development tools, for tasks such as: 

- Compiling SASS
- Minifying SASS
- Minifying JS
- Concatenating/Uglifying JS
- Compressing images
- Watching for changes and running certain tasks on file change
- Refreshing the browser on file change

#### Backend

We advocate PHP development uses the [Composer](https://getcomposer.org/) dependency manager as much as possible. Composer is becoming increasingly-well supported by open-source PHP software projects and the de facto standard for building PHP software distributions and projects.
  
Other similar dependency managers are available and should be employed for other languages and technologies. 

## Continuous integration

We use [continuous integration](http://www.martinfowler.com/articles/continuousIntegration.html) automation tools (and the [process and practices associated with continuous integration](https://www.thoughtworks.com/continuous-integration)) to continually build the development environment, run [tests](../testing/README.md) and return results. Automated builds are usually triggered when code is checked into the designated branch of the code source control repository, for example, after a feature pull request has been successfully reviewed and merged. 

This practice ensures errors are detected early by the development team, so they can be fixed and prevented from escalating or being accidentally deployed to production.

## Continuous deployment

[Continuous deployment](https://www.agilealliance.org/glossary/continuous-deployment/) or [continuous delivery](https://www.thoughtworks.com/continuous-delivery) is the natural extension of continuous integration. Changes made to the system are constructed as 'releasable' and these releases are then pushed to production automatically.

Continuous deployment is designed to _make releases boring_ so the project team can deliver frequently and get fast feedback on what users care about.