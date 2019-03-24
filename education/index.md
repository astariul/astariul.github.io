---
description: >
  Here you should be able to find everything you need to know to accomplish the most common tasks when blogging with Hydejack.
hide_description: true
permalink: /education/
---

# Education

I have a Engineer degree (equivalent of Master degree) from [ESISAR](http://esisar.grenoble-inp.fr/en) - [Grenoble INP](http://www.grenoble-inp.fr/en), a public school specialized in computer sciences & network security. 

Beyond the courses offered by the school, students also have several opportunities to discover the world of work, through internships and a special semester (called "Industrial Project") where they work full-time for a company, among a student team. 

It's also possible to make a semester abroad, in a different university.

---

* this unordered seed list will be replaced by toc as unordered list
{:toc}

## Bachelor Program

The Bachelor program of ESISAR focus on theorical knowledge, such as mathematics and physics. Other subjects are also introduced, with for example de basics of electronics, algorithms, and Linux. Non-exhaustive list of subjects :

* **Mathematics** : arithmetic, algebra, geometry, discrete mathematics.
* **Physics** : electromagnetism, semi-conductors, optical physics, mecanics of the particles.
* **Linux** : commands, bash scripts.
* **Electronic** : basics, robotic.
* **Networks** : basics.
* **Computer Sciences** : C language.
* **English**
* **Automatic** : basics, PID & RST controllers.
* **Management** : student project (selling calendars) to collect money and finance a class trip. 

## Technician Internship

Between the Bachelor and the Engineer program, I had to do a 3-months technician internship. I did this internship in the [Real-time Ubiquitous Systems laboratory](https://rubis.snu.ac.kr/home) of [Seoul National University](http://www.useoul.edu/).

During this internship I had to implement the [SPEED protocol](https://ieeexplore.ieee.org/document/1203451) (a network protocol) into the similator [Network Simulator](https://fr.wikipedia.org/wiki/Network_Simulator). The language used was `C++`.

I also helped members of the laboratory with various tasks, using bash scripts.

## Engineer Program

The Engineer program of ESISAR teach applied knowledge, focused on computer sciences, networks, and security. Non-exhaustive list of subjects :

* **Computer Sciences** : object-oriented programming, Java, theorical computer sciences, dynamic programming, software engineering, design patterns, database (SQL), theory of compiler.
* **Networks** : Wi-Fi, ethernet, IPv4, RFC, routers, VLAN, routing.
* **Mathematics** : probabilities, information theory, Markov chains, graphs, game theory, operations research, cryptography.
* **Operating Systems** : processes, inter-processes communication, network administration.
* **English**
* **Signal Theory**
* **Processors** : architecture, VHDL, compiler implementation.
* **Management** : strategy, accounting, entrepreneurship.

## Industrial Project

Industrial Project is a different semester in ESISAR, and it is what's make the school so special.

Students are grouped in team of 3, and for 6 months they work full-time for a external company. Office space are provided within the school for the students. Supervision is done by one professor, assigned to the project. Every 2 months the students are graded.

### Company
{:.no_toc}

For my Industrial Project, we worked with the company [MGI Technologies](http://www.mgi-fr.com/en/) based in Paris. They build and sell industrial-length printer. 

Building printer involve a lot of domains : electronic, automatic, chemistry, colorimetry, mecanic, and of course computer science.

### Project
{:.no_toc}

Among the printer MGI sell, there is a software taking care of each commands from the user, impressing in the right place, etc...

This software (called `kernel`) is written in `C#`, is not fast enough, and is difficult to maintain, because it was written without real design.

The goal of this project is to re-design the whole kernel, and implement this new design in `C++`. The objective is multiple :

* Easier to maintain
* Faster (thanks to language choice)
* multi-platform

### Realization
{:.no_toc}

We followed a `C++` speed formation, as none of the students of the group officially knew the language.

We then spent a great amount of time designing the system, using `UML` standard.

We finally implemented the kernel in `C++`. A important testing phase was performed, particularly because of the multi-platform specification.

### Results
{:.no_toc}

The company was really satisfied with the outcome of the project and the way we managed our team. They proposed us to keep working for MGI for the summer.

On our side, we learned a lot of things, such as a new language (`C++`), but also management skills, and most of all, to work within a team, even though we might not agree on everything.

## Semester Abroad

I did a semester abroad, in the [Seoul National University](http://www.useoul.edu/), in South Korea, for the fall semester of 2017.

I took the following courses :

* **Machine Learning Algorithms in Bioinformatics** : sequence alignement, Markov model, expectation-maximization, hidden markov model, motif discovery. For a project I implemented the K-means algorithm in `Python`, used for DNA pattern research.
* **Distributed Information Processing** : fundamentals, distributed memory/file systems, ubiquitous/peer-to-peer computing, embedded ystems, information protection, digital rights management, performance debugging, dynamic adaptation, distributed computing framework, cloud computing. We did a student project (team of 3) where we implemented the DES cryptographic algorithm in `C` and in parallel computing using `Cuda`.
* **Intelligent systems** : probabilistic modeling & inference (Bayesian networks, hidden markov models, kalman filters, markov decision processes), machine learning (linear classification / regression, EM algorithm, support vector machines, reinforcement learning), robotics (localization, mapping, motion planning, software architecture), computer vision (image formation, edge detection, image segmentation, object recognition). We did a student project (team of 3) where we designed an autonomous driving robot, with the path-finding algorithm A*.
* **Self-learning Neural Algorithms** : PCA, Self-Organizing Map, information-theoretic learning models, statistical physics, dynamic programming, neurodynamics, bayesian filtering, dynamically driven recurrent networks.

---

This was a very interesting experience, I discovered that the way to teach and to grade are completely different between France and South Korea. 

At first that was a great amount of stress to deal with, but eventually I got used to it and did very well : **I got a GPA of 4.15 (97.50%)**

## End of Study Internship

Since I did this internship in a company, I described this experience [here](/experience/2018-02-01-gracenote/).