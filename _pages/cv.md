---
layout: archive
title: "Curriculum vitae (CV)"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Downloadable PDF: [Here](https://mmrahman-utexas.github.io/files/Md_Mesbahur_Rahman_CV_Edu_August_2023.pdf)

Cover Letter
------
I work at [DeepX, Inc.](https://www.deepx.co.jp/), where I research and develop computer vision solution for Heavy machinery Automation projects. I helped build automatic inspection software system based on classical computer vision algorithm in DeepX. Currenly I have also developed point cloud filters and image processing algrothms for bev_image information retrieval. I am also doing a Masters in Computer Science at the University od Texas at Ausin and I am very close to my graduation. Before joining DeepX, I worked in Hiperdune Corporation as AI Engineer. In Hiperdyne, I worked in ml projects for some of the promient technology company namely Sony Computer Science Lbaoratories and Sony network and Communications (Sonet Inc.) and developed effective machine learning products which was deployed in real world applications.

Education
------
* **M.S. in Computer Science, The University of Texas at Austin (expected Dec 2023)**
  * GPA: 3.81 on 4.0 ([Latest Transcript](https://github.com/mmrahman-utexas/files/University_of_Texas_Academic_Summary.pdf))
  * Coursework ("A" grades): Deep Learning, Advanced Linear Algebra for Computing, Machine Learning, Natural Language Processing, Online Learning and Optimization.
* **B.Sc. in Electrical and Electronics Engineering, Bangladesh University of Engineering and Technology, 2017**
  * Thesis: Machine Learning for Anomaly-based Network Intrusion Detection, supervised by Dr. Mahesh Shirole.
  * GPA: 3.69 on 4.0 ([Transcript](https://github.com/mmrahman-utexas/files/MD_MESBAHUR_RAHMAN_Bangladesh_University_of_Engineer_&_Tech_Transcript.pdf))


Work experience
------

* **Feb 2022 - Present: Computer Vision Engineer, DeepX Inc., Tokyo, Japan**
  * Created real image dataset of industrial sample products by creating scratch and dents defect on them and taking images using industrial grade camera, lens and lighting equipment. Designed and implemented rule-based computer vision algorithms for scratch and dent defect detection in images of industrial sample products. Some of the notable implemented rule-based AD methods are “Adaptive Thresholding”, “Edge Detection”,
  “Morphology”, “FFT Bandpass filtering”, “Texture Entropy Analysis”, “Texture Laws Filtering” etc. which were implemented using Halcon and OpenCV frameworks. These algorithms were developed as part of the project (ongoing) of “Automation of Design Process of Visual Inspection System (Imaging Conditions and Inspection Algorithms)”.
  * Designed and developed a ROS2 based pass-through range filter in C++ for removing points of a pyramid shape building from a PointCloud using a geometry-based filtering. Generated simulation PointCloud test data and deployed the filter on site after testing its performance on real PointCloud test data.
  * Designed and developed an heightmap in-painting algorithm by identifying the convexhull of the missing areas and then extending the edge of the missing area linearly vertically along the direction of image gradients and vertically along the direction of a tunable slope angle up to a user defined height. Used image processing functions and tools from OpenCV, Scikit-Image and NumPy to implement the linear in-painting algorithm for filing in the missing pixel in a heightmap generated from a PointCloud.

* **Nov 2018 - Jan 2022: AI Engineer, Hiperdyne Corporation, Tokyo, Japan**
  * Annotated images of five categories of optical fiber construction objects using “labelImg”, an image annotation tool and modified the annotation output format to meet the specific need of the project. Then Fine-tuned a custom yolov4 model with pre-trained weight set to detect five categories of objects in the input images and then built a prototype python application for cropping into the input images for the detected five categories of objects or classifying the object images using the bounding box predicted by the yolov4 algorithm and organized the detected object images into five corresponding folders as per requirement of So-net (Sony Network Communications Inc.).
  * Designed and developed a python library in modular fashion for music information retrieval (e.g., beat, chord, genre, mood, bpm, segment prediction etc.) from input wav or mp3 song file using machine learning and Deep learning models for Sony CSL (Sony Computer Science Laboratory). Also built a command line python application to show the usage of the library. Also was in charge of adding new features to the library and multiple OS support to the library.
  * Implemented sequence classification using hierarchical attention for an LSTM sequenceAutoencoder on LibROSA extracted features to classify error pattern in beat tracking done by a proprietary music analysis tool for Sony CSL (Sony Computer Science Laboratory) at Hiperdyne Corporation.
  * Trained various deep learning model and machine learning model on a structured dataset by extracting numerous music related features from mp3 files using a proprietary music analysis tool and pre-processing them by exploratory data analysis and achieved beyond state of the art for predicting multi-label genre/mood of a song for Sony CSL (Sony Computer Science Laboratory) at Hiperdyne Corporation.
  * Implemented different machine learning and deep learning architecture to solve a multilabel classification problem for predicting various lyric-theme of a song lyrics in text form for a client company at Hiperdyne Corporation. Used frameworks like Scikit-Learn and Keras to train on features extracted using TF-IDF and Word2Vec to achieve best in class multi-label F1 score lyric-theme prediction model.
* **Sep 2018 - Nov 2022: Lecturer, Uttara University, Dhaka, Bangladesh**
  * Taught academic courses at the department of Electrical and Electronic Engineering in ttara University, Dhaka, Bangladesh.

  
Skills
------
* **Programming Languages**
  * Proficient (used at work): Python, C++
  * Familiar:  C, MATLAB, Assembly, SQL, JavaScript
* **Tools and Frameworks**
  * Data Science: PyTorch, Keras, Pandas, NumPy, HuggingFace Transformers, NLTK, TextBlob, SciPy, Matplotlib, Seaborn.
  * Image Procesing: OpenCV, Halcon
  * Point CLoud Processing: PCL, Open3D
  * Software Development: Git, Docker, Conda, pytest, ROS2
  * Academic: LaTeX, paperswithcode.com.
* **Industry Knowledge:**
  *  Object-Oriented Programming, Machine Learning, Deep Learning, Data Science, Computer Vision, Natural Language Processing, Reinforcement Learning, Robotics SOftware Development, Sofware Engineering
* **OS & Development Platform:**
  * Windows, Linux, macOS, Docker, AWS (Sagemaker, EC2, S3), Google Colab
* **Language Skills:**
  * Bangla, English, Hindi, Japanese (N5 Level), Korean (Basic)

Teaching
------
<!-- <i class="fas fa-link" aria-hidden="true"></i> <a href="https://mmrahman-utexas.github.io/teaching/">Details</a> -->
  <ul>{% for post in site.teaching %}
    {% include archive-single-short-teaching.html %}
  {% endfor %}</ul>

Projects
------
<i class="fas fa-link" aria-hidden="true"></i>  <a href="https://mmrahman-utexas.github.io/projects/">Details and Contribution</a>
<ul>{% for post in site.projects reversed %}
  {% include archive-single-short-project.html %}
{% endfor %}</ul>


