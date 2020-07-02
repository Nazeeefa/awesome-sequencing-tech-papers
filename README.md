# awesome-sequencing-tech-papers

**A collection of papers and preprints on comparison of long and/or short read sequencing technologies**
|Sequencing|Technologies|For|The Win|
|:--:|:--:|:--:|:--:|
|[2020](https://github.com/Nazeeefa/awesome-sequencing-tech-papers#2020)| [2019](https://github.com/Nazeeefa/awesome-sequencing-tech-papers#2019)| [2018](https://github.com/Nazeeefa/awesome-sequencing-tech-papers#2018)|[2017](https://github.com/Nazeeefa/awesome-sequencing-tech-papers#2017)|[2016](https://github.com/Nazeeefa/awesome-sequencing-tech-papers#2016)|
  
- **Key:**
  - PacBio, Pacific Biosciences
  - ONT, Oxford Nanopore Technology / ONTs, Oxford Nanopore Technologies
  - SMRT, Single-Molecule Real-Time (adapted by PacBio)
  
Contribute by submitting [pull requests](https://github.com/Nazeeefa/awesome-sequencing-tech-papers/pulls), or posting suggestions as [issues](https://github.com/Nazeeefa/awesome-sequencing-tech-papers/issues).

#### 2020

1. 🐟 [Draft genome assemblies using sequencing reads from Oxford Nanopore Technology and Illumina platforms for four species of North American killifish from the *Fundulus genus*](http://dx.doi.org/10.1093/gigascience/giaa067) - A study on a collection of whole genome data of killifish species obtained from ONT PromethION and Illumina platforms (HiSeq 4000 and NovaSeq).
2. [A technology-agnostic long-read analysis pipeline for transcriptome discovery and quantification](https://www.biorxiv.org/content/10.1101/672931v2) - Comparison of MinION and PacBio Sequel II for full-transcript discovery and quantification in GM12878 cell line. PacBio platform captured more as compared to direct-RNA performed by MinION, however PacBio data is prone to antisense transcript artifacts. PacBio Sequel II data was also compared with Illumina RNA-Seq data for expression levels.
2. [Long-read human genome sequencing and its applications](https://www.nature.com/articles/s41576-020-0236-x) - A review article that focuses on SMRT sequencing and ONT, and compare those two major long-read technologies with short-read sequencing platforms in terms of read accuracy, throughput, and cost.
2. [Opportunities and challenges in long-read sequencing data analysis](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-020-1935-5)
2. [A preliminary study on the potential of Nanopore MinION and Illumina MiSeq 16S rRNA gene sequencing to characterize building-dust microbiomes](https://www.nature.com/articles/s41598-020-59771-0)
2. 🦁 [Long live the king: chromosome-level assembly of the lion (Panthera leo) using linked-read, Hi-C, and long-read data](https://bmcbiol.biomedcentral.com/articles/10.1186/s12915-019-0734-5) - The study showed that data from 10x Genomics and Dovetai Hi-C were sufficient for chromosome genome assembly. For sequence fill-in (closing gaps between contigs with ambiguous sequence), nanopore data (MinION) was used. Besides quality of assembly and phylogenetic relationships of species taxa, the study reports how reference genome bias influences heterozygosity estimates across species.
2. [Long-read error correction: a survey and qualitative comparison](https://www.biorxiv.org/content/10.1101/2020.03.06.977975v2) - A comprehensive analysis of 29 tools using PacBio and nanopore data.
2. [Overcoming uncollapsed haplotypes in long-read assemblies of non-model organisms](https://www.biorxiv.org/content/10.1101/2020.03.16.993428v1) - Assessment of long-read assemblers on PacBio and nanopore reads from the non-model non-vertebrate organism Adineta *vaga*
2. 🇰🇷 [Comparative analysis of seven short-reads sequencing platforms using the Korean Reference Genome: MGI and Illumina sequencing benchmark for whole-genome sequencing](https://www.biorxiv.org/content/10.1101/2020.03.22.002840v1)

#### 2019

1. [Comparative analysis of sequencing technologies for single-cell transcriptomics](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1676-5) 
2. [Comprehensive analysis of structural variants in breast cancer genomes using
single molecule sequencing](https://www.biorxiv.org/content/10.1101/847855v1)
3. 🇰🇷 [Chromosome-scale assembly comparison of the Korean Reference Genome KOREF from PromethION and PacBio with Hi-C mapping information](http://dx.doi.org/10.1093/gigascience/giz125)
4. 💉🧬 [Long-Read Sequencing Emerging in Medical Genetics](https://www.frontiersin.org/articles/10.3389/fgene.2019.00426/full) - A review article that discusses potential of long-read sequencing technologies in a context of advancements in medical genetics.
5. 🦠 [Comparison of long-read sequencing technologies in the hybrid assembly of complex bacterial genomes](https://www.biorxiv.org/content/10.1101/530824v2)
6. 🌱 [A critical comparison of technologies for a plant genome sequencing project](https://academic.oup.com/gigascience/article/8/3/giy163/5281243) - Comparison between Illumina short read, PacBio, 10x Genomics linked reads, Dovetail Hi-C, and BioNano optical maps for assembling high-quality potato species *Solanum verrucosum*. The comparison involves assessment of completeness, accuracy, requirements, and sequencing costs.
7. [Illumina and Nanopore methods for whole genome sequencing of hepatitis B virus (HBV)](https://www.nature.com/articles/s41598-019-43524-9)

#### 2018

1. 💉🧬 [Single molecule real-time (SMRT) sequencing comes of age: applications and utilities for medical diagnostics](https://academic.oup.com/nar/article/46/5/2159/4833218) - A summary of how SMRT sequencing technology has evolved into PacBio's RS II and Sequel systems and its use for various types of genetics studies.
1. 💉🧬 [Single-Molecule Sequencing: Towards Clinical Applications](https://www.cell.com/trends/biotechnology/fulltext/S0167-7799(18)30204-X) - A nice review on how PacBio and ONTs are being used for microbiology, pharmacogenomics, cancer studies, and so on.
2. 🦠 [NGS Technologies and their Application to the Study and Control of Bacterial Infection](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5857210/)
1. 🦠 [Targeted Long-Read Sequencing of a Locus Under Long-Term Balancing Selection in *Capsella*](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5873921/)
1. 🦠 [Real-time analysis of nanopore-based metagenomic sequencing from infected orthopaedic devices](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-018-5094-y) (Comparison between Illumina MiSeq and MinION)
1. [High-throughput targeted long-read single cell sequencing reveals the clonal and transcriptional landscape of lymphocytes](https://www.biorxiv.org/content/10.1101/424945v1.full) (2018)

#### 2017
1. [A Review on the Applications of Next Generation Sequencing Technologies as Applied to Food-Related Microbiome Studies](https://www.frontiersin.org/articles/10.3389/fmicb.2017.01829/full)
1. [Hybrid sequencing and map finding (HySeMaFi): optional strategies for extensively deciphering gene splicing and expression in organisms without reference genome](https://www.nature.com/articles/srep43793)
1. [DNA Sequencing Technologies: 2006-2016](https://www.nature.com/articles/nprot.2016.182)

#### 2016
1. [Comparison of NGS technologies for the comprehensive assessment of full-length hepatitis C viral genomes](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5035407/)
1. [The sequence of sequencers: The history of sequencing DNA](https://www.sciencedirect.com/science/article/pii/S0888754315300410)

Feel free to contribute by submitting [pull requests](https://github.com/Nazeeefa/awesome-sequencing-tech-papers/pulls), or posting suggestions as [issues](https://github.com/Nazeeefa/awesome-sequencing-tech-papers/issues).
