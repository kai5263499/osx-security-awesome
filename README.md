osx-security-awesome [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
========================

A collection of OSX/iOS security related resources

## News

1. [The Safe Mac](http://www.thesafemac.com/)
* [Mac Virus](https://macviruscom.wordpress.com)
* [Mac Security](http://macsecurity.net/news/)
* [OSX Daily](http://osxdaily.com/) - Not secutiy-specific but it contains jailbreaking information which has security implications
* [Intego Mac Security Blog](https://www.intego.com/mac-security-blog/)

## Hardening

1. [Launchd](http://launchd.info/) - Everything you need to know about lunachd
* [OSX startup sequence](http://osxbook.com/book/bonus/ancient/whatismacosx/arch_startup.html)
* [Gogle OSX hardening](https://www.usenix.org/conference/lisa13/os-x-hardening-securing-large-global-mac-fleet)
* [Run any command in a sandbox](https://www.davd.eu/posts/os-x-run-any-command-in-a-sandbox/)
* [OSX El Capitan Hardening Guide](https://github.com/ernw/hardening/blob/master/operating_system/osx/10.11/ERNW_Hardening_OS_X_EL_Captain.md)
* [Hipster DFIR on OSX](https://speakerdeck.com/sroberts/hipster-dfir-on-osx-bsidescincy)

## Malware sources

1. [Alien Vault](https://www.alienvault.com/blogs/labs-research/os-x-malware-samples-analyzed)
* [Objective-See](https://objective-see.com/malware.html)
* [Contagio malware dump](http://contagiodump.blogspot.com/2013/11/osx-malware-and-exploit-collection-100.html)
* [Manwe Mac malware feed](http://macmalware.manwe.io) - Regularly updated fresh mac malware feed
* [exploit-db.com](https://www.exploit-db.com) - Great place to look for local and remote exploits

## Forensics

1. [Artefacts for Mac OSX](http://sud0man.blogspot.fr/2015/05/artefacts-for-mac-os-x.html?m=1) - Locations of sensitive files
* [Pac4Mac](https://github.com/sud0man/pac4mac) - Forensics framework
* [Inception](https://github.com/carmaa/inception) - Physical memory manipulation
* [Volafox](https://github.com/n0fate/volafox) - Memory analysis toolkit
* [Mac4n6](https://github.com/pstirparo/mac4n6) - Collection of OSX and iOS artifacts
* [Keychain analysis with Mac OSX Forensics](https://forensic.n0fate.com/wp-content/uploads/2012/07/Keychain-Analysis-with-Mac-OS-X-Memory-Forensics.pdf)
* [OSX Collector](https://github.com/Yelp/osxcollector) - Forensics utility developed by Yelp

## Reverse engineering

1. [New OS X Book](http://www.newosxbook.com/)
* [Collection of OSX reverse engineering resources](https://github.com/michalmalik/osx-re-101)
* [The iPhone Wiki](https://www.theiphonewiki.com/wiki/Main_Page)
* [Reverse engineering OSX](https://reverse.put.as/)
* [OSX crackmes](https://reverse.put.as/crackmes/) - A collection of puzzles to test your reverse engineering skills
* [Solving crackmes with LDPRELOAD](http://radare.today/posts/solving-crackmes-with-ldpreload/)

## Presentations and Papers
1. [Writing Bad @$$ Malware for OSX](http://www.slideshare.net/Synack/writing-bad-malware-for-os-x) - [Video](https://www.youtube.com/watch?v=fv4l9yAL2sU) and [another related video](https://www.youtube.com/watch?v=oT8BKt_0cJw)
* [Methods of Malware Persistence on OSX](https://www.youtube.com/watch?v=rhhvZnA4VNY)
* [Hack Mac OSX](https://dl.dropboxusercontent.com/u/31995154/HackMACOS-PUB/prez/HackMacOSX-GSDays2012.pdf)
* [Advanced Mac OSX Rootkits](https://www.blackhat.com/presentations/bh-usa-09/DAIZOVI/BHUSA09-Daizovi-AdvOSXRootkits-SLIDES.pdf)
* [The Python Bytes Your Apple](https://speakerdeck.com/flankerhqd/the-python-bites-your-apple-fuzzing-and-exploiting-osx-kernel-bugs) - Fuzzing and exploiting OSX kernel bugs
* [Breaking iOS Code Signing](https://papers.put.as/papers/ios/2011/syscan11_breaking_ios_code_signing.pdf)
* [The Apple Sandbox - 5 years later](http://newosxbook.com/files/HITSB.pdf)
* [Practical iOS App Hacking](https://papers.put.as/papers/ios/2012/Mathieu-RENARD-GreHACK-Practical-iOS-App-Hacking.pdf)
* [Behavioral Detection and Prevention of Malware on OS X](https://www.virusbulletin.com/blog/2016/september/paper-behavioural-detection-and-prevention-malware-os-x/)
* [Security on OSX and iOS](https://www.youtube.com/watch?v=fdxxPRbXPsI) - [Slides](http://www.slideshare.net/nosillacast/security-on-the-mac)

## Useful tools and guides
1. [jrswizzle](https://github.com/rentzsch/jrswizzle) - method interface exchange
* [MacDBG](https://github.com/blankwall/MacDBG) - C and Python debugging framework for OSX
* [bitcode_retriever](https://github.com/AlexDenisov/bitcode_retriever) - store and retrieve bitcode from Mach-O binary
* [machotools](https://github.com/enthought/machotools) - retrieve and change information about mach-o files
* [onyx-the-black-cat](https://github.com/gdbinit/onyx-the-black-cat) - kernel module for OSX to defeat anti-debugging protection
* [create-dmg](https://github.com/andreyvit/create-dmg) - CLI utility for creating and modifying DMG files
* [dmg2iso](https://sourceforge.net/projects/dmg2iso/?source=typ_redirect) - convert dmg to iso
* [Infosec Homebrew](https://github.com/kai5263499/homebrew-infosec) - Homebrew tap for security-related utilities
* [Awesome OSX Command Line](https://github.com/herrbischoff/awesome-osx-command-line) - Collection of really useful shell commands
* [Keychain dump](https://github.com/juuso/keychaindump) - Dump keychain credentials
* [KnockKnock](https://objective-see.com/products/knockknock.html) - Listing startup items. Also includes VirusTotal information
* [Lingon-X](https://www.peterborgapps.com/lingon/) - GUI for launchd
* [Hopper](https://www.hopperapp.com/) - Excellent OSX debugger (requires license)
* [Symhash](https://github.com/threatstream/symhash) - Python utility for generating imphash fingerprints for OSX binaries
* [KisMac2](https://igrsoft.com/en/kismac2/) - Wireless scanning and packet capturing
