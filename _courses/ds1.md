---
title: "DS-1"
permalink: /courses/ds1/
cycle: c3
kind: workshop
excerpt: Introduction to Data Science
sequence: 4
header:
  overlay_image: /assets/images/header/HeaderDesign3.jpeg
  teaser: /assets/images/header/HeaderDesign3.jpeg
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
<div class="modal fade modal-margin" id="Kuldeep" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
<div class="modal-dialog" role="document">
<div class="modal-content">
<div class="modal-header">
<h5 class="modal-title" id="exampleModalLabel">Dr. Kuldeep Prasad</h5>
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

<!-- TA Modal 3-->
<div class="container">
<div class="modal fade modal-margin" id="Sakthisree" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
<div class="modal-dialog" role="document">
<div class="modal-content">
<div class="modal-header">
<h5 class="modal-title" id="exampleModalLabel">Sakthisree Venkatesan</h5>
<button type="button" class="close" data-dismiss="modal" aria-label="Close">
<span aria-hidden="true">X</span>
</button>
</div>
<div class="modal-body">
<center><img src="/assets/images/people/Sakthisree.jpeg" alt="Sakthisree" style="height:200px;margin-right:15px;"></center>
<ul style="list-style:circle; padding-left: 2em;">
<li>Sakthisree is a Machine Learning Lead in a leading German-based wholesale company.</li>
<li>Her current goal is to establish autonomous systems that are able to comprehend the world for its multi-modal richness and dimensionality through casual inference, which she is pursuing through independent research.</li>
<li>She is also very active in the non-profit space where she leads courses, workshops and panels in the area of Tech Equity + Society, specifically catering to principles of Intersectionality and Social Justice in the Global South.</li>
</ul>
</div>
</div>
</div>
</div>
</div>
<script>
     $('#Sakthisree').appendTo('body');
</script>

<!-- TA Modal 4-->
<div class="container">
<div class="modal fade modal-margin" id="Chaitanya" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
<div class="modal-dialog" role="document">
<div class="modal-content">
<div class="modal-header">
<h5 class="modal-title" id="exampleModalLabel">Sai Chaitanya</h5>
<button type="button" class="close" data-dismiss="modal" aria-label="Close">
<span aria-hidden="true">X</span>
</button>
</div>
<div class="modal-body">
<center><img src="/assets/images/people/SaiChaitanya.png" alt="Chaitanya" style="height:200px;margin-right:15px;"></center>
<ul style="list-style:circle; padding-left: 2em;">
<li>Chaitanya is currently a final year Ocean Engineering and Naval Architecture student at IIT Madras.</li>
<li>He is excited about AI and it's applications in Agriculture and Healthcare.</li>
<li>In his free time, he can be found gardening or star-gazing.</li>
</ul>
</div>
</div>
</div>
</div>
</div>
<script>
     $('#Chaitanya').appendTo('body');
</script>

<!-------------------------------------------------------------------------------------------------------------------------->

Welcome to DS-1.
The objective of this module is to provide a fundamental understanding of data analysis.  The course proceeds in 3 parts, following the Data Science Process:

**Obtain and clean the data**: we will teach you how to obtain, clean, and process data from different sources such as scraped web pages, spreadsheets, APIs, and documents. 

**Exploratory Data Analysis**: we develop your skills in pre-modeling and post-modeling exploratory data analysis and visualization. This part is all about understanding your data.

**Modeling**: We choose some very specific models to cover, from the perspective of teaching techniques which are generalizable to any models. Thus we will cover classification and recommendation engines. We'll also cover similarity and PCA, as a way of understanding structure in your data and the models you ran on them.

At the end of this module, you will be ready to run the entire data science process, all on your own, from fetching (from the internet or databases) and cleaning the data, setting up pipelines, to exploratory data analysis, visualization, and modeling.

This page introduces you to the team, the basic instructions, the schedule, and various elements of our class.

## The Team

### (Dr.) Ignacio Becker

