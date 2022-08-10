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
* Master Degree in Mathematics and Applications Specialty Mathematical Engineering Financial Engineering and Random Models, Sorbonne University, 2014-2016
* Certification In Big Data, Sorbonne University, 2015-2016
* Master Degree in Actuarial Science, ISUP, 2017-2019 (expected)
* Ph.D in Data Science/Insurance, Sorbonne University, 2017-2020 (expected)

Work experience
======
* August 2020 - Today: Machine Learning Engineer, PacketAI
  * Creating and deploying an anomaly detection model in log sequence streams (on Tensorflow)
  * Working on a scalable method for log parsing
  * Creating preprocessing function for Time Series and Log files

* March 2017 - March 2020: PhD, LPSM (Sorbonne University) and Pacifica (CAA)
  * Using text to predict the severity of a claim. Predicted cost 40% better than traditional figures (on Tensorflow, Pyspark)
  * Programming on GPU (on AWS and local)
  * Combining Deep Learning models (LSTM and CNN) on a temporal
dataset containing structured and unstructured data
  * Creating a Graphic tool to interpret Grid Search and Model results (on Plotly)

* September 2016 - February 2017: P&C Actuarial Science, Pacifica (CAA)
    * Extreme Value Theory.
    * Impact of bodily injury claims.

* March 2016 - August 2016: P&C Actuarial Science (Internship), Pacifica (CAA)
    * Studying the geographical component on a bodily claim on Life Accident Guarantee
    * Challenging GLM, Random Forest and Gradient Boosting for modeling Average Cost and Frequency. Improvement of the loss by two (on Scikit-Learn)
  
Skills
======
* Programming
  * Python
  * R
  * C++
  * Julia
  * C
  * Cuda
* AWS
* Docker
* Python packages
  * Tensorflow
  * PyTorch
  * Scikit-Learn
  * Plotly
  * Matplotlib

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

MOOC
======
  <ul>{% for post in site.mooc %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>