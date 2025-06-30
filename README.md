# Hi there 👋

I am a software engineer and computational biologist with a strong background
algorithm design, machine learning, and genomic data analysis.

## Interests

* Machine learning
* Multi-modal data integration (genomic, transcriptomic, and proteomic)
* Protein language models
* Sequence alignment algorithms
* Microbiome and metagenomics

## Tools and analyses

### 🤖 Protein machine learning and language models

* **[Flamino](https://github.com/lrvdijk/flamino)**. A Flax NNX-based reimplementation of the ESM-2 protein language model.

### 🧬 Sequence alignment and graph genomes

* **[POASTA](https://github.com/lrvdijk/poasta)**. A new algorithm for Partial Order Alignment (POA), a form of DNA sequence-to-DAG alignment.
POA is a common component in pangenome graph construction pipelines, such as the pipelines used to construct the human pangenome reference graph \[[1](https://www.nature.com/articles/s41587-023-01793-w), [2](https://www.nature.com/articles/s41592-024-02430-3)\].
POASTA outperformed existing tools by 4.1x and enabled alignments not possible before, while retaining the guarantee of optimality. Published in [Oxford Bioinformatics (2025)](https://academic.oup.com/bioinformatics/article/41/1/btae757/7942505).
* **[Pyfrost](https://github.com/lrvdijk/pyfrost)**. A high-performance and low-memory Python library to construct and analyze _compacted, colored de Bruijn graphs_ (ccDBGs).
The ccDBG is a commonly used data structure in _de novo_ genome assemblers.
The library includes Python bindings to a fast, memory efficient, and C++-based ccDBG library [Bifrost](https://github.com/pmelsted/bifrost), and provides a NetworkX-like API.
* **[Tesserae](https://github.com/castcollab/tesserae2)**. A recombination-aware DNA sequence aligner that uses a hidden markov model (HMM) to determine the optimal alignment of a query sequence to a panel of potential reference sequences. This is an improved, much faster version of the HMM described in a paper analyzing _de novo_ genetic variants in experimental crossess of the malaria parasite _Plasmodium falciparum_ \[[1](https://genome.cshlp.org/content/30/8/1154.long)\].

### 💩 Microbiome and metagenomics

* **[Strain Genome Explorer (StrainGE)](https://gitub.com/broadinstitute/strainge)**. A toolkit to detect and characterize low-abundance bacterial strain-level genetic diversity in whole metagenomic data.
Published in [Genome Biology (2022)](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-022-02630-0). I used StrainGE to obtain detailed insights into gut and bladder E. coli dynamics of women with recurrent UTIs in a year-long study published in [Nature Microbiology (2022)](https://www.nature.com/articles/s41564-022-01107-x).