![](/assets/images/people/IgnacioBecker.jpeg)

- Astronomer currently pursuing a Ph.D. in Computer Science at Pontificia Universidad Católica in Chile. 
- His main area of research is applied AI to astrophysical problems. 
- Nowadays, he focuses on developing models to process the real-time data of the next generation of telescopes. 

### Teaching Assistants

*Click on avatars of the TAs to know more about them.*
<div style="display: grid; grid-template-columns: repeat(8, 1fr);">
  <div class="img-border" style="grid-column: 1/2">
    <div class="circular--portrait">
      <img src="/assets/images/people/AryaMohan.jpeg" class="circular--portrait-img" align="left" style="margin-top:-15px;" data-toggle="modal" data-target="#Arya"/>
    </div>
  </div>

  <div class="img-border" style="grid-column: 3/4">
    <div class="circular--portrait">
      <img src="/assets/images/people/Sakthisree.jpeg" class="circular--portrait-img" align="left" data-toggle="modal" data-target="#Sakthisree"/>
    </div>
  </div>

  <div class="img-border" style="grid-column: 5/6">
    <div class="circular--portrait">
      <img src="/assets/images/people/SaiChaitanya.png" class="circular--portrait-img" align="left" data-toggle="modal" data-target="#Chaitanya"/>
    </div>
  </div>

  <div class="img-border" style="grid-column: 7/8">
    <div class="circular--portrait">
      <img src="/assets/images/people/KuldeepPrasad.png" class="circular--portrait-img" align="left" data-toggle="modal" data-target="#Kuldeep"/>
    </div>
  </div>

</div>
<br>



## The Coursework

We have very carefully designed the coursework to give you, the student, a wholesome learning experience.
Each week shall include:

- 2 Sessions
- 1 Lab
- Office hours

### Session - What to expect

![](/assets/images/Session.png)

Before the session begins, students are expected to complete a pre-class reading assignment and attempt a quiz based on the same.

A session will have the following pedagogy layout which will be repeated a few times:

- Approx. 10-15 minutes of live online instruction followed by a quiz
- Some sessions will have hands-on coding exercises or group activities
- Sessions will help students develop the intuition for the core concepts, provide the necessary mathematical background, and provide guidance on technical details.
- Sessions will be accompanied by relevant examples to clarify key concepts and techniques.

After the session, students are expected to complete a short post-class quiz based on the principal concepts covered in class and optional post-class reading will be provided.

### Lab - What to expect

![](/assets/images/Lab.png)

A lab is a TA driven 1.5 hour session that is divided into 3 major parts. 

- Each lab begins by solving parts of a complete problem. This problem is designed to help you with your homework and further elucidate concepts you learned in lecture.
- After discussing exercises, we will have a semi-formal Q/A session. The first part of this session is limited to homework questions, but the second part is more free-for-all, where you can ask any doubts that lingered over from lecture.

![](/assets/ds1-c2.assets/Content.png)

## The Class

Coming Soon!

<!--
#### Welcome Session - Preparing for this class

There will be a Welcome Session scheduled on **09 January 2022** at **9:00 PM IST** for all registered students.

Please check your mail for more information.
-->

![](/assets/ds1-c3.assets/Schedule.png)


**Lecture Sessions:**

- Wednesday Series: ```8:30 PM - 10:00 PM IST [11:00 AM - 12:30 PM EST]```
- Saturday Series: ```8:30 PM - 10:00 PM IST [11:00 AM - 12:30 PM EST]```

**Lab Sessions:**

- Thursday Series: ```9:00 PM - 11:00 PM IST [12:00 Noon - 1:30 PM EST]```
- Sunday Series: ```9:00 PM - 11:00 PM IST [12:00 Noon - 1:30 PM EST]```

**Office hours:**

- Tuesdays: ```9:00 PM - 10:00 PM IST [11:30 AM - 12:30 PM EST]```


## Course Pre-Requisites

You are expected to have programming experience and basic machine learning concepts such as model fitting, test-validation, regularization, etc.

