---
layout: default
title: "Previous Edition: ECIR 2022"
nav_order: 2
---

# ECIR 2022 Tutorial: Technology-Assisted Review for High Recall Retrieval

**We are collaborating with [ALTARS Workshop](http://altars2022.dei.unipd.it/)! Join us in the morning and attend ALTARS in the afternoon to discuss more advanced topics in TAR.**


{:.mt-6}
Human-in-the-loop (HITL) IR workflows are being applied to an increasing range of tasks in the law, medicine, social media, and other areas.  These tasks differ from ad hoc retrieval in their focus on high recall, and differ from text categorization in their need for extensive human judgment. These tasks also differ from both in their industrial scale and, often, their use of teams of multiple reviewers. In the research literature, these tasks have been variously referred to as *review*, *moderation*, *annotation*, or *high recall retrieval (HRR)* tasks. Technologies applied to these tasks have also been referred to by many names, but *technology-assisted review (TAR)* has emerged as a consensus term, so these tasks are also referred to as *TAR tasks*. 

The growth in the deployment of TAR systems, combined with the many open research problems in this area, suggest this is an appropriate time for a TAR tutorial at a major IR conference.
Such a tutorial would also serve as background for attendees of the TAR workshop that has been approved for ECIR 2022. 

- Length: Half day.
- Target audience: Intermediate. 
- Expected prerequisite knowledge:  Some exposure to basics of information retrieval and machine learning. 

## Outline 


### Introduction to TAR
- What is a TAR task 
- Comparison to other IR tasks 
- Application areas
    - Law: litigation, antitrust, investigations
    - Systematic reviews in medicine 
    - Content moderation
    - Data set annotation 
    - Sunshine laws, declassification, and archival tasks
    - Patent search and other high recall review tasks 
- History 

### Dimensions of TAR Tasks
- Volume and temporal characteristics of data
- Time constraints 
- Reviewer characteristics 
- Cost structure and constraints 
- Nature of classification task (single, multiple, and cascaded classifications) 

### TAR Workflows
- Importance of workflow design in HITL system  
- One-phase vs. two-phase workflows 
- Quality vs. quantity of training
- Pipeline workflows 
- Collection segmentation and multi-technique workflows 
- When to stop?

### Technology: Basics
- Review software and traditional review workflows
- Duplicate detection, aggregation, and propagation
- Search and querying
- Unsupervised learning and visual analytics

### Technology: Supervised Learning
- Basics of text classification 
- Data modeling and task definition 
- Prioritization vs. classification 
- Reviewing and labeling in TAR workflows 
- Relevance feedback and other active learning approaches
- Implications of transductive context 
- Classifier reuse and transfer learning 
- Research questions

### Evaluation
- Effectiveness measures 
- Sample-based estimation of effectiveness
- Impact of category prevalence
- Cost measures 
- Evaluating progress within a TAR project
- Collection segmentation and evaluation  
- Choosing and tuning methods across multiple projects
- Research questions

### Stopping rules
- Stopping rules, cutoffs, and workflow design
- Cost targets and effectiveness targets
- The cost landscape 
- Distinctions among stopping rules
    - Interventional, standoff, and hybrid rules
    - Gold standard vs. self-evaluation rules
    - Certification vs. heuristic rules 
- Example stopping rules
    - [Knee, Target, and Budget Methods](https://dl.acm.org/doi/10.1145/2911451.2911510)
    - [Quant and QuantCI Rule](https://dl.acm.org/doi/10.1145/3469096.3469873)
    - [QBCB Rule](https://dl.acm.org/doi/10.1145/3459637.3482415)
- Research questions 

### Societal context  
- TAR and the ethical obligations of attorneys
- Bias and ethics issues in TAR for monitoring and surveillance
- Implications of TAR for evidence-based medicine 
- Controversies in automated content moderation
- Research questions 

### Summary and Future
- TAR research and industry practice 
- Challenges in access to data   
- The potential for interdisciplinary TAR research


## Presenters

**[Eugene Yang](https://www.eugene.zone/)**
is a Research Associate at Human Language Technology Center of Excellence at Johns Hopkins University. He has been developing state-of-the-art approaches for Technology-assisted reviews. His Ph.D. dissertation focuses on the cost reduction and analysis for TAR, including cost modeling and stopping rules for one and two phase workflows. He is currently working on cross-lingual human-in-the-loop retrieval approaches.

**[Jeremy Pickens](https://www.linkedin.com/in/jeremy-pickens-4b81bb5/)**
is a pioneer in the field of collaborative exploratory search, a form of information seeking in which a group of people who share a common information need actively collaborate to achieve it. As Principal Data Scientist at OpenText, he has spearheaded the development of Insight Predict. His ongoing research and development focuses on methods for continuous learning, and the variety of real world technology assisted review workflows that are only possible with this approach. Dr. Pickens earned his doctoral degree at the University of Massachusetts, Amherst, Center for Intelligent Information Retrieval. Before joining Catalyst Repository Systems and later OpenText, he spent five years as a research scientist at FX Palo Alto Lab, Inc. 

**[David D. Lewis](http://www.daviddlewis.com/)**
is Chief Scientific Officer for Redgrave Data, a legal technology services company.  He has researched, designed, and consulted on human-in-the-loop document classification and review systems since the early 1990’s. His 1994 paper with Gale introduced uncertainty sampling, a core technique used in commercial TAR systems. This paper won an ACM SIGIR Test of Time Award in 2017.  In 2005, Dave co-founded the TREC Legal Track, the first open evaluation of TAR technology. He was elected a Fellow of the American Association for the Advancement of Science in 2006 for foundational work on algorithms, data sets, and evaluation in text analytics.

