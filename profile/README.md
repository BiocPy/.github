![BiocPy logo](https://raw.githubusercontent.com/BiocPy/.github/main/logo/full.png)

# BiocPy: Facilitate Bioconductor Workflows in Python

**BiocPy is an effort to develop core data structures and representations from [Bioconductor](https://www.bioconductor.org) to Python.** 
These structures, including [BiocFrame](https://github.com/BiocPy/BiocFrame) and [GenomicRanges](https://github.com/BiocPy/GenomicRanges), 
serve as essential and foundational data structures, acting as the building 
blocks for extensive and complex representations. 
For example, container classes like 
[SummarizedExperiment](https://github.com/BiocPy/SummarizedExperiment), [SingleCellExperiment](https://github.com/BiocPy/SingleCellExperiment), 
and [MultiAssayExperiment](https://github.com/BiocPy/MultiAssayExperiment) represent single or multi-omic experimental data and metadata.

### 🔥 Explore the tutorial website - [https://biocpy.github.io/tutorial/](https://biocpy.github.io/tutorial/).

## Selected packages

For complete list of all packages, visit the 
[GitHub:BiocPy](https://github.com/orgs/BiocPy/repositories) repository.

#### Core Representations:

- `BiocFrame`: Bioconductor-like data frames in Python. ([GitHub](https://github.com/BiocPy/BiocFrame), [Docs](https://biocpy.github.io/BiocFrame/))
- `IRanges`: Python implementation of the IRanges package to support interval arithmetic. ([GitHub](https://github.com/BiocPy/IRanges), [Docs](https://biocpy.github.io/IRanges/))
- `GenomicRanges`: Container class to represent genomic locations and support genomic analysis. ([GitHub](https://github.com/BiocPy/GenomicRanges), [Docs](https://biocpy.github.io/GenomicRanges/), [BioC](https://bioconductor.org/packages/release/bioc/html/GenomicRanges.html))
- `SummarizedExperiment`: Container class to represent genomic experiments, following Bioconductor's SummarizedExperiment. ([GitHub](https://github.com/BiocPy/SummarizedExperiment), [Docs](https://biocpy.github.io/SummarizedExperiment/))
- `SingleCellExperiment`: Container class to represent single-cell experiments; follows Bioconductor’s SingleCellExperiment. ([GitHub](https://github.com/BiocPy/SingleCellExperiment), [Docs](https://biocpy.github.io/SingleCellExperiment/))
- `MultiAssayExperiment`: Container class to represent multiple experiments and assays performed over a set of samples, following Bioconductor's MAE R/Bioc Package. ([GitHub](https://github.com/BiocPy/MultiAssayExperiment), [Docs](https://biocpy.github.io/MultiAssayExperiment/))

#### Analysis Packages

- `scranpy`: Python bindings to single-cell analysis methods from libscran and related C++ libraries. ([GitHub](https://github.com/BiocPy/scranpy), [Docs](https://biocpy.github.io/scranpy/))
- `singler`: Python bindings to the singleR algorithm to annotate cell types from known references. ([GitHub](https://github.com/BiocPy/singler), [Docs](https://biocpy.github.io/singler/))

#### Interoperability with R

- `rds2py`: Read RDS files directly in Python, supporting Bioconductor's SummarizedExperiment and SingleCellExperiment, in addition to matrices, data frames, and vectors. ([GitHub](https://github.com/BiocPy/rds2py), [Docs](https://biocpy.github.io/rds2py/))

#### Utility Packages

- `BiocUtils`: Common utilities for use across packages, mostly to mimic convenient aspects of base R. ([GitHub](https://github.com/BiocPy/BiocUtils), [Docs](https://biocpy.github.io/BiocUtils/))
- `mopsy`: Helper functions to perform row or column operations over numpy and scipy matrices, providing an interface similar to base R matrix methods/MatrixStats methods. ([GitHub](https://github.com/BiocPy/mopsy), [Docs](https://biocpy.github.io/mopsy/))
- `pyBiocFileCache`: File system-based cache for resources & metadata. ([GitHub](https://github.com/BiocPy/pyBiocFileCache), [Docs](https://pypi.org/project/pyBiocFileCache/))

## Installation

All packages in the `BiocPy` ecosystem are published to [PyPI](https://pypi.org/). Use the `biocpy` wrapper to install the core packages:

```sh
pip install biocpy
```

Individual packages can also be installed separately. Refer to package's documentation for more details.

----

### Interested in contributing? Check out the [developer guide](https://github.com/BiocPy/developer_guide).
