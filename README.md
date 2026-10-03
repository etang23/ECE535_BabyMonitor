# ECE 535 Smart Baby Monitor 

# Motivation:
It's very difficult for parents to be around their babies all the time, so there needs to be a reliable way for parents to monitor their babies. They need to know where their baby is and how he/she feels. A smart baby monitor can help with this. It can detect unusual activities and alert parents. It can also detect activities like sleeping, crying, and playing. Furthermore, parents will be able to take a shower or cook while keeping an eye on their baby. Overall, a baby monitor will give parents safety and peace of mind. 

# Design Goals:
We will be using Visual Language Models (VLMs) to design a baby monitoring system. This system will be able to detect and report to the parents what their babies are doing like sleeping, crying, and playing with their toys using images or short video frames. We will be running this system on our laptops using CUDA and a goal of ours is to keep the information being taken private.

# Deliverables:
1. A written understanding of how VLMs can be adapted for activity recognition.
2. Implement a basic VLM pipeline that analyzes baby images or frames and determines whether the baby is awake, sleeping, or crying.
3. Natural language summaries of detected activities.
4. (OPTIONAL) An alerting mechanism: a rule that prints warning or sound alarms if the baby is crying.
5. A code snippet that demonstrates taking an image as input and outputs an activity classification and a short report.

# System Blocks:

# Hardware/Software Requirements:
Python, OpenCV library, Laptop with CUDA-enabled GPU

# Team Member Responsibilities:
Eric Tang: README/Report, Research, VLM Pipeline, Software, Networking
Jan Ralph Lujares: README/Report, Research, CUDA/Colab Setup, Algorithm Design, Software
Paulan Huang: README/Report, Research, Dataset search, Documentation/Writing, Software

# Project Timeline:

# References:
- https://arxiv.org/abs/2306.14895
- https://huggingface.co/docs/transformers/main/en/model_doc/llava
