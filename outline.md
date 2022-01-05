---
layout: default
title: Outline
nav_order: 2
---

# Tutorial Outline

## Introduction to TAR
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

## Dimensions of TAR Tasks
- Volume and temporal characteristics of data
- Time constraints 
- Reviewer characteristics 
- Cost structure and constraints 
- Nature of classification task (single, multiple, and cascaded classifications) 

## TAR Workflows
- Importance of workflow design in HITL system  
- One-phase vs. two-phase workflows 
- Quality vs. quantity of training
- Pipeline workflows 
- Collection segmentation and multi-technique workflows 
- When to stop?

## Technology: Basics
- Review software and traditional review workflows
- Duplicate detection, aggregation, and propagation
- Search and querying
- Unsupervised learning and visual analytics

## Technology: Supervised Learning
- Basics of text classification 
- Data modeling and task definition 
- Prioritization vs. classification 
- Reviewing and labeling in TAR workflows 
- Relevance feedback and other active learning approaches
- Implications of transductive context 
- Classifier reuse and transfer learning 
- Research questions

## Evaluation
- Effectiveness measures 
- Sample-based estimation of effectiveness
- Impact of category prevalence
- Cost measures 
- Evaluating progress within a TAR project
- Collection segmentation and evaluation  
- Choosing and tuning methods across multiple projects
- Research questions

## Stopping rules
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

## Societal context  
- TAR and the ethical obligations of attorneys
- Bias and ethics issues in TAR for monitoring and surveillance
- Implications of TAR for evidence-based medicine 
- Controversies in automated content moderation
- Research questions 

## Summary and Future
- TAR research and industry practice 
- Challenges in access to data   
- The potential for interdisciplinary TAR research