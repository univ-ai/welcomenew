---
title: "AI-2"
permalink: /courses/ai2/
cycle: c4
kind: course
excerpt: Convolutional Neural Networks and Autoencoders
sequence: 3
header:
  overlay_image: /assets/images/header/HeaderDesign2.jpeg
  teaser: /assets/images/header/HeaderDesign2.jpeg
  actions:
    - label: "Register"
      url: "https://application.univ.ai/applications"
---

<!-- Bootstrap CSS -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css" integrity="sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2" crossorigin="anonymous">
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.min.js" integrity="sha384-w1Q4orYjBQndcko6MimVbzY0tgp4pWB4lZ7lr30WKz0vr/aWKhXdBNmNb5D92v7s" crossorigin="anonymous"></script>
<style>
  .modal-margin {
    margin: 0 auto;
  }
  .modal {
    background: transparent;
  }
  .ta-img {
    zoom:55%; 
    border: 1px solid black; 
    border-radius: 2em; 
    margin-right: 1em; 
    height:225px;
  }
  .circular--portrait { 
    width: 5.7rem; 
    height: 5.7rem; 
    overflow: hidden; 
    border-radius: 50%; 
    } 
  .circular--portrait-img { 
    width: 100%; 
    height: auto; 
    }
  .img-border {
    border-left: 1px solid #787D80;
    border-top: 1px solid #787D80;
    border-radius: 50%;
    padding: 0.5rem;
  }
  .img-border:hover {
    box-shadow: -3px 3px #787D80, -2px 2px #787D80, -1px 1px #787D80;
  }
  @media (max-width: 630px) {
    .circular--portrait { 
    width: 2.5rem; 
    height: 2.5rem; 
    overflow: hidden; 
    border-radius: 50%; 
    } 
  }
  }
</style>

<!-- TA Modal Section -->
<style>
  
  .modal-margin {
    margin: 0 auto;
  }

  .modal {
    background: transparent;
  }

</style>

<!-- TA Modal 1--> 
<div class="container">
<div class="modal fade modal-margin" id="Arya" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Arya Mohan</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <center><img src="/assets/images/people/AryaMohan.jpeg" alt="Arya" style="height:200px;margin-right:15px;"></center>
        <ul style="list-style:circle; padding-left: 2em;">
          <li>Arya is working as a research and teaching fellow with Univ.AI.</li>
          <li>Previously, she was a data analyst at Schneider Electric.</li>
          <li>She is currently working as a research fellow at the StellarDNN lab.</li>
        </ul>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#Arya').appendTo('body');
</script>

<!-- TA Modal 2-->
<div class="container">
<div class="modal fade modal-margin" id="Shibani" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
<div class="modal-dialog" role="document">
<div class="modal-content">
<div class="modal-header">
<h5 class="modal-title" id="exampleModalLabel">Shibani Budhraja</h5>
<button type="button" class="close" data-dismiss="modal" aria-label="Close">
<span aria-hidden="true">X</span>
</button>
</div>
<div class="modal-body">
<center><img src="/assets/images/people/ShibaniBudhraja.png" alt="Shibani" style="height:200px;margin-right:15px;"></center>
<ul style="list-style:circle; padding-left: 2em;">
<li>A Psychologist and amateur  musician exploring the world of Data Science.</li>
<li>Her current and future goals include working towards mastering Reinforcement Learning along with exploring ethics and biases in AI.</li>
<li>Her previous occupations have included a few hospital internships under neuropsychologists and psychiatrists , teaching at a  NGO for young girls and thereafter teaching kids with special needs.</li>
</ul>
</div>
</div>
</div>
</div>
</div>
<script>
     $('#Shibani').appendTo('body');
</script>

<!-- TA Modal 3-->
<div class="container">
<div class="modal fade modal-margin" id="Kuldeep" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
<div class="modal-dialog" role="document">
<div class="modal-content">
<div class="modal-header">
<h5 class="modal-title" id="exampleModalLabel">Kuldeep Prasad</h5>
<button type="button" class="close" data-dismiss="modal" aria-label="Close">
<span aria-hidden="true">X</span>
</button>
</div>
<div class="modal-body">
<center><img src="/assets/images/people/KuldeepPrasad.png" alt="Kuldeep" style="height:200px;margin-right:15px;"></center>
<ul style="list-style:circle; padding-left: 2em;">
<li>Dr. Kuldeep Prasad works as a Research Scientist at the National Institute of Standards and Technology.</li>
<li>His research interests include application of Machine Learning for modeling the spread of forest fires as well as understanding the effects of climate change.</li>
<li>Dr. Prasad wants to accelerate the application of Artificial Intelligence to solve some of the world’s biggest challenges as well as using AI for social good.</li>
<li>Read more about him <a href="https://www.nist.gov/people/kuldeep-prasad">here</a>.</li>
</ul>
</div>
</div>
</div>
</div>
</div>
<script>
     $('#Kuldeep').appendTo('body');
</script>

