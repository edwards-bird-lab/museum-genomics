## Introduction

Welcome to the data repository for Card et al. Museum Genomics. In Press. *Annual Review of Genetics*. Please see below for information on how to retrieve data files associated with this article.

## Figure 1. Historical Growth of Major Natural History Museum Cryogenic Collections (2010-2019)

File Name: Figure1_Museum_growth_trends_2010-2019.txt

Data on temporal patterns of cryogenic collection growth for five major natural history collecions between 2010 and 2019: American Museum of Natural History (AMNH), Louisiana State University Museum of Natural Science (LSUMZ), Harvard University Museum of Comparative Zoology (MCZ), University of New Mexico Museum of Southwest Biology (MSB), and University of California Museum of Vertebrate Zoology (MVZ). All counts only reflect newly collected and catalogued samples with an associated voucher specimen but each of these collections also has significant numbers of samples with no associated voucher specimens and previously collected samples that have been more recently added to cryogenic collections. For examples, MSB has collected and cryopreserved 8,886 fish genomic samples between 2010 and 2019, but none had associated voucher specimens.

Both annual and cumulative counts of catalogued records per collection are available in a [tab-delimited text file](https://raw.githubusercontent.com/edwards-bird-lab/museum-genomics/main/Figure1_Museum_growth_trends_2010-2019.txt). The fields are the institution (see codes above), the collection, the year, the annual number of catalogued records, and the cumulative sum per year of catalogued records per collection and institution. Please see a hypothetical example below where 10 new records are added per year for each of three collections at two different institution.

| Institution | Collection  | Year | Annual_count | Collection_running_count |
|-------------|-------------|------|--------------|--------------------------|
| MCZ         | Ornithology | 2010 | 10           | 10                       |
| MCZ         | Ornithology | 2011 | 10           | 20                       |
| MCZ         | Ornithology | 2012 | 10           | 30                       |
| MCZ         | Herpetology | 2010 | 10           | 10                       |
| MCZ         | Herpetology | 2011 | 10           | 20                       |
| MCZ         | Herpetology | 2012 | 10           | 30                       |
| AMNH        | Herpetology | 2010 | 10           | 10                       |
| AMNH        | Herpetology | 2011 | 10           | 20                       |
| AMNH        | Herpetology | 2012 | 10           | 30                       |

## Figure 2. Empirical Patterns of Genome Assembly Contiguity for Avian Genome Assemblies Based on Varying Tissue Type and Preservation Protocol

File Name: Figure2_Edwards_Lab_Genome_Quality_Tissue_Preservation.txt

The Edwards laboratory at Harvard University has gathered internal data on genome assembly scaffold contiguity (N50) for avian genome assemblies generated in recent years. All assemblies utilized 10x Genomics but the original input tissue samples were collected from various tissues and were preserved using different protocols.

For each genome in this dataset, the scientific name, common name, technology utilized (10x Genomics), source of tissue and preservation mode, genome size estimate, approximate sequencing coverage, and contig and scaffold contiguity metrics (N50; in Mb) are available in a [tab-delimited text file](https://raw.githubusercontent.com/edwards-bird-lab/museum-genomics/main/Figure2_Edwards_Lab_Genome_Quality_Tissue_Preservation.txt).

## Figure 5. Overview of Holdings of Next-Generation, RNA-ready Genomic Samples for Diverse Avian Species in the Museum of Comparative Zoology at Harvard University

File Names: Figure5_MCZ_RNAquality_Tissues.txt and Figure5_Jetz2012_HackettBackbone_Phylogeny.tre

The Ornithology Collection at the Museum of Comparative Zoology has since 2012 collected high quality genomic samples from diverse avian taxa around the globe. These samples are compatible with RNA-seq and other methods utilizing very high quality tissue samples (long read sequencing, functional genomics, etc.), which are rare in most natural history collections in 2021. Most samples were minced and preserved in RNAlater within 10 minutes of sacrifice and then flash frozen in liquid nitrogen after ~12 hours at cool temperatures. A small percentage of samples were directly flash frozen without RNAlater.

A matrix with counts of high quality samples from 13 different tissue types in 101 avian species is available as a [tab-delimited text file](https://raw.githubusercontent.com/edwards-bird-lab/museum-genomics/main/Figure5_MCZ_RNAquality_Tissues.txt). The phylogeny used for plotting was the consensus taken from Jetz (2012; [10.1038/nature11631](https://dx.doi.org/10.1038/nature11631)) with the Hackett backbone available from [birdtree.org](https://birdtree.org/) and this phylogeny is also available in [Newick format](https://raw.githubusercontent.com/edwards-bird-lab/museum-genomics/main/Figure5_Jetz2012_HackettBackbone_Phylogeny.tre).
