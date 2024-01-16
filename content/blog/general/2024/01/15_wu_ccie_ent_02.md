+++
title = "Weekly Update 02: CCIE"
date = "2024-01-15"
author = "Steve"
cover = ""
description = ""
tags = ["Cisco", "CCIE-EI" ]
toc = false
draft = false
+++

## TIME

| Study Time     | Hours               |
|:---------------|:--------------------|
| **Last week**  | 31 hours 40 minutes |
| **This week**  | 33 hours 45 minutes |
| **2024 total** | 65 hours 25 minutes |

&nbsp;

## FOCUS 

Below are the core focus areas where I endeavour to hit one of the four sections each day. Other work will have been done if additional time becomes available, for example, while commuting or on lunch break at work. Different tasks include but are not limited to, flashcards, interleaving previous labs, reviewing notes, and researching available study materials for upcoming topics and weak areas.

&nbsp;

```YAML
| LABBING 
___________________________________________________________________________________________________
# INE CCIE R&S ATC: Foundation Lab 01 (Section 1-4 LAN, WAN, IGP)
# INE CCIE R&S ATC: Foundation Lab 01 (Section 5-7 Exterior Routing, DMVPN, IPv6)
# INE CCIE R&S ATC: Foundation Lab 02 (Section 1-4 LAN, WAN, IGP)
# INE CCIE R&S ATC: Foundation Lab 02 (Section 5-8 Exterior Routing, DMVPN, MPLS, IPv6)
# INE CCIE R&S ATC: Foundation Lab 03 (Section 1-4 LAN, DMVPN, IGP, Redistribution)
# INE CCIE R&S ATC: Foundation Lab 03 (Section 5-7 Ext. Routing, MPLS, IPv6)

| ACTIVE RECALL
___________________________________________________________________________________________________
# IGP - Redistributing a Subset of Routes Using a Route Map
# IGP - Mutual Redistribution at Multiple Routers 
# IGP - Preventing Suboptimal Routes by Setting Admin Distance & using Route Tags
# IGP - Using Metric and Metric Types to influence redistributed routes 
# IGP - Route Summarisation
# IGP - Default Routes

| READING 
___________________________________________________________________________________________________
# Developing IP Multicast Networks (Ch 01. A Brief History)
# Developing IP Multicast Networks (Ch 01. The Pros and Cons of IP Multicast)
# Developing IP Multicast Networks (Ch 01. Multicast Applications)
# Developing IP Multicast Networks (Ch 02. IP and MAC Addresses)
# Developing IP Multicast Networks (Ch 02. Distribution Trees)
# Developing IP Multicast Networks (Ch 02. Reverse Path Forwarding)
# Developing IP Multicast Networks (Ch 02. Forwarding Cache)

| VIDEOS 
___________________________________________________________________________________________________
# INE CCIE R&S ATC: MPLS (Layer 3 VPN Verification)
# INE CCIE R&S ATC: MPLS (Layer 3 VPN Troubleshooting, Part 1)
# INE CCIE R&S ATC: MPLS (Layer 3 VPN Troubleshooting, Part 2)
# INE CCIE R&S ATC: MPLS (Layer 3 VPN PE-CE Routing with EIGRP)
# INE CCIE R&S ATC: MPLS (Layer 3 VPN PE-CE Routing with OSPF)
# INE CCIE R&S ATC: MPLS (Layer 3 VPN PE-CE Routing with BGP)
# INE CCIE R&S ATC: MPLS (Multipath for MPLS L3VPN)
```
&nbsp;

## SUMMARY 

I had some issues with redistribution on the INE Foundation Lab #3. The task had multiple redistribution points and a routing loop issue. I had to look up the answers for the task in the workbook, but when applying the correct configuration, I could still observe the problem. Clearing the routing table (```clear ip route *```) on all routers allowed for the MP-BGP loopbacks to come up, but only temporarily. I don't know if this is an EVE-NG thing or the order of operations when applying the configuration.

The Developing IP Multicast Networks book has been an easy read so far over the first two chapters. The total reading time is 3 hours and 11 minutes so far. 

I need to improve on the Active Recall topics. This is the book's last chapter (OCG CCIE R&S v5.0, Vol 1), and I think I will cover SD-WAN material before moving on to OCG CCIE R&S v5.0 Volume 2.  

&nbsp;

## CHECKLIST

+ ```2023-01-07``` ```book``` Cisco IP Routing: Packet Forwarding and Intra-domain Routing Protocols
+ ```2023-01-08``` ```labs``` INE CCIE R&S Advanced Technology Labs Workbook
+ ```2023-01-09``` ```labs``` INE CCIE R&S Foundation Lab #1
+ ```2023-01-11``` ```labs``` INE CCIE R&S Foundation Lab #2
+ ```2023-01-14``` ```labs``` INE CCIE R&S Foundation Lab #3
