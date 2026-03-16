---
layout: default
title: Student Projects & Thesis Proposals
permalink: /thesis-proposals/
---

# Thesis Proposals

These are the steps:

1. Understand (1) **[kind of thesis](#background)** and (2) [**topics**]((#thesis-proposals)) you are interested in
    - If you are in "explorative mode", use proposals, [past completed theses](#past-co-supervised-theses), or [**other resources**](#inspiration) as a source for **inspiration**  
2. Take a look at my [research activity](/research) (to understand what is my core expertise) and **read carefully this page** for concrete **[thesis proposals](#thesis-proposals)**.
3. If you found a proposal that interests you, or would like to discuss **variations or other proposals**, please [contact me via e-mail](mailto:roby.casadei@unibo.it)
4. Once we have defined a direction/strategy/tentative project work, let's discuss [how to bootstrap work](#bootstrap)


## Background on Bachelors'/Masters' Theses or Dissertations
<a name="background"></a>

General information about theses can be found here: [LaTeX thesis template](https://github.com/unibo-disi-cesena/thesis-template).

Kinds of thesis:

- **Research-oriented** -- these aim at providing (small) contributions to the state of the art in some target field;
    - Ideal for ambitious Master Degree students who seek challenges, can tolerate risks, and can proactively look for innovative solutions (as well as for those who intend to pursue a PhD)
- **Software engineering projects** -- these are works aimed at developing complex software (cf., distributed systems);
    - Ideal for both Bachelor and Master students who would like to put into practice what they learnt during the degree course 
- **Surveys / Systematic Literature Reviews** -- the works include a comprehensive study of the literature (e.g., on self-* systems, multi-agent systems, collective intelligence) and an original synthesis (e.g., in terms of a taxonomy, learned lessons, challenges and opportunities).
    - Ideal for Bachelor students who would like to deepen the study of a specific topic

Notice that these are coarse-grained classifications and that theses might mix portions of all these three types (while formally be overall configured as one of the three types).

General principles about theses:

- **Student / Professor relationship.** It is key to understand that theses are *individual works* of the students, who take full responsibility for their work and overall path to the degree. The professor acts as a mentor and guide, and supervises the activity, but the student should not expect that the professor solves tasks for him, copy-checks the work, or notifies the student for the bureaucratic steps.
* **First gather knowledge and results, then write.** The writing step should be easy once the student has acquired the knowledge and results to be communicated.
* **How to write.** The general principle is to *assume the reader has very limited background on the topic*. Each and every technical term should be introduced on first use, and paragraph should provide a clear logical flow (narrative).

## Current Active Proposals and Thematic Areas
<a name="proposals"></a>

- Any topic relevant to the [Foundations of Macro-programming-based Software Engineering project](https://fis3-fomase.github.io/)
    - any investigation addressing the question: how to effectively engineer the micro-macro link in collective and multi-party systems?
- Scientific and inter-/multi-/trans-disciplinary topics:
    - *Investigations on aspects related to **["collective intelligence"](https://arxiv.org/pdf/2304.05147.pdf)***: how to reliably engineer collective behaviour? how to influence collective behaviour? what can we learn from animal behaviour? See Casadei's paper [Artificial Collective Intelligence Engineering: A Survey of Concepts and Perspectives Unavailable](https://doi.org/10.1162/artl_a_00408) for an overview of the topic.
    - **Ethic-aware** autonomous systems*: autonomous systems should not just focus on functional requirements and user preferences, but also on the broader implications of their actions (cf. social aspects). So: how to model soft/hard ethical requirements? How to deal with conflicting ethics? How to enforce collective ethics in a MAS? How to measure ethical-awareness and -effectiveness?
- Programming languages and frameworks for specific domains:
    - *Investigations on non-conventional / domain-specific programming paradigms* (cf. **[macro-programming](https://dl.acm.org/doi/10.1145/3579353)**)
    - **Integration of [ScaFi](https://scafi.github.io/) and the ARGoS Robot Simulator**
- Knowledge-intensive workflows
    - **Web platforms for knowledge-intensive workflows**
    - *DSLs for generating universal (web-based, desktop, mobile) knowledge-intensive workflow applications*
- **Artificial collective intelligence engineering**
    - See Casadei's paper [Software Engineering for Collective Cyber-Physical Ecosystems](https://doi.org/10.1145/3712004) for a research agenda on the topic.
- Software engineering topics: visualisation
    - **Software system visualisation, monitoring, and debugging** (with links to *Model@Runtime*)
- Software engineering topics: testing
    - **Testing solutions for complex adaptive multi-agent systems** (connected with scientific themes like *emergence*)
- Human-machine networks
    - Supporting effective collaboration in **human-machine networks**?
- Innovative applications
    - **Crowd Digital Twins**: design of digital twin-based solutions for physical situated human crowds. This topic is actually a research agenda, with several directions for investigations: see the papers [Crowd Digital Twins: Motivation, Architecture, and Roadmap](https://doi.org/10.1016/j.future.2026.108475) for an overview of the topic.

Some of these proposals are detailed in the following.

### Domain-Specific Language (DSL) Prototyping for Micro-Macro Design

- *Type of work*: research/project
- *Goal*: after an initial investigation of the state of the art in DSLs for macro-programming, develop a DSL prototype to investigate (some aspect of) the micro-macro link engineering (e.g., downward causation)
- *Requirements*: familiarity with the basic notions of DSL and PL design (e.g., APIs, ASTs, advanced language features, typing, compilers)
- *References*: 
    - [Macroprogramming: Concepts, State of the Art, and Opportunities of Macroscopic Behaviour Modelling (Casadei, 2022)](https://arxiv.org/abs/2201.03473)

### Case studies using research-level programming languages

- *Type of work*: research/project
- *Goal*: explore the practical expressiveness of research-level programming languages and/or make experiments/extensions for addressing limitations or specific functional/non-functional properties (e.g., adaptivity, reactiveness)
    - e.g., multi-agent oriented programming languages (e.g., JaCaMo, SARL, Kiko)
    - e.g., context-oriented programming, context-role oriented programming
- *References*: 
    - [Software Engineering for Collective Cyber-Physical Ecosystems (Casadei et al., 2025)](https://doi.org/10.1145/3712004)
    - [Macroprogramming: Concepts, State of the Art, and Opportunities of Macroscopic Behaviour Modelling (Casadei, 2023)](https://arxiv.org/abs/2201.03473)
    - [Programming IoT systems: A focused conceptual framework and survey of approaches (Casadei et al., 2025)](https://doi.org/10.1016/j.iot.2025.101548)

### Information-theoretical methods for analysis of collective computations

- *Type of work*: research/project
- *Goal*: consider collective computation models (e.g., cellular automata, aggregate computing) and apply information theoretic measures to analyse the dynamics on examples
- *Mainly aimed at*: Master Students
- *References*: please contact the professor

### A Framework for Reusable Logical Visualisations of Software Systems

- *Type of work*: project (+ survey)
- *Abstract:* Visualising software systems is key for understanding them, enabling debugging, software evolution, and team collaboration. Much of research has focussed on visualising program executions in terms of 'code'. However, sometimes, more flexible and logical forms of visualisations might be generated for purposes like conceptual comprehension, analysis, and education. Moreover, most of the frameworks are constrained in terms of the kinds of visualisations to be generated. Goal of this project/thesis is to investigate ways to design the generation of visualisations in a flexible, decoupled, and reusable manner. Multiple specific directions and applications can also be envisioned, from multi-level visualisations of collective systems (e.g., crowds) to semi-automatic visualisation of algorithms on different data structures.
- *References*: as there are some novel ideas not investigate in the literature, please contact the professor
    * [A Network-Based Visual Analytics Approach for Performance Evaluation of Swarms of Robots in the Surveillance Task (Linhares et al., 2022)](https://doi.org/10.1007/978-3-031-21686-2_5)

### Investigation on autonomic architectures for self-managing systems

- *Type of work*: project (+ survey)
- *Goal*: design and implement an autonomic architecture (e.g., following the MAPE-K or AWARE architectural patterns) on an identified case study (e.g., digital twin scenario, IoT/smart city scenario, or swarm robotics scenario)
- *References*:
    - [BOOK: An introduction to self-adaptive systems: A contemporary software engineering perspective (Weyns, 2020)](https://introsas.cs.kuleuven.be/2020ExcerptBook.pdf)
    - [The vision of autonomic computing (Kephart, Chess, 2003)](https://doi.org/10.1109/MC.2003.1160055)
    - [Breaking the loop: Aware is the new mape-k (Sanwouo et al, 2025)](https://doi.org/10.1145/3696630.3728512)

### *Integration of [ScaFi](https://scafi.github.io/) into Multi-Robot Simulators *

- *Type of work*: software engineering project
- *Background*: 
    - ScaFi is a DSL for programming collective adaptive systems (e.g., robot swarms)
    - Robot simulators like ARGoS and ROS2 (Robotic OS) support testing control logic in a variety of simulated environments
- *Goal*: allowing the execution of ScaFi programs to control robots in a robot simulator (e.g., into the ARGoS Robot Simulator or ROS2)
- *Requirements*: knowledge of C/C++ (since ARGoS is implemented in C++) and Java/Scala (since ScaFi runs on the JVM)
- *Mainly aimed at*: Master Students
* *References*:
    - [ScaFi: A Scala DSL and Toolkit for Aggregate Programming (Casadei et al., 2022)](https://doi.org/10.1016/j.softx.2022.101248)
    - [ScaFi website](https://scafi.github.io/) and [MacroSwarm website](https://scafi.github.io/macro-swarm/)
    - [ARGoS website](https://www.argos-sim.info/)
    - [Robotic Operating System (ROS) website](https://www.ros.org/)

### *Web platforms for knowledge-intensive workflows*

- *Type of work*: software engineering project
- *Goal*: the goal is to support the configurable creation of web-based knowledge-intensive workflow platforms, e.g. according to literature models (cf. SLRs).  For instance, suppose you are carrying out a collaborative research project. You and your groupmates need to select a bunch of papers or references to study. Then you need to analyse them, and take notes about them. This process consists of multiple phases: paper gathering, preliminary analysis, paper filtering, detailed analysis, and production of plots. The goal is to build a configurable platform allowing customisation of similar workflows and the flexible integration of plugins/tools therein for analyses etc.
- *Requirements*: web-based and database technologies
- *Mainly aimed at*: Bachelor / Master Students
- *References*: please contact the professor

## Need inspiration?
<a name="inspiration"></a>

Lectures and scientific articles are great sources for inspiration

- [Software Engineering Methods for Artificial Collective Intelligence (R. Casadei, Invited Talk at GSSI, 2025)](https://www.slideshare.net/slideshow/software-engineering-methods-for-artificial-collective-intelligence/277619307)
- Casadei, Roberto, et al. "Software engineering for collective cyber-physical ecosystems." ACM Transactions on Software Engineering and Methodology 34.5 (2025): 1-40. <https://doi.org/10.1145/3712004>
-  * Casadei, Roberto. "Artificial collective intelligence engineering: a survey of concepts and perspectives." Artificial Life 29.4 (2023): 433-467. <https://arxiv.org/abs/2304.05147>

## Past co-supervised theses

Take a look [here for theses (co-)supervised by me in the past](https://amslaurea.unibo.it/view/relatore/Casadei=3ARoberto=3A=3A/).

Some highlights (Master's Degree):

- ["Event-driven simulation and verification of FRASP systems against spatio-temporal properties", Cesario, 2024](https://amslaurea.unibo.it/id/eprint/31094)
- ["A functional-reactive perspective on the Aggregate Computing paradigm", Dente, 2023](https://amslaurea.unibo.it/id/eprint/28147/)
- ["A platform for aggregate computing over LoRaWAN network", Placuzzi, 2020](https://amslaurea.unibo.it/20484/)
- ["A Reinforcement Learning approach to discriminate unsafe devices in aggregate computing systems", Volonnino, 2020](https://amslaurea.unibo.it/20488/)
- ["Towards Aggregate Processes in a Field Calculus-Based Platform", Foschi, 2018](https://amslaurea.unibo.it/15725/)
- ["Distributing Aggregate Computations on top of Akka Actors", Peruzzi, 2018](https://amslaurea.unibo.it/17016/)
- ["Tecniche e algoritmi di aggregate computing a supporto di contesti di smart mobility", Berlini, 2017](https://amslaurea.unibo.it/14292/)
- ["Design and Deployment of an Execution Platform based on Microservices for Aggregate Computing in the Cloud", Farneti, 2017](https://amslaurea.unibo.it/12948/)

Some highlights (Bachelor's Degree):

- ["Progettazione di un ambiente di programmazione visuale block-based per ScaFi", Cerioni, 2022](https://amslaurea.unibo.it/id/eprint/25878/)
- ["Progettazione di un sistema di categorizzazione delle regressioni per il compilatore Rust", Pasini, 2020](https://amslaurea.unibo.it/20886/)
- ["Sviluppo di un front-end di simulazione per applicazioni aggregate nel framework Scafi", Aguzzi, 2018](https://amslaurea.unibo.it/16824/)
- ["Sviluppo di applicazioni distribuite con lo stack SMACK", Ciavatta, 2018](https://amslaurea.unibo.it/16836/)

## "I chose a thesis with your (co-)supervision, Prof. Casadei! How should I proceed?"
<a name="bootstrap"></a>

1. Please [contact me through my institutional e-mail](https://www.unibo.it/sitoweb/roby.casadei/en)
2. We will define a flexible plan/schedule: e.g. 1/2-weeks meetings 
3. I will provide (1) relevant materials as well as (2) practical information
    - A good starting point is: [LaTeX thesis template](https://github.com/unibo-disi-cesena/thesis-template)

