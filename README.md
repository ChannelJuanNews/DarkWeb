# DarkWeb

The following README is a step by step guide to accessing the deep/dark web. The knowledge I will show you, and the things you
will be able to access are NOT to be taken lightly. The deep web IS real and it is potentially dangerous if you don't know how to protect yourself. So please exercise caution when entering the forbidden side of the internet. 

##Step 1 - Download TOR

You will need a special browser to access the other side of the internet. [Download TOR here](https://www.torproject.org/download/download.html.en).
Just FYI, TOR stands for `The Onion Router` (because it's hidden in layers). This is the part where you are supposed to go "oooooooh".


#####SPECIAL ANONYMITY TIP:

You should be taking your anonymity very seriously if you are visiting the Deep Web and especially if you are viewing any Darknet Markets. The first thing you should do before doing anything is getting your self a VPN ([Virtual Private Network](https://en.wikipedia.org/wiki/Virtual_private_network)). The ISP’s and Government Agencies are tracking and logging everything you do online now so don’t make it easy for them to catch you. They will be tracking who downloads Tor, the ISP’s are already logging your Tor usage and agencies like the DEA and NSA will be digging through the data with a fine tooth comb. If you use a good VPN that keeps no logs then your internet traffic is completely encrypted so not even your ISP or Law Enforcement will even know that you are using Tor let alone looking at Darknet Markets.


##Step 2 - configure your computer


* Log out of everything. **I MEAN EVERYTHING**
* Turn off JavaScript, Flash and Java

Tor cannot protect your data with active content such as JavaScript, Adobe Flash, Java, QuickTime, ActiveX controls, VBScripts, etc.
because these binary applications run with your user account’s privileges, and may access and share your data.

JavaScript is a powerful browser language which websites can use to track you in ways which is not possible to protect using Tor. Java
and Adobe Flash run in virtual machines which may ignore your system’s configured proxy settings, and thus bypass Tor’s protection to
share your data directly with the websites.

Moreover, they may also store cookies and site’s data separately from the browser and operating system, which may be hard to detect and
delete. By disabling these technologies in your system using Tor, you can achieve a greater level of protection.

* **Delete Cookies AUTOMATICALLY**

Tor does route your network traffic through many relays in order to protect you from traffic analysis. It hides your real identity from the websites using network packets to prevent them from gathering information about you. But websites may use workarounds such as cookies and local data storage to track your online activities, analyze your Internet usage, and detect your real identity.

That is why, you must always drop cookies and site local data while using Tor to protect your privacy. You can also consider using add-on such as Self-Destructing Cookies to automatically delete cookies.

We will install a cookie destroyer before we begin browsing any deep web sites.


##Step 3 - Don't do certain things

* **Don't open ANYTHING you have downloaded while you are still using TOR.**

When started, Adobe Acrobat can initiate a "phone home" to check for an update; this might include an installation-specific ID that could be exploited by an intelligence agency, so your TOR session's address might be associated with your installation. Or the document may have a custom unique certificate with a CRL that identifies the reader when it's checked, or that certificate ID could be monitored at an OCSP server. Or there may be malicious code exploiting an unpatched bug in Word that communicates back to whoever is trying to trace the document.

DOC and PDF documents are likely being called out because they have historically had poor track records with respect to exploitable bugs.

It's possible to configure Acrobat Reader to not intentionally communicate, and to turn off macros and such in Word, but one careless setting and you may be completely exposing yourself. Not opening the documents while online simply avoids most of the potential vulnerabilities, and is very easy advice for people to follow.

* **Don't resize your windows** 

When you resize the TOR window, you are potentially giving information away about what type of computer you own (like how big your screen is) and therefore making it easier for anyone to identify you.


* **Avoid using http websites**

The Onion Router, as the name suggests, is only a traffic router and not a tool to encrypt the network traffic throughout the Internet.
That means Tor anonymizes the origin of your network traffic and encrypts everything inside the Tor network, but it doesn’t encrypt your
Internet traffic outside the network.

* **DON'T use google**

You should not use Google to search the Internet if you care for your privacy. Google is known for collecting information on users’ browsing and search data to facilitate the growth of its ads revenue.

You should consider using alternatives such as Startpage and DuckDuckGo. These services offer search results without logging your IP address and storing cookies on your computer. In simple words, these search engines are anonymity-compliant services, and that is why you should use them while using Tor instead of Google.

##Step 4




#Want Tor to really work?

You need to change some of your habits, as some things won't work exactly as you are used to

##### Use the Tor Browser

Tor does not protect all of your computer's Internet traffic when you run it. Tor only protects your applications that are properly configured to send their Internet traffic through Tor. To avoid problems with Tor configuration, we strongly recommend you use the Tor Browser. It is pre-configured to protect your privacy and anonymity on the web as long as you're browsing with the Tor Browser itself. Almost any other web browser configuration is likely to be unsafe to use with Tor.

#####Don't torrent over Tor

Torrent file-sharing applications have been observed to ignore proxy settings and make direct connections even when they are told to use Tor. Even if your torrent application connects only through Tor, you will often send out your real IP address in the tracker GET request, because that's how torrents work. Not only do you deanonymize your torrent traffic and your other simultaneous Tor web traffic this way, you also slow down the entire Tor network for everyone else.
Don't enable or install browser plugins
The Tor Browser will block browser plugins such as Flash, RealPlayer, Quicktime, and others: they can be manipulated into revealing your IP address. Similarly, we do not recommend installing additional addons or plugins into the Tor Browser, as these may bypass Tor or otherwise harm your anonymity and privacy.

#####Use HTTPS versions of websites

Tor will encrypt your traffic to and within the Tor network, but the encryption of your traffic to the final destination website depends upon on that website. To help ensure private encryption to websites, the Tor Browser includes HTTPS Everywhere to force the use of HTTPS encryption with major websites that support it. However, you should still watch the browser URL bar to ensure that websites you provide sensitive information to display a blue or green URL bar button, include https:// in the URL, and display the proper expected name for the website. Also see EFF's interactive page explaining how Tor and HTTPS relate.

#####Don't open documents downloaded through Tor while online

The Tor Browser will warn you before automatically opening documents that are handled by external applications. DO NOT IGNORE THIS WARNING. You should be very careful when downloading documents via Tor (especially DOC and PDF files) as these documents can contain Internet resources that will be downloaded outside of Tor by the application that opens them. This will reveal your non-Tor IP address. If you must work with DOC and/or PDF files, we strongly recommend either using a disconnected computer, downloading the free VirtualBox and using it with a virtual machine image with networking disabled, or using Tails. Under no circumstances is it safe to use BitTorrent and Tor together, however.

#####Use bridges and/or find company

Tor tries to prevent attackers from learning what destination websites you connect to. However, by default, it does not prevent somebody watching your Internet traffic from learning that you're using Tor. If this matters to you, you can reduce this risk by configuring Tor to use a Tor bridge relay rather than connecting directly to the public Tor network. Ultimately the best protection is a social approach: the more Tor users there are near you and the more diverse their interests, the less dangerous it will be that you are one of them. Convince other people to use Tor, too!



