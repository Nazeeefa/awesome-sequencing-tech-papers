# awesome-sequencing-tech-papers

**A collection of papers and preprints on comparison of long and/or short read sequencing technologies.**
|Sequencing|Technologies|For|The | Win|
|:--:|:--:|:--:|:--:|:--:|
| 2021 (Coming Soon)| [2020](https://github.com/Nazeeefa/awesome-sequencing-tech-papers#2020)| [2019](https://github.com/Nazeeefa/awesome-sequencing-tech-papers#2019)| [2018](https://github.com/Nazeeefa/awesome-sequencing-tech-papers#2018)|[2017](https://github.com/Nazeeefa/awesome-sequencing-tech-papers#2017)|
  
**Key:**
  - Hi-C, chromosome conformation capture
  - ONT, Oxford Nanopore Technology
  - PacBio, Pacific Biosciences
    - SMRT, Single-Molecule Real-Time
    - CCS, Circular Consensus Sequencing
    - Hi-Fi, High-Fidelity
    - CLR, Continuous Long Read
  - 📚 Review Article
  - 🧬 Study involves human genomes
  - 🦠 Bacterial genomes
  - 💉 Focused towards medical genetics
  
  
Contribute by submitting [pull requests](https://github.com/Nazeeefa/awesome-sequencing-tech-papers/pulls), or posting suggestions as [issues](https://github.com/Nazeeefa/awesome-sequencing-tech-papers/issues). Thank you.

---

## 2020

**Title:** [Benchmarking metagenomic classification tools for long-read sequencing data](https://www.biorxiv.org/content/10.1101/2020.11.25.397729v1)

**Platforms:** ONT and PacBio

---

**Title:** 🧬 [Telomere-to-telomere assembly of a complete human X chromosome](https://www.nature.com/articles/s41586-020-2547-7)

**Description:** The study presents first ever gapless telomere-to-telomere assembly of human X chromosome, enabled by ultra-long reads.

**Platforms:** Illumina linked reads, 10X Genomics, PacBio (Continuous Long Reads and HiFi Reads), ONT, Hi-C

---

**Title:** 🧬 [Benchmarking challenging small variants with linked and long reads](https://www.biorxiv.org/content/10.1101/2020.07.24.212712v1)

**Description:** Use of long and linked reads to expand Genome In A Bottle's benchmark in order to indentify difficult regions such as segmental duplications.

**Platforms:** 10x Genomics, Complete Genomics, PacBio Sequel II, ONT.

---

**Title:** 🌲🍂 [Siberian larch (*Larix sibirica Ledeb.*) mitochondrial genome assembled using both short and long nucleotide sequence reads is currently the largest known mitogenome](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-020-07061-4)

**Description:** Assessment of mitochondrial reads (using sequencing, assembly, and annotation) to study Siberian larch.

**Platforms:** Illumina HiSeq 2000 and ONT MinION.

---

**Title:** 🐟 [Draft genome assemblies using sequencing reads from Oxford Nanopore Technology and Illumina platforms for four species of North American killifish from the *Fundulus genus*](http://dx.doi.org/10.1093/gigascience/giaa067)

**Description:** A study on a collection of whole genome data of killifish species obtained from ONT and Illumina platforms

**Platforms:** ONT PromethION, and Illumina platforms (HiSeq 4000 and NovaSeq)

---

**Title:** [A technology-agnostic long-read analysis pipeline for transcriptome discovery and quantification](https://www.biorxiv.org/content/10.1101/672931v2) 

**Description:** Comparison of MinION and PacBio Sequel II for full-transcript discovery and quantification in GM12878 cell line. PacBio platform captured more as compared to direct-RNA performed by MinION, however PacBio data is prone to antisense transcript artifacts. PacBio Sequel II data was also compared with Illumina RNA-Seq data for expression levels.

**Platforms:** ONT MinION and PacBio Sequel II

---

**Title:** 🧬 [Long-read human genome sequencing and its applications](https://www.nature.com/articles/s41576-020-0236-x)

**Description:** A review article that focuses on SMRT sequencing and ONT, and compare those two major long-read technologies with short-read sequencing platforms in terms of read accuracy, throughput, and cost.

---

**Title:** 📚 [Opportunities and challenges in long-read sequencing data analysis](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-020-1935-5)

**Description:** An overview of the bioinformatics pipelines for nanopore and PacBio sequencing, with a focus on downstream analyses such as error correction, structural variant calling, and detection of base modifications.

---

**Title:** [A preliminary study on the potential of Nanopore MinION and Illumina MiSeq 16S rRNA gene sequencing to characterize building-dust microbiomes](https://www.nature.com/articles/s41598-020-59771-0)

**Description:**

**Platforms:** ONT MinION and Illumina MiSeq

---

**Title:** 🦁 [Long live the king: chromosome-level assembly of the lion (Panthera leo) using linked-read, Hi-C, and long-read data](https://bmcbiol.biomedcentral.com/articles/10.1186/s12915-019-0734-5)

**Description:** The study showed that data from 10x Genomics and Dovetai Hi-C were sufficient for chromosome genome assembly. For sequence fill-in (closing gaps between contigs with ambiguous sequence), nanopore data (MinION) was used. Besides quality of assembly and phylogenetic relationships of species taxa, the study reports how reference genome bias influences heterozygosity estimates across species.

---

**Title:** [Long-read error correction: a survey and qualitative comparison](https://www.biorxiv.org/content/10.1101/2020.03.06.977975v2)

**Description:** A comprehensive analysis of 29 tools using PacBio and nanopore data.

---

**Title:** [Overcoming uncollapsed haplotypes in long-read assemblies of non-model organisms](https://www.biorxiv.org/content/10.1101/2020.03.16.993428v1)

**Description:** Assessment of long-read assemblers on PacBio and nanopore reads from the non-model non-vertebrate organism *Adineta vaga*

---

**Title:** 🇰🇷🧬 [Comparative analysis of seven short-reads sequencing platforms using the Korean Reference Genome: MGI and Illumina sequencing benchmark for whole-genome sequencing](https://www.biorxiv.org/content/10.1101/2020.03.22.002840v1)

**Description:** Systematic comparison of a new whole-genome sequencer MGISEQ-T7 against Illumina short-read sequencers. The study concluded the MGI platform can be used for genomics research at nearly half the cost of the Illumina platforms.

**Platforms:** BGISEQ-500, MGISEQ-T7, HiSeq2000, HiSeq2500, HiSeq4000, HiSeqX10, and NovaSeq6000

---
**Title:** 🧬 [Comprehensive analysis of structural variants in breast cancer genomes using
single molecule sequencing](https://genome.cshlp.org/content/30/9/1258)

**Description:** Analysis of the SKBR3 breast cancer cell line and patient-derived organoids representing tumor and matching normal cells from two breast cancer
patients.

**Platforms:** ONT MinION (R9.1 flow cell) , PacBio Sequel (SMRTbell template prep kit 1.0), Illumina (TruSeq RNA Library prep kit), and 10x Genomics

---

## 2019

**Title:** [Comparative analysis of sequencing technologies for single-cell transcriptomics](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1676-5) 

---

**Title:** 🇯🇵🧬 [Construction and Integration of Three *De Novo* Japanese Human Genome Assemblies toward a Population-Specific Reference](https://www.biorxiv.org/content/10.1101/861658v1)

**Description:** Construction of a reference genome using hybrid scaffolding approach by integrating *de novo* assemblies of three Japanese male individuals. BionanoSolve  software (v3.2) was used for hybrid scaffolding.

**Platforms:** PacBio RSII (using P6-C4 chemistry),  Illumina HiSeq 2500 system (with a TruSeq Rapid PE Cluster kit and Rapid SBS kit), and Irys/Saphyr system (BioNano Genomics) for optical mapping.

---
**Title:** 🇰🇷🧬 [Chromosome-scale assembly comparison of the Korean Reference Genome KOREF from PromethION and PacBio with Hi-C mapping information](http://dx.doi.org/10.1093/gigascience/giz125)

**Description:** The study concludes that "the pore-based PromethION approach provides a good quality chromosome-scale human genome assembly at a low cost and is much more cost-effective than PacBio."

**Platforms:** ONT PromethION R9.4.1, PacBio Sequel, Illumina HiSeq 2000, and Arima-HiC kit (A160105 v01)

---

**Title:** 📚💉🧬 [Long-Read Sequencing Emerging in Medical Genetics](https://www.frontiersin.org/articles/10.3389/fgene.2019.00426/full)

**Description:** A review article that discusses potential of long-read sequencing technologies in a context of advancements in medical genetics.

---

**Title:** 📚🧬 [Long-read sequencing in deciphering human genetics to a greater depth](https://pubmed.ncbi.nlm.nih.gov/31538236/)

**Description:** A review article focused towards advantages and limitations of long-read sequencing

---

**Title:** 🦠 [Comparison of long-read sequencing technologies in the hybrid assembly of complex bacterial genomes](https://www.biorxiv.org/content/10.1101/530824v2)

---

**Title:** 🌱 [A critical comparison of technologies for a plant genome sequencing project](https://academic.oup.com/gigascience/article/8/3/giy163/5281243)

**Description:** Comparison between Illumina short read, PacBio, 10x Genomics linked reads, Dovetail Hi-C, and BioNano optical maps for assembling high-quality potato species *Solanum verrucosum*. The comparison involves assessment of completeness, accuracy, requirements, and sequencing costs.

---

**Title:** [Illumina and Nanopore methods for whole genome sequencing of hepatitis B virus (HBV)](https://www.nature.com/articles/s41598-019-43524-9)

---

**Title:** [Multi-platform discovery of haplotype-resolved structural variation in genomes](https://www.nature.com/articles/s41467-018-08148-z)

---

**Title:** 🧬 [Sequencing of human genomes with nanopore technology](https://www.nature.com/articles/s41467-019-09637-5)

**Description:** The main focus of this study is the use of nanopore technology (MinION) for clinical use. In addition to evaluating performance of basecallers for SNV calls, the study also looked at comparison of large variants (>100bp) from read data generated by ONT, PacBio, and Illumina (section 3.2, supplementary).

## 2018

**Title:** 📚💉🧬 [Single molecule real-time (SMRT) sequencing comes of age: applications and utilities for medical diagnostics](https://academic.oup.com/nar/article/46/5/2159/4833218)

**Description:** A summary of how SMRT sequencing technology has evolved into PacBio's RS II and Sequel systems and its use for various types of genetics studies.

---

**Title:** 📚💉🧬 [Single-Molecule Sequencing: Towards Clinical Applications](https://www.cell.com/trends/biotechnology/fulltext/S0167-7799(18)30204-X)

**Description:** A nice review on how PacBio and ONTs are being used for microbiology, pharmacogenomics, cancer studies, and so on.

---

**Title:** 🦠 [NGS Technologies and their Application to the Study and Control of Bacterial Infection](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5857210/)

----

**Title:** 🦠 [Targeted Long-Read Sequencing of a Locus Under Long-Term Balancing Selection in *Capsella*](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5873921/)

---
**Title:** 🦠 [Real-time analysis of nanopore-based metagenomic sequencing from infected orthopaedic devices](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-018-5094-y)

**Platforms:** Illumina MiSeq and ONT MinION

---

**Title:** [High-throughput targeted long-read single cell sequencing reveals the clonal and transcriptional landscape of lymphocytes](https://www.biorxiv.org/content/10.1101/424945v1.full)

---

## 2017

**Title:** 📚 [A Review on the Applications of Next Generation Sequencing Technologies as Applied to Food-Related Microbiome Studies](https://www.frontiersin.org/articles/10.3389/fmicb.2017.01829/full)

**Title:** [Hybrid sequencing and map finding (HySeMaFi): optional strategies for extensively deciphering gene splicing and expression in organisms without reference genome](https://www.nature.com/articles/srep43793)

**Title:** 📚 [DNA Sequencing Technologies: 2006-2016](https://www.nature.com/articles/nprot.2016.182)

---

Contribute by submitting [pull requests](https://github.com/Nazeeefa/awesome-sequencing-tech-papers/pulls), or posting suggestions as [issues](https://github.com/Nazeeefa/awesome-sequencing-tech-papers/issues). Thank you.
