# Technical Documentation Portfolio
_Writing samples and related work products_
<br>
David Welsch

Below are links to some of my work products. The documents listed here are publicly available on their respective companies' or projects' documentation websites and GitHub repositories, and the videos are publicly available on YouTube. Copyrights belong to the respective companies and projects; open source documentation is subject to its project's license.

Since 2019 I have worked as a consultant with Expert Support Inc. The first five sections below are from Expert Support client engagements, most recent first.

## Documentation Analysis for the Cloud Native Computing Foundation

Since 2023 I have analyzed documentation for open source projects sponsored by the [Cloud Native Computing Foundation](https://www.cncf.io/) (CNCF), part of the Linux Foundation. I rewrote the analysis criteria, procedures, and templates; my revised process is now used for all CNCF project documentation analyses. I have completed analyses for seven projects: Backstage, etcd, in-toto, KEDA, Knative, LitmusChaos, and Vitess.

### Analysis Process and Templates

The criteria, procedure, and templates that CNCF analysts use to evaluate a project's documentation. These show how I designed a repeatable process that other writers could apply consistently.

_[CNCF Documentation Analysis: Criteria, Procedure, and Templates](https://github.com/cncf/techdocs/blob/main/docs/analysis/index.md)_

### Sample Documentation Analyses

Each analysis evaluates a project's documentation for content, organization, and usability for its audiences, then recommends specific improvements.

_[etcd Documentation Analysis (2023)](https://github.com/cncf/techdocs/tree/main/analyses/2023/etcd)_

_[Knative Documentation Analysis (2025)](https://github.com/cncf/techdocs/tree/main/analyses/2025/knative)_

### Documentation Primer for Project Contributors

A short primer for open source maintainers and contributors, most of them software engineers. It gives them a shared vocabulary and a process framework for discussing their project's documentation. It also addresses patterns common in developer-written documentation, such as describing how software works where users need step-by-step procedures.

_[Documentation Primer for CNCF Projects](https://github.com/cncf/techdocs/blob/main/docs/sandbox-doc-primer.md)_

### GitHub Issues from an Analysis

Each analysis ends with GitHub issues that turn its recommendations into specific, actionable tasks for project contributors. The links below follow the Knative analysis from start to finish. The first is an umbrella issue that collects all the issues identified in the analysis. The second is a typical issue from that analysis. The third is the pull request in which a project contributor addressed the second issue; the pull request is not my work, but it shows how the process plays out end to end.

- _[Umbrella issue: Knative documentation analysis](https://github.com/knative/docs/issues/6301)_
- _[Individual Knative issue: update technical overview](https://github.com/knative/docs/issues/6304)_
- _[Contributor pull request resolving that issue](https://github.com/knative/docs/pull/6321)_

## User Documentation for OpenSearch Dashboards

In two engagements with the [OpenSearch Project](https://opensearch.org/) in 2025 and 2026, I wrote Getting Started content, user guides, and UI documentation for OpenSearch Dashboards, covering dashboards, visualizations, and data exploration. Earlier, I documented aggregation functions. I built and tested the documentation locally with Jekyll, verifying the APIs and UI against a local OpenSearch instance.

### Landing Page

This landing page became the most-viewed page on the OpenSearch documentation site. The page has been modified several times since I last worked on it. The Markdown source on GitHub includes its edit history.

- _[OpenSearch Dashboards landing page](https://docs.opensearch.org/latest/dashboards/)_
- _[Markdown source on GitHub](https://github.com/opensearch-project/documentation-website/blob/main/_dashboards/index.md)_

### Getting Started and User Guide

A Getting Started guide for OpenSearch Dashboards and a user guide for its Visualize application. Both pages have been edited since my last changes, but they are substantively as I wrote them.

- _[Getting started with OpenSearch Dashboards](https://docs.opensearch.org/latest/dashboards/getting-started/index/)_
- _[Visualize application user guide](https://docs.opensearch.org/latest/dashboards/visualize/visualize-app/index/)_

## Documentation Conversion for NVIDIA CUDA

From 2024 to 2026 I worked with NVIDIA engineers and other documentation consultants to convert about 60 CUDA and related documents, ranging from license agreements to programming guides several hundred pages long, from DITA through two reStructuredText-based formats. The conversion had been in progress for over three years when I completed it.

The tools and methods were proprietary to NVIDIA, so I can describe the process only in general terms.

My main responsibility was converting the documents from a source format based on an early (0.5-era) release of reStructuredText to one based on release 1.8. I worked with the documentation build engineer, the engineer who wrote the original conversion scripts, and another consultant who converted documents from DITA to the 0.5-based format. The work included:

- Splitting monolithic document files into chapter files
- Modifying an omnibus Python configuration so that every document built without errors
- Regression testing the conversion process
- Building the HTML and PDF documents from source locally to troubleshoot issues
- Running mock builds in Perforce to regression test the CI/CD build

The CUDA Toolkit documentation home page links to the full documentation set; the CUDA Programming Guide is a sample HTML document from it.

- _[CUDA Toolkit documentation](https://docs.nvidia.com/cuda/)_
- _[CUDA Programming Guide](https://docs.nvidia.com/cuda/cuda-programming-guide/)_

## Online Documentation for a Workflow Management API

During a short contract engagement with [Agnostiq](https://agnostiq.ai), I rewrote much of their documentation for the [Covalent](https://covalent.readthedocs.io/en/latest/) workflow scheduling system. (Covalent has since been acquired by DataRobot.)

### User Documentation

The latest _[Concepts](https://covalent.readthedocs.io/en/latest/concepts/concepts.html)_ and _[Web UI](https://covalent.readthedocs.io/en/latest/webapp_ui/index.html)_ sections are examples of my work.

### API Examples: Writing, Coding, and Testing

I rewrote the _[How-To](https://covalent.readthedocs.io/en/latest/how_to/index.html)_ examples in Jupyter notebooks, testing and in some cases rewriting the example code.

## Documentation Process and Infrastructure Development

From 2019 to 2022 I was the sole technical writer for software-defined memory startup [MemVerge](https://memverge.com/). I set up the documentation process from scratch: authoring in DITA with Oxygen XML Editor, publishing online and in PDF with customized versions of Oxygen's CSS templates, and managing the content in GitHub. I documented the process and tools and trained new and temporary writers to use them. The Memory Machine documentation through release 2.4 is mostly my work. MemVerge's current online documentation covers later releases.

The sample below is a PDF guide for Memory Machine, published with the CSS templates I developed.

_[Memory Machine Resiliency Guide, Release 2.0 (PDF)](https://github.com/Omphaloskepsis/writing-portfolio/blob/main/memverge/mvmm_resiliency_guide_2_0.pdf)_

## User and Programmer Documentation for Software-Defined Networking

I worked from 2015 to 2019 on Cisco's Unified Computing System (UCS) Director, a software product to deploy, provision, configure, and network data center resources. (Such systems are often called SDN, for "software-defined networking," though most do far more than provision networks.)

### Getting Started and User Guides

_[Cisco UCS Director Orchestration Guide, Release 6.7](https://www.cisco.com/c/en/us/td/docs/unified_computing/ucs/ucs-director/orchestration-guide/6-7/cisco-ucs-director-orchestration-67.html)_

This is a guide to using UCS Director Orchestration, a library of tasks (and supporting tools) for creating workflows to deploy, provision, and configure data center resources. I reorganized and substantially rewrote the guide beginning with Release 5.4. 

_[Cisco UCS Director Open Automation Getting Started Guide, Release 6.6](https://www.cisco.com/c/en/us/td/docs/unified_computing/ucs/ucs-director/open-automation-getting-started-guide/6-6/cisco-ucs-director-open-automation-getting-started-66.html)_

One of a set of guides, new with Release 5.4, for "bootstrapping" developers' use of various SDKs and APIs related to Cisco UCS Director. Open Automation is a toolkit for adding third-party components such as storage devices to the entities controllable by UCS Director.

### API Reference for SDN Scripting

_[UCS Director Task Library Reference, Release 6.7](https://www.cisco.com/c/en/us/td/docs/unified_computing/ucs/ucs-director/task-library-reference/6-7/cisco_ucs_director_task_library_reference_6700.html)_

Work on this Cisco document included generating and extracting information from software code comments and annotations and presenting it in reference form. In cooperation with leads from the software development team, I drove the project end-to-end. Some of the tasks I was responsible for:
- Wrote formatting instructions and a style guide for software engineers to write task documentation.
- Edited developer-written task documentation.
- Developed a process to convert an HTML version of the reference into Cisco's standard documentation format. Used Python, XSLT, regex, and publishing tools that included the DITA Open Toolkit.
- Worked with a development manager and an architect to:
  - Prioritize which tasks to document (there are almost 3000 tasks in over 100 categories).
  - Create a change log for existing tasks.
  - Enable technical writers to check work product into the codebase.

### Videos

_[Cisco UCS Director Device Discovery](https://www.youtube.com/watch?v=hkhvwo1pbmk&list=PLIlKAL_0d4EzcD9Eb5Xeff6eDIUwD3Bm2&index=3&t=0s)_

_[Cisco UCS Director - Deploying and Configuring Bare Metal Agent](https://www.youtube.com/watch?v=S380fK6Q0ys&list=PLIlKAL_0d4EzcD9Eb5Xeff6eDIUwD3Bm2&index=8&t=0s)_

I wrote and edited scripts and recorded the screen captures for these Cisco product demonstration videos. I liaised with our videographer to produce the videos.
