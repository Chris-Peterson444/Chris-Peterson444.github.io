---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Masters in Computer Science
	- University of California, Davis - 2022
* Bachelors in Computer Science and Engineering
	- Minor: Mathematics
	- University of Nevada, Reno - 2020
* Associates in Physics, Mathematics, and Natural Science
	- Sierra College - 2017
<!-- * A.S.-T. in Physics and Mathematics -->
<!-- 	- Sierra College - 2017 -->

[//]: # (* Ph.D in Version Control Theory, GitHub University, 2018 (expected))

Academic and Research Experience
======
* Graduate Student Researcher - Computational Linguistics Lab, University of California, Davis - Sept 2020 - July 2022
    - *Efficient Neural Semantic Parsing for Low-Resource Languages*: Developed a methodology to generate efficient neural models for semantic parsing in the zero-shot setting.
    Models generated using this methodology demonstrated competitive results to the current state-of-the-art work while requiring just 3% of the computational resources.
* Undergraduate Research Assistant - Robotics Research Lab, University of Nevada, Reno - Aug 2018 - Aug 2020
    - *Camera-to-2D-LiDAR Calibration Method*: Developed a new method of feature correspondence between lidar and rgb camera sensors capable of calibrating a multi-sensor system from a single sample without a priori information about the calibration target geometry.
    - *Intent Recognition System for PR2 Robot*: Assisted in developing an artificial intelligence human-intent recognition system to enable socially aware navigation of robotic platforms in a multi-agent setting.
    - *Pioneer3-DX Gazebo/ROS simulation*: Designed simulation and control code, as well as a custom simulation model, for a Pioneer3-DX in Gazebo.

* Undergraduate Researcher - Summer 2019
	- Research Experience for Undergraduates - University of Nevada, Reno - Human Robot Interaction
		- *Perceptions of Computer-Generated Speech for Social Robotics*: National Science Foundation sponsored research to investigate the existence of vocal-pitch-based stereotypes of social robots in human robot interaction.


Skills
======
* Programming:
	- Comfortable: C/C++, Python, PyTorch, NumPy, Git, LaTex, Linux, Bash
	- Familiar:  Java, Swift, Keras, Tensorflow, OpenCV, Robot Operating Sytem (ROS), Gazebo


Accepted Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


Teaching Experience
======
* Teaching Assistant - Mar 2022 - Jun 2022
	- MAT 17B: *Caculus for Biology and Medicine II* - UC, Davis
		- Weekly discussion sections to review course materials;
        review sessions before exams;
        proctoring and grading exams, including extensive feedback and post-exam follow up to encourage students to learn from mistakes;
        bi-weekly office hours;
        and bi-weekly tutoring hours to help students with a wide range of topics such as beginner algebra, calculus, linear algebra, and differential equations;

* Teaching Assistant - Jan 2022 - Mar 2022
	- MAT 17A: *Caculus for Biology and Medicine I* - University of California, Davis
		- Weekly discussion sections to review course materials;
        review sessions before exams;
        proctoring and grading exams, including extensive feedback and post-exam follow up to encourage students to learn from mistakes;
        bi-weekly office hours;
        and bi-weekly tutoring hours to help students with a wide range of topics such as beginner algebra, calculus, linear algebra, and differential equations;

* Teaching Assitant - Sep 2020 - Dec 2020
	- ECS 122A: *Algorithm Design and Analysis* - University of California, Davis
		- Independently preparing weekly discussion sections to teach course material;
        exam prep and review sessions;
        preparing exams and solutions;
        grading exams, including extensive feedback and post-exam follow up to encourage students to learn from mistakes;
        and 5 hours of private and public office hours per week.

* Teaching Fellow - Fall 2019
	- CS 482/682: *Artificial Intelligence* - University of Nevda, Reno
	- Led review sesssions, validated course materials, and graded assignments and exams for an undergraduate/graduate level course (approx. 65 students).

Other Projects
======

* **SoundsLike**: A multi-approach text-classifier which uses phonological features
to determine word sentiment and similarity; Python, OpenNMT

* **NLP with Disaster Tweets**: A neural text-classifier to help first responders
determine if tweets about a disaster are real or fictitious; Python, PyTorch

* **GhostOS**: A POSIX-compliant kernel and Operating System, as well as a small game,
to run on RISC-V architecture; C, Assembly, Docker

* **Minerva**: An iOS application utilizing Apple's CoreML framework to enable
deployment of GPU-based TensorFlow Style Transfer models onto mobile devices
for CPU-based inference; Swift, TensorFlow, CoreML

* **Parallel Optimizations to Genetic Algorithm solutions for the Chinese Postman Problem**:
An efficient cache-based optimization for a GPU-accelerated Genetic
Algorithm-based solution to the k-Chinese Postman problem, with a resulting
2.5x speedup; Python, C++, CUDA

Honors & Awards
=======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* GE Coding Competition Award for Intermediate - Second Place
