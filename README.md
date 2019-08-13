# Technical Documentation Portfolio
_Writing samples and related work products_
<br>
David Welsch

I worked from 2015 to 2019 on Cisco's Unified Computing System (UCS) Director, a software product to deploy, provision, configure, and network data center resources. (Such systems are often called SDN, for "software-defined networking," though most do far more than provision networks.)

Below are links to some of my work products. The links to Cisco technical documents are publicly available on Cisco's support website. The videos listed below are publicly available on YouTube. Cisco Systems owns the copyright to all of the linked materials.

## User and Developer Guides

These documents involve English-language explanation of concepts and tasks to a technical audience, primarily IT, DevOps and software development professionals. Complexity of the material is moderate to high.

### _[Cisco UCS Director Orchestration Guide, Release 6.7](https://www.cisco.com/c/en/us/td/docs/unified_computing/ucs/ucs-director/orchestration-guide/6-7/cisco-ucs-director-orchestration-67.html)_
A guide to using UCS Director Orchestration, a library of tasks (and supporting tools) for creating workflows to deploy, provision, and configure data center resources. I reorganized and substantially rewrote the guide beginning with Release 5.4. 

### _[Cisco UCS Director Open Automation Getting Started Guide, Release 6.6](https://www.cisco.com/c/en/us/td/docs/unified_computing/ucs/ucs-director/open-automation-getting-started-guide/6-6/cisco-ucs-director-open-automation-getting-started-66.html)_
One of a set of guides, new with Release 5.4, for "bootstrapping" developers' use of various SDKs and APIs related to Cisco UCS Director. Open Automation is a toolkit for adding third-party components such as storage devices to the entities controllable by UCS Director.


## API Reference

Work on this document included generating and extracting information from software code comments and annotations and presenting it in reference form. In cooperation with leads from the software development team, I drove the project end-to-end. Here are some of the tasks I was responsible for:
- Wrote formatting instructions and a style guide for software engineers to write task documentation.
- Edited developer-written task documentation.
- Developed a process to convert an HTML version of the reference into Cisco's standard documentation format. Used Python, XSLT, regex, and publishing tools that included the DITA Open Toolkit.
- Worked with a development manager and an architect to:
  - Prioritize which tasks to document (there are almost 3000 tasks in over 100 categories).
  - Create a change log for existing tasks.
  - Enable technical writers to check work product into the codebase.

### _[UCS Director Task Library Reference, Release 6.7](https://www.cisco.com/c/en/us/td/docs/unified_computing/ucs/ucs-director/task-library-reference/6-7/cisco_ucs_director_task_library_reference_6700.html)_

## Videos

I wrote and edited scripts and recorded the screen captures for the following product demonstration videos. I liaised with our videographer to produce the videos.

### _[Cisco UCS Director Flexpod Configuration](https://www.youtube.com/watch?v=GXeUi3zGUrk&list=PLIlKAL_0d4EzcD9Eb5Xeff6eDIUwD3Bm2&index=4&t=0s)_

### _[Cisco UCS Director Device Discovery](https://www.youtube.com/watch?v=hkhvwo1pbmk&list=PLIlKAL_0d4EzcD9Eb5Xeff6eDIUwD3Bm2&index=3&t=0s)_

### _[Cisco UCS Director - Deploying and Configuring Bare Metal Agent](https://www.youtube.com/watch?v=S380fK6Q0ys&list=PLIlKAL_0d4EzcD9Eb5Xeff6eDIUwD3Bm2&index=8&t=0s)_
