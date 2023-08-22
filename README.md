# The Isoform-centric Microglia Genomic Atlas (isoMiGA) Project

Jack Humphrey, Erica Brophy, Towfique Raj lab 2023

---



![overview](https://github.com/RajLabMSSM/isoMiGA/raw/main/isomiga_schematic.png)


The isoMiGA project combines long-read and short-read RNA-seq from microglia cells purified from post mortem human brains.

Using an atlas of novel isoforms, we show that microglia use a range of isoforms in response to stimulation and can differentiate microglia from different brain regions.

We then map genetic associations with isoform usage and other types of RNA splicing, observing that multiple GWAS variants act through novel microglia isoforms in Alzheimer's and Parkinson's disease.

---

## Manuscript 

In progress

## Pipelines

Short-read RNA-seq processing:  https://github.com/CommonMindConsortium/RAPiD-nf

Long-read RNA-seq processing: https://github.com/RajLabMSSM/isoseq-pipeline  

QTL mapping and meta-analysis: https://github.com/RajLabMSSM/mmQTL-pipeline

Genotype quality control: https://github.com/RajLabMSSM/Genotype_QC_Pipeline_2.0 


## Long-read RNA-seq isoforms

[script](https://github.com/RajLabMSSM/isoMiGA/blob/main/scripts/describe_stringtie.Rmd)
|
[html](https://RajLabMSSM.github.io/isoMiGA/html/)

## Genotype QC

[script](https://github.com/RajLabMSSM/isoMiGA/blob/main/scripts/genotype_qc.Rmd)
|
[html](https://RajLabMSSM.github.io/isoMiGA/html/)

## Mass spectrometry

[script](https://github.com/RajLabMSSM/isoMiGA/blob/main/scripts/explore_proteomics.Rmd)
|
[html](https://RajLabMSSM.github.io/isoMiGA/html/)

## Differential analyses

### Stimulation response

Differential gene expression

[script](https://github.com/RajLabMSSM/isoMiGA/blob/main/scripts/region_deg.Rmd)
|
[html](https://RajLabMSSM.github.io/isoMiGA/html/)

Differential transcript usage

[script](https://github.com/RajLabMSSM/isoMiGA/blob/main/scripts/region_dtu.Rmd)
|
[html](https://RajLabMSSM.github.io/isoMiGA/html/)

### Region specificity

Differential gene expression

[script](https://github.com/RajLabMSSM/isoMiGA/blob/main/scripts/stimulation_deg.Rmd)
|
[html](https://RajLabMSSM.github.io/isoMiGA/html/)

Differential transcript usage

[script](https://github.com/RajLabMSSM/isoMiGA/blob/main/scripts/stimulation_dtu.Rmd)
|
[html](https://RajLabMSSM.github.io/isoMiGA/html/)


## MESC

[script](https://github.com/RajLabMSSM/isoMiGA/blob/main/scripts/MESC.Rmd)
|
[html](https://RajLabMSSM.github.io/isoMiGA/html/)

## QTL Mapping

[script](https://github.com/RajLabMSSM/isoMiGA/blob/main/scripts/explore_mmQTL_results.Rmd)
|
[html](https://RajLabMSSM.github.io/isoMiGA/html/)

## GWAS Colocalization

[script](https://github.com/RajLabMSSM/isoMiGA/blob/main/scripts/COLOC.Rmd)
|
[html](https://RajLabMSSM.github.io/isoMiGA/html/)

## Visualizing QTLs

[script](https://github.com/RajLabMSSM/isoMiGA/blob/main/scripts/QTL_schematic_plots.Rmd)
|
[html](https://RajLabMSSM.github.io/isoMiGA/html/)