<!-- TA Modal 4-->
<div class="container">
<div class="modal fade modal-margin" id="Lakshay" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
<div class="modal-dialog" role="document">
<div class="modal-content">
<div class="modal-header">
<h5 class="modal-title" id="exampleModalLabel">Lakshay Chawla</h5>
<button type="button" class="close" data-dismiss="modal" aria-label="Close">
<span aria-hidden="true">X</span>
</button>
</div>
<div class="modal-body">
<center><img src="/assets/images/people/LakshayChawla.jpg" alt="Lakshay" style="height:200px;margin-right:15px;"></center>
<ul style="list-style:circle; padding-left: 2em;">
<li>Lakshay is a final year CSE undergrad at MAIT, Delhi.</li>
<li>Eventual goals include unravelling the mysteries of deep space with the help of ever-evolving AI.</li>
<li>You might find him engrossed in music and never-ending thoughts if not working for the future.</li>
</ul>
</div>
</div>
</div>
</div>
</div>
<script>
     $('#Lakshay').appendTo('body');
</script>

<!-- TA Modal 5-->
<div class="container">
<div class="modal fade modal-margin" id="Yash" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
<div class="modal-dialog" role="document">
<div class="modal-content">
<div class="modal-header">
<h5 class="modal-title" id="exampleModalLabel">Yash Surange</h5>
<button type="button" class="close" data-dismiss="modal" aria-label="Close">
<span aria-hidden="true">X</span>
</button>
</div>
<div class="modal-body">
<center><img src="/assets/images/people/YashSurange.jpg" alt="Yash" style="height:200px;margin-right:15px;"></center>
<ul style="list-style:circle; padding-left: 2em;">
<li>Yash is interested in the applications of AI in decoding the human brain.</li>
<li>He hopes to be a part of this effort in the future which could impact millions of lives and help us understand the brain.</li>
<li>In his free time, he likes listening to music and playing football.</li>
</ul>
</div>
</div>
</div>
</div>
</div>
<script>
     $('#Yash').appendTo('body');
</script>

<!-- TA Modal 6-->
<div class="container">
<div class="modal fade modal-margin" id="Mahima" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
<div class="modal-dialog" role="document">
<div class="modal-content">
<div class="modal-header">
<h5 class="modal-title" id="exampleModalLabel">Mahima Rao</h5>
<button type="button" class="close" data-dismiss="modal" aria-label="Close">
<span aria-hidden="true">X</span>
</button>
</div>
<div class="modal-body">
<center><img src="/assets/images/people/MahimaRao.png" alt="Mahima" style="height:200px;margin-right:15px;"></center>
<ul style="list-style:circle; padding-left: 2em;">
<li>Mahima is currently intern at Globalfoundries.</li>
<li>She is working on unsupervised classification of mask generated in foundries. </li>
<li>Her vision to introduce AI in centralized form in agriculture.</li>
</ul>
</div>
</div>
</div>
</div>
</div>
<script>
     $('#Mahima').appendTo('body');
</script>

<!-------------------------------------------------------------------------------------------------------------------------->

> *Long ago in a distant land, I, Multi-Layer Perceptron, the shapeshifting master of darkness, unleashed an unspeakable evil. But, a foolish samurai warrior wielding a convolutional sword stepped forth to oppose me. Before the final blow was struck, I tore open a portal in time and flung him into the future where my evil is law. Now, the fool seeks to return to the past and undo the future that is MLP.*


Welcome to the AI-2, a follow-up to our introductory course AI-1.

In this course, you will continue your data science journey to learn more about convolutional neural networks and how they're being used for machine learning. We'll emphasize both the basic algorithms and the practical tricks needed to get them to work well. 

The objective of this module is to provide you, the student, with a deeper intuition and understanding of neural networks including network architecture choices, activation functions, feed-forward, convolutional neural networks and auto-encoders. 

At the end of this course, you will be able to run a variety of advanced machine learning models, and learn to apply them to practical image recognition problems. This page introduces you to the team, the basic instructions, the schedule and various elements of our class.

## The Team

### Dr. Ignacio Becker

![](/assets/images/people/IgnacioBecker.jpeg)

- Astronomer currently pursuing a Ph.D. in Computer Science at Pontificia Universidad Católica in Chile. 
- His main area of research is applied AI to astrophysical problems. 
- Nowadays, he focuses on developing models to process the real-time data of the next generation of telescopes.

### Dr. Raghu Meka

![](/assets/images/people/RaghuMeka.png)

- Associate Professor of Computer Science at UCLA with a PhD from UT Austin.
- He was a postdoctoral fellow at the Institute for Advanced Study, (at Princeton University). 
- Before joining UCLA Raghu was a researcher at the Microsoft Research.

