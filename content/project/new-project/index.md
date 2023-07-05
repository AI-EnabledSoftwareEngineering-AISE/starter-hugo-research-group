---
title: New Project
subtitle: ""
date: 2023-07-05T16:09:33.961Z
draft: false
featured: false
external_link: ""
links: []
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
---
The utilization of Deep Learning (DL) models in identifying security threats has
proven to be highly successful. However, these models have shown limitations in
generalizing to real-world scenarios due to their data-driven nature, leading to
learned patterns that are often biased. One of the reasons for this limitation is the
predominantly synthetic nature of the available training data, which lacks realism
and fails to adequately represent actual vulnerabilities. Furthermore, within the
field of cyber-security, the available data is scarce and restricted due to the
sensitive nature of the information. The heterogeneous nature of information
sources in this domain, combined with confidentiality concerns, hinders data
sharing in most use cases. While there are publicly available databases provided
by federal and private organizations, such as CVE, CWE, SARD, NVD, and CAPEC,
containing information about security weaknesses, vulnerabilities, exploitation,
and attack reports, these datasets are insufficient to fully train unbiased DL
models.
To address these challenges, we propose an approach in this project that
optimizes the learning process of DL models for vulnerability detection by
considering and combining multiple dimensions of the available information,
despite its limitations. Firstly, we demonstrate that various classes of
vulnerabilities in the C programming language exhibit similarities across multiple
dimensions, including semantic, contextual, and structural characteristics.
Exploiting this observation, we train multiple deep neural models to identify the
multi-dimensional similarities of vulnerabilities in C code. Lastly, we integrate the
findings of the DL models into a comprehensive report generated automatically,
enabling human experts to identify potentially unknown vulnerabilities based on
their similarities to the closest vulnerable instances.
In summary, our project focuses on enhancing the representation of source code
to improve the detection of unknown vulnerabilities. By incorporating multiple
dimensions of information, we aim to overcome the limitations of biased learned
patterns and provide a more comprehensive approach to identifying
vulnerabilities in real-world scenarios.