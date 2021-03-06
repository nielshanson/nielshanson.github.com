---
layout: default
title: Website of Niels W. Hanson
---

# Portfolio

This page highlights a selection of my software, analyses, and visualization projects.

## Software

Here I've highlighted some of the software projects I have been involved with.

<div class="row">
<div class="col-sm-4">
<h3>MetaPathways</h3>
<img src="img/mp_logo.png", alt="MetaPathways pipeline" style="width: 140px; height: 140px;">
<p>A high-performance pipeline for the systematic processing and analysis of next-generation environmental datasets, allowing the systematic preprocessing, gene prediction, annotation, and comparison of thousands of metagenomic samples. Published in <a href="doi:10.1186/1471-2105-14-202">BMC Bioinformatics</a>.</p>
<p><a class="btn btn-default" href="https://github.com/hallamlab/metapathways" role="button">View details »</a></p>
</div>
<div class="col-sm-4">
<h3>Master-worker</h3>
<img src="img/mw_logo.png", alt="MetaPathways pipeline" style="width: 140px; height: 140px;">
<p>Designed a distributed Master-worker algorithm for the scheduling of compute tasks to multilple HPC computational grids. Implemented as a feature of the <a href="https://github.com/hallamlab/metapathways2">MetaPathways v2.0</a> to process computationally intensive homology-search tasks. Published in <a href="http://ieeexplore.ieee.org/xpl/articleDetails.jsp?arnumber=6845516">IEEE CIBCB 2014</a>.</p>
<p><a class="btn btn-default" href="https://github.com/hallamlab/metapathways2" role="button">View details »</a></p>
</div>
<div class="col-sm-4">
<h3>FastLSA</h3>
<a href="http://hallam.microbiology.ubc.ca/fastLSA/"><img src="img/lsa_logo.png", alt="MetaPathways pipeline" style="width: 140px; height: 140px;"></a>
<p>FastLSA is a correlation detection method specializing the detection of partial, leading, or lagging correlation, particilar within time-series. P-values are calculated using a <a href="http://www.biomedcentral.com/1471-2164/14/S1/S3">closed-form approximation</a>, implemented in C, and paralleized with p-threads; hundreds of times faster than previous implementations. Published in <a href="http://dx.doi.org/10.1186/1471-2164-14-S1-S3">BMC Genomics</a>.</p>
<p><a class="btn btn-default" href="http://hallam.microbiology.ubc.ca/fastLSA/" role="button">View details »</a></p>
</div>
</div>

## Analytics

I've been involved in a number of analysis of unstructured datasets from beginning to end. Applying a number of statistical and machine learning models and the [ggplot2](http://ggplot2.org/) visualization framework. I am an avid user of  [Knitr](http://yihui.name/knitr/), [RMarkdown](http://rmarkdown.rstudio.com/), and [RStudio](http://www.rstudio.com/) for reproducible data analysis. 

<div class="row">
<div class="col-sm-4">
<h3>Single Cell Genomes</h3>
<a href="https://github.com/nielshanson/microfluidic_single_cells"><img src="img/single_logo.png" class="img-rounded" alt="Single cells" style="width: 140px; height: 140px;"></a>
<p>Analysis combined three taxonomic identification methods, <a href="http://ab.inf.uni-tuebingen.de/software/megan/">MEGAN</a>, <a href="http://mltreemap.org/">ML-TreeMap</a>, and <a href="http://eggnog.embl.de/version_4.0.beta/">EggNOG</a>, to compare single-cell samples from three different environments, separated <a href="http://www.pnas.org/content/109/20/7665">using microfluidic device</a>. Techniques used included Gaussing <a href="http://en.wikipedia.org/wiki/Kernel_density_estimation">Kernel Density Estimation</a> and <a href="http://en.wikipedia.org/wiki/Hierarchical_clustering">Hierarchical Clustering</a>. Results visualized in R using the <a href="http://cran.r-project.org/web/packages/lattice/index.html">lattice</a> package. Results published in <a href="http://www.pnas.org/content/109/20/7665">PNAS</a>.</p>
<p><a class="btn btn-default" href="https://github.com/nielshanson/microfluidic_single_cells" role="button">View details »</a></p>
</div>
<div class="col-sm-4">
<h3>Metabolic Pathways</h3>
<img class="img-circle" src="img/pathways_logo.png" class="img-rounded" alt="Metabolic pathways" style="width: 140px; height: 140px;">
<p>Utilized MetaPathways to re-evaluate <a href="http://hahana.soest.hawaii.edu/hot/">Hawaii Ocean-time series</a> samples, providing guidelines for the analysis of predicted metabolic pathways from environmental samples. R and ggplot2 were used to compare activity of metabolic pathways biogeochemical variables like ocean depth and salinity. Developed a novel weighted distance to cacluate taxonomic variance within pathways. Published in <a href="http://dx.doi.org/10.1186/1471-2164-15-619">BMC Genomics</a>.</p>
<p><a class="btn btn-default" href="#" role="button">View details »</a></p>
</div>
<div class="col-sm-4">
<h3>Read Mapping</h3>
<img src="img/rpkm_logo.png" class="img-rounded" alt="Read Mapping" style="width: 140px; height: 140px;">
<p>An improvement in <a href="https://github.com/hallamlab/metapathways2">MetaPathways v2.5</a> is the ability to map reads to assembled sequences to estimate abundance. In this analysis we evaluate the variance of read-mapping against simple gene counting. Fitting a linear model mapped vs gene counts in metagenomic samples from the <a href="http://www.pac.dfo-mpo.gc.ca/science/oceans/data-donnees/line-p/index-eng.html">Pacific Ocean Line-P transact</a> showed variance is being corrected for in the mapped case. Published in <a href="http://dx.doi.org/10.1093/bioinformatics/btv361">Oxford Bioinformatics</a></p>
<p><a class="btn btn-default" href="https://github.com/hallamlab/mp_2_5_supplement" role="button">View details »</a></p>
</div>
</div>

