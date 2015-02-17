LUMPY
=====

A probabilistic framework for structural variant discovery

Ryan M Layer, Colby Chiang, Aaron R Quinlan, and Ira M Hall. 2014. "LUMPY: a Probabilistic Framework for Structural Variant Discovery." Genome Biology 15 (6): R84. [doi:10.1186/gb-2014-15-6-r84](http://dx.doi.org/10.1186/gb-2014-15-6-r84).

## Table of Contents
1. [Requirements](#requirements)
2. [Quick start](#quick-start)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Example workflows](#example-workflows)

## Requirements
- samtools or sambamba
- SAMBLASTER
- python2.7
    * pysam
    * numpy

## Quick start
```
git clone --recursive git@github.com:arq5x/lumpy-sv.git

cd lumpy-sv
make

bin/lumpyexpress \
    -B sample.bam \
    -o out-prefix \
```

## Installation