## DNSTunnelingSample

This sample demonstrates how you can use the DNSTunneling operator from the `com.ibm.streams.cybersecurity` toolkit.

## Use with local Streams installation

Build the application:

`ant`

The application is build using the cybersecurity and network toolkit from the local Streams installation ("$STREAMS_INSTALL/toolkits").

Launch:

`./output/DNSTunnelingBasic_Output/bin/standalone`

or 

`ant standalone`

Alternative you can submit the `./output/DNSTunnelingBasic_Output/com.ibm.streamsx.cybersecurity.sample.DNSTunnelingBasic.sab` file to your Streams instance.
In the Streams Console, go to the Log Viewer and Click on the PE's Console Log to view the output.

Clean:

`ant clean`

## Use with Streams in Cloud Pak for Data

To build the application in Streams build service and submit the bundle, run the following command:

`ant buildAndSubmitRemote`

or use the commands below.

Build the application:

`streamsx-sc --disable-ssl-verify --main-composite com.ibm.streamsx.cybersecurity.sample::DNSTunnelingBasic`

Launch:

`streamsx-streamtool --disable-ssl-verify submitjob output/com.ibm.streamsx.cybersecurity.sample.DNSTunnelingBasic.sab`

Cancel the job:

`streamsx-streamtool --disable-ssl-verify canceljob <job-id>`
