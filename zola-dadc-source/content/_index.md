+++
title = "The First Workshop on Dynamic Adversarial Data Collection (DADC)"
+++
# The First Workshop on Dynamic Adversarial Data Collection (DADC)
-----------------------------------------------------------------------------

The DADC Workshop '22 will be held on the <span style="font-weight: bold;">14<sup>th</sup> July, 2022</span> and is co-located with NAACL at the [Hyatt Regency](https://g.page/HyattRegencySeattle?share) in Seattle, Washington. Along with the announcement of our shared task results, we have a fantastic line up of keynote talks and a diverse and controversial panel discussion planned. It's going to be a great event, see you there!

## <span style="color:#267CB9"> Invited Speakers </span>

<div class="invited-speakers">

### [Anna Rogers, University of Copenhagen](https://annargrs.github.io)
#### What kinds of questions have we been asking? A taxonomy for QA/RC benchmarks

{{ resize_image(path="static/img/anna-rogers.jpeg", width=100, height=100, op="scale") }}

This talk provides an overview of the current landscape of resources for Question Answering and Reading comprehension, highlighting the current lacunae for future work. I will also present a new taxonomy of "skills" targeted by QA/RC datasets and discuss various ways in which questions may be unanswerable.

<hr />


### [Sam Bowman, Assistant Professor, New York University & Visiting Researcher (Sabbatical), Anthropic](https://cims.nyu.edu/~sbowman/)
#### Why Adversarially-Collected Test Sets Don’t Work as Benchmarks

{{ resize_image(path="static/img/sambowman.jpeg", width=100, height=100, op="fill") }}

Dynamic and/or adversarial data collection can be quite useful as a way of collecting training data for machine-learning models, identifying the conditions under which these models fail, and conducting online head-to-head comparisons between models. However, it is essentially impossible to use these practices to build usable static benchmark datasets for use in evaluating or comparing future new models. I defend this point using a mix of conceptual and empirical points, focusing on the claims (i) that adversarial data collection can skew the distribution of phenomena such as to make it unrepresentative of the intended task, and (ii) that adversarial data collection can arbitrarily shift the rankings of models on its resulting test sets to disfavor systems that are qualitatively similar to the current state of the art.

<hr />


### [Jordan Boyd-Graber, Associate Professor, University of Maryland at College Park](http://users.umiacs.umd.edu/~jbg/)
#### Incentives for Experts to Create Adversarial QA and Fact-Checking Examples

{{ resize_image(path="static/img/jbg.png", width=100, height=100, op="scale") }}

I'll discuss two examples of our work putting experienced writers in
front of a retrieval-driven adversarial authoring system: question
writing and fact-checking.  For question answering, we develop a
retrieval-based adversarial authoring platform and create incentives
to get people to use our system in the first place, write
interesting questions humans can answer, and challenge a QA system.
While the best humans lose to computer QA systems on normal questions,
computers struggle to answer our adversarial questions.  We then turn
to fact checking, creating a new game (Fool Me Twice) to solicit
difficult-to-verify claims---that can be either true or false---and to
test how difficult the claims are both for humans and computers.  We
argue that the focus on retrieval is important for knowledge-based
adversarial examples because it highlights diverse information,
prevents frustration in authors, and takes advantage of users'
expertise.

<hr />


### [Lora Aroyo, Research Scientist, Google](https://lora-aroyo.org)
#### Data Excellence: Better Data for Better AI

{{ resize_image(path="static/img/lora-aroyo.jpg", width=100, height=100, op="fill") }}

The efficacy of machine learning (ML) models depends on both algorithms and data. Training data defines what we want our models to learn, and testing data provides the means by which their empirical progress is measured. Benchmark datasets define the entire world within which models exist and operate, yet research continues to focus on critiquing and improving the algorithmic aspect of the models rather than critiquing and improving the data with which our models operate. If “data is the new oil,” we are still missing work on the refineries by which the data itself could be optimized for more effective use. In this talk, I will discuss data excellence and lessons learned from software engineering to achieve the scare and rigor in assessing data quality.

