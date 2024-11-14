---
layout: tjic
title: NH data sources
---

# Data sources

What data sources exist within NH ?

You can help this project by adding information here
1. clone this repo `git clone git@github.com:Travis4nh/open-gov-data-init.git`
1. edit the file `nh_data_sources.md` to include new information
1. `git add ; git commit -m"added a data source" ; git push origin`

## Justice & Police

- [NIBRS (National Incident-Based Reporting System)](https://www.fbi.gov/how-we-can-help-you/more-fbi-services-and-information/ucr/nibrs): system used by law enforcement agencies in the United States
  - [documentation of XML etc format](https://le.fbi.gov/informational-tools/ucr/ucr-technical-specifications-user-manuals-and-data-tools#NIBRS)
- [Odyssey Case Manager Suite](https://odyssey.tylertech.com/Products/ProductInfo/CaseManager.aspx): The Odyssey Case Manager product is used for all case information by NH's lower
  (Circuit and Superior) courts. While the NH instance of Odyssey is heavily customized, core case information should
  conform to the general schemas used by this product and the [standard Tyler/Odyssey API](https://www.tylertech.com/products/enterprise-justice/enterprise-justice-integration-portal) should be available
  with permission.
- [J-One (Justice One) System](https://www.nhsp.dos.nh.gov/our-services/justice-information-bureau/j-one-program): This is a bespoke ESB created and maintained by NH State Police connecting 
  numerous agencies within and without New Hampshire. It connects local police and sheriffs departments to the 
  State Police as well as integrating with the court system, division of motor vehicles, department of corrections, 
  and other state level agencies such as Fish & Game and the Liquor Commission.
  *(editorial note) While J-One's schemas, if they can be obtained, may be a good place to start to understand where 
  data related to state government functions may be found, the editor's experience of J-One (now eight years stale) 
  is that it was minimally functional and prone to frequent, often invisible integration failures because of some 
  foundational flaws in it's design (reliance on regex to parse XML). General advice would be to investigate J-One 
  as a key to discovering data in it's various source systems but not to rely on it as an integration point directly.*
- [New Hampshire Crime Statistics](https://crimestats.dos.nh.gov/tops): Department of Safety crime statistics, backed by a pretty simple json data 
  service

## Health

- [DHHS Wisdom](https://wisdom.dhhs.nh.gov/wisdom/): Very comprehensive list of up to date datasets with dashboards
  provided by NH DHHS.
- [NHVRIN Mortality data](https://nhvrinweb.sos.nh.gov/): Deaths and causes of deaths, with decedent data. Account 
  login needed, but can be requested by the public.

## Legislative

- [Current Session Bills](https://www.gencourt.state.nh.us/downloads/): The General Court provides an ODBC database
  directly available to the public, and also exports the contents of the tables to files. The database contains 
  legislative bills for the current session, details of current legislators, and how they voted on bills. The 
  [NHLA](nhliberty.org) uses this data extensively, and is a good resource for answering questions about the data.
- [Statutes](https://www.gencourt.state.nh.us/rsa/html/nhtoc.htm): The current NH Statutes (a.k.a. "The Law"). 
  Unfortunately gets replaced every year with the new Statutes, so historical data not available here, but may be
  directly from the State.
- [Local Election Results](https://www.sos.nh.gov/elections): Raw election result spreadsheets and PDF's  -- see 
  "20XX Election Results" links in the "Election Results" section. This data might in fact be easier to get from other
  data sources that collate National results.
- [House of Representatives Calendars and Journals](https://www.gencourt.state.nh.us/house/calendars_journals/)
  Proceedings of the State House in PDF documents.
- [Senate Calendars and Journals](https://www.gencourt.state.nh.us/senate/calendars_journals/)
  Proceedings of the State Senate in PDF documents.

## Miscellaneous

- [DES OneStop](https://nhdesonestop.sr.unh.edu/Html5Viewer/index.html?viewer=NH_DES.gvh): Department of Environmental Services geographic feature search tool
- anonymized EZ pass data showing  location, vehicle type, datetime 
- [Population from Census data](https://www.census.gov/library/stories/state-by-state/new-hampshire-population-change-between-census-decade.html)
  From the National Census website. Useful to do per-capita analyses. 
- [Population data from the Missouri Census Data Center](https://mcdc.missouri.edu/applications/population/by-age/)
  Additional source for population data, including estimates based on polls for years between Census dates.