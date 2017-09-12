+++
# default attributes for an incident.
#
# Hugo adds `title` and `date` by default
# when running `hugo new incidents/new-incident.md`,
# so we don't have to specify them here.

# severity: represents the impact of
# your system due to the current incident.
# This is the list of supported severities:
#
# - under-maintenance
# - degraded-performance
# - partial-outage
# - major-outage
#
severity = "partial-outage"

# affectedsystems: is a list of systems affected
# by the incident.
# Example:
# affectedsystems = ["API", "Build servers"]
#
affectedsystems = ["gis servers"]

# resolved: marks an incident as resolved.
# It can be either true or false.
#
resolved = false
+++
mapserv services are throwing many errors. thanks jack. {< track "2017-06-29T16:18:01.789Z" >}}
