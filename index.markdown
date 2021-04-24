---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Introduction
nav_order: 1
---

Single Sign On (SSO)
=======

SSO is an session user authentication Service which permits user to use his one set of credential to log in into multiple applications. This allows easier use of usernames password management. SSO is a part of FIM arrangement. (FIM- Federal Identity Management). SSO works by trust between Service Provider and Identity Provider. The Identity provider sends a Certificate to sign the identity information which the Service provider can be assured of that it is from a trusted source.

**Work FLow:**
* User browse to Service Providers
* Service provider sends a Token with some User information to identity Proivider
* Identity Provider checks if the Usern has already been authenticated, if yes then it sends token to Service Provider for confirming authentication But if the user is not authenticated already, then user will be asked to provide his username and password credentials (and in some cases OTP too)
* Once Identity provider confirms the identity of User, it send token to confirm his credentials
* The token is sent to user’s browser and to the service provider item The Service provider after confirming token from identity provider allows user to access its services.

SSO Token: The token contains information about users credentials like his username, email id etc. Tokens are digitally signed to maintain message integrity.
