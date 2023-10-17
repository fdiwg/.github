(DRAFT INTRODUCTION UNDER EDITION, REVIEW/SUGGESTIONS ARE WELCOME)

The [fdiwg](https://github.com/fdiwg) is a set of open and collaborative repositories to foster Fisheries Data Interoperability (FDI). It aims to be a collaborative working environment to progressively shape standards and implementation guidelines to facilitate fisheries data exchange. Currently it is used as working environment to foster collaboration and implementation of case studies in the context of:

* the [Coordinating Working Party on fishery statistics](https://www.fao.org/cwp-on-fishery-statistics/en/) ad hoc task groups, in particular the TG on Reference harmonization - TG-RH - and TG on Geospatial - TG-Geospatial.
* the [Fishery Resources Monitoring System](https://firms.fao.org/firms/en)

The [fdiwg](https://github.com/fdiwg) includes both __digital data resources__ and __supporting tools__.

The __digital data resources__ are structured into four main repositories:

* [_fdi-terms_](https://github.com/fdiwg/fdi-terms): referencing a list of fishery preferred terms, applicable for fishery concepts and their definitions, to be used as basis for data exchange, but also for dissemination
* [_fdi-codelists_](https://github.com/fdiwg/fdi-codelists): referencing all code lists (including CWP standard code lists) and their metadata.
* [_fdi-mappings_](https://github.com/fdiwg/fdi-mappings): referencing all mappings between code lists, including: 
* [_fdi-formats_](https://github.com/fdiwg/fdi-formats): referencing digital format specifications to be used as basis for data templating, validation and submission in data collection frameworks use cases piloted through the FIRMS [dcf-shiny](https://github.com/fdiwg/dcf-shiny) platform.

The __supporting tools__ currently under development include at this stage:
* R packages
    * [fdi4R](https://github.com/fdiwg/fdi4R) R package with a set of utilities
    * [vrule](https:/github.com/fdiwg/vrule) R package to support data validation rules based on [_fdi-formats_](https://github.com/fdiwg/fdi-formats) digital specifications
* R shiny applications
    * [dcf-shiny](https://github.com/fdiwg/dcf-shiny) R Shiny application in support of _Data Collection Frameworks_ and underlying data calls management, data validation & submission. The application relies on the [vrule](https:/github.com/fdiwg/vrule) R package for data validation.
    * [wecafis-dashboard](https://github.com/fdiwg/wecafis-dashboard) R Shiny application to disseminate data statistics from the WECAFIS regional data base
    * [smt-shiny](https://github.com/fdiwg/smt-shiny) R Shiny application for _Stock monitoring tools_, developed by FAO, is available to the global community and hosted via remote computational facilities with considerable processing resources. This tool was designed to allow users with little to no programming experience to run methods developed for data-limited situations to evaluate and monitor the sustainability of fish stocks.