You can [read more about him here](https://samueli.ucla.edu/people/raghu-meka/).


## The Coursework

We have very carefully designed the coursework to give you, the student, a wholesome learning experience.

Each week shall include:

- 2 Sessions
- 2 Labs
- Office hours

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

<img src="/assets/images/Lab.png" alt="Lab" class="center">


A lab is a TA driven one hour session that is divided into 3 major parts. 
- Each lab begins by revisiting the Quizzes and Exercises done in the previous lecture session. 
- After discussing exercises, we will have a semi-formal Q/A session. All doubts pertaining, but not limited, to the previous session, 
and homeworks are welcome.
- The last part of the labs deals predominantly with the upcoming homeworks. It is 
directed towards giving a brief overview of the homework problem. We will discuss some code to help you get started.   

![](/assets/ai2-c4.assets/Content.png)

## The Class


### Welcome Session - Preparing for this class 

There will be a **Welcome Session** scheduled. Timings will be updated. 


### High level course schedule 

![](/assets/ai2-c4.assets/Schedule.png)


**Lecture Sessions**: 

- Tuesday Series: ```8:30 PM - 10:00 PM IST [ 11:00 AM - 12:30 AM EST ]```  

- Saturday Series: ```8:00 PM - 9:30 PM IST [ 10:30 AM - 12:00 PM EST ]```

**Lab Sessions**: 

- Wednesday Series: ```8:00 PM - 9:30 PM IST [ 10:30 AM - 12:00 PM EST ] ``` 

- Sunday Series: ```8:00 PM - 9:30 PM IST [ 10:30 AM - 12:00 PM EST ]```

**Office hours**: 

- Mondays: ```8:00 PM - 9:00 PM [ 10:30 AM - 11:30 AM EST ]```


### Course Pre-Requisites 

You are expected to have programming experience at the level of Harvard’s [CS50](https://www.edx.org/course/cs50s-introduction-to-computer-science?source=aw&awc=6798_1597231309_7e3ec7ec847f629b7c399ad1816e752d&utm_source=aw&utm_medium=affiliate_partner&utm_content=text-link&utm_term=101248_adgoal+GmbH+-+Content), statistics knowledge at the level of Harvard’s [Stat 110](https://projects.iq.harvard.edu/stat110/home) or above and basic machine learning concepts such as model fitting, test-validation, regularization, etc. 

- Programming Experience:

    - Experience with Python: functions, variable scope, classes, modules, NumPy, SciPy, Matplotlib

    - Basic data structures

    - File I/O

- Statistics Experience:

    - Basics of probability, conditional probability, Bayes’ theorem

    - Univariate distributions, normal, binomial, Poisson distributions

    - Multivariate normal distribution

    - Central Limit Theorem

- Machine Learning Experience:

    - Basic understanding of supervised and unsupervised learning

    - Regression and Classification 

    - Loss functions 

    - Overfitting and Regularization 

    - Model Selection

Please find a more detailed summary of the pre-requisites for this program [here](/assets/ai2-c3.assets/courseprep/).

## Diversity & Inclusion

We actively seek and welcome people of diverse identities, from across the spectrum of disciplines and methods since Artificial Intelligence (AI) increasingly mediates our social, cultural, economic, and political interactions [1]. 

We believe in creating and maintaining an inclusive learning environment where all members feel safe, respected, and capable of producing their best work. 

We commit to an experience for all participants that is free from -- Harassment, bullying, and discrimination which includes but is not limited to:

- Offensive comments related to age, race, religion, creed, color, gender (including transgender/gender identity/gender expression), sexual orientation, medical condition, physical or intellectual disability, pregnancy, or medical conditions, national origin or ancestry.
- Intimidation, personal attacks, harassment, unnecessary disruption of talks during any of the learning activities.

Reference: 

[1] K. Stathoulopoulos and J. C. Mateos-Garcia, “Gender Diversity in AI Research,” SSRN Electronic Journal, 2019 [Online]. Available: [http://dx.doi.org/10.2139/ssrn.3428240](https://dx.doi.org/10.2139/ssrn.3428240).

## Logistics - What you need to begin?

We assume you have a [Univ.AI](https://course.univ.ai) account, created when you signed up at [course.univ.ai](https://course.univ.ai). 
If not, email [programs@univ.ai](mailto:programs@univ.ai).


### Education software we use

- Our lectures and labs are carried out via [Zoom](/support/zoom/) (install instructions).
- Quizzes & exercises will be conducted on the digital learning platform [Ed](/support/edstem/).
- Ocassionally, we may conduct in-class contests on [kaggle](https://www.kaggle.com/). Please register on kaggle and familarize yourself with it, if you haven't already done so. This is a short video that will help you learn how to use [kaggle](https://www.youtube.com/watch?v=Gp_qv317Gew).

All exercises and homeworks in this course will be done in jupyter notebooks. This [link](https://www.dataquest.io/blog/jupyter-notebook-tutorial/) will help you setup jupyter lab and get you acquianted with jupyter notebooks.

Our module policies around collaboration and grading are listed [here](/assets/policy/). Our expectations of you are also laid out in that document.

## Parting note

As you will learn in this course, data science is not just about writing efficient algorithms.

It requires proficiency in critical thinking, ideation & presentation, along with strong foundations in statistics, computer science & mathematics.

Keeping that in mind, you are adviced to give your full active attention to every session, homework & exercise.

We wish you best of luck for your data science journey.

![](/assets/images/end.jpeg)

## Links to previous cohorts

- [Cohort 1](/catalog/cohort1/ai2/)
- [Cohort 2](/catalog/cohort2/ai2/)
- [Cohort 3](/catalog/cohort3/ai2/)

