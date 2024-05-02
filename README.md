# ----------------- #
#
# README.md
# 
# Analytical pipeline for R from "Genetic divergence and adaptation of an isolated European lobster population in the Netherlands", ICES JMS (2024),
# by CD Ellis, JR Paris, TL Jenkins, MR van Stralen, NA Steins, J Schotanus, JR Stevens. 
# 
# All code by CD Ellis (c.ellis@exeter.ac.uk) and TL Jenkins (t.l.jenkins@exeter.ac.uk)
# 
# Series of 6 annotated .R files to be run (ideally in R version 4.3.2+ , in R Studio)
# 
# 01_InitialImport_OosATL_DenovoLobRad.R   - Import, filtering and formatting of genotype data to GENIND input compatible with adegenet package
# 02_PopwisePolymorphism_OosATL.R   - Calculation of sitewise diveristy metrics
# 03_OutlierDetection_OosATL_DenovoLobRad.R   - Assessment and detection of outlier SNP candidate loci, via BAYEscan and OUTflank
# 04_PCAs_ATLoos.R  - Interogation and plotting of genotype data via prinicpal components analysis, both for neutral and outlier SNP datasets
# 05_FstNeIBD_ATLoos_DenovoLobRad.R   - Calculation and plotting of global and pairwise differentiation metrics, effective population size, and assessment and plotting of Isolation by Distance
# 06_Mapmixture_ATLoos.R  - Mapmixture for all European lobster samples across neutral SNP loci, with undifferentiated adjacent pops merged as regional samples
# 
# All dependent files and datasets should be provisioned
#  
# Please contact author Charlie Ellis (c.ellis@exeter.ac.uk) with queries
# 
# END
# ----------------- #
