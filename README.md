# streamsx.cybersecurity.starterApps
(Incubation) Starter applications for IBM Streams cybersecurity toolkit

## Cybersecurity Toolkit - Getting Started
For information on how to get started with the cybersecurity toolkit, see the following link:
[http://ibmstreams.github.io/streamsx.documentation/docs/4.1/cybersecurity/cybersecurity-getting-started/](http://ibmstreams.github.io/streamsx.documentation/docs/4.1/cybersecurity/cybersecurity-getting-started/)

## Quick Start

 1. Download or clone the git repository to your system
 2. Each application comes with a build.xml that will download necessary dependencies and compile the application
   - For the DomainProfilingSamples and HostProfilingSamples application, run `ant`
   - For the PredictiveBlacklistingSamples application, run `ant -Dspss.toolkit.path=<path_to_spss_toolkit>`
 3. Submit the job! (the *.sab file can be found in the `output` directory)
