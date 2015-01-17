---
layout: page
title: Security
permalink: /security/
feature-img: ""
---

<div class="toc">
  

  <ul class="listContent">
    <li><a href="#hwgh">How we got here</a></li>
    <li> <a href="#pis">Problems in security</a></li>
    <li><a href="#wdtfl">Where does the future lead?</a></li>
    <li><a href="#eac">Examples and Code</a></li>
  </ul>
</div>

<h1 id="hwgh">How we got here</h1>

Security used to mean protecting our most valuable assets, often behind locked doors in vaults and safes. Now, thanks to advancements in computing/computer science, our most valued assets are often in the form of digital information.

With the development of the Internet, our computers became part of a network that includes millions of other computers.  We're happy to share information, certainly, but only with people we trust. We want to be sure that the right, accurate information is in the right hands. As more information is stored ditigally, the need for computer security grows. 

But who is developing the security software, and how effective is it? The beauty of open source is that any security software can be analyzed by the public. The public nature of the code means that any holes or flaws can be identified and fixed.

This is preferable to companies and groups creating and using security software that can't be publicly analyzed and checked for flaws. Security software can be successful even if the code is public, provided the security and encryption is done properly.

<h1 id="pis">Problems in security</h1>

The benefits of having access to a nearly infinite amount of knowledge and information should be balanced with our increased vulnerability. Being connected to servers and computers that may have malicious intents is an ongoing problem.

The world's population will inevitably become more computer literate. While that is undoubtedly a good thing overall, it also increases the number of individuals who might potentially lead attacks to steal information or threaten big target systems.


<h1 id="wdtfl">Where does the future lead?</h1>

As more of our information becomes digital, the need for proper security increases. We will likely see more "smart" hardware in our homes and the larger human environment. The very fact that this hardware is "connected" makes your home potentially vulnerable.

Imagine that you're heading off for a much needed winter vacation. You set your smart thermostat to keep your home cool while you're away, and to turn on your heating again in a week--just before you return home. Anyone who can access this information would suspect that there will be no-one in the house that week, leaving it vulnerable to a break-in. Security is needed here, too.

In the long run, there will be an increasing number of attacks by nefariously minded parties. Building all software with security as a basis for usage is already being seen in browsing technologies like SSL and HTTPS.

<h1 id="eac">Examples and Code</h1>


****

**Tor**

![tor]( {{ site.baseurl }}/img/security/tor.png)

Site: [torproject.org](https://www.torproject.org)

Github: [github.com/TheTorProject](https://github.com/TheTorProject)

Tor is one of the more popular pieces of open source security software because of the large community working to make it better and the increasing need to anonymize browsing traffic.

Tor is a browser, like Chrome, that allows you to surf the web, but with the goal of anonymizing your traffic. Tor achieves its anonymity by bouncing your communications around a distributed network of relays run by volunteers around the world which means your physical location is hidden.

<div class="resources" markdown='1'>
* **Tutorials**
	* [Installing Tor on different systems](https://www.torproject.org/docs/installguide.html.en)
	* [A beginner's guide to Tor](http://www.digitaltrends.com/computing/a-beginners-guide-to-tor-how-to-navigate-through-the-underground-internet/)
* **Examples**
	* [Who uses Tor?](https://www.torproject.org/about/torusers.html.en)
</div>


**Onionshare**

![onionshare]( {{ site.baseurl }}/img/security/onionshare.png)

Site: [onionshare.org](https://onionshare.org/)

Github: [github.com/micahflee/onionshare](https://github.com/nnnick/Chart.js/)

Onionshare is a file-sharing service built on top of the distributed network of Tor. Onionshare allows you to make a file on your computer temporarily available to others with a Tor browser through a special URL.

<div class="resources" markdown='1'>
* **Tutorials**
	* [github.com/micahflee/onionshare/blob/master/README.md](https://github.com/micahflee/onionshare/blob/master/README.md)
</div>


**SecureDrop**

SecureDrop is a lot like Dropbox, but for those who want a bit more attention to security. It was developed to allow whistleblowers to submit anonymized material to specific organizations. A few news organization now have their own SecureDrop system to allow information and stories to be submitted securely.

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

Cryptocat is browser extension that runs on Chrome, Firefox, or Safari. Cryptocat works by encrypting all chat before it gets sent to the Cryptocat servers, so only the other people in the chat room with the proper encryption keys can chat with you.

It's a much easier and friendlier experience than some of security focused communication software, but as they say on their website, it's not 100% bulletproof. All software is prone to bugs and holes that can hurt the encryption and make your communication less private.

<div class="resources" markdown='1'>
* **Tutorials**
	* [Video: How to use cryptocat](https://www.youtube.com/watch?v=3BeHR2nfaQg)
	* [Video: Encrypt your chats with cats](https://www.youtube.com/watch?v=Hhv-XyTXmQY)
</div>


**Other security links**

[Why King George III Can Encrypt](https://freedom-to-tinker.com/blog/randomwalker/why-king-george-iii-can-encrypt/) 
[minilock.io](https://minilock.io/)


