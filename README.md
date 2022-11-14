<div align="center">

<!-- title -->

<!--lint disable match-punctuation-->
<!--lint ignore no-dead-urls-->

# Awesome Reading List 
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
![GitHub last commit](https://img.shields.io/github/last-commit/EanNewton/Awesome-Reading-List) [![lint](https://github.com/EanNewton/Awesome-Reading-List/actions/workflows/lint.yaml/badge.svg)](https://github.com/EanNewton/Awesome-Reading-List/actions/workflows/lint.yaml) [![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

<!-- subtitle -->
"First – I’m very tired of posts that complain about how people are “wrong” about how a given piece of technology works without explaining why it’s helpful to be “right”." --Julia Evans


<!-- image -->

<a href="https://github.com/EanNewton/Awesome-Reading-List" target="_blank" rel="noopener noreferrer">
  <img src="https://github.com/EanNewton/Awesome-Reading-List/blob/main/image.jpg" />
</a>

<!-- description -->

Articles, blog posts, web apps, videos, and other tidbits of STEM related awesomeness that can be read over a lunch break. Curated and opinionated, I have and continue to add things over time when I find them particularly useful, unique, or entertaining. Never stop learning.


</div>

<!-- TOC -->

<!--lint disable awesome-toc-->
## Contents
- [main() {](#main-)
  - [Databases](#databases)
  - [Design and UI](#design-and-ui)
  - [DevOps / SRE](#devops--sre)
  - [Documentation](#documentation)
  - [Encryption](#encryption)
  - [Food and Cooking](#food-and-cooking)
  - [Fun Stuff That Doesn't Quite Fit Elsewhere](#fun-stuff-that-doesnt-quite-fit-elsewhere)
  - [Git / GitHub / GitLab](#git--github--gitlab)
  - [Linux / Unix / BSD](#linux--unix--bsd)
  - [Linux Class](#linux-class)
  - [Mathematics](#mathematics)
  - [Microsoft](#microsoft)
  - [Network](#network)
  - [Places to Find Things](#places-to-find-things)
  - [Python](#python)
  - [Reverse Engineering & Hardware Hacking](#reverse-engineering--hardware-hacking)
  - [Security](#security)
  - [Software Development](#software-development)
  - [System Development](#system-development)
  - [Videos](#videos)
  - [Vintage & Historical](#vintage--historical)
  - [Web](#web)
- [}](#)
- [Reference materials](#reference-materials)
  - [Algorithm & Logic References](#algorithm--logic-references)
  - [Data Structures References](#data-structures-references)
  - [Hardware](#hardware)
  - [Lists](#lists)
  - [Organizations](#organizations)
  - [Standards](#standards)
  - [RFC](#rfc)
- [Follow](#follow)
<!--lint enable awesome-toc-->


# BUY ME A COFFEE


I love teaching others and seeing the community grow. Time is limited but donations will allow me to to help the community more. How useful was this to you? If it  was I would be humbly grateful for your donation.🙏

[PayPal](https://www.paypal.com/donate/?hosted_button_id=BJ234WR6EKBDG) - to help me help you better.

Thank you! May you be rich as Crassus and happy as Buddha! :)

<!-- CONTENT -->
---
## main() {

This list is loosely organized into categories, not everything fits neatly and I have in cases chosen arbitrarily. Articles within sections are organized alphabetically. All links to other lists can be found under Reference Materials.

The format for an entry is:

`- Article Link - A brief description. (time to read, publication date).`

The time to read is based on the median between a reading speed of 183 words per minute (wpm) and 234 wpm from [The Read Time](https://thereadtime.com/).

Contributions are welcomed, please read the guidelines for doing so.

### What's New?

- [C Isn't A Programming Language Anymore](https://faultlore.com/blah/c-isnt-a-language/) - I wouldn’t [mind] if C was actually a programming language. Unfortunately, it’s not, and it hasn’t been for a long time. (20 minutes, 2022).
- [93% of Paint Splatters are Valid Perl Programs](https://www.mcmillen.dev/sigbovik/) - In this paper, we aim to answer a long-standing open problem in the programming languages community: is it possible to smear paint on the wall without creating valid Perl? (2 minutes, 2019).

### Databases

- [Data Denormalization is Broken](https://lironshapira.medium.com/data-denormalization-is-broken-7b697352f405) - Why it’s impossible to write good application-layer code for everyday business logic. (20 minutes, 2016).
- [Postgres Hashing](https://www.postgresql.org/docs/current/hash-intro.html) - A technical overview of what hash indexes are and how they are implemented. (5 minutes, 2022).
- [Re-introducing Hash Indexes in PostgreSQL](https://hakibenita.com/postgresql-hash-index) - There is another type of index you are probably not using, and may have never even heard of. It is wildly unpopular, and until a few PostgreSQL versions ago it was highly discouraged and borderline unusable, but under some circumstances it can out-perform even a B-Tree index. (15 minutes, 2021).
- [Spending $5k to Learn How Database Indixes Work](https://briananglin.me/posts/spending-5k-to-learn-how-database-indexes-work/) - How a simple design choice resulted in thousands of dollars in server costs per day. (4 minutes, 2021).
- [The Ultimate SQLite Extension Set](https://antonz.org/sqlean/) - Something like a standard library in Python or Go, only for SQLite. (3 minutes, 2021).
- [Twitter's Snowflake ID](https://blog.twitter.com/engineering/en_us/a/2010/announcing-snowflake) - Twitter needed something that could generate tens of thousands of ids per second in a highly available manner. This naturally led us to choose an uncoordinated approach. (3 minutes, 2010).
- [UUID's and ULID's](https://sudhir.io/uuids-ulids) - What UUIDs and ULIDs are under the hood, and how to encode and use them. (15 minutes).
- [UUID to UTF-8 in Ruby](https://gist.github.com/snikch/6969879) - Ruby script to Convert a UUID to UTF-8 encoding to visually shorten.

### Design and UI

Rule #0: Be awesome to one another and party on.

- [Collaborate with kindness: basic etiquette for Slack](https://slack.com/intl/en-gb/blog/collaboration/etiquette-tips-in-slack) - Reduce notifications and minimize distractions with these best practices for channels and direct messages. (6 minutes, 2022).
- [Fueling the Creation of New Electronic Curbcuts](http://www.accessiblesociety.org/topics/technology/eleccurbcut.htm) - Unusual things happen when products are designed to be accessible to people with disabilities. (13 minutes, 1999).
- [On Names](https://emmah.net/names.html) - You need to fix how your software and systems refer to people, because names change. (1 minute).
- [Privacy By Design: What Needs to be Done, How to do It, and How to Sell It to your Boss](https://medium.com/greater-than-experience-design/privacy-by-design-7b1165d045e0) - Could you imagine the outrage the public would experience if they found out that the postal service was holding their mail hostage and selling it to whoever was willing to pay? (21 minutes, 2018).
- [Trans-inclusive Design](https://alistapart.com/article/trans-inclusive-design/) - Covers issues touching on content, images, forms, databases, IA, privacy, and AI—just enough to get you thinking. (12 minutes, 2019).

### DevOps / SRE

- [A Few Ops Lessons](https://www.netmeister.org/blog/ops-lessons.html) - A few lessons in operations that we all (eventually) (have to) learn, often the hard way. Why things are the way they are, or what the lessons mean is left to the reader to interpret, agree, or disagree with. (6 minutes, 2020).
- [How complex systems fail](https://how.complexsystems.fail/) - The seminal treatise by Richard Cook. Being a Short Treatise on the Nature of Failure; How Failure is Evaluated; How Failure is Attributed to Proximate Cause; and the Resulting New Understanding of Patient Safety. (8 minutes).
- [The hows and whys of effective production-readiness reviews](https://www.infoq.com/articles/incidents-prr-psychological-safety/) - How to build production readiness reviews (PRR) with emphasis on context and psychological safety. (19 minutes, 2022).

### Documentation

- [Content Workflow Using GitHub and Markdown](https://www.portent.com/blog/content/content-with-github-markdown.htm) - We publish digital content. We write and create for the internet and screens. But our content workflow dates back to the days of desktop publishing. (25 minutes, 2018).
- [Hemingway App](https://hemingwayapp.com/) - The app highlights lengthy, complex sentences and common errors.
- [heyawhite/tech-writing-tools](https://github.com/heyawhite/tech-writing-tools) - This repository contains lists of suggested tools for technical writers. (2022).
- [How to Release a New Open Source Project](https://opensource.zalando.com/docs/releasing/index/) - This is the process for how Zalando employees release a new open source project. (5 minutes).
- [kylelobo/The-Documentation-Compendium](https://github.com/kylelobo/The-Documentation-Compendium) - Various templates & tips on writing high-quality documentation that people want to read. (2021).
- [Markdown](https://daringfireball.net/projects/markdown/) - John Gruber's original spec for Markdown. (5 minutes, 2004).
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet) - A quick reference and showcase of *Markdown Here's* version of GitHub-flavored Markdown. (7 minutes, 2017).
- [Markdown Tutorial](https://www.markdowntutorial.com/) - Learn Markdown in 10 minutes by doing.
- [PharkMillups/beautiful-docs](https://github.com/PharkMillups/beautiful-docs) - A list of docs and other developer resources that myself and others find particularly useful, well-written, and otherwise "beautiful." May they serve to inspire you when writing and designing yours. (2022).
- [Whos behind this website? A checklist for journalists](https://www.cjr.org/tow_center/whos-behind-this-website-a-checklist.php) - This checklist is meant to be used as a reporting tool to help journalists and researchers when trying to find out who published a website. (5 minutes, 2022).
- [Why I Use Markdown, & You Should Too](https://www.portent.com/blog/content/use-markdown-now.htm) - I once had to convert a Word document to a web page. Once. (4 minutes, 2016).
- [Writing on GitHub](https://docs.github.com/en/get-started/writing-on-github) - GitHub Docs official guide to Markdown and editing. 


### Encryption

- [CryptoPals](https://cryptopals.com/) - A set of 48 practical programming exercises that Thomas Ptacek and his team at Matasano Security have developed as a kind of teaching tool (and baited hook). This is a different way to learn about crypto than taking a class or reading a book.
- [DRM is not to prevent copyright violations](https://web.archive.org/web/20140906214521/https://plus.google.com/+IanHickson/posts/iPmatxBYuj2) - The purpose of DRM is to give content providers leverage against creators of playback devices. (5 minutes, 2013).
- [Extracting Randomness from Text](https://prgomez.com/randomness-from-text/) - While the running key cipher can be broken easily, BookPad offers a level of security comparable to that of a one-time-pad. In this article, I try to explain why in layman’s terms. (20 minutes, 2016).
- [Snake Cipher](https://prgomez.com/snake-cipher/) - Using this cipher is so much like playing the old “snake” video game, I’ve called it just that: Snake. (10 minutes, 2016).

### Food and Cooking

- [Healthy Soil is the real key to feeding the world](https://worldsensorium.com/healthy-soil-is-the-real-key-to-feeding-the-world/) - Agricultural myths hinder recognizing the potential to restore degraded soils to feed the world using fewer agrochemicals. (5 minutes, 2022).
- [One of the most famous Victorian dishes is a lie](https://www.atlasobscura.com/articles/victorian-brown-windsor-soup) - Brown Windsor soup was reportedly a favorite of the Queen. The only problem? It may not have existed. (6 minutes, 2022).

### Fun Stuff That Doesn't Quite Fit Elsewhere

- [52 Things I learned in 2021](https://kottke.org/22/01/52-things-i-learned-in-2021-1) - For the last few years, I’ve been a fan of Tom Whitwell’s annual list of 52 things he learned during the past year.
- [52 things I learned in 2021](https://medium.com/magnetic/52-things-i-learned-in-2021-8481c4e0d409) - 17) The battery in the new electric Hummer will weigh almost as much as an original Land Rover. 18) Most ransomware is designed not to install on computers that have Russian or Ukrainian language keyboards.
- [A few things I learned live streaming](https://dantepfer.com/blog/?p=1005) - “Thanks” to the pandemic, I’ve spent much more time figuring out how to deal with video and live streaming than I ever thought I would. It’s turned out to be a surprisingly rewarding experience.
- [Amateurs vs Professionals](https://fs.blog/amateurs-professionals/) - Why is it that some people seem to be hugely successful and do so much, while the vast majority of us struggle to tread water? The answer is complicated and likely multifaceted.
- [Amish Hackers](https://kk.org/thetechnium/amish-hackers-a/) - Amish lives are anything but anti-technological. I have found them to be ingenious hackers and tinkers, the ultimate makers and do-it-yourselfers and surprisingly pro technology.
- [Crazy Eddie, the popular electronics chain that scammed America](https://thehustle.co/the-popular-electronics-chain-that-scammed-america/) - On September 13, 1984, as stocks wavered through a bear market, a regional electronics chain held a hyped initial public offering.
- [DARPA shows off 1.8 gigapixel surveillance drone](https://www.extremetech.com/extreme/146909-darpa-shows-off-1-8-gigapixel-surveillance-drone-can-spot-a-terrorist-from-20000-feet) - These 1.8 gigapixels are provided via 368 smaller sensors, which DARPA/BAE says are just 5-megapixel smartphone camera sensors. (3 minutes, 2013).
- [Exploring the software that flies SpaceX](https://stackoverflow.blog/2021/12/27/dont-push-that-button-exploring-the-software-that-flies-spacex-starships/) - Steven Gerding, Dragon’s software development lead, speaks about the special challenges software development has for SpaceX’s many missions.
- [Fun with File Formats](https://blogs.loc.gov/thesignal/2021/12/fun-with-file-formats/) - To help you satisfy your need for in-depth technical, and perhaps more than a bit nerdy, knowledge about all things digital file formats.
- [How bad is QWERTY really?](https://www.erichgrunewald.com/posts/how-bad-is-qwerty-really-a-review-of-the-literature-such-as-it-is/) - One man's journey to deal with RSI.
- [How GPS works](https://ciechanow.ski/gps/) - Interactive website detailing how GPS actually works.
- [How rocket engines are cooled](https://everydayastronaut.com/engine-cooling-methodes/) - Gases inside an engines combustion chamber can reach ~3,500 K – which is about half as hot as the surface of the Sun – certainly above the melting point of most materials. Engines need to reach this temperature in order to function correctly, but how can they survive this?
- [The first Intel fab](https://thechipletter.substack.com/p/the-first-intel-fab) - A little history of Intel's early years. (3 minutes).
- [Japan's paper culture](https://www.jetpens.com/blog/Japan-s-Paper-Culture/pt/998) - Why paper is so important in Japan.
- [Mall Ninjas](https://lonelymachines.org/mall-ninjas/) - It all started back at the end of the halcyon summer of 2001, and his posts have created a certain urban legend that many refer to as the Mall Ninja.
- [Network Protocols in Orbit: Building a Space ISP](https://stackoverflow.blog/2021/05/11/building-a-space-based-isp/) - There are requirements that make software engineers sweat. Massive distribution to thousands of nodes. High reliability and availability. Multiple distinct platforms. Rapid network growth.
- [Notes from the end of a very long life](https://www.nytimes.com/2022/01/06/nyregion/ruth-willig-oldest-new-yorkers.html) - With the death of Ruth Willig at 98, a Times series on a set of the oldest New Yorkers — chronicled over seven years in 21 articles — offers their lessons on living with loss.
- [QArt Codes](https://research.swtch.com/qart) - Embedding images into QR codes.
- [QR Codes in Japan](https://blog.cliffano.com/2009/05/18/qr-code-usage-in-japan/) - Photos and samples of different creative QR codes found around Japan.
- [Roguelikes: The misnamed genre](https://zorbathut.livejournal.com/827037.html) - Roguelikes aren’t about dungeons. They’re not about text-based graphics, or random artifacts, or permadeath.
- [Secret military telephone buttons](https://computer.rip/2022-01-01-secret-military-telephone-buttons.html) - The military has four extra telephone buttons that they don't tell us about.
- [Terran Republic Interstellar Plotting System](https://github.com/BoatrightTBC/trips) - TRIPS (the Terran Interstellar Plotter System) is intended to be a flexible stellar cartography system designed for the needs of SF fans and writers.
- [Unusual Wikipedia Articles](https://en.wikipedia.org/wiki/Wikipedia:Unusual_articles) - These articles are verifiable, valuable contributions to the encyclopedia, but are a bit odd, whimsical, or something one would not expect to find in Encyclopædia Britannica.
- [When SimCity got serious](https://obscuritory.com/sim/when-simcity-got-serious/) - Maxis didn’t want to make professional simulation games. But for two brief, strange years, they did.

### Git / GitHub / GitLab

- [Configuring issue templates for your respository](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository) - You can customize the templates that are available for contributors to use when they open new issues in your repository.
- [jstrieb/github-stats](https://github.com/jstrieb/github-stats) - Pretty print your projects' most used languages.
- [Merging vs Rebasing](https://www.atlassian.com/git/tutorials/merging-vs-rebasing) - The `git rebase` command has a reputation for being magical Git voodoo that beginners should stay away from.
- [Oh Shit, Git!?!](https://ohshitgit.com/) - Git is hard: So here are some bad situations I've gotten myself into, and how I eventually got myself out of them in plain english. (3 minutes, 2022).


### Linux / Unix / BSD

- [A cozy nest for your scripts](https://ianthehenry.com/posts/a-cozy-nest-for-your-scripts/) - Take a peek at your ~/bin. How many scripts there have names like process or run or deploy? How many of them have you forgotten ever writing? (5 minutes, 2022).
- [A Survey of UNIX init schemes](https://arxiv.org/pdf/0706.2748.pdf) - (June 2007) This document describes existing solutions that implement the init process and/or init
scripts in Unix-like systems. These solutions range from the legacy and still-in-use BSD
and SystemV schemes, to recent and promising schemes from Ubuntu, Apple, Sun and
independent developers.
- [casync - A Tool for Distributing File System Images](http://0pointer.net/blog/casync-a-tool-for-distributing-file-system-images.html) - It combines the idea of the rsync algorithm with the idea of git-style content-addressable file systems, and creates a new system for efficiently storing and delivering file system images, optimized for high-frequency update cycles over the Internet. 
- [Create a user called '0day' and get root privs!](https://www.theregister.com/2017/07/05/linux_systemd_grants_root_to_invalid_user_accounts/) - Curiously, if systemd encounters an invalid name in a unit file, like "0day," it will ignore the parameter and create the requested service. But it will run the unit with root privileges instead of rejecting it or adopting more restrictive permissions.
- [debootstrap](https://wiki.debian.org/Debootstrap) - CLI debootstrap is a tool which will install a Debian base system into a subdirectory of another, already installed system.
- [dm-verity](https://www.kernel.org/doc/html/latest/admin-guide/device-mapper/verity.html) - Device-Mapper’s “verity” target provides transparent integrity checking of block devices using a cryptographic digest provided by the kernel crypto API.
- [Gentoo is Rice](https://www.shlomifish.org/humour/by-others/funroll-loops/Gentoo-is-Rice.html) - Welcome, this page is dedicated to the Linux Community's greatest ambassadors, Gentoo users. Like the annoying teenager next door with a 90hp import sporting a 6 foot tall bolt-on wing, Gentoo users are proof that society is best served by roving gangs of armed vigilantes, dishing out swift, cold justice with baseball bats to those fucking ricer bastards.
- [How X Window Managers Work, and How to Write One (Part 1)](https://jichu4n.com/posts/how-x-window-managers-work-and-how-to-write-one-part-i/) - Basic Concepts.
- [How X Window Managers Work, and How to Write One (Part 2)](https://jichu4n.com/posts/how-x-window-managers-work-and-how-to-write-one-part-ii/) - Introduction, Setup & Teardown, Initialization, Event Loop.
- [How X Window Managers Work, and How to Write One (Part 3)](https://jichu4n.com/posts/how-x-window-managers-work-and-how-to-write-one-part-iii/) - Interaction with Application Windows.
- [JACK Audio Connection Kit](https://jackaudio.org/) - Have you ever wanted to take the audio output of one piece of software and send it to another? How about taking the output of that same program and send it to two others, then record the result in the first program? Or maybe you’re a programmer?
<!--lint ignore awesome-spell-check-->
- [Making Mac OS X UNIX compliant](https://www.quora.com/What-goes-into-making-an-OS-to-be-Unix-compliant-certified) - Someone asks, "What goes into making an OS to be Unix compliant certified?" and Terry Lambert, an Apple Kernel developer, answers.
- [mkosi - A Tool for Generating OS Images](http://0pointer.net/blog/mkosi-a-tool-for-generating-os-images.html) - CLI mkosi stands for Make Operating System Image, and is a tool for precisely that: generating an OS tree or image that can be booted.
- [mkosi - GitHub Repo](https://github.com/systemd/mkosi) - Source code for above.
- [No easter eggs in cURL](https://daniel.haxx.se/blog/2021/12/06/no-easter-eggs-in-curl/) - The maintainer of cURL explains why it contains no easter eggs, and why that is a good thing.
- [Setting the record straight: containers vs Zones vs Jails vs VMs](https://blog.jessfraz.com/post/containers-zones-jails-vms/) - The Design of Solaris Zones, BSD Jails, VMs and containers are very different.
- [Stop writing shell scripts](https://pythonspeed.com/articles/shell-scripts/) -  Unless you are very careful from day one, any shell script above a certain complexity level is almost guaranteed to be buggy… and retrofitting the correctness features is quite difficult.
- [Technical Reasons to choose FreeBSD over Linux](https://unixsheikh.com/articles/technical-reasons-to-choose-freebsd-over-linux.html) - (2020) Survey of technical features in FreeBSD vs Linux operating systems at the time.
- [The growth of command line options: 1979 - present](https://danluu.com/cli-complexity/) - On ubuntu 17, if you read the manpage for coreutils ls, you don’t get a nice summary of options, but you’ll see that ls has 58 options (including --help and --version).
- [The important UNIX idea of the Virtual File System](https://utcc.utoronto.ca/~cks/space/blog/unix/VFSImportance) - Then Sun came up with NFS and found themselves with a problem; their kernel needed to support two different filesystems at once, the BSD FFS/UFS for local disks and NFS for networked filesystems.
- [The real motivation behind systemd](https://unixsheikh.com/articles/the-real-motivation-behind-systemd.html) - (2018) A mix between an OpEd and an inside historical look at systemd.
- [WirePlumber: The New PipeWire Manager](https://fedoramagazine.org/wireplumber-the-new-pipewire-session-manager/) - A session manager for PipeWire, an alternative to JACK or ALSA.

### Linux Class

More focused on learning practical *nix skills than the above section.

- [chroot](https://wiki.debian.org/chroot) - On Unix-like operating systems chroot is an operation that changes the apparent root directory for the current running process and its children.
- [Get Hardware Info](https://opensource.com/article/19/9/linux-commands-hardware-information) - How to find your hardware specs.
- [Hard & Soft Links](https://unix.stackexchange.com/questions/340676/use-cases-for-hardlinks/340710#340710) - What are the different types of file links and when should you use them?
- [How Brace Expansion Works](https://www.howtogeek.com/725657/how-to-use-brace-expansion-in-linuxs-bash-shell/) - What's the deal with those {funky} commands you sometimes see?
- [How to use dig](https://jvns.ca/blog/2021/12/04/how-to-use-dig/) - The CLI tool for finding DNS.
- [Quick Grep](https://github.com/adrianscheff/quick-grep) - Cheatsheet for grep, the CLI tool for searching text.
- [rclone: From Basics to Encryption](https://www.andyibanez.com/posts/rclone-basics-encryption/) - Your zero-to-hero guide getting started with rclone.
- [Simple awk](https://github.com/adrianscheff/simple-awk) - A quick reference to the AWK scripting language.
- [Special Characters in BASH](https://www.howtogeek.com/439199/15-special-characters-you-need-to-know-for-bash/) - Why do you sometimes see characters like ~ or * in commands? What do they mean?
- [Text Processing Recipes](https://github.com/adrianscheff/text-processing-recipes-linux) - Linux text processing reference & recipes. Featuring: `vim, tr, cat, tac, sort, shuf, seq, pr, paste, fmt, cut, nl, split, csplit, sed, awk, grep` and regex.
- [Useful Sed](https://github.com/adrianscheff/useful-sed) - Useful sed tips, techniques and tricks for daily usage.
- [Wizardly Tips for Vim](https://github.com/adrianscheff/wizardly-tips-vim) - A fast way to benefit from vim's power. Ideally you should read a good book and the `:h` section. But if you're in a hurry this should serve you well.
- [X11: Disable Cursor](https://web.archive.org/web/20210420050749/http://www.noah.org/wiki/cursor_disable_in_X11) - When working with touch-screen interfaces or embedded systems you often don't want or need the mouse cursor. 

### Mathematics

- [High dimenionsal sphere spilling out of a high dimensional cube](https://stanislavfort.github.io/blog/sphere-spilling-out/) - Make a square, split each side into two halves, producing four cells. Put a circle into each cell such that it fills it completely. There is a small gap right in the middle of the square. Put a circle there again such that it touches the other four circles. The central circle is obviously inside the square, right? Yes, but only if the dimension you are in is D ≤ 9.
- [Matrix multiplication](http://matrixmultiplication.xyz/) - Online matrix calculator app.
- [The Flaw of Averages](https://hbr.org/2002/11/the-flaw-of-averages) - Consider the case of the statistician who drowns while fording a river that he calculates is, on average, three feet deep. If he were alive to tell the tale, he would expound on the “flaw of averages,” which states, simply, that plans based on assumptions about average conditions usually go wrong. (5 minutes, 2002)

### Microsoft

- [How to Download Outlook Emails](https://www.kerneldatarecovery.com/blog/how-to-download-emails-from-microsoft-outlook/) - Step-by-step with pictures, how to export a user's Outlook mailbox. (2021).
- [Fantastic Rootkits and Where to Find Them](https://www.cyberark.com/resources/threat-research-blog/fantastic-rootkits-and-where-to-find-them-part-1) - In this first part, we will focus on some implementation examples of basic rootkit functionality and the basics of kernel driver development. (20 minutes, 2022).
- [Windows 8: Show/Hide Administrative Tools](https://web.archive.org/web/20150905204425/http://www.eightforums.com/tutorials/4861-administrative-tools-hide-show-windows-8-a.html)
- [Windows 10 Hotkeys](https://support.microsoft.com/en-us/windows/keyboard-shortcuts-in-windows-dcc61a57-8ff0-cffe-9796-cb9706c75eec#WindowsVersion=Windows_10)
- [Windows 10: System Requirements](https://support.microsoft.com/en-us/windows/windows-10-system-requirements-6d4e9a79-66bf-7950-467c-795cf0386715)
- [Robocopy: Documentation](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/robocopy) - The official Microsoft docs for all `robocopy` options.
- [Robocopy: Pros and Cons to the /j option](https://superuser.com/questions/1114311/are-there-any-pros-cons-to-the-j-robocopy-option-unbuffered-copying) - Robocopy has a `/j` option for unbuffere I/O. What (if any) downsides are there? Any reason this isn't enabled by default? (1 minute, 2016).
- [Why Pinball was removed from Windows Vista](https://devblogs.microsoft.com/oldnewthing/20121218-00/?p=5803) - Windows XP was the last client version of Windows to include the Pinball game that had been part of Windows since Windows 95. (2 minutes, 2012).

### Network

- [DNS does not propagate](https://jvns.ca/blog/2021/12/06/dns-doesn-t-propagate/) - I feel like the term "DNS propagation" is misleading, like you're not actually waiting for DNS records to "propagate", you're waiting for cached records to expire. (10 minutes, 2021).
- [DOS on Dope](https://secretgeek.net/dod_intro) - An MVC web framework made and running entirely on Batch scripts. (2 minutes, 2010).
- [Everything You Wanted to Know About UDP Sockets but were Afraid to Ask](https://blog.cloudflare.com/everything-you-ever-wanted-to-know-about-udp-sockets-but-were-afraid-to-ask-part-1/) - Although UDP is simple in principle, there is a lot of domain knowledge needed to run things at scale. In this blog post we'll cover the basics: all you need to know about UDP servers to get started. (8 minutes, 2021).
- [Fun with IP Address Parsing](https://blog.dave.tf/post/ip-addr-parsing/) - In my quest to write a fast IPv4+6 parser, I wrote a slow-but-I-think-correct parser, to use as a base of comparison. In doing so, I discovered more cursed IP address representations that I was previously unaware of. Let’s explore together! (5 minutes, 2021).
- [How to Tell if a Problem is Caused by DNS](https://jvns.ca/blog/2021/11/04/how-do-you-tell-if-a-problem-is-caused-by-dns/) - So here are a few tools I use to tell if a problem I’m having is caused by DNS, as well as a few DNS debuggging stories from my life. (8 minutes, 2021).
- [Is It DNS?](https://isitdns.com/) - Quickly check if your problem is caused by DNS or not. (2022).
- [Mess with DNS](https://messwithdns.net/) - Gives you a subdomain and DNS server to play with it online. (2022).
- [No, its not always DNS](https://thesoloadmin.com/no-its-not-always-dns/) - In today's environment of always-on, always-available Internet connectivity, network troubleshooting has become somewhat of a lost art. (10 minutes, 2022).
- [NVIDIA Cumulus and Sonic ethernet OS's](https://www.nvidia.com/en-us/networking/ethernet-switching/) - Open source network operating systems distributed by NVIDIA. (2022).
- [SSH Bastion Hosts: Setting up](https://goteleport.com/blog/ssh-bastion-host/) - What is an SSH bastion and how is this different from an SSH jump server or an SSH proxy? (7 minutes, 2022).
- [SSH Bastion Hosts: Security best practices](https://goteleport.com/blog/security-hardening-ssh-bastion-best-practices/) - Although it is relatively easy to deploy a bastion host in your infrastructure, securing a bastion host requires careful consideration from design to deployment. (10 minutes, 2022).
- [The Cyber-Plumber's Handbook](https://github.com/opsdisk/the_cyber_plumbers_handbook) - The definitive guide to Secure Shell (SSH) tunneling, port redirection, and bending traffic like a boss. The book was first published in October 2018. (70 minutes, 2021).
- [The Monstrosity Email has Become](https://ploum.net/the-monstrosity-email-has-become/) - The first and obvious problem with email is that it has been developed 40 years ago as a receiver-only protocol. (10 minutes, 2021).
- [What's in a hostname?](https://www.netmeister.org/blog/hostnames.html) - You can spend a surprising amount of time chasing RFCs and finding out more than you ever thought you'd need to know about something as trivial as "hostnames". (15 minutes, 2021).


### Places to Find Things

- [arXiv](https://arxiv.org/) - Cornell University's archive of free distribution service and an open-access archive for 2,000,301 scholarly articles in the fields of physics, mathematics, computer science, quantitative biology, quantitative finance, statistics, electrical engineering and systems science, and economics.
- [Library Genesis](https://libgen.is/) - A shadow library website for scholarly journal articles, academic and general-interest books.
- [Library Thing MDS](https://www.librarything.com/mds) - Find books by selecting narrowing topics of interest.

### Python

- [All You Need to Know About Python Asterisks](https://bas.codes/posts/python-asterisks) - Use the `*` for more than just multiplication. (5 minutes, 2022).
- [Borgs and Singletons](https://bas.codes/posts/python-dict-slots#introducing-the-borg) - Is there a use case where we want all instances to share the same storage? Singletons in Python. (7 minutes, 2022).
- [Borg Pitfalls](https://bas.codes/posts/python-involuntary-borgs) - Python, in general, is a pass-by-reference language. What does that mean, and what do you need to look out for? (5 minutes, 2022).
- [Compiling Python Syntax to x86-64 Assembly For Fun and (zero) Profit](https://benhoyt.com/writings/pyast64/) - Using Python’s built-in AST module to parse a subset of Python syntax and turn it into an x86-64 assembly program. (8 minutes, 2017).
- [Debugging with GDB](https://wiki.python.org/moin/DebuggingWithGdb) - Official Python wiki reference source for using `gdb`.
- [Don't Let dicts Spoil Your Code](https://roman.pt/posts/dont-let-dicts-spoil-your-code/) - What’s wrong with dicts? Dicts are opaque. Dicts are mutable. (7 minutes, 2021).
- [f-strings are more powerful than you might think](https://martinheinz.dev/blog/70) - Let's take a tour of some awesome f-string features that you'll want to use in your everyday coding. (5 minutes, 2022).
- [Extracting Text from HTML in Python: A very fast approach](https://rushter.com/blog/python-fast-html-parser/) - When working on NLP problems, sometimes you need to obtain a large corpus of text. (3 minutes, 2019).
- [Flake8: Style Guide Enforcement Checker](https://flake8.pycqa.org/en/latest/index.html) - Quickstart guide to using Flake8 to enforce code styling. 
- [Folders.py](https://github.com/SinaKhalili/Folders.py) - A programming language made in Python where the source code is the directory structure. (2021).
- [Garbage Collection in Python: Things You Need to Know](https://rushter.com/blog/python-garbage-collector/) - Understanding how garbage collection works can help you write better and faster Python programs. (10 minutes, 2020).
- [How to Patch Python Bytecode](https://rushter.com/blog/python-bytecode-patch/) - In standard Python, when executing a script, the raw source code is compiled into platform-independent bytecode which subsequently runs on Python's stack-based virtual machine. (3 minutes, 2017).
- [How vectorization speeds up your Python code](https://pythonspeed.com/articles/vectorization-python/) - What “vectorization” means, and when it applies. (10 minutes, 2022).
- [Keyword-only arguments](https://lukeplant.me.uk/blog/posts/keyword-only-arguments-in-python/) - To understand keyword-only arguments, we first have to clear up a common misunderstanding about Python positional and keyword arguments. (3 minutes, 2020).
- [Neural Network from scratch](https://sirupsen.com/napkin/neural-net) - Building a simple neural network to explore the core concepts. (30 minutes, 2022).
- [Python Type Hints are Turing Complete](https://arxiv.org/pdf/2208.14755.pdf) - Using Grigore's method to explain why Mypy sometimes enters an infinite loop, and why that is not a bug.
- [MyPy: Static Typing for Python](http://mypy-lang.org/)
- [Numpy SIMD optimizations](https://numpy.org/doc/stable/reference/simd/simd-optimizations.html)
- [On Code Isolation in Python](https://rushter.com/blog/python-code-isolation/)
- [Optimatization Tricks of Tuples vs Lists](https://rushter.com/blog/python-lists-and-tuples/)
- [PEP 8](https://www.python.org/dev/peps/pep-0008/) - Style Guide for Python Code.
- [PEP 20](https://www.python.org/dev/peps/pep-0020/) - The Zen of Python.
- [PEP 3102](https://www.python.org/dev/peps/pep-3102/)
- [PEP 570: Positional-only arguments](https://www.python.org/dev/peps/pep-0570/#how-to-teach-this)
- [Python Type Hints: Avoiding the Boolean Trap](https://adamj.eu/tech/2021/07/10/python-type-hints-how-to-avoid-the-boolean-trap/)
- [Python Type Hints: How to use the overload decorator](https://adamj.eu/tech/2021/05/29/python-type-hints-how-to-use-overload/)
- [Python Type Hints: How to type a context manager](https://adamj.eu/tech/2021/07/04/python-type-hints-how-to-type-a-context-manager/)
- [Python Type Hints: Typeguard](https://adamj.eu/tech/2021/06/09/python-type-hints-how-to-narrow-types-with-typeguard/) - See also [PEP 647](https://www.python.org/dev/peps/pep-0647/)
- [Python Type Hints: Use Cases for types Module](https://adamj.eu/tech/2021/09/08/python-type-hints-use-cases-for-the-types-module/)
- [Under the hood weirdness, Part 1](https://twitter.com/reuvenmlerner/status/1531552019101671424)

### Reverse Engineering & Hardware Hacking

- [An Ancient Greek Astronomical Calculation Machine Reveals New Secrets](https://www.scientificamerican.com/article/an-ancient-greek-astronomical-calculation-machine-reveals-new-secrets/)
- [Antenna Theory](https://www.antenna-theory.com/) - This website will strive to make antennas understandable, without unnecessary complexity.
- [Bypasssing early 2000's copy protection](https://blog.paavo.me/masa-copy-protection/)
- [Crazy Thin Deep-Insert ATM Skimmers](https://krebsonsecurity.com/2022/09/say-hello-to-crazy-thin-deep-insert-atm-skimmers/) - Here’s a look at some of the more sophisticated deep insert skimmer technology that fraud investigators have recently found in the wild. (5 minutes, 2022).
- [Dumping Firmware with a 555](https://jrainimo.com/build/2022/01/dumping-firmware-with-a-555/)
- [I'm not a human: Breaking the Google reCAPTCHA](https://www.blackhat.com/docs/asia-16/materials/asia-16-Sivakorn-Im-Not-a-Human-Breaking-the-Google-reCAPTCHA-wp.pdf)
- [Inside ReCaptcha](https://github.com/neuroradiology/InsideReCaptcha)
- [Pixel Perfect: Fingerprinting Canvas in HTML5](https://hovav.net/ucsd/dist/canvas.pdf)
- [Fixing a Tiny Corner of the Supply Chain](https://www.bunniestudios.com/blog/?p=6274)
- [Game Hacking](https://gamehacking.academy/GameHackingAcademy.pdf) - Free educational PDF, from "what is a computer?" to crafting game hacks.
- [Ghost in the ethernet optic](https://blog.benjojo.co.uk/post/smart-sfp-linux-inside)
- [How to Make a CPU](https://blog.robertelder.org/how-to-make-a-cpu/) - A simple step by step picture guide to making your own CPU. (4 minutes, 2021).
- [Make It Go Faster! How We Sped Up OS Provisioning On Bare Metal at Scale](https://web.archive.org/web/20211110191916/https://metal.equinix.com/blog/make-it-go-faster-how-we-sped-up-os-provisioning-on-bare-metal-at-scale/) - Here’s how adding a few bits of simple logic in the OS provisioning process can eliminate tons of network and time overhead and prolong the life of your storage.
- [Mechanical Computing Systems Using Only Links and Rotary Joints](https://arxiv.org/pdf/1801.03534.pdf)
- [Playstation Architecture: A practical analysis](https://www.copetti.org/writings/consoles/playstation/)
- [Playstation 2 Architecture](https://www.copetti.org/writings/consoles/playstation-2/)
- [Reverse Engineering the M1](https://www.youtube.com/watch?v=espRmO41Bg4)
- [Scan of the Month: Game Boy Compendium](https://scanofthemonth.com/)
- [Systems Performance: Enterprise and The Cloud](https://www.brendangregg.com/blog/2020-07-15/systems-performance-2nd-edition.html)
- [Teaching a cheap ethernet switch new tricks](https://blog.benjojo.co.uk/post/dell-switch-hacking)
- [The Inside Story of the Outside Investigation of SoftRAM 95](https://devblogs.microsoft.com/oldnewthing/20211111-00/?p=105897)
- [The Structure of a Smartphone](https://medium.com/telecom-expert/structure-of-a-smartphone-383575de3eaf)
- [What is AT&T doing at 1111340002?](https://scribe.rip/telecom-expert/what-is-at-t-doing-at-1111340002-c418876c212c)


### Security

- [10 Stories of how we've compromised CI/CD pipelines](https://research.nccgroup.com/2022/01/13/10-real-world-stories-of-how-weve-compromised-ci-cd-pipelines/)
- [Exploit Development: Browser Exploitation on Windows - CVE-2019-0567, A Microsoft Edge Type Confusion Vulnerability (Part 3)](https://connormcgarr.github.io/type-confusion-part-3/)
- [Exploit Development: No Code Execution? No Problem! Living The Age of VBS, HVCI, and Kernel CFG](https://connormcgarr.github.io/hvci/)
- [Counterfeit Fraud Prevention - Tips, Tools, and Techniques](https://www.fraudfighter.com/hs-fs/hub/76574/file-22799169-pdf/docs/counterfeit_fraud_-_tips,_tools_and_techniques.pdf)
- [Outline of forgery](https://en.wikipedia.org/wiki/Outline_of_forgery)
- [The curious case of the raspberry pi in the closet](https://blog.haschek.at/2019/the-curious-case-of-the-RasPi-in-our-network.html)

### Software Development

- [1001 Representations of Syntax with Binding](https://jesper.sikanda.be/posts/1001-syntax-representations.html)
- [21 compilers and 3 orders of magnitude in 60 minutes](https://github.com/EanNewton/Awesome-Reading-List/blob/main/media/Hoare%2C%20Graydon%20-%20CompilerTalk-2019.pdf) - What compilers look like from the perspective of people who make them for a living.
- [Algorithms](https://cp-algorithms.com/index.html) - Provides descriptions of many algorithms and data structures especially popular in field of competitive programming.
- [An Illustrated guide to Elliptic Curve Cryptography Validation](https://research.nccgroup.com/2021/11/18/an-illustrated-guide-to-elliptic-curve-cryptography-validation/)
- [Anatomy of a Great Library API](https://brandur.org/nanoglyphs/019-api-libraries)
- [Bootstrapping a small math library](https://www.johndcook.com/blog/2021/01/05/bootstrapping-math-library/)
- [Complexity is Killing Us](https://www.infoworld.com/article/3639050/complexity-is-killing-software-developers.html)
- [Data Oriented Programming](https://www.manning.com/books/data-oriented-programming?a_aid=viebel&a_bid=d5b546b7)
- [Distinction between 3 data related paradigms](https://blog.klipse.tech/visualization/2021/02/16/data-related-paradigms.html)
- [Don't be scared of functional programming](https://www.smashingmagazine.com/2014/07/dont-be-scared-of-functional-programming/)
- [Don't try to sanitize input, Escape output](https://benhoyt.com/writings/dont-sanitize-do-escape/)
- [Falsehoods Programmers Believe About Names](https://www.kalzumeus.com/2010/06/17/falsehoods-programmers-believe-about-names/)
- [Fast Checksum Computation](https://blogs.igalia.com/dpino/2018/06/14/fast-checksum-computation/)
- [Faster Auto-Complete Algorithm with a Pruning Radix Trie](https://seekstorm.com/blog/pruning-radix-trie/)
- [Faster Spelling Correction Algorithm](https://seekstorm.com/blog/1000x-spelling-correction/)
- [Falsehoods Programmers Believe About Time](https://infiniteundo.com/post/25326999628/falsehoods-programmers-believe-about-time)
- [FizzBuzz at 55GB/s](https://codegolf.stackexchange.com/questions/215216/high-throughput-fizz-buzz)
- [Generate All the Things](https://matklad.github.io//2021/11/07/generate-all-the-things.html) - Generating good data for testing.
- [Large Scale Terrain Generation from Tectonic Uplift and Fluvial Erosion](https://hal.inria.fr/hal-01262376/document)
- [Long Division](https://tavianator.com/2022/long_division.html)
- [Minimalism in Programming](https://pointersgonewild.com/2018/02/18/minimalism-in-programming/)
- [Minimalism in Programming Language Design](https://pointersgonewild.com/2022/05/23/minimalism-in-programming-language-design/)
- [More Falsehoods Programmers Believe About Time](https://infiniteundo.com/post/25509354022/more-falsehoods-programmers-believe-about-time) - You are getting time wrong and here's the how and why.
- [NaN boxing or how to make the world dynamic](https://piotrduperas.com/posts/nan-boxing) - Adding dynamic typing to C. (20 minutes, 2020).
- [Parallel curves of cubic Béziers](https://raphlinus.github.io/curves/2022/09/09/parallel-beziers.html) - Finding a better approach to matching parallel curves.
- [Practical Data Oriented Design](https://media.handmade-seattle.com/practical-data-oriented-design/)
- [Practical Introduction to Functional Programming](https://maryrosecook.com/blog/post/a-practical-introduction-to-functional-programming)
- [Practical Reed-Solomon for Programmers](https://berthub.eu/articles/posts/reed-solomon-for-programmers/) - A practical primer on R-S error correction.
- [Procedural Worlds from tiles](https://ijdykeman.github.io/ml/2017/10/12/wang-tile-procedural-generation.html)
- [Progressive Growing of GANs](https://github.com/tkarras/progressive_growing_of_gans)
- [Random points on a sphere](https://www.jasondavies.com/maps/random-points/)
- [Re-reading Tanenbaum's critique of RPC 30 years later](https://www.bu.edu/csmet/2018/08/30/re-reading-tanenbaums-critique-of-rpc-30-years-later/)
- [Rethinking Errors](http://neugierig.org/software/blog/2022/01/rethinking-errors.html)
- [Simple Stupid Funnel Algorithm](http://digestingduck.blogspot.com/2010/03/simple-stupid-funnel-algorithm.html)
- [Some Obscure C Features](https://multun.net/obscure-c-features.html)
- [Stop Celebrating Incompetence](https://world.hey.com/dhh/programmers-should-stop-celebrating-incompetence-de1a4725)
- [Terrain Erosion Generation 3 Ways](https://github.com/dandrino/terrain-erosion-3-ways)
- [The Joy of Concurrent Logic Programming](http://www.call-with-current-continuation.org/articles/the-joy-of-concurrent-logic-programming.txt)
- [The Science of Managing Our Digital Stuff](https://mitpress.mit.edu/books/science-managing-our-digital-stuff)
- [Tuple Spaces (or, Good Ideas Don't Always Win)](https://software-carpentry.org/blog/2011/03/tuple-spaces-or-good-ideas-dont-always-win.html)
- [VS Code vs JetBrains](https://blankly.finance/vscode-vs-jetbrains/)
- [Why not TOML?](https://hitchdev.com/strictyaml/why-not/toml/)
- [Worse is Better](https://www.dreamsongs.com/RiseOfWorseIsBetter.html)

### System Development

- [A Close Look at a Spinlock](https://blog.regehr.org/archives/2173)
- [Designing Better File Organization Around Tags, Not Hierarchies](https://www.nayuki.io/page/designing-better-file-organization-around-tags-not-hierarchies)
- [Filesystem Links: Everything You Ever Wanted to Know](https://controlaltbackspace.org/filesystem/filesystem-links-everything-you-ever-wanted-to-know/)
- [Modules, Monoliths, and Microservices](https://tailscale.com/blog/modules-monoliths-and-microservices/)
- [Resources to learn distributed systems](https://pierrezemb.fr/posts/distsys-resources/) - A distributed system is one in which the failure of a computer you didn’t even know existed can render your own computer unusable. (9 minutes, 2022).
- [Welcome to Operating Systems](https://pages.cs.wisc.edu/~remzi/OSTEP/) - A free online operating systems book. Centered around: virtualization, concurrency, and persistence.

### Videos

- ["Uptime 15,364 Days" - The Computers of Voyager](https://www.youtube.com/watch?v=H62hZJVqs2o)
- [Stanford - Lecture Collection | Convolutional Neural Networks for Visual Recognition (Spring 2017)](https://www.youtube.com/playlist?list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv)

### Vintage & Historical

- [10 Forgotten Image Formats](https://tedium.co/2021/11/10/10-forgotten-image-formats/)
- [A History of modern init systems](https://web.archive.org/web/20220618014428/https://blog.darknedgy.net/technology/2015/09/05/0/) - The subject of process management, supervision and init(8) for Unix-like systems is one plagued by a large degree of ahistoricity and “pop culture” explanations.
- [A Rational Design Process. How and Why to Fake It](https://www.ics.uci.edu/~taylor/classes/121/IEEE86_Parnas_Clement.pdf) - (1986).
- [A Short History of Objective-C](https://medium.com/chmcore/a-short-history-of-objective-c-aff9d2bde8dd)
- [Always more history](https://www.hillelwayne.com/post/always-more-history/)
- [Booting the IBM 1401](http://www.righto.com/2021/02/an-ibm-1401-mainframe-computer-at.html)
- [Decades of Computing: Machines built to last](https://www.datagubbe.se/30yearcomp/)
- [Don't Touch: The Story of the U-Force](https://thegaminghistorian.com/dont-touch-the-story-of-the-u-force/) - (37 minute video) All about the Nintendo U-Force and why you've never heard of it.
- [EXE Magazine interview with Anders Hejlsberg on Delphi](https://www.theopenforce.com/2020/02/anders-hejlsberg-delphi-1995.html) - (1995).
- [Hercules: IBM S/370 and ESA/390 Emulator](http://www.jaymoseley.com/hercules/)
- [How To Code](http://jvaltane.kapsi.fi/amiga/howtocode/) - (1993).
- [Software Library: Screensavers](https://archive.org/details/softwarelibrary_screensavers)
- [Taking this Serially: RS-232 History](https://computer.rip/2021-01-12%20taking%20this%20serially.html)
- [Why do interviewers ask linked list?](https://www.hillelwayne.com/post/linked-lists/)
- [Why ISO was retired](https://bkhome.org/news/202112/why-iso-was-retired-part-2.html)
- [WinWorld: Vintage Operating System Downloads](https://winworldpc.com/library/operating-systems)


### Web

<!--lint ignore no-repeat-punctuation-->
- [A Reality Where CSS and JavaScript Don't Exist..?](https://kevq.uk/reality-without-css-javascript)
- [Breaking out of the Box](https://alistapart.com/article/breaking-out-of-the-box/) - CSS is about styling boxes. In fact, the whole web is made of boxes, from the browser viewport to elements on a page. But every once in a while a new feature comes along that makes us rethink our design approach.
- [How to Build a Low-Tech Website](https://homebrewserver.club/low-tech-website-howto.html)
- [Hot to build HTML forms right](https://austingil.com/how-to-build-html-forms-right-semantics/) - A five part series on how to make actually usable and well designed web forms.
- [HTTP://HTTP://HTTP://@HTTP://HTTP://?HTTP://#HTTP://](https://daniel.haxx.se/blog/2022/09/08/http-http-http-http-http-http-http/) - Is a legitimate URL and here's why.
- [My Blog is Hilariously Overengineered to the Point People Think it's a Static Site](https://xeiaso.net/talks/how-my-website-works) - Xe Iaso explains how he fully automated his stupid fast blog website.
- [What's in a font? Website Typography Best Practices](https://kevq.uk/whats-in-a-font-researching-website-typography/)
- [Why are Hyperlinks blue, revisted](https://blog.mozilla.org/en/internet-culture/why-are-hyperlinks-blue-revisited/)
- [You can access a user's camera with just HTML](https://austingil.com/html-capture-attribute/) - About the `capture` attribute.


## }

---

## Reference materials


### Algorithm & Logic References

- [Aho-Corasick](https://en.wikipedia.org/wiki/Aho%E2%80%93Corasick_algorithm)
- [Berlekamp-Welch](https://en.wikipedia.org/wiki/Berlekamp%E2%80%93Welch_algorithm)
- [Bresenham's Line Algorithm](https://en.wikipedia.org/wiki/Bresenham%27s_line_algorithm)
- [Damerau-Levenshtein](https://en.wikipedia.org/wiki/Damerau%E2%80%93Levenshtein_distance)
- [De Morgan's Law](https://brilliant.org/wiki/de-morgans-laws/)
- [Delaunay Triangulation](https://en.wikipedia.org/wiki/Delaunay_triangulation)
- [Euler Method](https://en.wikipedia.org/wiki/Euler_method)
- [Hirschberg](https://en.wikipedia.org/wiki/Hirschberg%27s_algorithm)
- [Huen's Method](http://calculuslab.deltacollege.edu/ODE/7-C-2/7-C-2-h.html)
- [Lamports Bakery](https://en.wikipedia.org/wiki/Lamport%27s_bakery_algorithm)
- [Mersenne Twister](https://en.wikipedia.org/wiki/Mersenne_Twister)
- [Midpoint Method](https://en.wikipedia.org/wiki/Midpoint_method)
- [Mitchell's Best Cadidate](https://bl.ocks.org/mbostock/1893974)
- [Poisson Disk Sampling](https://www.jasondavies.com/poisson-disc/)
- [Ralston's Second Order Method](http://www.mymathlib.com/diffeq/runge-kutta/runge_kutta_ralston_2.html)
- [Reed-Solomon](https://en.wikipedia.org/wiki/Reed%E2%80%93Solomon_error_correction)
- [Runge-Kutta Method](https://en.wikipedia.org/wiki/Runge%E2%80%93Kutta_methods) - See Also: [Visualizing the Runge-Kutta Method](https://www.haroldserrano.com/blog/visualizing-the-runge-kutta-method)
- [Stochastic Rounding](https://en.wikipedia.org/wiki/Rounding#Stochastic_rounding)

### Data Structures References

- [Base32](https://www.crockford.com/base32.html)
- [Kuramoto Model](https://en.wikipedia.org/wiki/Kuramoto_model)
- [Lengauer Tarjan Dominator Tree](https://www.boost.org/doc/libs/1_66_0/libs/graph/doc/lengauer_tarjan_dominator.htm)
- [Trie](https://en.wikipedia.org/wiki/Trie)

### Hardware

- [The Pinouts Book](https://pinouts.org/)

### Lists

- [Awesome Docs](https://github.com/testthedocs/awesome-docs) - A curated list of awesome documentation tools. (2022).
- [Awesome Documentation Tools](https://github.com/unicodeveloper/awesome-documentation-tools) - Curated list of documentation tools in different languages. API, Architecture, Library and X Documentation. (2018).
- [Awesome GitHub Profile Readmes](https://github.com/durgeshsamariya/awesome-github-profile-readme-templates) - This repository contains best profile readme's for your reference.
- [Awesome Guidelines](https://awesome-guidelines.com/) - A set of style guides, practices, and methods for each aspect of a program written in that language.
- [Awesome Falsehoods](https://github.com/kdeldycke/awesome-falsehood) - Everything you know is a lie.
- [Awesome Markdown Editors](https://github.com/mundimark/awesome-markdown-editors) - A collection of awesome markdown editors and (pre)viewers for Linux, Apple macOS, Microsoft Windows, the World Wide Web and more. (2022).
- [Awesome Project Boilerplates](https://github.com/melvin0008/awesome-projects-boilerplates) - Curated list of boilerplates and templates to enhance productivity. Boilerplates for mobile and web apps.
- [Awesome Self-Reference](https://github.com/aztek/awesome-self-reference)
- [Awesome SRE](https://github.com/dastergon/awesome-sre) - A curated list of awesome Site Reliability and Production Engineering resources.
- [Awesome Regex](https://github.com/aloisdg/awesome-regex) - A curated collection of awesome Regex libraries, tools, frameworks and software. The goal is to build a categorized community-driven collection of very well-known resources.
- [Dan Craswell's Distributed Systems Reading List](https://dancres.github.io/Pages/) - All about distributed systems.
- [Hacker Laws](https://github.com/dwmkerr/hacker-laws) - Laws, Theories, Principles and Patterns that developers will find useful. (2022).
- [Papers We Love](https://github.com/papers-we-love/papers-we-love) - Papers from the computer science community to read and discuss. 
- [The Book of Secret Knowledge](https://github.com/trimstray/the-book-of-secret-knowledge) - Tools and resources aimed towards System and Network administrators, DevOps, Pentesters, and Security Researchers.
- [Trailblazers](https://trailblazerlist.xyz/) - A list of startups attempting to solve meaningful problems.

### Organizations

- [Electronic Frontier Foundation](https://www.eff.org/) - The leading nonprofit defending digital privacy, free speech, and innovation.
- [Open Compute Project](https://www.opencompute.org/)
- [Write the Docs](https://www.writethedocs.org/) - Write the Docs is a global community of people who care about documentation.

### Standards

- [PEP 0](https://www.python.org/dev/peps/) - Index of Python Enhancement Proposals (PEPs).
- [PEP 484: Type Hints](https://www.python.org/dev/peps/pep-0484/)
- [The Base16, Base32, and Base64 Data Encodings](https://datatracker.ietf.org/doc/html/rfc4648)
- [The HTTP QUERY Method](https://www.ietf.org/archive/id/draft-ietf-httpbis-safe-method-w-body-02.html)

### RFC

- [RFC 2308: Negative Caching of DNS Queries (DNS NCACHE)](https://www.rfc-editor.org/rfc/rfc2308)
- [RFC 4122: A Universally Unique IDentifier (UUID) URN Namespace](https://datatracker.ietf.org/doc/html/rfc4122)

<!--lint enable match-punctuation-->
<!-- END CONTENT -->

## Follow

<!-- list people worth following on social sites (Twitter, LinkedIn, GitHub, YouTube etc.) -->

Who else should we be following!?

## Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors

[Thanks goes to these contributors](https://github.com/EanNewton/Awesome-Reading-List/graphs/contributors)!