- Programming Experience:
  - [Pandas](https://jakevdp.github.io/PythonDataScienceHandbook/03.00-introduction-to-pandas.html) - Specific topics: [Introducing Pandas Objects Data](https://jakevdp.github.io/PythonDataScienceHandbook/03.01-introducing-pandas-objects.html), [Indexing and Selection](https://jakevdp.github.io/PythonDataScienceHandbook/03.02-data-indexing-and-selection.html)
  - [NumPy](https://jakevdp.github.io/PythonDataScienceHandbook/02.00-introduction-to-numpy.html) - Specific topics: [Understanding Data Types in Python](https://jakevdp.github.io/PythonDataScienceHandbook/02.01-understanding-data-types.html), [The Basics of NumPy Arrays](https://jakevdp.github.io/PythonDataScienceHandbook/02.02-the-basics-of-numpy-arrays.html), [Computation on Arrays: Broadcasting](https://jakevdp.github.io/PythonDataScienceHandbook/02.05-computation-on-arrays-broadcasting.html), [Comparisons, Masks, and Boolean Logic](https://jakevdp.github.io/PythonDataScienceHandbook/02.06-boolean-arrays-and-masks.html)
  - [Matplotlib](https://jakevdp.github.io/PythonDataScienceHandbook/04.00-introduction-to-matplotlib.html) - Specific topics: [Simple Line Plots](https://jakevdp.github.io/PythonDataScienceHandbook/04.01-simple-line-plots.html), [Simple Scatter Plots](https://jakevdp.github.io/PythonDataScienceHandbook/04.02-simple-scatter-plots.html), [Visualizing Errors](https://jakevdp.github.io/PythonDataScienceHandbook/04.03-errorbars.html), [Density and Contour Plots](https://jakevdp.github.io/PythonDataScienceHandbook/04.04-density-and-contour-plots.html), [Histograms, Binnings, and Density](https://jakevdp.github.io/PythonDataScienceHandbook/04.05-histograms-and-binnings.html)
  - [Sklearn API](https://jakevdp.github.io/PythonDataScienceHandbook/05.02-introducing-scikit-learn.html)

- Machine Learning Experience:
  - Loss functions
  - Overfitting and regularization
  - Regression and classification

You can also use, [MLPrep](https://github.com/univai-mlcfb-c1) and [PyPrep](https://github.com/univai-pyprep-c1) provided by Univ.AI to learn the topics mentioned above. 

In addition to this, you can use the book - [Introduction to Statistical Learning](https://faculty.marshall.usc.edu/gareth-james/ISL/ISLR Seventh Printing.pdf) to refresh the basic mathematical concepts and [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/) to refresh machine learning concepts.

## Diversity & Inclusion

We actively seek and welcome people of diverse identities, from across the spectrum of disciplines and methods since Artificial Intelligence (AI) increasingly mediates our social, cultural, economic, and political interactions [1].

We believe in creating and maintaining an inclusive learning environment where all members feel safe, respected, and capable of producing their best work.

We commit to an experience for all participants that is free from – Harassment, bullying, and discrimination which includes but is not limited to:

- Offensive comments related to age, race, religion, creed, color, gender (including transgender/gender identity/gender expression), sexual orientation, medical condition, physical or intellectual disability, pregnancy, or medical conditions, national origin or ancestry.
- Intimidation, personal attacks, harassment, unnecessary disruption of talks during any of the learning activities.

Reference:

[1] K. Stathoulopoulos and J. C. Mateos-Garcia, “Gender Diversity in AI Research,” SSRN Electronic Journal, 2019 [Online]. Available: http://dx.doi.org/10.2139/ssrn.3428240.

## Logistics - What you need to begin?

We assume you have a [Univ.AI](https://courses.univ.ai) account, created when you signed up at [courses.univ.ai](https://courses.univ.ai). 
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

- [Cohort 1](/catalog/cohort1/ds1/)
- [Cohort 2](/catalog/cohort2/ds1/)


