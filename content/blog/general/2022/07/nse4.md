+++
title = "Fortinet NSE4"
date = "2022-07-01"
author = "Steve"
cover = ""
description = ""
tags = ["Fortinet", "NSE4" ]
toc = true
draft = false
+++

&nbsp;
_________________

I passed the Fortinet NSE 4 exam today. This blog post will describe the exam, how I approached the topics and my experience of the exam itself.

## What is the NSE4?

Fortinet describes the NSE4 as ideal for Network Security Administrators, Technical Support Engineers, and System Engineers. It is placed on the second tier of the certification pyramid with Fortinet.

> _"NSE 4 identifies your ability to configure, install, and manage the day-to-day configuration, monitoring, and operation of a FortiGate device to support specific corporate network security policies. "_
&nbsp;

## Exam Topics

- **FortiGate deployment**
	- Perform initial configuration
	- Implement the Fortinet Security Fabric
	- Configure log settings and diagnose problems using the logs
	- Describe and configure VDOMs to split a FortiGate into multiple virtual devices
	- Identify and configure different operation modes for an FGCP HA cluster
	- Diagnose resource and connectivity problems
- **Firewall and authentication**
	- Identify and configure how firewall policy NAT and central NAT works
	- Identify and configure different methods of firewall authentication
	- Explain FSSO deployment and configuration
- **Content inspection**
	- Describe and inspect encrypted traffic using certificates
	- Identify FortiGate inspection modes and configure web and DNS filtering
	- Configure application control to monitor and control network applications
	- Explain and configure antivirus scanning modes to neutralize malware threats
	- Configure IPS, DoS, and WAF to protect the network from hacking and DDoS attacks
- **Routing and Layer 2 switching**
	- Configure and route packets using static and policy-based routes
	- Configure SD-WAN to load balance traffic between multiple WAN links effectively
	- Configure FortiGate interfaces or VDOMs to operate as Layer 2 devices
-**VPN**
	- Configure and implement different SSL-VPN modes to provide secure access to the private network
	- Implement a meshed or partially redundant IPsec VPN

&nbsp;

## Study Resources

Working for a Fortinet Partner, I was given access to their training institute portal to enrol on the following two courses:

- NSE 4 FortiGate Security 7.0
- NSE 4 FortiGate Infrastructure 7.0

I understand that access to their training institute was made available to the public for free during the COVID pandemic. The courses were straightforward in that they were text-to-speech narrated videos of animated PowerPoint slides, and at the end of each module were questions to test your knowledge. Each course had a supplementary Study Guide in PDF format, which included the slides used in the videos and the audio transcript if you preferred to read.

Additionally, I purchased two hardcover books authored by Daniel Howard from Amazon:

- [Introduction to FortiGate Part-I Infrastructure NSE4 Study Guide](https://www.amazon.co.uk/gp/product/B08QRKVDPV/ref=dbs_a_def_rwt_hsch_vapi_tu00_p1_i1)
- [Introduction to FortiGate Part-II Infrastructure NSE4 Study Guide](https://www.amazon.co.uk/gp/product/B08QS549Q7?ref_=dbs_m_mng_rwt_calw_thcv_1&storeType=ebooks)

These books were useful but not essential to pass the NSE 4 exam. They were written based on an older version of FortiOS (6.4), but the concepts and examples given are valuable for real-world scenarios.

Lastly, like when studying for any other exam, hands-on experience or labbing is invaluable. I was able to do some practice labbing on EVE-NG using FortiGate (FGT), FortiManager (FMG), and FortiAnalyzer (FAZ). However, it was limited, and I could not practice the UTM functionality without additional licences, but my exposure at work day-to-day mitigated this.

At the time, there weren't any on-demand video courses from any IT training providers that I could find online. This has since changed with [CBT Nuggets](https://www.cbtnuggets.com) and [INE](https://ine.com) launching some content in recent months.

&nbsp;

## Exam Experience

The exam was scheduled via PearsonVUE and was sat in person at a local test centre. PearsonVUE has been offering options to take the exams remotely, but I have heard nothing but poor user experiences and decided to have one less worry and continue with my traditional routine of attending a test centre to take the exam (and future exams).

|           |                            |
|-----------|----------------------------|
| **Exam name** | Fortinet NSE 4—FortiOS 7.0 |
| **Exam series** | NSE4_FGT-7.0 |
| **Time allowed** | 105 minutes |
| **Exam questions** | 60 multiple-choice questions |
| **Scoring** | Pass or fail, a score report is available from your Pearson VUE account |
| **Language** | English or Japanese |
| **Product version** | FortiOS 7.0 |

I found the exam to be fair on reflection. I likely over-studied for it due to the breadth of topics combined with challenges at work when working on the hardware on production networks. There was an element of perfection paralysis when getting started, as I had the desire to try some different study methodologies, but this did not materialise due to the lack of learning resources available. In terms of difficulty, I found the NSE 4 easier than the CCNA Security exam I sat, but this is not a fair comparison on my part as I now have many more years of experience under my belt. In terms of difficulty when comparing the certification pyramid with Cisco, I would place the NSE 4, or 'technical' tier of Fortinet exams, between Cisco's now discontinued CCENT and the CCNA.

&nbsp;

## Conclusion

The NSE 4 is definitely a worthwhile endeavour if you are working with Fortinet equipment day to day. The only drawback for me is that the Fortinet NSE 1 - 7 certifications have a validity period of two years, and only their NSE 8 certification (expert tier) has a validity period of three years. When recertification comes around, I will consider going for the NSE 7. I do not have to obtain the NSE 5 or NSE 6 as a prerequisite, but achieving NSE 7 would automatically renew NSE 4, 5, and 6 certifications.
