# Security Standards

Managing your digital security is all about understanding the risks you face and determining the levels of risk that are tolerable with the data for which you are responsible. The security profile of a personal blog is very different from an e-commerce site, and is different again from a central government portal service.

## Security Essentials

There's some basic steps to take for digital security of your website or application.

#### Secure installation

Open source software usually has comprehensive documentation on securing your installation. As a bare minimum, follow these.

**Strong passwords**

![XKCD: Password strength \(https://xkcd.com/936/\)](http://imgs.xkcd.com/comics/password_strength.png)

Ensure you have a strong password for the administrative or root user. There is much discussion online about what constitutes a strong password \([Google](https://support.google.com/accounts/answer/32040?src=soctw); [Wikipedia](https://en.wikipedia.org/wiki/Password_strength); [Correct Horse Battery Staple](http://correcthorsebatterystaple.net/)\). We rcommend using a _pass phrase_ rather than a password, ensuring it is at least 16 characters long and preferably longer than 24 characters.

**Password management**

Administrator passwords \(firewalls, Google, GitHub\) and laptop passwords are required to be changed regularly, at least every 60 days. See "strong passwords" above for guidance on strong passwords.

#### Update all the things

Open source software projects regularly release security updates for the core sofware and for modules within it. Some OSS will include an update status that will specifically identify any available or pending security updates. _**Always**_** ensure you install security updates.**

Drupal security updates are reported weekly and are reviewed by our technical team. Priority updates are installed within a maximum of 48 hours.

Software running on mobile devices must be set to automatically update to take advantage of updates as soon as they're available.

#### SSL encrypt your site

Post-Snowden, for technical and social reasons, encrypt your site with SSL. That's it.

Not just the obvious bits, like logins and checkouts. All of it. With the technical innovations of recent years, there are lots of ways to make a secure site run fast, so there's no need to worry about

## Data Security

### Cross-site scripting

We use open-source software that has a thorough understanding of site's vulnerabilities to cross-site scripting attacks and which thoroughly check user input. We're very careful with the extensions we include and custom code we write to keep project sites and applicaitons safe from cross-site scripting attacks.

### Encrypted database

Where appropriate, we will encrypt an application's production database to keep vulnerable personal data safe. In this case, encryption keys will be held securely, and that may warrant placing it in a separate location to the application itself.

### Restricted access

If the security profile of the system warrants it, we may opt to further restrict the application's access to the data in the database to only the data made available by an API layer in front of the database. That API itself will have strong boundary security and access limitations, via firewalls and other methods, to restrict and control access to it.

We also manage access to the application's hosting platform. If the project's security profile warrants it, we may include a number of elevated access control tools or systems.

Access to all of our systems is managed only by a limited number of senior members of staff.

### Access logging

For security and audit purposes all activity in our systems is logged.

All code updates via GitHub are automatically posted in a private Slack channel alerting all staff to the updates. GitHub records a log of all changes to code \(date, user, details of the change\). GitHub provides audit and access logs detailing user logins, password resets and full logs for access to repository data.

Similarly, Google Drive provides details of changes \(date, user, details of the change, approved by\). In both of these, there is the option to view changes and roll back if necessary.

Slack provides detailed access logs to us. Administrators are able to remotely terminate connections and sign out all devices authenticated to our account at any time.

Contactually is hosted by Amazon and monitored 24/7/365 with all data stored in Amazon Web Services data centers.

We recommend to clients and hosting companies that server logs are enabled and monitored.

### Clean database dumps of personal info

It almost goes without saying, but whenever we need to take a dump from a live database – for local development, debugging, support or whatever – we ensure that any personal and identifying data is cleaned out before the data touches any unsanctioned computers \(including servers within your hosting platform that have not been specifically accredited or authorised to host that personal data\).