<hr />


### [Sherry Tongshuang Wu, Assistant Professor, Carnegie Mellon University (CMU HCII)](https://homes.cs.washington.edu/~wtshuang/)
#### Model-in-the-loop Data Collection: What Roles does the Model Play?

{{ resize_image(path="static/img/sherry-wu.jpeg", width=100, height=100, op="fill") }}

Assistive models have been shown useful for supporting humans in creating challenging datasets, but how exactly do they help? In this talk, I will discuss different roles of assistive models in counterfactual data collection (i.e., perturbing existing text inputs to gain insight into task model decision boundaries), and the characteristics associated with these roles. I will use three examples (CheckList, Polyjuice, Tailor) to demonstrate how our objectives shift when we perturb texts for evaluation, explanation, and improvement, and how that change the corresponding assistive models from enhancing human goals (requiring model controllability) to competing with human bias (requiring careful data reranking). I will conclude by exploring additional roles that these models can play to become more effective.

<hr />

</div>


## <span style="color:#267CB9">Program (14<sup>th</sup> July, 2022)</span>

<span class="time">09:00 – 09:10:</span> Opening remarks

<span class="time">09:10 – 09:45:</span> Invited Talk 1: Anna Rogers

<span class="time">09:45 – 10:20:</span> Invited Talk 2: Jordan Boyd-Graber

