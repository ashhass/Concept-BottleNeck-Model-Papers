# Concept-BottleNeck-Model-Papers

This repository contains all papers on concept bottleneck models organized by year of publishing.


# 2023
[Interactive Concept Bottleneck Models](https://ojs.aaai.org/index.php/AAAI/article/view/25736)

[A closer look at the intervention procedure of concept bottleneck models](https://arxiv.org/pdf/2302.14260.pdf)


# 2022
[Post-hoc Concept Bottleneck Models](https://arxiv.org/pdf/2205.15480.pdf)

[Addressing Leakage in Concept Bottleneck Models](https://proceedings.neurips.cc/paper_files/paper/2022/file/944ecf65a46feb578a43abfd5cddd960-Paper-Conference.pdf)


# 2021
[Do Concept Bottleneck Models learn as intended](https://arxiv.org/abs/2105.04289)

Investigates which regions in the input space CBMs use to make predictions. Claims that pretrained concepts do not correspond to anything semantically meaningful in the input space suggesting that CBMs might be using confounding information to make concept label predictions.


# 2020
[Concept Bottleneck Model](https://proceedings.mlr.press/v119/koh20a.html)

Description:  Introduces a framework to extract concepts from feature vectors that are later used to predict target labels.
Three methods:
  1. Independent: Train to predict concept c from input x independently from predicting label y from concept c.
  2. Sequential: Train to predict concept c first then predict the label from predicted concepts c.
  3. Joint: Simultaneously predicts concept c and target label y using a joint loss function.

[Now You See Me (CME): Concept-based Model Extraction](https://arxiv.org/pdf/2010.13233.pdf)

[On Completeness-aware Concept-Based Explanations in Deep Neural Networks](https://proceedings.neurips.cc/paper_files/paper/2020/file/ecb287ff763c169694f682af52c1f309-Paper.pdf)

[DEBIASING CONCEPT-BASED EXPLANATIONS WITH CAUSAL ANALYSIS
](https://arxiv.org/pdf/2007.11500.pdf)

Introduces a causal prior graph which attempts to model unobserved confounding information the model might be using to make its predictions. Uses a two stage regression technique to remove the detected confounding information. 

[Wilds: A Benchmark of in-the-Wild Distribution Shifts
](https://www.researchgate.net/profile/Sara-Beery/publication/347125548_WILDS_A_Benchmark_of_in-the-Wild_Distribution_Shifts/links/60b7edf44585159354cae05a/WILDS-A-Benchmark-of-in-the-Wild-Distribution-Shifts.pdf)

# 2019
