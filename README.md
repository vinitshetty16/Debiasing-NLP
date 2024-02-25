# NLP Bias and Debiasing
![image](https://github.com/vinitshetty16/NLP-Bias-Debiasing/assets/63487624/86a7f3b7-23c5-42e1-ba70-0800f1cc85bf)

## Introduction
This project delves into Natural Language Processing (NLP), exploring bias and discrimination in AI systems. NLP enables computers to understand, interpret, and manipulate human language, making it a crucial component of various AI applications. In this project, we investigate the presence of bias in word embeddings and explore methodologies to mitigate these biases, aiming to create fairer and more inclusive AI systems in the domain of NLP.

## Methodology
- **Word Embeddings**: We begin by understanding word embeddings, particularly GloVe vectors, which represent words in a high-dimensional vector space. These vectors capture semantic relationships between words, forming the basis for many NLP tasks.
- **Cosine Similarity**: We measure the similarity between word vectors using cosine similarity, a metric that quantifies the degree of similarity between two vectors.
- **Word Analogy Task**: Through the word analogy task, we explore relationships between words and their embeddings, demonstrating how word vectors can be used to solve analogical reasoning problems.
- **Debiasing Word Vectors**: We investigate gender biases present in word embeddings and explore algorithms to mitigate these biases. This involves neutralizing and equalizing word vectors to reduce gender-specific associations and promote gender neutrality.
- **Multiclass Bias Removal**: We extend the debiasing techniques to address biases related to race and religion in word embeddings. Using algorithms introduced by Manzini et al., we identify and mitigate multiclass biases while preserving the utility of embeddings.

## Dependencies
Ensure the following libraries are installed:
- numpy
- matplotlib
- seaborn
- Any other necessary libraries specified in the assignment instructions.

## Conclusion
This assignment provides insights into the biases inherent in word embeddings and the methodologies to mitigate them. By understanding and implementing debiasing techniques, we aim to create more fair and inclusive AI systems in the domain of NLP.

## References
- Bolukbasi et al., 2016: [Link to Paper](https://arxiv.org/abs/1607.06520)
- Manzini et al., 2019: [Link to Paper](https://arxiv.org/pdf/1904.04047.pdf)

Feel free to explore the provided code and experiment with different word embeddings and debiasing techniques!
