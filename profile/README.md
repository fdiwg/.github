The [fdiwg](https://github.com/fdiwg) is a set of open and collaborative repositories to foster the Fisheries Data Interoperability (FDI) open initiative. It is working environment to shape standards and implementation guidelines to facilitate fisheries data exchange. The initiative is supported by two governance schemes at international level: 1) the [Coordinating Working Party on fishery statistics](https://www.fao.org/cwp-on-fishery-statistics/en/) in particular the Task Group on Reference harmonization - TG-RH - and the Task Group on Geospatial - TG-Geospatial; and 2) the [Fishery Resources Monitoring System](https://firms.fao.org/firms/en)

The [fdiwg](https://github.com/fdiwg) includes both __digital data resources__ and __supporting tools__.

The __digital data resources__ are structured into four main repositories:

* [_fdi-terms_](https://github.com/fdiwg/fdi-terms): referencing a list of fishery preferred terms, applicable for fishery concepts and their definitions, to be used as basis for data exchange, but also for dissemination
* [_fdi-codelists_](https://github.com/fdiwg/fdi-codelists): referencing all code lists (including CWP standard code lists) and their metadata.
* [_fdi-mappings_](https://github.com/fdiwg/fdi-mappings): referencing all mappings between code lists, including: 
* [_fdi-formats_](https://github.com/fdiwg/fdi-formats): referencing digital format specifications to be used as basis for data templating, validation and submission in data collection frameworks use cases piloted through the FIRMS [dcf-shiny](https://github.com/fdiwg/dcf-shiny) platform.

The __supporting tools__ currently under development include at this stage:
* R packages
    * [fdi4R](https://github.com/fdiwg/fdi4R) R package with a set of utilities
    * [vrule](https://github.com/fdiwg/vrule) R package to support data validation rules based on [_fdi-formats_](https://github.com/fdiwg/fdi-formats) digital specifications
    * [artfishr](https://github.com/fdiwg/artfishr) R package to support Artfish implementation
    * [repfishr](https://github.com/fdiwg/repfishr) R package to support countries regional and global reporting
* R shiny applications
    * [dcf-shiny](https://github.com/fdiwg/dcf-shiny) R Shiny application in support of _Data Collection Frameworks_ and underlying data calls management, data validation & submission. The application relies on the [vrule](https:/github.com/fdiwg/vrule) R package for data validation.
    * [dcf-dashboard](https://github.com/fdiwg/dcf-dashboard) R shiny application to show data availability from databases built on [dcf-shiny](https://github.com/fdiwg/dcf-shiny). Applied to
        * [dcf-dashboard-wecafis](https://github.com/fdiwg/dcf-dashboard-wecafis) WECAFIS regional data base
        * [dcf-dashboard-recofi](https://github.com/fdiwg/dcf-dashboard-recofi) RECOFI regional data base
        * [dcf-dashboard-gta](https://github.com/fdiwg/dcf-dashboard-gta) Global Tuna Atlas (GTA)
    * [smt-shiny](https://github.com/fdiwg/smt-shiny) R Shiny application for _Stock monitoring tools_, developed by FAO, is available to the global community and hosted via remote computational facilities with considerable processing resources. This tool was designed to allow users with little to no programming experience to run methods developed for data-limited situations to evaluate and monitor the sustainability of fish stocks.
