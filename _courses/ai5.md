---
title: "AI-5"
permalink: /courses/ai5/
cycle: c1
kind: course
excerpt: Productionizing AI (MLOps)
sequence: 8
header:
  overlay_image: /assets/images/header/HeaderDesign7.jpeg
  teaser: /assets/images/header/HeaderDesign7.jpeg
  actions:
    - label: "Register"
      url: "https://application.univ.ai/applications"
---
>Your journey in Deep Learning has lead you here. 
>You are now an expert at building everything from computer vision to language to generative to reinforcement models. 
>Those awesome models you trained now sit in notebook files right? 
>What if you want to give life 🌱 to these models? Maybe build an AI powered App 😁 
>
>This brings us to AI5!

Welcome to AI5. 

This course aims to review existing Deep Learning flow while applying it to a real-world problem. Then we will build and deploy an application that uses the deep learning model to understand how to productionize models.  This course follows the Univ.AI model of balancing between concept, theory, and implementation.

Split into three parts; the course starts with the review of Deep Learning concepts for data and modeling and how to apply them to different tasks, including vision and language tasks. The next part will be Development, where you use the models you trained in part 1 and incorporate them into real-world applications. Finally, you will Deploy the application in Google Cloud Platform (GCP). The three parts will cover in detail topics such as Transfer learning, Containerization using Docker, and Scaling deployments using Kubernetes.

At the end of this module, you will build efficient deep learning models and design, build and deploy applications that scale.

This page introduces you to the team, the basic instructions, the schedule, and various elements of our class.

## The Team

### Dr. Pavlos Protopapas

<img src="/assets/images/people/PavlosProtopapas.jpeg" style="width:300px;" />

- Scientific Director of the Institute for
  Applied Computational Science (IACS).
