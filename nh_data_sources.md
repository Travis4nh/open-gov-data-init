---
layout: tjic
title: NH data sources
---

# Data sources

What data sources exist within NH ?

You can help this project by adding information here
1. clone this repo `git clone git@github.com:Travis4nh/open-gov-data-init.git`
1. edit the file `data_tools.md` to include new information
1. `git add ; git commit -m"added a data source" ; git push origin`


List:

- [NIBRS (National Incident-Based Reporting System)](https://www.fbi.gov/how-we-can-help-you/more-fbi-services-and-information/ucr/nibrs): system used by law enforcement agencies in the United States
  - [documentation of XML etc format](https://le.fbi.gov/informational-tools/ucr/ucr-technical-specifications-user-manuals-and-data-tools#NIBRS)
- anonymized EZ pass data showing  location, vehicle type, datetime 
- [J-One (Justice One) System](https://www.nhsp.dos.nh.gov/our-services/justice-information-bureau/j-one-program): This is a bespoke ESB created and maintained by NH State Police connecting numerous agencies within and without New Hampshire. It connects local police and sheriffs departments to the State Police as well as integrating with the court system, division of motor vehicles, department of corrections, and other state level agencies such as Fish & Game and the Liquor Commission.
*(editorial note) While J-One's schemas, if they can be obtained, may be a good place to start to understand where data related to state government functions may be found, the editor's experience of J-One (now eight years stale) is that it was minimally functional and prone to frequent, often invisible integration failures because of some foundational flaws in it's design (reliance on regex to parse XML). General advice would be to investigate J-One as a key to discovering data in it's various source systems but not to rely on it as an integration point directly.*
- [Odyssey Case Manager Suite](https://odyssey.tylertech.com/Products/ProductInfo/CaseManager.aspx): The Odyssey Case Manager product is used for all case information by NH's lower (Circuit and Superior) courts. While the NH instance of Odyssey is heavily customized, core case information should conform to the general schemas used by this product and the [standard Tyler/Odyssey API](https://www.tylertech.com/products/enterprise-justice/enterprise-justice-integration-portal) should be available with permission.
