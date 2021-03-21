# EACL-2021
<img title="" src="Figures/EACL.PNG" alt="">

`Code and dataset of the tasks are released here. In order to use the dataset interested ones have to follow policy of workshop organizers`

# Shared Task#1
<img title="" src="Figures/offensive.PNG" alt="">

## Offensive Language Detection from Multilingual Code-Mixed Text using Transformers

**Author:** Omar , Eftekhar Hossain, and Mohammed Moshiul Hoque

**Venue:** Shared task description paper of DravidianLangTech workshop collocated with EACL-2021. [DravidianLangTech@EACL2021](https://dravidianlangtech.github.io/2021/index.html)

**Paper Link:** [https://arxiv.org/abs/2103.00455](https://arxiv.org/abs/2103.00455)
## Abstract

The increasing accessibility of the internet facilitated social media usage and encouraged individuals to express their opinions liberally. Nevertheless, it also creates a place for content polluters to disseminate offensive posts or contents. Most of such offensive posts are written in a cross-lingual manner and can easily evade the online surveillance systems. This paper presents an automated system that can identify offensive text from multilingual code-mixed data. In the task, datasets provided in three languages including Tamil, Malayalam and Kannada code-mixed with English where participants are asked to implement separate models for each language. To accomplish the tasks, we employed two machine learning techniques (LR, SVM), three deep learning (LSTM, LSTM+Attention) techniques and three transformers (m-BERT, Indic-BERT, XLM-R) based methods. Results show that
XLM-R outperforms other techniques in Tamil and Malayalam languages while m-BERT achieves the highest score in the Kannada language. The proposed models gained weighted f-1 score of 0.76 (for Tamil), 0.93 (for Malayalam), and 0:71 (for Kannada) with a rank of 3rd, 5th and 4th respectively

## Contribution
- Prepared transformer-based methods to identify the offensive texts from multilingual (Tamil, Malayalam, Kannada) code-mixed data..
- Perform experiments on the dataset with detail performance and error analysis, thus setting an important baseline to compare in future.

## Task Description

The CONSTRAINT shared task comprises of two tasks: task-A and task-B. The goal of task-A is to identify whether a tweet contains real or fake information. The tweets are related to the Covid-19 pandemic and written in English. In task-B, we have to perform multi-label multi-class classication on five hostile dimensions such as fake news, hate speech, ofensive, defamation and non-hostile.

- **Fake**: Articles, posts and tweets provide information or make claims which are verified not to be true.
- **Real**: The articles, posts and tweets which provided verified information and make authentic claims.
- **Hate speech**: Post having the malicious intention of spreading hate and violence against specific group or person based on some specific characteristics such as religious beliefs, ethnicity, and race.
- **Offensive**: A post contains vulgar, rude, impolite and obscene languages to insult a targeted individual or a group.
- **Defamation**: Posts spread misinformation against a group or individuals
which aim to damage their social identity publicly.
- **Non-hostile**: Posts without any hostility.

## Dataset Analysis

The number of instances used to train, validate and test the models summarized in table 1.

<img title="" src="Figures/Table1.PNG" alt="">

To get the useful insights, we investigated the train set. Statistics of the train set exhibited in table 2.

<img title="" src="Figures/Table2.PNG" alt="">

Figure 1 depicts the number of texts fall in various length range.
<img title="" src="Figures/Fig1.PNG" alt="">

## System Overview
Figure 2 presents the schematic diagram of our system, which has three major phases: preprocessing, feature extraction and classification.
<img title="" src="Figures/Fig2.PNG" alt="">

## Results 
Table 3 presents the evaluation results of task-A on the test set.
<img title="" src="Figures/Table3.PNG" alt="">

Evaluation results of task-B on the test set are presented in table 4.
<img title="" src="Figures/Table4.PNG" alt="">

Tables 5a-5f represent the confusion matrices of the classes for task-A and B.
<img title="" src="Figures/Table5.PNG" alt="">

Some misclassified examples with there actual (A) and predicted label (P) presented in table 6.
<img title="" src="Figures/Table6.PNG" alt="">

## Conclusion
This paper presents the system description with detailed results and error analysis developed in the CONSTRAINT 2021 shared task. Various learning technique have explored with tf-idf feature extraction, andWord2Vec embedding technique to accomplish the tasks A and B. Results shows that SVM with tf-idf achieved the highest of 94.39% f1 scores for the task-A and LPSVM with n-gram (1, 3) obtained the highest of 86.03% f1 scores for the task-B. However, the BERT pre-trained model provided the 98% accuracy in task-A and 97% accuracy in task-B. Since CNN and BiLSTM did not achieve satisfactory accuracy, it will be interesting to see how they perform after applying ensemble technique or adding attention layer. Increasing the number of posts in hostile classes can help to improve the performance of the models. These issues will address in future work.

## Ackonwlegement
Without my teammate [Eftekhar Hossain's](https://eftekhar-hossain.github.io/portfolio/) support and dedication this work would not be possible. Finally, thanks to [Prof. Dr. Mohammed Moshiul Hoque](https://www.researchgate.net/profile/Moshiul_Hoque) for his valuable guidance.

## Note
`If you find any anomaly or have any query/suggestion feel free to ping.`
#
# Shared Task#2
<img title="" src="Figures/hope.PNG" alt="">

## Multilingual Code-Mixed Hope Speech Detection using Cross-lingual Representation Learner

**Author:** Eftekhar Hossain, Omar Sharif, and Mohammed Moshiul Hoque

**Venue:** Shared task description paper of LT-EDI workshop collocated with EACL-2021. [LT-EDI@EACL2021](https://sites.google.com/view/lt-edi-2021/home)

**Paper Link:** [https://arxiv.org/abs/2103.00464](https://arxiv.org/abs/2103.00464)


