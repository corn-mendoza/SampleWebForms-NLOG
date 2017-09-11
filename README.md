# SampleWebForms-NLOG
This is a sample .NET 4.6x web forms application written as an example to output logging from NLog to the console in order to capture the log output to the PCF logs. Publish the code into an output directory and push the code.

`cf push SampleWebFormsApp -b hwc_buildpack -s windows2012R2`

Load the application in the browser.  Run the following command to view the log output:

`cf logs SampleWebFormsApp --recent`

