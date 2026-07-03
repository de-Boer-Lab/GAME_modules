### Community List of GAME Modules

If you would like to share your Evaluator or Predictor container please follow these instructions:

1. Fork this repo
2. Edit either the Predictors/Evaluators table with your addition
3. Submit a pull request
4. We will review and merge the changes

We encourage all contributors to include the link to their code used to build their containers. This helps users understand implementation details and allows for reusable code. 

#### Predictor Modules


| Predictor | Versioned Module | GAME Schema Version | Container Download link | Description | Github Repo |
| :------------ | :--------------- | :-----: | :--------------- | :----- | :----- |
| DeepBICCN2 | DeepBICCN2_20260616-135658_CEST | 1.0 | https://zenodo.org/records/20527751 | Peak regression model for mm10 (19 cell types) | https://github.com/aertslab/GAME-DeepBICCN2-Predictor |
| ORCA | ORCA_1M_20260623-185003_EDT | 1.0 | https://huggingface.co/datasets/deBoerLab/Orca_Predictor_GAME/ | Hi-C Chromatin Conformation Predictor for H1-ESC (1M resolution model) | https://github.com/de-Boer-Lab/GAME-ORCA-predictor |
| Borzoi Human | Borzoi_Human_20260506-022639_PDT | 1.0 | https://huggingface.co/datasets/deBoerLab/Borzoi_Predictor_GAME | Multi-assay coverage and gene regulation predictor for human (hg38) | https://github.com/de-Boer-Lab/GAME-Borzoi-human-predictor |
| Enformer | Enformer_20260601-173514_EDT | 1.0 | https://huggingface.co/datasets/deBoerLab/Enformer_Predictor_GAME | Multi-assay coverage and gene regulation predictor using long-range interactions for human (hg38) and mus-musculus | https://github.com/de-Boer-Lab/GAME-Enformer-predictor |
| DREAM-RNN Human | DREAM-RNN_Human_K562_20260430-012244_PDT | 1.0 | https://huggingface.co/datasets/deBoerLab/DREAMRNN_Predictor_GAME | Promoter expression predictor (optimized RNN) for human K562 cells | https://github.com/de-Boer-Lab/GAME-DREAM-RNN-human-k562-predictor |
| CpG Predictor | CpG_Predictor_20260622-140930_EDT | 1.0 | https://huggingface.co/datasets/deBoerLab/CpG_Predictor_GAME | Counter of CpG instances across the sequences | https://github.com/de-Boer-Lab/GAME-CpG-predictor |
| MPRALegNet | MPRALegNet_20260606-135427_MSK | 1.0 | https://huggingface.co/Ni-os/MPRALegNet-container | CNN model optimized for predicting gene expression from human lentiMPRAs (massive parallel reporter assays) across human K562, HepG2, and WTC11 cell lines. | https://github.com/autosome-ru/GAME-LegNet-predictor-CAGI5-evaluator/tree/master/MPRALegNet_v2 |
| ChromBPNet | ChromBPNet_20260528-171346_EDT | 1.0 | https://huggingface.co/datasets/deBoerLab/ChromBPNet_Predictor_GAME | 45 individual chromatin accessibility models (ATAC-seq models trained for K562, GM12878, HEPG2 andIMR90; DNASE trained models for K562, GM12878, HEPG2, IMR90, H1; 5 folds for each model) | https://github.com/de-Boer-Lab/GAME-ChromBPNet-predictor |
| Evo2-7B | Evo2_7b_Predictor_20260619-145824_EDT | 1.0 | https://huggingface.co/datasets/deBoerLab/Evo2_Predictor_GAME | Evo2 7B DNA language model | https://github.com/de-Boer-Lab/GAME-Evo2-predictor |


#### Evaluator Modules


