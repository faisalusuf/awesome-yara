# Awesome YARA

A curated list of awesome [YARA](https://virustotal.github.io/yara/) rules, tools,
and resources. Inspired by [awesome-python](https://github.com/vinta/awesome-python)
and [awesome-php](https://github.com/ziadoz/awesome-php).


[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

- [Awesome YARA](#awesome-yara)
   
    - [Rules](#rules)
   
    - [Tools](#tools)
       
    - [Services](#services)
   
    - [People](#people)
   
    - [Related Awesome Lists](#related-awesome-lists)
   
    - [Contributing](#contributing)

### Legend

| Icon | Meaning |
|---|---|
| :trophy: | Biggest collection |
| :fire: | Actively maintained |
| :gem: | Great content |
| :sparkles: | Recently added |

## Rules

* [0day1day Rules](https://github.com/0day1day/yarasigs)
    - A few signatures from various sources.
* [AlienVault Labs Rules](https://github.com/jaimeblasco/AlienvaultLabs/tree/master/malware_analysis)
    - Malware rules from AlienVault Labs.
* [BinaryAlert YARA Rules](https://github.com/airbnb/binaryalert/tree/master/rules)
    - Rules bundled into AirBnB's BinaryAlert tool.
* [Burp YARA Rules](https://github.com/codewatchorg/Burp-Yara-Rules)
    - Intended to be used with the Burp Yara-Scanner extension.
* [Brian Carter Rules](https://github.com/carterb/yararules)
    - Rules for YARA. Mostly for use with VirusTotal.
* [CAPE Rules](https://github.com/ctxis/CAPE/tree/master/data/yara/CAPE)
    - Rules from various authors bundled with the Config And Payload Extraction Cuckoo Sandbox extension.
* [CDI Rules](https://github.com/CyberDefenses/CDI_yara)
    - A few rules published by CyberDefenses.
* [Citizen Lab Malware Signatures](https://github.com/citizenlab/malware-signatures)
    - YARA signatures developed by Citizen Lab.
* [Dan Borges Rules](https://github.com/ahhh/YARA)
    - Rules for identifying features of binaries for deeper inspection.
* [Didier Stevens Rules](https://blog.didierstevens.com/2014/12/16/yara-rules/) :gem:
    - A couple rules published by Didier Stevens.
* [ESET IOCs](https://github.com/eset/malware-ioc/)
    - YARA and Snort rules from IOCs collected by ESET.
* [Fidelis Rules](https://github.com/fideliscyber/indicators/tree/master/yararules)
    - YARA rules from Fidelis Cyber's IOC repo.
* [Florian Roth Rules](https://github.com/Neo23x0/signature-base/tree/master/yara) :fire: :gem:
    - Rules provided in Florian Roth's signature base repository.
* [FSF Rules](https://github.com/EmersonElectricCo/fsf/tree/master/fsf-server/yara)
    - Mostly filetype detection rules, from the EmersonElectricCo FSF project.
* [GoDaddy Rules](https://github.com/godaddy/yara-rules)
    - Written for use with ProcFilter.
* [h3x2b Rules](https://github.com/h3x2b/yara-rules)
    - A collection of signatures from h3x2b.
* [Icewater Rules](https://github.com/SupportIntelligence/Icewater)
    - Repository of YARA rules generated by a malware classification algorithm, similar to AI and learning approaches.
* [InQuest Rules](https://github.com/InQuest/yara-rules)
    - A collection of YARA rules we wish to share with the world.
* [Kevin Falcoz Rules](https://github.com/0pc0deFR/YaraRules)
    - Small collection of malware-related rules.
* [kevthehermit Rules](https://github.com/kevthehermit/YaraRules)
    - A few dozen malware rules.
* [NCC Group Rules](https://github.com/nccgroup/Cyber-Defence/tree/master/Signatures/yara)
    - A few publicly released rules from NCC Group's Cyber Defence team.
* [Malice.IO YARA Plugin Rules](https://github.com/malice-plugins/yara/tree/master/rules)
    - Collected rules from various authors.
* [mikesxrs YARA Rules Collection](https://github.com/mikesxrs/Open-Source-YARA-rules) :trophy:
    - Large collection of open source rules from various authors.
* [Patrick Olsen Rules](https://github.com/sysforensics/YaraRules)
    - Miscellaneous YARA rules.
* [SpiderLabs Rules](https://github.com/SpiderLabs/malware-analysis/tree/master/Yara)
    - A few malware rules published by SpiderLabs.
* [Tenable Rules](https://github.com/tenable/yara-rules)
    - Small collection from Tenable Network Security.
* [VectraThreatLab Rules](https://github.com/VectraThreatLab/reyara)
    - YARA rules for identifying anti-RE malware techniques.
* [x64dbg Signatures](https://github.com/x64dbg/yarasigs)
    - A few signatures to possibly be included in x64dbg.
* [YARA-FORENSICS](https://github.com/Xumeiquer/yara-forensics)
    - Rules for finding files using magic headers.
* [YaraRules Project Official Repo](https://github.com/Yara-Rules/rules) :fire:
    - Large collection of rules constantly updated by the community.

## Tools

* [AirBnB BinaryAlert](https://github.com/airbnb/binaryalert)
    - Open-source serverless AWS pipeline where any file uploaded to an S3 bucket is immediately scanned with a configurable set of YARA rules.
* [findcrypt-yara](https://github.com/polymorf/findcrypt-yara)
    - IDA pro plugin to find crypto constants (and more).
* [File Scanning Framework (FSF)](https://github.com/EmersonElectricCo/fsf)
    - Modular, recursive file scanning solution.
* [InQuest ThreatKB](https://github.com/InQuest/ThreatKB)
    - Knowledge base workflow management for YARA rules and C2 artifacts (IP, DNS, SSL).
* [Laika BOSS](https://github.com/lmco/laikaboss)
    - Object scanner and intrusion detection system that strives to achieve the following goals: Scalable, Flexible, Verbose. ([whitepaper](http://lockheedmartin.com/content/dam/lockheed/data/isgs/documents/LaikaBOSS%20Whitepaper.pdf))
* [Loki](https://github.com/Neo23x0/Loki)
    - Simple IOC and YARA rule scanner.
* [MITRE MultiScanner](https://github.com/mitre/multiscanner)
    - File analysis framework that assists the user in evaluating a set of files by automatically running a suite of tools for the user and aggregating the output.
* [OCYara](https://github.com/bandrel/OCyara)
    - Performs OCR on image files and scans them for matches to YARA rules.
* [PasteHunter](https://github.com/kevthehermit/PasteHunter)
    - Scan pastebin.com with YARA rules.
* [ProcFilter](https://github.com/godaddy/procfilter)
    - Helps create YARA signatures that protect Windows environments against a specific threat.
* [stoQ](https://github.com/PUNCH-Cyber/stoq)
    - Modular and highly customizable framework for the creation of data sets from multiple disparate data sources.
* [yabin](https://github.com/AlienVault-OTX/yabin)
    - Creates YARA signatures from executable code within malware.
* [YaraGenerator](https://github.com/Xen0ph0n/YaraGenerator)
    - Quick, simple, and effective yara rule creation to isolate malware families and other malicious objects of interest.
* [YaraGuardian](https://github.com/PUNCH-Cyber/YaraGuardian)
    - Django web inerface for managing YARA rules.
* [yaraMail](https://github.com/kevthehermit/yaraMail)
    - YARA scanner for IMAP feeds and saved streams.
* [YaraManager](https://github.com/kevthehermit/YaraManager)
    - Web based manager for YARA rules.
* [yarAnalyzer](https://github.com/Neo23x0/yarAnalyzer)
    - YARA rule set coverage analyzer.
* [yaraPCAP](https://github.com/kevthehermit/YaraPcap)
    - YARA scanner For IMAP feeds and saved streams.
* [Yara Python ICAP Server](https://github.com/RamadhanAmizudin/python-icap-yara)
    - ICAP server with YARA scanner.
* [Yara-Scanner](https://github.com/PolitoInc/Yara-Scanner)
    - Python-based extension that integrates a YARA scanner into Burp Suite.
* [Yara-Validator](https://github.com/CIRCL/yara-validator)
    - Validates YARA rules and tries to repair the broken ones.
* [yarGen](https://github.com/Neo23x0/yarGen)
    - YARA rule generator for finding related samples and hunting.
* [Yeti](https://github.com/yeti-platform/yeti)
    - Platform meant to organize observables, indicators of compromise, TTPs, and knowledge on threats in a single, unified repository.
* [yextend](https://github.com/BayshoreNetworks/yextend)
    - YARA integrated software to handle archive file data.

### Services

* [MalShare](https://malshare.com/)
    - Free malware repository providing researchers access to samples, malicous feeds, and YARA results.
* [YaraEditor (Web)](https://www.adlice.com/download/yaraeditorweb/)
    - All-in-one website to create and manage YARA rules.
* [YaraRules Analyzer](https://analysis.yararules.com/)
    - Upload and run files against rulesets from the YaraRules Project.

## People

Check out InQuest's [awesome-yara Twitter list](https://twitter.com/InQuest/lists/awesome-yara).

## Related Awesome Lists

* [Crawler](https://github.com/BruceDone/awesome-crawler)
* [CVE PoC](https://github.com/qazbnm456/awesome-cve-poc)
* [Forensics](https://github.com/Cugu/awesome-forensics)
* [Hacking](https://github.com/carpedm20/awesome-hacking)
* [Honeypots](https://github.com/paralax/awesome-honeypots)
* [Incident-Response](https://github.com/meirwah/awesome-incident-response)
* [Infosec](https://github.com/onlurking/awesome-infosec)
* [IOCs](https://github.com/sroberts/awesome-iocs)
* [Malware Analysis](https://github.com/rshipp/awesome-malware-analysis)
* [ML for Cyber Security](https://github.com/jivoi/awesome-ml-for-cybersecurity)
* [OSINT](https://github.com/jivoi/awesome-osint)
* [PCAP Tools](https://github.com/caesar0301/awesome-pcaptools)
* [Pentesting](https://github.com/enaqx/awesome-pentest)
* [Security](https://github.com/sbilly/awesome-security)
* [Static Analysis](https://github.com/mre/awesome-static-analysis)
* [Threat Intelligence](https://github.com/hslatman/awesome-threat-intelligence)

## Contributing

Pull requests and issues with suggestions are welcome! Please try to keep your changes
cleanly formatted and alphabetized. By submitting a PR you agree to release your
contributions under the terms of the [LICENSE](LICENSE).
