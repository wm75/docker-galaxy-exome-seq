[![Build Status](https://travis-ci.org/bgruening/docker-galaxy-exome-seq.svg?branch=master)](https://travis-ci.org/bgruening/docker-galaxy-exome-seq)
[![Docker Repository on Quay](https://quay.io/repository/bgruening/galaxy-exome-seq/status "Docker Repository on Quay")](https://quay.io/repository/bgruening/galaxy-exome-seq)
[![Gitter](https://badges.gitter.im/bgruening/docker-galaxy-stable.svg)](https://gitter.im/bgruening/docker-galaxy-stable?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

Galaxy Image for Exome/Whole-Genome Sequencing Analysis
=======================================================

:whale: Galaxy Docker repository for exome sequencing data analysis (Galaxy exome sequencing flavor)

# Installed tools

 * [BWA](http://bio-bwa.sourceforge.net/)
 * [Bowtie2](http://bowtie-bio.sourceforge.net/bowtie2)
 * [SnpEff](http://snpeff.sourceforge.net/)
 * [FASTQC](http://www.bioinformatics.babraham.ac.uk/projects/fastqc/)
 * [SAMTools](http://samtools.sourceforge.net/)
 * [FreeBayes](https://github.com/ekg/freebayes)
 * [GEMINI](http://gemini.readthedocs.org)
 * [deepTools](http://fidelram.github.io/deepTools/)
 * [MultiQC](https://multiqc.info/)
 * [Qualimap](http://qualimap.bioinfo.cipf.es/)
 * [JBrowse](http://jbrowse.org/)
 * [Circos](http://circos.ca/)

# Requirements

 - [Docker](https://docs.docker.com/installation/) for Linux / Windows / OSX
 - [Kitematic](https://kitematic.com/) for Windows / OS-X

# Training

To learn what kind of analyses you can perform with this Galaxy flavor, have a
look at the following
[Galaxy training network](https://training.galaxyproject.org/training-material/)
tutorials:

- [Exome sequencing data analysis for diagnosing a genetic disease](https://galaxyproject.github.io/training-material/topics/variant-analysis/tutorials/exome-seq/tutorial.html)
- [Identification of somatic and germline variants from tumor and normal sample pairs](https://training.galaxyproject.org/training-material/topics/variant-analysis/tutorials/somatic-variants/tutorial.html)
- [Mapping and molecular identification of phenotype-causing mutations](https://galaxyproject.github.io/training-material/topics/variant-analysis/tutorials/mapping-by-sequencing/tutorial.html)

# Usage

To launch:

```
docker run -d -p 8080:80 -p 8021:21 -p 8022:22 bgruening/galaxy-exome-seq
```

For more details about this command line or specific usage, please consult the
[`README`](https://github.com/bgruening/docker-galaxy-stable/blob/master/README.md) of the main Galaxy Docker image, on which the current image is based.

# Contributors

- Bjoern Gruening
- Bérénice Batut
- Wolfgang Maier

# Support & Bug Reports

You can file a [github issue](https://github.com/bgruening/galaxy-exom-seq/issues) or ask us on the [Galaxy help forum](https://help.galaxyproject.org/).
