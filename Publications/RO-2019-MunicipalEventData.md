---
Title: Packaging Municipal Legislative Event Data for Reuse & Exchange
Date: 09.01.2019
Author1: Jackson Brown, Allen Institute for Cell Science
Author2: Nic Weber, University of Washington
Corresponding Author Email: nmweber@uw.edu
---

# Packaging Legislative Event Data for Reuse & Exchange

## Abstract

Municipal governments in the USA are often divided between a legislative (city council) and executive (mayoral) branch. These two branches not only differ in their power to govern a municipality, but also in the way their governing activities are organized: executive activities are periodic and random in occurrence, legislative activities are regularly occurring and organized around key events (e.g. committee and subcommittee meetings, expert testimony, public comment, introduction and debate of new legislation, and voting). Further, legislative events are subject to Open Meetings laws at both the State and Federal level - so that citizens can have a transparent record of how officials are performing their elected duties [1]. This openness mandate further requires that the events of any municipal legislature are recorded and published to the web in an openly accessible format. However, many municipal governments lack the time, money, and expertise to provide citizens with well described data beyond a simple audio or video file of a legislative event. [2]

The Council Data Project (CDP) is our attempt to provide a platform for adding needed context to event based legislative data. In particular we provide open-source tools for transcribing, indexing, modeling, and publishing legislative event data to the web. Our on-going research is focused on how to package a bundle of event-based digital objects (audio-files, videos, transcripts, votes, etc) along with relevant metadata parameters to facilitate meaningful reuse by researchers.

## Public Records Archives

A core challenge for cleaning, packaging, and distributing public records archives on a large scale is due to the drastic differences from city to city in how each city stores and maintains their data. While many cities use the same or similar infrastructure to track legislative actions (e.g. Granicus' Legistar), it is up to each city to determine how data is entered into their instance of the infrastructure and additionally, it is up to each city to design and develop a web application for citizens to access this data [3]. Due to these requirements, it is common for each city to have their own standard for how label legislative actions and attach metadata about those legislative actions.

## Implementation

Previous preliminary work on this project was strictly limited to the proof-of-concept deployment of a CDP instance for Seattle, Washington, USA [4]. While we still maintain a CDP instance for Seattle, the infrastructure for interacting with, maintaining, and deploying new CDP instances has been rewritten to make the system modular to allow for developers and researchers the ability to quickly and easily generate packaged legislative event data for the municipality of their choosing. The open-source toolkit for interacting with, maintaining, and deploying CDP instances in Python can be found under our GitHub organization: https://github.com/CouncilDataProject. The CDP web deployment for Seattle can be found at: https://councildataproject.github.io/seattle.


## References

1. Piotrowski, Suzanne & Borry, Erin. (2010). An Analytic Framework for Open Meetings and Transparency. Public Administration & Management. 15. 138-176.
2. Daxton R. “Chip” Stewart (2010) Let the Sunshine In, or Else: An Examination of the “Teeth” of State and Federal Open Meetings and Open Records Laws, Communication Law and Policy, 15:3, 265-310, DOI: 10.1080/10811680.2010.489858
3. Government Agenda Management, Granicus. [Online]. Available: https://granicus.com/solution/govmeetings/
4. Weber, Nic, & Brown, Jackson. (2018). Remediating Civic Tech. iConference Proceedings. http://hdl.handle.net/2142/100265
