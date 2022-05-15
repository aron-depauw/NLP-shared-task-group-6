# NLP-shared-task-group-6
Group 6 – group.apply(set, member=3)

## Abstract

This paper presents the design decisions taken and challenges encountered in the automatic detection of offensive language in English social media posts based on a dataset provided by the organizers of OffensEval 2019, Subtask A (Zampieri et al., 2019a) (Zampieri et al., 2019b), which poses the problem of identifying and categorizing offensive language in tweets. Our proposed solutions explore both traditional Machine Learning and Deep Learning techniques using a fine-tuned BERT based classifier and Linear Support Vector classification to identify offensive and/or hateful language in social media texts. We also study the usefulness of sentiment-based and lexical features, and investigate the effect of different preprocessing methods on offensive language detection using the macro F1 measure. The results of the conducted experiments show that sentiment-related and task-specific lexical features can improve model performance for the traditional SVM model, while extensive preprocessing can result in too much information loss, thereby decreasing performance for the neural BERT model. We make the source code of our experiments publicly available.


## Repository overview

The NLP-shared-task-group-6 folder contains all relevant files, including a jupyter notebook with code for the classical classifier (Group-6-traditional), a jupyter notebook for neural classifier (Group-6-neural), and all other relevant files, data, images, etc. Please note that the Notebooks appended with "Submissions" contain the models used for generating the predictions that were submitted to the shared task.


## Authors

Aron Depauw,
Valentina Ravest Córdova,
Anqi Yu
