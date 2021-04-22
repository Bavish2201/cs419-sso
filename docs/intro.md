---
layout: default
title: Introduction
nav_order: 1
---

Single sign-on (SSO) is an authentication scheme that allows a user to log in with a single ID and password to any of several related, yet independent, software systems.

True single sign-on allows the user to log in once and access services without re-entering authentication factors.

It should not be confused with same-sign on (Directory Server Authentication), often accomplished by using the Lightweight Directory Access Protocol (LDAP) and stored LDAP databases on (directory) servers.[1][2]

A simple version of single sign-on can be achieved over IP networks using cookies but only if the sites share a common DNS parent domain.[3]

For clarity, a distinction is made between Directory Server Authentication (same-sign on) and single sign-on: Directory Server Authentication refers to systems requiring authentication for each application but using the same credentials from a directory server, whereas single sign-on refers to systems where a single authentication provides access to multiple applications by passing the authentication token seamlessly to configured applications.

Conversely, single sign-off or single log-out (SLO) is the property whereby a single action of signing out terminates access to multiple software systems.

As different applications and resources support different authentication mechanisms, single sign-on must internally store the credentials used for initial authentication and translate them to the credentials required for the different mechanisms.

Other shared authentication schemes, such as OpenID and OpenID Connect, offer other services that may require users to make choices during a sign-on to a resource, but can be configured for single sign-on if those other services (such as user consent) are disabled.[4] An increasing number of federated social logons, like Facebook Connect, do require the user to enter consent choices upon first registration with a new resource, and so are not always single sign-on in the strictest sense.