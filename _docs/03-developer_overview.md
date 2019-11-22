---
title: "Toolkit Development overview"
permalink: /docs/developer/overview/
excerpt: "Contributing to this toolkits development."
last_modified_at: 2017-08-04T12:37:48-04:00
redirect_from:
   - /theme-setup/
sidebar:
   nav: "developerdocs"
---
{% include toc %}
{% include editme %}

## Quick Start

 1. Download or clone the git repository to your system
 2. Each application comes with a build.xml that will compile the application using local Streams
   - For the BWListTaggerSamples, DomainProfilingSamples, DNSTunnelingSamples and HostProfilingSamples application, run `ant`
   - For the PredictiveBlacklistingSamples application, run `ant -Dspss.toolkit.path=<path_to_spss_toolkit>`
 3. Submit the job! (the *.sab file can be found in the `output` directory)

### Cloud Pak for Data

To launch the samples (BWListTaggerSamples, DomainProfilingSamples, DNSTunnelingSamples, HostProfilingSamples) using [streamsx command line tools](https://streamsxtopology.readthedocs.io/en/stable/scripts/streamtool.html) to a remote Streams instance (Cloud Pak for Data),
run `ant buildAndSubmitRemote`

## Cybersecurity Toolkit - Getting Started
For information on how to get started with the cybersecurity toolkit, see the following link:
[http://ibmstreams.github.io/streamsx.documentation/docs/4.1/cybersecurity/cybersecurity-getting-started/](http://ibmstreams.github.io/streamsx.documentation/docs/4.1/cybersecurity/cybersecurity-getting-started/)

