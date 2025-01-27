---
title: "Analyzing and Mitigating Dataset Artifacts"
collection: projects
urlslug: "nlp-ut-mscs-nlp-project"
type: "Academic"
permalink: /projects/2022-12-11-nlp-ut-mscs-nlp-project
contributors: "Md Mesbahur Rahman"
contribution: "Trained ELECTRA-small model  on the SQuAD dataset. Then we generated predictions for the respective dataset of Checklist sets and Adversarial SQuAD from this model using our own scripts. Then we used Checklist and Adversarial framework to identify some of the artifacts in the model’s learning. Implemented Inoculation by fine-tuning mwthod for mitigating dataset artifacts by taking our original Electra-small model training on the training set of the SQuAD dataset and fine-tuning it on a small subset sampled from the training set of the 'Adversarial SQuAD' dataset. Then we evaluated dataset artifacts of this finetuned model using Checklist sets and Adversarial SQuAD and caompared with the original result."
date: 2022-12-11
teaserurl: 'sample-number-vs-f1.png'
reporturl: 'https://mmrahman-utexas.github.io/files/UTCS_NLP_Analyzing_and_Mitigating_Dataset_Artifacts.pdf'
excerpt: 'In NLP research arena Benchmark datasets are often used to compare the performance of different SOTA models. But a high held-out accuracy
        measure neither conveys the whole story about a model&apos;s strengths and weaknesses nor it can guarantee that the model has meaningfully solved the dataset. The model can just learn some spurious correlation in the dataset and can still achieve some high accuracy. This phenomenon is known
        as Dataset Artifacts and in this project, we tried to identify some cases of it for the ELECTRA-small (Clark et al., 2020) model on the SQuAD problem setting using Checklist and Adverserial Dataset frameworks and took attempt of mitigating some of the Dataset Artifacts using Dataset Inoculation by fine-tuning strategy.'
---

Md Mesbahur Rahman

**Description:**
In NLP research arena Benchmark datasets are often used to compare the performance of different SOTA models. But a high held-out accuracy
        measure neither conveys the whole story about a model&apos;s strengths and weaknesses nor it can guarantee that the model has meaningfully solved the dataset. The model can just learn some spurious correlation in the dataset and can still achieve some high accuracy. This phenomenon is known
        as Dataset Artifacts and in this project, we tried to identify some cases of it for the ELECTRA-small (Clark et al., 2020) model on the SQuAD problem setting using Checklist and Adverserial Dataset frameworks and took attempt of mitigating some of the Dataset Artifacts using Dataset Inoculation by fine-tuning strategy.

**My contribution:**
Trained ELECTRA-small model  on the SQuAD dataset. Then we generated predictions for the respective dataset of Checklist sets and Adversarial SQuAD from this model using our own scripts. Then we used Checklist and Adversarial framework to identify some of the artifacts in the model’s learning. Implemented Inoculation by fine-tuning mwthod for mitigating dataset artifacts by taking our original Electra-small model training on the training set of the SQuAD dataset and fine-tuning it on a small subset sampled from the training set of the &apos;Adversarial SQuAD&apos; dataset. Then we evaluated dataset artifacts of this finetuned model using Checklist sets and Adversarial SQuAD and caompared with the original result.

**Resources:** [[Technical report](https://mmrahman-utexas.github.io/files/UTCS_NLP_Analyzing_and_Mitigating_Dataset_Artifacts.pdf)]
