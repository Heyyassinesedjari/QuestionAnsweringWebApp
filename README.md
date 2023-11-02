# Question Answering Web Application

[![Discord](https://img.shields.io/discord/823720615965622323.svg?style=for-the-badge)](https://discord.gg/DGxZRP3qeg)
[python](https://img.shields.io/badge/Python-3.9.12-green)
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg?style=for-the-badge)](https://github.com/alelievr/Mixture/blob/master/LICENSE)
[![Documentation](https://img.shields.io/badge/Documentation-github-brightgreen.svg?style=for-the-badge)](https://alelievr.github.io/Mixture/manual/GettingStarted.html)

## A fully functional web application that answers factoid questions in arabic or english and written in Python.

This project is a part of my Introduction to Natural Language Processing course at [ENSIAS](https://fr.wikipedia.org/wiki/%C3%89cole_nationale_sup%C3%A9rieure_d%27informatique_et_d%27analyse_des_syst%C3%A8mes), [Mohammed V University](https://en.wikipedia.org/wiki/Mohammed_V_University). When selecting a project for the class, I chose to focus on Question and Answering, a part of NLP. Back then, ChatGPT and Language Models were quite popular, and I was very interested in understanding how these technologies function. However, these topics were rather advanced, so my professor advised me to proceed gradually. I began with a basic Q&A project, aiming to grasp the fundamentals of NLP. This initial step was meant to prepare me for deeper exploration into the world of LLMs.

Every part of this project is sample code which shows how to do the following:

* Create an open-domain Arabic and English question answering system using Python.
* Implement a Document Retriever using wikipedia api.
* Implement a Document Reader using both [distilbert-base-cased-distilled-squad](https://huggingface.co/distilbert-base-cased-distilled-squad) and [AraElectra-Arabic-SQuADv2-QA](https://huggingface.co/ZeyadAhmed/AraElectra-Arabic-SQuADv2-QA) models through api calls to HuggingFace server using inference api.
* Create a Messenger like web application using Flask, HTML, CSS and JavaScript.

## Getting Started (Ubuntu/Debian)
* Install Git
  ```bash
  sudo apt update
  sudo apt install git
* Navigate to the Directory
  ```bash
  cd path/to/desired/location
  
* Clone this repository
  ```bash
  git clone https://github.com/Heyyassinesedjari/QuestionAnsweringWebApp.git
* Install Conda
  ```bash
  wget https://repo.anaconda.com/miniconda/Miniconda3-4.12.0-Linux-x86_64.sh
  bash Miniconda3-4.12.0-Linux-x86_64.sh
  source ~/.bashrc

* Creating a Conda Environment
  ```bash
  conda create --name myenv python=3.9.12
* Activate Conda Environment and Install all requirements
  ```bash
  conda activate myenv
  conda install --file path_to_requirements.txt
* Run the App
  ```bash
  python app.py

## High-level functional explanation

### Q&A System Architecture Diagram
<img src="https://github.com/Heyyassinesedjari/QuestionAnsweringWebApp/assets/94799575/ced251a7-9413-4dc0-8f0e-beac07ba3668" width="70%" height="70%">

### Document Retriever Architecture Diagram
<img src="https://github.com/Heyyassinesedjari/QuestionAnsweringWebApp/assets/94799575/602dad7c-bbd6-42a4-837d-a90e797ab187" width="70%" height="70%">

### Document Reader Architecture Diagram
<img src="https://github.com/Heyyassinesedjari/QuestionAnsweringWebApp/assets/94799575/ced251a7-9413-4dc0-8f0e-beac07ba3668" width="70%" height="70%">

### Application Sequence Diagram
<img src="https://github.com/Heyyassinesedjari/QuestionAnsweringWebApp/assets/94799575/83f19996-94c1-4be5-ba6f-ef1ff1329bbd" width="70%" height="70%">

###  Video Demo
https://github.com/Heyyassinesedjari/QuestionAnsweringWebApp/assets/94799575/5bd7fd0f-f1a5-409f-91ef-5dafd6d35a80

### Project Defense Presentation (Google Slides)
https://docs.google.com/presentation/d/1vQKFpJJx6TmtOgJ8upJHEEu_9QU-tWXH/edit?usp=sharing&ouid=100061785569173216725&rtpof=true&sd=true

