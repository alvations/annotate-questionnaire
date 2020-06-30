# A Survey of NLP Annotation Platforms

This `README` is a summary of responses to questionnaire on annotation platforms (from https://forms.gle/iZk8kehkjAWmB8xe9). The questionnaire is a short survey on users' usage and wants of annotation for text and/or image processing for Natural Language Processing (NLP) tasks.

This summary is based on the results collated on 30 June 2020. We may update the results if there are significant no. of new responses after the stipulate dated in the previous sentence. 

The raw data for the survey results can be found on:

 - [`.csv` format](https://github.com/alvations/annotate-questionnaire/blob/master/NLP-Annotation-Platforms.csv)
 - [`.tsv` format](https://github.com/alvations/annotate-questionnaire/blob/master/NLP-Annotation-Platforms.tsv)
 - [`.xlsx` format](https://github.com/alvations/annotate-questionnaire/blob/master/NLP-Annotation-Platforms.xlsx)
 
# Overview

 - [**Population**](https://github.com/alvations/annotate-questionnaire/blob/master/README.md#population)
   - Population Breakdown
 - [**Annotations Requirements**](https://github.com/alvations/annotate-questionnaire/blob/master/README.md#annotations-requirements)
   - Why do you need annotations for your task/data?
   - What NLP tasks do you need annotation for?
   - Would the annotations you need require domain expertise or can it be handled by crowdsource workers with some minimum requirements?
   - Do you have a pool of trusted/expert annotators that can work on your annotation task(s)?
 - [**Annotation Platforms**](https://github.com/alvations/annotate-questionnaire/blob/master/README.md#annotation-platforms)
   - Have you used open source / commercial annotation platforms before? 
   - Which of these *open source* annotation platforms/tools have you ***used*** before?
   - Which of these *commercial* annotation platforms/tools have you ***heard*** before?
   - Which of these *commercial* annotation platforms/tools have you ***used*** before?
   - Most Useful Features
   - Suggestions to annotation tool creators
   - Any other feedback on annotation tools?
 - [**Your Dream Annotation Platform**](https://github.com/alvations/annotate-questionnaire/blob/master/README.md#your-dream-annotation-platform)
    - Notable Mentions about "Your Dream Anntoation Platform"
 - [**Acknowledgements**](https://github.com/alvations/annotate-questionnaire/blob/master/README.md#acknowledgement)
 
#  Population 

 - There are 78 responses to the questionnaire. 
 - **94.9% need _annotations_** for their work
 - **80.8% have used an _annotation platform_** before
 

## Population Breakdown

![](https://docs.google.com/spreadsheets/d/e/2PACX-1vTMa1QOjA4b45HvT3FKnRnfsgIpgjtjOb7RzJ8ZODJZ1vZr0ImtQ313CdAxcnSi3tXcHiXcXc-oUEoC/pubchart?oid=483246479&format=image)


   - 47.4% from academia
   - 34.6% from industry
   -  6.4% are students
   -  3.8% freelance/independent researchers
   -  1.3% government 
   - the rest comes from a mix of either of the above categories


# Annotations Requirements


## Why do you need annotations for your task/data?


![](https://docs.google.com/spreadsheets/d/e/2PACX-1vTMa1QOjA4b45HvT3FKnRnfsgIpgjtjOb7RzJ8ZODJZ1vZr0ImtQ313CdAxcnSi3tXcHiXcXc-oUEoC/pubchart?oid=1144655843&format=image)

 - **65.3% (of 78 respondents) can't find existing open datasets** that fit their needs
 - **53.8% (of 78 respondents) stated that there is no data in the domain** they're interested in
 - **47.4% (of 78 respondents) wants to explore new facet of data/task** that requires new annotations

 - **Others** reasons includes:
   - Data for low-resource languages doesn't exist (e.g. marginalised and indigenous langauges)
   - Security/privacy reason
   - Developing new annotation methods
   - Available data size is insufficient for specific phenomena / task
   - Data for biomedical data is inadequate/insufficient
   - Academic datasets and pre-trained models are unusable on real data
   - "We build datasets in my lab"
  

## What NLP tasks do you need annotation for?

![](https://docs.google.com/spreadsheets/d/e/2PACX-1vTMa1QOjA4b45HvT3FKnRnfsgIpgjtjOb7RzJ8ZODJZ1vZr0ImtQ313CdAxcnSi3tXcHiXcXc-oUEoC/pubchart?oid=1777988562&format=image)

 - **75.6% (of 78 respondents) need Classification** annotations
 - **60.0% (of 78 respondents) need Span** annotations**
 - **38.5% (of 78 respondents) need Entity Linking** annotations

 - **Others** annotation includes:
    - Video captioning (3 out of 78 respondents)
    - Bounding boxes (2 out of 78 respondents)
    - Word level annotation (includes correction of word tokens)
    - Sentiment / Emotions annotation
    - Stance annotation 
    - NER annotation
    - Writing paraphrases / Dialog systems
    - MCQ answering
    - Item/Product relevancy scoring
    - Semantic Role Labeling
    - Open Information Extraction
    
## Would the annotations you need require domain expertise or can it be handled by crowdsource workers with some minimum requirements?

![](https://docs.google.com/spreadsheets/d/e/2PACX-1vTMa1QOjA4b45HvT3FKnRnfsgIpgjtjOb7RzJ8ZODJZ1vZr0ImtQ313CdAxcnSi3tXcHiXcXc-oUEoC/pubchart?oid=2081029176&format=image)

## Do you have a pool of trusted/expert annotators that can work on your annotation task(s)?

![](https://docs.google.com/spreadsheets/d/e/2PACX-1vTMa1QOjA4b45HvT3FKnRnfsgIpgjtjOb7RzJ8ZODJZ1vZr0ImtQ313CdAxcnSi3tXcHiXcXc-oUEoC/pubchart?oid=1814184526&format=image)

 - **Others** comments includes:
   - Had some trusted annotators for last project. Would have to train a new team the next time.
   - Often, it is the researchers who want to use the annotations for a specific task annotating the data.
   - Kind of - I train university students to annotate as needed for specific projects.
   - Somtimes.
   - I don't really know.
   - Can't say we have trusted or expert annotators but we have annotators.

# Annotation Platforms

## Have you used open source / commercial annotation platforms before?

![](https://docs.google.com/spreadsheets/d/e/2PACX-1vTMa1QOjA4b45HvT3FKnRnfsgIpgjtjOb7RzJ8ZODJZ1vZr0ImtQ313CdAxcnSi3tXcHiXcXc-oUEoC/pubchart?oid=851618670&format=image)

 - 79.7% (63 of 78 respondents) **have** used open source annotation platforms before
 - 58.2% (46 of 78 respondents) **have not** used commercial annotation platforms before

## Which of these *open source* annotation platforms/tools have you ***used*** before?


![](https://docs.google.com/spreadsheets/d/e/2PACX-1vTMa1QOjA4b45HvT3FKnRnfsgIpgjtjOb7RzJ8ZODJZ1vZr0ImtQ313CdAxcnSi3tXcHiXcXc-oUEoC/pubchart?oid=1311576751&format=image)

 - 50.0% (out of 78 respondents) used [Brat](https://brat.nlplab.org/) before 
 - 28.2% (out of 78 respondents) used [WebAnno](https://webanno.github.io/webanno/) before
 - 17.9% (out of 78 respondents) have not used any open source annotation tools before
 - 12 other tools (not listed in the questionnaire) is used by 2 respondents
 - 40 other tools (not listed in the questionnaire) is used by 1 respondent
 

## Which of these commercial annotation platforms/tools have you ***heard*** before?

![](https://docs.google.com/spreadsheets/d/e/2PACX-1vTMa1QOjA4b45HvT3FKnRnfsgIpgjtjOb7RzJ8ZODJZ1vZr0ImtQ313CdAxcnSi3tXcHiXcXc-oUEoC/pubchart?oid=922848789&format=image)

 - 51.3% (out of 78 respondents) have heard of [Amazon Mechanical Turk](https://www.mturk.com/) (MTurk)
 - 41.0% (out of 78 respondents) have heard of [Appen Data Annotation](https://appen.com/solutions/platform-overview/) (formerly known as Figure8, former-formerly known Crowdflower)
 - 33.3% (out of 78 respondents) have heard of [Prodigy](https://prodi.gy/)
 - 19.2% (out of 78 respondents) have not heard of any of the commercial tools before
 
(**Note**: Fiverr and Upwork are generally crowd-source sites that provides huamn annotators but may/may not provide an annotation platform)

## Which of these commercial annotation platforms/tools have you ***used*** before?

![](https://docs.google.com/spreadsheets/d/e/2PACX-1vTMa1QOjA4b45HvT3FKnRnfsgIpgjtjOb7RzJ8ZODJZ1vZr0ImtQ313CdAxcnSi3tXcHiXcXc-oUEoC/pubchart?oid=14680981&format=image)

**Note:** The response for this question is really low, so it might not be representative of all annotation platform users. But this also highlights the stark adoption rate between open source vs commercial annotation tools. 

## Most Useful Features

| Feature | Open Source | Commercial | 
|:-|:-:|:-:|
| Active Learning | ✓ | ✓ | 
| Annotation progress monitor | ✓ | | 
| Annotation shortcuts | ✓ | | 
| Annotation visualization | ✓ | | 
| Automatically suggesting annotations | ✓ | | 
| Audio annotation support | ✓ | | 
| Available Online (No installation)| ✓ | | 
| Connecting to external resources (e.g. storage / knowledge base / dictionary) | ✓ | | 
| Customizable annotation tasks/labels (with extra code/schema)| ✓ |  ✓ | 
| Customizable annotation view (when annotating) |  ✓ | | 
| Drag and drop interactions | ✓ | | 
| Easy setup/installation (e.g Docker) | ✓ | | 
| Export to multiple formats| ✓ | ✓ | 
| Good UI/UX | ✓ | | 
| Interoperability (e.g. load/combine annotations from other tools, integration with other tools)| ✓ |  ✓  | 
| Multi-annotator agreement mechanisms/metrics / Automatic evaluation of annotations | ✓ | ✓ | 
| Post-Annotation curation | ✓ | | 
| Project Management with collaboration features | ✓ | ✓ | 
| Python-based | ✓ | | 
| Simple Login/Sign-on | ✓ | | 
| Supports multiple tasks | ✓ | | 
| Communication tools (e.g. annotators interaction with project managers) |  | ✓ | 
| Documentation (e.g. forums, example setup) | | ✓ | 
| Built-in quality control (e.g. screening tests, data cleanup/filer) | | ✓ | 
| Demo/test small projects with least setup effort | | ✓ | 
| Access to large/diverse/global pool of annotators | | ✓ | 

### Suggestions to annotation tool creators

The keywords **flexibility** and **ease**/**easy**/**simple** appears in many of the comments to list the top features for annotation platform. We suggest the following for annotation tools creators to accomodate these feedbacks:

 - Customizable tasks / labels / schema setup and output formats for annotation project managers
 - User-friendly and intuitive UI/UX 
 - Customizable shortcuts and/or mobile-friendly features to help annotators 

Another recurring theme in the top feature list includes:

 - Respondents highlighting ability to annotate (i) overlapping spans, (ii) discontinuous spans, (iii) corrections to initial tokenizations (iv) entity relation annotations
 - In cases where free text annotation is allowed, some sort of respondents highlighted **need for constraints/limitations of free text**


## Any other feedback on annotation tools?

Here are a couple of aggregated free-form feedbacks from our respondents: 


Feedback for **Open Source** annotation tools:

 - Tokenizations can/should be explicit in the data input format
 - Pre-definition of tagset is important
 - Automatic publishing of annotations as open source 
 - Having web version accessible to everyone is preferred
 - Tools for documentation updates during the annotation project progress
 - Having an active community to maintain the open source annotation tool
 - Automatic population of annotations in the tools would be great
 - Annotating across texts segments would be nice

Feedback for annotation tools **in general**:

 - Make the platforms as open source
 - Support changes in the annotation schema and reclassification of the annotation that are already done.
 - There's no universal tool and there will never be. So we need to find ways to combine the output of different tools.
 - 1-2 years ago, annotation platforms were all simplistic and difficult to use for non-trivial tasks outside of their tutorials
 - Most platforms work well for an individual task, but there's an enormous amount of effort needed to add new features or repurpose an existing tool to a more complicated NLP task. 

# Your Dream Annotation Platform

Summarizing the respondents' dream platforms:

 - All in one
 - Quick, easy to use, simple, plug & play 
 - Flexibity (ability to customize annotation project, labels, tasks, schema, in-/output formats)
 - Interoperability (ability to integrate with other annotation tools and their in-/output formats)
 - Active and large pool of annotators, annotation project creators and annotation tool management community
 
#### Notable Mentions about "Your Dream Anntoation Platform"

 - "*Takes over all the server hosting etc. and leaves the researcher with the task of designing experiments.*"
 - "*Fair treatment of both the annotator and the task creator.*"
 
 
# Acknowledgement

We thank all participants/respondents of the questionnaire and the precious insights/feedbacks given!!! 

We also have a thankful mention to `Mariana Neves` for referring us to the following survey 

- [An extensive review of tools for manual annotation of documents](https://academic.oup.com/bib/advance-article/doi/10.1093/bib/bbz130/5670958) (published on Dec 2019) [List of tool reviewed](https://github.com/mariananeves/annotation-tools)

# Cite 

If reference to this report is necessary, 

to cite (in-text):

> Liling Tan. 2020. A Survey of NLP Annotation Platforms. Retrieved from https://github.com/alvations/annotate-questionnaire


in bibtex:

```
@misc{survey-annotation-platform,
author =   {Liling Tan},
title =    {A Survey of NLP Annotation Platforms},
howpublished = {https://github.com/alvations/annotate-questionnaire},
year = {2020}
}
```
