### Community List of GAME Modules

If you would like to share your Evaluator or Predictor container please follow these instructions:

1. Fork this repo
2. Edit either the Predictors/Evaluators table with your addition
3. Submit a pull request
4. We will review and merge the changes

We encourage all contributors to include the link to their code used to build their containers. This helps users understand implementation details and allows for reusable code. 

#### Predictor Modules


| Predictor  | Container Download link  | Description | Github Repo |
| :------------ |:---------------| :-----| :-----|
| DeepBICCN2_20260616-135658_CEST              |      https://zenodo.org/records/20527751        | Peak regression model for mm10 (19 cell types)       | https://github.com/aertslab/GAME-DeepBICCN2-Predictor |
| ORCA_1M_20260623-185003_EDT              |  https://huggingface.co/datasets/deBoerLab/Orca_Predictor_GAME/           | Hi-C Chromatin Conformation Predictor for H1-ESC (1M resolution model)       | https://github.com/de-Boer-Lab/GAME-ORCA-predictor|
| Borzoi_Human_20260506-022639_PDT              |  https://huggingface.co/datasets/deBoerLab/Borzoi_Predictor_GAME             | Multi-assay coverage and gene regulation predictor for human (hg38)       | https://github.com/de-Boer-Lab/GAME-Borzoi-human-predictor |
| Enformer_20260601-173514_EDT              |  https://huggingface.co/datasets/deBoerLab/Enformer_Predictor_GAME            | Multi-assay coverage and gene regulation predictor using long-range interactions for human (hg38) and mus-musculus       |https://github.com/de-Boer-Lab/GAME-Enformer-predictor |
| DREAM-RNN_Human_K562_20260430-012244_PDT              |  https://huggingface.co/datasets/deBoerLab/DREAMRNN_Predictor_GAME             | Promoter expression predictor (optimized RNN) for human K562 cells     | https://github.com/de-Boer-Lab/GAME-DREAM-RNN-human-k562-predictor|
| CpG_Predictor_20260622-140930_EDT              |  https://huggingface.co/datasets/deBoerLab/CpG_Predictor_GAME            | Counter of CpG instances across the sequences    | https://github.com/de-Boer-Lab/GAME-CpG-predictor|
| MPRALegNet_20260606-135427_MSK             |  https://huggingface.co/Ni-os/MPRALegNet-container             | CNN model optimized for predicting gene expression from human lentiMPRAs (massive parallel reporter assays) across human K562, HepG2, and WTC11 cell lines.    | https://github.com/autosome-ru/GAME-LegNet-predictor-CAGI5-evaluator/tree/master/MPRALegNet_v2 |
| ChromBPNet_20260528-171346_EDT             |  https://huggingface.co/datasets/deBoerLab/ChromBPNet_Predictor_GAME             | 45 individual chromatin accessibility models (ATAC-seq models trained for K562, GM12878, HEPG2 andIMR90; DNASE trained models for K562, GM12878, HEPG2, IMR90, H1; 5 folds for each model)| https://github.com/de-Boer-Lab/GAME-ChromBPNet-predictor |
| Evo2_7b_Predictor_20260619-145824_EDT             |  https://huggingface.co/datasets/deBoerLab/Evo2_Predictor_GAME             | Evo2 7B DNA language model    |https://github.com/de-Boer-Lab/GAME-Evo2-predictor |


#### Evaluator Modules


