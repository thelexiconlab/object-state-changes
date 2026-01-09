# Repository Guide

This repository contains the data, experiment code, and analysis scripts for the manuscript *Representing object state change during sentence comprehension: Boundary conditions and language-specific constraints*. In this work, we failed to replicate this sentence-picture match effect found by Horchak and Garrido (2021). To explore this non-replication, we designed three pre-registered extensions to examine the effects of another type of state change (slicing, Experiment 2), the role of implicit target object properties (squashability, Experiment 3), and the role of syntactic structure (sentence focus, Experiment 4). Contrary to previous work, we only observed a match effect on response times in Experiment 4, and only when the target object was the focus (i.e., subject) of the sentence. A follow-up survey comparing readers’ interpretation of the original Portuguese stimuli and English translations corroborated the interpretation that the syntactic structure of Portuguese led to relatively more salient representations of the objects described in the state change event. Overall, these findings suggest that the representation of object state changes during language comprehension depends on the interaction of object properties and language-specific syntactic constraints.

## Navigation

Within the main (experiments) folder, there are separate folders that correspond to each experiment (Experiment 1 - 4b). Within each experiment folder, materials and code used to conduct the experiment (using jspsych) can be found in the /experiment_code subfolder. Data for each experiment can be found in the /data subfolder within each experiment. Analysis scripts (R notebooks) can be found in the /analysis subfolders.

## Data CSV Guide

Experiment 1 (preregistered.csv):
subject = Subject ID
rt = Verification Time (in ms)
correct = Accuracy (True/False)
typeoftrial = Trial Type, critical trials = picture
trialcondition = Condition (Sentence Weight x Object State or Filler)
sentence = Specific sentence stimulus
object = Specific image stimulus

Experiment 2:
subject = Subject ID
rt = Verification Time (in ms)
correct = Accuracy (True/False)
typeoftrial = Trial Type, critical trials = picture
trialcondition = Condition (Sentence Verb x Object State or Filler)
sentence = Specific sentence stimulus
object = Specific image stimulus

Experiment 3:
subject = Subject ID
rt = Verification Time (in ms)
correct = Accuracy (True/False)
typeoftrial = Trial Type, critical trials = picture
trialcondition = Condition (Squashability x Object State or Filler)
sentence = Specific sentence stimulus
object = Specific image stimulus

Experiments 4a and 4c:
subject = Subject ID
rt = Verification Time (in ms)
correct = Accuracy (True/False)
typeoftrial = Trial Type, critical trials = picture
trialcondition = Condition (Sentence Weight x Object State x Focus or Filler)
sentence = Specific sentence stimulus
object = Specific image stimulus
