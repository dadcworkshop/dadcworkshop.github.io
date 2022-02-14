# The First Workshop on Dynamic Adversarial Data Collection (DADC)
-----------------------------------------------------------------------------

Latest News: See our [Call for Papers here](/call-for-papers.html)!

## Important Dates

| <!-- -->              | <!-- -->                                               |
|:----------------------|:-------------------------------------------------------|
| **February 14, 2022** | First [Call for Workshop Papers](call-for-papers.html) |
| **March 11, 2022**    | Second Call for Workshop Papers                        |
| **April 8, 2022**     | Submission deadline (papers requiring peer review)     |
| **May 1, 2022**       | Submission deadline (papers with ARR reviews)          |
| **May 1, 2022**       | Submission deadline (non-archival papers)              |
| **May 6, 2022**       | Notification of Acceptance                             |
| **May 20, 2022**      | Camera-ready Papers Due                                |
| **July 14-15, 2022**  | Workshop Dates at NAACL 2022                           |


## Overview of DADC Shared Task
The DADC Shared Task this year will focus on the Extractive Question Answering (QA) task. We hope to expand to other NLP-related tasks in future iterations of the competition.

**Specific details and a call for participation will be issued shortly. In the meantime, here's a taster of what we're planning:** 

### Track 1: Better Annotators
Participants will submit 100 "official" question answering (QA) examples through the [Dynabench](https://dynabench.org/tasks/qa){:target="_blank"} platform. The collected dataset will form parts of the evaluation set for Tracks 2 and 3. The objective is to find as many model-fooling examples as possible -- the winning team will be the one with the highest validated model error rate (vMER). 

### Track 2: Better Training Data
In this data-centric track, participants will submit 1000 **training** examples (in SQuAD v1.1 JSON format, see [https://huggingface.co/datasets/adversarial_qa#dataset-structure](https://huggingface.co/datasets/adversarial_qa#dataset-structure){:target="_blank"}). These examples can be selected from existing datasets, expert-annotated, crowdsourced, or synthetically-generated. The workshop organisers will then train ELECTRA-Large models and evaluate them on the evaluation data collected in Track 1. The team with the highest word-overlap F1 score will be considered the winner.    

### Track 3: Better Models
The workshop organisers will pre-specify a set of evaluation weights for the [Dynabench](https://dynabench.org/tasks/qa){:target="_blank"} QA leaderboard. Participants can train any models on any data and submit their models directly to [Dynabench](https://dynabench.org/tasks/qa){:target="_blank"}. The team with the highest **dynascore** will be considered the winner.

### Overall
Teams can choose to participate on individual tracks only. To further encourage the formation of diverse teams working on a range of challenges, we will also have an overall DADC Shared Task Winning Team based on performance across all 3 tracks.

## Organizers


### Core Team

* [Max Bartolo](http://bartolo.ai/){:target="_blank"}
* [Hannah Rose Kirk](https://www.hannahrosekirk.com/){:target="_blank"}
* [Pedro Rodriguez](https://www.pedro.ai){:target="_blank"}
* [Katerina Margatina](https://katerinamargatina.github.io/){:target="_blank"}
* [Tristan Thrush](http://www.tristanthrush.com/){:target="_blank"}
* [Mimansa Jaiswal](https://mimansajaiswal.github.io/){:target="_blank"}

### Advisory Committee

* [Pontus Stenetorp](https://pontus.stenetorp.se/){:target="_blank"}
* [Robin Jia](https://robinjia.github.io/){:target="_blank"}
* [Adina Williams](https://wp.nyu.edu/adinawilliams/){:target="_blank"}
* [Douwe Kiela](https://douwekiela.github.io/){:target="_blank"}

[//]: # (### Program Committee)

[//]: # ()
[//]: # (* Shi Feng)

[//]: # (* Paul Röttger)

[//]: # (* Chen Zhao)

[//]: # (* Maharshi Gor)

[//]: # (* Johnny Wei)

[//]: # (* Maximilian Mozes)

[//]: # (* Joe Barrow)

[//]: # (* Yixin Nie)

[//]: # (* Candace Ross)

[//]: # (* Mohit Bansal)

[//]: # (* Bertram Vidgen)

[//]: # (* Scott Hale)

[//]: # (* Zeerak Talat)

[//]: # (* Amanpreet Singh)

[//]: # (* Atticus Geiger)

[//]: # (* Christopher Potts)

[//]: # (* Ethan Perez)

[//]: # (* Scott Yih)

[//]: # (* Sebastian Riedel)

[//]: # (* Eric Wallace)

[//]: # (* Joao Sedoc)

[//]: # (* John P. Lalor)

[//]: # (* Phu Mon Htut)

## Contact

Please join our [mailing list](https://groups.google.com/u/0/g/dadc-workshop){:target="_blank"} to get important updates. If you have any questions, please contact `dadc-workshop@googlegroups.com`.
