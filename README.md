**Problem Description:**

In NLP, accurately labelled data is scarce when dealing with specialized domains and internal business initiatives. NLP projects undertaken by businesses often deal with the lack of labelled data – especially when the business defines domain specific (e.g. internal) labels and cannot make use of pre-existing resources. In many cases, there is a need to rely on massive sets of hand-labelled domain-specific training data or large pre-trained language models.

**Context of the Problem:**

In the modern world, there is infinite availability of text document. Unfortunately, there is huge scarcity of meaningful labelled data. This issue magnifies in resource-poor languages and/or uncommon textual domains, also extended to projects without pre-existing datasets.

**Limitation About other Approaches:**

There are many ways to get more labeled training data however each have their own drawbacks.

* **Traditional Supervision (Hand-Labeled Data by Subject Matter Experts (SMEs))**

     Hand-labeled training datasets are expensive and time-consuming to create, and are not able to swiftly accommodate to change if new labelling guidelines are introduced. For example, if a new domain-specific label was introduced, a full review of the training data set would be required by SMEs.

* **Semi-supervised Learning (Use of structural assumptions on unlabeled data)**

     The semi-supervised learning approach takes a small labelled dataset and a large unlabelled dataset to extract structural assumptions. However, it needs some labeled data.

* **Transfer Learning (Use of pre-trained models)**

     Transfer Learning makes use of already existing pre-trained models and fine-tunes them on a different task. However, transfer learning only works if the initial and target problems are similar enough for the first round of training to be relevant. This is often not the case in cross sector NLP projects.

**Solution:**

The Skweak framework relies on weak supervision eliminating labelling data by hand. Skweak relies on weak supervision to programmatically label data points through a collection of labelling functions. Another feature of skweak is the ability to create labelling functions that produce underspecified labels.
