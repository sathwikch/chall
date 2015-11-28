# awesome-windows-exploitation
A curated list of awesome Windows Exploitation resources, and shiny things. Inspired by awesom

## Tutorials

### windows stack overflows
+ [Win32 Buffer Overflows (Location, Exploitation and Prevention) by dark spyrit in 1999](http://www.phrack.com/issues.html?issue=55&id=15#article)
+ [S.K Chong Win32 Stack Based Buffer Overflow Walkthrough  in july 2002](http://www.scan-associates.net/papers/win32_bo_walkthrough.txt)
+ [Nish Bhalla’s series on  Writing Stack Based Overflows on Windows in 2005](http://www.packetstormsecurity.org/papers/win/)

### windows heap overflows
+ [Third Generation Exploitation smashing heap on 2k by halvar Flake in 2002](http://www.blackhat.com/presentations/win-usa-02/halvarflake-winsec02.ppt)
+ [Exploiting the MSRPC Heap Overflow two part by Dave Aitel (MS03-026) sep 2003](http://freeworld.thc.org/root/docs/exploit_writing/msrpcheap.pdf)
+ [Exploiting the MSRPC Heap Overflow two part by Dave Aitel (MS03-026) sep 2003](http://freeworld.thc.org/root/docs/exploit_writing/msrpcheap2.pdf)
+ [david litchfield did a great detailed penetration in black hat 2004](https://www.blackhat.com/presentations/win-usa-04/bh-win-04-litchfield/bh-win-04-litchfield.ppt)

### kernel based Windows overflows
+ [how to attack kernel based vulns on windows was done by a Polish group called “sec-labs” around 2003](http://www.derkeiler.com/Mailing-Lists/Full-Disclosure/2003-08/0101.html)
+ [sec-lab old whitepaper](http://www.artofhacking.com/tucops/hack/windows/live/aoh_win32dcv.htm)
+ [sec-lab old exploit](http://www.securityfocus.com/bid/8329/info)
+ [Windows Local Kernel Exploitation by S.K Chong in 2004 (based on sec-lab research)](http://www.packetstormsecurity.org/hitb04/hitb04-sk-chong.pdf)
+ [How to exploit Windows kernel memory pool in 2005 by SoBeIt](http://packetstormsecurity.nl/Xcon2005/Xcon2005_SoBeIt.pdf)
+ [exploiting remote kernel overflows in windows by eeye security](http://research.eeye.com/html/papers/download/StepIntoTheRing.pdf)
+ [Kernel-mode Payloads on Windows in uninformed by matt miller](http://www.uninformed.org/?v=3&a=4&t=pdf)
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

### Windows memory protections
+ [Data Execution Prevention](http://support.microsoft.com/kb/875352)
+ [/GS (Buffer Security Check)](http://msdn.microsoft.com/en-us/library/Aa290051)
+ [/SAFESEH](http://msdn.microsoft.com/en-us/library/9a89h429(VS.80).aspx)
+ [ASLR](http://blogs.msdn.com/michael_howard/archive/2006/05/26/address-space-layout-randomization-in-windows-vista.aspx)
+ [SEHOP](http://blogs.technet.com/srd/archive/2009/02/02/preventing-the-exploitation-of-seh-overwrites-with-sehop.aspx)

### Bypassing filter and protections
+ [Third Generation Exploitation smashing heap on 2k by halvar Flake in 2002](http://www.blackhat.com/presentations/win-usa-02/halvarflake-winsec02.ppt)
+ [chris anley wrote Creating Arbitrary Shellcode In Unicode Expanded Strings](http://www.net-security.org/dl/articles/unicodebo.pdf)
+ [Dave aitel advanced windows exploitation in 2003 ](http://www.immunityinc.com/downloads/immunity_win32_exploitation.final2.ppt)
+ [Defeating the Stack Based Buffer Overflow Prevention Mechanism of Microsoft Windows 2003 Server by david litchfield](http://www.ngssoftware.com/papers/defeating-w2k3-stack-protection.pdf)
+ [reliable heap exploits  (matt Conover  in cansecwest 2004 ) and after that Windows Heap Exploitation (Win2KSP0 through WinXPSP2)](http://cybertech.net/~sh0ksh0k/projects/winheap/XPSP2%20Heap%20Exploitation.ppt)
+ [later in 2004 matt miller wrote an article Safely Searching Process Virtual Address Space](http://www.hick.org/code/skape/papers/egghunt-shellcode.pdf)
+ [IE exploit and used a technology called Heap Spray](http://www.exploit-db.com/exploits/612)
+ [bypassing hardware-enforced DEP skape (matt miller) Skywing (ken johnson) (in October 2005](http://www.uninformed.org/?v=2&a=4&t=pdf)
+ [Exploiting Freelist[0] On XP Service Pack 2 by brett moore (dec 2005)](http://www.orkspace.net/secdocs/Windows/Protection/Bypass/Exploiting%20Freelist%5B0%5D%20On%20XP%20Service%20Pack%202.pdf)
+ [Kernel-mode Payloads on Windows in uninformed](http://www.uninformed.org/?v=3&a=4&t=pdf)
+ [Exploiting 802.11 Wireless Driver Vulnerabilities on Windows](http://www.uninformed.org/?v=6&a=2&t=pdf)
+ [Exploiting Comon Flaws In Drivers](http://www.reversemode.com/index.php?option=com_content&task=view&id=38&Itemid=1)
+ [Heap Feng Shui in JavaScript by Alexander sotirov (2007)](http://www.blackhat.com/presentations/bh-europe-07/Sotirov/Presentation/bh-eu-07-sotirov-apr19.pdf)
+ [Understanding and bypassing Windows Heap Protection by Nicolas Waisman (2007)](http://kkamagui.springnote.com/pages/1350732/attachments/579350)
+ [Heaps About Heaps by brett moore (in 2008)](http://www.insomniasec.com/publications/Heaps_About_Heaps.ppt)
+ [Bypassing browser memory protections in Windows Vista  by Mark Dowd and Alex Sotirov (in 2008)](http://taossa.com/archive/bh08sotirovdowd.pdf)
+ [Attacking the Vista Heap by ben hawkes (in 2008)](http://www.ruxcon.org.au/files/2008/hawkes_ruxcon.pdf)
+ [Return oriented programming Exploitation without Code Injection by Hovav Shacham  (and others ) (in 2008)](http://cseweb.ucsd.edu/~hovav/dist/blackhat08.pdf)
+ [Cesar Cerrudo wrote Token Kidnapping and a super reliable exploit for windows 2k3 and 2k8 (2008)](http://www.argeniss.com/research/TokenKidnapping.pdf)
+ [Defeating DEP Immunity Way by Pablo sole (2008)](http://www.immunityinc.com/downloads/DEPLIB.pdf)
+ [Practical Windows XP2003 Heap Exploitation (bh 2009) by John McDonald and Chris Valasek](http://www.blackhat.com/presentations/bh-usa-09/MCDONALD/BHUSA09-McDonald-WindowsHeap-PAPER.pdf)
+ [Bypassing SEHOP  by Stefan Le Berre Damien Cauquil (in 2009)](http://www.sysdream.com/articles/sehop_en.pdf)
+ [Interpreter Exploitation  : Pointer Inference and JIT Spraying by Dionysus Blazakis (2010)](http://www.semantiscope.com/research/BHDC2010/BHDC-2010-Slides-v2.pdf)
+ [write-up of Pwn2Own 2010 by  Peter Vreugdenhil (2010)](http://vreugdenhilresearch.nl/Pwn2Own-2010-Windows7-InternetExplorer8.pdf)
+ [ruben santamarta all in one 0day presented in rootedCON (2010)](http://wintercore.com/downloads/rootedcon_0day_english.pdf)

### Typical windows exploits
+ [real-world HW-DEP bypass Exploit by devcode](http://www.exploit-db.com/exploits/3652)
+ [bypassing DEP by returning into HeapCreate by toto](http://www.metasploit.com/redmine/projects/framework/repository/revisions/7246/entry/modules/exploits/windows/brightstor/mediasrv_sunrpc.rb)
+ [first public ASLR bypass exploit by using partial overwrite  by skape](http://www.metasploit.com/redmine/projects/framework/repository/entry/modules/exploits/windows/email/ani_loadimage_chunksize.rb)
+ [heap spray and bypassing DEP by skylined](http://skypher.com/SkyLined/download/www.edup.tudelft.nl/%7Ebjwever/exploits/InternetExploiter2.zip)
+ [first public exploit that used ROP  for bypassing DEP in adobe lib TIFF vulnerability](http://www.metasploit.com/redmine/projects/framework/repository/revisions/8833/raw/modules/exploits/windows/fileformat/adobe_libtiff.rb)
+ [exploit codes of bypassing browsers memory protections](http://phreedom.org/research/bypassing-browser-memory-protections/bypassing-browser-memory-protections-code.zip)
+ [Cesar Cerrudo PoC’s on Tokken TokenKidnapping .  PoC for 2k3](http://www.argeniss.com/research/Churrasco.zip)
+ [Cesar Cerrudo PoC’s on Tokken TokenKidnapping .  PoC for 2k8](http://www.argeniss.com/research/Churrasco2.zip)
+ [Tavis Ormandy KiTra0d an exploit works from win 3.1 to win 7](http://lock.cmpxchg8b.com/c0af0967d904cef2ad4db766a00bc6af/KiTrap0D.zip)
+ [old ms08-067 metasploit module multi-target and DEP bypass](http://metasploit.com/svn/framework3/trunk/modules/exploits/windows/smb/ms08_067_netapi.rb)
+ [PHP 6.0 Dev str_transliterate() Buffer overflow – NX + ASLR Bypass](http://www.exploit-db.com/exploits/12189)
+ [Stephen Fewer SMBv2 Exploit](http://www.metasploit.com/redmine/projects/framework/repository/revisions/8916/raw/modules/exploits/windows/smb/ms09_050_smb2_negotiate_func_index.rb)
