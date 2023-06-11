---
title: Leveraging code-test co-evolution patterns for automated test case
  recommendation
subtitle: Samiha Shimmi, Mona Rahimi
publication_types:
  - "1"
authors:
  - Hamed Barzamini
  - Mona Rahimi
doi: https://doi.org/10.1145/3524481.3527222
publication: In *Proceedings of the 3rd ACM/IEEE International Conference on
  Automation of Software Test*
publication_short: In *AST*
abstract: >-
  Context: Prior research revealed that code components with similar structures
  tend to require structurally similar test cases and they often co-evolve over
  time. Objective: Leveraging this pattern, we implemented a prototype tool,
  Test Suite Evolver (TSE), to support the generation of test cases for
  structurally similar methods. Our prototype tool is applicable to both,
  incomplete test suites with the purpose of test case augmentation, as well as
  evolving test suites when a newer version of a software becomes available.


  Method: Making use of the aforementioned code-test co-evolution pattern, TSE leverages source code structural similarity and a set of existing test cases to synthesise and recommend new unit tests. For this, TSE initially identifies groups of structurally similar methods in the code, determines changes at the token-level, and integrates the retrieved information to synthesise updated test cases.


  Results: Our evaluations indicated that 38% of the source code of five large open-source applications consist of methods which are structurally similar to each other and therefore for which, the co-evolution pattern holds. Applying TSE to these methods, TSE generated 72% of the minimum required test cases with only 11% token-based edit distance between the generated test cases and those written by developers. To evaluate the test cases' validity, we used code2vec a neural network to measure the structural and semantic similarity between the generated and developed test cases. The results indicated that TSE successfully generated test cases with a similarity measure of more than 80% in more than 95.6% of test cases and similarity measure of 100% for 88.35% of the test cases. Conclusion: The evaluations revealed that TSE is able to generate the majority of the necessary test cases with an insignificant amount of modifications required from the developers.
draft: false
url_pdf: https://www.researchgate.net/profile/Hamed-Barzamini/publication/365120599_CADE_The_Missing_Benchmark_in_Evaluating_Dataset_Requirements_of_AI-enabled_Software/links/63d5f44bc465a873a267858c/CADE-The-Missing-Benchmark-in-Evaluating-Dataset-Requirements-of-AI-enabled-Software.pdf
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2022-06-17T16:24:00.521Z
---
