+++
title = "Network Load Balancer Failure"
date = 2019-04-18T18:45:45.000Z
severity = "major-outage"
affectedsystems = ["web api", "mapserv"]
resolved = true
+++
All AGRC web servers and GIS servers that are hosted in the Capitol Datacenter are currently inaccessible. All AGRC websites and the web api are not responding. A critical ticket has been submitted and we hope Capitol Hosting can resolve the issues quickly.

## Update

All of the services are returning to green. We are working with Capitol Hosting to determine the cause. We will continue to monitor for issues. {{< track "2019-04-18T19:35:25.000Z" >}}

## Postmortem

The primary network load balancer that handles all of the mapserv traffic failed. The fail over load balancer did not take control. Capitol Hosting is investigatting both failures. {{< track "2019-04-18T19:42:25.000Z" >}}
