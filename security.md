---
layout: page
title: Security
permalink: /Security/
feature-img: ""
---

<div class="toc">
  

  <ul class="listContent">
    <li><a href="#hwgh">How we got here</a></li>
    <li><a href="#cm">Common Misconceptions</li>
    <li><a href="#pis">Problems in security</a></li>
    <li><a href="#wdtfl">Where does the future lead?</a></li>
    <li><a href="#eac">Examples and Code</a></li>
  </ul>
</div>

<h1 id="hwgh">How we got here</h1>

Security used to concern protecting our most valuable physical assets, often behind locked doors in vaults and safes. Now, thanks to advancements in computing/computer science, our most valued assets are often in the form of digital information. This makes our information nearly cost-free to duplicate, convenient to intercept and increasingly cheap to store in massive quantities.

With the development of the Internet, our computers became part of a network that includes millions of other computers.  We're happy to share information, certainly, but only with people we trust. We want to be sure that the right, accurate information is in the right hands. As more information is stored digitally, the need for computer security grows.

But who is developing the security software, and how effective is it? A primary benefit of free and open source software is that it can be analyzed by anyone interested in understanding how it works. The public nature of the code means it is more likely that any holes or flaws can be identified and fixed.

This is preferable to companies and groups creating and using security software that can't be publicly analyzed and checked for flaws. Security software is strongest when all of the code is public, as it helps to ensure the challenging security and encryption features are properly designed. It is important when we trust our sensitive information to software that we can verify it does what it claims to do and is acting in the best interest of the user, not the company. While it may seem strange at first telling, secrets are best kept with software that itself is not secret.[^1]

[^1]: Cryptographers refer to this as Kerckhoff's Principle

<h1 id="cm">Common Misconceptions</h1>

Privacy is a right that extends to your online activity, and as such needs no justification or explanation. The argument that "I've got nothing to hide" falls short when we realize that in having your choice or want for privacy questioned, your right to it has already been ignored. Having your online activities monitored and tracked should have an opt-in feature, instead of actively having opt-out each time you are online. Even if we feel we have nothing to hide, it is not up to ISPs, advertising companies, governments or anyone else to question or exploit our online activities.

People often make the mistake of assuming that using a Virtual Private Network (VPN) is enough to safeguard and protect their online activities. However, the use of a VPN alone is not sufficient, because even though the payload of what you are sending, viewing, communicating, etc. is encrypted, the overhead is not. Anyone monitoring the network or your computer can still see when you are online, the duration of time spent and the size of your communications. Also worth noting is that by entrusting your privacy to a VPN you are handing over your sensitive communications to a third party and trusting them to keep them safe further adding a potential weak link in the information chain.

HTTPS provides anonymity, however the metadata is still accessible and easily tracked. Anonymizing proxies act as a middleman to redirect your traffic, hiding your IP address from the website you are trying to access. However only one proxy server is used to redirect your connection and if being monitored, the size of your incoming connection can be matched up with the size out the outgoing request.

ISPs also keep logs of all server activities, which can easily be subpoenaed. Websites can access data from your browser's plug-ins to attempt to reveal your original IP address, with Flash being one of the most notorious enablers as it shares much more information than is needed. Many people also fail to realize that logging into any website requiring a password and username allows the website to track you, regardless if you are using a proxy or not. If you must access these kinds of websites, http://bugmenot.com/ can provide a generic login where available.

<h1 id="pis">Problems in security</h1>

The benefits of having access to a nearly infinite amount of knowledge and information should be balanced with our increased vulnerability. Being connected to servers and computers that may be running software designed with malicious intent is an ongoing problem.

The world's population will inevitably become more computer literate. While that is undoubtedly a good thing overall, it also increases our dependence on a system vulnerable to individuals who might potentially lead attacks to steal information or block access.


<h1 id="wdtfl">Where does the future lead?</h1>

As more of our information becomes digital, the need for strong trustworthy security increases. We will likely see more "smart" hardware in our homes and the larger human environment. The very fact that this hardware is "connected" makes your home potentially less private.

Imagine that you're heading off for a much needed winter vacation. You set your smart thermostat to keep your home cool while you're away, and to turn on your heating again in a week--just before you return home. Anyone who can access this information would suspect that there will be no-one in the house that week, leaving it vulnerable to a break-in. Security and privacy is needed here, too.

In the long run, there will be an increasing number of attacks by nefariously minded parties. Building software with security features is common place, however it is harder to find software that is secure by default. Thankfully the last few years have helped a number of free and open source security projects mature into reliable tools.

