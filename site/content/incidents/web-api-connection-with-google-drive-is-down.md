+++
title = "WebAPI connection with Google Drive is down"
date = 2018-04-13T17:48:43.000Z
severity = "major-outage"
affectedsystems = [
  "web api"
]
resolved = true
+++
The webapi reads data from a Google Drive spreadsheet on initialization. Something is causing it to crash when it tries to authenticate.
