+++ 
draft = false
date = 2026-01-13T20:10:29-05:00
title = "FDA released a draft guidance on the use of AI to support regulatory decision-making for drugs"
description = ""
slug = ""
authors = []
tags = []
categories = []
externalLink = ""
series = []
+++

Last week the [FDA released a draft guidance on the use of AI to support regulatory decision-making for drugs](https://www.fda.gov/media/184830/download). Overall the guidance covers the basics for model development, training and testing and the special considerations based on the level of risk associated with the model. Reassuringly the guidance doesn’t deviate from many best practices that the industry has developed over the last decade. In many cases the recommendations are high level and are left up to the sponsor to determine the exact methodology and rationale for their decisions.

The document introduces some new language - the “credibility assessment plan”, but much of the language should be familiar to those developing AI models in this space.

It highlights the unique challenges of using AI in regulatory decision making: 

Variability in quality, size and representatives of datasets for training AI models - data should be fit for use (this is something we’ve seen with many of our collaborations).
Complexity surrounding how models are developed and how they produce answers requires greater transparency.
Interpretability of findings.
Model drift - performance to change over time with new inputs that differ from training data.

A seven step process is defined to “establish the credibility of an AI Model output for a specific context of use based on model risk”. Below are the seven steps:

Define the question of interest that will be addressed by the AI model
Define the context of use for the AI model (e.g. how will the model be used, will it be used in isolation or with additional data).
Assess the AI model risk. There are two primary variables for looking at risk: a) model influence and b) decision outcome. If the model has high influence (e.g. the only deciding factor) and a significant decision outcome, then it will be high risk.
Develop a plan (“credibility assessment plan”) to establish the credibility of AI model output within the context of use.
Execute the plan.
Document the results of the credibility assessment plan and discuss deviations from the plan.
Determine the adequacy of the AI model for the context of use.

Finally the document outlines several considerations around model life cycle maintenance and emphasizes connecting with the FDA early to get feedback on the credibility assessment plan. 