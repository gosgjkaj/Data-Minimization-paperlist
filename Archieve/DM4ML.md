# Data Minimization for Machine Learning

## Survey
- [A Comprehensive Survey of Dataset Distillation](#1)
- [Data Distillation: A Survey](#2)

### <span id="1">A Comprehensive Survey of Dataset Distillation</span>
[link to this paper](https://arxiv.org/abs/2301.05603)

**Authors:** Shiye Lei, Dacheng Tao

Deep learning technology has developed unprecedentedly in the last decade and has become the primary choice in many application domains. This progress is mainly attributed to a systematic collaboration in which rapidly growing computing resources encourage advanced algorithms to deal with massive data. However, it has gradually become challenging to handle the unlimited growth of data with limited computing power. To this end, diverse approaches are proposed to improve data processing efficiency. Dataset distillation, a dataset reduction method, addresses this problem by synthesizing a small typical dataset from substantial data and has attracted much attention from the deep learning community. Existing dataset distillation methods can be taxonomized into meta-learning and data matching frameworks according to whether they explicitly mimic the performance of target data. Although dataset distillation has shown surprising performance in compressing datasets, there are still several limitations such as distilling high-resolution data or data with complex label spaces. This paper provides a holistic understanding of dataset distillation from multiple aspects, including distillation frameworks and algorithms, factorized dataset distillation, performance comparison, and applications. Finally, we discuss challenges and promising directions to further promote future studies on dataset distillation.

### <span id="2">Data Distillation: A Survey</span>
[link to this paper](https://arxiv.org/abs/2301.04272)

**Authors:** Noveen Sachdeva, Julian McAuley

The popularity of deep learning has led to the curation of a vast number of massive and multifarious datasets. Despite having close-to-human performance on individual tasks, training parameter-hungry models on large datasets poses multi-faceted problems such as (a) high model-training time; (b) slow research iteration; and (c) poor eco-sustainability. As an alternative, data distillation approaches aim to synthesize terse data summaries, which can serve as effective drop-in replacements of the original dataset for scenarios like model training, inference, architecture search, etc. In this survey, we present a formal framework for data distillation, along with providing a detailed taxonomy of existing approaches. Additionally, we cover data distillation approaches for different data modalities, namely images, graphs, and user-item interactions (recommender systems), while also identifying current challenges and future research directions.

---

## General paper
<!-- no toc -->
- [Dataset Regeneration for Sequential Recommendation](#3)
- [Large-scale Dataset Pruning with Dynamic Uncertainty](#4)
- [Entropy Law The Story Behind Data Compression and LLM Performance](#5)
- [RecRanker Instruction Tuning Large Language Model as Ranker for Topk Recommendation](#6)
- [The Data Minimization Principle in Machine Learning](#7)
- [Deep Learning on a Data Diet Finding Important Examples Early in Training](#8)
- [Less Is Better Unweighted Data Subsampling via Influence Function](#9)
- [InfoBatch Lossless Training Speed Up by Unbiased Dynamic Data Pruning](#10)
- [Coverage-centric Coreset Selection for High Pruning Rates](#11)
- [Selection via Proxy Efficient Data Selection for Deep Learning](#12)
- [Dataset Condensation via Efficient SyntheticData Parameterization](#13)
- [Dataset Condensation with Gradient Matching](#14)

### <span id="3">Dataset Regeneration for Sequential Recommendation</span>
[link to this paper](https://arxiv.org/abs/2405.17795)

**Authors:** Mingjia Yin, Hao Wang, Wei Guo, Yong Liu, Suojuan Zhang, Sirui Zhao, Defu Lian, Enhong Chen

The sequential recommender (SR) system is a crucial component of modern recommender systems, as it aims to capture the evolving preferences of users. Significant efforts have been made to enhance the capabilities of SR systems. These methods typically follow the model-centric paradigm, which involves developing effective models based on fixed datasets. However, this approach often overlooks potential quality issues and flaws inherent in the data. Driven by the potential of data-centric AI, we propose a novel data-centric paradigm for developing an ideal training dataset using a model-agnostic dataset regeneration framework called DR4SR. This framework enables the regeneration of a dataset with exceptional cross-architecture generalizability. Additionally, we introduce the DR4SR+ framework, which incorporates a model-aware dataset personalizer to tailor the regenerated dataset specifically for a target model. To demonstrate the effectiveness of the data-centric paradigm, we integrate our framework with various model-centric methods and observe significant performance improvements across four widely adopted datasets. Furthermore, we conduct in-depth analyses to explore the potential of the data-centric paradigm and provide valuable insights. The code can be found at https://anonymous.4open.science/r/KDD2024-86EA

### <span id="4">Large-scale Dataset Pruning with Dynamic Uncertainty</span>
[link to this paper](https://arxiv.org/abs/2306.05175)

**Authors:** Muyang He, Shuo Yang, Tiejun Huang, Bo Zhao

The state of the art of many learning tasks, e.g., image classification, is advanced by collecting larger datasets and then training larger models on them. As the outcome, the increasing computational cost is becoming unaffordable. In this paper, we investigate how to prune the large-scale datasets, and thus produce an informative subset for training sophisticated deep models with negligible performance drop. We propose a simple yet effective dataset pruning method by exploring both the prediction uncertainty and training dynamics. We study dataset pruning by measuring the variation of predictions during the whole training process on large-scale datasets, i.e., ImageNet-1K and ImageNet-21K, and advanced models, i.e., Swin Transformer and ConvNeXt. Extensive experimental results indicate that our method outperforms the state of the art and achieves 25% lossless pruning ratio on both ImageNet-1K and ImageNet-21K. The code and pruned datasets are available at [this https URL](https://github.com/BAAI-DCAI/Dataset-Pruning).

### <span id="5">Entropy Law: The Story Behind Data Compression and LLM Performance</span>
[link to this paper](https://arxiv.org/abs/2407.06645)

**Authors:** Mingjia Yin, Chuhan Wu, Yufei Wang, Hao Wang, Wei Guo, Yasheng Wang, Yong Liu, Ruiming Tang, Defu Lian, Enhong Chen

Data is the cornerstone of large language models (LLMs), but not all data is useful for model learning. Carefully selected data can better elicit the capabilities of LLMs with much less computational overhead. Most methods concentrate on evaluating the quality of individual samples in data selection, while the combinatorial effects among samples are neglected. Even if each sample is of perfect quality, their combinations may be suboptimal in teaching LLMs due to their intrinsic homogeneity or contradiction. In this paper, we aim to uncover the underlying relationships between LLM performance and data selection. Inspired by the information compression nature of LLMs, we uncover an “entropy law” that connects LLM performance with data compression ratio and first-epoch training loss, which reflect the information redundancy of a dataset and the mastery of inherent knowledge encoded in this dataset, respectively. Through both theoretical deduction and empirical evaluation, we find that model performance is negatively correlated to the compression ratio of training data, which usually yields a lower training loss. Based on the findings of the entropy law, we propose a quite efficient and universal data selection method named ZIP for training LLMs, which aim to prioritize data subsets exhibiting a low compression ratio. Based on a multi-stage algorithm that selects diverse data in a greedy manner, we can obtain a good data subset with satisfactory diversity. Extensive experiments have been conducted to validate the entropy law and the superiority of ZIP across different LLM backbones and alignment stages. We also present an interesting application of entropy law that can detect potential performance risks at the beginning of model training.

### <span id="6">RecRanker: Instruction Tuning Large Language Model as Ranker for Topk Recommendation</span>
[link to this paper](https://arxiv.org/abs/2306.01495)

**Authors:** Sichun Luo, Bowei He, Haohan Zhao, Wei Shao, Yanlin Qi, Yinya Huang, Aojun Zhou, Yuxuan Yao, Zongpeng Li, Yuanzhang Xiao, Mingjie Zhan, Linqi Song

Large Language Models (LLMs) have demonstrated remarkable capabilities and have been extensively deployed across various domains, including recommender systems. Prior research has employed specialized \textit{prompts} to leverage the in-context learning capabilities of LLMs for recommendation purposes. More recent studies have utilized instruction tuning techniques to align LLMs with human preferences, promising more effective recommendations. However, existing methods suffer from several limitations. The full potential of LLMs is not fully elicited due to low-quality tuning data and the overlooked integration of conventional recommender signals. Furthermore, LLMs may generate inconsistent responses for different ranking tasks in the recommendation, potentially leading to unreliable results.
In this paper, we introduce \textbf{RecRanker}, tailored for instruction tuning LLMs to serve as the \textbf{Ranker} for top-\textit{k} \textbf{Rec}ommendations. Specifically, we introduce an adaptive sampling module for sampling high-quality, representative, and diverse training data. To enhance the prompt, we introduce a position shifting strategy to mitigate position bias and augment the prompt with auxiliary information from conventional recommendation models, thereby enriching the contextual understanding of the LLM. Subsequently, we utilize the sampled data to assemble an instruction-tuning dataset with the augmented prompts comprising three distinct ranking tasks: pointwise, pairwise, and listwise rankings. We further propose a hybrid ranking method to enhance the model performance by ensembling these ranking tasks. Our empirical evaluations demonstrate the effectiveness of our proposed RecRanker in both direct and sequential recommendation scenarios.

### <span id="7">The Data Minimization Principle in Machine Learning</span>
[link to this paper](https://arxiv.org/abs/2405.19471v1)

**Authors:** Prakhar Ganesh, Cuong Tran, Reza Shokri, Ferdinando Fioretto

The principle of data minimization aims to reduce the amount of data collected, processed or retained to minimize the potential for misuse, unauthorized access, or data breaches. Rooted in privacy-by-design principles, data minimization has been endorsed by various global data protection regulations. However, its practical implementation remains a challenge due to the lack of a rigorous formulation. This paper addresses this gap and introduces an optimization framework for data minimization based on its legal definitions. It then adapts several optimization algorithms to perform data minimization and conducts a comprehensive evaluation in terms of their compliance with minimization objectives as well as their impact on user privacy. Our analysis underscores the mismatch between the privacy expectations of data minimization and the actual privacy benefits, emphasizing the need for approaches that account for multiple facets of real-world privacy risks.

### <span id="8">Deep Learning on a Data Diet: Finding Important Examples Early in Training</span>
[link to this paper](https://arxiv.org/abs/2103.12961)

**Authors:** Mansheej Paul, Surya Ganguli, Gintare Karolina Dziugaite

Recent success in deep learning has partially been driven by training increasingly overparametrized networks on ever larger datasets. It is therefore natural to ask: how much of the data is superfluous, which examples are important for generalization, and how do we find them? In this work, we make the striking observation that, in standard vision datasets, simple scores averaged over several weight initializations can be used to identify important examples very early in training. We propose two such scores -- the Gradient Normed (GraNd) and the Error L2-Norm (EL2N) scores -- and demonstrate their efficacy on a range of architectures and datasets by pruning significant fractions of training data without sacrificing test accuracy. In fact, using EL2N scores calculated a few epochs into training, we can prune half of the CIFAR10 training set while slightly improving test accuracy. Furthermore, for a given dataset, EL2N scores from one architecture or hyperparameter configuration generalize to other configurations. Compared to recent work that prunes data by discarding examples that are rarely forgotten over the course of training, our scores use only local information early in training. We also use our scores to detect noisy examples and study training dynamics through the lens of important examples -- we investigate how the data distribution shapes the loss surface and identify subspaces of the model's data representation that are relatively stable over training.

### <span id="9">Less Is Better: Unweighted Data Subsampling via Influence Function</span>
[link to this paper](https://arxiv.org/abs/2110.14034)

**Authors:** Zifeng Wang, Hong Zhu, Zhenhua Dong, Xiuqiang He, Shao-Lun Huang

In the time of Big Data, training complex models on large-scale data sets is challenging, making it appealing to reduce data volume for saving computation resources by subsampling. Most previous works in subsampling are weighted methods designed to help the performance of subset-model approach the full-set-model, hence the weighted methods have no chance to acquire a subset-model that is better than the full-set-model. However, we question that how can we achieve better model with less data? In this work, we propose a novel Unweighted Influence Data Subsampling (UIDS) method, and prove that the subset-model acquired through our method can outperform the full-set-model. Besides, we show that overly confident on a given test set for sampling is common in Influence-based subsampling methods, which can eventually cause our subset-model's failure in out-of-sample test. To mitigate it, we develop a probabilistic sampling scheme to control the worst-case risk over all distributions close to the empirical distribution. The experiment results demonstrate our methods superiority over existed subsampling methods in diverse tasks, such as text classification, image classification, click-through prediction, etc.

### <span id="10">InfoBatch: Lossless Training Speed Up by Unbiased Dynamic Data Pruning</span>
[link to this paper](https://arxiv.org/abs/2303.04947)

**Authors:** Ziheng Qin, Kai Wang, Zangwei Zheng, Jianyang Gu, Xiangyu Peng, Zhaopan Xu, Daquan Zhou, Lei Shang, Baigui Sun, Xuansong Xie, Yang You

Data pruning aims to obtain lossless performances with less overall cost. A common approach is to filter out samples that make less contribution to the training. This could lead to gradient expectation bias compared to the original data. To solve this problem, we propose \textbf{InfoBatch}, a novel framework aiming to achieve lossless training acceleration by unbiased dynamic data pruning. Specifically, InfoBatch randomly prunes a portion of less informative samples based on the loss distribution and rescales the gradients of the remaining samples to approximate the original gradient. As a plug-and-play and architecture-agnostic framework, InfoBatch consistently obtains lossless training results on classification, semantic segmentation, vision pertaining, and instruction fine-tuning tasks. On CIFAR10/100, ImageNet-1K, and ADE20K, InfoBatch losslessly saves 40\% overall cost. For pertaining MAE and diffusion model, InfoBatch can respectively save 24.8\% and 27\% cost. For LLaMA instruction fine-tuning, InfoBatch is also able to save 20\% cost and is compatible with coreset selection methods. The code is publicly available at [this http URL](http://github.com/NUS-HPC-AI-Lab/InfoBatch).

### <span id="11">Coverage-centric Coreset Selection for High Pruning Rates</span>
[link to this paper](https://arxiv.org/abs/2210.15809)

**Authors:** Haizhong Zheng, Rui Liu, Fan Lai, Atul Prakash

One-shot coreset selection aims to select a representative subset of the training data, given a pruning rate, that can later be used to train future models while retaining high accuracy. State-of-the-art coreset selection methods pick the highest importance examples based on an importance metric and are found to perform well at low pruning rates. However, at high pruning rates, they suffer from a catastrophic accuracy drop, performing worse than even random sampling. This paper explores the reasons behind this accuracy drop both theoretically and empirically. We first propose a novel metric to measure the coverage of a dataset on a specific distribution by extending the classical geometric set cover problem to a distribution cover problem. This metric helps explain why coresets selected by SOTA methods at high pruning rates perform poorly compared to random sampling because of worse data coverage. We then propose a novel one-shot coreset selection method, Coverage-centric Coreset Selection (CCS), that jointly considers overall data coverage upon a distribution as well as the importance of each example. We evaluate CCS on five datasets and show that, at high pruning rates (e.g., 90%), it achieves significantly better accuracy than previous SOTA methods (e.g., at least 19.56% higher on CIFAR10) as well as random selection (e.g., 7.04% higher on CIFAR10) and comparable accuracy at low pruning rates. We make our code publicly available at [this https URL](https://github.com/haizhongzheng/Coverage-centric-coreset-selection).

### <span id="12">Selection via Proxy: Efficient Data Selection for Deep Learning</span>
[link to this paper](https://arxiv.org/abs/2306.00184)

**Authors:** Cody Coleman, Christopher Yeh, Stephen Mussmann, Baharan Mirzasoleiman, Peter Bailis, Percy Liang, Jure Leskovec, Matei Zaharia

Data selection methods, such as active learning and core-set selection, are useful tools for machine learning on large datasets. However, they can be prohibitively expensive to apply in deep learning because they depend on feature representations that need to be learned. In this work, we show that we can greatly improve the computational efficiency by using a small proxy model to perform data selection (e.g., selecting data points to label for active learning). By removing hidden layers from the target model, using smaller architectures, and training for fewer epochs, we create proxies that are an order of magnitude faster to train. Although these small proxy models have higher error rates, we find that they empirically provide useful signals for data selection. We evaluate this "selection via proxy" (SVP) approach on several data selection tasks across five datasets: CIFAR10, CIFAR100, ImageNet, Amazon Review Polarity, and Amazon Review Full. For active learning, applying SVP can give an order of magnitude improvement in data selection runtime (i.e., the time it takes to repeatedly train and select points) without significantly increasing the final error (often within 0.1%). For core-set selection on CIFAR10, proxies that are over 10x faster to train than their larger, more accurate targets can remove up to 50% of the data without harming the final accuracy of the target, leading to a 1.6x end-to-end training time improvement.

### <span id="13">Dataset Condensation via Efficient Synthetic Data Parameterization</span>
[link to this paper](https://arxiv.org/abs/2206.00719)

**Authors:** Jang-Hyun Kim, Jinuk Kim, Seong Joon Oh, Sangdoo Yun, Hwanjun Song, Joonhyun Jeong, Jung-Woo Ha, Hyun Oh Song

The great success of machine learning with massive amounts of data comes at a price of huge computation costs and storage for training and tuning. Recent studies on dataset condensation attempt to reduce the dependence on such massive data by synthesizing a compact training dataset. However, the existing approaches have fundamental limitations in optimization due to the limited representability of synthetic datasets without considering any data regularity characteristics. To this end, we propose a novel condensation framework that generates multiple synthetic data with a limited storage budget via efficient parameterization considering data regularity. We further analyze the shortcomings of the existing gradient matching-based condensation methods and develop an effective optimization technique for improving the condensation of training data information. We propose a unified algorithm that drastically improves the quality of condensed data against the current state-of-the-art on CIFAR-10, ImageNet, and Speech Commands.

### <span id="14">Dataset Condensation with Gradient Matching</span>
[link to this paper](https://arxiv.org/abs/2202.07122)

**Authors:** Bo Zhao, Konda Reddy Mopuri, Hakan Bilen

As the state-of-the-art machine learning methods in many fields rely on larger datasets, storing datasets and training models on them become significantly more expensive. This paper proposes a training set synthesis technique for data-efficient learning, called Dataset Condensation, that learns to condense large dataset into a small set of informative synthetic samples for training deep neural networks from scratch. We formulate this goal as a gradient matching problem between the gradients of deep neural network weights that are trained on the original and our synthetic data. We rigorously evaluate its performance in several computer vision benchmarks and demonstrate that it significantly outperforms the state-of-the-art methods. Finally we explore the use of our method in continual learning and neural architecture search and report promising gains when limited memory and computations are available.