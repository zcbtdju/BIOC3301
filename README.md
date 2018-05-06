# BIOC3301
All batch codes used in project report data analysis.

Standard workflow:
Map validation
Join paired reads
Demultiplex
OTU picking - option to use SILVA reference database with open reference UCLUST clustering not available, hence manual assignment of taxonomy and formation of otu table (OTU table is read to obtain sampling depth (-e) for diversity analysis).
Diversity analysis - for alpha and beta diversity metrics
UPGMA phylogenetic tree
Statistical tests - ANOSIM (-c = UPGMA clustering), BIO-ENV (-c = UPGMA clustering and longitude) and db-RDA (-c = distance)

Merged 15/16, 16/17 & 17/18 datasets workflow:
Concatinated map validation
Join paried reads - 17/18 only, due to poor quality Read2 in 15/16 and 16/17 datasets
Demultiplex - run independently for each dataset
OTU picking - run independently for each dataset, closed reference UCLUST clustering with SILVA 128 reference database (timing errors restricted use of open reference)
OTU tables merged - OTU table is read to obtain sampling depth (-e) for diversity analysis)
Diversity analysis - for alpha and beta diversity metrics
UPGMA phylogenetic tree
Statistical tests - ANOSIM (-c = UPGMA clustering), (-c = rainfall - presence/absence of rain), (-c = rainfallmm - amount of rain)

GreenGenes workflow:
Map validation
Join paired reads
Demultiplex
OTU picking - open reference UCLUST clustering with GreenGenes 13_8 reference databas, timing error hence manaul sequence alignment, taxonomy asssignment, phylogenetic tree formation and OTU table formation (with OTU table read to obtain sampling depth (-e) for diversity analysis)
Diversity analysis - for alpha and beta diversity metrics

Stringent workflow:
Map validation
Join paired reads
Demultiplex
OTU picking - option to use SILVA reference database with open reference UCLUST clustering not available, hence manual assignment of taxonomy and formation of otu table (OTU table is read to obtain sampling depth (-e) for diversity analysis).
Diversity analysis - for alpha and beta diversity metrics
