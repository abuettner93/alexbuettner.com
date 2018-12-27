+++
title = "Clinical Dataset Analysis and Patient Outcome Prediction via Machine Learning"
date = 2018-12-19T15:10:34-07:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Alex Buettner"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["5"]

# Publication name and optional abbreviated version.
publication = "Masters Thesis, University of Nevada, Reno"
publication_short = ""

# Abstract and optional shortened version.
abstract = "We analyze and evaluate relevant machine learning methods for use in extracting
and understanding clinical data sets in the context of optimization of clinical
processes. Three data sets were considered to demonstrate the types and style of
data found in the healthcare field: (a) the Pima Indians diabetes dataset
(PIDD), a non-time-dependent diabetes onset study, (b) an alcoholism EEG dataset
(AED), studying responses of alcoholic and control subjects when exposed to
image stimulus, and (c) the diabetes readmission dataset (DRD), that focuses on
factors that relate to diabetic patient readmission times. Each dataset is
modeled using a variety of machine learning methods, including Bayesian, neural
network, and decision tree methods, to better understand the advantages and
disadvantages as applicable to rapid dependency extraction and understanding of
the information contained therein. The goal of this work is to analyze the
potential of machine learning for use in management of clinical processes and
operations. Neural network models are used to assess all three data sets; two
using dense neural networks, and one using convolutional neural networks. The
dense neural network model used on the PIDD resulted in a maximum prediction
accuracy of 81.77%. In contrast, the use of neural network (NN) models on the
much larger DRD demonstrated some drawbacks that were not expected upon initial
analysis of the data. We found that the NN model performs poorly on this
dataset, with classification accuracy no higher than 61.17%, due to the
complexity of the dataset and potential need for more data. The use of
convolutional neural networks for analysis of time series data was demonstrated
on the alcoholism EEG dataset, resulting i in subject classification accuracies
between 91.41% and 98.82% depending on the training and testing sets used to
analyze the model. Bayesian methods are used to analyze all three datasets, both
in supervised and unsupervised manners. Supervised learning analysis on the PIDD
showed improvement over published results, but are generally in agreement with
the literature. Classifications accuracies of resulted in a maximum of 84.49% on
a preprocessed dataset, and 79.75% on an unmodified dataset. Similarly,
supervised learning was applied to the DRD, resulting in maximum classification
accuracies on a three-class and two-class model of 58% and 62%, respectively.
Unsupervised Bayesian methods are applied to the alcoholism EEG dataset in order
to extract the true number of classes present in the model, in which all trials
correctly identified two subject classes without the aid of labeling. Hidden
Markov models are also applied to the alcoholism EEG dataset in an unsupervised
fashion, allowing us to extract characteristic states in each EEG sample, for
each subject class. The PIDD and DRD sets are also processed using decision tree
models; gradient boosting classifiers (GBC) are applied to the PIDD, and extreme
gradient boosting classifiers (XGBC) are applied to the DRD. The GBC model used
to analyze the PIDD resulted in a maximum classification accuracy of 82.48% on
preprocessed data, and 80.60% on an unmodified dataset. The DRD showed
difficulty in model development, with maximum classification accuracy reaching
approximately 55%, and with insensitivity to two of three data labels. The model
seems unable to capture the components of the third class, showing that the
distinguishability of the classes may be lacking."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = ["machine_learning"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["machine-learning", "optimization", "big data", "flow models", "healthcare", "patient-centered"]

# Links (optional).
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "View Thesis", url = "http://unr.idm.oclc.org/login?url=https://search.proquest.com/docview/304445874?accountid=452"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
