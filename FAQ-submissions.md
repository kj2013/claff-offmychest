1. What should be the format of the submission file for Task 1?

csv, with fields as:
sentenceid,Emotional_disclosure,Information_disclosure,Support,General_support,Info_support,Emo_support


2. There are 2 subtasks(semi-supervised and unsupervised) specified in the shared task. Do participants have to do both - or is one of them okay?

Since Task 2 is open ended, we encourage participants to use it, at the very least, to descibe their solution approach for Task 1, or the insights which their solution approach provided about the dataset. 


3. What needs to be submitted by Nov 30? What if my system design changes from the Abstract I submitted earlier?

It's ok if you change your approach later on. 


4. What’s the format and minimum pages of the paper (Shared Task Report)?
 
 No minimum pages; maximum page limit of 10 pages. Please follow the LNCS publication guidelines. We'll be publishing an open-access proceedings at http://ceur-ws.org/HOWTOSUBMIT.html


5. What results should we report in the system paper?

For Task 1: Evaluation using 10-fold cross validation  on the training dataset.

For Task 2: method, description, insights, whatever else you want to include, since this is open-ended.


6. What results need to be uploaded? 

Your system's outputs for Task 1 on the test set (which is unlabeled).


7. Where should I upload this file?

 We've added a new field to EasyChair to let you submit your system runs there. In case that doesn't work, you can email us.


8. Should the submission file for Task 1 be sent directly to email?

 We've added a new field to EasyChair to let you submit your system runs there. In case that doesn't work, you can email us.


9. What is the evaluation criteria for Task 1 and Task 2?

Evaluation (Task 1): Accuracy, F1, Precision-1, Recall-1 for each of the fields and also an overall average

Evaluation (Task 2): Subjective, based on qualitative characteristics.


10. What do you mean by "system runs"? is it a deployed model that takes an input and predict the output?

Yes!


11. How many runs (prediction sets) can we submit for the Cl-Aff test set (Task 1)?

A maximum of ten, please.

 
12. What do we submit for task 2?

Results for Task 2 should be a part of the main paper, we do not need any system runs for those.


13. When will we know our performance on the test set?

At the workshop, or in the weeks leading up to the workshop. The overview paper of the Shared Task will rank all the systems on their performance on the test set.


14. Is the peer review of submissions blind? What is the process of the peer review?

It will not be blind -- we will send around the pdf assignments and participants will submit their feedback. Everyone will know who got their paper and who reviewed their paper.


15. Can we utilize the unlabeled data you have posted, for training our models?

Sure go ahead. If you find anything else (not in the GitHub) useful, that would be great too.


16. Can we use pretrained models or pretrained embeddings?

Yes!


17. What is the rationale used when the labels for agency and social are given?

Please check our documentation and coding scheme. We'll try to update any information that's not yet up. The labels were chosen based on inter-coder agreement, so there is only a consensus, not a ground truth. It is even possible that you don't agree with the majority.


18. There's a glitch in the test data!

Email us, we'll take care of it. We may exclude that data point from analysis, but will not be releasing a fresh test set right now.
