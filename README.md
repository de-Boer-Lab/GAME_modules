### Community List of GAME Modules

If you would like to share your Evaluator or Predictor container please follow these instructions:

1. Fork this repo
2. Edit either the Predictors/Evaluators table with your addition
3. Submit a pull request
4. We will review and merge the changes

We encourage all contributors to include the code they used to build their containers on their independent Github repositories. This helps users understand implementation details and allows for reusable code. 

#### Predictor Modules


| Predictor  | Container Download link  | Description |
| :------------ |:---------------| :-----|
| DeepBICCN2 (no matcher)              |  https://zenodo.org/records/17804107            | Peak regression model for mm10 (19 cell types)       |
| ORCA - H1-ESC (1M)              |  https://zenodo.org/records/18182683            | Hi-C Chromatin Conformation Predictor for H1-ESC (1M resolution model)       |
| Borzoi Human              |  https://zenodo.org/records/18182688             | Multi-assay coverage and gene regulation predictor for human (hg38)       |
| Enformer Human              |  https://zenodo.org/records/18182763             | Multi-assay coverage and gene regulation predictor using long-range interactions for human (hg38)       |
| DREAM-RNN Human K562              |  https://zenodo.org/records/18178626             | Promoter expression predictor (optimized RNN) for human K562 cells     |
| ChromBPNet              |  https://zenodo.org/records/18182691             | 45 individual chromatin accessibility models (ATAC-seq models trained for K562, GM12878, HEPG2 andIMR90; DNASE trained models for K562, GM12878, HEPG2, IMR90, H1; 5 folds for each model)     |
| CpG Predictor              |  https://zenodo.org/records/18182725            | Counter of CpG instances across the sequences    |
| MPRA LegNet             |  https://huggingface.co/Ni-os/MPRALegNet-container             | CNN model optimized for predicting gene expression from human lentiMPRAs (massive parallel reporter assays) across human K562, HepG2, and WTC11 cell lines.    |


#### Evaluator Modules


| Evaluator  | Container Download link  | Description |
| :------------ |:---------------| :-----|
| Martyn et al. (2025) Variant-EFFECTS Evaluator              | https://zenodo.org/records/18182385              | Variant effect predictions in THP-1 monocytes and Jurkat T cells.|
| Gosai et al. (2024) Synthetic CREs (51k)              | https://zenodo.org/records/18203018              | Expression predictions for 51k synthetic sequences in K562 (erythroid precursors), HepG2 (hepatocytes) and SK-N-SH (neuroblastoma) cells|
| Agarwal et al. (2025) Joint Library Dataset (56k sequences)               | https://zenodo.org/records/18182021              | Expression predictions for ~56k cCREs in WTC11, K562 and HepG2|
| Consistency Evaluator Point Request (K562/homo_sapiens)               | https://zenodo.org/records/18182295               | Consistency Evaluator (point) for homo_sapiens in K562        |
| Consistency Evaluator Track Request (K562/homo_sapiens)               | https://zenodo.org/records/18182295               | Consistency Evaluator (track) for homo_sapiens in K562        |
| Consistency Evaluator Point Request (Astro/mus_musculus)               | https://zenodo.org/records/18182295               | Consistency Evaluator for mus_musculus in Astrocytes        |
| 3D Chromatin interaction Evaluator (H1-ESC, Chromosome 8)              | https://huggingface.co/datasets/Iluthra/3D_Chromatin_interaction_Evaluator_GAMEAPI_H1_ESC_Chromosome_8/tree/v1               | 3D Chromatin interaction Evaluator - Chromosome 8 in H1-ESC        |
| 3D Chromatin interaction Evaluator (H1-ESC, Chromosome 9)              | https://huggingface.co/datasets/Iluthra/3D_Chromatin_interaction_Evaluator_GAMEAPI_H1_ESC_Chromosome_9/tree/v1               | 3D Chromatin interaction Evaluator - Chromosome 9 in H1-ESC        |
| 3D Chromatin interaction Evaluator (H1-ESC, Chromosome )              | https://huggingface.co/datasets/Iluthra/3D_Chromatin_interaction_Evaluator_GAMEAPI_H1_ESC_Chromosome_10/tree/v1               | 3D Chromatin interaction Evaluator - Chromosome 10 in H1-ESC        |
| Enhancer Label Classification             | https://zenodo.org/records/17802620               | 171 validated enhancers from the BRAIN Initiative Cell Census Network across 19 mouse motor cortex cell types        |
| Fulco CRISPRi            | https://zenodo.org/records/18189526              | Dataset to evaluate the ability of models to predict long-range regulatory effects by comparing experimental CRISPRi-mediated enhancer repression in K562 cells against random/simulated sequence shuffles across 30 unique genes.         |
| Kircher CAGI5 MPRA            | https://huggingface.co/datasets/Ni-os/Kircher-container              | ~44k SNVs from 21 regulatory elements from CAGI5 challenge         |
| Enformer/Borzoi Test Set Track Readout            | https://zenodo.org/records/18190139              | Evaluator to assess track readout model performance by comparing predicted chromatin accessibility tracks against ENCODE K562 ATAC-seq data        |

#### Additional Modules


| Matcher  | Container Download link  | Description |
| :------------ |:---------------| :-----|
| Matcher V1               | https://zenodo.org/records/18203297             | LLM-powered genomics ontology matcher with a recursive tournament algorithm for superior scalability and more precise, granular matching.        |
| Predictor Distributor               | https://zenodo.org/records/18203313            | Transparent load balancer/ orchestrater module to speed up predictions by dividing request across available Predictor nodes.     |

If you have any questions feel free to reach out to Ishika Luthra (ishika.luthra@ubc.ca). Please report bugs on the main GAME Github or on the individual repository pages for module specific questions/bugs.