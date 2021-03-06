![alt tag](https://user-images.githubusercontent.com/24201238/29351849-9c3087b4-82b8-11e7-8fed-350e3b8b4945.png)

# Panopticon Project

## A primer to get you started

Here is a primer to all the things Panopticon Project looks at.

### How do APTs (Advanced Persistent Threats) operate?

[Like government agencies](https://www.youtube.com/watch?v=wP2J9aYM6Oo) according to [The Grugq](https://twitter.com/thegrugq). they are groups, often employed by a government, that are directed to hack into organisations and the devices of individuals that the government they work for deem to hold useful intelligence.

They leverage [infrastucture](https://www.darkreading.com/threat-intelligence/forget-apts-lets-talk-about-advanced-persistent-infrastructure/a/d-id/1330427) like [command and control servers (C&C or C2 servers)](https://whatis.techtarget.com/definition/command-and-control-server-CC-server) to launch [malware](https://en.wikipedia.org/wiki/Malware) from. [IP addresses](https://en.wikipedia.org/wiki/IP_address) of malicious servers are one of the things P2 looks for to define the infrastructure being used by malicious parties.

[Phishing](https://en.wikipedia.org/wiki/Phishing) is often used by malicious parties to trick the recipient into clicking a link, which connects your computer to a C&C server, to download malware. Malware can do all sorts of nasty things, such as [encrypt sections of a computers operating system](https://en.wikipedia.org/wiki/Ransomware), [rendering it unusbale and destroying all the information it contains](https://www.wired.com/story/notpetya-cyberattack-ukraine-russia-code-crashed-the-world/). Malware can [steal credit card data](https://blog.sucuri.net/2017/10/credit-card-stealer-investigation-uncovers-malware-ring.html). Malware can cause [blackouts](https://www.wired.com/2016/03/inside-cunning-unprecedented-hack-ukraines-power-grid/). Blackouts caused by malware aren't common but they have [happened](https://www.wired.com/story/russian-hackers-attack-ukraine/). 

APTs have done all of this in the past, but the main goal of an APT, usually, is not to destroy things or steal money, it is to gather intelligence. The malware you will often see in connection with APTs are [spyware](https://www.malwarebytes.com/spyware/), [infostealers](https://www.symantec.com/security-center/writeup/2000-122016-0558-99) and Remote Access Trojans, commonly known as [RATs](https://en.wikipedia.org/wiki/Remote_access_trojan).

As well as targeting [individuals](https://motherboard.vice.com/en_us/article/kzyg3a/smartphone-malware-nso-group-amnesty-international-saudi-arabia) that can lead to harm or even death if sensitive information, like someone's location, is passed to the wrong parties, APTs can be used by governments to sway a rival country's [elections](https://www.theregister.co.uk/2018/07/20/microsoft_fancy_bear_warning/) or [cripple their critical infrastructure](https://www.wired.com/story/russian-hacking-teams-infrastructure/). 

### Why would a corporation put you under surveillance?

Corporations collect data about people to [build profiles that they then sell](https://www.youtube.com/watch?v=3ABaGEWjFIg). These profiles are valuable as information is often easy to collect, providing a very cheap revenue stream, and profiles inform how [advertising is targeted](https://www.washingtonpost.com/apps/g/page/business/how-targeted-advertising-works/412/?noredirect=on). People talk about the [attention encomy](https://www.vidyard.com/blog/attention-economy-marketers-killing-not-capturing-attention/), and it is [bad](https://techcrunch.com/2017/07/30/the-attention-economy-created-by-silicon-valley-is-bankrupting-us/), but we live in something worse. We live in a [surveillance economy](https://medium.com/the-graph/algorithms-dictators-the-surveillance-economy-e89139d42214). 

This is not just about economics either. Companies like [Palantir](https://www.theverge.com/2018/2/27/17054740/palantir-predictive-policing-tool-new-orleans-nopd) have run predictive crime systems on U.S. soil, generating priority lists for local law enforcement based on the probability, generated from a [black box](https://en.wikipedia.org/wiki/Black_box), that someone will commit a crime. Cambridge Analytica was caight on tape claiming they [stage managed the 2017 Kenyan elections](https://www.reuters.com/article/us-facebook-cambridge-analytica-kenya/cambridge-analytica-stage-managed-kenyan-presidents-campaigns-uk-tv-idUSKBN1GV300) in which [ninety two Kenyans lost their lives](https://qz.com/africa/1233084/channel-4-news-films-cambridge-analytica-execs-saying-they-staged-kenya-uhuru-kenyatta-elections/). 

### What are nation states really doing online?

Turns out, [a lot](https://snowdenarchive.cjfe.org/greenstone/cgi-bin/library.cgi). In recent years we have had unpreciented glimpses into [what nation states are doing online](https://www.youtube.com/watch?v=0hLjuVyIIrs), sometimes from [surprising sources](https://www.nytimes.com/2017/11/12/us/nsa-shadow-brokers.html). Edward Snowden leaked documents that outlined the NSA's default position of collecting vast amounts and data and storing it, often targetting U.S. citizens in violation of the U.S. constitution, as part of the [PRISM Program](https://en.wikipedia.org/wiki/PRISM_(surveillance_program)). An APT that called itself [TheShadowBrokers](https://steemit.com/shadowbrokers/@theshadowbrokers/repost-theshadowbrokers-message-1-august-2016) releaesd a number of exploits targeting [previously unknown vulnerabilities](https://arstechnica.com/information-technology/2017/04/nsa-leaking-shadow-brokers-just-dumped-its-most-damaging-release-yet/). 

Among them were [exploits](https://arstechnica.com/information-technology/2017/04/nsa-leaking-shadow-brokers-just-dumped-its-most-damaging-release-yet/) for the [SWIFT system](https://en.wikipedia.org/wiki/Society_for_Worldwide_Interbank_Financial_Telecommunication), the global banking communication system. One of the exploits released by TheShadowBrokers was [EternalBlue](https://en.wikipedia.org/wiki/EternalBlue) which went on to become the [engine that propelled Wannacry and NotPetya around the world](https://www.theguardian.com/technology/2017/dec/30/wannacry-petya-notpetya-ransomware). While the [United States](https://www.forbes.com/sites/thomasbrewster/2017/05/12/nsa-exploit-used-by-wannacry-ransomware-in-global-explosion/#2ee611dfe599) wrote EternalBlue, it's believed the rest of both Wannacry and NotPetya was authored by [North Korea](https://www.washingtonpost.com/world/national-security/the-nsa-has-linked-the-wannacry-computer-worm-to-north-korea/2017/06/14/101395a2-508e-11e7-be25-3a519335381c_story.html?utm_term=.f3581abb9f00) and [Russia](https://www.washingtonpost.com/world/national-security/russian-military-was-behind-notpetya-cyberattack-in-ukraine-cia-concludes/2018/01/12/048d8506-f7ca-11e7-b34a-b85626af34ef_story.html?utm_term=.0d6fb0727559) respectively. Other global malware incidents attributed to nation states include [Stuxnet](https://www.wired.com/2014/11/countdown-to-zero-day-stuxnet/) and [Bad Rabbit](https://www.zdnet.com/article/bad-rabbit-ten-things-you-need-to-know-about-the-latest-ransomware-outbreak/). The sophistication of the malware, on many levels demonstrate the kind of capabilities nation states have online.

### What is this "Cyber War" I keep hearing about?
Cyber is a silly term, but it seems to have caught on and now it is a new domain of warfare. [Cyber War](https://www.wired.com/story/cyberwar-guide/) is war over the medium of the internet. And everything these days is connected to the internet.

### Other topics you might be wondering about as you get started

* [Social media platforms, inclusion and exclusion online](https://www.youtube.com/watch?v=pO-brBVRyN8&index=12&list=PLYiaJo7rYNXLQSEAa2RdyyiS28Ke2Rl60)
* [Operational Security (OPSEC)](https://medium.com/@thegrugq/twitter-activist-security-7c806bae9cb0)

If you would like more topics added, please [create an issue](https://github.com/Panopticon-Project/panopticon-Primer/issues) or email panopticonproject at protonmail.com
