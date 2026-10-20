# Copilot-VASI-TRM-Report-Generator
Looking to create a script based on the concept which Frank and I worked on a couple of weeks ago to generate a VASI/TRM Report given one or more VASI ID's
---
**Here's the prompt**
Prompt me for a list of one or more VASI ID's (e.g. 1414, 2341, 1415).
For each id given, using the following link for VASI,
[https://vaww.vear.ea.oit.va.gov/#system_and_application_domain_vasystems_na.htm](https://vaww.vear.ea.oit.va.gov/#system_and_application_domain_vasystems_na.htm)
retrieve the system name and vasi link from the returned data.
For each VASI record retrieved open the VASI record and retrieve the IT Product Manager from the system view tab.
Then from the technical view tab retrieve the list of all systems, their current version, technology name and TRM Link.
For each system open the TRM link and from the decision tab identify all versions which are authorized for the current quarter.
From all the information retrieved, create a report showing the following:
System Name
VASI ID with a link to the VASI record specified for that ID
IT Product Manager
the list of all Systems (with their TRM Link), their current version, and technology name, if the current version is authorized for the current quarter provide the authorization from the TRM.
If the system is not authorized list all release versions which are authorized for the current quarter.
Title each report using exactly this pattern: `VASI/TRM Report for {System Name} - {VASI ID}`. Include the report's preparation date and the quarter/year evaluated. If multiple VASI IDs are requested, include one summary row per VASI system and group technology rows under the corresponding system.

