---
title: "Toolkit Usage Overview"
permalink: /docs/user/overview/
excerpt: "How to use this toolkit."
last_modified_at: 2017-08-04T12:37:48-04:00
redirect_from:
   - /theme-setup/
sidebar:
   nav: "userdocs"
---
{% include toc %}
{%include editme %}

The Cybersecurity Toolkit provides operators that are capable of analyzing network traffic and detecting suspicious behaviour.

In order to get started with using the Cybersecurity Toolkit, it is highly recommended that the sample applications be used as a baseline for building cybersecurity applications. In many cases, the data must be pre-processed (filtered and enriched) prior to be being analyzed, otherwise the analytics will not work correctly. The sample applications contain the necessary pre-processing operators that enable the analytics to work properly. The three introductory sample projects are:

* DomainProfiling - Detects suspicious behaviour based on profiles built using domains found in DNS response traffic.
* HostProfiling - Detects suspicious behaviour based on profiles built using hosts found in DNS response traffic.
* PredictiveBlacklisting - Predicts where a domain should be added to a blacklist.


## SPLDOC

[Toolkit](https://ibmstreams.github.io/streamsx.cybersecurity.starterApps/doc/tkspldoc/html/)

[Samples](https://ibmstreams.github.io/streamsx.cybersecurity.starterApps/doc/spldoc/html/)
