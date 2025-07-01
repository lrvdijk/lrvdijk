# Hi there 👋

I am a software engineer and computational biologist with a strong background
algorithm design, machine learning, and genomic data analysis.
I am comfortable with low-level performance engineering in languages such as C++ and Rust,
and experienced with high-level data analysis and visualization in Python and JavaScript.

<p align="center">
    <img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue" alt="Python" height="25">
    <img src="https://img.shields.io/badge/Rust-black?style=for-the-badge&logo=rust&logoColor=#E57324" alt="Rust" height="25">
    <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" height="25">
</p>

## Interests

* Machine learning for multi-modal data integration (genomic, transcriptomic, and proteomic)
* Protein language models
* Sequence alignment algorithms
* Microbiome and metagenomics

## Bioinformatics tools and analyses

### 🤖 Protein machine learning and language models

* **[Flamino](https://github.com/lrvdijk/flamino)**. A Flax NNX-based reimplementation of the ESM-2 protein language model.

### 🧬 Sequence alignment and graph genomes

* **[POASTA](https://github.com/lrvdijk/poasta)**. A new algorithm for Partial Order Alignment (POA), a form of DNA sequence-to-DAG alignment.
POA is a common component in pangenome graph construction pipelines, such as the pipelines used to construct the human pangenome reference graph \[[1](https://www.nature.com/articles/s41587-023-01793-w), [2](https://www.nature.com/articles/s41592-024-02430-3)\].
POASTA outperformed existing tools by 4.1x and enabled alignments not possible before, while retaining the guarantee of optimality. Published in [Oxford Bioinformatics (2025)](https://academic.oup.com/bioinformatics/article/41/1/btae757/7942505).
* **[Pyfrost](https://github.com/broadinstitute/pyfrost)**. A high-performance and low-memory Python library to construct and analyze _compacted, colored de Bruijn graphs_ (ccDBGs).
The ccDBG is a commonly used data structure in _de novo_ genome assemblers.
The library includes Python bindings to a fast, memory efficient, and C++-based ccDBG library [Bifrost](https://github.com/pmelsted/bifrost), and provides a NetworkX-like API.
* **[Tesserae](https://github.com/castcollab/tesserae2)**. A recombination-aware DNA sequence aligner that uses a hidden markov model (HMM) to determine the optimal alignment of a query sequence to a panel of potential reference sequences. This is an improved, much faster version of the HMM described in a paper analyzing _de novo_ genetic variants in experimental crossess of the malaria parasite _Plasmodium falciparum_ \[[1](https://genome.cshlp.org/content/30/8/1154.long)\].

### 💩 Microbiome and metagenomics

* **[Strain Genome Explorer (StrainGE)](https://gitub.com/broadinstitute/strainge)**. A toolkit to detect and characterize low-abundance bacterial strain-level genetic diversity in whole metagenomic data.
Published in [Genome Biology (2022)](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-022-02630-0). I used StrainGE to obtain detailed insights into the gut and bladder E. coli dynamics of women with recurrent UTIs in a year-long study published in [Nature Microbiology (2022)](https://www.nature.com/articles/s41564-022-01107-x).

### 🛠️ Tooling and editors

* **[Zed WDL](https://github.com/broadinstitute/zed-wdl)**. An extension for the code editor [Zed](https://zed.dev/) providing syntax highlighting and code completion support for the Workflow Description Language (WDL).
* **[dotfiles](https://github.com/lrvdijk/dotfiles)**. My personal configuration files for various tools and editors.

## Old projects

### 🥳 Social and fun

* **[Reddit /r/place headless pixel placement bot](https://github.com/PlaceNL2022/rPlace2022)**. A CLI tool written in Python that would automatically place pixels on Reddit's /r/place canvas during its 2022 April Fool's event. It obtains instructions from a command and control server, and then logins to Reddit and to submit the correct pixel color.

### 💻 Embedded software and electronics

* **[TLC5940 Raspberry Pi Driver](https://github.com/lrvdijk/tlc5940-raspberry)**. The TLC5940 is a commonly used LED driver chip that can drive up to 16 LEDs (or more if chaining multiple chips).
This C++ library provides a simple interface to control the TLC5940 from a Raspberry Pi.

### 📊 Data visualization

* **[OpenGL-powered graph visualization system in VisPy](https://vispy.org)**. As part of the Google Summer of Code 2015, I contributed an OpenGL-powered graph visualization system in VisPy: I added OpenGL visuals required for displaying graphs and implemented several automatic graph layout algorithms. I additionally blogged about how to [draw arbitrary shapes using OpenGL points](https://lucasvandijk.nl/2015/06/drawing-arbitrary-shapes-with-opengl-points/).
* **[Visualizing the height of the Netherlands](https://github.com/lrvdijk/nl-height)**. Data preprocessing and visualiztion scripts to explore the height of the Netherlands. Built with PostgreSQL+PostGIS and d3.js. For the visualization, [see my blog post](https://lucasvandijk.nl/2018/02/visualizing-the-height-of-the-netherlands/).