| Evaluator  | Container Download link  | Description | Github Repo |
| :------------ |:---------------| :-----|:-----|
| Martyn et al. (2025) Variant-EFFECTS Evaluator              |  https://huggingface.co/datasets/deBoerLab/Martyn_VariantEffects_GAME/            | Variant effect predictions in THP-1 monocytes and Jurkat T cells.| https://github.com/de-Boer-Lab/GAME-Martyn-variant-effects-evaluator|
| Gosai et al. (2024) Synthetic CREs (51k)              |    https://zenodo.org/records/21135510           | Expression predictions for 51k synthetic sequences in K562 (erythroid precursors), HepG2 (hepatocytes) and SK-N-SH (neuroblastoma) cells| https://github.com/de-Boer-Lab/GAME-Gosai-synthetic-MPRA-evaluator|
| Agarwal et al. (2025) Joint Library Dataset (56k sequences)               | https://zenodo.org/records/21135333              | Expression predictions for ~56k cCREs in WTC11, K562 and HepG2| https://github.com/de-Boer-Lab/GAME-Agarwal-MPRA-joint-library-evaluator|
| Consistency Evaluator Point Request (K562/homo_sapiens)               |  https://huggingface.co/datasets/deBoerLab/Consistency_Point_K562_GAME              | Consistency Evaluator (point) for homo_sapiens in K562        | https://github.com/de-Boer-Lab/GAME-consistency-evaluators/tree/main/Consistency_evaluator_point|
| Consistency Evaluator Track Request (K562/homo_sapiens)               |    https://huggingface.co/datasets/deBoerLab/Consistency_Track__GAME            | Consistency Evaluator (track) for homo_sapiens in K562        | https://github.com/de-Boer-Lab/GAME-consistency-evaluators/tree/main/Consistency_evaluator_track|
| Consistency Evaluator Point Request (Astro/mus_musculus)               |https://huggingface.co/datasets/deBoerLab/Consistency_Point_Astro_GAME                | Consistency Evaluator for mus_musculus in Astrocytes        | https://github.com/de-Boer-Lab/GAME-consistency-evaluators/tree/main/Consistency_evaluator_point_astrocyte|
| 3D Chromatin interaction Evaluator (H1-ESC, Chromosome 8)              |https://huggingface.co/datasets/deBoerLab/Orca_Chr8_testSet_GAME               | 3D Chromatin interaction Evaluator - Chromosome 8 in H1-ESC        |https://github.com/de-Boer-Lab/GAME-Orca-evaluators/tree/main/Test_setChr8_Evaluator |
| 3D Chromatin interaction Evaluator (H1-ESC, Chromosome 9)              | https://huggingface.co/datasets/deBoerLab/Orca_Chr9_testSet_GAME              | 3D Chromatin interaction Evaluator - Chromosome 9 in H1-ESC        |https://github.com/de-Boer-Lab/GAME-Orca-evaluators/tree/main/Test_setChr9_Evaluator |
| 3D Chromatin interaction Evaluator (H1-ESC, Chromosome )              |  https://huggingface.co/datasets/deBoerLab/Orca_Chr10_validationSet_GAME             | 3D Chromatin interaction Evaluator - Chromosome 10 in H1-ESC        | https://github.com/de-Boer-Lab/GAME-Orca-evaluators/tree/main/Validation_setChr10_Evaluator|
| Enhancer Label Classification             |   https://zenodo.org/records/20527751            | 171 validated enhancers from the BRAIN Initiative Cell Census Network across 19 mouse motor cortex cell types        | https://github.com/aertslab/GAME-BICCN-Evaluator-EnhancerLabel|
| Fulco CRISPRi            |  https://huggingface.co/datasets/deBoerLab/FulcoCRISPRi            | Dataset to evaluate the ability of models to predict long-range regulatory effects by comparing experimental CRISPRi-mediated enhancer repression in K562 cells against random/simulated sequence shuffles across 30 unique genes.         | https://github.com/de-Boer-Lab/GAME-Fulco-CRISPRi-evaluator|
| Kircher CAGI5 MPRA            |  https://huggingface.co/datasets/Ni-os/Kircher-container             | ~44k SNVs from 21 regulatory elements from CAGI5 challenge         |https://github.com/autosome-ru/GAME-LegNet-predictor-CAGI5-evaluator/tree/master/Kircher_2019_Evaluator_v2 |
| Enformer/Borzoi Test Set Track Readout            | https://huggingface.co/datasets/deBoerLab/Track_Evaluator_Borzoi_Enformer_TestSet             | Evaluator to assess track readout model performance by comparing predicted chromatin accessibility tracks against ENCODE K562 ATAC-seq data        | https://github.com/de-Boer-Lab/GAME-Borzoi-Enformer-TestSet-track-evaluator|

#### Additional Modules


| Matcher  | Container Download link  | Description |Github Repo |
| :------------ |:---------------| :-----|:-----|
| Matcher V1               |     https://huggingface.co/datasets/deBoerLab/Matcher_GAME         | LLM-powered genomics ontology matcher with a recursive tournament algorithm for superior scalability and more precise, granular matching.        | https://github.com/de-Boer-Lab/GAME_matcher|
| Predictor Distributor               |       https://huggingface.co/datasets/deBoerLab/PredictorDistributor_GAME     | Transparent load balancer/ orchestrater module to speed up predictions by dividing request across available Predictor nodes.     |https://github.com/de-Boer-Lab/GAME-predictor-distributor |

If you have any questions feel free to reach out to Ishika Luthra (ishika.luthra@ubc.ca). Please report bugs on the main GAME Github or on the individual repository pages for module specific questions/bugs.