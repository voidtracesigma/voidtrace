# Benchmarking Practices in LLM-driven Offensive Security: Testbeds, Metrics, and Experiment Design


Getting pwned by AI [13]                    R VM R lin.security 1 ? ✓ localhost
LLMs as Hackers [16]                        S VM R THM 12 ✓ 12 ✓ localhost
Autonomously Hack Websites [10]             S C 15 15 ✓ single-host
Autonomously Exploit One-day Vulns. [9]     S D CVEs 15 15 ✓ ✓ ✓ single-host
Exploit Zero-Day Vulnerabilities [11]       S D CVEs 15 15 ✓ single-host
PenHeal [18]                                R VM R metasploitable 1 10 ✓ ✓ single-host
AUTOPENBENCH [12]                           S C R basic + CVEs 33 ✓ 33 ✓ ✓ ✓ single-host
HackSynth [29]                              R R picoCTF, OTW 200 200 ✓ ✓ ✓ single-host
Vulnbot [24]                                B - [12, 19] single-host
Multistage Network Attacks [38]             S R VulnHub 13 ✓ 152 ✓ network
pentestGPT [7]                              R VM R HTB, VulnHub 13 ✓ 182 ✓ ✓ ✓ single-host
Can LLMs hack Enterprise Networks? [15]     R VM R GOAD 15+ ✓ ? ✓ network
Towards Automated Penetration Testing [19]  S VM R VulnHub 13 162 ✓ single-host
AutoAttacker [44]                           S VM C 14 14 ✓ ✓ single-host
CyBench [47]                                S C R CTFs 40 ✓ ✓ ✓ ✓ single-host
NYU CTF Dataset [36, 37]                    S C R CTFs 26 ✓ ✓ single-host
RapidPen [31]                               R VM R HTB 1 ✓ single-host
AutoPT [42]                                 R VM R VulnHub 17 20 ✓ single-host



`entries`:
CyBench      [47]   - run_task.py run_benchmark.py
AutoPenBench [12]   - cli.py
RapidPen     [31]   - wish_cli.main:main
cochise      [15]   - src/cochise.py	src/wintermute.py	
Vulnbot      [24]   - cli.py: startup_main pentest_main pentestgpt_main


