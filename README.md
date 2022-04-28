# Resources
Collection of resources I have used throughout my studies (cybersecurity and systems)

## Table of Contents
[Basics](#1)  
[Linux Userland Exploitation](#2)  
[Linux Kernel Exploitation](#3)  
[Browser Exploitation](#4)  
[Embedded Security](#5)  
[Fuzzing](#6)  
[Malware](#7)  
[Windows Userland Exploitation](#8)  
[Game Hacking](#9)  
[Appsec](#10)  
[Compilers](#11)  
[Optimized Programming](#12)  
[Computer Architecture](#13)  

<a name="1"/></a>
### Basics

<ins>ASM/Reverse Engineering:</ins>
* [arm\_azeria](https://azeria-labs.com/writing-arm-assembly-part-1/)
* [x86\_Programming from the ground
up](https://download-mirror.savannah.gnu.org/releases/pgubook/ProgrammingGroundUp-1-0-booksize.pdf)
* [begin.re](https://www.begin.re/)
* [Hackadayu](https://www.youtube.com/watch?v=d4Pgi5XML8E)
* [Beginners.re](https://beginners.re/main.html)
* [Secrets of RE](https://www.amazon.com/Reversing-Secrets-Engineering-Eldad-Eilam/dp/0764574817)

<ins>Secure Coding/Code Auditing:</ins>
* [Secure Coding in C/C++](https://www.amazon.com/Secure-Coding-2nd-Software-Engineering/dp/0321822137)
* [Art of software Security
Assessment](https://www.amazon.com/Art-Software-Security-Assessment-Vulnerabilities/dp/0321444426)

<ins>Other:</ins>
* [Dive into Systems](https://diveintosystems.org/book/)
* [Practical Binary Analysis](https://nostarch.com/binaryanalysis)
* [OS in 3 Steps](https://pages.cs.wisc.edu/~remzi/OSTEP/)

<a name="2"/></a>
### Linux Userland Exploitation
<ins>Stack</ins>
* [pwn.college](https://pwn.college)
* [Rop Emporium](https://ropemporium.com/)
* [Nightmare](https://guyinatuxedo.github.io/)
* [CTF-Wiki](https://ctf-wiki.org/pwn/readme/ )
* [Ret2 Systems](https://wargames.ret2.systems/) (paid)
* [Ironstone](https://ir0nstone.gitbook.io/notes)
* [PWN Practice](https://github.com/seal9055/PWN_Zero2Hero) (mine)

<ins>Heap</ins>
* [azeria](https://azeria-labs.com/heap-exploitation-part-1-understanding-the-glibc-heap-implementation/)
* [Heaplab Udemy](https://www.udemy.com/course/linux-heap-exploitation-part-1/) (paid)
* [Shellphish How2Heap](https://github.com/shellphish/how2heap)
* [Starcross](https://github.com/StarCross-Tech/heap_exploit_2.31)
* [Faith](https://faraz.faith/2019-10-12-picoctf-2019-heap-challs/)
* [Dhavalkapil](https://heap-exploitation.dhavalkapil.com/)


<a name="3"/></a>
### Linux Kernel Exploitation

<ins>Kernel basics/dev</ins>  
* [Linux Device Drivers](https://lwn.net/Kernel/LDD3/)
* [Linux Kernel Labs](https://linux-kernel-labs.github.io/refs/heads/master/)
* [Understanding the Linux Kernel](https://www.amazon.com/Understanding-Linux-Kernel-Third-Daniel/dp/0596005652)
* [Linux Kernel Programming P1](https://www.amazon.com/Linux-Kernel-Development-Cookbook-programming/dp/178995343X)
* [Linux Kernel Programming P2](https://www.amazon.com/Linux-Kernel-Programming-Part-Synchronization-ebook/dp/B08ZSV58G8)

<ins>Exploitation</ins>  
* [lkmidas](https://lkmidas.github.io/posts/20210123-linux-kernel-pwn-part-1/)
* [Kernel ROP](https://seal9055.com/blog/kernel/return_oriented_programming) (mine)
* [ptr-yudai](https://ptr-yudai.hatenablog.com/entry/2020/03/16/165628#LeakAARAAWRIP%E5%88%B6%E5%BE%A1%E3%81%AB%E4%BD%BF%E3%81%88%E3%82%8B%E6%A7%8B%E9%80%A0%E4%BD%93%E4%B8%80%E8%A6%A7)
* [Lexfo](https://blog.lexfo.fr/cve-2017-11176-linux-kernel-exploitation-part1.html)
* [Kernel Heap Exploitation](https://argp.github.io/2012/01/03/linux-kernel-heap-exploitation/)
* [Pr0cf5](https://pr0cf5.github.io/ctf/2019/10/10/balsn-ctf-krazynote.html)

<a name="4"/></a>
### Browser Exploitation
* [seal9055\_Complete Introduction](https://seal9055.com/blog/browser/browser_architecture) (mine)
* [Official V8 Blog](https://v8.dev/blog)
* [pwnbykenny V8 Objects](https://pwnbykenny.com/2020/07/05/v8-objects-and-their-structures/)
* [Jayconrod V8 Objects](https://www.jayconrod.com/posts/52/a-tour-of-v8--object-representation)
* [Doar](https://doar-e.github.io/blog/2019/01/28/introduction-to-turbofan/)
* [Saelo Phrack](http://www.phrack.org/issues/70/9.html)
* [Faith](https://faraz.faith/2019-12-13-starctf-oob-v8-indepth/)
* [MGP25](https://mgp25.com/browser-exploitation/)
* [Ret2](https://blog.ret2.io/2018/06/05/pwn2own-2018-exploit-development/)
* [Google Project Zero](https://googleprojectzero.blogspot.com/2020/09/jitsploitation-one.html)

<a name="5"/></a>
### Embedded Security
* [Embedded Intro Videos](https://www.youtube.com/watch?v=LSQf3iuluYo&list=PLoFdAHrZtKkhcd9k8ZcR4th8Q8PNOx7iU)
* [&>/dev/null](https://www.thirtythreeforty.net/posts/)
* [Debugmen Enabot](https://debugmen.dev/hardware-series/2022/02/18/enabot_series_part_1.html)
* [Embedded Bits](https://embeddedbits.org/introduction-embedded-linux-security-part-1/)
* [Sans Whitepaper Router Hack](https://www.sans.org/reading-room/whitepapers/testing/paper/34022)
* [Grimm](https://blog.grimm-co.com/)
* [Car Hacking Paper](http://www.autosec.org/pubs/cars-oakland2010.pdf)
* [Flashback Team](https://www.youtube.com/channel/UCBrKPoIYCS7BlT7Q_UiBwAQ)
* [Printer Hacking Stream](https://www.youtube.com/watch?v=qti5_NOLE8M&list=PLSkhUfcCXvqGGQN8ATgWI0XYGvU-jq0uG)
* [Hardware Hacking Handbook](https://nostarch.com/hardwarehacking)

<a name="6"/></a>
### Fuzzing

<ins>General</ins>  
* [Fuzzing Book](https://www.fuzzingbook.org/)
* [Gamozolabs](https://gamozolabs.github.io/)
* [Fuzzing101 Practice](https://github.com/antonio-morales/Fuzzing101)

<ins>Papers</ins>  
* [Collection of papers + intro](https://github.com/seal9055/sfuzz/blob/main/fuzzing.md) (mine)

<ins>Codeql</ins>  
* [Readteam-village](https://www.youtube.com/watch?v=-bJ2Ioi7Icg&ab_channel=RedTeamVillage)  
* [Security-lab](https://securitylab.github.com/research/rhino-in-the-room/)  
* [Github](https://www.youtube.com/watch?v=nvCd0Ee4FgE&ab_channel=GitHub)  

<a name="7"/></a>
### Malware
* [Practical Malware Analysis](https://nostarch.com/malware)
* [Windows Internals](https://www.amazon.com/Windows-Internals-Part-architecture-management/dp/0735684189)
* [0xpat Malware Dev](https://0xpat.github.io/Malware_development_part_1/)
* [Uni Course](https://class.malware.re/)
* [Malware Unicorn](https://malwareunicorn.org/workshops/re101.html#0)
* [Zero2Auto](https://courses.zero2auto.com/) (paid)

<a name="8"/></a>
### Windows Userland Exploitation
* [Windows Internals](https://www.amazon.com/Windows-Internals-Part-architecture-management/dp/0735684189)
* [Corelan](https://www.corelan.be/index.php/articles/)
* [Fuzzysecurity](https://www.fuzzysecurity.com/tutorials.html)
* [OSED Prep](https://github.com/r0r0x-xx/OSED-Pre#DEP-Bypass)
* [Epi052](https://epi052.gitlab.io/notes-to-self/blog/)

<a name="9"/></a>
### Game Hacking
* [Guided Hacking](https://guidedhacking.com/threads/ghb0-game-hacking-bible-introduction.14450/)
* [Gamehacking Academy](https://gamehacking.academy/about)
* [seal9055\_Minesweeper/ds3 Intro](https://seal9055.com/blog/game/dark_souls_3) (mine)
* [Abraxus\_GH Intro](https://kasimir123.github.io/blog-posts/JourneyToSavagePlanet.html)

<a name="10"/></a>
### Appsec
* [Art of software Security Assessment](https://www.amazon.com/Art-Software-Security-Assessment-Vulnerabilities/dp/0321444426)
* [Pentesterlab](https://pentesterlab.com/)
* [Beginner Guide](https://0xboku.com/2021/09/14/0dayappsecBeginnerGuide.html)
* [Source-code Tester](https://www.sourcecodester.com/) (practice)

<a name="11"/></a>
### Compilers

<ins>General</ins>  
* [Crafting Interpreters](https://craftinginterpreters.com/)
* [Engineering a Compiler](https://www.amazon.com/Engineering-Compiler-Keith-Cooper/dp/012088478X)

<ins>Backend</ins>  
* [Youtube](https://www.youtube.com/user/pronesto/videos)
* [cytron\_Generate SSA](https://www.cs.utexas.edu/~pingali/CS380C/2010/papers/ssaCytron.pdf)
* [Computing Liveness for SSA](https://hal.inria.fr/inria-00558509v2/document)
* [Linear Scan Register Allocation](http://citeseerx.ist.psu.edu/viewdoc/download;jsessionid=018086FDA4BF35452D6324C96C3EC9D1?doi=10.1.1.162.2590&rep=rep1&type=pdf)
* [Linear Scan Regalloc](http://web.cs.ucla.edu/~palsberg/course/cs132/linearscan.pdf)
* [llvm regalloc](https://blog.llvm.org/2011/09/greedy-register-allocation-in-llvm-30.html)
* [Cornell Advanced Compilers](https://www.cs.cornell.edu/courses/cs6120/2020fa/self-guided/)

<a name="12"/></a>
### Optimized Programming
* [Algorithms for modern Hardware](https://en.algorithmica.org/hpc/)
* [Denis Yaroshevskiy](https://www.youtube.com/channel/UC4N2-1Wky5rzPgH4rv3tSFg/videos)
* [Jonas Skeppstedt](https://www.youtube.com/channel/UC3stBkbGaerSBDqKfe-NKsg/featured)
* [Fernando](https://www.youtube.com/user/pronesto)

<a name="13"/></a>
### Computer Architecture
* [Hennessy](https://www.amazon.com/Computer-Architecture-Quantitative-John-Hennessy/dp/012383872X)
* [Fabian Giesen youtube](https://www.youtube.com/channel/UCcRaa0AcYX32c0m8wJJHNWg/videos)
* [Sushi Roll](https://gamozolabs.github.io/metrology/2019/08/19/sushi_roll.html)
* [Princeton](https://www.youtube.com/watch?v=9nuAjYRbITQ&t=13975s&ab_channel=Nerd%27slesson)
* [ETH Zuerich](https://www.youtube.com/watch?v=AJBmIaUneB0&list=PL5Q2soXY2Zi_FRrloMa2fUYWPGiZUBQo2&ab_channel=OnurMutluLectures)
