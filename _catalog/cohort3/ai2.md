---
title: "AI-2"
permalink: /catalog/cohort3/ai2/
cycle: c3
kind: course
excerpt: Convolutional Neural Networks and Autoencoders
sequence: 3
header:
  overlay_image: /assets/images/header/greyHeaderDesign2.jpeg
  teaser: /assets/images/header/greyHeaderDesign2.jpeg
  actions:
    - label: "Register"
      url: "https://application.univ.ai/applications"
---

<!-- Bootstrap CSS -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css" integrity="sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2" crossorigin="anonymous">
<!-- -->
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

<br>

### Teaching Assistants

*Click on avatars of the TAs to know more about them.*
<div style="display: grid; grid-template-columns: repeat(10, 1fr);">
  <div class="img-border" style="grid-column: 1/2">
    <div class="circular--portrait">
      <img src="/assets/images/people/AnshikaGupta.png" class="circular--portrait-img" align="left" data-toggle="modal" data-target="#AnshikaModal"/>
    </div>
  </div>


  <div class="img-border" style="grid-column: 3/4">
    <div class="circular--portrait">
      <img src="/assets/images/people/VishalBalaji.jpeg" class="circular--portrait-img" align="left" data-toggle="modal" data-target="#VishalModal"/>
    </div>
  </div>

  <div class="img-border" style="grid-column: 5/6">
    <div class="circular--portrait">
      <img src="/assets/images/people/ShibaniBudhraja.png" class="circular--portrait-img" align="left" data-toggle="modal" data-target="#ShibaniModal"/>
    </div>
  </div>

  <div class="img-border" style="grid-column: 7/8">
    <div class="circular--portrait">
      <img src="/assets/images/people/KuldeepPrasad.jpeg" class="circular--portrait-img" align="left" style="margin-top:-12px;" data-toggle="modal" data-target="#KuldeepModal"/>
    </div>
  </div>

  <div class="img-border" style="grid-column: 9/10">
    <div class="circular--portrait">
      <img src="/assets/images/people/VishnuM.png" class="circular--portrait-img" align="left" style="margin-top:-15px;" data-toggle="modal" data-target="#VishnuModal"/>
    </div>
  </div>

</div>
<br>

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

![](/assets/ai2-c3.assets/Content.jpg)

## The Class

### Welcome Session - Preparing for this class 

There will be a **Welcome Session** scheduled on ```6 March 2022``` at ``` 6:30 PM``` IST for all registered students. 

Please check your mail for more information.


### High level course schedule 

![](/assets/ai2-c3.assets/Schedule.jpg)

**Lecture Sessions**: 
- Wednesday Series: ```7:30 PM - 9:00 PM IST```  ```[ 09:00 AM - 10:30 AM EST]```
- Saturday Series: ```5:30 PM - 7:00 PM IST```  ```[ 07:00 AM - 08:30 AM EST]```

**Lab Sessions**: 

- Thursday Series: ```7:30 PM - 9:00 PM IST```  ```[ 09:00 AM - 10:30 AM EST]``` 
- Sunday Series: ```5:30 PM - 7:00 PM IST```  ```[ 07:00 AM - 08:30 AM EST]```

**Office hours**: 

- Mondays: ```7:30 PM - 9:00 PM```

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


<!-- Modal Section -->

<style>
  .modal-margin {
    margin: 0 auto;
  }

  .modal {
    background: transparent;
  }

</style>

<!-- Modal --> 
<div class="container">
<div class="modal fade modal-margin" id="VishnuModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Vishnu M</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <center><img src="/assets/images/people/VishnuM.png" alt="Vishnu" style="height:200px;margin-right:15px;"></center>
        <ul style="list-style:circle; padding-left: 2em;">
          <li>Vishnu is the Program Coordinator for academic operations at Univ.AI.</li>
          <li>He is a Computer Vision enthusiast and a final year CSE undergrad at JECRC University, Jaipur.</li>
          <li>Currently, he is also working as a research assistant in StellarDNN lab at Harvard, where he is working on the intersection of Deep Learning and Astronomy.</li>
        </ul>
      </div>
    </div>
  </div>
</div>
</div>

<script>
     $('#VishnuModal').appendTo('body');
</script>



<!-- Modal -->
<div class="container">
<div class="modal fade modal-margin" id="AnshikaModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
<div class="modal-dialog" role="document">
<div class="modal-content">
<div class="modal-header">
<h5 class="modal-title" id="exampleModalLabel">Anshika Gupta</h5>
<button type="button" class="close" data-dismiss="modal" aria-label="Close">
<span aria-hidden="true">X</span>
</button>
</div>
<div class="modal-body">
<center><img src="/assets/images/people/AnshikaGupta.png" alt="Anshika" style="height:200px;margin-right:15px;"></center>
<ul style="list-style:circle; padding-left: 2em;">
<li>Anshika is a deep learning enthusiast currently a final year undergrad at JECRC University, Jaipur.</li>
<li>Previously, she was a Research Intern at a healthcare startup where she worked on developing algorithms for medical image analysis and segmentation.</li>
<li>When not studying, she can be found writing prose and poetry while sipping a cup of coffee.</li>
</ul>
</div>

</div>
</div>
</div>
</div>

<script>
     $('#AnshikaModal').appendTo('body');
</script>

