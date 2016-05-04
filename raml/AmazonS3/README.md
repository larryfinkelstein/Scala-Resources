AmazonS3
=======

This repository contains AmazonS3 API defined using [RAML](http://raml.org/).
This RAML ise created and maintained on a best-effort basis by Mulesoft and contributors.

# What can I use it for?

* To automatically configure Mulesoft's [Anypoint Studio](http://www.mulesoft.com/platform/mule-studio) when consuming APIs
* Test your RAML based tools

## To auto configure an HTTP Connector in Mulesoft's [Anypoint Studio](http://www.mulesoft.com/platform/mule-studio)

* Clone this repository to you local machine.
* Import to `/src/main/apis` folder of your Mule Studio project.
* Depending on the RAML file you're using, there may be [further instructions](#examples-for-connectors).

# Structure
The root folder contains one o more main RAML files which define APIs related to same pack.

Root RAML folders:

* `/docs`: Contains documentation files
* `/schemes`: Contains schemas for request and response bodies. These are refered by main RAML files.
* `/examples`: Contains examples for request and response bodies. These are refered by main RAML files.
* `/securitySchemes`: Contains security schemes consumed by main RAML files.
* `/resourceTypes`: Contains resource types consumed by main RAML files.
* `/traits`: Contains traits consumed by main RAML files.

Other root folders:

* `/notebooks`: Contains a set of Api Notebooks ( powered by [Api Notebook](https://api-notebook.anypoint.mulesoft.com/) ).
* `/portal`: Contains specific information used by Mulesoft's Anypoint API Platform to show human-readable descriptions as well as interactive API Notebooks source files ( for use with the [Api Notebook](https://api-notebook.anypoint.mulesoft.com/) ).
* `/connectors`: [Instructions on how to use these RAMLs in MuleSoft's Anypoint Studio](#examples-for-connectors).

In those projects which contain multiple APIs these folders are split into several folders named after main RAML files.
