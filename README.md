---
tags:
 - sentence-similarity
---

# Azerbaijani Sentence Similarity Based on BERT - Model Description

This model is developed by Alas Development Center and is tailored for the specific use case of sentence similarity in the Azerbaijani language. It employs the bert-base-multilingual-cased architecture, fine-tuned on a Azerbaijani sentence similarity dataset. The primary function of this model is to predict the similarity score between two sentences, which can be highly beneficial in various NLP applications such as information retrieval, question answering, and content analysis.

# Motivation

The core motivation behind developing this model is to address the challenge of Semantic Similarity in the Azerbaijani language. Semantic Similarity assesses how close two sentences are in terms of their underlying meanings. This concept is crucial in many fields, including but not limited to natural language processing, linguistics, and artificial intelligence, facilitating a deeper understanding and processing of human languages.

# Model Training and Evaluation Data


The dataset used for fine-tuning the bert-base-multilingual-cased model specifically targets sentence similarity in Azerbaijani. Below are some details about the training and evaluation data:

    Total Training Samples: 77,499
    Total Validation Samples: 5,500
    Total Test Samples: 7,500


The dataset categorizes sentence pairs into two distinct classes based on their similarity:

    Contradiction: The sentences share no similarity.
    Entailment: The sentences have a similar or nearly identical meaning.
    Neutral: The sentences are neutral.

# Use and Access

This model is shared open source and is intended for wide usage across different applications where understanding sentence similarity in Azerbaijani is crucial. It can be especially useful for developers and researchers working on Azerbaijani language processing tasks.


# Acknowledgements

We express our gratitude to our team who participated in the development, training, and evaluation phases of this model. Their dedication and hard work have been instrumental in advancing Azerbaijani language processing technologies.

This model, used in one of our projects, was developed without the allocation of extensive resources. We believe that with more resources, a better outcome is achievable. It's worth mentioning that this model marks the first endeavor in exploring semantic similarity within the Azerbaijani language context. As such, there is considerable potential for further refinement and improvement, which could significantly enhance its performance and applicability in various fields.

 ## Model Plot

![Model Image](./model.png)

