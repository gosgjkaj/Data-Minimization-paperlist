# Recommendation Privacy : A Survey About Data Minimization and Unlearning in Recommendation Systems

In this repository, we introduce some of the least reaserch paper highlighting the topic of Recommendation Privacy, specificlly **Data minimization** and **Unlearning**. We primarily gather papers related to recommendation systems, which are the main focus of our research. However, to broaden the scope of knowledge, we also include relevant papers from other domains or algorithms, categorized under each subsection.

The concept of Data Minimization and Unlearning came from the following regulations:
- [GDPR](https://gdpr-info.eu/)
- [CCPA](https://oag.ca.gov/privacy/ccpa/regs)

## Data Minimization

**Keywords:** Dataset Distillation, Coreset Selection, Dataset Pruning 

### DM4Rec
<table>
  <tbody>
    <tr>
      <th>Title</th>
      <th align="center">Comments</th>
      <th align="center">Link</th>
    </tr>
    <!-- Paper list start here -->
    <tr>
      <td align="left">Operationalizing the Legal Principle of Data Minimization for Personalization</td>
      <td align="center">Baseline, one of the first paper about DM4Rec</td>
      <td align="center">
        <a href="https://arxiv.org/abs/2005.13718">
          WWW 2022
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">Dataset condensation for recommendation (Condensing Pre-augmented Recommendation Data via Lightweight Policy Gradient Estimation)</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://arxiv.org/abs/2310.01038">
          TKDE 01.2025
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">Data-efficient Fine-tuning for LLM-based Recommendation</td>
      <td align="center">LLM, Influence function</td>
      <td align="center">
        <a href="https://arxiv.org/abs/2401.17197">
        SIGIR 2024
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">The trade-off between data minimization and fairness in collaborative filtering</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://arxiv.org/abs/2410.07182">
        Arxiv 2024
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">Exploring Recommendations Under User-Controlled Data Filtering</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://dl.acm.org/doi/10.1145/3240323.3240399">
        RecSys 2018
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">Privacy-Preserving Synthetic Data Generation for Recommendation Systems</td>
      <td align="center">Generates new items to replace the original interactions</td>
      <td align="center">
        <a href="https://dl.acm.org/doi/10.1145/3477495.3532044">
        SIGIR 2022
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">Leveraging Uncertainty Quantification for Reducing Data for Recommender Systems</td>
      <td align="center">Introducing uncertainty</td>
      <td align="center">
        <a href="https://ieeexplore.ieee.org/document/10386790">
        BigData 2023
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">Dataset Regeneration for Sequential Recommendation</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://dl.acm.org/doi/10.1145/3637528.3671841">
        KDD 2024
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
  </tbody>
</table>

### DM4ML

<table>
  <tbody>
    <tr>
      <th>Title</th>
      <th align="center">Comments</th>
      <th align="center">Link</th>
    </tr>
    <!-- Paper list start here -->
    <tr>
      <td align="left">The Data Minimization Principle in Machine Learning</td>
      <td align="center">Bi-level optimization</td>
      <td align="center">
        <a href="https://arxiv.org/abs/2405.19471">
        Arxiv 2024
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">Coverage-Centric Corest Selection For High Pruning Rates</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://arxiv.org/abs/2210.15809">
        ICLR 2023
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">Deep Learning on a Data Diet: Finding Important Examples Early in Training</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://arxiv.org/abs/2107.07075">
        NIPS 2021
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">I Prefer Not To Say: Protecting User Consent in Models with Optional Personal Data</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://arxiv.org/abs/2210.13954">
        AAAI 2024
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">Large-scale Dataset Pruning with Dynamic Uncertainty</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://arxiv.org/abs/2306.05175">
        CVPR 2024
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">Selection Via Proxy: Efficient Data Selection For Deep Learning</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://arxiv.org/abs/1906.11829">
        ICLR 2020
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">Privacy for Free: How does Dataset Condensation Help Privacy?</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://arxiv.org/abs/2206.00240">
        ICML 2022
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">No Free Lunch in “Privacy for Free: How does Dataset  Condensation Help Privacy”</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://arxiv.org/abs/2209.14987">
        Arxiv 2022
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">The trade-off between data minimization and fairness in collaborative filtering</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://arxiv.org/abs/2410.07182">
        Arxiv 2024
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">Learning to Limit Data Collection via Scaling Laws: A Computational Interpretation for the Legal Principle of Data Minimization</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://dl.acm.org/doi/10.1145/3531146.3533148">
        FAccT 2022
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">Distill Gold from Massive Ores: Efficient Dataset Distillation via Critical Samples Selection</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://arxiv.org/abs/2305.18381">
        ECCV 2024
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">“I’m not convinced that they don’t collect more than is necessary”:  User-Controlled Data Minimization Design in Search Engines</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://www.usenix.org/conference/usenixsecurity24/presentation/sharma">
        USENIX 2024
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">Data Distillation: A Survey</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://arxiv.org/abs/2301.04272">
        TMLR 2023
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">Data Minimization for GDPR Compliance in  Machine Learning Models</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://link.springer.com/article/10.1007/s43681-021-00095-8">
        AI & Ethics 2021
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
  </tbody>
</table>

## Unlearning

### Unlearn4Rec

<table>
  <tbody>
    <tr>
      <th>Title</th>
      <th align="center">Comments</th>
      <th align="center">Link</th>
    </tr>
    <!-- Updated paper list with comments -->
    <tr>
      <td align="left">Recommendation Unlearning</td>
      <td align="center">Further apply Unlearning in Rec</td>
      <td align="center">
        <a href="https://arxiv.org/abs/2201.06820">
          WWW 2022
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">CURE4Rec: A Benchmark for Recommendation Unlearning with Deeper Influence</td>
      <td align="center">4 Benchmarks</td>
      <td align="center">
        <a href="https://arxiv.org/abs/2408.14393">
          NIPS 2024
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Post-Training Attribute Unlearning in Recommender Systems</td>
      <td align="center"></td>
      <td align="center">
        <a href="https://dl.acm.org/doi/10.1145/3701987">
          TOIS 2024
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Recommendation Unlearning via Influence Function</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://dl.acm.org/doi/10.1145/3701763">
          TOIS 2024
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">On the Effectiveness of Unlearning in Session-Based Recommendation</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://dl.acm.org/doi/10.1145/3616855.3635823">
          WSDM 2024
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">A General Strategy Graph Collaborative Filtering for Recommendation Unlearning</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://dl.acm.org/doi/10.1145/3627673.3679637">
          CIKM 2024
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <!-- End of updated paper list -->
  </tbody>
</table>

### Unlearn4ML

<table>
  <tbody>
    <tr>
      <th>Title</th>
      <th align="center">Comments</th>
      <th align="center">Link</th>
    </tr>
    <!-- Updated paper list with comments -->
    <tr>
      <td align="left">Machine Unlearning</td>
      <td align="center">Foundational approach</td>
      <td align="center">
        <a href="https://arxiv.org/abs/1912.03817">
          TCSP 2021
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Graph Unlearning</td>
      <td align="center">Apply Unlearning on Graph</td>
      <td align="center">
        <a href="https://dl.acm.org/doi/10.1145/3548606.3559352">
          CCS 2022
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Fast Machine Unlearning Without Retraining Through Selective Synaptic Dampening</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://arxiv.org/abs/2308.07707">
          AAAI 2024
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">What makes unlearning hard and what to do about it</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://arxiv.org/abs/2406.01257">
          NIPS 2024
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Scalability of memorization-based machine unlearning</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://arxiv.org/abs/2410.16516">
          NIPS 2024
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Machine Unlearning: Solutions and Challenges</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://ieeexplore.ieee.org/document/10488864">
        TETCI 2024
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">Machine Unlearning: A Survey</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://dl.acm.org/doi/10.1145/3603620">
        CSUR 2023
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">Machine Unlearning: A Comprehensive Survey</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://dl.acm.org/doi/10.1145/3603620">
        Arxiv 2024
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">Machine Unlearning Doesn't Do What You Think: Lessons for Generative AI Policy, Research, and Practice</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://arxiv.org/abs/2412.06966v1">
        ICML 2024
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">A Survey of Machine Unlearning</td>
      <td align="center">-</td>
      <td align="center">
        <a href="https://arxiv.org/abs/2209.02299">
        Arxiv 2024
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <tr>
      <td align="left">Machine Unlearning: Taxonomy, Metrics, Applications, Challenges, and Prospects</td>
      <td align="center">Good graph, comparison with other surveys</td>
      <td align="center">
        <a href="https://arxiv.org/abs/2403.08254">
        Arxiv 2024
        </a>
      </td>
    </tr>
    <!-- This is one paper, follow this format -->
    <!-- End of updated paper list -->
  </tbody>
</table>


<!-- 
## [Data Minimization for Machine Learning](/DM4ML.md)

### Survey
- [A Comprehensive Survey of Dataset Distillation](https://arxiv.org/abs/2301.05603)
- [Data Distillation: A Survey](https://arxiv.org/abs/2301.04272)

### General paper
- [Dataset Regeneration for Sequential Recommendation](https://arxiv.org/abs/2405.17795)
- [Large-scale Dataset Pruning with Dynamic Uncertainty](https://arxiv.org/abs/2306.05175)
- [Entropy Law The Story Behind Data Compression and LLM Performance](https://arxiv.org/abs/2407.06645)
- [RecRanker Instruction Tuning Large Language Model as Ranker for Topk Recommendation](https://arxiv.org/abs/2306.01495)
- [The Data Minimization Principle in Machine Learning](https://arxiv.org/abs/2405.19471v1)
- [Deep Learning on a Data Diet Finding Important Examples Early in Training](https://arxiv.org/abs/2103.12961)
- [Less Is Better Unweighted Data Subsampling via Influence Function](https://arxiv.org/abs/2110.14034)
- [InfoBatch Lossless Training Speed Up by Unbiased Dynamic Data Pruning](https://arxiv.org/abs/2303.04947)
- [Coverage-centric Coreset Selection for High Pruning Rates](https://arxiv.org/abs/2210.15809)
- [Selection via Proxy Efficient Data Selection for Deep Learning](https://arxiv.org/abs/2306.00184)
- [Dataset Condensation via Efficient SyntheticData Parameterization](https://arxiv.org/abs/2206.00719)
- [Dataset Condensation with Gradient Matching](https://arxiv.org/abs/2202.07122)

## [LLM for Recommendation](/LLM4Rec.md)

### Survey
- [A Survey on Large Language Models for Recommendation](https://arxiv.org/abs/2305.19860)
- [How Can Recommender Systems Benefit from Large Language Models A Survey](https://arxiv.org/abs/2311.12338)

### General Paper
- [Recommender Systems in the Era of Large Language Models LLMs](https://arxiv.org/abs/2307.02046)
- [A Bi-Step Grounding Paradigm for Large Language Models in Recommendation Systems](https://arxiv.org/abs/2308.08434)
- [Recommendation as Instruction Following A Large Language Model Empowered Recommendation Approach](https://arxiv.org/abs/2306.01495)
- [Uncovering ChatGPTs Capabilities in Recommender Systems](https://arxiv.org/abs/2305.02182)

## [Privacy](/privacy.md)
- [No Free Lunch in Privacy for Free How does Dataset Condensation Help Privacy](https://arxiv.org/abs/2209.14987)
- [The Utility and Privacy Effects of a Click](https://arxiv.org/abs/2206.00240)
- [Privacy for Free How does Dataset Condensation Help Privacy](https://dl.acm.org/doi/abs/10.1145/3077136.3080783)

## [Other useful paper](/others.md)

- [LoRA LowRank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685)
- [Recommender Systems with Generative Retrieval](https://arxiv.org/abs/2305.05065)
- [Our Model Achieves Excellent Performance on MovieLens What Does It Mean](https://arxiv.org/abs/2307.09985)
- [TALLRec An Effective and Efficient Tuning Framework to Align Large Language Model with Recommendation](https://arxiv.org/abs/2305.00447) -->
