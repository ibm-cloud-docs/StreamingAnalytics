---

copyright:
  years: 2015, 2021
lastupdated: "2021-06-07"

subcollection: StreamingAnalytics

---

<!-- Attribute definitions -->
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:deprecated: .deprecated}
{:codeblock: .codeblock}
{:screen: .screen}
{:pre: .pre}

# Developing Python applications
{: #t_develop_apps_python}

{{site.data.keyword.streaminganalyticsfull}} is deprecated. As of July 30, 2021, 
you can't create new instances, and access to free Lite instances will be removed. 
Existing paid plan instances are supported until May 1, 2022. Any instance that still exist on that date will be stopped and deleted. 
For more information, see [End of Market](/docs/StreamingAnalytics?topic=StreamingAnalytics-end_of_market).
{: deprecated}

You can now develop Python applications in {{site.data.keyword.DSX_full}} or in your local Python development environment and deploy these applications in {{site.data.keyword.streaminganalyticsshort}}.
{:shortdesc}

Develop and deploy your Python applications to {{site.data.keyword.cloud}} with the {{site.data.keyword.streaminganalyticsshort}} service with one of these methods:


## Developing Streams Python applications in Watson Studio
{: #t_develop_python_dsx}

If you do not have a Python development environment, the easiest way to get started is to use the {{site.data.keyword.streamsshort}} notebooks in {{site.data.keyword.DSX_short}} and create sample Python applications. These notebooks provide the steps and code samples to create and deploy simple Python applications for the {{site.data.keyword.streaminganalyticsshort}} service within the {{site.data.keyword.DSX_short}} Python environment:

* [Hello World! ![External link icon](../../icons/launch-glyph.svg "External link icon")](https://dataplatform.cloud.ibm.com/exchange/public/entry/view/9fc33ce7301f10e21a9f92039ca9c6e8): Create a simple Hello World! application to get started and then deploy the application to an instance of the {{site.data.keyword.streaminganalyticsshort}} service.

* [Rolling Average Demo ![External link icon](../../icons/launch-glyph.svg "External link icon")](https://github.com/IBMStreams/sample.starter_notebooks/blob/latest/Streams-RollingAverageSample.ipynb): This application simulates a data hub that receives readings from sensors. It computes the 30 second rolling average of the reported readings using Pandas. Use the setup instructions under **"Connect to a Streams instance from IBM Watson Studio and other environments"** to deploy the application to an instance of the {{site.data.keyword.streaminganalyticsshort}} service.

* [Neural Net Demo ![External link icon](../../icons/launch-glyph.svg "External link icon")](https://dataplatform.cloud.ibm.com/exchange/public/entry/view/9fc33ce7301f10e21a9f92039ca60bb7): Create a sample data set, create a data model, use that model in a streaming application, visualize the streaming data, and submit the streaming application to the service.

## Developing applications in your local Python environment
 {: #t_develop_python_api}

With the [{{site.data.keyword.streamsshort}} Python Application API ![External link icon](../../icons/launch-glyph.svg "External link icon")](http://ibmstreams.github.io/streamsx.documentation/docs/python/python-appapi-devguide/#50-api-features), which is included in the streamsx package, you can create stream processing applications with Python callable classes or functions. You use the Python Application API to then define and submit the application to the service.

Get started by following the steps in the [Developing for the {{site.data.keyword.streaminganalyticsshort}} service ![External link icon](../../icons/launch-glyph.svg "External link icon")](http://ibmstreams.github.io/streamsx.documentation/docs/python/1.6/python-appapi-devguide-2a/index.html) tutorial. In this tutorial, you create a sample application in your local Python environment and deploy it to the {{site.data.keyword.streaminganalyticsshort}} service.
