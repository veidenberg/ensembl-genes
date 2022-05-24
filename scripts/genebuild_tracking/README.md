# Tracking script for status of Genebuild Annotations

A script to check the status of Ensembl annotation on assemblies.


## To run

**python3 genebuild_tracking.py -h**

usage: `genebuild_tracking.py [-h] [--summary SUMMARY] [--in_progress IN_PROGRESS] [--unannotated UNANNOTATED] [--projects_missing PROJECTS_MISSING] [--project PROJECT] [--busco_score_missing BUSCO_SCORE_MISSING]`

Track status of assemblies in Ensembl.

optional arguments:
```
  -h, --help            show this help message and exit
  --summary SUMMARY     Provide a summary of the status of assemblies in Ensembl
  --in_progress IN_PROGRESS
                        Provide a summary of the status of assemblies in Ensembl
  --unannotated UNANNOTATED
                        Provide a list of GCAs for the assemblies that have yet to be annotated.
  --projects_missing PROJECTS_MISSING
                        Provide a list of the core dbs for the Ensembl annotated assemblies that have been release on rapid.ensembl.org
  --project PROJECT     Name of project for which to obtain information, e.g. dtol, vgp, etc.
  --busco_score_missing BUSCO_SCORE_MISSING
                        Provide a list of core dbs for which the BUSCO completeness scores are not available in the FTP (http://ftp.ebi.ac.uk/pub/databases/ensembl/dtol/busco_scores/)
```