## Visualization

I also develop interactive visualizations using the [d3.js](http://d3js.org/) JavaScript library. <a href="http://bl.ocks.org/nielshanson">bl.ocks.org/nielshanson</a>

<div class="row">
    <div class="col-sm-4">
        <h3>World Map</h3>
        <a href="http://goo.gl/WVjdAv"><img src="img/world_map_logo.png" class="img-circle" alt="World Map" style="width: 140px; height: 140px;"></a>
        <p>World map of global metagenomes scaled by their sequencing abundance.</p>
        <p><a class="btn btn-default" href="http://goo.gl/WVjdAv" role="button">View details »</a></p>
    </div>
    <div class="col-sm-4">
        <h3>Sunburst Plot</h3>
        <a href="http://goo.gl/3LlXIq"><img src="img/sunburst_logo.png" class="img-circle" alt="Sunburst Plot" style="width: 140px; height: 140px;"></a>
        <p>Radial tree-map or Sunburst plot of global metagenomes classified by sampling category.</p>
        <p><a class="btn btn-default" href="http://goo.gl/3LlXIq" role="button">View details »</a></p>
    </div>
    <div class="col-sm-4">
        <h3>Bubble Tree</h3>
        <a href="http://goo.gl/2SBVsp"><img src="img/bubble_tree_logo.png" class="img-circle" alt="Bubble Tree" style="width: 140px; height: 140px;"></a>
        <p>Interative dendrogram to show taxonomy across multiple samples.</p>
        <p><a class="btn btn-default" href="http://goo.gl/2SBVsp" role="button">View details »</a></p>
    </div>
</div>
<div class="row">
    <div class="col-sm-4">
        <h3>Heatmap</h3>
        <a href="http://goo.gl/3dIurm"><img src="img/heatmap_logo.png" class="img-circle" alt="Heatmap" style="width: 140px; height: 140px;"></a>
        <p>Two-variable heatmap with calculated marginal distributions.</p>
        <p><a class="btn btn-default" href="http://goo.gl/3dIurm" role="button">View details »</a></p>
    </div>
    <div class="col-sm-4">
        <h3>Bubble Plot</h3>
        <a href="http://goo.gl/Jfslu1"><img src="img/bubble_plot_logo.png" class="img-circle" alt="Bubble Plot" style="width: 140px; height: 140px;"></a>
        <p>A two-variable sortable bubble plot with one-side marginal.</p>
        <p><a class="btn btn-default" href="http://goo.gl/Jfslu1" role="button">View details »</a></p>
    </div>
<div class="col-sm-4">
    <h3>Basic Barplot</h3>
        <a href="http://bl.ocks.org/nielshanson/a436b784293160dd4a20"><img src="img/basic_bar_logo.png", alt="Basic Barplot" class="img-circle" style="width: 140px; height: 140px;"></a>
        <p>Basic d3.js barplot to get started.</p>
        <p><a class="btn btn-default" href="http://bl.ocks.org/nielshanson/a436b784293160dd4a20" role="button">View details »</a></p>
    </div>
</div>
