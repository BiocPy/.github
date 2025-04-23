![BiocPy logo](https://raw.githubusercontent.com/BiocPy/.github/main/logo/full.png)

# BiocPy: Facilitate Bioconductor Workflows in Python

**BiocPy brings [Bioconductor](https://www.bioconductor.org)'s core data structures and analysis tools to the Python ecosystem.** 
These structures, including [BiocFrame](https://github.com/BiocPy/BiocFrame) and [GenomicRanges](https://github.com/BiocPy/GenomicRanges), 
serve as essential and foundational data structures, acting as the building 
blocks for extensive and complex representations. 
For example, container classes like 
[SummarizedExperiment](https://github.com/BiocPy/SummarizedExperiment), [SingleCellExperiment](https://github.com/BiocPy/SingleCellExperiment), 
and [MultiAssayExperiment](https://github.com/BiocPy/MultiAssayExperiment) represent single or multi-omic experimental data and metadata.

> [!NOTE]
> #### Resources:
> - **🔥 [Workshop tutorials from Bioc2024](https://biocpy.github.io/BiocWorkshop2024/)**
> - **📚 [WIP] [BiocPy book - Tutorials and guides](https://biocpy.github.io/tutorial/)**

## Core Packages

For a complete list of packages, visit our [GitHub organization](https://github.com/orgs/BiocPy/repositories).


### Data Structures

| Package | Description | PyPI | Links |
|---------|-------------|------|-------|
| BiocFrame | Bioconductor-like data frames | [![PyPI](https://img.shields.io/pypi/v/BiocFrame.svg)](https://pypi.org/project/BiocFrame/) | [GitHub](https://github.com/BiocPy/BiocFrame) \| [Docs](https://biocpy.github.io/BiocFrame/) |
| IRanges | Interval arithmetic operations | [![PyPI](https://img.shields.io/pypi/v/iranges.svg)](https://pypi.org/project/iranges/) | [GitHub](https://github.com/BiocPy/IRanges) \| [Docs](https://biocpy.github.io/IRanges/) \| [Bioconductor](https://bioconductor.org/packages/release/bioc/html/IRanges.html) |
| GenomicRanges | Genomic location analysis | [![PyPI](https://img.shields.io/pypi/v/genomicranges.svg)](https://pypi.org/project/genomicranges/) | [GitHub](https://github.com/BiocPy/GenomicRanges) \| [Docs](https://biocpy.github.io/GenomicRanges/) \| [Bioconductor](https://bioconductor.org/packages/release/bioc/html/GenomicRanges.html) |

### Containers

| Package | Description | PyPI | Links |
|---------|-------------|------|-------|
| SummarizedExperiment | Genomic experiments container | [![PyPI](https://img.shields.io/pypi/v/summarizedexperiment.svg)](https://pypi.org/project/summarizedexperiment/) | [GitHub](https://github.com/BiocPy/SummarizedExperiment) \| [Docs](https://biocpy.github.io/SummarizedExperiment/) \| [Bioconductor](https://bioconductor.org/packages/release/bioc/html/SummarizedExperiment.html) |
| SingleCellExperiment | Single-cell genomics container | [![PyPI](https://img.shields.io/pypi/v/singlecellexperiment.svg)](https://pypi.org/project/singlecellexperiment/) | [GitHub](https://github.com/BiocPy/SingleCellExperiment) \| [Docs](https://biocpy.github.io/SingleCellExperiment/) \| [Bioconductor](https://bioconductor.org/packages/release/bioc/html/SingleCellExperiment.html) |
| SpatialExperiment | Spatial transcriptomics container | [![PyPI](https://img.shields.io/pypi/v/spatialexperiment.svg)](https://pypi.org/project/spatialexperiment/) | [GitHub](https://github.com/BiocPy/SpatialExperiment) \| [Docs](https://biocpy.github.io/SpatialExperiment/) \| [Bioconductor](https://bioconductor.org/packages/release/bioc/html/SpatialExperiment.html) |
| SpatialFeatureExperiment | Extends Spatial transcriptomics container | [![PyPI](https://img.shields.io/pypi/v/spatialfeatureexperiment.svg)](https://pypi.org/project/spatialfeatureexperiment/) | [GitHub](https://github.com/BiocPy/SpatialFeatureExperiment) \| [Docs](https://biocpy.github.io/SpatialFeatureExperiment/) \| [Bioconductor](https://bioconductor.org/packages/release/bioc/html/SpatialFeatureExperiment.html) |
| MultiAssayExperiment | Multi-omics data framework | [![PyPI](https://img.shields.io/pypi/v/multiassayexperiment.svg)](https://pypi.org/project/multiassayexperiment/) | [GitHub](https://github.com/BiocPy/MultiAssayExperiment) \| [Docs](https://biocpy.github.io/MultiAssayExperiment/) \| [Bioconductor](https://bioconductor.org/packages/release/bioc/html/MultiAssayExperiment.html) |


### R Interoperability

| Package | Description | PyPI | Links |
|---------|-------------|------|-------|
| rds2py | Read RDS files directly in Python | [![PyPI](https://img.shields.io/pypi/v/rds2py.svg)](https://pypi.org/project/rds2py/) | [GitHub](https://github.com/BiocPy/rds2py) \| [Docs](https://biocpy.github.io/rds2py/) |
| BiocUtils | Common utilities mirroring R's base functionality | [![PyPI](https://img.shields.io/pypi/v/biocutils.svg)](https://pypi.org/project/biocutils/) | [GitHub](https://github.com/BiocPy/biocutils) \| [Docs](https://biocpy.github.io/BiocUtils/) |
| mopsy | Matrix operations with R-like syntax | [![PyPI](https://img.shields.io/pypi/v/mopsy.svg)](https://pypi.org/project/mopsy/) | [GitHub](https://github.com/BiocPy/mopsy) \| [Docs](https://biocpy.github.io/mopsy/) |
| pyBiocFileCache | Resource caching system | [![PyPI](https://img.shields.io/pypi/v/pybiocfilecache.svg)](https://pypi.org/project/pybiocfilecache/) | [GitHub](https://github.com/BiocPy/pyBiocFileCache) \| [Docs](https://biocpy.github.io/pyBiocFileCache/) \| [Bioconductor](https://www.bioconductor.org/packages/release/bioc/html/BiocFileCache.html) |

#### Delayed Operations

| Package | Description | PyPI | Links |
|---------|-------------|------|-------|
| DelayedArray | Delayed operations in Python | [![PyPI](https://img.shields.io/pypi/v/delayedarray.svg)](https://pypi.org/project/delayedarray/) | [GitHub](https://github.com/BiocPy/DelayedArray) \| [Docs](https://biocpy.github.io/DelayedArray/)  \| [Bioconductor](https://bioconductor.org/packages/release/bioc/html/DelayedArray.html) |
| HDF5Array | HDF5-backed arrays | [![PyPI](https://img.shields.io/pypi/v/hdf5array.svg)](https://pypi.org/project/hdf5array/) | [GitHub](https://github.com/BiocPy/HDF5Array) \| [Docs](https://biocpy.github.io/HDF5Array/) \| [Bioconductor](https://bioconductor.org/packages/release/bioc/html/HDF5Array.html) |
| TileDBArray | TileDB-backed arrays | [![PyPI](https://img.shields.io/pypi/v/mopsy.svg)](https://pypi.org/project/mopsy/) | [GitHub](https://github.com/BiocPy/TileDBArray) \| [Docs](https://biocpy.github.io/TileDBArray/) \| [Bioconductor](https://bioconductor.org/packages/release/bioc/html/TileDBArray.html) |

----

## Get Started
All packages in the `BiocPy` are published to [BiocPy PyPI org](https://pypi.org/org/BiocPy/). Install the core packages using the `biocpy` wrapper:

```sh
pip install biocpy
```

Individual packages can be installed separately. See each package's documentation for specific installation instructions.

### Environments

We provide conda/mamba configuration files to create environments containing most BiocPy (& friends) packages. 
Check out the [environments repository](https://github.com/biocpy/environments) for more information.

----

## Friends of BiocPy

BiocPy integrates with several analysis tools and frameworks

### Analysis Tools

- [libscran](https://github.com/libscran): Multi-model single-cell analysis in R, Python and JavaScript.
- [SingleR-inc](https://github.com/SingleR-inc): Cell type annotation for single-cell data.

### Data Management

- [ArtifactDB](https://github.com/ArtifactDB): Language-agnostic access to data across computational environments.
- [tatami-inc](https://github.com/tatami-inc): Read various matrix representations through a common interface.

### Model Training

- [CellArr](https://github.com/CellArr): TileDB-based genomic data storage with AI/ML dataloaders.

----

## Contributing

We welcome contributions! Check out our [developer guide](https://github.com/BiocPy/developer_guide) to get started.
