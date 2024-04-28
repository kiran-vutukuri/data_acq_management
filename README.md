
Enhancing communication within university communities is imperative to meet the diverse needs of stakeholders, including prospective and current students, alumni, and other information seekers. Current academic chatbot systems often exhibit imprecise communication, necessitating tailored solutions. To address this, we propose KatzBot, leveraging Katz generative pre-trained transformer (KatzGPT), a sophisticated custom large language model (LLM), to effectively bridge precision gaps in existing chatbot systems and academic universities. Moreover, we have curated two datasets: 6,280 sentence-completion pairs and 7,330 question-answer pairs. We train KatzGPT on the sentence-completion pairs to expand its knowledge base, followed by training on the question-answer pairs to enhance its accuracy. Through extensive experimentation, KatzGPT demonstrates superior performance compared to state-of-the-art methods on our dataset. In addition, our KatzBot system enables a concise and effective interface to enhance the communication between users and the KatzGPT model. The source code can be found in github.


# KatzBot - Enhancing University Community Communication

Welcome to the GitHub repository for KatzBot, an innovative chatbot designed to enhance communication within university communities. KatzBot is powered by KatzGPT, a custom-trained large language model that bridges the precision gaps in existing academic chatbot systems.

## Features
- **Dual Training Datasets**: Utilizes 6,280 sentence-completion pairs and 7,330 question-answer pairs to improve knowledge base and accuracy.
- **Existing LLM Training**: Leveraging existing LLMs(GPT2, Llama2, Mistral), using our created datasets to create a chatbot.
- **Custom Language Model**: Leveraging KatzGPT, a pre-trained transformer model tailored for academic environments.


## Repository Contents

- `/html`: HTML interface for interacting with KatzBot.
- `/code`: Includes all necessary code for training and deploying KatzGPT and KatzBot systems.

## Getting Started

### Prerequisites

Ensure you have Python 3.x installed on your machine. You can install Python by downloading it from [python.org](https://www.python.org/downloads/). The code can also be run on Google collab. In cases on some LLMs , extra GPU might be required.


<div align="center">
    <a><img width="720" src="images/face-recognition-attendance-system.jpg" alt="soft"></a>
</div>

# KatzBot - Enhancing University Community Communication

## Table of Contents

- [Course Attendance System with Facial Recognition](#course-attendance-system-with-facial-recognition)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
      - [Project Description](#project-description)
      - [Website](#website-screenshots)
  - [Datasets](#datasets)
      - [Raw Images](#raw-images-data-collection)
      - [Processed Images ](#processed-images)
  - [Method](#method)
      - [RetinaFace](#retinaface)
      - [Face Recognition](#face-recognition)
  - [Results](#results)
  - [Technical Information](#technical-information)
  - [Benefits](#benefits)
  - [Applications](#applications)
  - [Citations](#citations)
