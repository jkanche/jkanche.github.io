---
title: Projects
---
> If you’re interested in working with me, please drop me a line at [jayaram.kancherla@gmail.com](mailto:jayaram.kancherla@gmail.com)!

For a complete list, visit my [GitHub](https://github.com/jkanche).

---

## Visualization Tools

- **Kanaverse: Multi-modal Single-cell Analysis**

  <div style="display:flex; flex-wrap:wrap; gap:15px; margin-bottom:2px; align-items:center">
  <div style="flex:1; min-width:200px; max-width:250px">
  <img src="../About/attachments/v3_release.gif" width="100%" height="auto" alt="Kana visualization demo">
  </div>
  <div style="flex:2; min-width:300px">
  <a target="_blank" href="https://kanaverse.org/kana">Kana</a> is a web application for interactive single-cell 'omics data analysis directly in the browser. Check out <a href="https://www.biorxiv.org/content/10.1101/2022.03.02.482701v1">our manuscript</a> for details, <a href="https://joss.theoj.org/papers/10.21105/joss.05603">JOSS</a> to cite or <a target="_blank" href="https://github.com/kanaverse/kana">GitHub</a> for more information.
  </div>
  </div>

- **Genome Viewers**

  <div style="display:flex; flex-wrap:wrap; gap:15px; margin-bottom:2px; align-items:center">
  <div style="flex:1; min-width:200px; max-width:200px; order:2">
  <img src="../About/attachments/epiviz.png" width="100%" height="auto" alt="Epiviz visualization">
  </div>
  <div style="flex:2; min-width:300px; order:1">
  <ul>
  <li><a href="http://www.epiviz.org/">Epiviz</a> - Interactive visualization platform for functional genomic data. <a href="https://github.com/epiviz/epiviz">GitHub</a></li>
  <li><a href="http://www.metaviz.org/">Metaviz</a> - Interactive visualization for metagenomic data. <a href="https://github.com/epiviz/metaviz">GitHub</a></li>
  <li>Bioconductor integration through <a href="https://www.bioconductor.org/packages/release/bioc/html/epivizr.html">epivizR</a>, <a href="https://github.com/epiviz/metavizr">metavizr</a>, and <a href="https://www.bioconductor.org/packages/release/bioc/html/epivizrChart.html">epivizChart</a>.</li>
  </ul>
  </div>
  </div>

- **Genomic Visualization Libraries**
  - [epiviz.gl](https://github.com/epiviz/epiviz.gl) - High-performance genomic data visualization using WebGL and WebWorkers
    - [epiviz.scatter.gl](https://github.com/epiviz/epiviz.scatter.gl) - Performant scatter/dot plot library
    - [epiviz.heatmap.gl](https://github.com/epiviz/epiviz.heatmap.gl) - Specialized for generating heatmap-like plots
  - [unicplot](https://github.com/jkanche/unicplot) - Fun JavaScript library for generating plots using Unicode characters

---

## Analysis tools and methods

- **CellArr: Cell Arrays Backed by TileDB**
  CellArr provides a TileDB-backed store for large collections of genomic experimental data, supporting millions of cells across multiple single-cell experiment objects. 
  
  Visit the <a href="https://github.com/CellArr/">CellArr organization</a> for more information.

- **BiocPy: Bioconductor Workflows in Python**

  BiocPy brings [Bioconductor](https://www.bioconductor.org)'s core data structures to Python. These serve as essential building blocks for complex data representations to enable Bioconductor workflows in Python. 
  
  Visit the [BiocPy organization](https://github.com/BiocPy/) for more information.


- **ArtifactDB: Language-agnostic Genomic Data Store**
  ArtifactDB is a storage system for analysis-ready artifacts, providing easy access to datasets and analysis results across multiple programming frameworks like R and Python. 
  
  Visit the <a href="https://github.com/ArtifactDB/">ArtifactDB organization</a> for more details.

---

### Other

- Epiviz-related
  - [Epiviz File Server](https://github.com/epiviz/epivizFileServer) - In-situ query API and transformation of genomic data files.
  - [Epiviz Quindex](https://github.com/epiviz/EpivizQuindex) - Indexing and searching collections of BigWig/BigBed files

- Infrastructure & DevOps
  - [asynchronous-api-dask-terraform](https://github.com/jkanche/asynchronous-api-dask-terraform) - Terraform modules to orchestrate dask-based dynamic workflows in the cloud
  - [pypi-terraform](https://github.com/jkanche/pypi-terraform) - Terraform deployment script for hosting a private PyPI registry