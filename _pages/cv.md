---
layout: archive
title: "Curriculum vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
- Ph.D. in Computer Science, Artificial Intelligence
    - Graduated June 2020
    - University of California San Diego
    - Advisor: [Kamalika Chaudhuri](http://cseweb.ucsd.edu/~kamalika/)
- M.S. in Computer Science
    - Received 2016
    - University of California San Diego
- B.S. Mathematics, B.S. Computer Science
    - Graduated 2014
    - University of California Irvine

Work experience
======
* Summer 2018: AI Research Intern
  * Amazon
  * Location: Cambridge, UK
  * Supervisors: Borja Balle, Tom Diethe

* 2014 - 2020: Graduate Student Researcher, Teaching Assistant
  * University of California San Diego
  * Advisor: Kamalika Chaudhuri

* 2019 - 2020: Associate-In (teaching a course)
  * University of California San Diego
  * Instructor Of Record
  * Taught upperdivision undergraduate courses, ranging from 40 to 100 students per section
  * Managed teams of 4 or more teaching assistants and tutors

Skills
======
* Applied and Theoretical Machine Learning
  * Differential Privacy
  * Privacy Preserving Bayesian Data Analysis
  * Renyi Differential Privacy
  * Alternative Privacy Definitions
* Mathematics
  * Linear Algebra
  * Abstract Algebra
  * Real Analysis
  * Measure Theory
* Programming
  * C++
  * Python
  * R, MATLAB
  * Linux Input Event Handling, Userspace Device Drivers
* Teaching
  * Effective Online Course Design
    * Canvas LMS, Blackboard LMS
    * Lecture Video Production
    * Formative and Summative Feedback
  * Universal Design for Learning

Publications
======
{% assign sortedpubs = site.publications | sort: 'date' | reverse %} 
  <ul>{% for post in sortedpubs %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
