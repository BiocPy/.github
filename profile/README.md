# BiocPy: enabling Bioconductor workflows in Python

**BiocPy is an effort to bring core data structures and representations from [Bioconductor](https://www.bioconductor.org) to Python.**

Currently, the following **core** packages are available - 
- `BiocFrame` ([GitHub](https://github.com/BiocPy/BiocFrame), [Docs](https://biocpy.github.io/BiocFrame/)): A lite version of dataframes. It is not equivalent to `Pandas` but provides many similar operations.
- `GenomicRanges` ([GitHub](https://github.com/BiocPy/GenomicRanges), [Docs](https://biocpy.github.io/GenomicRanges/), [BioC](https://bioconductor.org/packages/release/bioc/html/GenomicRanges.html)): Container class to represent genomic locations and support genomic analysis. Similar to Bioconductor's [GenomicRanges](https://bioconductor.org/packages/release/bioc/html/GenomicRanges.html).
- `SummarizedExperiment` ([GitHub](https://github.com/BiocPy/SummarizedExperiment), [Docs](https://biocpy.github.io/SummarizedExperiment/), [BioC](https://bioconductor.org/packages/release/bioc/html/SummarizedExperiment.html)): Container class to represent genomic experiments, following Bioconductor's [SummarizedExperiment](https://bioconductor.org/packages/release/bioc/html/SummarizedExperiment.html).
- `SingleCellExperiment` ([GitHub](https://github.com/BiocPy/SingleCellExperiment), [Docs](https://biocpy.github.io/SingleCellExperiment/), [BioC](https://bioconductor.org/packages/release/bioc/html/SingleCellExperiment.html)): Container class to represent single-cell experiments; follows Bioconductor’s [SingleCellExperiment](https://bioconductor.org/packages/release/bioc/html/SingleCellExperiment.html).
- `MultiAssayExperiment` ([GitHub](https://github.com/BiocPy/MultiAssayExperiment), [Docs](https://biocpy.github.io/MultiAssayExperiment/), [BioC](https://bioconductor.org/packages/release/bioc/html/MultiAssayExperiment.html)): Container class to represent multiple experiments and assays performed over a set of samples. follows Bioconductor's [MAE R/Bioc Package](https://bioconductor.org/packages/release/bioc/html/MultiAssayExperiment.html).

**Utility packages**

- `rds2py` ([GitHub](https://github.com/BiocPy/rds2py), [Docs](https://biocpy.github.io/rds2py/)): Parse, extract and create Python representations for datasets stored in RDS files. Currently supports Bioconductor's `SummarizedExperiment` and `SingleCellExperiment` objects.
- `mopsy` ([GitHub](https://github.com/BiocPy/mopsy), [Docs](https://biocpy.github.io/mopsy/)): Convenience library to perform row/column operations over numpy and scipy matrices. Provides an interface similar to base R matrix methods/MatrixStats methods.
- `pyBiocFileCache` ([GitHub](https://github.com/BiocPy/pyBiocFileCache), [Docs](https://pypi.org/project/pyBiocFileCache/), [BioC](https://github.com/Bioconductor/BiocFileCache)): File system based cache for resources & metadata. 

## Installation

All packages in the `BiocPy` ecosystem are published to Python's Package Index - [PyPI](https://pypi.org/). 

`BiocPy` is a wrapper package that installs all packages in the ecosystem

```sh
pip install biocpy
```

Packages can also be installed individually. Checkout package docs for installation instructions.


### Immediate goals

***This is not an exhaustive list. more to come...***

- [ ] Visualization interfaces preferably to existing packages, [epiviz](https://github.com/epiviz/epiviz-chart)? [pygenomeViz](https://moshi4.github.io/pyGenomeViz/)? [gosling](https://github.com/gosling-lang/gos)? [pyGenomeTracks](https://github.com/deeptools/pyGenomeTracks)?
  - [ ] also something like [complexHeatMap](https://jokergoo.github.io/ComplexHeatmap-reference/book/) would be nice
- [ ] language-agnostic serialization, hdf5 based formats or protobufs?
- [ ] Import from common genomic file formats, something like [rtracklayer](https://www.bioconductor.org/packages/release/bioc/html/rtracklayer.html)
  - [ ] can repurpose [epivizFileParser](https://github.com/epiviz/epivizFileParser)
- [ ] Interfaces to frequently used analysis methods
- [ ] Outreach and community feedback, involvement and support.


### Future

- [ ] File backed mode for formats that support in-situ querying
- [ ] Delayed operations
- [ ] Optimizations and in general enhancements
- [ ] Interfaces to commonly used analysis methods

