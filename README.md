# Awesome sequence-to-function

A collection of models and methods that predict functional genomic readouts directly from DNA sequence.

## Sequence-to-expression models

- [AlphaGenome](https://github.com/google-deepmind/alphagenome): unified model predicting many regulatory modalities across 1 Mb of sequence at base resolution
- [Basenji](https://github.com/calico/basenji): dilated convolutional model predicting CAGE and epigenomic tracks from sequence
- [Borzoi](https://github.com/calico/borzoi): predicts RNA-seq coverage from sequence, including splicing and polyadenylation effects
- [Decima](https://github.com/Genentech/decima): single-cell resolution expression prediction from sequence
- [Enformer](https://github.com/google-deepmind/deepmind-research/tree/master/enformer): transformer model extending the receptive field for gene expression prediction
- [enformer-pytorch](https://github.com/lucidrains/enformer-pytorch): community PyTorch implementation with pretrained weights
- [EPInformer](https://github.com/pinellolab/EPInformer): gene expression prediction combining sequence, epigenomic signal, and enhancer-promoter contacts
- [ExPecto](https://github.com/FunctionLab/ExPecto): predicts tissue-specific expression and variant effects from sequence
- [Sei](https://github.com/FunctionLab/sei-framework): predicts sequence regulatory activity and assigns it to regulatory classes
- [Xpresso](https://github.com/vagarwal87/Xpresso): predicts steady-state mRNA levels from promoter sequence

## Chromatin accessibility and TF binding

- [Basset](https://github.com/davek44/Basset): learns the regulatory code of accessible DNA with convolutional networks
- [basepairmodels](https://github.com/kundajelab/basepairmodels): training and interpretation code for base-resolution profile models
- [BPNet](https://github.com/kundajelab/bpnet): base-resolution models of TF binding profiles
- [bpnet-lite](https://github.com/jmschrei/bpnet-lite): lightweight PyTorch reimplementation of BPNet and ChromBPNet
- [chromBPNet](https://github.com/kundajelab/chrombpnet): bias-factorized, base-resolution models of chromatin accessibility
- [CREsted](https://github.com/aertslab/CREsted): training and interpreting sequence models of cell-type-specific accessibility
- [DanQ](https://github.com/uci-cbcl/DanQ): hybrid convolutional and recurrent model of noncoding function
- [DeepSEA](https://www.nature.com/articles/nmeth.3547): early deep model predicting chromatin effects of noncoding variants
- [DeepSTARR](https://github.com/bernardo-de-almeida/DeepSTARR): predicts enhancer activity measured by STARR-seq
- [gkmExplain](https://github.com/kundajelab/gkmexplain): efficient importance scores for gapped k-mer SVMs
- [lsgkm](https://github.com/Dongwon-Lee/lsgkm): large-scale gapped k-mer SVM for regulatory sequence classification
- [maxATAC](https://github.com/MiraldiLab/maxATAC): TF binding prediction from ATAC-seq signal and sequence
- [scBasset](https://github.com/calico/scBasset): sequence-based modeling of single-cell chromatin accessibility
- [scPrinter](https://github.com/buenrostrolab/scPrinter): multi-scale footprinting and TF binding inference from accessibility data
- [Selene](https://github.com/FunctionLab/selene): PyTorch library for training and applying sequence models (DeepSEA successor framework)

## Splicing

- [MMSplice / MTSplice](https://github.com/gagneurlab/MMSplice_MTSplice): modular models of splicing and tissue-specific splicing effects
- [Pangolin](https://github.com/tkzeng/Pangolin): splice site usage prediction across tissues and species
- [SpliceAI](https://github.com/Illumina/SpliceAI): predicts splice junctions from primary sequence

## RNA stability, UTRs, and translation

- [APARENT](https://github.com/johli/aparent): predicts alternative polyadenylation from sequence
- [APARENT2](https://github.com/johli/aparent-resnet): residual network version of APARENT for polyadenylation variant effects
- [DeepRiPe](https://github.com/ohlerlab/DeepRiPe): predicts RNA-binding protein binding from sequence
- [Optimus 5-Prime](https://github.com/pjsample/human_5utr_modeling): 5' UTR design and variant effect prediction on translation
- [Orthrus](https://github.com/bowang-lab/Orthrus): contrastive mature RNA model for functional RNA property prediction
- [Saluki](https://github.com/calico/basenji/tree/master/manuscripts/saluki): predicts mRNA half-life from sequence
- [UTR-LM](https://github.com/a96123155/UTR-LM): language model of 5' UTRs for translation and expression prediction

## 3D genome from sequence

- [Akita](https://github.com/calico/basenji/tree/master/manuscripts/akita): predicts 3D genome architecture and Hi-C contact maps directly from DNA sequence
- [Orca](https://github.com/jzhoulab/orca): predicts multiscale 3D genome folding from sequence
- [Puffin](https://github.com/jzhoulab/puffin): interpretable model of transcription initiation from promoter sequence

## Enhancer-gene linking

- [ABC model](https://github.com/broadinstitute/ABC-Enhancer-Gene-Prediction): activity-by-contact enhancer-gene prediction
- [Cicero](https://cole-trapnell-lab.github.io/cicero-release/): cis-regulatory co-accessibility links from single-cell accessibility
- [GraphReg](https://github.com/karbalayghareh/GraphReg): chromatin-interaction-aware gene regulation model
- [scE2G](https://github.com/EngreitzLab/sc-E2G): enhancer-gene prediction from single-cell multiome data
- [SCENIC+](https://github.com/aertslab/scenicplus): single-cell multiomic inference of enhancer-driven regulatory networks
- [SCENT](https://github.com/immunogenomics/SCENT): single-cell enhancer target gene mapping
- [TargetFinder](https://github.com/shwhalen/targetfinder): predicts enhancer-promoter interactions from genomic features

## Variant effect prediction

- [AlphaMissense](https://github.com/google-deepmind/alphamissense): proteome-wide missense variant pathogenicity prediction
- [CADD](https://cadd.gs.washington.edu/): integrative deleteriousness score for variants across the genome
- [GPN](https://github.com/songlab-cal/gpn): genomic pretrained network, including GPN-MSA for variant effect scoring

## Model interpretation

- [DeepLIFT](https://github.com/kundajelab/deeplift): importance scores by backpropagating activation differences
- [fastISM](https://github.com/kundajelab/fastISM): fast in-silico mutagenesis for convolutional sequence models
- [gopher](https://github.com/shtoneyan/gopher): evaluation and interpretation of quantitative regulatory sequence models
- [SHAP](https://github.com/shap/shap): unified framework for feature attribution
- [tangermeme](https://github.com/jmschrei/tangermeme): toolkit for attribution, marginalization, and motif analysis on sequence models
- [TF-MoDISco](https://github.com/kundajelab/tfmodisco): discovers motifs from attribution scores
- [tfmodisco-lite](https://github.com/jmschrei/tfmodisco-lite): faster, leaner reimplementation of TF-MoDISco

## Regulatory sequence design

- [boda2 / Malinois](https://github.com/sjgosai/boda2): deep learning design of cell-type-specific regulatory elements
- [DDSM](https://github.com/jzhoulab/ddsm): Dirichlet diffusion score model for generating regulatory sequence
- [Ledidi](https://github.com/jmschrei/ledidi): turns trained sequence models into sequence editors
- [regLM](https://github.com/Genentech/regLM): language-model-based design of regulatory DNA

## Frameworks and tooling

- [EUGENe](https://github.com/ML4GLand/EUGENe): end-to-end framework for building and evaluating sequence models
- [EvoAug](https://github.com/p-koo/evoaug): evolution-inspired data augmentation for regulatory sequence models
- [gReLU](https://github.com/Genentech/gReLU): comprehensive framework for training, interpreting, and designing with sequence models
- [Kipoi](https://github.com/kipoi/kipoi): model zoo and standardized API for genomics models
- [ML4GLand](https://github.com/ML4GLand): collection of libraries for sequence-based machine learning in genomics

## Benchmarks and evaluation

- [BEND](https://github.com/frederikkemarin/BEND): benchmark of DNA language models on realistic genomic tasks
- [CAGI](https://genomeinterpretation.org/): community assessment of genome interpretation methods
- [DART-Eval](https://github.com/kundajelab/DART-Eval): benchmark of DNA models on regulatory sequence tasks
- [Genomic Benchmarks](https://github.com/ML-Bioinfo-CEITEC/genomic_benchmarks): datasets and baselines for genomic sequence classification

## Reviews

- [Deep learning: new computational modelling techniques for genomics](https://doi.org/10.1038/s41576-019-0122-6)
- [Obtaining genetics insights from deep learning via explainable artificial intelligence](https://doi.org/10.1038/s41576-022-00532-2)
- [Current sequence-based models capture gene expression determinants in promoters but mostly ignore distal enhancers](https://doi.org/10.1186/s13059-023-02899-9)
- [Leveraging genomic deep learning models for non-coding variant effect prediction](https://doi.org/10.48550/arxiv.2411.11158)
- [Advancing regulatory variant effect prediction with AlphaGenome](https://doi.org/10.1038/s41586-025-10014-0)
- [AlphaGenome, a Swiss-army knife for exploring non-coding DNA](https://doi.org/10.1016/j.tig.2025.11.007)
