# Unlearning for Recommender System 

<!-- no toc -->
- [Operationalizing the Legal Principle of Data Minimization for Personalization](#1)
- [Dataset condensation for recommendation](#2)
- [Leveraging Large Language Models LLMs to Empower TrainingFree Dataset Condensation for ContentBased Recommendation](#3)
- [Data-efficient Fine-tuning for LLM-based Recommendation](#4)

---

### <span id="1">Operationalizing the Legal Principle of Data Minimization for Personalization</span>
[link to this paper](https://arxiv.org/abs/2005.13718)

**Authors:** Asia J. Biega, Peter Potash, Hal Daumé III, Fernando Diaz, Michèle Finck

Article 5(1)(c) of the European Union's General Data Protection Regulation (GDPR) requires that "personal data shall be [...] adequate, relevant, and limited to what is necessary in relation to the purposes for which they are processed ('data minimisation')". To date, the legal and computational definitions of 'purpose limitation' and `data minimization' remain largely unclear. In particular, the interpretation of these principles is an open issue for information access systems that optimize for user experience through personalization and do not strictly require personal data collection for the delivery of basic service.
In this paper, we identify a lack of a homogeneous interpretation of the data minimization principle and explore two operational definitions applicable in the context of personalization. The focus of our empirical study in the domain of recommender systems is on providing foundational insights about the (i) feasibility of different data minimization definitions, (ii) robustness of different recommendation algorithms to minimization, and (iii) performance of different minimization strategies.We find that the performance decrease incurred by data minimization might not be substantial, but that it might disparately impact different users---a finding which has implications for the viability of different formal minimization definitions. Overall, our analysis uncovers the complexities of the data minimization problem in the context of personalization and maps the remaining computational and regulatory challenges.