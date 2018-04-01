osx-security-awesome [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)[![Travis](https://api.travis-ci.org/kai5263499/osx-security-awesome.svg?branch=master)](https://travis-ci.org/kai5263499/osx-security-awesome)

------------------------------------------------------------------------------------------

A collection of OSX/iOS security related resources

* [**News**](#news)

* [**Hardening**](#hardening)

* [**Malware sample sources**](#malware-sample-sources)

* [**DFIR**](#digital-forensics--incident-response-dfir)

* [**Reverse engineering**](#reverse-engineering)

* [**Presentations and Papers**](#presentations-and-papers)

* [**Virus and exploit writeups**](#virus-and-exploit-writeups)

* [**Useful tools and guides**](#useful-tools-and-guides)

* [**Remote Access Toolkits**](#remote-access-toolkits)

* [**Worth following on Twitter**](#worth-following-on-twitter)


------------------------------------------------------------------------------------------

## News

---------------------------------------------------------------------
### [iOS display bugs](https://docs.google.com/document/d/1TDCVavaqDJCFjcQxZsL6InzHxPEYWwMMMh9QtfRGjbY/edit)
* Regularly updated list of iOS display bugs

### [Mac Virus](https://macviruscom.wordpress.com)
* Frequently updated blog that provides a good summary of the latest unique mac malware.

### [Intego Mac Security Blog](https://www.intego.com/mac-security-blog/)
* Intego's corporate Mac security blog often contains recent and in-depth analysis of mac malware and other security issues

### [Objective-See](https://objective-see.com/blog.html)
* Objective-See's blog often contains in-depth breakdowns of malware they've reverse engineered and vulnarabilities they've discovered.

### [The Safe Mac](http://www.thesafemac.com/)
* Resource to help educate Mac users about security issues. Contains historical as well as timely security updates.

### [Mac Security](https://macsecurity.net/news/)
* Another Mac security blog. This often includes more in-depth analysis of specific threats.

### [OSX Daily](http://osxdaily.com/)
* Not strictly security-specific but it contains jailbreaking information which has security implications

## Hardening
### [Launchd](http://www.launchd.info/)
* Everything you need to know about the launchd service

### [OSX startup sequence](http://osxbook.com/book/bonus/ancient/whatismacosx/arch_startup.html)
* Step-by-step guide to the startup process

### [Google OSX hardening](https://www.usenix.org/conference/lisa13/os-x-hardening-securing-large-global-mac-fleet)
* Google's system hardening guide

### [Run any command in a sandbox](https://www.davd.eu/os-x-run-any-command-in-a-sandbox/)
* How to for using OSX's sandbox system

### [Sandblaster](https://github.com/malus-security/sandblaster)
* Reversing the Apple sandbox
* [Paper](https://arxiv.org/pdf/1608.04303.pdf)

### [OSX El Capitan Hardening Guide](https://github.com/ernw/hardening/blob/master/operating_system/osx/10.11/ERNW_Hardening_OS_X_EL_Captain.md)
* Hardening guide for El Capitan

### [OSX application hardening scorecard](http://cyber-itl.org/blog-1/2016/9/12/a-closer-look-at-the-osx-continuum)
* Useful checklist for hardening systems

### [Hardening hardware and choosing a good BIOS](https://media.ccc.de/v/30C3_-_5529_-_en_-_saal_2_-_201312271830_-_hardening_hardware_and_choosing_a_goodbios_-_peter_stuge)
* Protecting your hardware from "evil maid" attacks

### [Fortify](https://github.com/alichtman/fortify)
* Easily configure Mac security settings from the terminal.

## Malware sample sources
### [Objective-See](https://objective-see.com/malware.html)
* Curated list of malware samples. Use this list if you're looking for interesting samples to reverse engineer
### [Manwe Mac malware feed](http://macmalware.manwe.io)
* Regularly updated fresh mac malware feed
### [Alien Vault](https://www.alienvault.com/blogs/labs-research/os-x-malware-samples-analyzed)
### [Contagio malware dump](http://contagiodump.blogspot.com/2013/11/osx-malware-and-exploit-collection-100.html)

## Digital Forensics / Incident Response (DFIR)
### [Artefacts for Mac OSX](http://sud0man.blogspot.fr/2015/05/artefacts-for-mac-os-x.html?m=1)
* Locations of sensitive files
### [Pac4Mac](https://github.com/sud0man/pac4mac)
* Forensics framework
### [Inception](https://github.com/carmaa/inception)
* Physical memory manipulation
### [Volafox](https://github.com/n0fate/volafox)
* Memory analysis toolkit
### [Mac4n6](https://github.com/pstirparo/mac4n6)
* Collection of OSX and iOS artifacts
### [Keychain analysis with Mac OSX Forensics](https://forensic.n0fate.com/wp-content/uploads/2012/07/Keychain-Analysis-with-Mac-OS-X-Memory-Forensics.pdf)
### [OSX Collector](https://github.com/Yelp/osxcollector)
* Forensics utility developed by Yelp
### [OSX incident response](https://www.youtube.com/watch?v=gNJ10Kt4I9E)
* OSX incident response at GitHub [Slides](https://speakerdeck.com/sroberts/hipster-dfir-on-osx-bsidescincy)
### [iOS Instrumentation without jailbreaking](https://www.nccgroup.trust/uk/about-us/newsroom-and-events/blogs/2016/october/ios-instrumentation-without-jailbreak/)
* How to debug an iOS application that you didn't create
### [Certo](https://www.certosoftware.com/)
* Paid service for analyzing the iTunes backup of your iOS device
### [Blackbag Tech free tools](https://www.blackbagtech.com/resources/freetools.html)
### [OSX (Mac) Memory Acquisition and Analysis Using OSXpmem and Volatility](https://ponderthebits.com/2017/02/osx-mac-memory-acquisition-and-analysis-using-osxpmem-and-volatility/)
### [mac-apt](https://github.com/ydkhatri/mac_apt)
* Mac Artifact Parsing Tool for processing full disk images and extracting useful information
* The author also has a collection of [DFIR scripts](https://github.com/ydkhatri/MacForensics)

## Reverse engineering
### [New OS X Book](http://www.newosxbook.com/)
* Frequently updated book on OSX internals
### [Collection of OSX reverse engineering resources](https://github.com/michalmalik/osx-re-101)
* Another Awesome-style list dedicated to OSX reverse engineering resources
### [The iPhone Wiki](https://www.theiphonewiki.com/wiki/Main_Page)
### [Reverse engineering OSX](https://reverse.put.as/)
### [OSX crackmes](https://reverse.put.as/crackmes/)
* A collection of puzzles to test your reverse engineering skills
### [Introduction to Reverse Engineering Cocoa Applications](https://www.fireeye.com/blog/threat-research/2017/03/introduction_to_reve.html)
* Walkthrough for Coca applications
### [iOS Kernel source](https://github.com/apple/darwin-xnu)
* Source code for iOS kernel
### [Reverse Engineering Challenges](https://challenges.re/)
* Very good list of various crackme challenges that is categorized by level and OS
### [Awesome Reversing](https://github.com/fdivrp/awesome-reversing/)
* Awesome list dedicated to reversing

## Presentations and Papers
### [Writing Bad @$$ Malware for OSX](https://www.youtube.com/watch?v=fv4l9yAL2sU)
* [Slides](https://www.slideshare.net/Synack/writing-bad-malware-for-os-x) and [another related video](https://www.youtube.com/watch?v=oT8BKt_0cJw).
### [Methods of Malware Persistence on OSX](https://www.youtube.com/watch?v=rhhvZnA4VNY)
### [Advanced Mac OSX Rootkits](https://www.blackhat.com/presentations/bh-usa-09/DAIZOVI/BHUSA09-Daizovi-AdvOSXRootkits-SLIDES.pdf)
### [The Python Bytes Your Apple](https://speakerdeck.com/flankerhqd/the-python-bites-your-apple-fuzzing-and-exploiting-osx-kernel-bugs)
* Fuzzing and exploiting OSX kernel bugs
### [Breaking iOS Code Signing](https://papers.put.as/papers/ios/2011/syscan11_breaking_ios_code_signing.pdf)
### [The Apple Sandbox - 5 years later](http://newosxbook.com/files/HITSB.pdf)
### [Practical iOS App Hacking](https://papers.put.as/papers/ios/2012/Mathieu-RENARD-GreHACK-Practical-iOS-App-Hacking.pdf)
### [Behavioral Detection and Prevention of Malware on OS X](https://www.virusbulletin.com/blog/2016/september/paper-behavioural-detection-and-prevention-malware-os-x/)
### [Security on OSX and iOS](https://www.youtube.com/watch?v=fdxxPRbXPsI)
* [Slides](https://www.slideshare.net/nosillacast/security-on-the-mac)

### [Thunderstrike](https://trmm.net/Thunderstrike_31c3)
* [Video](https://www.youtube.com/watch?v=5BrdX7VdOr0), hacking Mac's extensible firmware interface (EFI)
### [Direct Memory Attack the Kernel](https://github.com/ufrisk/presentations/blob/master/DEFCON-24-Ulf-Frisk-Direct-Memory-Attack-the-Kernel-Final.pdf)
### [Don't trust your eye, Apple graphics is compromised](https://speakerdeck.com/marcograss/dont-trust-your-eye-apple-graphics-is-compromised)
* security flaws in IOKit's graphics acceleration that lead to exploitation from the browser
### [Fuzzing and Exploiting OSX Vulnerabilities for Fun and Profit Complementary Active & Passive Fuzzing](https://www.slideshare.net/PacSecJP/moony-li-pacsec18?qid=15552f01-6655-4555-9894-597d62fd803c)
### [Strolling into Ring-0 via I/O Kit Drivers](https://speakerdeck.com/patrickwardle/o-kit-drivers)
### [Juice Jacking](https://www.youtube.com/watch?v=TKAgemHyq8w)
### [Attacking OSX for fun and profit tool set limiations frustration and table flipping Dan Tentler](https://www.youtube.com/watch?v=9T_2KYox9Us)
* [Follow-up from target](https://www.youtube.com/watch?v=bjYhmX_OUQQ)
### [Building an EmPyre with Python](https://www.youtube.com/watch?v=79qzgVTP3Yc)
### [PoisonTap](https://www.youtube.com/watch?v=Aatp5gCskvk)
### [Storing our Digital Lives - Mac Filesystems from MFS to APFS](https://drive.google.com/file/d/0B7Ptn5b5q2FLMUdsLTdUMjBHVzQ/edit)
### [Collection of mac4en6 papers/presentations](https://drive.google.com/drive/folders/0B37-sa0Wh9_TdjVSbzRvMEVGQ2c)
### [The Underground Economy of Apple ID](https://www.youtube.com/watch?v=4acVKs9WPts)
### [iOS of Sauron: How iOS Tracks Everything You Do](https://www.youtube.com/watch?v=D6cSiHpvboI)
### [macOS/iOS Kernel Debugging and Heap Feng Shui](https://github.com/zhengmin1989/MyArticles/blob/master/PPT/DEFCON-25-Min-Spark-Zheng-macOS-iOS-Kernel-Debugging.pdf)
### [Billy Ellis iOS/OSX hacking YouTube channel](https://www.youtube.com/channel/UCk2sx_3FUkKvDGlIhdUQa8A)
### [A Technical Autopsy of the Apple - FBI Debate using iPhone forensics | SANS DFIR Webcast](https://www.youtube.com/watch?v=_q_2mN8U91o)
### [Jailbreaking Apple Watch at DEFCON-25](https://www.youtube.com/watch?v=eJpbi-Qz6Jc)
### [SandScout: Automatic Detection of Flaws in iOS Sandbox Profiles](https://www.trust.informatik.tu-darmstadt.de/fileadmin/user_upload/Group_TRUST/PubsPDF/sandscout-final-ccs-2016.pdf)
* An exploration of the sandbox protections policies
* [Presentation](https://www.youtube.com/watch?v=TnwXEDCIowQ)


## Virus and exploit writeups
### [Leveraging emond on macOS for persistence](https://posts.specterops.io/leveraging-emond-on-macos-for-persistence-a040a2785124)
### [APFS credential leak vulnerability](https://www.mac4n6.com/blog/2018/3/21/uh-oh-unified-logs-in-high-sierra-1013-show-plaintext-password-for-apfs-encrypted-external-volumes-via-disk-utilityapp)
* A flaw in Unified Logs leaks the password for encrypted APFS volumes

### [A fun XNU infoleak](https://bazad.github.io/2018/03/a-fun-xnu-infoleak/)
### Meltdown
* CPU flaw allowing kernel memory to be accessed by hijacking speculative
  execution
* [Proof of concept](https://github.com/gkaindl/meltdown-poc)
* [Apple's statement](https://support.apple.com/en-us/HT208394)
* [Measuring OSX meltdown patches performance](https://reverse.put.as/2018/01/07/measuring-osx-meltdown-patches-performance/)
* [iPhone performance after Spectre patch](https://www.gsmarena.com/spectre_and_meltdown_testing_performance_impact_on_iphone_8_plus-news-29132.php)
### [Why gets your root](https://www.synack.com/2017/11/29/why-gets-you-root/)
* An Apple update introduced a bug where a blank password was set for root,
  allowing attackers to easily gain root access
### [Flashback](https://www.cnet.com/news/more-than-600000-macs-infected-with-flashback-botnet/)
* [Detailed analysis](https://www.intego.com/mac-security-blog/more-about-the-flashback-trojan-horse/)
### [Flashback pt 2](https://www.intego.com/mac-security-blog/flashback-botnet-is-adrift/)
### [iWorm](http://www.thesafemac.com/iworm-method-of-infection-found/)
* [Detailed analysis](https://www.intego.com/mac-security-blog/iworm-botnet-uses-reddit-as-command-and-control-center/)
### [Thunderbolt](http://www.theregister.co.uk/2015/01/08/thunderstrike_shocks_os_x_with_first_firmware_bootkit/)
* Firmware bootkit
### [Malware in firmware: how to exploit a false sense of security](https://www.welivesecurity.com/2017/10/19/malware-firmware-exploit-sense-security/)
* A post on the resurgence of bootkits and how to defend against them
### [Proton RAT](https://www.cybereason.com/blog/labs-proton-b-what-this-mac-malware-actually-does)
* Exploration of a Remote Access Toolkit

### [Mokes](https://thehackernews.com/2016/09/cross-platform-malware.html)
### [MacKeeper](https://www.cultofmac.com/170522/is-mackeeper-really-a-scam/)
### [OpinionSpy](http://www.thesafemac.com/opinionspy-is-back/)
### [Elanor](https://blog.malwarebytes.com/cybercrime/2016/07/new-mac-backdoor-malware-eleanor/)
### [Mac Defender](https://macsecurity.net/view/79/)
### [Wire Lurker](http://researchcenter.paloaltonetworks.com/2014/11/wirelurker-new-era-os-x-ios-malware/)
### [KeRanger](https://techcrunch.com/2016/03/07/apple-has-shut-down-the-first-fully-functional-mac-os-x-ransomware/)
* First OSX ransomware
### [Proof-of-concept USB attack](http://www.ehackingnews.com/2016/09/a-usb-device-can-steal-credentials-from.html)
### [Dark Jedi](https://reverse.put.as/2015/05/29/the-empire-strikes-back-apple-how-your-mac-firmware-security-is-completely-broken/)
### EFI attack that exploits a vulnerability in suspend-resume cycle [Sentinel One write-up](https://www.sentinelone.com/blog/reverse-engineering-mac-os-x/)
### [XAgent Mac Malware Used In APT-28](https://labs.bitdefender.com/2017/02/new-xagent-mac-malware-linked-with-the-apt28/)
* [Samples](http://contagiodump.blogspot.com/2017/02/russian-apt-apt28-collection-of-samples.html)
### [Juice Jacking](https://www.howtogeek.com/166497/htg-explains-what-is-juice-jacking-and-how-worried-should-you-be/)
### [Root a Mac with a Rubber Ducky](http://patrickmosca.com/root-a-mac-in-10-seconds-or-less/)
### [Hacking Mac with Empyre](http://www.lukeager.com/hacking-mac-empyre/)
### [Local Privilege Escalation for macOS 10.12.2 and XNU port Feng Shui](https://jaq.alibaba.com/community/art/show?articleid=781)

### [Ian Beer, Google Project Zero: "A deep-dive into the many flavors of IPC available on OS X."](https://www.youtube.com/watch?v=D1jNCy7-g9k)
* Deep dive into the interprocess communication and its design flaws

### [PEGASUS iOS Kernel Vulnerability Explained](http://sektioneins.de/en/blog/16-09-02-pegasus-ios-kernel-vulnerability-explained.html)
### [Analysis of iOS.GuiInject Adware Library](https://www.sentinelone.com/blog/analysis-ios-guiinject-adware-library/)
### [Broadpwn](https://blog.exodusintel.com/2017/07/26/broadpwn/)
* Gaining access through the wireless subsystem

### [Reverse Engineering and Abusing Apple Call Relay Protocol](https://www.martinvigo.com/diy-spy-program-abusing-apple-call-relay-protocol/)
* Details the discovery of a vulnerability in Apple's Call handoff between mobile and desktop through analyzing network traffic.

### Exploiting the Wifi Stack on Apple Devices
Google's Project Zero series of articles that detail vulnerabilities in the wireless stack used by Apple Devices
  * [Over The Air: Exploiting Broadcom’s Wi-Fi Stack (Part 1)](https://googleprojectzero.blogspot.co.uk/2017/04/over-air-exploiting-broadcoms-wi-fi_4.html)
  * [Over The Air: Exploiting Broadcom’s Wi-Fi Stack (Part 2)](https://googleprojectzero.blogspot.co.uk/2017/04/over-air-exploiting-broadcoms-wi-fi_11.html)
  * [Over The Air - Vol. 2, Pt. 1: Exploiting The Wi-Fi Stack on Apple Devices](https://googleprojectzero.blogspot.com/2017/09/over-air-vol-2-pt-1-exploiting-wi-fi.html)
  * [Over The Air - Vol. 2, Pt. 2: Exploiting The Wi-Fi Stack on Apple Devices](https://googleprojectzero.blogspot.com/2017/10/over-air-vol-2-pt-2-exploiting-wi-fi.html)
  * [Over The Air - Vol. 2, Pt. 3: Exploiting The Wi-Fi Stack on Apple Devices](https://googleprojectzero.blogspot.com/2017/10/over-air-vol-2-pt-3-exploiting-wi-fi.html)

### [ChaiOS bug](https://www.grahamcluley.com/chaios-bug-crash-ios-macos-messages/)
* A message that crashes iMessage
* Looks similar to [previous](https://arstechnica.com/gadgets/2013/08/rendering-bug-crashes-os-x-and-ios-apps-with-string-of-arabic-characters/) [bugs](https://www.intego.com/mac-security-blog/crash-text-message-iphone/) rendering Arabic characters

## Useful tools and guides
### [mac-a-mal](https://github.com/phdphuc/mac-a-mal)
* Automated malware analysis on macOS
* [Paper](https://www.blackhat.com/docs/asia-18/asia-18-Phuc-Mac-A-Mal-An%20Automated%20Framework%20for%20Mac%20Malware%20Hunting-wp.pdf)
### [jrswizzle](https://github.com/rentzsch/jrswizzle)
* method interface exchange
### [MacDBG](https://github.com/blankwall/MacDBG)
* C and Python debugging framework for OSX
### [bitcode_retriever](https://github.com/AlexDenisov/bitcode_retriever)
* store and retrieve bitcode from Mach-O binary
### [machotools](https://github.com/enthought/machotools)
* retrieve and change information about mach-o files
### [onyx-the-black-cat](https://github.com/gdbinit/onyx-the-black-cat)
* kernel module for OSX to defeat anti-debugging protection
### [create-dmg](https://github.com/andreyvit/create-dmg)
* CLI utility for creating and modifying DMG files
### [dmg2iso](https://sourceforge.net/projects/dmg2iso/?source=typ_redirect)
* convert dmg to iso
### [Infosec Homebrew](https://github.com/kai5263499/homebrew-infosec)
* Homebrew tap for security-related utilities
### [Awesome OSX Command Line](https://github.com/herrbischoff/awesome-macos-command-line)
* Collection of really useful shell commands
### [Keychain dump](https://github.com/juuso/keychaindump)
* Dump keychain credentials
### [KnockKnock](https://objective-see.com/products/knockknock.html)
* Listing startup items. Also includes VirusTotal information
### [Lingon-X](https://www.peterborgapps.com/lingon/)
* GUI for launchd
### [Hopper](https://www.hopperapp.com/)
* Excellent OSX debugger (requires license)
### [Symhash](https://github.com/threatstream/symhash)
* Python utility for generating imphash fingerprints for OSX binaries
### [KisMac2](https://github.com/IGRSoft/KisMac2)
* Wireless scanning and packet capturing
### [Passive fuzz framework](https://github.com/SilverMoonSecurity/PassiveFuzzFrameworkOSX)
* Framework is for fuzzing OSX kernel vulnerability based on passive inline hook mechanism in kernel mode
### [Platypus](http://sveinbjorn.org/platypus)
* GUI for generating .app bundles
### [createOSXinstallPkg](https://github.com/munki/createOSXinstallPkg)
* CLI for generating .pkg installers
### [PoisonTap](https://github.com/samyk/poisontap)
### [Chipsec](https://github.com/chipsec/chipsec)
* System firmware checker by Intel
### [Revisiting Mac OS X Kernel Rootkits by Phrack Magazine](http://phrack.org/issues/69/7.html)
* A collection of OSX rootkit ideas
### [iPhone Data Protection in Depth](http://conference.hackinthebox.org/hitbsecconf2011ams/materials/D2T2%20-%20Jean-Baptiste%20Be%CC%81drune%20&%20Jean%20Sigwald%20-%20iPhone%20Data%20Protection%20in%20Depth.pdf)
### [Cycript](http://www.cycript.org/)
* Remote control library for fuzz testing iOS apps
### [ChaoticMarch](https://github.com/synack/chaoticmarch)
* Blackbox fuzz testing for iOS apps (requires jailbreak)
### [iOS backup decrypt script](https://stackoverflow.com/questions/1498342/how-to-decrypt-an-encrypted-apple-itunes-iphone-backup)
* Contains a script for decrypting an encrypted iOS backup archive
### [Remote Packet Capture for iOS Devices](https://useyourloaf.com/blog/remote-packet-capture-for-ios-devices/)
* Use a remote virtual interface to capture packets from a tethered iOS device
* [Python utility](https://thrysoee.dk/iospcap/)
* [Another python utility](https://github.com/gh2o/rvi_capture)

## Remote Access Toolkits
### [Empyre](https://github.com/EmpireProject/EmPyre)
### [Bella](https://github.com/kai5263499/Bella)
### [Stitch](https://nathanlopez.github.io/Stitch/)
### [Pupy](https://github.com/n1nj4sec/pupy)
### [EggShell surveillance tool](https://github.com/neoneggplant/EggShell) - Works on OSX and jailbroken iOS
### [EvilOSX](https://github.com/Marten4n6/EvilOSX) - Pure python post-exploitation toolkit

## Worth following on Twitter
* [@patrickwardle](https://twitter.com/patrickwardle)
* [@objective_see](https://twitter.com/objective_see)
* [@0xAmit](https://twitter.com/0xAmit)
* [@Morpheus______](https://twitter.com/Morpheus______)
* [@osxreverser](https://twitter.com/osxreverser)
* [@liucoj](https://twitter.com/liucoj)
* [@osxdaily](https://twitter.com/osxdaily)
* [@iamevltwin](https://twitter.com/iamevltwin)
* [@claud_xiao](https://twitter.com/claud_xiao)
* [@JPoForenso](https://twitter.com/JPoForenso)
* [@patrickolsen](https://twitter.com/patrickolsen)
* [@cheesecakeufo](https://twitter.com/cheesecakeufo)
