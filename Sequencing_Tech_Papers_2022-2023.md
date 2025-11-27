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
## 2023

**Title:** [Primed and ready: Nanopore metabarcoding can now recover highly accurate consensus barcodes that are generally indel-free](https://www.biorxiv.org/content/10.1101/2023.08.04.552069v1.full)

**Description:** Sequencing of zooplankton samples to recover molecular operational taxonomic units (MOTUs). At the sample-level, Illumina metabarcoding recovered more MOTUs than nanopore.

**Platforms:** Illumina MiSeq and ONT's minION (R10.3 chemistry)

#

🧬💉 **Title:** [Performance analysis of conventional and AI-based variant callers using short and long reads](https://link.springer.com/article/10.1186/s12859-023-05596-3)

**Description:** Becnhmarking of five variant‑calling tools (conventional and AI‑based) on the same human samples from the Genome In A Bottle (GIAB) dataset, using data from Illumina, PacBio Hi‑Fi, and ONT. The study finds that AI‑based callers (especially DeepVariant and DNAscope) outperform conventional tools (e.g. BCFTools, GATK4, Platypus) when calling SNVs and INDELs across both long- and short-read data. On PacBio Hi‑Fi, precision and recall for SNVs/INDELs exceed ~99.9%; on ONT data, DeepVariant yields higher recall and precision than BCFTools (though both detect many ONT-specific variants likely due to error profile). The study also compares computational cost: conventional tools tend to run faster and use less memory, while AI-based callers demand more computing resources.

**Platforms:** Illumina HiSeq2500 as a reference, PacBio (Hi‑Fi, CCS), and ONT.

#

**Title:** [The long and short of it: Benchmarking viromics using Illumina, Nanopore and PacBio sequencing technologies](https://www.biorxiv.org/content/10.1101/2023.02.12.527533v1)

**Description:** Assessment of assembly algorithms for the analysis of viromes (mock community of 15 bacteriophage genomes), and assessment of error rates across different platforms.

**Platforms:** Illumina MiSeq (NexteraXT library prep kit), minION (library prep by SQK-LSK109), and PacBio Sequel.

## 2022

**Title:** [Sequencing of individual barcoded cDNAs on Pacific Biosciences and Oxford Nanopore reveals platform-specific error patterns](https://www.biorxiv.org/content/10.1101/2022.01.17.476636v1)

**Description:** Isoform analysis of mouse data via sequencing cDNA of reverse transcription events.

**Platforms:** PacBio Sequel II, and ONT PromethION

#

**Title:** 🧬 [Target enrichment long-read sequencing with adaptive sampling can determine the structure of the small supernumerary marker chromosomes](https://www.nature.com/articles/s10038-021-01004-x)

**Description:** Comparative analysis of two clinical samples

**Platforms:** HiSeq 1500 (2 × 101 bp) and, ONT's GridION using R9.4.1 flowcell (ligation sequencing kit SQK-LSK109)

#

**Title:** 🧬 [An assessment of bioinformatics tools for the detection of human endogenous retroviral insertions in short-read genome sequencing data](https://www.biorxiv.org/content/10.1101/2022.02.18.481042v1)

**Description:** Analysis of 50 human endogenous retroviruses (HERVs) short-read whole-genome sequences, "matching long and short read data, and simulated short-read data."

**Platforms:** Illumina HiSeq 2000 and 2500, and PacBio Sequel