<!-- 3 -->
<!-- Modal -->
<div class="container">
<div class="modal fade modal-margin" id="VishalModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
<div class="modal-dialog" role="document">
<div class="modal-content">
<div class="modal-header">
<h5 class="modal-title" id="exampleModalLabel">Vishal Balaji</h5>
<button type="button" class="close" data-dismiss="modal" aria-label="Close">
<span aria-hidden="true">X</span>
</button>
</div>
<div class="modal-body">
<center><img src="/assets/images/people/VishalBalaji.jpeg" alt="Vishal" style="height:200px;margin-right:15px;"></center>
<ul style="list-style:circle; padding-left: 2em;">
<li>Currently working as a Machine Learning Engineer at a voice AI startup</li>
<li>In my free time, I like to trek, read sci-fi and history books</li>
</ul>
</div>

</div>
</div>
</div>
</div>

<script>
     $('#VishalModal').appendTo('body');
</script>


<!-- 4 -->

<!-- Modal -->
<div class="container">
<div class="modal fade modal-margin" id="ShibaniModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
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
     $('#ShibaniModal').appendTo('body');
</script>

<!-- 6 -->

<!-- Modal -->
<div class="container">
<div class="modal fade modal-margin" id="KuldeepModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
<div class="modal-dialog" role="document">
<div class="modal-content">
<div class="modal-header">
<h5 class="modal-title" id="exampleModalLabel">Kuldeep Prasad</h5>
<button type="button" class="close" data-dismiss="modal" aria-label="Close">
<span aria-hidden="true">X</span>
</button>
</div>
<div class="modal-body">
<center><img src="/assets/images/people/KuldeepPrasad.jpeg" alt="Kuldeep" style="height:200px;margin-right:15px;"></center>
<ul style="list-style:circle; padding-left: 2em;">
<li>Dr. Kuldeep Prasad works as a Research Scientist at the National Institute of Standards and Technology.</li>
<li>His research interests include application of Machine Learning for modeling the spread of forest fires as well as understanding the effects of climate change.</li>
<li>Dr. Prasad wants to accelerate the application  of Artificial Intelligence  to solve some of the world’s biggest challenges as well as using AI for social good.</li>
<li>Read more about him <a href="https://www.nist.gov/people/kuldeep-prasad">here</a>.</li>
</ul>
</div>

</div>
</div>
</div>
</div>

<script>
     $('#KuldeepModal').appendTo('body');
</script>
<!-- 7 -->

<!-- Modal -->
<div class="container">
<div class="modal fade modal-margin" id="MeghanaModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
<div class="modal-dialog" role="document">
<div class="modal-content">
<div class="modal-header">
<h5 class="modal-title" id="exampleModalLabel">Meghana Sarikonda</h5>
<button type="button" class="close" data-dismiss="modal" aria-label="Close">
<span aria-hidden="true">X</span>
</button>
</div>
<div class="modal-body">
<center><img src="/assets/images/people/MeghanaSarikonda.png" alt="Meghana" style="height:200px;margin-right:15px;"></center>
<ul style="list-style:circle; padding-left: 2em;">
<li>Previously worked as a freelance full stack developer</li>
<li>Fascinated about AI and it’s ability to solve complex problems</li>
</ul>
</div>

</div>
</div>
</div>
</div>

<script>
     $('#MeghanaModal').appendTo('body');
</script>
<!-- 8 -->

<!-- Modal -->
<div class="container">
<div class="modal fade modal-margin" id="HaydenModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
<div class="modal-dialog" role="document">
<div class="modal-content">
<div class="modal-header">
<h5 class="modal-title" id="exampleModalLabel">Shibani Budhraja</h5>
<button type="button" class="close" data-dismiss="modal" aria-label="Close">
<span aria-hidden="true">X</span>
</button>
</div>
<div class="modal-body">
<p><img src="/assets/images/people/ShibaniBudhraja.png" alt="Pavlos" style="height:350px;margin-right:15px;" align="left">
- A Psychologist and amateur  musician exploring the world of Data Science. 
<br>
-Her current and future goals include working towards mastering Reinforcement Learning along with exploring ethics and biases in AI.
<br>
- Her previous occupations have included a few hospital internships under neuropsychologists and psychiatrists , teaching at a  NGO for young girls and thereafter teaching kids with special needs.
</p>
</div>

</div>
</div>
</div>
</div>

<script>
     $('#HaydenModal').appendTo('body');
</script>
<!-- 9 -->

<!-- Modal -->
<div class="container">
<div class="modal fade modal-margin" id="JoyModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
<div class="modal-dialog" role="document">
<div class="modal-content">
<div class="modal-header">
<h5 class="modal-title" id="exampleModalLabel">Joy Parekh</h5>
<button type="button" class="close" data-dismiss="modal" aria-label="Close">
<span aria-hidden="true">X</span>
</button>
</div>
<div class="modal-body">
<p><img src="/assets/images/people/JoyParekh.jpeg" alt="Pavlos" style=height:200px;margin-right:15px; align="left">
- AI researcher who has collaborated with teams from Mass Gen, MIT, Harvard and NTU Singapore.
- Incoming masters student at Columbia University's Computer Science program.
<br>
-Likes to explore variety of applications of AI models, with social impact, while simultaneously developing the models as well.
</p>
</div>

</div>
</div>
</div>
</div>

<script>
     $('#JoyModal').appendTo('body');
</script>
