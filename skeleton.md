---
title: outline
layout: default
---

<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [data](#data)
	- [images](#images)
	- [shapes](#shapes)
	- [graphs](#graphs)
	- [vectors](#vectors)
- [tools](#tools)
	- [store](#store)
		- [images](#images)
		- [shapes](#shapes)
		- [graphs](#graphs)
		- [vectors](#vectors)
	- [explore](#explore)
		- [images](#images)
		- [shapes](#shapes)
		- [graphs](#graphs)
		- [vectors](#vectors)
	- [analyze](#analyze)
		- [images](#images)
		- [time-series](#time-series)
			- [ophys](#ophys)
			- [ephys](#ephys)
			- [high-dimensional](#high-dimensional)
		- [shapes](#shapes)
		- [vectors](#vectors)
		- [Graphs](#graphs)
			- [Inference of Graphs](#inference-of-graphs)
			- [Vertex Clustering/Classification](#vertex-clusteringclassification)
			- [Graph Comparisons](#graph-comparisons)
			- [Graph Matching](#graph-matching)
			- [Graph Featurization](#graph-featurization)
			- [Graph Classification](#graph-classification)
			- [Joint Graph Embedding](#joint-graph-embedding)
		- [metric objects](#metric-objects)
		- [Computational Primitives](#computational-primitives)
- [applications](#applications)
	- [Nano-Cortical (Bobby paper)](#nano-cortical-bobby-paper)
	- [Nano-hippocampal (Kristen paper)](#nano-hippocampal-kristen-paper)
	- [Micro-Cortical (Eva paper)](#micro-cortical-eva-paper)
	- [Micro-molecular Cortical (Nick paper)](#micro-molecular-cortical-nick-paper)
	- [3D Synapse Distribution (ndpaper)](#3d-synapse-distribution-ndpaper)
	- [sex prediction (signal subgraph)](#sex-prediction-signal-subgraph)
	- [Joint C. Elegans Chemical + Electrical Connectomes (http://dx.doi.org/10.1080/21624054.2016.1142041)](#joint-c-elegans-chemical-electrical-connectomes-httpdxdoiorg1010802162405420161142041)
	- [Drosophila Neural Line-Behavior Map](#drosophila-neural-line-behavior-map)
	- [Micro/mammal dynamics (Hofer paper)](#micromammal-dynamics-hofer-paper)
	- [brain dependence stuff (mgc paper)](#brain-dependence-stuff-mgc-paper)
	- [supervenience paper](#supervenience-paper)
	- [optimal pipelines (discriminability paper)](#optimal-pipelines-discriminability-paper)
	- [CLARITY classification (ndpaper?)](#clarity-classification-ndpaper)
	- [individual differences (http://dx.doi.org/10.1002/hbm.23150)](#individual-differences-httpdxdoiorg101002hbm23150)
	- [AD prediction](#ad-prediction)
- [about](#about)
	- [mission & values](#mission-values)
	- [references](#references)
	- [links](#links)
	- [press](#press)
	- [people](#people)
	- [funding](#funding)
	- [review articles?](#review-articles)
- [documentation?](#documentation)

<!-- /TOC -->

# data

## images
(neurodata.io/projects / openconnecto.me)

## shapes
(na)

## graphs
(http://openconnecto.me/graph-services/download/)

## vectors
(na)


# tools

the organization of this section is really a matrix, as seen below:


|   		| images  | time-series  | shapes  | vectors  | graphs | objects |
|---		|---|---|---|---|  |  |
| store 	|   |   |   |   | | |
| explore   |   |   |   |   | | |
| analyze   |   |   |   |   | | |

## store

### images
- ndstore (http://docs.neurodata.io/ndstore/, http://arxiv.org/abs/1306.3543, https://github.com/neurodata/ndstore/)

### shapes

- ndblaze (https://github.com/neurodata/ndblaze)
- ndramondb (http://docs.neurodata.io/nddocs/ndprocess/ramon.html)


### graphs
- c4 (http://openconnecto.me/graphs/, https://github.com/neurodata/ndgrutedb)

### vectors
- nan

### objects

- ndingest (http://docs.neurodata.io/ndstore/sphinx/ingesting.html, http://docs.neurodata.io/ndstore/sphinx/console.html)
- ndio (http://docs.neurodata.io/nddocs/ndio/)
- ndlims (https://github.com/neurodata/ndlims)


## explore

### images
- ndviz (https://github.com/neurodata/ndviz/, ndviz.neurodata.io)
- ndhist (http://hx.neurodata.io, https://github.com/neurodata/histogram-explorer)
- ndtilecache (http://docs.neurodata.io/ndtilecache/api/tilecache_api.html, )

### shapes
-nan

### graphs
- graph explorer (gx.neurodata.io, https://github.com/neurodata/ExploratoryGraph, http://shiny.neurodata.io/lduan/graphX/)

### vectors
- vector explorer (vx.neurodata.io)

## analyze

(essentially, every bullet point in here has code and publication associated with it,
many do not have "websites" per se, it is not obvious that they need a website, might just need an image, header, text, and links to code, free paper, paid paper, talks, posters, etc.)

### images
- 2d hist (https://github.com/mkazhdan/DMG, http://www.cs.jhu.edu/~misha/MyPapers/ToG10.pdf)
- 3d hist (http://www.cs.jhu.edu/~misha/Code/GradientDomainFusion/Version1.0/, http://arxiv.org/pdf/1506.02079v1.pdf)
- object detection
  - VESICLE (http://vcg.seas.harvard.edu/files/pfister/files/paper081.pdf?m=1462206453, http://docs.neurodata.io/vesicle/, https://github.com/neurodata/vesicle)
  - ndparse (https://github.com/neurodata/ndparse)

	references (lacking code)
  - sweeney (http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0095753)


### time-series

#### ophys

there is only 1 up-to-date repo: (https://github.com/jovo/oopsi)

here are arxival repo's that include references
- fast-oopsi (https://github.com/jovo/fast-oopsi)
- smc-oopsi (https://github.com/jovo/smc-oopsi)
- pop-oopsi (https://github.com/jovo/pop-oopsi)

#### ephys
- spike sorting (https://github.com/jovo/spike-sorting)
- online spike sorting (https://github.com/decarlson/opass)

#### high-dimensional
- system identification (https://github.com/shachen/PLDS)

another reference (but not a tool)
- a new look (https://www.researchgate.net/publication/26712056_A_new_look_at_state-space_models_for_neural_data?ev=prf_pub)

### shapes
- non-parametric shape descriptors (https://github.com/mkazhdan/ShapeSPH)
- nonlinear registration (https://github.com/neurodata/ndreg, kutten paper)

background:
- LDDMM (http://cis.jhu.edu/software/)

### vectors

- LOL (https://github.com/neurodata/LOL)
- Randomer Forest (https://github.com/ttomita/RandomerForest)
- Density estimation (http://papers.nips.cc/paper/4944-multiscale-dictionary-learning-for-estimating-conditional-distributions)
- k-means (not available yet)

other references (lacking code)
- Matrix inversion (http://arxiv.org/abs/1312.1869)

### Graphs

#### Inference of Graphs
- Electron Microscopy (i2g.io)
- Diffusion MRI (m2g.io)

references
  - MR. CAP (https://www.researchgate.net/publication/223963176_Magnetic_Resonance_Connectome_Automated_Pipeline_An_Overview)
  - MIGRAINE (http://arxiv.org/abs/1312.4875)
- Quality/Quantity trade-off (https://www.researchgate.net/publication/51941784_Optimizing_the_quantityquality_trade-off_in_connectome_inference)


#### Vertex Clustering/Classification

- FlashX implementation of SBM


references:
- Robust (http://ieeexplore.ieee.org/xpl/articleDetails.jsp?arnumber=7159084)
- Community detection (http://arxiv.org/abs/1412.8576)
- SBM (http://arxiv.org/abs/1108.2228)

#### Graph Comparisons

- FlashX implementation of
	- Semipar
	- Nonpar

references:
- Deltacon (http://dl.acm.org/citation.cfm?doid=2824443)
- Semipar (http://arxiv.org/abs/1403.7249)
- Nonpar (http://arxiv.org/abs/1409.2344)

#### Graph Matching

- code: https://github.com/jovo/FastApproximateQAP

references:  FAQ (http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0121002),
 Divide & Conquer (http://www.sciencedirect.com/science/article/pii/S0167819115000484)
, SGM (http://arxiv.org/abs/1401.3813)
, Robust GM (http://papers.nips.cc/paper/4925-robust-multimodal-graph-matching-sparse-coding-meets-graph-matching)
, Relax at own risk (http://arxiv.org/abs/1405.3133)

#### Graph Featurization

- FlashGraph (https://usenix.org/system/files/conference/fast15/fast15-paper-zheng.pdf, and documentation in github wiki)


references
- Covariate assisted spectral clustering (http://arxiv.org/abs/1411.2158)
- Glocal statistics (http://arxiv.org/abs/1312.4318)
- HSBM (http://arxiv.org/abs/1503.02115)

#### Graph Classification

references:
- Shuffled (http://link.springer.com/article/10.1007%2Fs00357-015-9170-6)
- Signal Subgraphs (http://arxiv.org/abs/1108.1427)
- supervenience (https://www.researchgate.net/publication/45889003_Are_mental_properties_supervenient_on_brain_properties)

#### Joint Graph Embedding

references:
- Bayesian population model (http://arxiv.org/abs/1406.7851)






### metric objects
- Manifold matching (http://arxiv.org/abs/1412.4098)
- Dependence Discovery (na)
- Discriminability (na)
- Optimal Design (na)


###  Computational Primitives
(flashx.io)

- FlashEigen: Spectral Graph Embedding (http://arxiv.org/abs/1602.01421)
- FlashGraphMatrix: Sparse matrix multiply (http://arxiv.org/abs/1602.02864)
- SAFS (http://dl.acm.org/citation.cfm?id=2503225, and github repo)
- Dense matrix operations (http://arxiv.org/abs/1604.06414v1)


# applications

these are all papers, or results from papers, a subset of them have an existing corresponding website.  
i imagine for each of these making a mini website with a figure, caption, and links (to free version of paper, paid version, and code/talks/posters as appropriate)

not sure how to organize: species? scale? modality? all options? chronologically seems like maybe the best option?



- Nano-Cortical (Bobby paper)
- Nano-hippocampal (Kristen paper)
- Micro-Cortical (Eva paper)
- Micro-molecular Cortical (Nick paper)
- 3D Synapse Distribution (ndpaper)
- sex prediction (signal subgraph)
- Joint C. Elegans Chemical + Electrical Connectomes (http://dx.doi.org/10.1080/21624054.2016.1142041)
- Drosophila Neural Line-Behavior Map
- Micro/mammal dynamics (Hofer paper)
- brain dependence stuff (mgc paper)
- supervenience paper
- optimal pipelines (discriminability paper)
- CLARITY classification (ndpaper?)
- individual differences (http://dx.doi.org/10.1002/hbm.23150)
- AD prediction



# about

(all this stuff is basically here: http://neurodata.io/about)


## mission & values

## references

## links

## press

## people

## funding

## review articles?
- CCC
- cosmos to connectomes
- human connectomes

# documentation?


## How do I:

- Look at some data?
- Show some data to my labmates/colleages?
- Download some data to play with on my computer?
- Share my data?
- Manually annotate some data?
- Train my machine vision algorithm on some data?
- Run my machine vision algorithm at scale?
- Assess the performance of my classifiers?
- Infer neuroscientific meaning?
