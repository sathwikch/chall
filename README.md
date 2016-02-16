# Awesome Windows Exploitation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome Windows Exploitation resources, and shiny things.

There is no pre-established order of items in each category, the order is for contribution. If you want to contribute, please read the [guide](CONTRIBUTING.md).

### Table of Contents
- [windows stack overflows](#windows_stack_overflows)
- [windows heap overflows](#windows_heap_overflows)
- [kernel based Windows overflows](#kernel_based_Windows_overflows)
- [Windows memory protections](#Windows_memory_protections)
- [Bypassing filter and protections](#Bypassing_filter_and_protections)
- [Typical windows exploits](#Typical_windows_exploits)
- [Exploit development tutorial series](#Exploit_development_tutorial_series)
  + [Corelan Team](#corelan)
  + [Fuzzysecurity](#fuzzysecurity)
  + [Securitysift](#securitysift)
- [Tools](#tools)

<a name="windows_stack_overflows" />
## Windows stack overflows
*Stack Base Overflow Articles.*
+ [Win32 Buffer Overflows (Location, Exploitation and Prevention)](http://www.phrack.com/issues.html?issue=55&id=15#article)  by dark spyrit [1999]
+ [Writing Stack Based Overflows on Windows](http://www.packetstormsecurity.org/papers/win/) by Nish Bhalla’s [2005]

<a name="windows_heap_overflows" />
## Windows heap overflows
*Heap Base Overflow Articles.*
+ [Third Generation Exploitation smashing heap on 2k](http://www.blackhat.com/presentations/win-usa-02/halvarflake-winsec02.ppt) by halvar Flake [2002]
+ [Exploiting the MSRPC Heap Overflow - Part 1](http://freeworld.thc.org/root/docs/exploit_writing/msrpcheap.pdf) by Dave Aitel (MS03-026) [September 2003]
+ [Exploiting the MSRPC Heap Overflow - Part 2](http://freeworld.thc.org/root/docs/exploit_writing/msrpcheap2.pdf) by Dave Aitel (MS03-026) [September 2003]
+ [windows heap overflow penetration in black hat](https://www.blackhat.com/presentations/win-usa-04/bh-win-04-litchfield/bh-win-04-litchfield.ppt) by David litchfield [2004]

<a name="kernel_based_Windows_overflows" />
## Kernel based Windows overflows
*Kernel Base Exploit Development Articles.*
+ [how to attack kernel based vulns on windows was done](http://www.derkeiler.com/Mailing-Lists/Full-Disclosure/2003-08/0101.html) by a Polish group called “sec-labs” [2003]
+ [sec-lab old whitepaper](http://www.artofhacking.com/tucops/hack/windows/live/aoh_win32dcv.htm)
+ [sec-lab old exploit](http://www.securityfocus.com/bid/8329/info)
+ [Windows Local Kernel Exploitation (based on sec-lab research)](http://www.packetstormsecurity.org/hitb04/hitb04-sk-chong.pdf) by S.K Chong [2004]
+ [How to exploit Windows kernel memory pool](http://packetstormsecurity.nl/Xcon2005/Xcon2005_SoBeIt.pdf) by SoBeIt [2005]
+ [exploiting remote kernel overflows in windows](http://research.eeye.com/html/papers/download/StepIntoTheRing.pdf) by eeye security
+ [Kernel-mode Payloads on Windows in uninformed](http://www.uninformed.org/?v=3&a=4&t=pdf) by matt miller
+ [Exploiting 802.11 Wireless Driver Vulnerabilities on Windows](http://www.uninformed.org/?v=6&a=2&t=pdf)
+ [BH US 2007 Attacking the Windows Kernel](http://www.blackhat.com/presentations/bh-usa-07/Lindsay/Whitepaper/bh-usa-07-lindsay-WP.pdf)
+ [Remote and Local Exploitation of Network Drivers](http://www.blackhat.com/presentations/bh-usa-07/Bulygin/Presentation/bh-usa-07-bulygin.pdf)
+ [Exploiting Comon Flaws In Drivers](http://www.reversemode.com/index.php?option=com_content&task=view&id=38&Itemid=1)
+ [I2OMGMT Driver Impersonation Attack](http://www.immunityinc.com/downloads/DriverImpersonationAttack_i2omgmt.pdf)
+ [Real World Kernel Pool Exploitation](http://sebug.net/paper/Meeting-Documents/syscanhk/KernelPool.pdf)
+ [exploit for windows 2k3 and 2k8](http://www.argeniss.com/research/TokenKidnapping.pdf)
+ [nalyzing local privilege escalations in win32k](http://www.uninformed.org/?v=10&a=2&t=pdf)
+ [Intro to Windows Kernel Security Development](http://www.dontstuffbeansupyournose.com/trac/browser/projects/ucon09/Intro_NT_kernel_security_stuff.pdf)
+ [There’s a party at ring0 and you’re invited](http://www.cr0.org/paper/to-jt-party-at-ring0.pdf)
+ [Windows kernel vulnerability exploitation](http://vexillium.org/dl.php?call_gate_exploitation.pdf)

<a name="Windows_memory_protections" />
## Windows memory protections
*Windows memory protections Introduction Articles.*
+ [Data Execution Prevention](http://support.microsoft.com/kb/875352)
+ [/GS (Buffer Security Check)](http://msdn.microsoft.com/en-us/library/Aa290051)
+ [/SAFESEH](http://msdn.microsoft.com/en-us/library/9a89h429(VS.80).aspx)
+ [ASLR](http://blogs.msdn.com/michael_howard/archive/2006/05/26/address-space-layout-randomization-in-windows-vista.aspx)
+ [SEHOP](http://blogs.technet.com/srd/archive/2009/02/02/preventing-the-exploitation-of-seh-overwrites-with-sehop.aspx)

<a name="Bypassing_filter_and_protections" />
## Bypassing filter and protections
*Windows memory protections Bypass Methods Articles.*
+ [Third Generation Exploitation smashing heap on 2k](http://www.blackhat.com/presentations/win-usa-02/halvarflake-winsec02.ppt) by halvar Flake [2002]
+ [chris anley wrote Creating Arbitrary Shellcode In Unicode Expanded Strings](http://www.net-security.org/dl/articles/unicodebo.pdf)
+ [Dave aitel advanced windows exploitation](http://www.immunityinc.com/downloads/immunity_win32_exploitation.final2.ppt) [2003]
+ [Defeating the Stack Based Buffer Overflow Prevention Mechanism of Microsoft Windows 2003 Server](http://www.ngssoftware.com/papers/defeating-w2k3-stack-protection.pdf) by david litchfield
+ [reliable heap exploits and after that Windows Heap Exploitation (Win2KSP0 through WinXPSP2)](http://cybertech.net/~sh0ksh0k/projects/winheap/XPSP2%20Heap%20Exploitation.ppt) by matt Conover in cansecwest 2004
+ [Safely Searching Process Virtual Address Space](http://www.hick.org/code/skape/papers/egghunt-shellcode.pdf) by matt miller [2004]
+ [IE exploit and used a technology called Heap Spray](http://www.exploit-db.com/exploits/612)
+ [bypassing hardware-enforced DEP](http://www.uninformed.org/?v=2&a=4&t=pdf) by skape (matt miller) and Skywing (ken johnson) [October 2005]
+ [Exploiting Freelist[0] On XP Service Pack 2](http://www.orkspace.net/secdocs/Windows/Protection/Bypass/Exploiting%20Freelist%5B0%5D%20On%20XP%20Service%20Pack%202.pdf) by brett moore [2005]
+ [Kernel-mode Payloads on Windows in uninformed](http://www.uninformed.org/?v=3&a=4&t=pdf)
+ [Exploiting 802.11 Wireless Driver Vulnerabilities on Windows](http://www.uninformed.org/?v=6&a=2&t=pdf)
+ [Exploiting Comon Flaws In Drivers](http://www.reversemode.com/index.php?option=com_content&task=view&id=38&Itemid=1)
+ [Heap Feng Shui in JavaScript](http://www.blackhat.com/presentations/bh-europe-07/Sotirov/Presentation/bh-eu-07-sotirov-apr19.pdf) by Alexander sotirov [2007]
+ [Understanding and bypassing Windows Heap Protection](http://kkamagui.springnote.com/pages/1350732/attachments/579350) by Nicolas Waisman [2007]
+ [Heaps About Heaps](http://www.insomniasec.com/publications/Heaps_About_Heaps.ppt) by brett moore [2008]
+ [Bypassing browser memory protections in Windows Vista](http://taossa.com/archive/bh08sotirovdowd.pdf) by Mark Dowd and Alex Sotirov [2008]
+ [Attacking the Vista Heap](http://www.ruxcon.org.au/files/2008/hawkes_ruxcon.pdf) by ben hawkes [2008]
+ [Return oriented programming Exploitation without Code Injection](http://cseweb.ucsd.edu/~hovav/dist/blackhat08.pdf) by Hovav Shacham  (and others ) [2008]
+ [Token Kidnapping and a super reliable exploit for windows 2k3 and 2k8](http://www.argeniss.com/research/TokenKidnapping.pdf) by Cesar Cerrudo [2008]
+ [Defeating DEP Immunity Way](http://www.immunityinc.com/downloads/DEPLIB.pdf) by Pablo sole [2008]
+ [Practical Windows XP2003 Heap Exploitation](http://www.blackhat.com/presentations/bh-usa-09/MCDONALD/BHUSA09-McDonald-WindowsHeap-PAPER.pdf) by John McDonald and Chris Valasek [2009]
+ [Bypassing SEHOP](http://www.sysdream.com/articles/sehop_en.pdf) by Stefan Le Berre Damien Cauquil [2009]
+ [Interpreter Exploitation  : Pointer Inference and JIT Spraying](http://www.semantiscope.com/research/BHDC2010/BHDC-2010-Slides-v2.pdf) by Dionysus Blazakis[2010]
+ [write-up of Pwn2Own 2010](http://vreugdenhilresearch.nl/Pwn2Own-2010-Windows7-InternetExplorer8.pdf) by  Peter Vreugdenhil
+ [all in one 0day presented in rootedCON](http://wintercore.com/downloads/rootedcon_0day_english.pdf) by ruben santamarta [2010]

<a name="Typical_windows_exploits" />
## Typical windows exploits
+ [real-world HW-DEP bypass Exploit](http://www.exploit-db.com/exploits/3652) by devcode
+ [bypassing DEP by returning into HeapCreate](http://www.metasploit.com/redmine/projects/framework/repository/revisions/7246/entry/modules/exploits/windows/brightstor/mediasrv_sunrpc.rb) by toto
+ [first public ASLR bypass exploit by using partial overwrite ](http://www.metasploit.com/redmine/projects/framework/repository/entry/modules/exploits/windows/email/ani_loadimage_chunksize.rb) by skape
+ [heap spray and bypassing DEP](http://skypher.com/SkyLined/download/www.edup.tudelft.nl/%7Ebjwever/exploits/InternetExploiter2.zip) by skylined
+ [first public exploit that used ROP  for bypassing DEP in adobe lib TIFF vulnerability](http://www.metasploit.com/redmine/projects/framework/repository/revisions/8833/raw/modules/exploits/windows/fileformat/adobe_libtiff.rb)
+ [exploit codes of bypassing browsers memory protections](http://phreedom.org/research/bypassing-browser-memory-protections/bypassing-browser-memory-protections-code.zip)
+ [PoC’s on Tokken TokenKidnapping .  PoC for 2k3 -part 1](http://www.argeniss.com/research/Churrasco.zip) by Cesar Cerrudo
+ [PoC’s on Tokken TokenKidnapping .  PoC for 2k8 -part 2](http://www.argeniss.com/research/Churrasco2.zip) by Cesar Cerrudo
+ [an exploit works from win 3.1 to win 7](http://lock.cmpxchg8b.com/c0af0967d904cef2ad4db766a00bc6af/KiTrap0D.zip) by Tavis Ormandy KiTra0d
+ [old ms08-067 metasploit module multi-target and DEP bypass](http://metasploit.com/svn/framework3/trunk/modules/exploits/windows/smb/ms08_067_netapi.rb)
+ [PHP 6.0 Dev str_transliterate() Buffer overflow – NX + ASLR Bypass](http://www.exploit-db.com/exploits/12189)
+ [SMBv2 Exploit](http://www.metasploit.com/redmine/projects/framework/repository/revisions/8916/raw/modules/exploits/windows/smb/ms09_050_smb2_negotiate_func_index.rb) by Stephen Fewer


<a name="Exploit_development_tutorial_series" />
## Exploit development tutorial series
*Exploid Development Tutorial Series Base on Windows Operation System Articles.*
<a name="corelan" />
- Corelan Team
  + [Exploit writing tutorial part 1 : Stack Based Overflows](https://www.corelan.be/index.php/2009/07/19/exploit-writing-tutorial-part-1-stack-based-overflows/)
  + [Exploit writing tutorial part 2 : Stack Based Overflows – jumping to shellcode](https://www.corelan.be/index.php/2009/07/23/writing-buffer-overflow-exploits-a-quick-and-basic-tutorial-part-2/)
  + [Exploit writing tutorial part 3 : SEH Based Exploits](https://www.corelan.be/index.php/2009/07/25/writing-buffer-overflow-exploits-a-quick-and-basic-tutorial-part-3-seh/)
  + [Exploit writing tutorial part 3b : SEH Based Exploits – just another example](https://www.corelan.be/index.php/2009/07/28/seh-based-exploit-writing-tutorial-continued-just-another-example-part-3b/)
  + [Exploit writing tutorial part 4 : From Exploit to Metasploit – The basics](https://www.corelan.be/index.php/2009/08/12/exploit-writing-tutorials-part-4-from-exploit-to-metasploit-the-basics/)
  + [Exploit writing tutorial part 5 : How debugger modules & plugins can speed up basic exploit development](https://www.corelan.be/index.php/2009/09/05/exploit-writing-tutorial-part-5-how-debugger-modules-plugins-can-speed-up-basic-exploit-development/)
  + [Exploit writing tutorial part 6 : Bypassing Stack Cookies, SafeSeh, SEHOP, HW DEP and ASLR](https://www.corelan.be/index.php/2009/09/21/exploit-writing-tutorial-part-6-bypassing-stack-cookies-safeseh-hw-dep-and-aslr/)
  + [Exploit writing tutorial part 7 : Unicode – from 0x00410041 to calc](https://www.corelan.be/index.php/2009/11/06/exploit-writing-tutorial-part-7-unicode-from-0x00410041-to-calc/)
  + [Exploit writing tutorial part 8 : Win32 Egg Hunting](https://www.corelan.be/index.php/2010/01/09/exploit-writing-tutorial-part-8-win32-egg-hunting/)
  + [Exploit writing tutorial part 9 : Introduction to Win32 shellcoding](https://www.corelan.be/index.php/2010/02/25/exploit-writing-tutorial-part-9-introduction-to-win32-shellcoding/)
  + [Exploit writing tutorial part 10 : Chaining DEP with ROP – the Rubik’s Cube](https://www.corelan.be/index.php/2010/06/16/exploit-writing-tutorial-part-10-chaining-dep-with-rop-the-rubikstm-cube/)
  + [Exploit writing tutorial part 11 : Heap Spraying Demystified](https://www.corelan.be/index.php/2011/12/31/exploit-writing-tutorial-part-11-heap-spraying-demystified/)
<a name="fuzzysecurity" />
- Fuzzysecurity
  + [Part 1: Introduction to Exploit Development](https://www.fuzzysecurity.com/tutorials/expDev/1.html)
  + [Part 2: Saved Return Pointer Overflows](https://www.fuzzysecurity.com/tutorials/expDev/2.html)
  + [Part 3: Structured Exception Handler (SEH)](https://www.fuzzysecurity.com/tutorials/expDev/3.html)
  + [Part 4: Egg Hunters](https://www.fuzzysecurity.com/tutorials/expDev/4.html)
  + [Part 5: Unicode 0x00410041](https://www.fuzzysecurity.com/tutorials/expDev/5.html)
  + [Part 6: Writing W32 shellcode](https://www.fuzzysecurity.com/tutorials/expDev/6.html)
  + [Part 7: Return Oriented Programming](https://www.fuzzysecurity.com/tutorials/expDev/7.html)
  + [Part 8: Spraying the Heap [Chapter 1: Vanilla EIP]](https://www.fuzzysecurity.com/tutorials/expDev/8.html)
  + [Part 9: Spraying the Heap [Chapter 2: Use-After-Free]](https://www.fuzzysecurity.com/tutorials/expDev/11.html)
<a name="securitysift" />
- Securitysift
  + [Windows Exploit Development – Part 1: The Basics](http://www.securitysift.com/windows-exploit-development-part-1-basics/)
  + [Windows Exploit Development – Part 2: Intro to Stack Based Overflows](http://www.securitysift.com/windows-exploit-development-part-2-intro-stack-overflow/)
  + [Windows Exploit Development – Part 3: Changing Offsets and Rebased Modules](http://www.securitysift.com/windows-exploit-development-part-3-changing-offsets-and-rebased-modules/)
  + [Windows Exploit Development – Part 4: Locating Shellcode With Jumps](http://www.securitysift.com/windows-exploit-development-part-4-locating-shellcode-jumps/)
  + [Windows Exploit Development – Part 5: Locating Shellcode With Egghunting](http://www.securitysift.com/windows-exploit-development-part-5-locating-shellcode-egghunting/)
  + [Windows Exploit Development – Part 6: SEH Exploits](http://www.securitysift.com/windows-exploit-development-part-6-seh-exploits/)
  + [Windows Exploit Development – Part 7: Unicode Buffer Overflows](http://www.securitysift.com/windows-exploit-development-part-7-unicode-buffer-overflows/)

<a name="tools" />
## Tools
*Disassemblers, debuggers, and other static and dynamic analysis tools.*

+ [angr](https://github.com/angr/angr) - Platform-agnostic binary analysis
  framework developed at UCSB's Seclab.
+ [BARF](https://github.com/programa-stic/barf-project) - Multiplatform, open
  source Binary Analysis and Reverse engineering Framework.
+ [binnavi](https://github.com/google/binnavi) - Binary analysis IDE for
  reverse engineering based on graph visualization.
+ [Bokken](http://www.bokken.re/) - GUI for Pyew and Radare.
+ [Capstone](https://github.com/aquynh/capstone) - Disassembly framework for
  binary analysis and reversing, with support for many architectures and
  bindings in several languages.
+ [codebro](https://github.com/hugsy/codebro) - Web based code browser using
  clang to provide basic code analysis.
+ [dnSpy](https://github.com/0xd4d/dnSpy) - .NET assembly editor, decompiler
  and debugger.
+ [Evan's Debugger (EDB)](http://codef00.com/projects#debugger) - A
  modular debugger with a Qt GUI.
+ [GDB](http://www.sourceware.org/gdb/) - The GNU debugger.
+ [GEF](https://github.com/hugsy/gef) - GDB Enhanced Features, for exploiters
  and reverse engineers.
+ [hackers-grep](https://github.com/codypierce/hackers-grep) - A utility to
  search for strings in PE executables including imports, exports, and debug
  symbols.
+ [IDA Pro](https://www.hex-rays.com/products/ida/index.shtml) - Windows
  disassembler and debugger, with a free evaluation version.
+ [Immunity Debugger](http://debugger.immunityinc.com/) - Debugger for
  malware analysis and more, with a Python API.
+ [ltrace](http://ltrace.org/) - Dynamic analysis for Linux executables.
+ [objdump](https://en.wikipedia.org/wiki/Objdump) - Part of GNU binutils,
  for static analysis of Linux binaries.
+ [OllyDbg](http://www.ollydbg.de/) - An assembly-level debugger for Windows
  executables.
+ [PANDA](https://github.com/moyix/panda) - Platform for Architecture-Neutral Dynamic Analysis
+ [PEDA](https://github.com/longld/peda) - Python Exploit Development
  Assistance for GDB, an enhanced display with added commands.
+ [pestudio](https://winitor.com/) - Perform static analysis of Windows
  executables.
+ [Process Monitor](https://technet.microsoft.com/en-us/sysinternals/bb896645.aspx) -
  Advanced monitoring tool for Windows programs.
+ [Pyew](https://github.com/joxeankoret/pyew) - Python tool for malware
  analysis.
+ [Radare2](http://www.radare.org/r/) - Reverse engineering framework, with
  debugger support.
+ [SMRT](https://github.com/pidydx/SMRT) - Sublime Malware Research Tool, a
  plugin for Sublime 3 to aid with malware analyis.
+ [strace](http://sourceforge.net/projects/strace/) - Dynamic analysis for
  Linux executables.
+ [Udis86](https://github.com/vmt/udis86) - Disassembler library and tool
  for x86 and x86_64.
+ [Vivisect](https://github.com/vivisect/vivisect) - Python tool for
  malware analysis.
+ [X64dbg](https://github.com/x64dbg/) - An open-source x64/x32 debugger for windows.
