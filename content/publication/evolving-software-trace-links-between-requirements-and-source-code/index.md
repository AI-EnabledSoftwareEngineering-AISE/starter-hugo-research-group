---
title: Evolving software trace links between requirements and source code
subtitle: ""
publication_types:
  - "2"
authors:
  - Mona Rahimi
  - Jane Cleland-Huang
doi: https://doi.org/10.1007/s10664-017-9561-x
publication: In *Empirical Software Engineering*
publication_short: In * ESE*
abstract: Traceability provides support for diverse software engineering
  activities including safety analysis, compliance verification, test-case
  selection, and impact prediction. However, in practice, there is a tendency
  for trace links to degrade over time as the system continually evolves. This
  is especially true for links between source-code and upstream artifacts such
  as requirements – because developers frequently refactor and change code
  without updating the links. In this paper we present TLE (Trace Link Evolver),
  a solution for automating the evolution of bidirectional trace links between
  source code classes or methods and requirements. TLE depends on a set of
  heuristics coupled with refactoring detection tools and informational
  retrieval algorithms to detect predefined change scenarios that occur across
  contiguous versions of a software system. We first evaluate TLE at the class
  level in a controlled experiment to evolve trace links for revisions of two
  Java applications. Second, we comparatively evaluate several variants of TLE
  across six releases of our in-house Dronology project. We study the results of
  integrating human analyst feed back in the evolution cycle of this emerging
  project. Additionally, in this system, we compare the efficacy of class-level
  versus method-level evolution of trace links. Finally, we evaluate TLE in a
  larger scale across 27 releases of the Cassandra Database System and show that
  the evolved trace links are significantly more accurate than those generated
  using only information retrieval techniques.
draft: false
url_pdf: https://link.springer.com/article/10.1007/s10664-017-9561-x
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2017-11-03T22:12:57.113Z
---
