**UPDATE: LABELED TRAINING AND TEST DATA IS UP! Please register for the task at <a>https://easychair.org/conferences/?conf=affcon2020</a>**


# CL-Aff Shared Task: Get it #OffMyChest
Corpus and annotations for the CL-Aff Shared Task - Get it #OffMyChest - from Nanyang Technological University Singapore

A part of the AffCon Workshop @ AAAI 2019 for Modeling Affect-in-Response

There is a growing interest in understanding how humans initiate and hold conversations. The affective understanding of conversations focuses on the problem of how speakers use emotions to react to a situation and to each other. We introduce the OffMyChest conversation dataset, and invite submissions for the Computational Linguistics Affect Understanding (CL-Aff) Shared Task on modeling interactive affective responses. 

**UPDATED ABSTRACT SUBMISSION DEADLINE: November 7, 2019**



## The Tasks

**GIVEN**: Sentences sampled out of the casual and confessional conversations among Redittors on the /r/CasualConversations and the /r/OffMyChest community, labeled for their disclosure and supportive characteristics.

**TASK 1** : Semi-supervised learning task: Predict labels for Disclosure and Supportiveness for sentences based on a small labeled and large unlabeled training data.    

**TASK 2**: Unsupervised task: Propose new characterizations and insights to model conversation dynamics.

## Corpus details (All released!)

**Unlabeled training set** :

**UNLABELED POSTS:** The top posts in 2018 in /r/CasualConversations and /r/OffMyChest mentionining any of the keyword terms. Posts that are parents of comments in the training and test sets are separately identified.

**UNLABELED COMMENTS:** Over 420k sentences extracted from 130k comments posted to "POSTS"


**Labeled training set** : 12,860 labeled sentences, extracted from the top comments posted to "POSTS".

**Test set:** 5,000 unlabeled sentences, extracted from the top comments posted to "POSTS".


## Label descriptions

Check out the annotation instructions under /docs/.

1. *Disclosure* is further categorized into informational and emotional disclosure.

2. *Supportiveness* is further categorized into general, informational, and emotional supportiveness.



## Git Contents

This is the open repository for Affect Understanding in Text and Annotations contributed to the public through the collaboration between Nanyang Technological University, the University of Pennsylvania, and Adobe Research India. It comprises comments (some labeled) and the parent posts (all unlabeled) from the /r/CasualConversations and the /r/OffMyChest communities  


    ./README.md
 
This file.


    ./FAQ2020
	
To be added, will have frequently asked questions including updates to the corpus.


    ./docs/labeldescriptions.txt
  
Definitions for each of the labels


    ./scripts/*
  
Python script used to collect data


    wife, girlfriend, gf, husband, boyfriend, bf
  
The search keywords used to collect data from the API


    ./docs/corpusconstruction.txt
 
To be added, a readme detailing the rules and steps followed to create the document
corpus.
  

    ./docs/annotation_*.txt
  
Rules followed for the annotation.


    ./data/unlabeled data
  
Directory containing unlabeled data pertaining to the training and the test sets.


    ./data/training data
  
Directory containing the training set.


    ./data/test data

Directory containing the test set.



## Organisers' Contacts

The system outputs from the test set should be submitted to the task organizers, for the collation of the final results to be presented at the workshop.

If you have any questions regarding the workshop scope or need further information, please do not hesitate to send an e-mail: 

Niyati, nchhaya [AT] adobe.com

Kokil, jaidka [AT] sas.upenn.edu 

Jiahui, jhlu [AT] ntu.edu.sg






## Check out the FAQ! (TO BE RELEASED)

Please "WATCH" this repository! We may be pushing more updates in the following weeks.
After the Shared Task, we also plan to further enrich this data, with more annotations, meta-features and trained classifiers to aid with downstream applications.

If you use the data and publish, please let us know and cite our CL-Aff overview paper:

@inproceedings

{TBA
}


## Acknowledgement

We're grateful to the Pushshift API and Jason Baumgartner for the code that made this task possible. Thank you!


## Organizers

Kokil Jaidka, Nanyang Technological University

Niyati Chhaya , Big Data Experience Lab, Adobe Research

Jiahui Lu, Nanyang Technological University

Iknoor Singh, Panjab University

Lyle Ungar, University of Pennsylvania

Check out the Workshop and Shared Task website: <a>https://sites.google.com/view/affcon2020/home</a>



