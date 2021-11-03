# awesome-sequencing-tech-papers

**A collection of papers on comparison of long and/or short read sequencing technologies (and data generated from the platforms).**
|Sequencing|Technologies|For|The | Win|
|:--:|:--:|:--:|:--:|:--:|
| [2022](https://github.com/Nazeeefa/awesome-sequencing-tech-papers#2022) |[2021](https://github.com/Nazeeefa/awesome-sequencing-tech-papers#2021) | [2020](https://github.com/Nazeeefa/awesome-sequencing-tech-papers#2020)| [2019](https://github.com/Nazeeefa/awesome-sequencing-tech-papers/blob/master/Sequencing_Tech_2019_Papers.md)| [2018](https://github.com/Nazeeefa/awesome-sequencing-tech-papers/blob/master/Sequencing_Tech_2018_Papers.md)|
  
**Key:**
  - Hi-C, chromosome conformation capture
  - ONT, Oxford Nanopore Technology
  - PacBio, Pacific Biosciences
    - SMRT, Single-Molecule Real-Time
    - CLR, Continuous Long Read
    - CCS, Circular Consensus Sequencing
    - Hi-Fi, High-Fidelity
  - 📚 Review/Opinion Article
  - 🧬 Study involves human genome(s)
  - 🦠 Prokaryotic genome(s)
  - 🌱 Plant genome(s)
  - 💉 Focused towards medical genetics
  - 🛠 Includes tool/software development
  
  
Contribute by submitting [pull requests](https://github.com/Nazeeefa/awesome-sequencing-tech-papers/pulls), or posting suggestions as [issues](https://github.com/Nazeeefa/awesome-sequencing-tech-papers/issues). Thank you.

---

## 2021

**Title:** 🛠 🧬 [Haplotype-aware variant calling enables high accuracy in nanopore long-reads using deep neural networks](https://www.nature.com/articles/s41592-021-01299-w)

**Description:** Evaluation of variant calling performance and runtime comparison of haplotype-aware pipelines

**Platforms:**

#

**Title:** 🌱 [Combined use of Oxford Nanopore and Illumina sequencing yields insights into soybean structural variation biology](https://www.biorxiv.org/content/10.1101/2021.08.26.457816v1)

**Description:** The study is about exploring structural variants (SVs) in soybean's transposable element (TE) . The authors developed a pipeline to find whether SVs at various sites were due to novel TE insertion and/or excision.

**Platforms:** ONT MinION (SQK-LSK109 genomic DNA ligation kit) with a FLO-MIN106D flowcell (R9 chemistry), and Illumina HiSeq 2500

#

**Title:** 🦠 [Microbial metagenome-assembled genomes of the Fram Strait from short and long read sequencing platforms](https://peerj.com/articles/11721/)

**Platforms:** Comparison was performed on datasets from marine environmental samples usinng PacBio Sequel II and Illumina HiSeq 3000.

#

**Title:** 🦠 [Benchmarking metagenomic classification tools for long-read sequencing data](https://www.biorxiv.org/content/10.1101/2020.11.25.397729v2)

**Platforms:** ONT and PacBio - See section 2.2 Test Datasets for information on data sources.

#

**Title:** 🧬 [Long-read cDNA sequencing identifies functional pseudogenes in the human transcriptome](https://www.biorxiv.org/content/10.1101/2021.03.29.437610v1)

**Platforms:** Comparison was performed between data from  Illumina Human BodyMap 2.0 Project and PacBio Sequel II

#

**Title:** 🦠😛 [High molecular weight DNA extraction strategies for long-read sequencing of complex metagenomes](https://www.biorxiv.org/content/10.1101/2021.03.03.433801v2)

**Description:** The study involves samples from human tongue.

**Platforms:** Illumina MiSeq and NextSeq500 and ONT's MinION

#

**Title:** 🧬 [Targeted long-read sequencing identifies missing disease-causing variation](https://www.cell.com/ajhg/fulltext/S0002-9297(21)00230-5)

**Description:** Use of adaptive sampling via ONT and PacBio platforms

**Platforms:** ONT's GridION (with MinKNOW control software v18.04.1), PacBio CLR sequencing (SMRT Cell 1Ms on the Sequel platform using v3 chemistry), and PacBio HiFi sequencing (SMRT Cell 8M on a Sequel II instrument)

#

**Title:** 🧬 [Structural variant selection for high-altitude adaptation using single-molecule long-read sequencing](https://www.biorxiv.org/content/10.1101/2021.03.27.436702v1)

**Platforms:** ONT and PacBio

#

**Title:** 🦠 [High-accuracy long-read amplicon sequences using unique molecular identifiers with Nanopore or PacBio sequencing](https://www.nature.com/articles/s41592-020-01041-y)

**Description:** Comparison of ONT R9.4.1, PacBio CCS, and ONT R10.3 UMI (Unique Molecular Identifier)

**Platforms:** ONT MinION and PacBio Sequel II

---

## 2020

**Title:** 🇸🇪 🧬 [Evaluation of Single-Molecule Sequencing Technologies for Structural Variant Detection in Two Swedish Human Genomes](https://www.mdpi.com/2073-4425/11/12/1444)

**Platforms:** ONT's PromethION, and PacBio RS II.

#

**Title:** 🧬 [An Extensive Sequence Dataset of Gold-Standard Samples for Benchmarking and Development](https://www.biorxiv.org/content/10.1101/2020.12.11.422022v1)

**Platforms:**  PacBio Sequel II System (Chemistry 2.0), and Illumina (NovaSeq, HiSeq4000, and HiSeqX)

#

**Title:** 🧬 [Fully phased human genome assembly without parental data using single-cell strand sequencing and long reads](https://www.nature.com/articles/s41587-020-0719-5)

**Description:** "Assembly workflow that combines Strand-seq and long reads in a reference-free manner to provide fully phased and highly contiguous *de novo* assemblies of diploid human genomes"

**Platforms:** PacBio Sequel II (Chemistry v1), and PacBio  RSII  (P6-C4 Chemistry) and PacBio Sequel II (Chemistry 2.0) for BAC clone insert sequencing

#

**Title:** 📚 [Sequencing platform shifts provide opportunities but pose challenges for combining genomic datasets](https://onlinelibrary.wiley.com/doi/10.1111/1755-0998.13309)

**Description:** Opinion article that highlights impact of Illumina's base calling for sequencing data produced with four-channel chemistry (e.g. HiSeqX) and two-channel chemistry (e.g. NextSeq and NovaSeq).

#

**Title:** 🦠 [Analytical validity of nanopore sequencing for rapid SARS-CoV-2 genome analysis](https://www.nature.com/articles/s41467-020-20075-6)

**Platforms:** ONT PromethION and Illumina MiSeq

#

**Title:** 🌱 [Comparison of the two up-to-date sequencing technologies for genome assembly: HiFi reads of Pacific Biosciences Sequel II system and ultralong reads of Oxford Nanopore](https://academic.oup.com/gigascience/article/9/12/giaa123/6034784)

**Description:** Comparison of two assemblies of *Oryza sativa* (rice)

**Platforms:** ONT PromethION and PacBio Sequel II

#

**Title:** 🌱 [*Austropuccinia psidii*, causing myrtle  rust,  has a gigabase-sized genome shaped by transposable elements](https://academic.oup.com/g3journal/advance-article/doi/10.1093/g3journal/jkaa015/6007476) 

**Description:** A combination of long-read sequencing and Hi-C technology to generate contiguous dikaryotic reference genome. See Table 1 for statistics.

**Platforms:** PacBio  RSII (18  SMRT cells), PacBio Sequel (11 SMRT cells), Hi-C, and Illumina  paired-end  reads  (125bp  on  HiSeq, 150bp on NextSeq 500).

#

**Title:** 🧬 [Telomere-to-telomere assembly of a complete human X chromosome](https://www.nature.com/articles/s41586-020-2547-7)

**Description:** The study presents first ever gapless telomere-to-telomere assembly of human X chromosome, enabled by ultra-long reads.

**Platforms:** Illumina linked reads, 10X Genomics, PacBio (CLRs and HiFi Reads), ONT, and Hi-C.

#

**Title:** 🧬 [Benchmarking challenging small variants with linked and long reads](https://www.biorxiv.org/content/10.1101/2020.07.24.212712v1)

**Description:** Use of long and linked reads to expand Genome In A Bottle's benchmark in order to indentify regions such as segmental duplications.

**Platforms:** 10x Genomics, Complete Genomics, PacBio Sequel II, ONT.

#

**Title:** 🌱 [Siberian larch (*Larix sibirica Ledeb.*) mitochondrial genome assembled using both short and long nucleotide sequence reads is currently the largest known mitogenome](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-020-07061-4)

**Description:** Assessment of mitochondrial reads (using sequencing, assembly, and annotation) to study Siberian larch.

**Platforms:** Illumina (HiSeq 2000) and ONT (MinION).

#

**Title:** 🐟 [Draft genome assemblies using sequencing reads from Oxford Nanopore Technology and Illumina platforms for four species of North American killifish from the *Fundulus genus*](http://dx.doi.org/10.1093/gigascience/giaa067)

**Description:** A study on a collection of whole genome data of killifish species obtained from ONT and Illumina platforms

**Platforms:** ONT PromethION, and Illumina platforms (HiSeq 4000 and NovaSeq)

#

**Title:** [A technology-agnostic long-read analysis pipeline for transcriptome discovery and quantification](https://www.biorxiv.org/content/10.1101/672931v2) 

**Description:** Comparison of MinION and PacBio Sequel II for full-transcript discovery and quantification in GM12878 cell line. PacBio platform captured more as compared to direct-RNA performed by MinION, however PacBio data is prone to antisense transcript artifacts. PacBio Sequel II data was also compared with Illumina RNA-Seq data for expression levels.

**Platforms:** ONT MinION and PacBio Sequel II

#

**Title:** 🧬 [Long-read human genome sequencing and its applications](https://www.nature.com/articles/s41576-020-0236-x)

**Description:** A review article that focuses on SMRT sequencing and ONT, and compare those two major long-read technologies with short-read sequencing platforms in terms of read accuracy, throughput, and cost.

#

**Title:** 📚 [Opportunities and challenges in long-read sequencing data analysis](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-020-1935-5)

**Description:** An overview of the bioinformatics pipelines for nanopore and PacBio sequencing, with a focus on downstream analyses such as error correction, structural variant calling, and detection of base modifications.

#

**Title:** 🦠 [A preliminary study on the potential of Nanopore MinION and Illumina MiSeq 16S rRNA gene sequencing to characterize building-dust microbiomes](https://www.nature.com/articles/s41598-020-59771-0)

**Platforms:** ONT's MinION (FLO-MAP R7.3 flowcell) and Illumina MiSeq (16S Metagenomic Sequencing kit, 2×300bp paired-end) 

#

**Title:** 🦠 [Benchmarking of long-read assemblers for prokaryote whole genome sequencing](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6966772/)

**Platforms:** ONT MinION (R9.4), PacBio RSII (CLR), and Illumina (for hybrid assemblies)

#

**Title:** 🦁 [Long live the king: chromosome-level assembly of the lion (Panthera leo) using linked-read, Hi-C, and long-read data](https://bmcbiol.biomedcentral.com/articles/10.1186/s12915-019-0734-5)

**Description:** The study showed that data from 10x Genomics and Dovetai Hi-C were sufficient for chromosome genome assembly. For sequence fill-in (closing gaps between contigs with ambiguous sequence), nanopore data (MinION) was used. Besides quality of assembly and phylogenetic relationships of species taxa, the study reports how reference genome bias influences heterozygosity estimates across species.

#

**Title:** [Long-read error correction: a survey and qualitative comparison](https://www.biorxiv.org/content/10.1101/2020.03.06.977975v3)

**Description:** A comprehensive analysis of 29 tools using PacBio and nanopore data.

#

**Title:** [Overcoming uncollapsed haplotypes in long-read assemblies of non-model organisms](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-021-04118-3)

**Description:** Assessment of six long-read assembly algorithms for PacBio and ONT reads from a non-model non-vertebrate organism *Adineta vaga*

#

**Title:** 🇰🇷 🧬 [Comparative analysis of seven short-reads sequencing platforms using the Korean Reference Genome: MGI and Illumina sequencing benchmark for whole-genome sequencing](https://academic.oup.com/gigascience/article/10/3/giab014/6168811)

**Description:** Systematic comparison of a new whole-genome sequencer MGISEQ-T7 against Illumina short-read sequencers. The study concluded the MGI platform can be used for genomics research at nearly half the cost of the Illumina platforms.

**Platforms:** BGISEQ-500, MGISEQ-T7, HiSeq2000, HiSeq2500, HiSeq4000, HiSeqX10, and NovaSeq6000

#

**Title:** 🧬 [Comprehensive analysis of structural variants in breast cancer genomes using
single molecule sequencing](https://genome.cshlp.org/content/30/9/1258)

**Description:** Analysis of the SKBR3 breast cancer cell line and patient-derived organoids representing tumor and matching normal cells from two breast cancer
patients.

**Platforms:** ONT MinION (R9.1 flow cell) , PacBio Sequel (SMRTbell template prep kit 1.0), Illumina (TruSeq RNA Library prep kit), and 10x Genomics

---

Contribute by submitting [pull requests](https://github.com/Nazeeefa/awesome-sequencing-tech-papers/pulls), or posting suggestions as [issues](https://github.com/Nazeeefa/awesome-sequencing-tech-papers/issues). Thank you.
