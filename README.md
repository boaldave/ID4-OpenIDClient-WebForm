# ID4-OpenIDClient-Webform

IMPORTANT NOTICE:
!!!THIS REPO IS JUST STARTING AND SHOULD BE CONSIDERED WORK IN PROGRESS!!!
- I will remove this notice when the code is complete.

This Identity Server 4 Client for WebForms implements Authentiation and Authorization by using ASP.Net Identity 4, and OAuth2 "Authorization Code" Flow extended by OpenIDConnect, implemented via Identity Server 4.

##The purpose of this demo:
This demo allows you to see project differences, via repo history, between a WebForms Application with no Authentication, and one that connects to Identity Server 4.

The theory is, if you already know how to remove your existing Membership Provider from a WebForms app leaving you with no Authentication, then by examining the before and after project differences, you should be able to see how to replace an existing Authentication and Authorization Membership Provider with ASP.Net Identity 4 and Identity Server 4.

##Running this demo:
1. Prerequisite repo "ID4-Server-Applications":
https://github.com/boaldave/ID4-Server-Applications
Once you realize that Identity Server 4 can be implemented as one or more applications, you may decide to split "Identity Server 4" into the 3  individual applications and host them on separate servers.  For the purpose of this demo, the 3 applications have been packaged and are intended to be deployed as one. This repo contains forks of other projects that serve as base code for those applications with modifications, so breaking changes in those dependencies will not be a factor.

The 3 applications "ID4-Server-Applications" deployed as one application include:
- ASP.Net Core MVC Login UI
- ASP.Net Core WebApi Authorization Services
- ASP.Net Core WebApi Token Services

You will need a server hosting the ID4-Server-Applications, which by default configuration, hosts the deployment at http://localhost:5000/ 

2. When you start this ID4-OpenIDClient-Webform WebForms application, its default configuration hosts the deployment at http://localhost:4000/.

