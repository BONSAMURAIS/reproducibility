# system-model Tasks

## first version

The system model frame work. Turning the raw data into into a computational structure.

This project will be take care of all the modelling choices and data reconciliation between the different data sources. As the very core it will take the raw data from the rdf database and turn it into a computational structure (such as an A-matrix). It will then export it again to the rdf database.

This module relies on the electricity and exiobase data to be in the rdf database. As well as the availability of concordances between entso and exiobase (both region and electricity source) as well as unit correspondences (e.g. kWh/Joules etc)

### Inputs

 - RDF database
 - modelling choices

### Outputs

 - Export A-matrix to database

### Reproducibility objectives

 - Serialized modeling choices (!)
 - database input / query / provenance information
 - serialized A-matrix output

