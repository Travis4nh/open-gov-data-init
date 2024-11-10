---
layout: tjic
title: The Open Government Data Initiative
description: long term vision
---
# Long Term Vision

The eventual ecosystem that we'd like to see would include:

1. a variety of government data sources (each located at fixed URLs), some mandated by legislation, others published by various departments and agencies proactively in a quest to help the citizens
1. a central registry of all such data sources, perhaps maintained by the state IT department
1. a variety of third party filters and tools that take state data as input and delivery filtered and reworked data (each located at fixed URLs)
1. a registry of _those_ data sources

One can imagine, for example, a portion of this:

- a majority of New Hampshire towns publish their NIBRS XML files, each at http://&lt;townname&gt;.nh.gov/stats/&lt;year&gt;/nibrs.xml
- the NH Department of Transporation publishes EZ pass information showing when vehicles of various types pass through toll booths

and then

- the ACLU downloads and post processes the crime data and publishes a filtered and unified file, perhaps concentrating on racial aspects of policing, at https://www.aclu-nh.org/stats/&lt;year&gt;/acludata.xml
- the New England Mountain Bike Association downloads and post processes the crime data and publishes new data, perhaps concentrating on bike thefts, at https://www.nemba.org/stats/&lt;year&gt;/bikethefts.xml
- the Motorcycle Safety Foundation downloads both sets of data to create a dashboard that shows that motorcycle crashes happen disproportionately near certain toll booths and publishes it at https://msf-usa.org/&lt;year&gt;/crashdata.xml

and, of course, other entities could download a variety of both original and processed data from various sources.

In time we'd love to see the data move from once-per-year updates to once-per-month, and eventually real-time updates.