- Teaches Introduction to Data Science ([CS109a](https://harvard-iacs.github.io/2020-CS109A/)), Advanced Topics in Data Science ([CS109b](https://harvard-iacs.github.io/2021-CS109B/)) and Advanced Practical Data Science ([AC295](https://harvard-iacs.github.io/2020F-AC295/)).
- He is a leader in
  astrostatistics and he is excited about
  the new telescopes coming online in
  the next few years. 

You can <a href="https://www.univ.ai/team/pavlos-protopapas-2" target="_blank">read more about him here</a>.


### Shivas Jayaram

<img src="/assets/images/people/ShivasJayaram.jpg" style="width:300px;" />

* Researcher @Harvard IACS and Deep Learning Practitioner
* Masters in Data Science from Harvard University
* Previously, co founder and CTO of a Deep Learning startup 
* Prior to that helped build up a data science team at a manufacturing company
* Over 15 years of Solution Architecture and Development experience

You can <a href="https://www.linkedin.com/in/shivasj/" target="_blank">read more about him here</a>.


## The Coursework


We have very carefully designed the coursework to give you, the student, a wholesome learning experience.

Each week shall include:

-  2 Sessions
-  2 Labs
-  Office hours

### Session - What to expect

![](/assets/images/Session.png)

Before the session begins, students are expected to complete a pre-class reading assignment and and attempt a quiz based on the same.

A session will have the following pedagogy layout which will be repeated three times:

- Approx. 15 minutes of live online instruction followed by approx 15 minutes of Q/A + Quiz + Exercises. 
- Sessions will help students develop the intuition for the core concepts, 
  provide the necessary mathematical background, and provide guidance on technical details. 
- Sessions will be accompanied by relevant examples to clarify key concepts and techniques.

After the session, students are expected to complete a short post-class quiz based on the principal concepts covered in class.

### Lab - What to expect

![](/assets/images/Lab.png)

A lab is a one hour session that is divided into 3 major parts. 

- Each lab begins by revisiting the 
  Quizzes and Exercises done in the previous lecture session. 
- After discussing exercises,
  we will have a semi-formal Q/A session. All doubts pertaining, but not limited, to the previous session, 
  and homeworks are welcome.

- The last part of the labs deals predominantly with the upcoming homeworks. It is 
  directed towards giving a brief overview of the homework problem. We will discuss some code to help you get started.   


### Topics

<table style="width:800px;"><tr><th>Module</th><th></th><th>Concepts</th></tr><tr><td colspan=3><strong>Project Outline</strong></td></tr><tr><td></td><td>Introduction to Projects</td><td><ul><li>Problem Definition</li><li>Proposed Solutions</li><li>Project Scope</li></ul></td></tr><tr><td colspan=3><strong>Deep Learning</strong></td></tr><tr><td></td><td>Data</td><td><ul><li>Data Pipelines</li><li>Tensorflow Data</li><li>Tensorflow Records</li><li>Dask</li><li>Cloud Storage Buckets</li></ul></td></tr><tr><td></td><td>Models</td><td><ul><li>Computer Vision: Classification</li><li>Computer Vision: Segmentation</li><li>NLP & Language Models</li><li>Transfer Learning and SOTA Models</li><li>Distillation and Compression</li></ul></td></tr><tr><td colspan=3><strong>Development</strong></td></tr><tr><td></td><td>Design</td><td><ul><li>Virtual Environments, Virtual Boxes, and Containers</li><li>Containerization  & Docker</li><li>App Design</li></ul></td></tr><tr><td></td><td>Develop</td><td><ul><li>Setup and Code organization</li><li>APIs and Model serving</li><li>App frontend</li></ul></td></tr><tr><td colspan=3><strong>Operations</strong></td></tr><tr><td></td><td>Deployment, Scaling, & Automation</td><td><ul><li>Google Cloud Platform (GCP)</li><li>Kubernetes</li><li>Ansible</li></ul></td></tr></table>
<br><br>

### Projects

During the entire course you will work in teams and implement a project. The various topics in the class are designed to help you build milestones in an incremental fashion and build towards the end goal. The final outcome with your project will be  a fully working AI App.

* Project groups need to be formed by the first week of class
* Group size : 4
* Select a project from the list given or bring your own
* Criteria for projects are:
    * Deep learning task implemented should include both computer vision and language models
    * The end product should be a deployable app that uses the models in the backend in some form
* If you plan to bring your own project idea, the following additional criteria must be met:
    * Dataset size 5 Gigabytes or larger
    * Data should include images and text

<br>
Here are some of the projects:
<br>
<br>

<table style="width:600px;">
<tr>
    <th colspan="2">Mushroom Identification (In class demo)</th>
</tr>
<tr>
<td style="vertical-align: top; padding:20px; width:50%;">
<ul>
<li>Pavlos likes to go the forest for mushroom picking</li>
<li>Some mushrooms can be poisonous</li>
<li>Help build an app to identify mushroom type and if poisonous or not</li>
<ul>
</td>
<td>
<img src='/assets/ai5-c1.assets/mushroomapp.png' style="width:300px;">
</td>
</tr>
</table>

<br>
<br>

<table style="width:600px;">
<tr>
    <th colspan="2">Austin Pets Alive (APA)</th>
</tr>
<tr>
<td style="vertical-align: top; padding:20px; width:50%;">
<ul>
<li>APA is an association of pet owners</li>
<li>They would like to help future dog owners find a dog who is a perfect fit for them</li>
<li>Help build an app that can help owners find the right pet</li>
<ul>
</td>
<td>
<img src='/assets/ai5-c1.assets/petsapp.png' style="width:300px;">
</td>
</tr>
</table>
<br><br>

<table style="width:600px;">
<tr>
    <th colspan="2">Visual Question Answering</th>
</tr>
<tr>
<td style="vertical-align: top; padding:20px; width:50%;">
<ul>
<li>The VQA dataset contains open-ended questions about images</li>
<ul>
</td>
<td>
<img src='/assets/ai5-c1.assets/vqaapp.png' style="width:300px;">
</td>
</tr>
</table>
<br><br>
Please find a more detailed summary of all <a href="https://docs.google.com/document/d/1tC1k8XX1RjxxH7Ojay1lqSBTx-oYtMM67oOMyNsA4bU/edit?usp=sharing" target="_blank">projects here</a>.


## The Class

### Welcome Session - Preparing for this class 

There will be a **Welcome Session** scheduled on ```Monday, 9th August 2021``` at ``` 7:30 PM``` IST for all registered students. 
Please check your mail for more information.


### High level course schedule 

![](/assets/ai5-c1.assets/schedule.png)


*NOTE*: Below timings are in IST

**Lecture Sessions**: 

- Tuesday Series: ```7:30 PM - 9:00 PM IST [ 10:00 AM - 11:30 AM EST ]```  

- Saturday Series: ```8:00 PM - 9:30 PM IST [ 10:30 AM - 12:00 AM EST ]```

**Lab Sessions**: 

- Wednesday Series: ```7:30 PM - 9:00 PM IST [ 10:00 AM - 11:30 AM ] ``` 

- Sunday Series: ```8:00 PM - 9:30 PM IST [ 10:30 AM - 12:00 AM EST ]```

**Office hours**: 

- Mondays: ```7:30 PM - 8:30 PM [ 10:00 AM - 11:00 AM EST ]```

### Course Pre-Requisites 

Your are expected to know the following:  
* Good working knowledge of python  
* Good understanding on the `Tensorflow` Deep Learning framework  
* Basic shell commands  


#### Install Docker 
Install [`Docker Desktop`](https://www.docker.com/products/docker-desktop) for your operating system. 

#### Install VSCode  
Follow the [instructions](https://code.visualstudio.com/download) for your operating system.  
If you already have a preferred text editor, skip this step.  


## Diversity & Inclusion

We actively seek and welcome people of diverse identities, from across the spectrum of disciplines and methods since Artificial Intelligence (AI) increasingly mediates our social, cultural, economic, and political interactions [1]. 

We believe in creating and maintaining an inclusive learning environment where all members feel safe, respected, and capable of producing their best work. 

We commit to an experience for all participants that is free from -- Harassment, bullying, and discrimination which includes but is not limited to:

- Offensive comments related to age, race, religion, creed, color, gender (including transgender/gender identity/gender expression), sexual orientation, medical condition, physical or intellectual disability, pregnancy, or medical conditions, national origin or ancestry.
- Intimidation, personal attacks, harassment, unnecessary disruption of talks during any of the learning activities.

Reference: 

[1] K. Stathoulopoulos and J. C. Mateos-Garcia, “Gender Diversity in AI Research,” SSRN Electronic Journal, 2019 [Online]. Available: [http://dx.doi.org/10.2139/ssrn.3428240](https://dx.doi.org/10.2139/ssrn.3428240).

## Logistics - What you need to begin?

We assume you have a [Univ.AI](https://course.univ.ai) account, created when you signed up at [course.univ.ai](https://courses.univ.ai). 
If not, email [programs@univ.ai](mailto:programs@univ.ai).


### Education software we use

- Our lectures and labs are carried out via [Zoom](/support/zoom/) (install instructions).
- Quizzes & exercises will be conducted on the digital learning platform [Ed](/support/edstem/).
- All exercises and homeworks in this course will be done/submitted in Google Colab or GitHub code repos.

<style>
table {
  font-family: Arial, Helvetica, sans-serif;
  border-collapse: collapse;
  width: 100%;
  border-top: 0px solid black;
  border-bottom: 0px solid black;
}

td, th {
  border: 1px solid #ddd;
  padding: 8px;
}
tr:nth-child(even){background-color: #ffffff;}
tr:nth-child(odd){background-color: #ffffff;}
th {
  padding-top: 12px;
  padding-bottom: 12px;
  text-align: left;
  background-color: #848484;
  color: white;
}
ul {
  margin-top: 0;
  margin-bottom: 0;
}
</style>unicate your findings


## Links to previous cohorts 

- [Cohort 1](/catalog/cohort1/ai5/)