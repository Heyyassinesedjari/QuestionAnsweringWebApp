# Question Answering Web Application

## A fully functional web application that answers factoid questions in arabic or english and written in Python.

This project is a part of my Introduction to Natural Language Processing course at [ENSIAS](https://fr.wikipedia.org/wiki/%C3%89cole_nationale_sup%C3%A9rieure_d%27informatique_et_d%27analyse_des_syst%C3%A8mes), [Mohammed V University](https://en.wikipedia.org/wiki/Mohammed_V_University). When selecting a project for the class, I chose to focus on Question and Answering, a part of NLP. Back then, ChatGPT and Language Models were quite popular, and I was very interested in understanding how these technologies function. However, these topics were rather advanced, so my professor advised me to proceed gradually. I began with a basic Q&A project, aiming to grasp the fundamentals of NLP. This initial step was meant to prepare me for deeper exploration into the world of LLMs.

Every part of this project is sample code which shows how to do the following:

* Create an open-domain Arabic and English question answering system using Python.
* Implement a Document Retriever using wikipedia api.
* Implement a Document Reader using both [distilbert-base-cased-distilled-squad](https://huggingface.co/distilbert-base-cased-distilled-squad) and [AraElectra-Arabic-SQuADv2-QA](https://huggingface.co/ZeyadAhmed/AraElectra-Arabic-SQuADv2-QA) models through api calls to HuggingFace server using inference api.
* Create a Messenger like web application using Flask, HTML, CSS and JavaScript.

  
## High-level functional explanation

### Q&A System Architecture Diagram
<img src="[https://your-image-url.type](https://github.com/Heyyassinesedjari/QuestionAnsweringWebApp/assets/94799575/ced251a7-9413-4dc0-8f0e-beac07ba3668)" width="100" height="100">
![image](https://github.com/Heyyassinesedjari/QuestionAnsweringWebApp/assets/94799575/ced251a7-9413-4dc0-8f0e-beac07ba3668)

### Document Retriever Architecture Diagram
![image](https://github.com/Heyyassinesedjari/QuestionAnsweringWebApp/assets/94799575/602dad7c-bbd6-42a4-837d-a90e797ab187)

### Document Reader Architecture Diagram
![image](https://github.com/Heyyassinesedjari/QuestionAnsweringWebApp/assets/94799575/0e57a945-5f8e-4088-b53a-f4bc8fa81202)

### Application Sequence Diagram
![image](https://github.com/Heyyassinesedjari/QuestionAnsweringWebApp/assets/94799575/83f19996-94c1-4be5-ba6f-ef1ff1329bbd)

###  Video Demo
https://github.com/Heyyassinesedjari/QuestionAnsweringWebApp/assets/94799575/5bd7fd0f-f1a5-409f-91ef-5dafd6d35a80

### Project Defense Presentation (Google Slides)
https://docs.google.com/presentation/d/1vQKFpJJx6TmtOgJ8upJHEEu_9QU-tWXH/edit?usp=sharing&ouid=100061785569173216725&rtpof=true&sd=true
