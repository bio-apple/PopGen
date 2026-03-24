## 1.变异位点注释工具

- **[Illumina Connected Annotations](https://illumina.github.io/NirvanaDocumentation/)**

 **PrimateAI-3D, SpliceAI,PromoterAI**

- **[ANNOVAR](https://annovar.openbioinformatics.org/en/latest/)**

- **[SnpEff & SnpSift](https://pcingola.github.io/SnpEff/)**

- **[Ensembl Variant Effect Predictor (VEP)](https://github.com/Ensembl/ensembl-vep)**

## 2.算法分类

| No. | Algorithm | Description | VIPs |
| :--- | :--- | :--- | :--- |
| 1 | Naive Bayes | A probabilistic graphical model that represents a set of variables and their conditional dependencies | PolyPhen-2, PolyPhen-HCM, CanPredict, SPANR |
| 2 | Support vector machines | A supervised learning model that analyzes data for classification and regression analysis | CADD, PhD-SNP, MetaSVM |
| 3 | Random forest | An ensemble learning method that operates by constructing multiple decision trees | VEST, MutPred, SQUIRLS, GWAVA, VIPPID, PdmIRD, REVEL, parSMURF |
| 4 | Gradient boosting machines | An ML technique for regression and classification problems that builds a model in a stage-wise fashion. | MAGPIE, CAPICE, INDELpred, M-CAP, PON-P3, CardioBoost |
| 5 | Neural networks | A set of algorithms modeled after the human brain, designed to recognize patterns | DANN, PrimateAI, DeepSEA, Basenji, PromoterAI, SpliceAI, MMSplice, AIVAR |
| 6 | Transformer | A DL model that uses self-attention mechanisms to process sequential data, capturing long-range dependencies and relationships in the data. | AlphaMissense, VariPred, Enformer, AlphaGenome, EpiGePT, MutFormer, GeneT, SpTransformer |

## 3.代表性的变异位点预测算法

| No. | Methodological paradigm | VIPs | Variant type(s) | Reported performance (as published) |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Rule-based | SIFT | Missense (amino acid-altering) variants | ROC-AUC: 0.80–0.82 |
| | | PolyPhen | Missense (amino acid-altering) variants | ROC-AUC: ≈0.83 |
| 2 | Statistical | MutationAssessor | Missense (amino acid-altering) variants | ROC-AUC: ≈0.86 |
| | | FATHMM | Coding and non-coding variants | Accuracy: ≈0.86 |
| 3 | Machine learning | CADD | Coding and non-coding variants | ROC-AUC: 0.90–0.93 |
| | | REVEL | Missense (amino acid-altering) variants | ROC-AUC: 0.90–0.91 |
| 4 | Deep learning | SpliceAI | Splicing-altering variants | PR-AUC: ≈0.90 |
| | | DeepSEA | Non-coding regulatory variants | ROC-AUC: ≈0.96 |
| 5 | Transformer/pLM | AlphaMissense | Missense (amino acid-altering) variants | ROC-AUC: ≈0.94 |
| | | MutFormer | Missense (amino acid-altering) variants | ROC-AUC: 0.92–0.97 |

## 4.一些人群队列所用的变异预测算法

* **Select：REVEL, MTR, and CADD**

UK Biobank Whole-Genome Sequencing Consortium, Li S, Carss K J, et al. Whole-genome sequencing of half-a-million UK Biobank participants[J]. medRxiv, 2023: 2023.12. 06.23299426.

* **Select：LRT, SIFT, MutationTaster, and Polyphen2**

Kawai Y, Watanabe Y, Omae Y, et al. Exploring the genetic diversity of the Japanese Population: Insights from a Large-Scale Whole Genome Sequencing Analysis[J]. bioRxiv, 2023: 2023.01. 23.525133. 

* **Select： REVEL, PrimateAI and SpliceAI**

Chan S H, Bylstra Y, Teo J X, et al. Analysis of clinically relevant variants from ancestrally diverse Asian genomes[J]. Nature Communications, 2022, 13(1): 6694.

* **Select： SIFT, PolyPhen-2, MutationTaster**

Cong P K, Bai W Y, Li J C, et al. Genomic analyses of 10,376 individuals in the Westlake BioBank for Chinese (WBBC) pilot project[J]. Nature Communications, 2022, 13(1): 2939. 






