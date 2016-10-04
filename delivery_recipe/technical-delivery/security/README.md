# Security

Managing your digital security is all about understanding the risks you face and determining the levels of risk that are tolerable with the data for which you are responsible. The security profile of a personal blog is very different from an e-commerce site, and is different again from a central government portal service.

## Security Essentials

There's some basic steps to take for digital security of your website or application.

### Secure installation

Open source software usually has comprehensive documentation on securing your installation. As a bare minimum, follow these.

#### Strong passwords

[<img alt="XKCD: Password strength (https://xkcd.com/936/)" src="http://imgs.xkcd.com/comics/password_strength.png" width="500">](https://xkcd.com/936/)

Ensure you have a strong password for the administrative or root user. There is much discussion online about what constitutes a strong password ([Google]( https://support.google.com/accounts/answer/32040?src=soctw); [Wikipedia](https://en.wikipedia.org/wiki/Password_strength); [Correct Horse Battery Staple](http://correcthorsebatterystaple.net/)). We rcommend using a _pass phrase_ rather than a password, ensuring it is at least 16 characters long and preferably longer than 24 characters. 

### Update all the things

Open source software projects regularly release security updates for the core sofware and for modules within it. Some OSS will include an update status that will specifically identify any available or pending security updates. **_Always_ ensure you install security updates.**

### SSL your site

post-Snowden, for technical and social reasons, put your site on SSL.

## Data Security

- XSS vectors
- Encrypted database
- database access only through API
- clean DB dumps of personal info

