---
layout: base
title: Research
permalink: /research/
---

## Why am I receiving ICMP probes from this host?

These ICMP (ping) probes are part of a long-term computer science research project at the University of California, Los Angeles. The goal of this project is to measure global Internet reachability, monitor the health of the network, and study trends in routing and connectivity. To do this, we send standard ICMP Echo Request packets to a subset of publicly reachable IPv4 address. Hosts may receive multiple probes per day in order to study network stability and packet-loss patterns.

ICMP Echo Requests are harmless diagnostic packets used routinely by system administrators and network operators. The only data we receive is the basic ICMP Echo Reply information that any host exposes when responding to a ping.

## Why are you collecting this data?

All information collected through these probes consists solely of publicly visible network reachability data—specifically whether a host responds to ICMP Echo Requests and basic metadata such as round-trip time.

This data helps researchers understand:
- global Internet availability
- packet loss and latency trends
- how connectivity changes over time due to outages, misconfigurations, or infrastructure events

These measurements support research on Internet reliability and network topology changes in global connectivity. Aggregated results will be shared with the research community to support reproducible scientific work.

## Can I opt out of these measurements?

These measurements help improve understanding of global Internet performance and reliability. However, if you do not wish to participate, you can configure your firewall or router to drop ICMP Echo Requests originating from the subnet used for this research:

`169.232.20.16/28`

If you have additional questions or believe you received probes in error, please contact:

ucla.scan@gmail.com
