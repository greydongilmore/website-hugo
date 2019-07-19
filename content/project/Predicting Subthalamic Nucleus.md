+++
# Date this page was created.
date = 2016-04-27T00:00:00

# Project title.
title = "Electrophysiology Predictive Models"

# Project summary to display on homepage.
# summary = "Optimal targeting of the subthalamic nucleus (STN) for Parkinson disease is essential to the clinical outcome. Machine learning, using # single and multi-unit spike recordings from the operating room, will be used to estimate STN boundaries and optimal electrode placement."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "project_icons/spikeTrace.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Machine Learning", "Deep brain stimulation"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++
<DIV align="justify">
Deep brain stimulation of the subthalamic nucleus (STN) has been shown to benefit individuals living with Parkinson disease. The STN is a very small surgical target (7.0mm x 4.0mm), which makes targeting the nucleus very difficult. Furthermore, the sensorimotor subdivision of the STN is the optimal target location for optimal clinical motor symptom improvement. This subdivision is a much smaller region located in the dorso-lateral aspect, recent studies have show characteristic signal features in this area. 

<img src = "/img/featureExample.png"></img>

The figure above shows an example feature, Teager energy, extracted from the raw brain recording data. The depth values indicate distance from the surgically planned target (negative values above, positive values below), there are 5 electrodes used during the recording. This figure illustrates that as the electrodes enter the STN, the Teager energy increases above the avergae (dotted line) and indidates that the electrodes have entered a nucleus. Using various features, extracted from the raw signal, this project aims to build a predictive model that informs the surgeon of the most optimal surgical implantation site. 

The ability to train a predictive model that is capable of estimating the dorsal/ventral borders of the STN, as well as the sensorimotor aspect, would reduce surgery time and improve patient outcome. 
</DIV>