<h1 id="eac">Examples and Code</h1>


****

**Tor**

![tor]( {{ site.baseurl }}/img/security/tor.png)

Site: [torproject.org](https://www.torproject.org)

Github: [github.com/TheTorProject](https://github.com/TheTorProject)

Tor is one of the more popular pieces of open source security software because of the large community working to make it better and the increasing need to anonymize browsing traffic.

The Tor project makes available a browser ([the Tor Browser](https://www.torproject.org/projects/torbrowser.html.en)), like Chrome, that allows you to surf the web, but with the goal of anonymizing your traffic. Tor achieves its anonymity by bouncing your communications around a distributed network of relays run by volunteers around the world helping keep your physical location and web traffic hidden.

<div class="resources" markdown='1'>
* **Tutorials**
	* [Installing Tor on different systems](https://www.torproject.org/docs/installguide.html.en)
	* [A beginner's guide to Tor](http://www.digitaltrends.com/computing/a-beginners-guide-to-tor-how-to-navigate-through-the-underground-internet/)
	* [Comparing Tor and VPNs](https://thetinhat.com/tutorials/darknets/tor-vpn.html)
* **Examples**
	* [Who uses Tor?](https://www.torproject.org/about/torusers.html.en)
</div>

**Tails - the amnesic incognito live system**

Site: [https://tails.boum.org/](https://tails.boum.org/)

Git: [https://git-tails.immerda.ch/](https://git-tails.immerda.ch/)

Tails is an operating system, like Windows or OSX, but designed explicitly for security and privacy. It comes preloaded with both Tor and Onionshare and is an easy way to get started with many privacy focused tools. Tails is designed to be loaded onto a CD or a USB stick and used as-needed without replacing your existing day to day operating system outright.

<div class="resources" markdown='1'>
* **Tutorials**
	* [Installing Tails onto a USB stick or SD card](https://tails.boum.org/doc/first_steps/installation/index.en.html)
	* [First steps and options](https://tails.boum.org/doc/first_steps/index.en.html)
</div>


**Onionshare**

![onionshare]( {{ site.baseurl }}/img/security/onionshare.png)

Site: [onionshare.org](https://onionshare.org/)

Github: [github.com/micahflee/onionshare](https://github.com/micahflee/onionshare/)

Onionshare is a file-sharing service built on top of the distributed anonymity network Tor. Onionshare allows you to make a file on your computer temporarily available to others with a Tor browser through a special URL. The file sharing is both anonymous and secure against eavesdroppers.

<div class="resources" markdown='1'>
* **Tutorials**
	* [github.com/micahflee/onionshare/blob/master/README.md](https://github.com/micahflee/onionshare/blob/master/README.md)
</div>

**PGP**

![onionshare]( {{ site.baseurl }}/img/security/pgp.png)

Site: [gpgtools.org](https://gpgtools.org/)

Github: [github.com/GPGTools](https://github.com/GPGTools)

PGP (Pretty Good Privacy) is a technology that aims to make emailing more private through encryption. It's one of the more complex setups for messaging others, but also one of the more secure because of the encryptions independence from any other servers or third parties.

A common setup is using [Mozilla's Thunderbird](https://www.mozilla.org/en-US/thunderbird/) email client and then installing the [Enigmail](https://addons.mozilla.org/en-US/thunderbird/addon/enigmail/) plug-in.

<div class="resources" markdown='1'>
* **Tutorials**
	* [PGP and You, thoughtbot](http://robots.thoughtbot.com/pgp-and-you)
	* [How to: Use PGP for Mac OS X](https://ssd.eff.org/en/module/how-use-pgp-mac-os-x)
	* [Frequently asked PGP questions](http://www.faqs.org/faqs/pgp-faq/part1/)
	* [Reasons not to start using PGP](http://secushare.org/PGP)
	* [Getting started with PGP on Windows](https://xato.net/cryptography/pgp-10-minutes-or-less)
	* [PGP Trust](http://www.phildev.net/pgp/gpgtrust.html)
	* [Video: GPG Encryption for Mac](https://www.youtube.com/watch?v=yXm0dtYFxZk)
</div>


**SecureDrop**

SecureDrop is a lot like Dropbox, but focused on security and anonymity. It was developed to allow whistleblowers to submit anonymized material to specific organizations. A few news organization now have their own SecureDrop system to allow information and stories to be submitted securely.

![securedrop]( {{ site.baseurl }}/img/security/securedrop.png)

Site: [freedom.press/securedrop](https://freedom.press/securedrop/)

Github: [github.com/freedomofpress/securedrop](https://github.com/freedomofpress/securedrop/)

<div class="resources" markdown='1'>
* **Tutorials**
	* [Using SecureDrop with the Washington Post](http://pagebuilder.washingtonpost.com/pb/securedrop/)
* **Examples**
	* [The Guardian uses SecureDrop for confidential stories](https://securedrop.theguardian.com/)
	* [Using SecureDrop with The Intercept](https://firstlook.org/theintercept/securedrop/	)
	* [Using SecureDrop with ProPublica](https://securedrop.propublica.org/)
</div>


**Cryptocat**

![cryptocat]( {{ site.baseurl }}/img/security/cryptocat.png)

Site: [crypto.cat](https://crypto.cat/)

Github: [github.com/cryptocat/cryptocat](https://github.com/cryptocat/cryptocat)

Cryptocat is browser extension that runs on Chrome, Firefox, or Safari. Cryptocat works by encrypting all chat before it gets sent to the Cryptocat servers, so only the users you intend to participate in the conversation can read your messages.

It's a much easier and friendlier experience than some of security focused communication software, but as they say on their website, it's not 100% bulletproof. All software is prone to bugs and holes that can bypass the encryption and make your communication less private.

<div class="resources" markdown='1'>
* **Tutorials**
	* [Video: How to use cryptocat](https://www.youtube.com/watch?v=3BeHR2nfaQg)
	* [Video: Encrypt your chats with cats](https://www.youtube.com/watch?v=Hhv-XyTXmQY)
</div>

**RedPhone**

![redphone]( {{ site.baseurl }}/img/security/redphone.png)

Site: [whispersystems.org](https://whispersystems.org/)

Github: [github.com/WhisperSystems/RedPhone](https://github.com/WhisperSystems/RedPhone)

RedPhone is an Android phone app that allows for encrypted calls through data, instead of regular voice calling.

<div class="resources" markdown='1'>
* **Tutorials**
	* [Reviewing and understanding RedPhone](http://www.ghacks.net/2013/08/12/encrypt-android-phone-conversations-with-redphone/)
	* [Installing RedPhone](https://ssd.eff.org/en/module/how-use-redphone-android)
</div>

**ProtonMail**

![protonmail]( {{ site.baseurl }}/img/security/protonmail.png)

Site: [protonmail.ch](https://protonmail.ch/)

Github: [github.com/ProtonMail](https://github.com/ProtonMail)

ProtonMail is an intermediary service for using with any email service like Gmail or Yahoo. It's goal is to protect your emails using end-to-end encryption. This means as soon as you hit send your email is encrypted and then sent to the ProtonMail servers.

ProtonMail is an easier option than tools like PGP for sending messages, because no key exchanging needs to be done prior to you sending a message. All you need is the other person's email address.

<div class="resources" markdown='1'>
* **Tutorials**
	* [How ProtonMail's threat model works](https://blog.protonmail.ch/protonmail-threat-model/)
	* [Setting up a ProtonMail account](https://www.cryptocoinsnews.com/inside-look-protonmail-end-end-encrypted-email/)
</div>

**miniLock**

![minilock]( {{ site.baseurl }}/img/security/minilock.png)

Site: [minilock.io](https://minilock.io/)

Github: [github.com/kaepora/miniLock](https://github.com/kaepora/miniLock)

miniLock is a Chrome app that allows you to send single files to a recipient. miniLock was made to make sharing single files easier and just as important, securely. Past encryption software wasn't as user friendly, but miniLock aims to make well designed encryption software a standard.

Every user gets a key to give out to friends, which allows others to send you files. miniLock can be used on Mac, Windows, or Linux.

<div class="resources" markdown='1'>
* **Tutorials**
	* [Video: Introducing miniLock](http://vimeo.com/101237413)
	* [Slides: Introducing miniLock](https://minilock.io/files/HOPEX.pdf)
	* [miniLock simple encryption, Wired](http://www.wired.com/2014/07/minilock-simple-encryption/)
	* [Meet miniLock, The Verge](http://www.theverge.com/2014/8/4/5960637/meet-minilock-a-powerful-new-encryption-tool-build-on-chromeos)
</div>




**Other security links**

[Why King George III Can Encrypt](https://freedom-to-tinker.com/blog/randomwalker/why-king-george-iii-can-encrypt/)

[The Guardian Project](https://guardianproject.info/code/)

[EFF: Lessons for journalism students](https://ssd.eff.org/en/playlist/journalism-student)

