+++
title = "mapserv.utah.gov not serving static files"
date = 2017-10-02T19:10:38-06:00
severity = "partial-outage"
affectedsystems = [
  "mapserv"
]
resolved = true
+++
**Cause**: The mapserv web server is not serving sgtatic content items (html, css, images). This affects a variety of other domains. This is caused by security software (OpenAM). A ticket has been created. We are waiting on resolution.

**Resolution**: The OpenAM client was patched. {{<track "2017-10-02T19:49:38-06:00">}}
