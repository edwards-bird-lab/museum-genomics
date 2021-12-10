[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5093841.svg)](https://doi.org/10.5281/zenodo.5093841)

## Introduction

Welcome to the webpage accompanying Card et al. [Museum Genomics](https://doi.org/10.1146/annurev-genet-071719-020506). 2021. *Annual Review of Genetics 55*: 633-659. [https://doi.org/10.1146/annurev-genet-071719-020506](https://doi.org/10.1146/annurev-genet-071719-020506). This webpage is maintained by [Daren Card](https://darencard.net). 

While this website was initially created to archive data files associated with this review, I am also experimenting with ways of extending its utility. Namely, I hypothesize that enabling ways in which the museum genomics community can interact with this website in a dynamic manner may yield dividends for this research community. Most data repositories are static in nature and only allow a one-way flow of information from the authors to the audience. I am aiming to make this website dynamic and bidirectional in an open way by taking advantages of the version control, collaboration, and hosting capabilities of Git and GitHub. The initial, raw data repository will always be available through the badge link at the top of this page and is also preserved in the commit history of this repository. However, I am also experimenting with adding new features to the webpage that foster interaction among museum genomics researchers, thus creating more of a "living" supplement for the research article. I welcome feedback on these ideas and their implementation. 

Please see below for information on how to interact with this webpage and retrieve data files associated with this article.

## Interacting with this website/repository

#### Museum Genomics Researcher Forum

With any research article, it is always possible to contact the corresponding author to ask questions, provide feedback, or commence research discussions. However, these interactions are often hidden from public view. This is certainly appropriate for some interactions, but in other cases, it may make sense to have a public forum to facilitate interactions between the authors and audience and among community members. It seems horribly inefficient for an author to respond to the same question from many readers through email, for example, when viable alternatives are well established. In an effort to demonstrate this manner of interaction, I am leveraging GitHub Issues. Each GitHub repository, including the one hosting this webpage and the archived data files, has an associated Issue forum, which is normally used to support software by allowing users to report problems or request features. I am co-opting this functionality to make a simple forum where anyone can come to ask the author questions, provide feedback, or initiate other types of research interactions.

Please visit the [Museum Genomics Researcher Forum](https://github.com/edwards-bird-lab/museum-genomics/issues) and interact with other museum genomics researchers through existing discussion threads or submit a [new forum post](https://github.com/edwards-bird-lab/museum-genomics/issues/new) to start a new thread.

#### Museum Genomics DOI Form

If you publish research in museum genomics, please also submit the corresponding DOI (digital object identifier) using the form below to help keep track of emerging research in this field. My goal with this feature is to facilitate the collection and curation of new literature within museum genomics so that there is a central location where interested parties can retrieve a relevant bibliography. Ideally, through community engagement and shared effort, a thorough body of relevant literature will be built, which may prove useful for future reviews of this young and growing research field. If we collect and curate physical natural history materials, why not do the same with the peer-reviewed literature that we create? I challenge other museum scientists who work with and publish genomics data to continue long traditions of contributing to community collections by submitting their work using the following form.

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSfTAK3YdDZp33oym3lChU2kezQNqv-3HsBYxdfmh4Sa6Ua_IQ/viewform?embedded=true" width="640" height="603" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>

**In progress**: If interest materializes and other researchers begin adding DOIs for relevant literature, I will work to automate the collation of a bibliography based on user submissions. I will share this bibliography through this webpage so that others can quickly and easily engage with peer-reviewed literature in this field. For now, you can view a running list of the submitted DOIs at [this Google Sheet](https://docs.google.com/spreadsheets/d/1hLBH_Qg5S8ygZjBP9h1dxILar2_rbKJy28xsu1NC92s/edit?usp=sharing).

#### Museum Genomics Twitter Bot

**In progress**: The plan here is to create an automated Twitter bot that will retweet relevant research based on keywords or hashtags, such as #MuseumGenomics. Depending on engagement, I may share a digest of relevant tweets using this webpage, which is a great way to highlight relevant work and source literature that may be of interest to the research community. Please check back for more details once this Twitter bot is created.

## Data files

The raw data associated with several figures is described and linked below. An archive of this data repository has been created through Zenodo with an accompanying DOI, which can be accessed at [https://doi.org/10.5281/zenodo.5093841](https://doi.org/10.5281/zenodo.5093841).

#### Figure 1. Historical Growth of Major Natural History Museum Cryogenic Collections (2010-2019)

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

#### Figure 2. Empirical Patterns of Genome Assembly Contiguity for Avian Genome Assemblies Based on Varying Tissue Type and Preservation Protocol

File Name: Figure2_Edwards_Lab_Genome_Quality_Tissue_Preservation.txt

The Edwards laboratory at Harvard University has gathered internal data on genome assembly scaffold contiguity (N50) for avian genome assemblies generated in recent years. All assemblies utilized 10x Genomics but the original input tissue samples were collected from various tissues and were preserved using different protocols.

For each genome in this dataset, the scientific name, common name, technology utilized (10x Genomics), source of tissue and preservation mode, genome size estimate, approximate sequencing coverage, and contig and scaffold contiguity metrics (N50; in Mb) are available in a [tab-delimited text file](https://raw.githubusercontent.com/edwards-bird-lab/museum-genomics/main/Figure2_Edwards_Lab_Genome_Quality_Tissue_Preservation.txt).

#### Figure 5. Overview of Holdings of Next-Generation, RNA-ready Genomic Samples for Diverse Avian Species in the Museum of Comparative Zoology at Harvard University

File Names: Figure5_MCZ_RNAquality_Tissues.txt and Figure5_Jetz2012_HackettBackbone_Phylogeny.tre

The Ornithology Collection at the Museum of Comparative Zoology has since 2012 collected high quality genomic samples from diverse avian taxa around the globe. These samples are compatible with RNA-seq and other methods utilizing very high quality tissue samples (long read sequencing, functional genomics, etc.), which are rare in most natural history collections in 2021. Most samples were minced and preserved in RNAlater within 10 minutes of sacrifice and then flash frozen in liquid nitrogen after ~12 hours at cool temperatures. A small percentage of samples were directly flash frozen without RNAlater.

A matrix with counts of high quality samples from 13 different tissue types in 101 avian species is available as a [tab-delimited text file](https://raw.githubusercontent.com/edwards-bird-lab/museum-genomics/main/Figure5_MCZ_RNAquality_Tissues.txt). The phylogeny used for plotting was the consensus taken from Jetz (2012; [10.1038/nature11631](https://dx.doi.org/10.1038/nature11631)) with the Hackett backbone available from [birdtree.org](https://birdtree.org/) and this phylogeny is also available in [Newick format](https://raw.githubusercontent.com/edwards-bird-lab/museum-genomics/main/Figure5_Jetz2012_HackettBackbone_Phylogeny.tre).
