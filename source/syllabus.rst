
.. `ReStructured-Text <https://github.com/ralsina/rst-cheatsheet/blob/master/rst-cheatsheet.rst>`_ 


Syllabus
========

Summary
-------
Modern research approaches tightly integrate experimentation with data analysis and mathematical modeling to provide unprecedented insights into the organization and functioning of living systems. This course explores the quantitative basis of major cellular processes and their coordination to form a cohesive physiological entity that is capable of rapid growth and acclimation to changing environments. Weekly lectures will be accompanied by 'dry lab sessions' in which students analyze experimental data sets and discuss the challenges of accomplishing rigorous and reproducible research. As such, students will actively develop a fundamental skill set of quantitative biology which includes knowledge in coding, dynamical systems modeling, and statistics. 

Time & Location
---------------
Tuesday and Thursday 9:00 to 10:50 am. All class meetings are in the Sapp Building, room 104.

Office Hours: At Clark W3.3, 4-5pm on Tuesdays (Jonas) and 11am-12pm on Wednesdays (Shaili)

Prerequesites
--------------
Recommended preliminary knowledge in math, coding, and cell biology is outlined here. Please contact the instructor if unsure about these requirements.


Math: Mathematical considerations are a fundamental part of quantitative biology and
rigorous data analyses. But these considerations do not always require advanced
techniques in calculus and statistics and can simply start with a comparison of different
numbers and the simple arithmetics and basic considerations of statistics. In this
course, we will apply beyond these basic approaches a few techniques from the
mathematical toolbox which are fundamentally important for the analysis of complex
biological systems including differential equations, linear regression models, and
inference statistics. These techniques will be introduced during the class and prior
in-depth knowledge is not required. More important than the previous knowledge is the
interest and openness to learn the basic rationale and potential of these approaches.

Coding: Python is used during the dry-lab classes to analyze data and run statistics.
Some familiarity with coding is therefore helpful. However, we encourage students with
all levels of coding experience to join. We will provide introductory Jupyter notebooks for
students with little or no coding experience while students with more advanced
experience can work together to develop the provided modeling and data analysis
scripts further and more deeply investigate the different biological questions we
consider.

Molecular and cell biology: This course considers different fundamental processes of
biology. A basic knowledge of cell biology is therefore required but knowledge does not
need to go beyond what is usually taught in undergraduate biology courses like BIO 82
and BIO 83.


Required equipment
--------------------
To become familiar with Python and the different modeling/data-analysis approaches,
we highly recommend that students bring their own computers to the dry-lab classes.
The computer needs to be able to run Anaconda or an alternative collection of Python
packages and we will provide setup instructions at the beginning of the course.  Let us know as soon as possible if you don't have a laptop that you can use for the course, so that we can make arrangements for you!


Course content in more detail
------------------------------

Organisms and the cells which form them operate an astonishing machinery of life. In
clockwork-like precision, this machinery (i) sustains metabolism and energy supply, (ii)
promotes biomass accumulation and replication, (iii) and ensures stress resilience and
survival, often across very different environmental conditions. In this course we discuss
the integrative nature of this machinery as a reference scenario to introduce essential
data analysis approaches and considerations of rigor and reproducibility in modern
biology. To this end, students will work on datasets from recent experiments which cover
very different biological processes, from the molecular features of translation,
metabolism, and gene regulation, via the growth and survival of cells, to the ecological
and evolutionary dynamics of populations. To foster the utilization of quantitative
approaches and raise awareness for the requirements of rigorous research in modern
biology, weekly lectures on biology and quantitative approaches will be accompanied by
“dry-lab” sessions. During these sessions, students will apply the coding language
Python to employ and present major exercises in data analysis, mathematical modeling,
statistics, and experimental design. During the final three weeks, students will further
apply learned approaches to dissect a biological problem of their own choice. In all
considerations, students will use the GitHub repository of the course and as such
become familiar with state of the art approaches to collaborate and transparently share
analysis pipelines and data.

This weekly schedule summarizes the different biological themes and the quantitative
approaches covered.ents

.. list-table:: Syllabus
    :widths: 5, 10, 40, 30, 15
    :header-rows: 1

    * - Week
      - Date
      - Class 
      - Dry lab 
      - Due Homework
    * - 1
      - 1/9 and 1/11 2024
      - Course Introduction - life, biological complexity, and cell biology by the numbers
      - Introduction to Jupyter, GitHub, and data handling with Pandas
      - 1/18
    * - 2
      - 1/16 and 1/18 2024
      - Cellular biomass acumulation. Differential equations in a nut shell.
      - Linear regression and solving differential equations.
      - 1/25 
    * - 3
      - 1/23 and 1/25 2024
      - Stochastic in biology - Brownian motion, stochastic processes, and the law of large numbers
      - Introduction to probability and statistical considerations of uncertainty. 
      - 2/1
    * - 4
      - 1/30 and 2/1 2024
      - Cellular resource allocation and growth
      - Ressource allocation models
      - 2/8
    * - 5
      - 2/6 and 2/8 2024
      - From gene expression and transcription to translation, protein synthesis, and cell composition – a quantitative view of the central dogma.
      - Analyzing the relation between transcriptomics and proteomics data sets. How to go from the observation of correlations to mechanism?
      - 2/15
    * - 6
      - 2/13 and 2/15 2024
      - Global regulators and the coordination of cellular processes
      - Deterministic behavior in a stochastic world - an example with gene expression
      - 2/22
    * - 7
      - 2/20 and 2/22 2024
      - Cellular behavior in changing conditions. Gene expression and tradeoffs in different environments.
      - Analysis of experiments on bacterial growth in changing environments
      - 2/29  
    * - 8
      - 2/27 and 2/29 2024
      - tbd
      - tbd
      - no homework 
    * - 9
      - 3/5 and 3/7 2024
      - Project phase
      - Project phase
      - no homework  
    * - 10
      - 3/12 and 3/14 2024
      - Project phase
      - Presentation of project
      - Project submission by the end of Tuesday, 3/12. 

	 
Course structure
----------------

This course will include lectures, dry-labs, home-work, and a project phase. 

Lectures (Tuesdays)
%%%%%%%%%%%%%%%%%%%%%
We will discuss cell physiology and major concepts of quantiative biology. 

Dry labs (Thurdays)
%%%%%%%%%%%%%%%%%%%%%
We will work on different problem sets which students will complete as homework. 

Homework
%%%%%%%%%%
There are overall seven different problem sets, presented in Jupyter notebooks, which students work on at home. Submission is due the following week before the next dry lab session.

Project
%%%%%%%%%%
The final two weeks of the course are reserved for a project phase in which students work in teams on a biological project of their interest. 
	  
..      -  :download:`Mendel 1865 <papers/gm-65.pdf>`
..      - `Problem Set 1 <problem_sets/problem_set_1.html>`_

.. This table is produced from this RST code.

..  code-block::
    
