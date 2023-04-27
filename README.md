# Technical Documentation Portfolio
_Writing samples and related work products_
<br>
David Welsch

Below are links to some of my work products. The technical documents listed here, both web-based and PDF, are publicly available on their respective companies' support and documentation websites. The videos listed below are publicly available on YouTube. The companies own the copyrights to all of their respective materials that I've liked to.

## Online Documentation for a Workflow Management API

During a short contract engagement with [Agnostiq](https://agnostiq.ai), I rewrote much of their documentation for the [Covalent](https://covalent.readthedocs.io/en/latest/) workflow scheduling system. 

### User Documentation

The latest _[Concepts](https://covalent.readthedocs.io/en/latest/concepts/concepts.html)_ and _[Web UI](https://covalent.readthedocs.io/en/latest/webapp_ui/index.html)_ sections are examples of my work.

### API Examples: Writing, Coding, and Testing

I rewrote the _[How-To](https://covalent.readthedocs.io/en/latest/how_to/index.html)_ examples in Jupyter notebooks, testing and in some cases rewriting the example code.

## Documentation Process and Infrastructure Development

I implemented a documentation process from scratch for memory software startup [MemVerge](https://memverge.com/), authoring their documentation in DITA using OxygenXML Editor. I [published the documentation online](https://docs.memverge.com/) and in PDF format, modifying OxygenXML's supplied CSS templates, managing and archiving the content in GitHub. I documented the process and trained other team members on the procedures and tools. The [Memory Machine](https://docs.memverge.com/topics/mvmm2.html) documents for release 2.4 and earlier are mostly my work.

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


