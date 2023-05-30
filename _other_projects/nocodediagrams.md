---
layout: project
title: No Code Automatised Software Generation
caption: Software built from diagram flows and test data
description: >
 Automatised code generation from diagram flows and test data with Large Language Models.

date: 30 May 2023
image: 
  path: /assets/img/projects/stresstestgraph.jpg
  srcset: 
    1920w: /assets/img/projects/stresstestgraph.jpg
    960w:  /assets/img/projects/stresstestgraph@0,5x.jpg
    480w:  /assets/img/projects/stresstestgraph@0,25x.jpg
layout: project
links:
  - title: Code
    url: https://github.com/gilgameshjw/tmp
accent_color: '#4fb1ba'
accent_image:
  background: '#193747'
theme_color: '#193747'
sitemap: false
---

# No Code Software

### Vision

* Large language models can be leveraged to automatically generate code snippets. 

* On the other hand, humans think in term of diagrams and express ideas in a mix of natural language and examples. 

We have combined these two principles to build a software that automatically generates working code.

### Motivation

#### Software Can Be Easy To Build For Anybody
Not only should the technology I am designing allow to design complex systems swiftly and complement human feedback and creativity. 

In practice, it should revolutionize the way we build software, making development intuitive, easy and cheaper. Anybody will be able to do develop complex ideas!

#### Task Planning With Constrained Ideation And Action
Seen in more abstract terms, it is about  solving the planning and buiding of software, given a particular task an a few examples of what the software should do.

The approach is original and grounded in the sense that it starts by successfully solving human designed diagrams is inherently tests driven.

The plan is to gradually learn how to relax some of the tests and allowing the agent to add substeps and deal with abstract requests. 

#### Agent Interacting with The World (Or Internet...)
An agent capable of planning and generating its own software, generating its own good test data would have a method for interacting with its environment (thus creating more useful learning material)!


### Current Solution
In a nutshell, the code linked above works in the following fashion:

**1.** Diagram structure is being parsed.

**2.** A conversation with the language model is used to generate the necessary code snippets.

**3.** Data snippets are used to stabilise the code, by looping over the errors and asking the language model to improve.


#### Current Work
We are now extending the technology in making the full code generation (including the diagram design) automatised.

This requires a mix of experiments, prototyping and literature reviews.





