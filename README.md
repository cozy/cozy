# Cozy, Your Digital Home

![Cozy Logo](https://raw.githubusercontent.com/cozy/cozy-setup/gh-pages/assets/images/happycloud.png)

Cozy is an app-based personal cloud you can host at home. It allows you to turn
a cheap hardware like a Raspberry Pi or an online VPS in a powerful app
platform. It comes with common applications like a contact manager, a calendar,
a webmail and a filebox. An Android app is provided. You can sync
your contacts, calendars and files with your mobile. Last but not least, the
community built many personal tools like a feed reader, a bank operation
manager or an IRC client.

Cozy is based on Node.js and allows realtime interaction between apps. Any app
can request access to other application data. That way they can communicate
and share information.

Website: http://cozy.io

[![Cozy Home screenshot](https://cozy.io/assets/press/screenshots/home_th.png)](https://cozy.io/assets/press/screenshots/home.png))
[![Cozy Contacts screenshot](https://cozy.io/assets/press/screenshots/contacts_th.png)](https://cozy.io/assets/press/screenshots/contacts.png))
[![Cozy Emails screenshot](https://cozy.io/assets/press/screenshots/emails_th.png)](https://cozy.io/assets/press/screenshots/emails.png))
[![Cozy Calendar screenshot](https://cozy.io/assets/press/screenshots/calendar_th.png)](https://cozy.io/assets/press/screenshots/calendar.png))
[![Cozy Files screenshot](https://cozy.io/assets/press/screenshots/files_th.png)](https://cozy.io/assets/press/screenshots/files.png))

### Main Benefits

* Smoother experience of your digital life
* Ownership of your data and respected privacy
* Vendor-agnostic synchronization
* Quick start with Google data importer (contacts and calendars)
* Playground for developers to build new services around personal data


## Install

There are many ways to install Cozy:

* [Through Debian repository](https://cozy.io/en/host/install/install-on-debian.html), ([repo](https://github.com/cozy/cozy-debian))
* [Image For Raspberry Pi 2](https://cozy.io/en/host/install/install-on-raspberry.html)
* [Via Docker](https://cozy.io/en/host/install/install-on-docker.html), ([repo](https://github.com/cozy/cozy-docker))
* [All methods](https://cozy.io/en/)


## Community

We have a vibrant community that will be glad to welcome you. You can share
with us your thoughts, your feedback, bug reports of your app ideas. 

*NB: The community is composed mainly of French users, but don't be afraid they
can speak English too.*

* [Forum](https://forum.cozy.io)
* [Wiki](https://github.com/cozy/cozy-setup/wiki)
* [Twitter](https://twitter.com/mycozycloud)
* [Github](https://github.com/cozy)
* [Labs on Github](https://github.com/cozy-labs)
* Chat: #cozycloud on irc.freenode.net


### Translators

Like many free and open source projects, you can contribute by translating 
the user interface texts. To manage that, we use the Transifex platform. Cozy
is already translated in English, French, German and Spanish. If you want to
add your own language, connect with us via our [Transifex
Dashboard](https://www.transifex.com/organization/cozy)


### Developers

Building an app for Cozy is the fastest way to learn full stack development
with Node.js. We propose [a complete
Tutorial](http://cozy.io/en/hack/getting-started/) that will teach you how to
use Express.js and AngularJS to build your first Single Page Application.

For experimented web developers you can use the frameworks you want. The only
requirement is to use the [Cozy database driver](https://github.com/cozy/cozydb).

Whatever your skill level is, we propose a [Mentorship Program](https://forum.cozy.io/t/mentorship-program/529). 
A member of the Cozy Team will help you in the process of building your Cozy
app. Reel free to subscribe to it via the forum.


#### Benefits for developers

* Learn full-stack development with Node.js
* Experiment and build quickly prototypes for your next app
* Avoid the pain of deployment and user administration
* Fix one of your problem related to personal data
* Share your app and get feedback from the community


#### Connectors

There is an app called Konnectors that allows to fetch data from many vendors.
It's easier to build a connector than writing an app. Look at the
[Konnectors](https://github.com/cozy-labs/konnectors) repository for more
information.


### Platform maintenance

You will find here every open tickets and pull request for the Cozy platform:

* [Bug List](https://github.com/issues?q=is%3Aopen+is%3Aissue+user%3Acozy+label%3Abug+-repo%3Acozy%2Ftodos+-repo%3Acozy%2Fnotes+-repo%3Acozy%2Fcozy-editor+)
* [Feature Request List](https://github.com/issues?q=is%3Aopen+is%3Aissue+user%3Acozy+label%3Aenhancement+-repo%3Acozy%2Ftodos+-repo%3Acozy%2Fnotes+-repo%3Acozy%2Fcozy-editor+)
* [Opened Pull Requests](https://github.com/pulls?user=cozy)
* [Waiting tickets](https://github.com/issues?q=is%3Aopen+is%3Aissue+user%3Acozy+no%3Alabel+-repo%3Acozy%2Fcozy-guidelines)
* [Tickets good for a first contribution](https://github.com/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+user%3Acozy+label%3A%22Good+For+First+Contribution%22+-repo%3Acozy%2Ftodos+-repo%3Acozy%2Fnotes+-repo%3Acozy%2Fcozy-editor+)


## Architecture

Here is a quick overview of the architecture. You can find details and
explanation 
[here](https://cozy.io/en/hack/getting-started/architecture-overview.html)

![Architecture diagram](https://cozy.io/assets/images/architecture-overview.svg)


## License

Cozy is developed by Cozy Cloud under the AGPL v3 license (see each module for
exceptions).

