# The First Workshop on Dynamic Adversarial Data Collection (DADC)
-----------------------------------------------------------------------------

## Latest News: 
* **May 2, 2022**: The Official Example Creation Window for [Track 1](/shared-task.html#track-1-better-annotators) is now live on the [Dynabench](https://dynabench.org/tasks/qa){:target="_blank"} platform. To participate, [register your details here](https://docs.google.com/forms/d/e/1FAIpQLSfKXEFdkgkvxzZfvtT7EXhmzHjpzTYldca76Fd4P8APfvyGBA/viewform){:target="_blank"}. 
* **April 25, 2022**: The DADC Shared Task [registration](https://docs.google.com/forms/d/e/1FAIpQLSfKXEFdkgkvxzZfvtT7EXhmzHjpzTYldca76Fd4P8APfvyGBA/viewform){:target="_blank"} deadline has been extended to May 15, 2022. [Sign up](https://docs.google.com/forms/d/e/1FAIpQLSfKXEFdkgkvxzZfvtT7EXhmzHjpzTYldca76Fd4P8APfvyGBA/viewform){:target="_blank"} today!
* **April 22, 2022**: We are delighted to announce that the awesome folks at [MLCommons](https://mlcommons.org/en/){:target="_blank"} will be sponsoring the DADC workshop! Their support will allow us to award prizes for the [shared task](shared-task.html) winners as well as a best paper award 🏆!
* **April 7, 2022**: Following extensions by other NAACL workshops, we have also decided to extend the submission deadline for papers from April 8 to April 15. We look forward to your submissions! Submit at [https://openreview.net/group?id=aclweb.org/NAACL/2022/Workshop/DADC](https://openreview.net/group?id=aclweb.org/NAACL/2022/Workshop/DADC){:target="_blank"}. 
* **March 29, 2022**: The [OpenReview DADC workshop page](https://openreview.net/group?id=aclweb.org/NAACL/2022/Workshop/DADC){:target="_blank"} is now open and accepting paper submissions!
* **March 23, 2022**: The DADC Shared Task [Call for Participation](/shared-task.html) is now live! To register your team's interest, fill out the [registration form](https://docs.google.com/forms/d/e/1FAIpQLSfKXEFdkgkvxzZfvtT7EXhmzHjpzTYldca76Fd4P8APfvyGBA/viewform){:target="_blank"}.
* **February 14, 2022**: See our [Call for Papers here](/call-for-papers.html)!

## The DADC Shared Task
The DADC Shared Task this year will focus on the Extractive Question Answering (QA) task. We have three (3) tracks focusing on better annotators, better training data and better models.

**Specific details and a call for participation can be found [here](/shared-task.html). Here's a quick overview:** 

### Track 1: Better Annotators
Participants will submit 100 "official" question answering (QA) examples through the [Dynabench](https://dynabench.org/tasks/qa){:target="_blank"} platform. The collected dataset will form parts of the evaluation set for Tracks 2 and 3. The objective is to find as many model-fooling examples as possible -- the winning team will be the one with the highest validated model error rate (vMER).

If you think you have what it takes to fool our best AI model, [sign up](https://docs.google.com/forms/d/e/1FAIpQLSfKXEFdkgkvxzZfvtT7EXhmzHjpzTYldca76Fd4P8APfvyGBA/viewform){:target="_blank"} today!

### Track 2: Better Training Data
In this data-centric track, participants will submit 10,000 **training** examples (in SQuAD v1.1 JSON format, see [https://huggingface.co/datasets/adversarial_qa#dataset-structure](https://huggingface.co/datasets/adversarial_qa#dataset-structure){:target="_blank"}). These examples can be selected from existing datasets, expert-annotated, crowdsourced, or synthetically-generated. The workshop organisers will then train ELECTRA-Large models and evaluate them on the data collected in Track 1. The team with the highest word-overlap F1 score on the test set will be considered the winner.    

### Track 3: Better Models
The workshop organisers have pre-specified a set of evaluation weights for the [Dynabench](https://dynabench.org/tasks/qa){:target="_blank"} QA leaderboard. Participants can train any models on any data and submit their models directly to [Dynabench](https://dynabench.org/tasks/qa){:target="_blank"}. The team with the highest **dynascore** will be considered the winner.

### Overall
Teams can choose to participate on individual tracks only. To further encourage the formation of diverse teams working on a range of challenges, we will also have an overall DADC Shared Task Winning Team based on performance across all 3 tracks.

<form action="https://docs.google.com/forms/d/e/1FAIpQLSfKXEFdkgkvxzZfvtT7EXhmzHjpzTYldca76Fd4P8APfvyGBA/viewform" method="get" target="_blank"><button class="btn btn-success" type="submit">Sign up</button></form>
<br />

## Submission Information

The [OpenReview DADC workshop page](https://openreview.net/group?id=aclweb.org/NAACL/2022/Workshop/DADC){:target="_blank"} is now open and accepting paper submissions. 
The paper commitment page for work already having ARR reviews will be coming shortly.
Papers should follow the official [*ACL Paper Styles](https://github.com/acl-org/acl-style-files){:target="_blank"} and [paper formatting guidelines](https://acl-org.github.io/ACLPUB/formatting.html#paper-format){:target="_blank"} (also see [Overleaf template](https://www.overleaf.com/read/crtcwgxzjskr){:target="_blank"}).

For more information, refer to the [Call for Papers](/call-for-papers.html) page.
<br />

## Important Dates (Paper Submission)

| <!-- -->                                           | <!-- -->                                               |
|:---------------------------------------------------| :----------------------------------------------------- |
| **February 14, 2022**                              | First [Call for Workshop Papers](call-for-papers.html) |
| **April** <del>8</del> **<ins>15</ins>, 2022**     | Submission deadline (papers requiring peer review)     |
| **May** <del>1</del> **<ins>6</ins>, 2022**        | Submission deadline (papers with ARR reviews)          |
| **May** <del>1</del> **<ins>6</ins>, 2022**        | Submission deadline (non-archival papers)              |
| **May** <del>6</del> **<ins>13</ins>, 2022**       | Notification of Acceptance                             |
| **May** <del>20</del> **<ins>27</ins>, 2022**      | Camera-ready Papers Due                                |
| **July 14-15, 2022**                               | Workshop Dates at NAACL 2022                           |

## Important Dates (Shared Task)

| <!-- -->                                          | <!-- -->                                                                                                                                            |
|:--------------------------------------------------| :-------------------------------------------------------------------------------------------------------------------------------------------------- |
| <del>April 25</del> **<ins>May 15</ins>, 2022**   | [Team Registration](https://docs.google.com/forms/d/e/1FAIpQLSfKXEFdkgkvxzZfvtT7EXhmzHjpzTYldca76Fd4P8APfvyGBA/viewform){:target="_blank"} Deadline |
| **May 2 - 15, 2022**                              | Official Example Creation Window for [Track 1](/shared-task.html#track-1-better-annotators)                                                         |
| **June 3, 2022**                                  | [Track 2](/shared-task.html#track-2-better-training-data) Submission Deadline                                                                       |
| **June 3, 2022**                                  | [Track 3](/shared-task.html#track-3-better-models) Submission Deadline                                                                              |
| **June 10, 2022**                                 | System Description Paper (Optional) Submission Deadline                                                                                             |
| **June 17, 2022**                                 | System Description Paper Notification of Acceptance                                                                                                 |
| **June 17, 2022**                                 | Results Announced                                                                                                                                   |
| **June 24, 2022**                                 | System Description Paper Camera-Ready Deadline                                                                                                      |
| **July 14-15, 2022**                              | Workshop Dates & Overall Winning Team Announcement 🏆                                                                                                |

<br />


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

<hr />

## Sponsors
We would like to thank our generous sponsors for their help and support.

### Platinum Sponsors

<a href="https://mlcommons.org/en/" target="_blank"><img src="/img/mlc_logo.png" width="320px" /></a>

### Gold Sponsors

<a href="https://ai.facebook.com/" target="_blank"><img src="/img/meta_logo.png"  width="240px"/></a>
