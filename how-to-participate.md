# How to Participate
**! Coming soon** --- instructions on how to participate.


### Track 1: Better Annotators
Participants will submit 100 "official" question answering (QA) examples through the [Dynabench](https://dynabench.org/tasks/qa){:target="_blank"} platform. The collected dataset will form parts of the evaluation set for Tracks 2 and 3. The objective is to find as many model-fooling examples as possible -- the winning team will be the one with the highest validated model error rate (vMER). 

### Track 2: Better Training Data
In this data-centric track, participants will submit 1000 **training** examples (in SQuAD v1.1 JSON format, see [https://huggingface.co/datasets/adversarial_qa#dataset-structure](https://huggingface.co/datasets/adversarial_qa#dataset-structure){:target="_blank"}). These examples can be selected from existing datasets, expert-annotated, crowdsourced, or synthetically-generated. The workshop organisers will then train ELECTRA-Large models and evaluate them on the evaluation data collected in Track 1. The team with the highest word-overlap F1 score will be considered the winner.    

### Track 3: Better Models
The workshop organisers will pre-specify a set of evaluation weights for the [Dynabench](https://dynabench.org/tasks/qa){:target="_blank"} QA leaderboard. Participants can train any models on any data and submit their models directly to [Dynabench](https://dynabench.org/tasks/qa){:target="_blank"}. The team with the highest **dynascore** will be considered the winner.
