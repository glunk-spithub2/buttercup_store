# About Buttercup Store

## Intro

Buttercup Store project, is an example payload used to demonstrate how Splunk can monitor your CI/CD process.

Buttercup Store project has been used in the following projects:
1. [Splunk .Conf2018 Session: Splunking the DevOps Pipeline](https://static.rainfocus.com/splunk/splunkconf18/sess/1523463746818001xqvM/finalPDF/IT1502_SplunkingTheDevOpsPipeline_Final%20%281%29_1538861347994001rvNT.pdf)
1.[Testing of the GitHub Audit Log Monitoring Add-On For Splunk](https://splunkbase.splunk.com/app/5595/)
1.[Testing of the GitHub App for Splunk](https://splunkbase.splunk.com/app/5596/)

## Composition

The Buttercup store is a collection of microservices that replicate an online store. This App is based on MVC architecture with each portion containing a database and an API based controller. There are also a couple dedicated frontend services that present the data to users.

All the frontend services are NodeJS based while the controller microservices are built with Go.

## Road Map

Right now, there isn't any planned enhancements, however as needs arise for this type of test payload, changes will be made. For example, if a flawed dependency is needed for a DevSecOps use case, one will be introduced.
