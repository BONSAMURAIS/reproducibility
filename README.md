# reproducibility
Work space for the reproducibility working group for BONSAI [hackathon2019](https://github.com/BONSAMURAIS/hackathon-2019)

## Group members

 * [Brandon Kuczenski](https://github.com/bkuczenski), group coordinator
 * [Miguel Astudillo](https://github.com/mfastudillo)
 * [Carlos Gaete](https://github.com/cdgaete)
 * [Massimo Pizzol](https://github.com/massimopizzol)
 * [Tom Millross](https://github.com/tmillross) (observing member)

# Guide for Hackathon Participants

Please refer to [our working groups page](working-groups.md)

## Task Management

Please review repo [issues](https://github.com/BONSAMURAIS/reproducibility/issues) for currently open tasks.

## Defining goals and objectives

The goal of this working group is to provide transparency and reproducibility of the work products of the hackathon.

One effective definition for transparency be found in the [FAIR Guiding Principles](https://www.nature.com/articles/sdata201618) for "Findable, Accessible, Interoperable, and Reusable" data objects.

Regarding reproducibility, obviously we expect people to be able to  reproduce our findings by downloading and running our GitHub repositories.  Beyond that, we are also  interested in replicability, which is a broader goal of enabling the findings to be independently confirmed  (see a set of  [recommendations](https://www.amstat.org/asa/News/ASA-Develops-Reproducible-Research-Recommendations.aspx) from the American Statistical Association on reproducible research). 

To that end, we adopt the following general goals:

 * Accessible _Deliverables_: Deliver outputs in a standard, external format.  The `datapackage` library from [frictionless data](https://frictionlessdata.io/docs/using-data-packages-in-python/) has been proposed.
 * Operable _Workflows_: Procedures that demonstrate the achievement of project tasks. Probably in the form of unit tests.
 * Provide _Provenance_: the original data sources used for input information should be reported, and the steps required to convert input data to output data should be documented.


## Hackathon Deliverables

These can be grouped into "before", "during", and "stretch" goals.

### Before the hackathon

We need to have a set of loose guidelines to the other groups about what their data products will look like.


### During the hackathon

Follow the progress of the other groups and ensure that their works in progress meet our transparency and reproducibility standards.  By the end of the week, we should have operable standards that demonstrate the reproduciblity of data products.

See [Hackathon working groups](working-groups.md).


### Stretch goals

 - Operable standards that demonstrate "interoperable life cycle inventory models"
 - Independent replication of one or more results



## Meeting Notes and other bits of info

* Hasty [notes](notes/repro-kickoff-20190318.txt) from the kickoff call 2019-03-18

