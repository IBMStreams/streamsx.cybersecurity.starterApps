# streamsx.cybersecurity.starterApps
Starter applications for IBM Streams cybersecurity toolkit

* These sample applications are compatible with **Streams 4.3** and later.
* Requires version **[3.0.0,4.0.0)** of the toolkit `com.ibm.streams.cybersecurity`.

You can build and run the samples with local Streams or with Streams in **Cloud Pak for Data**.

*For Streams 4.3 and toolkit version 2.x use version* [2.0](https://github.com/IBMStreams/streamsx.cybersecurity.starterApps/tree/v2.0.0) *of the samples.*

*For Streams 4.2 use version* [1.0](https://github.com/IBMStreams/streamsx.cybersecurity.starterApps/tree/v1.0.0) *of the samples.*

## Quick Start

 1. Download or clone the git repository to your system
 2. Each application comes with a build.xml that will compile the application using local Streams
   - For the BWListTaggerSamples, DomainProfilingSamples, DNSTunnelingSamples and HostProfilingSamples application, run `ant` or `ant -Dcybersecurity.toolkit=<path_to_cybersecurity_toolkit>`
   - For the PredictiveBlocklistingSamples application, run `ant -Dspss.toolkit=<path_to_spss_toolkit>`  or `ant -Dspss.toolkit=<path_to_spss_toolkit> -Dcybersecurity.toolkit=<path_to_cybersecurity_toolkit>`
 3. Submit the job! (the *.sab file can be found in the `output` directory)

### Cloud Pak for Data

To launch the samples (BWListTaggerSamples, DomainProfilingSamples, DNSTunnelingSamples, HostProfilingSamples) using [streamsx command line tools](https://streamsxtopology.readthedocs.io/en/stable/scripts/streamtool.html) to a remote Streams instance (Cloud Pak for Data),
run `ant buildAndSubmitRemote`

## Cybersecurity Toolkit - Getting Started

For information on how to get started with the cybersecurity toolkit, see the following link:
* [Detect Active Threats in Real-time: Streams Cybersecurity Toolkit](https://ibmstreams.github.io/streamsx.cybersecurity.starterApps/docs/knowledge/overview/)
* [Getting Started](http://ibmstreams.github.io/streamsx.documentation/docs/4.1/cybersecurity/cybersecurity-getting-started/)

To learn more about Streams:
* [IBM Streams on Github](http://ibmstreams.github.io)
* [StreamsDev](https://developer.ibm.com/streamsdev/)
