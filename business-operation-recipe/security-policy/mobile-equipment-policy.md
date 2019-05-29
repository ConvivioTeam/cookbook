# Mobile Equipment Policy

It's Convivio's responsibility to implement procedures to manage and provide necessary access to data, while at the same time ensuring the confidentiality, integrity, availability, accountability and auditability of the information.

The use of laptop/notebook/tablet computers and other mobile devices increases the risks associated with the secure storage of data. The purpose of this policy is to set out the criteria for the provision of portable computers and the conditions relating to their use. This document forms part of our alignment to the ISO 27001 Information Security Management System standard.

## Responsibility

### Users

Laptops/notebooks and media must be handled and stored securely. In cars they must be stored out of sight when the car is left unattended e.g. in boot. When users are travelling, laptops/notebooks \(and media\) should not be left unattended in public places and should always be carried as hand luggage when travelling by public transport. Unofficial, unauthorised or unlicensed software must not be loaded on laptops/notebooks.

All laptops must have Bitdefender installed to protect against malware, viruses and Trojans, and the spread of these to other users. Quick scans are scheduled to run daily, full scans are run weekly. There is a quarterly review of firewall configurations when all users are required to update their configuration to meet the company policy.

Users are responsible for maintaining the security of their devices. This includes locking devices when leaving them, not sharing login details, not providing unauthorised users with access to the device and installing security updates regularly.

It is also the responsibility of the user to immediately report the loss, theft or unauthorised access of any mobile equipment to Convivio.

### Convivio

Convivio should ensure the correct configuration of the laptop/notebooks i.e. hard drives are encrypted to 256 bit, Data Loss Protection \(DLP\) software is installed and all relevant group policies are enforced. All laptops must be password protected with a password over 16 characters long containing both Alphanumeric characters and punctuation.

Convivio must approve and recommend a member of staff to be given remote access, having regard to the role and remit of the member of staff.

Convivio must ensure that when an employee leaves their remote access rights are removed and the laptop returned to Convivio.

Convivio will consider the provision of a laptop/notebook computer if the following criteria are met:

* a member of staff is required to work from more than one location and convenient access to a desktop PC is not available in all the locations;
* a member of staff regularly undertakes work at home, provided that such work does not breach the Working Times Directive;

Requests for laptop/notebook computers must be peer reviewed, with the management completing the purchase.

## Provision of Laptop/Notebook Computers

The provision of laptop/notebook computers shall be subject to the following conditions:

### Person Identifiable Information

In order to comply with the GDPR, person identifiable information shall be stored in a laptop/notebook only when this is absolutely necessary. Where it is necessary to store such information, the following conditions apply:

* Unnecessary user accounts \(e.g. Guest accounts and unnecessary administrative accounts\) should be removed or disabled.
* Unnecessary software \(including application, system utilities and network services\) should be removed or disabled.
* The auto-run feature should be disabled \(to prevent software programs running automatically when removable storage media is connected to a computer or when network folders are accessed\).
* A personal firewall \(or equivalent\) should be enabled on desktop PCs and laptops,and configured to disable \(block\) unapproved connections by default.
* Password authentication must be applied; encryption must be applied to the hard drive;
* It shall be stored only for the time period when it is actively being used;
* It shall be deleted immediately after use;
* Only the minimum amount of person identifiable information, necessary for the current purpose, shall be stored;
* The person’s name shall be stored only when absolutely necessary;
* Measures shall be taken to maximise the physical security of the laptop/notebook computer;
* For work involving person identifiable information from locations within Convivio, users will be required, wherever possible, to use Convivio’s network to store data.
* Public wifi should not be used to transfer sensitive data, if public wifi is unavoidable, the Convivio VPN should be used.

### Standard Build

There is a standard company laptop build which is provided from a centrally controlled source. When a laptop is booted up for the first time the user must run through the following steps:

* Create a new user with a secure password \(see [password policy](../../delivery-recipe/digital-service-standards/delivery-methodologies/automation/security-standards.md) page\)
* Ensure that encryption is enabled on user creation
* Install Brew
* Install Ansible
* Download our _Private_ OSX Provisioning repo
* Run OSX Provisioning

This is a private repo containing proprietary code and a standard build defined by Convivio. The process installs and configures key software including anti-malware, remote desktop, firewall, virtualbox, vagrant and OSX defaults, as defined by our administrators.

## Provision of Network Equipment

All networking equipment including firewalls and routers should not have their administration interface accessible over the internet.

Default and supplied passwords should be changed on acquisition of new hardware.

## Backups

It is not permissible for Convivio or its customer data to be stored solely on the hard disk of a laptop or notebook. Users of laptops/notebooks are responsible for ensuring that all Convivio data used on the laptops/notebooks is backed up. Common practice is for data to be stored on network or shared drives as these are backed centrally.

## VPN

When connected to 3rd party network Convivio VPN must be used. VPN accounts are created as part of the new employee on-boarding.

## Software maintenance

As Convivio predominantly use Apple Mac computers it is priority to outline maintaining security on OSX. Periodically, Apple releases free updates for OSX software. Updates should be set to run automatically. These include important security updates that protect Apple computers from potential threats.

Any patches that are released for threats should be implemented immediately. It is the responsibility of Convivio employees to observe changes in technology and maintain their computers to prevent risk. Software updates should be set to update automatically.

Updates suggested by other software vendors used for products used by Convivio should also be implemented.

## Hardware faults

Any hardware faults are to be monitored by the member of staff and reported to Convivio management. All Apple products are covered by Applecare and can be fixed under the policies outlined by Apple.

## Laptop Insurance

All Convivio hardware is insured both within the UK and abroad \(within the EU\).

## Disposal of Hardware

After 2 years of use any Convivio hardware will become the property of the user who requested its original purchase. This is supported by the Convivio ISMS data policy whereby no company information is kept on laptops and computers but is stored in a central location, this prevents the need to destroy company laptops.

If a user leaves the company before 2 years any hardware can be purchased from Convivio for a cost that represents its current value.

Because the software we produce is open source, there is no requirement to delete everything from any purchased machines. Any accounts relating to the user/laptop will be removed, see _Staff Leaving_ in our [Document Access](https://github.com/convivio/the-convivio-cookbook/tree/fe6bd3bde6ed1049b323d750b43bbb620c87c384/business_operation_recipe/security/document_access.html) policy.

## Mobile Phones and Tablets

### Bring your own device \(BYOD\)

Personal mobile phones and tablets can be used for Convivio purposes. Any customer data stored on the device should only be done so in line with the Person Identifiable Information policy outlined in the computers section.  

Team members are responsible for maintaining the security of their phones and tablets. This includes locking devices when they're not in use and also monitoring their safety to prevent data loss.

It is also the responsibility of the user to immediately report the loss, theft or unauthorised access of any phones or tablets that are used for Convivio purposes. 

### Mobile device security settings

Those devices used for Convivio purposes must have the following enabled in case of theft or loss; 

* iPhones should have 'Find my iPhone' enabled and the remote restore functionality switched on.
* Android devices should have 'Android Device Manager' enabled,  which locates devices associated with a Google account, reset your device’s screen lock PIN and erase all data on the phone.
* Encryption must be enabled on all phone types.

Team members using their own devices that have Convivio customers in their contacts must not use apps that share those details with third parties. This includes WhatsApp, Facebook and any other social media product. All team members using their own devices are responsible for checking the terms and conditions on all downloaded apps.

