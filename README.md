# Language Representation Models for Fine Grained Sentiment Classification

## Team

Brian Cheang, Bailey Wei, David Kogan, Howey Qiu, Masud Ahmed

Thank you to my teammates for the great work!

## Abstract

Sentiment classification is a quickly advancing field of study with applications in almost any field. While various models and datasets have shown high accuracy in the task of binary classification, the task of fine-grained sentiment classification is still an area with room for significant improvement. Analyzing the SST-5 dataset,previous work by Munikar et al. (2019) showed that the embedding tool BERT allowed a simple model to achieve state-of-the-art accuracy. Since that paper, several BERT alternatives have been published, with three primary ones being AlBERT (Lan et al., 2019), DistilBERT (Sanh et al. 2019), and RoBERTa (Liu etal. 2019). While these models report some improvement over BERT on the popular benchmarks GLUE, SQuAD, and RACE, they have not been applied to the fine-grained classification task. In this paper, we examine whether the improvements hold true when applied to a novel task, by replicating the BERT model from Munikar et al., and swapping the embedding layer to the alternative models. Over the experiments, we found that AlBERT suffers significantly more accuracy loss than reported on other tasks, DistilBERT has accuracy loss similar to their reported loss on other tasks while being the fastest model to train, and RoBERTa reaches a new state-of-the-art accuracy for prediction on the SST-5 root level (60.2%).

## Final Results

Our model RoBERTa based model reached a 60.2% accuracy for the prediction on the SST-5 root level.

## Future Steps

We are currently experimenting on implementing dropout to further drive our accuracy. 

## Paper

https://arxiv.org/abs/2005.13619