| Evaluator | Versioned Module | GAME Schema Version | Container Download link | Description | Github Repo |
| :------------ | :--------------- | :-----: | :--------------- | :----- | :----- |
| Martyn et al. (2025) Variant-EFFECTS Evaluator | martyn_variant_effects_20260610-163836_EDT | 1.0 | https://huggingface.co/datasets/deBoerLab/Martyn_VariantEffects_GAME/ | Variant effect predictions in THP-1 monocytes and Jurkat T cells. | https://github.com/de-Boer-Lab/GAME-Martyn-variant-effects-evaluator |
| Gosai et al. (2024) Synthetic CREs (51k) | gosai_2024_synthetic_mpra_20260501-062616_PDT | 1.0 | https://zenodo.org/records/21135510 | Expression predictions for 51k synthetic sequences in K562 (erythroid precursors), HepG2 (hepatocytes) and SK-N-SH (neuroblastoma) cells | https://github.com/de-Boer-Lab/GAME-Gosai-synthetic-MPRA-evaluator |
| Agarwal et al. (2025) Joint Library Dataset (56k sequences) | agarwal_2025_joint_lib_20260425-062017_PDT | 1.0 | https://zenodo.org/records/21135333 | Expression predictions for ~56k cCREs in WTC11, K562 and HepG2 | https://github.com/de-Boer-Lab/GAME-Agarwal-MPRA-joint-library-evaluator |
| Consistency Evaluator Point Request (K562/homo_sapiens) | Consistency_Point_K562_20260618-122556_EDT | 1.0 | https://huggingface.co/datasets/deBoerLab/Consistency_Point_K562_GAME | Consistency Evaluator (point) for homo_sapiens in K562 | https://github.com/de-Boer-Lab/GAME-consistency-evaluators/tree/main/Consistency_evaluator_point |
| Consistency Evaluator Track Request (K562/homo_sapiens) | Consistency_Track_K562_20260618-152654_EDT | 1.0 | https://huggingface.co/datasets/deBoerLab/Consistency_Track__GAME | Consistency Evaluator (track) for homo_sapiens in K562 | https://github.com/de-Boer-Lab/GAME-consistency-evaluators/tree/main/Consistency_evaluator_track |
| Consistency Evaluator Point Request (Astro/mus_musculus) | Consistency_Point_Astrocyte_20260625-132521_EDT | 1.0 | https://huggingface.co/datasets/deBoerLab/Consistency_Point_Astro_GAME | Consistency Evaluator for mus_musculus in Astrocytes | https://github.com/de-Boer-Lab/GAME-consistency-evaluators/tree/main/Consistency_evaluator_point_astrocyte |
| 3D Chromatin interaction Evaluator (H1-ESC, Chromosome 8) | orca_chr8_test_20260628-060104_EDT | 1.0 | https://huggingface.co/datasets/deBoerLab/Orca_Chr8_testSet_GAME | 3D Chromatin interaction Evaluator - Chromosome 8 in H1-ESC | https://github.com/de-Boer-Lab/GAME-Orca-evaluators/tree/main/Test_setChr8_Evaluator |
| 3D Chromatin interaction Evaluator (H1-ESC, Chromosome 9) | orca_chr9_test_20260628-061322_EDT | 1.0 | https://huggingface.co/datasets/deBoerLab/Orca_Chr9_testSet_GAME | 3D Chromatin interaction Evaluator - Chromosome 9 in H1-ESC | https://github.com/de-Boer-Lab/GAME-Orca-evaluators/tree/main/Test_setChr9_Evaluator |
| 3D Chromatin interaction Evaluator (H1-ESC, Chromosome 10) | orca_chr10_validation_20260628-061346_EDT | 1.0 | https://huggingface.co/datasets/deBoerLab/Orca_Chr10_validationSet_GAME | 3D Chromatin interaction Evaluator - Chromosome 10 in H1-ESC | https://github.com/de-Boer-Lab/GAME-Orca-evaluators/tree/main/Validation_setChr10_Evaluator |
| Enhancer Label Classification | DeepBICCN2_EnhancerLabel_Evaluator_20260603-133706_CEST | 1.0 | https://zenodo.org/records/20527751 | 171 validated enhancers from the BRAIN Initiative Cell Census Network across 19 mouse motor cortex cell types | https://github.com/aertslab/GAME-BICCN-Evaluator-EnhancerLabel |
| Fulco CRISPRi | fulco_crispri_20260612-172435_EDT | 1.0 | https://huggingface.co/datasets/deBoerLab/FulcoCRISPRi | Dataset to evaluate the ability of models to predict long-range regulatory effects by comparing experimental CRISPRi-mediated enhancer repression in K562 cells against random/simulated sequence shuffles across 30 unique genes. | https://github.com/de-Boer-Lab/GAME-Fulco-CRISPRi-evaluator |
| Kircher CAGI5 MPRA | Kircher_20260529-213347_MSK | 1.0 | https://huggingface.co/datasets/Ni-os/Kircher-container | ~44k SNVs from 21 regulatory elements from CAGI5 challenge | https://github.com/autosome-ru/GAME-LegNet-predictor-CAGI5-evaluator/tree/master/Kircher_2019_Evaluator_v2 |
| Enformer/Borzoi Test Set Track Readout | Enformer_Borzoi_TestSetOverlap_20260629-135521_EDT | 1.0 | https://huggingface.co/datasets/deBoerLab/Track_Evaluator_Borzoi_Enformer_TestSet | Evaluator to assess track readout model performance by comparing predicted chromatin accessibility tracks against ENCODE K562 ATAC-seq data | https://github.com/de-Boer-Lab/GAME-Borzoi-Enformer-TestSet-track-evaluator |

#### Additional Modules


| Matcher | Versioned Module | GAME Schema Version | Container Download link | Description | Github Repo |
| :------------ | :--------------- | :-----: | :--------------- | :----- | :----- |
| Matcher | Matcher_20260505-013416_PDT | 1.0 | https://huggingface.co/datasets/deBoerLab/Matcher_GAME | LLM-powered genomics ontology matcher with a recursive tournament algorithm for superior scalability and more precise, granular matching. | https://github.com/de-Boer-Lab/GAME_matcher |
| Predictor Distributor | PredictorDistributor_20260505-042012_PDT | 1.0 | https://huggingface.co/datasets/deBoerLab/PredictorDistributor_GAME | Transparent load balancer/ orchestrater module to speed up predictions by dividing request across available Predictor nodes. | https://github.com/de-Boer-Lab/GAME-predictor-distributor |

If you have any questions feel free to reach out to Ishika Luthra (ishika.luthra@ubc.ca). Please report bugs on the main GAME Github or on the individual repository pages for module specific questions/bugs.
