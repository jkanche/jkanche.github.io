---
title: "Home"
enableToc: "false"
---

I am currently a **Senior Research Software Engineer** at Genentech. I develop interactive and integrative visual analysis and exploratory tools for biomedical datasets (epigenomic, metagenomics & single-cell). My interests include bioinformatics, data visualization & web development.

Find me on [bsky](https://bsky.app/profile/did:plc:3pz77k4ljmluuqcvz744jx2y), [twitter](http://twitter.com/jayaram), [scholar](http://scholar.google.com/citations?user=CFOvaRwAAAAJ) or send a [message](mailto:jayaram.kancherla@gmail.com).

## Recent Software

For a complete list, visit the [Projects](./About/Projects) section or my [GitHub](https://github.com/jkanche).

<style>
  .projects-container {
    display: flex;
    /* flex-wrap: wrap; */
    gap: 7px;
    justify-content: space-between;
    margin: 5px 0;
  }
  
  .project-card {
    flex: 1;
    min-width: calc(33% - 15px);
    background-color: #ffffff;
    border-radius: 8px;
    border: 1px solid #3165a5;
    overflow: hidden;
    transition: transform 0.3s ease;
  }

  .project-image {
    width: 100%;
    height: 200px;
    object-fit: cover !important;
    border-bottom: 1px solid #e0e0e0;
  }
  
  .project-content {
    padding: 24px;
  }
  
  .project-title {
    font-size: 20px;
    font-weight: 600;
    color: #3165a5;
    margin-bottom: 12px;
  }
  
  .project-description {
    color: #555;
    margin-bottom: 5px;
  }
  
  @media (max-width: 768px) {
    .project-card {
      min-width: 100%;
    }
  }
</style>

<div class="projects-container">
  <div class="project-card">
    <img src="./About/attachments/v3_release.png" alt="Kanaverse" class="project-image" />
    <div class="project-content">
      <a class="project-title" target="_blank" href="https://github.com/kanaverse">Kanaverse</a>
      <p class="project-description">Multi-modal single-cell analysis and exploration tool with interactive visualizations.</p>
    </div>
  </div>
  
  <div class="project-card">
    <img src="./About/attachments/biocpy.png" alt="BiocPy" class="project-image" />
    <div class="project-content">
      <a class="project-title" target="_blank" href="https://github.com/biocpy">BiocPy</a>
      <p class="project-description">Facilitating Bioconductor workflows in Python.</p>
    </div>
  </div>

  <div class="project-card">
    <img src="./About/attachments/cellarr.png" alt="CellArray" class="project-image" />
    <div class="project-content">
      <a class="project-title" target="_blank" href="https://github.com/cellarr">Cell Arrays</a>
      <p class="project-description">TileDB backed store and dataloaders for genomics.</p>
    </div>
  </div>
</div>
