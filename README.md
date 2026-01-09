# Repository Guide

This repository contains the data, experiment code, and analysis scripts for the manuscript *Representing object state change during sentence comprehension: Boundary conditions and language-specific constraints*. In this work, we failed to replicate this sentence-picture match effect found by Horchak and Garrido (2021). To explore this non-replication, we designed three pre-registered extensions to examine the effects of another type of state change (slicing, Experiment 2), the role of implicit target object properties (squashability, Experiment 3), and the role of syntactic structure (sentence focus, Experiment 4).
## Navigation

Within the main (experiments) folder, there are separate folders that correspond to each experiment (Experiment 1 - 4c). Within each experiment folder, materials and code used to conduct the experiment (using jspsych) can be found in the /experiment_code subfolder. Data for each experiment can be found in the /data subfolder within each experiment. Analysis scripts (R notebooks) can be found in the /analysis subfolders. All key statistical analyses for each experiment are contained within the single _analysis.Rmd file for each experiment. Rmds for data cleaning and "sanity check" code used to validate the experiment are also included where relevant.

## Data CSV Guide

Experiment 1 (preregistered.csv):
subject = Subject ID,
rt = Verification Time (in ms),
correct = Accuracy (True/False),
typeoftrial = Trial Type, critical trials = picture,
trialcondition = Condition (Sentence Weight x Object State or Filler),
sentence = Specific sentence stimulus,
object = Specific image stimulus

Experiment 2:
subject = Subject ID,
rt = Verification Time (in ms),
correct = Accuracy (True/False),
typeoftrial = Trial Type, critical trials = picture,
trialcondition = Condition (Sentence Verb x Object State or Filler),
sentence = Specific sentence stimulus,
object = Specific image stimulus

Experiment 3:
subject = Subject ID,
rt = Verification Time (in ms),
correct = Accuracy (True/False),
typeoftrial = Trial Type, critical trials = picture,
trialcondition = Condition (Squashability x Object State or Filler),
sentence = Specific sentence stimulus,
object = Specific image stimulus

Experiments 4a and 4c:
subject = Subject ID,
rt = Verification Time (in ms),
correct = Accuracy (True/False),
typeoftrial = Trial Type, critical trials = picture,
trialcondition = Condition (Sentence Weight x Object State x Focus or Filler),
sentence = Specific sentence stimulus,
object = Specific image stimulus
