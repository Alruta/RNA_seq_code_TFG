This script is a general version with the commands lines to import data generated with kallisto and do the differential expression analysis with DESeq2. 

IT'S CRUCIAL TO KNOW THAT IN THIS PIPELINE WE ARE NOT CONSIDERING ISOFORMS. WE ARE CONSIDERING EACH DETECTED TRANSCRIPT AS AN INDEPENDENT GENE. In future I want to add how manage the isoforms but here we don't consider it son take this analysis as a first approximation to your data.

You have to change names or add things to fits the script to your data. This is only the backbone of the script. 

I highly recommend to keep on hand these articles about DESeq2. They are really helpfull to resolve any doubt:
https://rstudio-pubs-static.s3.amazonaws.com/329027_593046fb6d7a427da6b2c538caf601e1.html#example-1-two-group-comparison
http://bioconductor.org/packages/devel/bioc/vignettes/DESeq2/inst/doc/DESeq2.html

Any question don't doubt and ask.