# Project

You will send me a series of Jupyter notebooks that consist in three parts :

1. Presentation of your dataset
2. Description of your dataset
3. Modeling on your dataset

## Presentation of the dataset

With some text and images, present the dataset you work on, based on the presentation you gave in front of your peers (on Friday 21st October), enriched with their feedbacks and questions.

You should inform the reader on what the dataset contains, where it comes from, who collected the data, its intended use, its known uses etc.
You should also explain why this dataset matters, to you and your readers (eg. professionals from your area of expertise).

## Description of the dataset

Present a descriptive analysis of your dataset, with a number of dataviz showing :

- the distribution of certains columns (eg. histograms, stacked bar charts...),
- the joint distribution of pairs of columns (eg. pair plots, scatter plots...),

on the whole dataset, or on relevant subgroups.

Comment on each dataviz and explain why it is interesting and relevant (what it shows that was or was not expected, what new information it suggests or confirms...).
Your goal here should be to provide a global view of the dataset, and exhibit salient features that are of interest for an analyst or stakeholder in this sector.

## Modelling

Define a problem, in the form of a classification or regression task, for which you want to build a [predictive model in a supervised manner](https://scikit-learn.org/stable/supervised_learning.html), or an [outlier detection task](https://scikit-learn.org/stable/modules/outlier_detection.html).
Then split your dataset in a training and test sets (or train, dev and test), build such a model, perform [cross-validation](https://scikit-learn.org/stable/modules/cross_validation.html), [evaluate its performance](https://scikit-learn.org/stable/modules/model_evaluation.html) and if relevant [plot scores](https://scikit-learn.org/stable/modules/learning_curve.html).

If your attempts at defining a relevant classification, regression or outlier detection task fail, try to perform advanced exploratory data analysis using [clustering algorithms](https://scikit-learn.org/stable/modules/clustering.html#clustering).

If all of your attempts failed, you need to present in detail what leads you explored and for each such lead, explain why it turned out to be impossible or a bad idea.
Then, instead of a model, define a complex but readable dataviz on your dataset, comment on it and explain the additional insights it provides.

## Delivery

You need to send your set of notebooks by email :

- to <mathieu@datactivist.coop>
- before Monday 21st November (2022-11-21), 10am (Paris timezone).
