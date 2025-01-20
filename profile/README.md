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

| Package | Description | Links |
|---------|-------------|-------|
| BiocFrame | Bioconductor-like data frames | [GitHub](https://github.com/BiocPy/BiocFrame) \| [Docs](https://biocpy.github.io/BiocFrame/) |
| IRanges | Interval arithmetic operations | [GitHub](https://github.com/BiocPy/IRanges) \| [Docs](https://biocpy.github.io/IRanges/) \| [Bioconductor](https://bioconductor.org/packages/release/bioc/html/IRanges.html) |
| GenomicRanges | Genomic location analysis | [GitHub](https://github.com/BiocPy/GenomicRanges) \| [Docs](https://biocpy.github.io/GenomicRanges/) \| [Bioconductor](https://bioconductor.org/packages/release/bioc/html/GenomicRanges.html) |

### Containers

| Package | Description | Links |
|---------|-------------|-------|
| SummarizedExperiment | Genomic experiments container | [GitHub](https://github.com/BiocPy/SummarizedExperiment) \| [Docs](https://biocpy.github.io/SummarizedExperiment/) \| [Bioconductor](https://bioconductor.org/packages/release/bioc/html/SummarizedExperiment.html) |
| SingleCellExperiment | Single-cell genomics container | [GitHub](https://github.com/BiocPy/SingleCellExperiment) \| [Docs](https://biocpy.github.io/SingleCellExperiment/) \| [Bioconductor](https://bioconductor.org/packages/release/bioc/html/SingleCellExperiment.html) |
| MultiAssayExperiment | Multi-omics data framework | [GitHub](https://github.com/BiocPy/MultiAssayExperiment) \| [Docs](https://biocpy.github.io/MultiAssayExperiment/) \| [Bioconductor](https://bioconductor.org/packages/release/bioc/html/MultiAssayExperiment.html) |


### R Interoperability

- **rds2py**: Read RDS files directly in Python ([GitHub](https://github.com/BiocPy/rds2py) \| [Docs](https://biocpy.github.io/rds2py/))
- **BiocUtils**: Common utilities mirroring R's base functionality ([GitHub](https://github.com/BiocPy/biocutils) \| [Docs](https://biocpy.github.io/BiocUtils/))
- **mopsy**: Matrix operations with R-like syntax ([GitHub](https://github.com/BiocPy/mopsy) \| [Docs](https://biocpy.github.io/mopsy/))
- **pyBiocFileCache**: Resource caching system ([GitHub](https://github.com/BiocPy/pyBiocFileCache) \| [Docs](https://biocpy.github.io/pyBiocFileCache/))


## BiocPy Ecosystem

BiocPy integrates with several analysis tools and frameworks

### Analysis Tools

- [libscran](https://github.com/libscran): Multi-model single-cell analysis in R, Python and JavaScript.
- [SingleR-inc](https://github.com/SingleR-inc): Cell type annotation for single-cell data.

### Data Management

- [ArtifactDB](https://github.com/ArtifactDB): Language-agnostic access to data across computational environments.
- [tatami-inc](https://github.com/tatami-inc): Read various matrix representations through a common interface.

### Model Training

- [TileOme](https://github.com/TileOme): TileDB-based genomic data storage with AI/ML dataloaders.

## Installation

All packages in the `BiocPy` are published to [PyPI](https://pypi.org/). Install the core packages using the `biocpy` wrapper:

```sh
pip install biocpy
```

Individual packages can be installed separately. See each package's documentation for specific installation instructions.

----

## Contributing

We welcome contributions! Check out our [developer guide](https://github.com/BiocPy/developer_guide) to get started.