<span class="time">10:20 – 10:35:</span> Collaborative Progress: [MLCommons](https://mlcommons.org/) Introduction

<span class="time">10:35 – 10:50:</span> Coffee Break

<span class="time">10:50 – 11:10:</span> Best Paper Talk: Margaret Li and Julian Michael

<span class="time">11:10 – 11:45:</span> Invited Talk 3: Sam Bowman

<span class="time">11:45 – 12:20:</span> Invited Talk 4: Sherry Tongshuang Wu

<span class="time">12:20 – 13:20:</span> Lunch

<span class="time">13:20 – 13:55:</span> Invited Talk 5: Lora Aroyo

<span class="time">13:55 – 14:55:</span> Panel on The Future of Data Collection moderated by [Adina Williams](https://wp.nyu.edu/adinawilliams/). Panelists: [Anna Rogers](https://annargrs.github.io/), [Jordan Boyd-Graber](http://users.umiacs.umd.edu/~jbg/), [Sam Bowman](https://cims.nyu.edu/~sbowman/), [Sherry Tongshuang Wu](https://homes.cs.washington.edu/~wtshuang/), [Lora Aroyo](https://lora-aroyo.org/), [Douwe Kiela](https://douwekiela.github.io/) & [Swabha Swayamdipta](https://swabhs.com/).

<span class="time">14:55 – 15:10:</span> Coffee Break

<span class="time">15:10 – 15:20:</span> Shared Task Introduction: Max Bartolo

<span class="time">15:20 – 15:30:</span> Shared Task Presentations: Team Fireworks

<span class="time">15:30 – 15:40:</span> Shared Task Presentations: Team Longhorns

<span class="time">15:40 – 15:50:</span> Shared Task Presentations: Team Supersamplers

<span class="time">15:50 – 16:50:</span> Poster Session

<span class="time">16:50 – 17:00:</span> Closing Remarks

<span class="time">18:30 – 21:30:</span> The DADC Social Event

<hr />

## Latest News: 
* **Jun 9, 2022**: The Shared Task [Track 2](/shared-task/#track-2-better-training-data) dataset submission form is now open at [https://forms.gle/icJ5cijHtd9b4UmL6](https://forms.gle/icJ5cijHtd9b4UmL6).
* **Jun 8, 2022**: The Shared Task System Description Papers submission form is now open at [https://forms.gle/iEq4nGp9miy81Qn7A](https://forms.gle/iEq4nGp9miy81Qn7A).
* **May 22, 2022**: The Official Example Creation Window for [Track 1](/shared-task/#track-1-better-annotators) is now closed. Congratulations and good luck to all the participants!
* **May 2, 2022**: The Official Example Creation Window for [Track 1](/shared-task/#track-1-better-annotators) is now live on the [Dynabench](https://dynabench.org/tasks/qa) platform. To participate, [register your details here](https://docs.google.com/forms/d/e/1FAIpQLSfKXEFdkgkvxzZfvtT7EXhmzHjpzTYldca76Fd4P8APfvyGBA/viewform). 
* **April 25, 2022**: The DADC Shared Task [registration](https://docs.google.com/forms/d/e/1FAIpQLSfKXEFdkgkvxzZfvtT7EXhmzHjpzTYldca76Fd4P8APfvyGBA/viewform) deadline has been extended to May 15, 2022. [Sign up](https://docs.google.com/forms/d/e/1FAIpQLSfKXEFdkgkvxzZfvtT7EXhmzHjpzTYldca76Fd4P8APfvyGBA/viewform) today!
* **April 22, 2022**: We are delighted to announce that the awesome folks at [MLCommons](https://mlcommons.org/en/) will be sponsoring the DADC workshop! Their support will allow us to award prizes for the [shared task](shared-task/) winners as well as a best paper award 🏆!
* **April 7, 2022**: Following extensions by other NAACL workshops, we have also decided to extend the submission deadline for papers from April 8 to April 15. We look forward to your submissions! Submit at [https://openreview.net/group?id=aclweb.org/NAACL/2022/Workshop/DADC](https://openreview.net/group?id=aclweb.org/NAACL/2022/Workshop/DADC). 
* **March 29, 2022**: The [OpenReview DADC workshop page](https://openreview.net/group?id=aclweb.org/NAACL/2022/Workshop/DADC) is now open and accepting paper submissions!
* **March 23, 2022**: The DADC Shared Task [Call for Participation](/shared-task/) is now live! To register your team's interest, fill out the [registration form](https://docs.google.com/forms/d/e/1FAIpQLSfKXEFdkgkvxzZfvtT7EXhmzHjpzTYldca76Fd4P8APfvyGBA/viewform).
* **February 14, 2022**: See our [Call for Papers here](/call-for-papers/)!

## The DADC Shared Task
The DADC Shared Task this year will focus on the Extractive Question Answering (QA) task. We have three (3) tracks focusing on better annotators, better training data and better models.

**Specific details and a call for participation can be found [here](/shared-task/). Here's a quick overview:** 

### Track 1: Better Annotators
Participants will submit 100 "official" question answering (QA) examples through the [Dynabench](https://dynabench.org/tasks/qa) platform. The collected dataset will form parts of the evaluation set for Tracks 2 and 3. The objective is to find as many model-fooling examples as possible -- the winning team will be the one with the highest validated model error rate (vMER).

If you think you have what it takes to fool our best AI model, [sign up](https://docs.google.com/forms/d/e/1FAIpQLSfKXEFdkgkvxzZfvtT7EXhmzHjpzTYldca76Fd4P8APfvyGBA/viewform) today!

### Track 2: Better Training Data
In this data-centric track, participants will submit 10,000 **training** examples (in SQuAD v1.1 JSON format, see [https://huggingface.co/datasets/adversarial_qa#dataset-structure](https://huggingface.co/datasets/adversarial_qa#dataset-structure)). These examples can be selected from existing datasets, expert-annotated, crowdsourced, or synthetically-generated. The workshop organisers will then train ELECTRA-Large models and evaluate them on the data collected in Track 1. The team with the highest word-overlap F1 score on the test set will be considered the winner.    

### Track 3: Better Models
The workshop organisers have pre-specified a set of evaluation weights for the [Dynabench](https://dynabench.org/tasks/qa) QA leaderboard. Participants can train any models on any data and submit their models directly to [Dynabench](https://dynabench.org/tasks/qa). The team with the highest **dynascore** will be considered the winner.

### Overall
Teams can choose to participate on individual tracks only. To further encourage the formation of diverse teams working on a range of challenges, we will also have an overall DADC Shared Task Winning Team based on performance across all 3 tracks.

<form action="https://docs.google.com/forms/d/e/1FAIpQLSfKXEFdkgkvxzZfvtT7EXhmzHjpzTYldca76Fd4P8APfvyGBA/viewform" method="get" target="_blank"><button class="btn btn-success" type="submit">Sign up</button></form>
<br />

## Submission Information

The [OpenReview DADC workshop page](https://openreview.net/group?id=aclweb.org/NAACL/2022/Workshop/DADC) is now open and accepting paper submissions. 
The paper commitment page for work already having ARR reviews will be coming shortly.
Papers should follow the official [*ACL Paper Styles](https://github.com/acl-org/acl-style-files) and [paper formatting guidelines](https://acl-org.github.io/ACLPUB/formatting.html#paper-format) (also see [Overleaf template](https://www.overleaf.com/read/crtcwgxzjskr)).

For more information, refer to the [Call for Papers](/call-for-papers/) page.
<br />


## Organizers

### Core Team

* [Max Bartolo](http://bartolo.ai/)
* [Hannah Rose Kirk](https://www.hannahrosekirk.com/)
* [Pedro Rodriguez](https://www.pedro.ai)
* [Katerina Margatina](https://katerinamargatina.github.io/)
* [Tristan Thrush](http://www.tristanthrush.com/)
* [Robin Jia](https://robinjia.github.io/)

### Advisory Committee

* [Pontus Stenetorp](https://pontus.stenetorp.se/)
* [Adina Williams](https://wp.nyu.edu/adinawilliams/)
* [Douwe Kiela](https://douwekiela.github.io/)

### Program Committee

* Giorgos Vernikos, EPFL & HEIG-VD
* John P. Lalor, University of Notre Dame
* Maharshi Gor, University of Maryland, College Park
* Pasquale Minervini, University College London
* Paul Röttger, University of Oxford
* Shi Feng, University of Maryland, College Park
* Unso Eun Seo Jo, Stanford University & HuggingFace

[//]: # (* Chen Zhao)

[//]: # ()
[//]: # (* Maharshi Gor)

[//]: # ()
[//]: # (* Johnny Wei)

[//]: # ()
[//]: # (* Maximilian Mozes)

[//]: # ()
[//]: # (* Joe Barrow)

[//]: # ()
[//]: # (* Yixin Nie)

[//]: # ()
[//]: # (* Candace Ross)

[//]: # ()
[//]: # (* Mohit Bansal)

[//]: # ()
[//]: # (* Bertram Vidgen)

[//]: # ()
[//]: # (* Scott Hale)

[//]: # ()
[//]: # (* Zeerak Talat)

[//]: # ()
[//]: # (* Amanpreet Singh)

[//]: # ()
[//]: # (* Atticus Geiger)

[//]: # ()
[//]: # (* Christopher Potts)

[//]: # ()
[//]: # (* Ethan Perez)

[//]: # ()
[//]: # (* Scott Yih)

[//]: # ()
[//]: # (* Sebastian Riedel)

[//]: # ()
[//]: # (* Eric Wallace)

[//]: # ()
[//]: # (* Joao Sedoc)

[//]: # ()
[//]: # (* John P. Lalor)

[//]: # ()
[//]: # (* Phu Mon Htut)

## Contact

Please join our [mailing list](https://groups.google.com/u/0/g/dadc-workshop) to get important updates. If you have any questions, please contact `dadc-workshop@googlegroups.com`.

<hr />

## Sponsors
We would like to thank our generous sponsors for their help and support.

### Platinum Sponsors

<a href="https://mlcommons.org/en/" target="_blank"><img src="/img/mlc_logo.png" width="320px" /></a>

### Gold Sponsors

<a href="https://ai.facebook.com/" target="_blank"><img src="/img/meta_logo.png"  width="240px"/></a>
