+++
title = "Shared Task"
template = "page.html"
+++

# The DADC Shared Task
The DADC Shared Task this year will focus on the Extractive Question Answering (QA) task. We hope to expand to other NLP-related tasks in future iterations of the competition.

Register your team's interest in participating [here](https://docs.google.com/forms/d/e/1FAIpQLSfKXEFdkgkvxzZfvtT7EXhmzHjpzTYldca76Fd4P8APfvyGBA/viewform).


## How to Participate
### Track 1: Better Annotators
Participants will submit 100 "official" question answering (QA) examples through the [Dynabench](https://dynabench.org/tasks/qa) platform. The collected dataset will form parts of the evaluation set for Tracks 2 and 3. The objective is to find as many model-fooling examples as possible -- the winning team will be the one with the highest validated model error rate (vMER).

#### Participation Instructions
1. Create an "official" Dynabench account for your team (and share your account username with us when filling out the [Team Registration Form](https://docs.google.com/forms/d/e/1FAIpQLSfKXEFdkgkvxzZfvtT7EXhmzHjpzTYldca76Fd4P8APfvyGBA/viewform)).
2. Test out [Dynabench QA Interface](https://dynabench.org/tasks/qa/create). **Important: DO NOT use your "official" shared task account for this. We recommend that you either create personal test accounts or switch to Sandbox mode in the interface.**. You are free to interact with the model as often as you like from your *test* accounts to try to identify model failure patterns.
3. The actual submission will occur over a 2-week *Track 1 Example Creation* window. The organisers will provide a new set of annotation passages, but you will be competing against the [current best QA model](https://dynabench.org/models/109) which will remain the same as during the previous testing phase. Some rules regarding the official submission phase:
    * You should only submit **100** examples from your *official* participation account. If you submit more than 100, only the first 100 will be taken into consideration.
    * You will **NOT** be allowed to retract examples.
    * You **MUST provide explanations** for all your **model-fooling** examples only.
    * You are **NOT** allowed to use sandbox mode on passages for which you will submit questions to the competition.
4. Once the *Track 1 Example Creation* window is over, your submitted examples will get validated by an **expert validator**. Please refer to the [Validation Instructions](/shared-task/#validation-instructions) below for more information.
5. The winning team will be the one with the highest validated model error rate (vMER).
6. By participating, you agree to make any of the data you submit available for public release.

After validation and cleaning, this dataset will form part of the validation and testing for the other competition tracks.

#### Validation Instructions

1. Questions must have only one valid answer in the passage.
2. The shortest span which correctly answers the question is selected.
3. Questions can be correctly answered from a span in the passage and DO NOT require a Yes or No answer.
4. Questions can be answered from the content of the passage and DO NOT rely on expert external knowledge but can rely on *commonsense* knowledge (e.g. knowing that the sky is blue).
5. DO NOT ask questions about the passage structure such as *"What is the third word in the passage?"*.
6. There should be NO duplicate (or very similar) model-fooling questions. To ensure this, we require that all your model-fooling example for the same passage have different answers.
7. You *MUST provide explanations* for all your *model-fooling examples only*.
8. If the interface suggests that you didn't fool the model, but you actually consider the model to be fooled, please prepend the text **MODELFOOLED** to your explanation and then provide the explanation for why the model is fooled as normal. 

Valid examples should be questions about the content of the passage (not its structure) that the model answers incorrectly and a sufficiently well-trained human answers correctly.

These instructions may be updated by the workshop organisers prior to the start of the *Track 1 Example Creation* window.


### Track 2: Better Training Data
In this data-centric track, participants will submit 10,000 **training** examples (in SQuAD v1.1 JSON format, see [https://huggingface.co/datasets/adversarial_qa#dataset-structure](https://huggingface.co/datasets/adversarial_qa#dataset-structure)). These examples can be selected from existing datasets, expert-annotated, crowdsourced, or synthetically-generated. The workshop organisers will then train ELECTRA-Large models and evaluate them on the data collected in Track 1. The team with the highest word-overlap F1 score on the test set will be considered the winner.

To facilitate participation in this task, **we make a variety of resources available** including datasets, question generator models, and general tools and utilities at [https://github.com/dadcworkshop/shared-task-resources](https://github.com/dadcworkshop/shared-task-resources).

#### Participation Instructions
1. Each team must submit 10,000 **training** examples (in SQuAD v1.1 JSON format, see [https://huggingface.co/datasets/adversarial_qa#dataset-structure](https://huggingface.co/datasets/adversarial_qa#dataset-structure)). Submissions in the **wrong format** will be **disqualified**.
1. It is the team’s responsibility to ensure that all question IDs are unique.
1. Data can be self-annotated, selected from existing datasets, synthetically generated, crowdsourced, etc. Please also refer to the [DADC Shared Task resources](https://github.com/dadcworkshop/shared-task-resources).
1. The submitted data cannot include passages from the test set. These will be made available by the start of the *Track 1 Example Creation* window. Any examples for which we find significant overlap will be removed.
1. The **workshop organisers** will then train five (5) ELECTRA-Large models on your provided training dataset using the default 🤗 HuggingFace hyper-parameters and different random seeds (these will not be disclosed in advance).
1. We will create both a *validation* and *test* set from the *Track 1 Dataset* that will be used to determine which model checkpoint to use and evaluate these models.
1. We will evaluate word-overlap F1 score of each model on the *Track 1 Test Dataset*.
1. Your official result will be the median score of the **best 3 performing models (of the 5 trained)**.
1. The team with the highest word-overlap F1 score on the test set will be considered the winner.


### Track 3: Better Models
The workshop organisers have pre-specified a set of evaluation weights for the [Dynabench](https://dynabench.org/tasks/qa) QA leaderboard. Participants can train any models on any data and submit their models directly to [Dynabench](https://dynabench.org/tasks/qa). The team with the highest **dynascore** will be considered the winner.

#### Participation Instructions
1. Create an "official" Dynabench account for your team (and share your account username with us when filling out the [Team Registration Form](https://docs.google.com/forms/d/e/1FAIpQLSfKXEFdkgkvxzZfvtT7EXhmzHjpzTYldca76Fd4P8APfvyGBA/viewform)).
1. You may train any models on whatever data you want.
1. Models should be submitted directly to [Dynabench](https://dynabench.org/tasks/qa) using [Dynalab](https://github.com/facebookresearch/dynalab).
1. The official **dynaboard evaluation weights** we will use are:
    * QA F1: 4
        * aqa-r1-test: 5
        * dadc-track-1-test: 4
        * squad-dev: 3
    * Throughput: 1
    * Memory: 1
    * Fairness: 1
    * Robustness: 1
1. Kindly take note of the weighting allocated to the *Track 1 Test Dataset*, for which you will **NOT** be provided with a *validation* set.
1. The team with the highest **dynascore** will be considered the winner.

The workshop organisers refer the right to modify the official evaluation weights if required.

### Overall
Teams can choose to participate on individual tracks only. To further encourage the formation of diverse teams working on a range of challenges, we will also have an overall DADC Shared Task Winning Team based on performance across all 3 tracks.

Teams awarded points based on their position in each track:

| Team Rank | Points        |
| :-------- | :------------ |
| 1st       | **25 points** |
| 2nd       | **18 points** |
| 3rd       | **15 points** |
| 4th       | **12 points** |
| 5th       | **10 points** |
| 6th       | **8 points**  |
| 7th       | **6 points**  |
| 8th       | **4 points**  |
| 9th       | **2 points**  |
| 10th      | **1 point**   |

The team with the highest number of points overall will be the **DADC Shared Task Winning Team** 🏆.

## Important Dates

| <!-- -->                                        | <!-- -->                                                                                                                          |
|:------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------|
| <del>April 25</del> **<ins>May 22</ins>, 2022** | [Team Registration](https://docs.google.com/forms/d/e/1FAIpQLSfKXEFdkgkvxzZfvtT7EXhmzHjpzTYldca76Fd4P8APfvyGBA/viewform) Deadline |
| **May 2 - <del>15</del> <ins>22</ins>, 2022**   | Official Example Creation Window for [Track 1](/shared-task/#track-1-better-annotators)                                       |
| **June 3, 2022**                                | [Track 2](/shared-task/#track-2-better-training-data) Submission Deadline                                                     |
| **June 3, 2022**                                | [Track 3](/shared-task/#track-3-better-models) Submission Deadline                                                            |
| **June 10, 2022**                               | System Description Paper (Optional) Submission Deadline                                                                           |
| **June 17, 2022**                               | System Description Paper Notification of Acceptance                                                                               |
| **June 17, 2022**                               | Results Announced                                                                                                                 |
| **June 24, 2022**                               | System Description Paper Camera-Ready Deadline                                                                                    |
| **July 14, 2022**                               | Workshop Dates & Overall Winning Team Announcement 🏆                                                                             |
