---
layout: archive
title: "Resume"
permalink: /resume/
author_profile: true
redirect_from:
  - /cv
---

{% include base_path %}

### Education

* M.S. Computer Science, Georgia Institute of Technology, 2030 (expected)
* B.S. Computer Science Mathematics, University of Texas at Austin, 2025
  * GPA: 3.83

### Technical Work Experience

* Production Engineer, Enterprise Infrastructure & Security, Meta
  * Tests, develops Terraform plugins for unified lifecycle management of services & infrastructure
    * Implemented CRUD operations for storage volumes, virtual machines, networks, with polling resumption
    * Added 10+ Terraform resource tests, caught 100+ potential errors in code changes before merge
  * Manages fleet of ~9k baremetal, ~22k virtual hosts for internal Meta services, monitors & fixes service gaps
    * Built end-to-end testing for corp virtual machine provisioning, detected 10+ provisioning service errors

* Software Dev Engineer Intern, Echo Board Platform Software, Amazon
  * Implemented 50+ tests for 200+ types of Amazon devices, eliminated device, OS discrepancies for users
  * Built testing abstraction across 4 OS for 100+ Amazon engineers, saving 20 hrs/wk in testing
  * Enabled 60+ nightly tests to migrate from outdated testing framework, reduced false error rate by 90%

* Software Engineering Intern, Tenant Lifecycle, Benchling
  * Built configuration migration history tracking for 1000+ enterprise Benchling clients with Python, React
  * Created flexible data table, connection to 1m+ Amazon S3 storage entries using Layered Architecture
  * Modernized config. migration user interface, developed new card-based components for history display

* Software Engineering Intern, Payment Devices, The Home Depot
  * Built bridging API using Golang, extending device tracking for store associates to include 90000+ PIN pads
  * Streamlined data flow from checkout lanes to associates with custom database, with device error identification
  * Supports data analytics and store cybersecurity by providing reliable logging of PIN pad activities

* Undergraduate Research Intern, Scalable Health Lab, Rice University
  * Classified 2+ mil. food diary entries with word embedding without labelled data or computing server access
  * Converted processed entries to 5000+ graphs of dietary correlations using NetworkX, USDA food categories
  * Used neural networks to identify health attribute predictors in diet using MatPlotLib from graphs
  
### Skills

* Python
  * Service development via Flask
  * Data visualization via Matplotlib, etc.
* Terraform
  * Plugin development
* Linux
* Golang

### Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- ### Conferences

  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->
  
### Teaching

  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
### Service and leadership

* Texas Exes New York Chapter
  * Board Member, Tech, 2025 - Present
* Texas Product Engineering Organization
  * Engineering Fellow, 2022 - 2025
  * Co-Events Director, 2024 - 2025
* Texas Association for Computing Machinery
  * Webmaster, 2023 - 2024
