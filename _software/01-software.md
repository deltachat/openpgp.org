---
title: "Email Encryption"
permalink: /software/
excerpt: "Email Encryption"
modified: 2016-08-15T15:00:00-00:00
---

{% include base_path %}

{% include toc %}

All email applications on this page support the OpenPGP standard either directly or with additional software.
The authors of this webpage are not actively participating in the development of each of these third-party apps.
No security audits have been done by us and, thus, we cannot provide any security guarantees.

## Windows
* Outlook: [Gpg4Win](https://www.gpg4win.de) with [GpgOL](https://www.gpg4win.org/about.html)
* Outlook: [gpg4o](https://www.giepa.de/produkte/gpg4o/)
* [Thunderbird](https://www.mozilla.org/de/thunderbird/): [Engimail](https://enigmail.net)
* [Pretty Easy Privacy](https://prettyeasyprivacy.com/)

## Mac OS
* Apple Mail: [GPGTools](https://gpgtools.org)
* [Thunderbird](https://www.mozilla.org/de/thunderbird/): [Engimail](https://enigmail.net)

## Android
* [K-9 Mail](https://k9mail.github.io/): [OpenKeychain](http://www.openkeychain.org)
* [Pretty Easy Privacy](https://prettyeasyprivacy.com/)

## iOS
* [iPGMail](https://ipgmail.com/)

## GNU/Linux
* [KMail](https://www.kde.org/applications/internet/kmail/): [GnuPG](https://gnupg.org)/[Kleopatra](https://www.kde.org/applications/utilities/kleopatra/)
* [Evolution](https://wiki.gnome.org/Apps/Evolution): [GnuPG](https://gnupg.org)/[Seahorse](https://wiki.gnome.org/action/show/Apps/Seahorse)
* [Thunderbird](https://www.mozilla.org/de/thunderbird/): [Engimail](https://enigmail.net)

## Browser Plugins
* [Mailvelope](https://www.mailvelope.com)
* [Google's End-to-End](https://github.com/google/end-to-end)
* [Yahoo's End-to-End](https://github.com/yahoo/end-to-end)

## Webmail Provider with Browser Plugins
The following webmail providers support email encryption via the OpenPGP standard using browser plugins.

* [WEB.DE](http://web.de/) (Mailvelope)
* [GMX](http://www.gmx.net/) (Mailvelope)
* [POSTEO](https://posteo.de) (Mailvelope)
* [mailbox.org](https://mailbox.org/) (Mailvelope, also In-Browser Cryptography)

## Webmail Provider with In-Browser Cryptography
In contrast to the previous section, the following webmail providers do not require the installation of additional plugins, instead JavaScript cryptographic libraries are served by the website itself.
While these are easier to set up and provide basic security guarantees with OpenPGP, [some people don't consider this "end-to-end"](https://tonyarcieri.com/whats-wrong-with-webcrypto).

* [ProtonMail](https://protonmail.com/)
* [Hushmail](https://www.hushmail.com/)

## Gateways
* [Symantec PGP Encryption Software](https://www.symantec.com/de/de/encryption/)

## Project Missing?
If a project is missing and you would like it included, please open a pull request at [github.com/OpenPGP/openpgp.github.io](https://github.com/OpenPGP/openpgp.github.io).