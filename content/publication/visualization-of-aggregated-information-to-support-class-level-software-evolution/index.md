---
title: Visualization of aggregated information to support class-level software
  evolution
publication_types:
  - "2"
authors:
  - Mona Rahimi
  - Michael Vierhauser
doi: https://doi.org/10.1016/j.jss.2022.111421
publication: In *Journal of Systems and Software*
publication_short: In *JSS*
abstract: >-
  Context:

  Software is inherently prone to constant change, especially in the source code, making it difficult for developers to keep track of changes performed over time and to fully understand their implications.


  Objective:

  To this end, we present an Eclipse plug-in for visualizing heterogeneous information, collected from multiple sources, at different levels of granularity. This visualization provides a single graphical representation of a system’s change histories over multiple versions, allowing developers to identify the previous and present dependencies in the system, while adding new or removing and modifying the current functionalities of a software. Summarizing and associating the relevant changes in a single graph, further supports developers, not familiar with the overall system, to conduct a self-study and explore the systems design and changes of its functionality over time.


  Method:

  Our tool, DejaVu, initially infers and further visualizes change scenarios that have been applied to a given class in source code, across multiple versions of a software. DejaVu additionally augments the change information with prior commits from GitHub repositories, as well as associated issues from Jira issue tracking system.


  Evaluation:

  As part of the evaluation, we conducted a controlled experiment, recruiting participants with research or industrial programming experiences. The participants were asked to investigate and assess a set of change stories with and without the use of the DejaVu. As such, we empirically evaluated the impact of DejaVu in alleviating developers’ understanding of code class-level changes across multiple versions.


  Results:

  Our results showed an average of 52% reduction in completion time and a 51% increase in correctness of several change-comprehension tasks once, users adopted DejaVu in comparison to the manual completion of the same tasks. A student’s t-test verified the significant improvement in time and correctness of the tasks with p-values of 0.01 and 0.002.


  Conclusion:

  Visualizing aggregated information from multiple sources provides developers with a more comprehensive intuition of the change and its rationale, facilitating software maintenance tasks.
draft: false
url_pdf: https://www.sciencedirect.com/science/article/abs/pii/S0164121222001297
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2022-11-02T04:11:36.416Z
---
