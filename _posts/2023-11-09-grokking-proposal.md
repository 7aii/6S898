---
layout: distill
title: Grokking Proposal
description:
  In the study of neural networks, “grokking” is an unusual event where a model suddenly shifts from simply memorizing to truly understanding and generalizing information. This research aims to dissect the conditions that prompt grokking by experimenting with different data sets and neural network designs. We will investigate the effects of training size, weight decay, and network complexity on grokking. Our goal is to replicate the grokking event, test theories about its causes, and clarify its relationship to the concept of double descent, providing a clearer picture of this peculiar learning behavior.
date: 2023-11-07
htmlwidgets: true

# Anonymize when submitting
# authors:
#   - name: Anonymous

authors:
  - name: Siwakorn Fuangkawinsombut
    # url: "https://en.wikipedia.org/wiki/Albert_Einstein"
    affiliations:
      name: MEng 6-3, MIT 
  - name: Thana Somsirivattana
    # url: "https://en.wikipedia.org/wiki/Boris_Podolsky"
    affiliations:
      name: BS 18 & 6-3, MIT
  # - name: Nathan Rosen
  #   url: "https://en.wikipedia.org/wiki/Nathan_Rosen"
  #   affiliations:
  #     name: IAS, Princeton

# must be the exact same name as your blogpost
bibliography: 2023-11-07-grokking-proposal.bib  

# Add a table of contents to your post.
#   - make sure that TOC names match the actual section names
#     for hyperlinks within the post to work correctly.
toc:
  - name: Introduction
  - name: Related Works
  - name: Exploratory Analysis
  - name: Timeline
    subsections:
    - name: Week 1
    - name: Week 2
    - name: Week 3
    - name: Week 4
  # - name: Equations
  # - name: Images and Figures
  #   subsections:
  #   - name: Interactive Figures
  # - name: Citations
  # - name: Footnotes
  # - name: Code Blocks
  # - name: Layouts
  # - name: Other Typography?

# Below is an example of injecting additional post-specific styles.
# This is used in the 'Layouts' section of this post.
# If you use this post as a template, delete this _styles block.
_styles: >
  .fake-img {
    background: #bbb;
    border: 1px solid rgba(0, 0, 0, 0.1);
    box-shadow: 0 0px 4px rgba(0, 0, 0, 0.1);
    margin-bottom: 12px;
  }
  .fake-img p {
    font-family: monospace;
    color: white;
    text-align: left;
    margin: 12px 0;
    text-align: center;
    font-size: 16px;
  }
---

## Introduction

This research delves into neural networks to decode the grokking phenomenon: a sudden shift from memorizing data to achieving broad generalization. We aim to identify and analyze the triggers for this leap in learning capability. We will meticulously review relevant studies, pinpoint knowledge gaps, and engage in empirical research to understand grokking’s mechanics. Our exploration will cross the boundaries from algorithmic to non-algorithmic data, evaluating the potential roles of network sparsity, the capabilities of minimalist networks, and the enigmatic delayed learning onset associated with grokking.

## Related Works

We’ll be dissecting the literature on grokking, tracing its progression from initial sightings in structured algorithmic environments to unexpected appearances with more complex, natural datasets. Our analytical journey will revisit Power’s foundational observations and delve into the latest theories <d-cite key="power2022grokking"></d-cite>, such as Varma’s efficient circuit hypothesis<d-cite key="varma2023explaining"></d-cite> and Nanda’s approach to unpacking the network's learning mechanics<d-cite key="nanda2023progress"></d-cite>.

Furthermore, we’ll scrutinize pioneering studies that shed light on the internal rivalry within neural networks, examining Merrill’s discovery of subnetwork competition<d-cite key="merrill2023tale"></d-cite>, Gromov’s application of modular arithmetic to straightforward network structures<d-cite key="gromov2023grokking"></d-cite>, and Miller’s insights into how model complexity impacts the learning process<d-cite key="miller2023grokking"></d-cite>. Each piece of research enriches our understanding and provides critical context for our investigation into the grokking enigma.

## Exploratory Analysis

Our hands-on phase starts with attempts to recreate grokking in various settings, followed by a deep dive into why and how it happens, and how it differs from the known pattern of epoch-double-descent. We’ll be tinkering with the elements of neural networks to see what sparks this intriguing switch from memorization to generalization.

## Timeline

### Week 1: Foundation and Replication
* Delve into the foundational papers on grokking.
* Begin experiments to replicate the grokking phenomenon.

### Week 2: Hypothesis and Experimentation
* Formulate hypotheses based on week 1 insights.
* Design and conduct targeted experiments.

### Week 3: Testing and Analysis
* Test the proposed hypotheses in varied scenarios.
* Analyze the data to assess the occurrence of grokking.

### Week 4: Synthesis and Reporting
* Compile and synthesize the findings.
* Draft the research blog post to narrate the exploration journey.
