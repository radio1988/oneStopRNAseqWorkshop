# Comprehensive RNAseq Analysis with *oneStopRNAseq*

# Instructors and contact information
- Rui Li: rui.li@umassmed.edu
- Kai Hu: kai.hu@umassmed.ed
- Haibo Liu: haibol2017@gmail.com
- Lihua Julie Zhu: julie.zhu@umassmed.edu

# Workshop Description

RNAseq is a popular technique to generate insight into the transcriptome. Generally, the anlaysis of RNAseq involved many steps and takes time. Here we present a *oneStopRNAseq* pipeline that does comprehensive RNAseq analysis, including QC, alignment, expression quantification, differential expression, alternative splicing, differential exon usage, alternative polyadenylation, allele-specific expression analysis, and [GSEA][11]. Additionally, it touches scRNAseq analysis. It runs on local computer, HPC, and AWS efficiently. Bioinformaticians can use the command line interface. Biologists can use the web interface.

During this workshop, we will give an overview of popular RNAseq analysis, and the advantages and disadvantages of selected popular tools, the reason we pre-built a comprehensive analysis pipeline with selected tools, then demostrate running *oneStopRNAseq* in both interfaces.

## Pre-requisites
* Basic knowledge of RNAseq technology and popular analysis concepts
* If you have coding experience
    * Basic knowledge of R, Bash, Anaconda 
    * A computer that runs on Unix-like system and have Anaconda installed
* If you don't have coding experience
    * A computer with internet connection

## Workshop Participation

* An overview of popular RNAseq analysis methods and tools and the rational we seleted tools in our pre-build pipeline
* Hands-on workshop learning how to do RNAseq analysis with the command line interface and web interface of *oneStopRNAseq*

## _R_ / _Bioconductor_ packages used

* [DESeq2][7] 
* [edgeR][15]
* [DEXSeq][14]
* [InPAS][18]
* [EnhancedVolcano][9]
* [ComplexHeatmap][10]

## Time outline


| Activity                     | Time |
|------------------------------|------|
| Overview of analysis methods and *oneStopRNAseq* | 20m|
| Demo of commandline interface and web interface  | 10min |
| Hands-on workshop | 25m |
| Q & A| 5 min|

# Workshop goals and objectives

## Learning goals

* Identify popular tools in comprehensive RNAseq analysis
* Understand advantages and disadvantages of popular tools
* Identify some common caveats in RNAseq analysis
* Apply an integrated RNAseq analysis with *oneStopRNAseq*

## Learning objectives

* Analyze an example RNAseq dataset with *oneStopRNAseq*
* Knowledge about:
    * aligners ([HISAT2][1], [STAR][2]), and pseudo-aligners ([Kallisto][3], [Salmon][4])
    * expression quantification (count based and EM based)
    * normalization methods (e.g. [TPM][6])
    * differential expression analysis ([DESeq2][7], [edgeR][15])
    * alternative splicing analysis ([DEXSeq][14], [rMATS][16])
    * alternative polyadenylation analysis ([InPAS][18])
    * allele-specific expression analysis
    
* Create: 
    * annotated expression table in excel format
    * differential expression results in excel format
    * alternative splicing analysis results
    * differential exon usage analysis results
    * allele-specific expression analysis results
    * volcano-plot labeled with marker genes
    * heatmap of differentially expressed genes
    * GO, KEGG enrichment results
    * GSEA results
    
    
* Additionally
    * knowledge about basic scRNAseq analysis
    * create files to be viewed and analyzed by Loupe Cell Browser from 10x genomics scRNAseq dataset


[1]: http://daehwankimlab.github.io/hisat2/ "HISAT2"
[2]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3530905/ "STAR"
[3]: https://www.nature.com/articles/nbt.3519 "Kallisto"
[4]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5600148/ "Salmon"
[5]: https://www.gencodegenes.org/ "GENCODE"
[6]: https://www.rna-seqblog.com/rpkm-fpkm-and-tpm-clearly-explained/ "TPM"
[7]: https://bioconductor.org/packages/release/bioc/html/DESeq2.html "DESeq2"
[8]: https://bioconductor.org/packages/release/bioc/html/ChIPpeakAnno.html "ChIPpeakAnno"
[9]: https://bioconductor.org/packages/release/bioc/html/EnhancedVolcano.html "EnhancedVolcano"
[10]: https://bioconductor.org/packages/release/bioc/html/ComplexHeatmap.html "ComplexHeatmap"
[11]: https://www.gsea-msigdb.org/gsea/index.jsp "GSEA"
[12]: http://www.pantherdb.org "PANTHER"
[13]: https://www.ncbi.nlm.nih.gov/pubmed/24227677 "featureCounts"
[14]: https://bioconductor.org/packages/release/bioc/html/DEXSeq.html "DEXSeq"
[15]: https://bioconductor.org/packages/release/bioc/html/edgeR.html "edgeR"
[16]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4280593/ "rMATS"
[17]: https://satijalab.org/seurat/ "SEURAT"
[18]: https://bioconductor.org/packages/release/bioc/html/InPAS.html "InPAS"
