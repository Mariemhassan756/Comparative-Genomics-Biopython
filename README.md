# Comparative Genomics: Analyzing DNA Length and GC Content

## 📌 Project Overview
As a beginner in Bioinformatics, this is my first practical project focusing on **Comparative Genomics**. The goal of this project is to analyze and compare real genomic sequences from two different organisms to determine their sequence length and thermal stability based on their **GC Fraction**.

## 🧬 Scientific Background
* **Sequence Length:** Indicates the size of the sequenced genomic fragment.
* **GC Content (GC Fraction):** Guanine (G) and Cytosine (C) pairs share three hydrogen bonds, making them chemically stronger than Adenine (A) and Thymine (T) pairs (which share only two). Therefore, a higher GC content indicates higher structural and thermal stability of the DNA sequence under extreme conditions.

## 🛠️ Tools Used
* **Language:** Python
* **Libraries:** Biopython (`Bio.SeqIO`, `Bio.SeqUtils.gc_fraction`)
* **Environment:** Google Colab

## 📊 Methodology & Workflow
1. **Data Fetching:** Automatically downloaded real FASTA sequence files using Python's `urllib` from official biological repositories.
2. **Parsing:** Utilized `SeqIO.parse` to read the FASTA files.
3. **Calculation:** Computed the sequence lengths using `len()` and the GC fractions using `gc_fraction()`.

## 📈 Results & Key Findings
* **Organism 1 (Orchid Genom):** Had shorter sequence lengths (Max: ~784 bp) but demonstrated **significantly higher thermal stability** with a GC fraction of **51.4%**.
* **Organism 2 (Opuntia Genom):** Had longer sequence lengths (Max: ~902 bp) but showed lower stability with a GC fraction of only **27.3%**.

**Conclusion:** Organism 1 is genetically more stable and resilient to thermal stress compared to Organism 2, despite having shorter DNA fragments.
