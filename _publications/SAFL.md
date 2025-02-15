---
title: "SAFL: Structure-Aware Personalized Federated Learning via Client-Specific Clustering and SCSI-Guided Model Pruning"
collection: publications
permalink: /publication/2025-2-15-SAFL
excerpt: 'My paper will be published soon'
date: 2009-10-01
venue: 'Journal 1'
paperurl: 'https://arxiv.org/abs/2501.18659'
citation: 'Nan Li, Xiaolu Wang, Xiao Du, Puyu Cai, Ting Wang.'
---
Federated Learning (FL) enables clients to collaboratively train machine learning models without sharing local data, preserving privacy in diverse environments. While traditional FL approaches preserve privacy, they often struggle with high computational and communication overhead. To address these issues, model pruning is introduced as a strategy to streamline computations. However, existing pruning methods, when applied solely based on local data, often produce sub-models that inadequately reflect clients' specific tasks due to data insufficiency. To overcome these challenges, this paper introduces SAFL (Structure-Aware Federated Learning), a novel framework that enhances personalized federated learning through client-specific clustering and Similar Client Structure Information (SCSI)-guided model pruning. SAFL employs a two-stage process: initially, it groups clients based on data similarities and uses aggregated pruning criteria to guide the pruning process, facilitating the identification of optimal sub-models. Subsequently, clients train these pruned models and engage in server-based aggregation, ensuring tailored and efficient models for each client. This method significantly reduces computational overhead while improving inference accuracy. Extensive experiments demonstrate that SAFL markedly diminishes model size and improves performance, making it highly effective in federated environments characterized by heterogeneous data.

[Download paper here](https://arxiv.org/abs/2501.18659)

