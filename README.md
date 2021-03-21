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

## Dataset Analysis

The number of instances used to train, validate and test the models summarized in table 1.


<img title="" src="Figures/off_data.PNG" alt="">


## System Overview
Figure 1 presents the schematic diagram of our system, which has three major phases: preprocessing, feature extraction and classification.
<p align = "center">
<img title="" src="Figures/off_block.png" alt="">
</p>

## Results 
Table 2 presents the evaluation results of the tasks on the test set.

<img title="" src="Figures/off_result.PNG" alt="">


Figure 2 presents the confusion matrices of the best model for each language.

<img title="" src="Figures/off_confusion.PNG" alt="">


## Conclusion
In this work, we have described and analyzed the system’s performance implemented as a participation in the offensive language identification shared task at EACL-2021. Initially, SVM, LR, LSTM, LSTM+Attention models have employed with tf-idf and word embedding features. Results indicate that ML ensemble achieved higher accuracy than DL methods. However, the outcomes are not promising for the available datasets. Code-mixing of multilingual texts might be a reason behind this. We applied transformer-based models to overcome this situation, which provides an astonishing rise in accuracy than ML and DL-based methods. Weighted f-1 score increased from 0.73 to 0.76, 0.88 to 0.93 and 0.48 to 0.71 for Tamil, Malayalam and Kannada language respectively. In future, the idea of ensemble technique could be adopted on transformer-based models to investigate the system’s overall performance.In this work, we have described and analyzed the system’s performance implemented as a participation in the offensive language identification shared task at EACL-2021. Initially, SVM, LR, LSTM, LSTM+Attention models have employed with tf-idf and word embedding features. Results indicate that ML ensemble achieved higher accuracy than DL methods. However, the outcomes are not promising for the available datasets. Code-mixing of multilingual texts might be a reason behind this. We applied transformer-based models to overcome this situation, which provides an astonishing rise in accuracy than ML and DL-based methods. Weighted f-1 score increased from 0.73 to 0.76, 0.88 to 0.93 and 0.48 to 0.71 for Tamil, Malayalam and Kannada language respectively. In future, the idea of ensemble technique could be adopted on transformer-based models to investigate the system’s overall performance.

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


