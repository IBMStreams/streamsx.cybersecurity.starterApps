## PredictiveBlacklistingSamples

This sample demonstrates how you can use the PredictiveBlacklisting operator from the `com.ibm.streams.cybersecurity` toolkit.

## Use with local Streams installation

Build the application:

`ant -Dspss.toolkit.path=<path_to_spss_toolkit>`

The application is build using the cybersecurity and network toolkit from the local Streams installation ("$STREAMS_INSTALL/toolkits").

Launch:

`./output/PredictiveBlacklistingBasic_Output/bin/standalone`


Alternative you can submit the `./output/PredictiveBlacklistingBasic_Output/com.ibm.streamsx.cybersecurity.sample.PredictiveBlacklistingBasic.sab` file to your Streams instance.
In the Streams Console, go to the Log Viewer and Click on the PE's Console Log to view the output.

Clean:

`ant clean`

## Use with Streams in Cloud Pak for Data

To build the application in Streams build service and submit the bundle, run the following command:

`ant buildAndSubmitRemote`

or use the commands below.

Prepare the files used by the application:

`ant init`

Build the application:

`streamsx-sc --disable-ssl-verify --main-composite com.ibm.streamsx.cybersecurity.sample::PredictiveBlacklistingBasic --spl-path <path_to_spss_toolkit>`

Launch:

`streamsx-streamtool --disable-ssl-verify submitjob output/com.ibm.streamsx.cybersecurity.sample.PredictiveBlacklistingBasic.sab`

Cancel the job:

`streamsx-streamtool --disable-ssl-verify canceljob <job-id>`
