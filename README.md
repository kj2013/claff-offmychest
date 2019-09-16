# CL-Aff Shared Task: Get it #OffMyChest
Corpus and annotations for the CL-Aff Shared Task - Get it #OffMyChest - from Nanyang Technological University Singapore

A part of the AffCon Workshop @ AAAI 2019 for Modeling Affect-in-Response

There is a growing interest in understanding how humans initiate and hold conversations. The affective understanding of conversations focuses on the problem of how speakers use emotions to react to a situation and to each other. We introduce the OffMyChest conversation dataset, and invite submissions for the Computational Linguistics Affect Understanding (CL-Aff) Shared Task on modeling interactive affective responses. 

# LABELED TRAINING DATA TO BE RELEASED ON SEPTEMBER 18, 2019

Organizers:

Kokil Jaidka, Nanyang Technological University

Niyati Chhaya , Big Data Experience Lab, Adobe Research

Jiahui Lu, Nanyang Technological University

Iknoor Singh, Panjab University

Lyle Ungar, University of Pennsylvania

Check out the Workshop and Shared Task website: https://sites.google.com/view/affcon2020/home

ABSTRACT SUBMISSION DEADLINE: October 20, 2019


## The Tasks

**GIVEN**: Sentences sampled out of the casual and confessional conversations among Redittors on the /r/CasualConversations and the /r/OffMyChest community, labeled for their informational, social and affective characteristics.

**TASK 1** : Semi-supervised learning task: Predict labels for Disclosure and Supportiveness for sentences based on a small labeled and large unlabeled training data.    

**TASK 2**: Unsupervised task: Propose new characterizations and insights to model conversation dynamics.

## Corpus details

**Unlabeled training set** (Already released!):

**UNLABELED POSTS:** The top posts in 2018 in /r/CasualConversations and /r/OffMyChest mentionining any of the keyword terms. Posts that are parents of comments in the training and test sets are separately identified.

**UNLABELED COMMENTS:** Over 420k sentences extracted from 130k comments posted to "POSTS"


**Labeled training set** (To be released on Sep 18): About 10,000 labeled sentences, extracted from the top comments posted to "POSTS".

**Test set:** About 3,000 unlabeled sentences, extracted from the top comments posted to "POSTS".


## Label descriptions

Check out the annotation instructions under /docs/.

1. *Disclosure* is further categorized into informational and emotional disclosure.

2. *Supportiveness* is further categorized into general, informational, and emotional supportiveness.

## Check out the FAQ! (TO BE RELEASED)

Please "WATCH" this repository! We may be pushing more updates in the following weeks.
After the Shared Task, we also plan to further enrich this data, with more annotations, meta-features and trained classifiers to aid with downstream applications.

If you use the data and publish, please let us know and cite our CL-Aff overview paper:

@inproceedings

{TBA
}


If you have any questions regarding the workshop scope or need further information, please do not hesitate to send an e-mail: 

Niyati, nchhaya [AT] adobe.com

Kokil, jaidka [AT] sas.upenn.edu 

Jiahui, jhlu [AT] ntu.edu.sg

Thank you!
